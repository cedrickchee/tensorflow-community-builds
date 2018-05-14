# Tensorflow Community Builds

This repo is a place to upload TensorFlow prebuilt binary from source.

## How to build TensorFlow sources into a TensorFlow binary

See this official [guide](https://www.tensorflow.org/install/install_sources) from TensorFlow team.

## Catalogue of Binaries (Python Wheels)

| Path | Compiler | CUDA/cuDNN | SIMD | Compute Capability | Notes |
|-|-|-|-|-|-|
| 1.8.0/py36/GPU/cuda91_cudnn71_avx2_fma_sse4 | GCC 5.4.0 | 9.1.85.3/7.1.3 | x86_64 | 3.7 | Python 3.6. Compiler optimization flags: -march=native. jemalloc enabled. No XLA, OpenCL, MPI support. NCCL 1.3.4. CXX flag: D_GLIBCXX_USE_CXX11_ABI=0 |
