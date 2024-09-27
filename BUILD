load("@rules_python//python:defs.bzl", "py_library", "py_binary")

py_library(
    name = "mdadm_py",
    srcs = ["mdadm.py"],
    visibility = ["//visibility:public"],
)

py_binary(
    name = "mdadm_main",
    srcs = ["mdadm.py"],
    deps = [":mdadm_py"],
    main = "mdadm.py",
)
