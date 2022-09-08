# POSIX error numbers for Rust

This library defines a single type, the `Error` enum, which represents the
symbolic constants for error numbers defined in the POSIX standard.

To depend on `posix-errno` from a Bazel workspace:

```python
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rust_posix_errno",
    # Obtain the package checksum from the release page:
    # https://github.com/jmillikin/rust-posix-errno/releases/tag/v1.0.1
    sha256 = "",
    strip_prefix = "posix-errno-1.0.1",
    urls = ["https://github.com/jmillikin/rust-posix-errno/releases/download/v1.0.1/posix-errno-1.0.1.tar.xz"],
)
```

To depend on `posix-errno` from a Cargo workspace:

```
[dependencies]
posix-errno = { version = "1.0.1" }
```
