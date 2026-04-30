# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/backends/default/ops.py

Prompts

```
['quantize a torch tensor to 4-bit nf4 or fp4 format using blockwise quantization', 'dequantize a 4-bit packed tensor back to its original float dtype', 'run int8 matrix multiply with row and column stats dequantization and optional bias', 'quantize a float tensor to int8 with per-row scaling and optional outlier column handling', 'run a 32-bit optimizer update for adam, lion, momentum, rmsprop, adagrad, or ademamix']
```

Usage

```
{'quantize_4bit_tensor': 'quantize a torch tensor to 4-bit nf4 or fp4 format using blockwise quantization', 'dequantize_4bit_tensor': 'dequantize a 4-bit packed tensor back to its original float dtype', 'run_int8_scaled_mm': 'run int8 matrix multiply with row and column stats dequantization and optional bias', 'quantize_int8_vectorwise': 'quantize a float tensor to int8 with per-row scaling and optional outlier column handling', 'run_optimizer_update_32bit': 'run a 32-bit optimizer update for adam, lion, momentum, rmsprop, adagrad, or ademamix'}
```

