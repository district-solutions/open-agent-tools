# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/gpu/quantization/awq_kernels.py

Prompts

```
['apply the AWQLinearKernel to dequantize weights and compute a matmul forward pass on a layer', 'apply the AWQMarlinLinearKernel to run a forward pass using repacked Marlin format weights', 'apply the AWQMoEKernel to run a mixture of experts forward pass with Marlin quantized weights', 'process AWQ linear layer weights after loading by freezing qweight, qzeros, and scales parameters', 'process AWQ MoE weights after loading by repacking w13 and w2 weights into Marlin format']
```

Usage

```
{'apply_awq_linear_kernel': 'apply the AWQLinearKernel to dequantize weights and compute a matmul forward pass on a layer', 'apply_awq_marlin_linear_kernel': 'apply the AWQMarlinLinearKernel to run a forward pass using repacked Marlin format weights', 'apply_awq_moe_kernel': 'apply the AWQMoEKernel to run a mixture of experts forward pass with Marlin quantized weights', 'process_awq_linear_weights': 'process AWQ linear layer weights after loading by freezing qweight, qzeros, and scales parameters', 'process_awq_marlin_moe_weights': 'process AWQ MoE weights after loading by repacking w13 and w2 weights into Marlin format'}
```

