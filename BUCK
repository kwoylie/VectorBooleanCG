fb_apple_library(
    name = "VectorBooleanCG",
    srcs = glob([
        "Shared/*.m",
        "Shared/*.c",
    ]),
    exported_headers = glob([
        "Shared/*.h",
    ]),
    compiler_flags = ["-Wno-implicit-retain-self"],
    frameworks = [
        "$SDKROOT/System/Library/Frameworks/CoreGraphics.framework",
        "$SDKROOT/System/Library/Frameworks/Foundation.framework",
        "$SDKROOT/System/Library/Frameworks/QuartzCore.framework",
    ],
    ios_frameworks = [
        "$SDKROOT/System/Library/Frameworks/UIKit.framework",
    ],

    macosx_frameworks = [
        "$SDKROOT/System/Library/Frameworks/AppKit.framework",
        "$SDKROOT/System/Library/Frameworks/ApplicationServices.framework",
    ],
    sdks = (IOS, MACOSX),
    preprocessor_flags = OBJC_ARC_PREPROCESSOR_FLAGS + DEBUG_PREPROCESSOR_FLAGS,
    visibility = ["PUBLIC"],
    deps = [],
)
