load("@rules_rust//rust:defs.bzl", "rust_doc", "rust_library")

package(default_visibility = ["//visibility:public"])

rust_library(
    name = "posix-errno",
    srcs = ["posix-errno.rs"],
)

rust_doc(
    name = "posix-errno_doc",
    crate = ":posix-errno",
)
