# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/nn/modules.py

Prompts

```
['create a 4-bit quantized linear layer using Linear4bit for QLoRA finetuning', 'create an 8-bit linear layer using Linear8bitLt for LLM.int8() quantization', 'create a 4-bit quantized embedding layer using Embedding4bit for memory-efficient NLP models', 'create a stable embedding layer with 32-bit optimizer states and layer normalization', 'quantize model weights by loading state dict into Linear4bit and calling .to(device)', 'create a 4-bit quantized PyTorch module parameter with automatic dequantization via parametrization', 'replace an existing module parameter with a pre-quantized 4-bit parameter and its quantization state', 'replace a module parameter with a 4-bit quantized version using nf4 or fp4 quantization format', 'build a state dict that includes quantization state for saving and loading 4-bit quantized parameters', 'test parametrization hooks that enable caching and disable cache for dequantization during forward passes']
```

Usage

```
{'create_QuantizedLinearLayer': 'create a 4-bit quantized linear layer using Linear4bit for QLoRA finetuning', 'create_Int8LinearLayer': 'create an 8-bit linear layer using Linear8bitLt for LLM.int8() quantization', 'create_QuantizedEmbedding': 'create a 4-bit quantized embedding layer using Embedding4bit for memory-efficient NLP models', 'create_StableEmbeddingLayer': 'create a stable embedding layer with 32-bit optimizer states and layer normalization', 'quantize_model_weights': 'quantize model weights by loading state dict into Linear4bit and calling .to(device)'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/nn/parametrize.py

Prompts

```
['create a 4-bit quantized linear layer using Linear4bit for QLoRA finetuning', 'create an 8-bit linear layer using Linear8bitLt for LLM.int8() quantization', 'create a 4-bit quantized embedding layer using Embedding4bit for memory-efficient NLP models', 'create a stable embedding layer with 32-bit optimizer states and layer normalization', 'quantize model weights by loading state dict into Linear4bit and calling .to(device)', 'create a 4-bit quantized PyTorch module parameter with automatic dequantization via parametrization', 'replace an existing module parameter with a pre-quantized 4-bit parameter and its quantization state', 'replace a module parameter with a 4-bit quantized version using nf4 or fp4 quantization format', 'build a state dict that includes quantization state for saving and loading 4-bit quantized parameters', 'test parametrization hooks that enable caching and disable cache for dequantization during forward passes']
```

Usage

```
{'create_parametrize_4bit': 'create a 4-bit quantized PyTorch module parameter with automatic dequantization via parametrization', 'replace_param_4bit_prequantized': 'replace an existing module parameter with a pre-quantized 4-bit parameter and its quantization state', 'replace_param_4bit': 'replace a module parameter with a 4-bit quantized version using nf4 or fp4 quantization format', 'build_quantized_state_dict': 'build a state dict that includes quantization state for saving and loading 4-bit quantized parameters', 'test_parametrization_hooks': 'test parametrization hooks that enable caching and disable cache for dequantization during forward passes'}
```

