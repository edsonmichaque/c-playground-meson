project('main', 'c')
src_files = [
    'src/main.c',
]

lib_files = [
    'src/hello_world.c',
]

incdir = include_directories('src/include')

lib = library('hello_world', lib_files, version: '0.1.0')
executable('main', src_files, link_with: lib, include_directories : incdir)
