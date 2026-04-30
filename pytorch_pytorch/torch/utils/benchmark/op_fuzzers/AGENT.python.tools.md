# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/utils/benchmark/op_fuzzers/spectral.py

Prompts

```
['create a SpectralOpFuzzer instance with a seed and optional dtype, cuda, and probability_regular parameters', 'test spectral operations with regular FFT-friendly sizes from REGULAR_SIZES for optimal performance', 'test spectral operations with random dimension sizes between MIN_DIM_SIZE and MAX_DIM_SIZE', 'test spectral operations with varying memory strides to benchmark strided memory access patterns', 'test spectral operations across 1D, 2D, and 3D tensor configurations with configurable dimensionality']
```

Usage

```
{'create_SpectralOpFuzzer': 'create a SpectralOpFuzzer instance with a seed and optional dtype, cuda, and probability_regular parameters', 'test_spectral_fft_sizes': 'test spectral operations with regular FFT-friendly sizes from REGULAR_SIZES for optimal performance', 'test_spectral_random_sizes': 'test spectral operations with random dimension sizes between MIN_DIM_SIZE and MAX_DIM_SIZE', 'test_spectral_strided_access': 'test spectral operations with varying memory strides to benchmark strided memory access patterns', 'test_spectral_multidimensional': 'test spectral operations across 1D, 2D, and 3D tensor configurations with configurable dimensionality'}
```

