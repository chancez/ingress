package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "authentication_client.go",
        "doc.go",
        "generated_expansion.go",
        "tokenreview.go",
        "tokenreview_expansion.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/scheme:go_default_library",
        "//vendor/k8s.io/client-go/pkg/apis/authentication/v1:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
    ],
)
