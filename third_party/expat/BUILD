# Copyright 2016 The Bazel Authors. All rights reserved.
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

package(default_visibility = ["//visibility:public"])

load("//closure/private:deb_extract.bzl", "deb_extract")

licenses(["notice"])  # MIT-style

deb_extract(
    name = "libexpat_k8",
    src = "@libexpat_amd64_deb//file",
    outs = {"lib/x86_64-linux-gnu/libexpat.so.1.6.0": "k8/libexpat.so.1"},
)
