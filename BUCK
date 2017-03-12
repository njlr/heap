include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-heap',
  header_only = True,
  header_namespace = 'boost/heap',
  exported_headers = subdir_glob([
    ('include/boost/heap', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
