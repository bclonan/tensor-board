# Description:
#   urllib3, another url library

load("@rules_python//python:py_library.bzl", "py_library")

package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # MIT

exports_files(["LICENSE.md"])

py_library(
    name = "org_pythonhosted_urllib3",
    srcs = glob(["urllib3/**/*.py"]),
    srcs_version = "PY3",
)
