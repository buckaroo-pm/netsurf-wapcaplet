load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'wapcaplet',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.c',
  ]),
  visibility = [
    'PUBLIC',
  ],
)
