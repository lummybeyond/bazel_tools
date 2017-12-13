cc_binary(
    name = "main",
    srcs = ["main.cc"],
    copts = [
        "-O2",
    ],
    deps = [
        "@com_github_glog_glog//:glog",
    ],
    linkopts = [
        "-pthread",
    ],
    visibility = ["//visibility:public"],
)
