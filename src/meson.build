project('command-options', 'c', 'cpp',
        version : '0.1',
        meson_version : '>= 0.43.0',
        default_options : [
            'warning_level=1',
            'c_std=gnu89',
        ],
)

subdir('command_options')

executable('testcmdopts',
    sources : 'main.c',
    dependencies : libcmdopts_dep,
    install : true
)