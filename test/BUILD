cc_library(
    name = "TritonTestAnalysis",
    srcs = glob(["lib/Analysis/*.cpp"]),
    deps = [
        "@llvm-project//mlir:Analysis",
        "@llvm-project//mlir:GPUDialect",
        "@llvm-project//mlir:IR",
        "@llvm-project//mlir:Pass",
        "@llvm-project//mlir:SCFToControlFlow",
        "@llvm-project//mlir:Transforms",
        "//:TritonAnalysis",
        "//:TritonGPUDialect",
    ],
    visibility = ["//visibility:public"],
)
