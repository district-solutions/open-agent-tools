# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/hpu/qlinear_hpu.py

Prompts

```
['create a QuantLinear HPU module with 4-bit quantization for Intel Habana processor inference', 'build a function that packs a tensor into compressed 4-bit format using bitwise operations', 'test the QuantLinear forward pass that converts uint4 weights and performs matrix multiplication on HPU', 'refactor the QuantLinear preprocessing method to unpack CUDA format weights and repack for HPU', 'review the QuantLinear unpack_zeros and unpack_weight methods that decompress 4-bit quantized tensors', 'create a QuantLinear HPU module with 4-bit quantization for Intel Habana processors', 'pack a tensor into 4-bit quantized format using bitwise operations for storage efficiency', 'run forward inference through a QuantLinear HPU layer with uint4 weight conversion', 'unpack quantized zeros from CUDA old format using bitwise right shift and masking', 'set packed quantized weights and zeros from another QuantLinear class instance']
```

Usage

```
{'create_quantlinear_hpu_module': 'create a QuantLinear HPU module with 4-bit quantization for Intel Habana processor inference', 'build_pack_tensor': 'build a function that packs a tensor into compressed 4-bit format using bitwise operations', 'test_quantlinear_forward': 'test the QuantLinear forward pass that converts uint4 weights and performs matrix multiplication on HPU', 'refactor_quantlinear_preprocessing': 'refactor the QuantLinear preprocessing method to unpack CUDA format weights and repack for HPU', 'review_quantlinear_unpack_methods': 'review the QuantLinear unpack_zeros and unpack_weight methods that decompress 4-bit quantized tensors'}
```

## File: intel_auto-round/auto_round_extension/hpu/qlinear_hpu_gptq.py

Prompts

```
['create a QuantLinear HPU module with 4-bit quantization for Intel Habana processor inference', 'build a function that packs a tensor into compressed 4-bit format using bitwise operations', 'test the QuantLinear forward pass that converts uint4 weights and performs matrix multiplication on HPU', 'refactor the QuantLinear preprocessing method to unpack CUDA format weights and repack for HPU', 'review the QuantLinear unpack_zeros and unpack_weight methods that decompress 4-bit quantized tensors', 'create a QuantLinear HPU module with 4-bit quantization for Intel Habana processors', 'pack a tensor into 4-bit quantized format using bitwise operations for storage efficiency', 'run forward inference through a QuantLinear HPU layer with uint4 weight conversion', 'unpack quantized zeros from CUDA old format using bitwise right shift and masking', 'set packed quantized weights and zeros from another QuantLinear class instance']
```

Usage

```
{'create_quantlinear_hpu': 'create a QuantLinear HPU module with 4-bit quantization for Intel Habana processors', 'pack_tensor_4bit': 'pack a tensor into 4-bit quantized format using bitwise operations for storage efficiency', 'forward_quantlinear_inference': 'run forward inference through a QuantLinear HPU layer with uint4 weight conversion', 'unpack_zeros_cuda_format': 'unpack quantized zeros from CUDA old format using bitwise right shift and masking', 'set_packed_quantlinear': 'set packed quantized weights and zeros from another QuantLinear class instance'}
```

