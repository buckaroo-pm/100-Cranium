cxx_library(
  name = "cranium",
  header_namespace = '',
  exported_headers = glob(["src/*.h"]),
  srcs = [],
  visibility = ["PUBLIC"]
)

cxx_binary(
  name = "optimizer_test",
  srcs = ["tests/optimizer_tests.c"],
  deps = [":cranium"]
)
