# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/algorithms/test_alg_ext.py

Prompts

```
['test AutoRound quantization with MXFP4, NVFP4, W2A16G64, or GGUF schemes using enable_alg_ext', 'test 2-bit quantization with AutoRound using bits=2, group_size=64, and enable_alg_ext=True', 'test the auto_round CLI module with enable_alg_ext, avg_bits, and options flags', 'run AutoRound quantize_and_save to produce a quantized model and evaluate accuracy with evaluate_accuracy', 'review AutoScheme configuration with options, avg_bits, and ignore_scale_zp_bits parameters', 'build an AutoScheme with target avg_bits and quantization options like GGUF or MXFP4', 'build an AutoRound quantizer with a model path and AutoScheme for mixed precision quantization', 'test AutoRound quantize method to quantize a model and return layer config', 'test AutoRound quantize_and_save to quantize a model and export it in GGUF format', 'test compute_avg_bits_for_model to verify the average bits per weight of a quantized model']
```

Usage

```
{'test_quantize_with_scheme': 'test AutoRound quantization with MXFP4, NVFP4, W2A16G64, or GGUF schemes using enable_alg_ext', 'test_2bit_quantization': 'test 2-bit quantization with AutoRound using bits=2, group_size=64, and enable_alg_ext=True', 'test_cli_quantization': 'test the auto_round CLI module with enable_alg_ext, avg_bits, and options flags', 'run_quantize_and_save': 'run AutoRound quantize_and_save to produce a quantized model and evaluate accuracy with evaluate_accuracy', 'review_autoscheme_config': 'review AutoScheme configuration with options, avg_bits, and ignore_scale_zp_bits parameters'}
```

## File: intel_auto-round/test/test_cuda/algorithms/test_auto_scheme.py

Prompts

```
['test AutoRound quantization with MXFP4, NVFP4, W2A16G64, or GGUF schemes using enable_alg_ext', 'test 2-bit quantization with AutoRound using bits=2, group_size=64, and enable_alg_ext=True', 'test the auto_round CLI module with enable_alg_ext, avg_bits, and options flags', 'run AutoRound quantize_and_save to produce a quantized model and evaluate accuracy with evaluate_accuracy', 'review AutoScheme configuration with options, avg_bits, and ignore_scale_zp_bits parameters', 'build an AutoScheme with target avg_bits and quantization options like GGUF or MXFP4', 'build an AutoRound quantizer with a model path and AutoScheme for mixed precision quantization', 'test AutoRound quantize method to quantize a model and return layer config', 'test AutoRound quantize_and_save to quantize a model and export it in GGUF format', 'test compute_avg_bits_for_model to verify the average bits per weight of a quantized model']
```

Usage

```
{'build_autoscheme_mixed_precision': 'build an AutoScheme with target avg_bits and quantization options like GGUF or MXFP4', 'build_autoround_quantizer': 'build an AutoRound quantizer with a model path and AutoScheme for mixed precision quantization', 'test_autoround_quantize': 'test AutoRound quantize method to quantize a model and return layer config', 'test_autoround_quantize_and_save': 'test AutoRound quantize_and_save to quantize a model and export it in GGUF format', 'test_compute_avg_bits_for_model': 'test compute_avg_bits_for_model to verify the average bits per weight of a quantized model'}
```

