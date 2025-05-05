load("@rules_rust//rust:defs.bzl", "rust_doc", "rust_library")

rust_library(
    name = "posix-errno",
    srcs = ["posix-errno.rs"],
    edition = "2015",
    visibility = ["//visibility:public"],
)

rust_doc(
    name = "posix-errno_doc",
    crate = ":posix-errno",
)
