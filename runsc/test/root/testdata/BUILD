load("@io_bazel_rules_go//go:def.bzl", "go_library")

package(licenses = ["notice"])

go_library(
    name = "testdata",
    srcs = [
        "busybox.go",
        "containerd_config.go",
        "httpd.go",
        "httpd_mount_paths.go",
        "sandbox.go",
    ],
    importpath = "gvisor.googlesource.com/gvisor/runsc/test/root/testdata",
    visibility = [
        "//visibility:public",
    ],
)
