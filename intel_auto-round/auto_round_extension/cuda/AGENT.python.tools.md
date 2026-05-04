# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/cuda/gptqmodel_marlin.py

Prompts

```
['get the MarlinQuantLinear class from gptqmodel for CUDA quantized linear layer inference', 'create a MarlinQuantLinear layer with 4-bit quantization, group size 128, and specified input and output features', 'apply the GPTQ Marlin GEMM kernel to perform quantized matrix multiplication on CUDA tensors', 'repack quantized weights from autogptq format to marlin format using gptq_marlin_repack kernel', 'dequantize the packed qzeros tensor of a MarlinQuantLinear layer and repeat by group size']
```

Usage

```
{'get_marlin_layer': 'get the MarlinQuantLinear class from gptqmodel for CUDA quantized linear layer inference', 'create_marlin_quant_linear': 'create a MarlinQuantLinear layer with 4-bit quantization, group size 128, and specified input and output features', 'apply_gptq_marlin_linear': 'apply the GPTQ Marlin GEMM kernel to perform quantized matrix multiplication on CUDA tensors', 'repack_marlin_weights': 'repack quantized weights from autogptq format to marlin format using gptq_marlin_repack kernel', 'dequantize_qzeros': 'dequantize the packed qzeros tensor of a MarlinQuantLinear layer and repeat by group size'}
```

