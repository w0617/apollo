## Auto generated by `proto_build_generator.py`
load("@rules_proto//proto:defs.bzl", "proto_library")
load("@rules_cc//cc:defs.bzl", "cc_proto_library")
load("//tools:python_rules.bzl", "py_proto_library")

package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "audio_cc_proto",
    deps = [
        ":audio_proto",
    ],
)

proto_library(
    name = "audio_proto",
    srcs = ["audio.proto"],
)

py_proto_library(
    name = "audio_py_pb2",
    deps = [
        ":audio_proto",
    ],
)

cc_proto_library(
    name = "audio_conf_cc_proto",
    deps = [
        ":audio_conf_proto",
    ],
)

proto_library(
    name = "audio_conf_proto",
    srcs = ["audio_conf.proto"],
)

py_proto_library(
    name = "audio_conf_py_pb2",
    deps = [
        ":audio_conf_proto",
    ],
)
