package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

go_library(
    name = "go_default_library",
    srcs = ["treecache.go"],
    tags = ["automanaged"],
    deps = ["//vendor:github.com/skynetservices/skydns/msg"],
)

go_test(
    name = "go_default_test",
    srcs = ["treecache_test.go"],
    library = "go_default_library",
    tags = ["automanaged"],
    deps = ["//vendor:github.com/skynetservices/skydns/msg"],
)
