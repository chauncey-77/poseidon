load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["charset.go"],
    importmap = "github.com/kubernetes-sigs/poseidon/vendor/golang.org/x/net/html/charset",
    importpath = "golang.org/x/net/html/charset",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/net/html:go_default_library",
        "//vendor/golang.org/x/text/encoding:go_default_library",
        "//vendor/golang.org/x/text/encoding/charmap:go_default_library",
        "//vendor/golang.org/x/text/encoding/htmlindex:go_default_library",
        "//vendor/golang.org/x/text/transform:go_default_library",
    ],
)
