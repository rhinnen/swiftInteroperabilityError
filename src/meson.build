main = files('main.cpp')
swiftLib = static_library('module', 'module.swift')

src_files += files()

executable(
    meson.project_name(),
    main,
    include_directories: inc_dirs,
    link_with: swiftLib,
    install : true
)
