# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/layers/awq/quantize/cuda.py

Prompts

```
['create a WQLinear module with 4-bit quantized weights, zeros, scales, and optional bias', 'run the WQLinear forward pass to perform quantized matrix multiplication using CUDA GEMM kernels', 'test WQLinear initialization with 4-bit quantized weights and group size alignment', 'refactor WQLinear to support additional bit widths beyond the current 4-bit limitation', 'review WQLinear forward method that calls awq_inference_engine.gemm_forward_cuda for quantized inference', 'create a WQLinear 4-bit quantized linear layer using IPEX with AWQ_GEMM quantization method', 'run the WQLinear forward pass on an input tensor with INT4 weight-only quantization', 'review the WQLinear class initialization that validates 4-bit quantization and group size alignment', 'refactor the WQLinear forward method to handle different input tensor shapes and output reshaping', 'test the WQLinear layer with IPEX weight-only quantized linear using AWQ_GEMM quant method']
```

Usage

```
{'create_WQLinear_module': 'create a WQLinear module with 4-bit quantized weights, zeros, scales, and optional bias', 'run_WQLinear_forward': 'run the WQLinear forward pass to perform quantized matrix multiplication using CUDA GEMM kernels', 'test_WQLinear_initialization': 'test WQLinear initialization with 4-bit quantized weights and group size alignment', 'refactor_WQLinear_quantization': 'refactor WQLinear to support additional bit widths beyond the current 4-bit limitation', 'review_WQLinear_cuda_kernel': 'review WQLinear forward method that calls awq_inference_engine.gemm_forward_cuda for quantized inference'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/awq/quantize/ipex.py

Prompts

```
['create a WQLinear module with 4-bit quantized weights, zeros, scales, and optional bias', 'run the WQLinear forward pass to perform quantized matrix multiplication using CUDA GEMM kernels', 'test WQLinear initialization with 4-bit quantized weights and group size alignment', 'refactor WQLinear to support additional bit widths beyond the current 4-bit limitation', 'review WQLinear forward method that calls awq_inference_engine.gemm_forward_cuda for quantized inference', 'create a WQLinear 4-bit quantized linear layer using IPEX with AWQ_GEMM quantization method', 'run the WQLinear forward pass on an input tensor with INT4 weight-only quantization', 'review the WQLinear class initialization that validates 4-bit quantization and group size alignment', 'refactor the WQLinear forward method to handle different input tensor shapes and output reshaping', 'test the WQLinear layer with IPEX weight-only quantized linear using AWQ_GEMM quant method']
```

Usage

```
{'create_wqlinear_layer': 'create a WQLinear 4-bit quantized linear layer using IPEX with AWQ_GEMM quantization method', 'run_wqlinear_forward': 'run the WQLinear forward pass on an input tensor with INT4 weight-only quantization', 'review_wqlinear_init': 'review the WQLinear class initialization that validates 4-bit quantization and group size alignment', 'refactor_wqlinear_forward': 'refactor the WQLinear forward method to handle different input tensor shapes and output reshaping', 'test_wqlinear_quantization': 'test the WQLinear layer with IPEX weight-only quantized linear using AWQ_GEMM quant method'}
```

