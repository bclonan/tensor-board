# Description:
#   Markdown processor

load("@rules_python//python:py_library.bzl", "py_library")

package(default_visibility = ["//visibility:public"])

# This software says they use a BSD license.
licenses(["notice"])

exports_files(["LICENSE.md"])

py_library(
    name = "org_pythonhosted_markdown",
    srcs = glob(["markdown/**/*.py"]),
    srcs_version = "PY3",
)
