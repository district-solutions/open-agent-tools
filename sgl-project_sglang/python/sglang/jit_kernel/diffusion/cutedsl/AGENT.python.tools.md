# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/jit_kernel/diffusion/cutedsl/norm_tanh_mul_add_norm_scale.py

Prompts

```
['create a fused norm tanh mul add operation with layer norm or rms norm on a 3D tensor', 'create a double fused norm tanh mul add with norm scale on two output tensors', 'build a CuTeDSL JIT kernel class for fused normalization and tanh scaling operations', 'test a 3D tensor for supported dtype, shape, and contiguous dimension constraints', 'test a weight or bias tensor for supported dtype and shape constraints', 'build a torch custom op that fuses norm(x) * (1 + scale) + shift with layer or rms norm', 'build a torch custom op that fuses norm(residual + gate * x) * (1 + scale) + shift with layer or rms norm', 'test the validate_x function checks dtype, shape, and stride of a tensor', 'test the validate_scale_shift function checks dtype, shape, and stride for scale/shift tensors', 'build a CuTeDSL GPU kernel class that performs scale residual norm scale shift with compile-time caching']
```

Usage

```
{'create_fused_norm_tanh_mul_add': 'create a fused norm tanh mul add operation with layer norm or rms norm on a 3D tensor', 'create_fused_norm_tanh_mul_add_norm_scale': 'create a double fused norm tanh mul add with norm scale on two output tensors', 'build_norm_tanh_kernel': 'build a CuTeDSL JIT kernel class for fused normalization and tanh scaling operations', 'test_validate_3d': 'test a 3D tensor for supported dtype, shape, and contiguous dimension constraints', 'test_validate_weight_bias': 'test a weight or bias tensor for supported dtype and shape constraints'}
```

## File: sgl-project_sglang/python/sglang/jit_kernel/diffusion/cutedsl/scale_residual_norm_scale_shift.py

Prompts

```
['create a fused norm tanh mul add operation with layer norm or rms norm on a 3D tensor', 'create a double fused norm tanh mul add with norm scale on two output tensors', 'build a CuTeDSL JIT kernel class for fused normalization and tanh scaling operations', 'test a 3D tensor for supported dtype, shape, and contiguous dimension constraints', 'test a weight or bias tensor for supported dtype and shape constraints', 'build a torch custom op that fuses norm(x) * (1 + scale) + shift with layer or rms norm', 'build a torch custom op that fuses norm(residual + gate * x) * (1 + scale) + shift with layer or rms norm', 'test the validate_x function checks dtype, shape, and stride of a tensor', 'test the validate_scale_shift function checks dtype, shape, and stride for scale/shift tensors', 'build a CuTeDSL GPU kernel class that performs scale residual norm scale shift with compile-time caching']
```

Usage

```
{'build_fused_norm_scale_shift': 'build a torch custom op that fuses norm(x) * (1 + scale) + shift with layer or rms norm', 'build_fused_scale_residual_norm_scale_shift': 'build a torch custom op that fuses norm(residual + gate * x) * (1 + scale) + shift with layer or rms norm', 'test_validate_x': 'test the validate_x function checks dtype, shape, and stride of a tensor', 'test_validate_scale_shift': 'test the validate_scale_shift function checks dtype, shape, and stride for scale/shift tensors', 'build_ScaleResidualNormScaleShift': 'build a CuTeDSL GPU kernel class that performs scale residual norm scale shift with compile-time caching'}
```

