# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/compressed_tensors_integration/test_compressed_models.py

Prompts

```
['test that compressed and uncompressed model weights match within tolerance', 'test that loading compressed tensor models produces no missing or unexpected key warnings', 'test that models loaded by default keep linear modules in compressed quantization state', 'test that run_compressed=False decompresses all modules so none stay in compressed state', 'test that model generation output is identical whether run_compressed is true or false', 'test CompressedTensorsConfig constructor rejects invalid quantization scheme arguments and accepts valid config groups', 'test CompressedTensorsConfig serialization roundtrip using to_dict and from_dict methods', 'test loading a W4A16 quantized TinyLlama model and verify perplexity stays under threshold', 'test loading an FP8 quantized TinyLlama model and verify perplexity stays under threshold', 'test loading a W8A8 quantized TinyLlama model and verify perplexity stays under threshold']
```

Usage

```
{'test_compressed_uncompressed_model_shapes': 'test that compressed and uncompressed model weights match within tolerance', 'test_no_warnings_for_all_models': 'test that loading compressed tensor models produces no missing or unexpected key warnings', 'test_default_run_compressed_true': 'test that models loaded by default keep linear modules in compressed quantization state', 'test_default_run_compressed_false': 'test that run_compressed=False decompresses all modules so none stay in compressed state', 'test_run_compressed_outputs_match': 'test that model generation output is identical whether run_compressed is true or false'}
```

## File: huggingface_transformers/tests/quantization/compressed_tensors_integration/test_compressed_tensors.py

Prompts

```
['test that compressed and uncompressed model weights match within tolerance', 'test that loading compressed tensor models produces no missing or unexpected key warnings', 'test that models loaded by default keep linear modules in compressed quantization state', 'test that run_compressed=False decompresses all modules so none stay in compressed state', 'test that model generation output is identical whether run_compressed is true or false', 'test CompressedTensorsConfig constructor rejects invalid quantization scheme arguments and accepts valid config groups', 'test CompressedTensorsConfig serialization roundtrip using to_dict and from_dict methods', 'test loading a W4A16 quantized TinyLlama model and verify perplexity stays under threshold', 'test loading an FP8 quantized TinyLlama model and verify perplexity stays under threshold', 'test loading a W8A8 quantized TinyLlama model and verify perplexity stays under threshold']
```

Usage

```
{'test_compressed_tensors_config_args': 'test CompressedTensorsConfig constructor rejects invalid quantization scheme arguments and accepts valid config groups', 'test_config_to_from_dict': 'test CompressedTensorsConfig serialization roundtrip using to_dict and from_dict methods', 'test_quantized_model_w4a16': 'test loading a W4A16 quantized TinyLlama model and verify perplexity stays under threshold', 'test_quantized_model_fp8': 'test loading an FP8 quantized TinyLlama model and verify perplexity stays under threshold', 'test_quantized_model_int8': 'test loading a W8A8 quantized TinyLlama model and verify perplexity stays under threshold'}
```

