# gtest
new_git_repository(
    name = "googletest",
    build_file = "//bazel:gmock.BUILD",
    #build_file = "gmock.BUILD",
    remote = "https://github.com/google/googletest",
    tag = "release-1.8.0",
)

# glog
git_repository(
    name   = "com_github_gflags_gflags",
    commit = "f8a0efe03aa69b3336d8e228b37d4ccb17324b88",
    remote = "https://github.com/gflags/gflags.git",
)

new_git_repository(
    name   = "com_github_glog_glog",
    #build_file = "glog.BUILD",
    build_file = "//bazel:glog.BUILD",
    remote = "https://github.com/google/glog.git",
    tag = "v0.3.5",
)
