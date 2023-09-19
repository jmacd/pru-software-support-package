package(default_visibility = ["//visibility:public"])

cc_library(
    name = "include",
    hdrs = glob(["*.h"]),
    srcs = [],
    copts = ["-I$(WORKSPACE_ROOT)/include"],
    strip_include_prefix = "include",
)
