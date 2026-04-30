# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/quantization/awq_kernels.py

Prompts

```
['build a python module to instantiate AWQAscendLinearKernel with a quantization config for NPU linear layer inference', 'process AWQ quantized linear layer weights after loading by repacking qweights and converting qzeros to NPU layout', 'apply the AWQAscendLinearKernel forward pass using npu_weight_quant_batchmatmul on a quantized linear layer with optional bias', 'build a python module to instantiate AWQAscendMoEKernel with a quantization config for NPU mixture-of-experts inference', 'process AWQ quantized MoE layer weights after loading by converting w13 and w2 qweights and qzeros to NPU layout', 'run fused MoE inference with W4A4 quantization on NPU using grouped matmul and dynamic quant', 'run fused MoE inference on NPU with W8A8 or W4A16 quantization and configurable routing', 'run W8A8 fused MoE inference on NPU optimized for decode phase with token unpermute', 'run unquantized fused MoE on NPU with configurable activation function (silu or gelu)', 'create NPU W4A4 int4 dynamic MoE method with weight packing and scale conversion for quantized inference', 'create NPU W8A8 int8 linear method class for quantized matrix multiplication on NPU hardware', 'create NPU W8A8 int8 dynamic linear method class with dynamic quantization support for NPU', 'create NPU W4A4 dynamic linear method class with int4 weight packing for NPU', 'apply NPU W8A8 int8 linear method to quantize input tensor and perform matmul with bias', 'process weights after loading for NPU W8A8 int8 linear method by transposing and format casting']
```

Usage

```
{'build_linear_kernel': 'build a python module to instantiate AWQAscendLinearKernel with a quantization config for NPU linear layer inference', 'process_linear_weights': 'process AWQ quantized linear layer weights after loading by repacking qweights and converting qzeros to NPU layout', 'apply_linear_forward': 'apply the AWQAscendLinearKernel forward pass using npu_weight_quant_batchmatmul on a quantized linear layer with optional bias', 'build_moe_kernel': 'build a python module to instantiate AWQAscendMoEKernel with a quantization config for NPU mixture-of-experts inference', 'process_moe_weights': 'process AWQ quantized MoE layer weights after loading by converting w13 and w2 qweights and qzeros to NPU layout'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/quantization/fused_moe_method_npu.py

Prompts

```
['build a python module to instantiate AWQAscendLinearKernel with a quantization config for NPU linear layer inference', 'process AWQ quantized linear layer weights after loading by repacking qweights and converting qzeros to NPU layout', 'apply the AWQAscendLinearKernel forward pass using npu_weight_quant_batchmatmul on a quantized linear layer with optional bias', 'build a python module to instantiate AWQAscendMoEKernel with a quantization config for NPU mixture-of-experts inference', 'process AWQ quantized MoE layer weights after loading by converting w13 and w2 qweights and qzeros to NPU layout', 'run fused MoE inference with W4A4 quantization on NPU using grouped matmul and dynamic quant', 'run fused MoE inference on NPU with W8A8 or W4A16 quantization and configurable routing', 'run W8A8 fused MoE inference on NPU optimized for decode phase with token unpermute', 'run unquantized fused MoE on NPU with configurable activation function (silu or gelu)', 'create NPU W4A4 int4 dynamic MoE method with weight packing and scale conversion for quantized inference', 'create NPU W8A8 int8 linear method class for quantized matrix multiplication on NPU hardware', 'create NPU W8A8 int8 dynamic linear method class with dynamic quantization support for NPU', 'create NPU W4A4 dynamic linear method class with int4 weight packing for NPU', 'apply NPU W8A8 int8 linear method to quantize input tensor and perform matmul with bias', 'process weights after loading for NPU W8A8 int8 linear method by transposing and format casting']
```

Usage

```
{'run_npu_fused_experts_w4a4': 'run fused MoE inference with W4A4 quantization on NPU using grouped matmul and dynamic quant', 'run_npu_fused_experts': 'run fused MoE inference on NPU with W8A8 or W4A16 quantization and configurable routing', 'run_npu_fused_experts_w8a8_decode': 'run W8A8 fused MoE inference on NPU optimized for decode phase with token unpermute', 'run_fused_moe_npu': 'run unquantized fused MoE on NPU with configurable activation function (silu or gelu)', 'create_npu_w4a4_int4_dynamic_moe_method': 'create NPU W4A4 int4 dynamic MoE method with weight packing and scale conversion for quantized inference'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/quantization/linear_method_npu.py

Prompts

```
['build a python module to instantiate AWQAscendLinearKernel with a quantization config for NPU linear layer inference', 'process AWQ quantized linear layer weights after loading by repacking qweights and converting qzeros to NPU layout', 'apply the AWQAscendLinearKernel forward pass using npu_weight_quant_batchmatmul on a quantized linear layer with optional bias', 'build a python module to instantiate AWQAscendMoEKernel with a quantization config for NPU mixture-of-experts inference', 'process AWQ quantized MoE layer weights after loading by converting w13 and w2 qweights and qzeros to NPU layout', 'run fused MoE inference with W4A4 quantization on NPU using grouped matmul and dynamic quant', 'run fused MoE inference on NPU with W8A8 or W4A16 quantization and configurable routing', 'run W8A8 fused MoE inference on NPU optimized for decode phase with token unpermute', 'run unquantized fused MoE on NPU with configurable activation function (silu or gelu)', 'create NPU W4A4 int4 dynamic MoE method with weight packing and scale conversion for quantized inference', 'create NPU W8A8 int8 linear method class for quantized matrix multiplication on NPU hardware', 'create NPU W8A8 int8 dynamic linear method class with dynamic quantization support for NPU', 'create NPU W4A4 dynamic linear method class with int4 weight packing for NPU', 'apply NPU W8A8 int8 linear method to quantize input tensor and perform matmul with bias', 'process weights after loading for NPU W8A8 int8 linear method by transposing and format casting']
```

Usage

```
{'create_NPUW8A8Int8LinearMethod': 'create NPU W8A8 int8 linear method class for quantized matrix multiplication on NPU hardware', 'create_NPUW8A8Int8DynamicLinearMethod': 'create NPU W8A8 int8 dynamic linear method class with dynamic quantization support for NPU', 'create_NPU_W4A4DynamicLinearMethod': 'create NPU W4A4 dynamic linear method class with int4 weight packing for NPU', 'apply_NPUW8A8Int8LinearMethod': 'apply NPU W8A8 int8 linear method to quantize input tensor and perform matmul with bias', 'process_weights_after_loading_NPUW8A8Int8LinearMethod': 'process weights after loading for NPU W8A8 int8 linear method by transposing and format casting'}
```

