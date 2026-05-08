# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/cuda/cuda_tensor.py

Prompts

```
['create a CUDALongTensor wrapper from a torch tensor or array-like object on a CUDA device', 'perform matrix multiplication on CUDALongTensor by encoding to fp64 and decoding results back to int64', 'run conv1d, conv2d, conv_transpose1d, or conv_transpose2d on CUDALongTensor using fp64 block encoding', 'apply avg_pool2d on a CUDALongTensor with fp64 encoding and integer division rounding', 'register a custom torch function override for CUDALongTensor using the implements decorator']
```

Usage

```
{'create_CUDALongTensor': 'create a CUDALongTensor wrapper from a torch tensor or array-like object on a CUDA device', 'matmul_CUDALongTensor': 'perform matrix multiplication on CUDALongTensor by encoding to fp64 and decoding results back to int64', 'conv_CUDALongTensor': 'run conv1d, conv2d, conv_transpose1d, or conv_transpose2d on CUDALongTensor using fp64 block encoding', 'avg_pool_CUDALongTensor': 'apply avg_pool2d on a CUDALongTensor with fp64 encoding and integer division rounding', 'implements_decorator': 'register a custom torch function override for CUDALongTensor using the implements decorator'}
```

