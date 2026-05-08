# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/experimental/tooling/test_layer_memory_tracker.py

Prompts

```
['test the LayerwiseMemoryTracker by monitoring a PyTorch model and collecting forward and backward memory traces', 'test the LayerwiseMemoryTracker with DistributedDataParallel to collect memory traces across multiple GPUs', 'test the LayerwiseMemoryTracker with FullyShardedDataParallel to collect memory traces and all-gathered activations', 'test the find_best_reset_points function to compute optimal activation checkpointing split points for a list of layer activations', 'test the LayerwiseMemoryTracker with a GPT2 NLP model to verify memory trace collection on a realistic architecture']
```

Usage

```
{'test_layerwise_memory_tracker': 'test the LayerwiseMemoryTracker by monitoring a PyTorch model and collecting forward and backward memory traces', 'test_layerwise_memory_tracker_with_ddp': 'test the LayerwiseMemoryTracker with DistributedDataParallel to collect memory traces across multiple GPUs', 'test_layerwise_memory_tracker_with_fsdp': 'test the LayerwiseMemoryTracker with FullyShardedDataParallel to collect memory traces and all-gathered activations', 'test_find_best_reset_points': 'test the find_best_reset_points function to compute optimal activation checkpointing split points for a list of layer activations', 'test_layerwise_memory_tracker_with_nlp_model': 'test the LayerwiseMemoryTracker with a GPT2 NLP model to verify memory trace collection on a realistic architecture'}
```

