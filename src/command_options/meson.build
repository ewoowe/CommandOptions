libcmdopts_sources = files('''
    command-options.c
'''.split())

libcmdopts = static_library('cmdopts',
    sources : libcmdopts_sources,
    dependencies : [],
    install : false)

libcmdopts_dep = declare_dependency(
    link_with : libcmdopts,
    dependencies : [])



