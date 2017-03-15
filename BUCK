include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'websocketpp',
  header_only = True,
  header_namespace = 'websocketpp',
  exported_headers = subdir_glob([
    ('websocketpp', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
