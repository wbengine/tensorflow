licenses(["notice"])  # Apache 2.0

package(default_visibility = ["//visibility:private"])

py_binary(
    name = "generate_v2_renames_map",
    srcs = ["generate_v2_renames_map.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/python:lib",
        "//tensorflow/python:no_contrib",
        "//tensorflow/tools/common:public_api",
        "//tensorflow/tools/common:traverse",
        "//tensorflow/tools/compatibility:tf_upgrade_v2_lib",
    ],
)

py_binary(
    name = "generate_v2_reorders_map",
    srcs = ["generate_v2_reorders_map.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow:tensorflow_py",
        "//tensorflow/python:lib",
        "//tensorflow/python:no_contrib",
        "//tensorflow/tools/common:public_api",
        "//tensorflow/tools/common:traverse",
        "//tensorflow/tools/compatibility:tf_upgrade_v2_lib",
    ],
)
