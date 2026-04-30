# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/layers/bnb.py

Prompts

```
['create a Linear8bitLt layer from a weight tensor and optional bias for 8-bit quantized inference', 'create a Linear4bit layer with fp4 or nf4 quantization from a weight tensor and bias', 'build a BNBWeight dataclass wrapping a torch.Tensor to produce an 8-bit linear layer via get_linear', 'build a BNBFP4Weight dataclass wrapping a torch.Tensor to produce an fp4 quantized 4-bit linear layer', 'build a BNBNF4Weight dataclass wrapping a torch.Tensor to produce an nf4 quantized 4-bit linear layer', 'load a Conv2d layer with weight and bias from checkpoint weights using init_empty_weights', 'load a Conv2d layer with weight only and no bias from checkpoint weights', 'monkey-patch torch.nn.Conv2d with a load classmethod to load layers from weights', 'review the Conv2d load and load_no_bias methods for correct weight and bias handling', 'refactor the Conv2d load methods to support additional layer parameters like padding or dilation', 'build an Fp8Linear module from FP8 quantized weights and scales for HPU inference', 'create a HybridFP8UnquantLoader to load FP8 and unquantized weights from a checkpoint', 'quantize a PyTorch tensor to FP8 format using the fp8_quantize function with a given scale', 'dequantize a block-wise FP8 weight tensor back to bfloat16 using dequant_block_fp8_weight_naive', 'apply block-wise FP8 matrix multiplication on HPU using apply_block_fp8_linear_hpu_dynamic']
```

Usage

```
{'create_8bit_linear_layer': 'create a Linear8bitLt layer from a weight tensor and optional bias for 8-bit quantized inference', 'create_4bit_linear_layer': 'create a Linear4bit layer with fp4 or nf4 quantization from a weight tensor and bias', 'build_bnb_weight': 'build a BNBWeight dataclass wrapping a torch.Tensor to produce an 8-bit linear layer via get_linear', 'build_fp4_weight': 'build a BNBFP4Weight dataclass wrapping a torch.Tensor to produce an fp4 quantized 4-bit linear layer', 'build_nf4_weight': 'build a BNBNF4Weight dataclass wrapping a torch.Tensor to produce an nf4 quantized 4-bit linear layer'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/layers/conv.py

Prompts

```
['create a Linear8bitLt layer from a weight tensor and optional bias for 8-bit quantized inference', 'create a Linear4bit layer with fp4 or nf4 quantization from a weight tensor and bias', 'build a BNBWeight dataclass wrapping a torch.Tensor to produce an 8-bit linear layer via get_linear', 'build a BNBFP4Weight dataclass wrapping a torch.Tensor to produce an fp4 quantized 4-bit linear layer', 'build a BNBNF4Weight dataclass wrapping a torch.Tensor to produce an nf4 quantized 4-bit linear layer', 'load a Conv2d layer with weight and bias from checkpoint weights using init_empty_weights', 'load a Conv2d layer with weight only and no bias from checkpoint weights', 'monkey-patch torch.nn.Conv2d with a load classmethod to load layers from weights', 'review the Conv2d load and load_no_bias methods for correct weight and bias handling', 'refactor the Conv2d load methods to support additional layer parameters like padding or dilation', 'build an Fp8Linear module from FP8 quantized weights and scales for HPU inference', 'create a HybridFP8UnquantLoader to load FP8 and unquantized weights from a checkpoint', 'quantize a PyTorch tensor to FP8 format using the fp8_quantize function with a given scale', 'dequantize a block-wise FP8 weight tensor back to bfloat16 using dequant_block_fp8_weight_naive', 'apply block-wise FP8 matrix multiplication on HPU using apply_block_fp8_linear_hpu_dynamic']
```

Usage

```
{'load_conv2d_with_weights': 'load a Conv2d layer with weight and bias from checkpoint weights using init_empty_weights', 'load_conv2d_no_bias': 'load a Conv2d layer with weight only and no bias from checkpoint weights', 'monkey_patch_conv2d_load': 'monkey-patch torch.nn.Conv2d with a load classmethod to load layers from weights', 'review_conv_layer_loading': 'review the Conv2d load and load_no_bias methods for correct weight and bias handling', 'refactor_conv2d_loading': 'refactor the Conv2d load methods to support additional layer parameters like padding or dilation'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/layers/fp8.py

Prompts

```
['create a Linear8bitLt layer from a weight tensor and optional bias for 8-bit quantized inference', 'create a Linear4bit layer with fp4 or nf4 quantization from a weight tensor and bias', 'build a BNBWeight dataclass wrapping a torch.Tensor to produce an 8-bit linear layer via get_linear', 'build a BNBFP4Weight dataclass wrapping a torch.Tensor to produce an fp4 quantized 4-bit linear layer', 'build a BNBNF4Weight dataclass wrapping a torch.Tensor to produce an nf4 quantized 4-bit linear layer', 'load a Conv2d layer with weight and bias from checkpoint weights using init_empty_weights', 'load a Conv2d layer with weight only and no bias from checkpoint weights', 'monkey-patch torch.nn.Conv2d with a load classmethod to load layers from weights', 'review the Conv2d load and load_no_bias methods for correct weight and bias handling', 'refactor the Conv2d load methods to support additional layer parameters like padding or dilation', 'build an Fp8Linear module from FP8 quantized weights and scales for HPU inference', 'create a HybridFP8UnquantLoader to load FP8 and unquantized weights from a checkpoint', 'quantize a PyTorch tensor to FP8 format using the fp8_quantize function with a given scale', 'dequantize a block-wise FP8 weight tensor back to bfloat16 using dequant_block_fp8_weight_naive', 'apply block-wise FP8 matrix multiplication on HPU using apply_block_fp8_linear_hpu_dynamic']
```

Usage

```
{'build_fp8_linear_layer': 'build an Fp8Linear module from FP8 quantized weights and scales for HPU inference', 'create_fp8_weight_loader': 'create a HybridFP8UnquantLoader to load FP8 and unquantized weights from a checkpoint', 'quantize_tensor_to_fp8': 'quantize a PyTorch tensor to FP8 format using the fp8_quantize function with a given scale', 'dequantize_block_fp8_weight': 'dequantize a block-wise FP8 weight tensor back to bfloat16 using dequant_block_fp8_weight_naive', 'apply_fp8_gemm_on_hpu': 'apply block-wise FP8 matrix multiplication on HPU using apply_block_fp8_linear_hpu_dynamic'}
```

