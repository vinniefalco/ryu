package(default_visibility=["//visibility:public"])

cc_library(
  name = "ryu",
  srcs = [
    "f2s.c",
    "d2s.c",
    "d2s.h",
    "d2s_full_table.h",
    "d2s_intrinsics.h",
    "digit_table.h",
    "common.h",
  ],
  hdrs = ["ryu.h"],
)

cc_library(
  name = "generic_128",
  srcs = [
    "generic_128.c",
    "generic_128.h",
  ],
  hdrs = [
    "ryu_generic_128.h",
  ],
  # The code does not compile on Windows.
  tags = ["nowindows"],
)

cc_library(
  name = "d2s_intrinsics",
  hdrs = [
    "common.h",
    "d2s_intrinsics.h",
  ],
)

cc_library(
  name = "ryu_printf",
  srcs = [
    "d2fixed.c",
#    "d2fixed.h",
    "d2s_intrinsics.h",
    "d2fixed_full_table.h",
    "digit_table.h",
    "common.h",
  ],
  hdrs = ["ryu2.h"],
)
