"""
Copyright (c) 2019, NVIDIA CORPORATION. All rights reserved.

NVIDIA CORPORATION and its licensors retain all intellectual property
and proprietary rights in and to this software, related documentation
and any modifications thereto. Any use, reproduction, disclosure or
distribution of this software and related documentation without an express
license agreement from NVIDIA CORPORATION is strictly prohibited.
"""

load("@com_nvidia_isaac_sdk//bzl:module.bzl", "isaac_cc_module", "isaac_component")

isaac_component(
    name = "ae400_camera_comp",
    deps = [
        "@com_nvidia_isaac_engine//engine/gems/geometry:pinhole",
        "@ae400_realsense_sdk",
    ],
)

isaac_cc_module(
    name = "ae400",
    deps = [
        "ae400_camera_comp",
    ],
)
