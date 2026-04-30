# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/jit_kernel/diffusion/cutedsl/common/norm_fusion.py

Prompts

```
['build a CTA-level kernel dispatcher that applies RMSNorm or LayerNorm to a tensor fragment', 'create a CTA-level RMS normalization kernel that computes y[i] = x[i] / sqrt(sum(x^2)/D + eps) * w[i]', 'create a CTA-level Layer normalization kernel that computes mean, variance, and normalizes with optional weight and bias', 'build a function that broadcasts a tensor to (B, S, D) shape without memory copy for BSFD-compatible indexing', 'create a function that slices a BSFD-compatible tensor into per-thread gmem tile and rmem fragment for a given batch and seq id', 'run the warp_reduce_sum function to perform a warp-level reduction sum using shuffle_sync_down operations', 'run the cta_reduce_sum function to perform a CTA-level reduction sum using shared memory across multiple warps', 'build a CUDA kernel using warp_reduce_sum for warp-level parallel reduction of numeric values', 'build a CUDA kernel using cta_reduce_sum for block-level parallel reduction across warps with shared memory', 'test the warp_reduce_sum and cta_reduce_sum functions for correctness in GPU reduction operations']
```

Usage

```
{'build_apply_norm_cta': 'build a CTA-level kernel dispatcher that applies RMSNorm or LayerNorm to a tensor fragment', 'create_apply_rmsnorm_cta': 'create a CTA-level RMS normalization kernel that computes y[i] = x[i] / sqrt(sum(x^2)/D + eps) * w[i]', 'create_apply_layernorm_cta': 'create a CTA-level Layer normalization kernel that computes mean, variance, and normalizes with optional weight and bias', 'build_broadcast_tensor_for_bsfd': 'build a function that broadcasts a tensor to (B, S, D) shape without memory copy for BSFD-compatible indexing', 'create_tensor_slice_for_bsfd': 'create a function that slices a BSFD-compatible tensor into per-thread gmem tile and rmem fragment for a given batch and seq id'}
```

## File: sgl-project_sglang/python/sglang/jit_kernel/diffusion/cutedsl/common/reduce.py

Prompts

```
['build a CTA-level kernel dispatcher that applies RMSNorm or LayerNorm to a tensor fragment', 'create a CTA-level RMS normalization kernel that computes y[i] = x[i] / sqrt(sum(x^2)/D + eps) * w[i]', 'create a CTA-level Layer normalization kernel that computes mean, variance, and normalizes with optional weight and bias', 'build a function that broadcasts a tensor to (B, S, D) shape without memory copy for BSFD-compatible indexing', 'create a function that slices a BSFD-compatible tensor into per-thread gmem tile and rmem fragment for a given batch and seq id', 'run the warp_reduce_sum function to perform a warp-level reduction sum using shuffle_sync_down operations', 'run the cta_reduce_sum function to perform a CTA-level reduction sum using shared memory across multiple warps', 'build a CUDA kernel using warp_reduce_sum for warp-level parallel reduction of numeric values', 'build a CUDA kernel using cta_reduce_sum for block-level parallel reduction across warps with shared memory', 'test the warp_reduce_sum and cta_reduce_sum functions for correctness in GPU reduction operations']
```

Usage

```
{'run_warp_reduce_sum': 'run the warp_reduce_sum function to perform a warp-level reduction sum using shuffle_sync_down operations', 'run_cta_reduce_sum': 'run the cta_reduce_sum function to perform a CTA-level reduction sum using shared memory across multiple warps', 'build_warp_reduce_kernel': 'build a CUDA kernel using warp_reduce_sum for warp-level parallel reduction of numeric values', 'build_cta_reduce_kernel': 'build a CUDA kernel using cta_reduce_sum for block-level parallel reduction across warps with shared memory', 'test_reduce_functions': 'test the warp_reduce_sum and cta_reduce_sum functions for correctness in GPU reduction operations'}
```

