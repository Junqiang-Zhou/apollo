load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "sequence_predictor",
    srcs = ["sequence_predictor.cc"],
    hdrs = ["sequence_predictor.h"],
    deps = [
        "//modules/common:log",
        "//modules/common/adapters/proto:adapter_config_proto",
        "//modules/prediction/common:prediction_map",
        "//modules/prediction/common:road_graph",
        "//modules/prediction/common:prediction_gflags",
        "//modules/prediction/predictor:predictor",
        "//modules/prediction/container:container_manager",
        "//modules/prediction/container/obstacles:obstacles_container",
        "//modules/prediction/container/pose:pose_container",
        "//modules/prediction/proto:lane_graph_proto",
        "@eigen//:eigen",
    ]
)

cpplint()