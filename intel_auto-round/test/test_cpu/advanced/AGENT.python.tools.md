# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cpu/advanced/test_evaluation_functions.py

Prompts

```
['test parse_vllm_args returns empty dict for None or empty string input', 'test parse_vllm_args correctly parses comma separated integer arguments like tensor_parallel_size', 'test parse_vllm_args correctly parses comma separated float arguments like gpu_memory_utilization', 'test parse_vllm_args correctly parses boolean arguments like trust_remote_code and enable_lora', 'test _load_gguf_model_if_needed returns correct values for non GGUF model paths', 'test an FP8 block quantized model by checking weight dtype and converting CompressedLinear layers to high precision', 'test a W4A16 quantized model by verifying INT4 packed weights and converting to bfloat16', 'check and mark quantized modules in a model to detect FP8, NVFP4, MXFP4, or WOQ weight types', 'convert compressed linear layers in a quantized model back to high precision bfloat16 weights', 'quantize a W4A16 model to MXFP4 format using AutoRound and save with llm_compressor format']
```

Usage

```
{'test_parse_vllm_args_empty': 'test parse_vllm_args returns empty dict for None or empty string input', 'test_parse_vllm_args_integers': 'test parse_vllm_args correctly parses comma separated integer arguments like tensor_parallel_size', 'test_parse_vllm_args_floats': 'test parse_vllm_args correctly parses comma separated float arguments like gpu_memory_utilization', 'test_parse_vllm_args_booleans': 'test parse_vllm_args correctly parses boolean arguments like trust_remote_code and enable_lora', 'test_load_gguf_model_if_needed': 'test _load_gguf_model_if_needed returns correct values for non GGUF model paths'}
```

## File: intel_auto-round/test/test_cpu/advanced/test_low_precision_input_model.py

Prompts

```
['test parse_vllm_args returns empty dict for None or empty string input', 'test parse_vllm_args correctly parses comma separated integer arguments like tensor_parallel_size', 'test parse_vllm_args correctly parses comma separated float arguments like gpu_memory_utilization', 'test parse_vllm_args correctly parses boolean arguments like trust_remote_code and enable_lora', 'test _load_gguf_model_if_needed returns correct values for non GGUF model paths', 'test an FP8 block quantized model by checking weight dtype and converting CompressedLinear layers to high precision', 'test a W4A16 quantized model by verifying INT4 packed weights and converting to bfloat16', 'check and mark quantized modules in a model to detect FP8, NVFP4, MXFP4, or WOQ weight types', 'convert compressed linear layers in a quantized model back to high precision bfloat16 weights', 'quantize a W4A16 model to MXFP4 format using AutoRound and save with llm_compressor format']
```

Usage

```
{'test_fp8_block_quantized_model': 'test an FP8 block quantized model by checking weight dtype and converting CompressedLinear layers to high precision', 'test_w4a16_quantized_model': 'test a W4A16 quantized model by verifying INT4 packed weights and converting to bfloat16', 'check_and_mark_quantized_module': 'check and mark quantized modules in a model to detect FP8, NVFP4, MXFP4, or WOQ weight types', 'convert_module_to_hp_if_necessary': 'convert compressed linear layers in a quantized model back to high precision bfloat16 weights', 'quantize_w4a16_to_mxfp4': 'quantize a W4A16 model to MXFP4 format using AutoRound and save with llm_compressor format'}
```

