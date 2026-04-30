# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/layers/marlin/fp8.py

Prompts

```
['create a GPTQMarlinFP8Linear layer from unquantized weights using the from_unquant class method', 'create a GPTQMarlinFP8Linear layer from existing FP8 weights and scales using the from_fp8 class method', 'run the forward pass of a GPTQMarlinFP8Linear layer on an input tensor to get quantized output', 'build a packed int32 tensor from an FP8 tensor by repacking four uint8 values into each int32 element', 'repack an FP8 weight tensor and its scales for use with the GPTQ-Marlin kernel format', 'check if GPTQ or AWQ quantized model parameters are compatible with Marlin kernels on the current CUDA device', 'repack GPTQ quantized weights into the Marlin kernel format for faster inference on CUDA', 'create a weights loader that loads GPTQ or AWQ quantized weights and repacks them for Marlin kernels', 'build a linear layer that uses repacked GPTQ Marlin weights for quantized matrix multiplication', 'convert AWQ packed zero points to the Marlin zero point format for quantized inference', 'build a MarlinWeightsLoader to load int4 quantized Marlin weights from a Weights object with a given prefix', 'build a MarlinLinear nn.Module that performs quantized GEMM using the Marlin kernel on int32-packed weights', 'build a GPTQMarlin24Linear layer that performs 2:4 sparse quantized GEMM with 4-bit or 8-bit weights', 'create a MarlinWeight dataclass holding int32-packed weights and float16 scales for Marlin quantized linear layers', 'create a GPTQMarlin24Weight dataclass holding packed weights, sparsity metadata, and scales for 2:4 sparse quantization', 'pack quantized weight tensor columns into compact uint32 format for Marlin kernel compatibility', 'unpack packed quantized weight tensor columns back to their original expanded format', 'permute a scales tensor using Marlin permutation for quantized model weight dequantization', 'permute interleave and pack zero-point tensors for Marlin quantized model inference', 'check if the current system has CUDA SM 8.0+ GPU and marlin kernels installed']
```

Usage

```
{'create_GPTQMarlinFP8Linear_from_unquant': 'create a GPTQMarlinFP8Linear layer from unquantized weights using the from_unquant class method', 'create_GPTQMarlinFP8Linear_from_fp8': 'create a GPTQMarlinFP8Linear layer from existing FP8 weights and scales using the from_fp8 class method', 'run_GPTQMarlinFP8Linear_forward': 'run the forward pass of a GPTQMarlinFP8Linear layer on an input tensor to get quantized output', 'build_pack_fp8_as_int32': 'build a packed int32 tensor from an FP8 tensor by repacking four uint8 values into each int32 element', 'repack_repack_fp8_for_marlin': 'repack an FP8 weight tensor and its scales for use with the GPTQ-Marlin kernel format'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/marlin/gptq.py

Prompts

```
['create a GPTQMarlinFP8Linear layer from unquantized weights using the from_unquant class method', 'create a GPTQMarlinFP8Linear layer from existing FP8 weights and scales using the from_fp8 class method', 'run the forward pass of a GPTQMarlinFP8Linear layer on an input tensor to get quantized output', 'build a packed int32 tensor from an FP8 tensor by repacking four uint8 values into each int32 element', 'repack an FP8 weight tensor and its scales for use with the GPTQ-Marlin kernel format', 'check if GPTQ or AWQ quantized model parameters are compatible with Marlin kernels on the current CUDA device', 'repack GPTQ quantized weights into the Marlin kernel format for faster inference on CUDA', 'create a weights loader that loads GPTQ or AWQ quantized weights and repacks them for Marlin kernels', 'build a linear layer that uses repacked GPTQ Marlin weights for quantized matrix multiplication', 'convert AWQ packed zero points to the Marlin zero point format for quantized inference', 'build a MarlinWeightsLoader to load int4 quantized Marlin weights from a Weights object with a given prefix', 'build a MarlinLinear nn.Module that performs quantized GEMM using the Marlin kernel on int32-packed weights', 'build a GPTQMarlin24Linear layer that performs 2:4 sparse quantized GEMM with 4-bit or 8-bit weights', 'create a MarlinWeight dataclass holding int32-packed weights and float16 scales for Marlin quantized linear layers', 'create a GPTQMarlin24Weight dataclass holding packed weights, sparsity metadata, and scales for 2:4 sparse quantization', 'pack quantized weight tensor columns into compact uint32 format for Marlin kernel compatibility', 'unpack packed quantized weight tensor columns back to their original expanded format', 'permute a scales tensor using Marlin permutation for quantized model weight dequantization', 'permute interleave and pack zero-point tensors for Marlin quantized model inference', 'check if the current system has CUDA SM 8.0+ GPU and marlin kernels installed']
```

Usage

```
{'check_gptq_marlin_compatibility': 'check if GPTQ or AWQ quantized model parameters are compatible with Marlin kernels on the current CUDA device', 'repack_gptq_weights_for_marlin': 'repack GPTQ quantized weights into the Marlin kernel format for faster inference on CUDA', 'create_gptq_marlin_weights_loader': 'create a weights loader that loads GPTQ or AWQ quantized weights and repacks them for Marlin kernels', 'build_gptq_marlin_linear_layer': 'build a linear layer that uses repacked GPTQ Marlin weights for quantized matrix multiplication', 'convert_awq_zero_points_to_marlin': 'convert AWQ packed zero points to the Marlin zero point format for quantized inference'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/marlin/marlin.py

Prompts

```
['create a GPTQMarlinFP8Linear layer from unquantized weights using the from_unquant class method', 'create a GPTQMarlinFP8Linear layer from existing FP8 weights and scales using the from_fp8 class method', 'run the forward pass of a GPTQMarlinFP8Linear layer on an input tensor to get quantized output', 'build a packed int32 tensor from an FP8 tensor by repacking four uint8 values into each int32 element', 'repack an FP8 weight tensor and its scales for use with the GPTQ-Marlin kernel format', 'check if GPTQ or AWQ quantized model parameters are compatible with Marlin kernels on the current CUDA device', 'repack GPTQ quantized weights into the Marlin kernel format for faster inference on CUDA', 'create a weights loader that loads GPTQ or AWQ quantized weights and repacks them for Marlin kernels', 'build a linear layer that uses repacked GPTQ Marlin weights for quantized matrix multiplication', 'convert AWQ packed zero points to the Marlin zero point format for quantized inference', 'build a MarlinWeightsLoader to load int4 quantized Marlin weights from a Weights object with a given prefix', 'build a MarlinLinear nn.Module that performs quantized GEMM using the Marlin kernel on int32-packed weights', 'build a GPTQMarlin24Linear layer that performs 2:4 sparse quantized GEMM with 4-bit or 8-bit weights', 'create a MarlinWeight dataclass holding int32-packed weights and float16 scales for Marlin quantized linear layers', 'create a GPTQMarlin24Weight dataclass holding packed weights, sparsity metadata, and scales for 2:4 sparse quantization', 'pack quantized weight tensor columns into compact uint32 format for Marlin kernel compatibility', 'unpack packed quantized weight tensor columns back to their original expanded format', 'permute a scales tensor using Marlin permutation for quantized model weight dequantization', 'permute interleave and pack zero-point tensors for Marlin quantized model inference', 'check if the current system has CUDA SM 8.0+ GPU and marlin kernels installed']
```

Usage

```
{'build_marlin_weights_loader': 'build a MarlinWeightsLoader to load int4 quantized Marlin weights from a Weights object with a given prefix', 'build_marlin_linear_layer': 'build a MarlinLinear nn.Module that performs quantized GEMM using the Marlin kernel on int32-packed weights', 'build_gptq_marlin_24_linear': 'build a GPTQMarlin24Linear layer that performs 2:4 sparse quantized GEMM with 4-bit or 8-bit weights', 'create_marlin_weight': 'create a MarlinWeight dataclass holding int32-packed weights and float16 scales for Marlin quantized linear layers', 'create_gptq_marlin_24_weight': 'create a GPTQMarlin24Weight dataclass holding packed weights, sparsity metadata, and scales for 2:4 sparse quantization'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/marlin/util.py

Prompts

```
['create a GPTQMarlinFP8Linear layer from unquantized weights using the from_unquant class method', 'create a GPTQMarlinFP8Linear layer from existing FP8 weights and scales using the from_fp8 class method', 'run the forward pass of a GPTQMarlinFP8Linear layer on an input tensor to get quantized output', 'build a packed int32 tensor from an FP8 tensor by repacking four uint8 values into each int32 element', 'repack an FP8 weight tensor and its scales for use with the GPTQ-Marlin kernel format', 'check if GPTQ or AWQ quantized model parameters are compatible with Marlin kernels on the current CUDA device', 'repack GPTQ quantized weights into the Marlin kernel format for faster inference on CUDA', 'create a weights loader that loads GPTQ or AWQ quantized weights and repacks them for Marlin kernels', 'build a linear layer that uses repacked GPTQ Marlin weights for quantized matrix multiplication', 'convert AWQ packed zero points to the Marlin zero point format for quantized inference', 'build a MarlinWeightsLoader to load int4 quantized Marlin weights from a Weights object with a given prefix', 'build a MarlinLinear nn.Module that performs quantized GEMM using the Marlin kernel on int32-packed weights', 'build a GPTQMarlin24Linear layer that performs 2:4 sparse quantized GEMM with 4-bit or 8-bit weights', 'create a MarlinWeight dataclass holding int32-packed weights and float16 scales for Marlin quantized linear layers', 'create a GPTQMarlin24Weight dataclass holding packed weights, sparsity metadata, and scales for 2:4 sparse quantization', 'pack quantized weight tensor columns into compact uint32 format for Marlin kernel compatibility', 'unpack packed quantized weight tensor columns back to their original expanded format', 'permute a scales tensor using Marlin permutation for quantized model weight dequantization', 'permute interleave and pack zero-point tensors for Marlin quantized model inference', 'check if the current system has CUDA SM 8.0+ GPU and marlin kernels installed']
```

Usage

```
{'pack_quantized_weights': 'pack quantized weight tensor columns into compact uint32 format for Marlin kernel compatibility', 'unpack_quantized_weights': 'unpack packed quantized weight tensor columns back to their original expanded format', 'permute_scales_tensor': 'permute a scales tensor using Marlin permutation for quantized model weight dequantization', 'compute_marlin_zero_points': 'permute interleave and pack zero-point tensors for Marlin quantized model inference', 'check_marlin_kernel_support': 'check if the current system has CUDA SM 8.0+ GPU and marlin kernels installed'}
```

