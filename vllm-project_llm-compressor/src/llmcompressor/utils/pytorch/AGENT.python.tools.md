# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/utils/pytorch/module.py

Prompts

```
['build ModelParameterizedLayer objects for model modules matching given target patterns and parameter names', 'expand special target constants like __ALL_PRUNABLE__ to explicit class names with deprecation warnings', 'test if any layers in a PyTorch model have quantization enabled by checking for weight_fake_quant attributes', 'get list of module class names that should not be split when sharding a Hugging Face Transformer model', 'infer or validate sequential targets for layer-wise processing from a model or provided targets list', 'test the measure_accelerator_memory context manager to track peak GPU memory consumption', 'create a measure_accelerator_memory context manager instance for a specified device', 'build a memory profiling block using measure_accelerator_memory to measure peak memory usage', 'run reset_peak_memory_stats to clear peak memory statistics before a new measurement', 'summarize the deprecated measure_cuda_memory function that wraps measure_accelerator_memory']
```

Usage

```
{'build_parameterized_layers': 'build ModelParameterizedLayer objects for model modules matching given target patterns and parameter names', 'expand_special_targets': 'expand special target constants like __ALL_PRUNABLE__ to explicit class names with deprecation warnings', 'qat_active': 'test if any layers in a PyTorch model have quantization enabled by checking for weight_fake_quant attributes', 'get_no_split_params': 'get list of module class names that should not be split when sharding a Hugging Face Transformer model', 'infer_sequential_targets': 'infer or validate sequential targets for layer-wise processing from a model or provided targets list'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/utils/pytorch/utils.py

Prompts

```
['build ModelParameterizedLayer objects for model modules matching given target patterns and parameter names', 'expand special target constants like __ALL_PRUNABLE__ to explicit class names with deprecation warnings', 'test if any layers in a PyTorch model have quantization enabled by checking for weight_fake_quant attributes', 'get list of module class names that should not be split when sharding a Hugging Face Transformer model', 'infer or validate sequential targets for layer-wise processing from a model or provided targets list', 'test the measure_accelerator_memory context manager to track peak GPU memory consumption', 'create a measure_accelerator_memory context manager instance for a specified device', 'build a memory profiling block using measure_accelerator_memory to measure peak memory usage', 'run reset_peak_memory_stats to clear peak memory statistics before a new measurement', 'summarize the deprecated measure_cuda_memory function that wraps measure_accelerator_memory']
```

Usage

```
{'test_measure_accelerator_memory': 'test the measure_accelerator_memory context manager to track peak GPU memory consumption', 'create_measure_accelerator_memory': 'create a measure_accelerator_memory context manager instance for a specified device', 'build_measure_peak_memory': 'build a memory profiling block using measure_accelerator_memory to measure peak memory usage', 'run_reset_peak_memory_stats': 'run reset_peak_memory_stats to clear peak memory statistics before a new measurement', 'summarize_measure_cuda_memory': 'summarize the deprecated measure_cuda_memory function that wraps measure_accelerator_memory'}
```

