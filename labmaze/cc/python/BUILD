# Copyright 2019 DeepMind Technologies Limited.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ============================================================================
#
# Description:
#   Raw pybind11 bindings for LabMaze. Intended for internal usage only.
#   Please use the Python API provided directly under the LabMaze package.

load("@pybind11_bazel//:build_defs.bzl", "pybind_extension")

pybind_extension(
    name = "_defaults",
    srcs = ["_defaults.cc"],
    visibility = ["//labmaze:__subpackages__"],
    deps = ["//labmaze/cc:defaults"],
)

pybind_extension(
    name = "_random_maze",
    srcs = ["_random_maze.cc"],
    visibility = ["//labmaze:__subpackages__"],
    deps = ["//labmaze/cc:random_maze"],
)
