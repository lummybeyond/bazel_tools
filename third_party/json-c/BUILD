licenses(["notice"])

package(default_visibility = ["//visibility:public"])

include_files = glob(["include/json-c/*.h"])

cc_library(
    name = "json-c",
    srcs = [
        "lib/libjson-c.a",
    ],
    hdrs = include_files,
    includes = [
        "include/json-c",
    ],
    linkstatic = 1,
)


