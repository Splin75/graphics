#Copyright 2018 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# Differentiable Rasterizer functionalities for tf-graphics.

# google internal package dependency 8)
# google internal package dependency 5

licenses(["notice"])  # Apache 2.0

package(default_visibility = ["//visibility:public"])

py_library(
    name = "rasterizer",
    srcs = ["rasterizer.py"],
    srcs_version = "PY2AND3",
    # google internal rule 1
    deps = [
        # google internal package dependency 1,
        "//tensorflow_graphics/rendering/camera:orthographic",
        "//tensorflow_graphics/util:shape",
    ],
)

py_library(
    name = "differentiable_renderer",
    srcs = ["__init__.py"],
    srcs_version = "PY2AND3",
    # google internal rule 1
    deps = [
        ":rasterizer",
        "//tensorflow_graphics/util:export_api",
    ],
)

py_test(
    name = "rasterizer_test",
    srcs = ["tests/rasterizer_test.py"],
    srcs_version = "PY2AND3",
    # google internal rule 1
    # google internal rule 2
    # google internal rule 3
    # google internal rule 4
    # google internal rule 5
    # google internal rule 6
    deps = [
        ":rasterizer",
        # google internal package dependency 3
        # google internal package dependency 2
        # google internal package dependency 6
        # google internal package dependency 1,
        "//tensorflow_graphics/util:test_case",
    ],
)
