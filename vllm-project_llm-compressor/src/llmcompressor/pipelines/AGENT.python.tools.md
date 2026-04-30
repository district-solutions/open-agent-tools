# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/cache.py

Prompts

```
['build an empty intermediate values cache with a specified number of batches and offload device', 'create a cache prepopulated with intermediate values from a PyTorch DataLoader', 'fetch offloaded intermediate values for a specific batch and optional input names', 'update a cache batch with new intermediate values that are offloaded to the specified device', 'iterate over cached batches with background prefetching to overlap H2D transfers with compute', 'create a calibration pipeline instance from a list of modifiers and optional user specification', 'run a calibration pipeline on a torch model with a dataloader and dataset arguments', 'test the pipeline inference logic that selects datafree or sequential based on quantization modifiers', 'review the from_modifiers class method that resolves the best calibration pipeline from available modifiers', 'summarize the abstract CalibrationPipeline class that standardizes model calibration workflows']
```

Usage

```
{'build_cache_empty': 'build an empty intermediate values cache with a specified number of batches and offload device', 'create_cache_from_dataloader': 'create a cache prepopulated with intermediate values from a PyTorch DataLoader', 'fetch_intermediate_values': 'fetch offloaded intermediate values for a specific batch and optional input names', 'update_cache_batch': 'update a cache batch with new intermediate values that are offloaded to the specified device', 'iterate_prefetch_batches': 'iterate over cached batches with background prefetching to overlap H2D transfers with compute'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/registry.py

Prompts

```
['build an empty intermediate values cache with a specified number of batches and offload device', 'create a cache prepopulated with intermediate values from a PyTorch DataLoader', 'fetch offloaded intermediate values for a specific batch and optional input names', 'update a cache batch with new intermediate values that are offloaded to the specified device', 'iterate over cached batches with background prefetching to overlap H2D transfers with compute', 'create a calibration pipeline instance from a list of modifiers and optional user specification', 'run a calibration pipeline on a torch model with a dataloader and dataset arguments', 'test the pipeline inference logic that selects datafree or sequential based on quantization modifiers', 'review the from_modifiers class method that resolves the best calibration pipeline from available modifiers', 'summarize the abstract CalibrationPipeline class that standardizes model calibration workflows']
```

Usage

```
{'create_CalibrationPipeline': 'create a calibration pipeline instance from a list of modifiers and optional user specification', 'run_CalibrationPipeline': 'run a calibration pipeline on a torch model with a dataloader and dataset arguments', 'test_infer_pipeline': 'test the pipeline inference logic that selects datafree or sequential based on quantization modifiers', 'review_from_modifiers': 'review the from_modifiers class method that resolves the best calibration pipeline from available modifiers', 'summarize_CalibrationPipeline': 'summarize the abstract CalibrationPipeline class that standardizes model calibration workflows'}
```

