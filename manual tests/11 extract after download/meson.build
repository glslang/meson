project('extract', 'c')

cc = meson.get_compiler('c')

s = subproject('libpng').get_variable('png_dep')

e = executable('extract_test', 'main.c',
  dependencies : [s])
