# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/tooling/layer_memory_tracker.py

Prompts

```
["create a LayerwiseMemoryTracker to monitor a PyTorch model's memory usage layer by layer during forward and backward passes", 'use suggest_checkpoint_location to find the best places to insert activation memory reset checkpoints in a model trace', 'call compare_memory_traces_in_plot to generate memory allocation and activation plots from LayerMemoryTrace data', 'use find_best_reset_points to compute ideal checkpoint placement given a list of per-layer activation sizes', 'wrap a ProcessGroup with ProcessGroupTracker to monitor allgather calls and correlate them with memory traces']
```

Usage

```
{'monitor_model_memory_layerwise': "create a LayerwiseMemoryTracker to monitor a PyTorch model's memory usage layer by layer during forward and backward passes", 'suggest_checkpoint_locations': 'use suggest_checkpoint_location to find the best places to insert activation memory reset checkpoints in a model trace', 'plot_memory_traces': 'call compare_memory_traces_in_plot to generate memory allocation and activation plots from LayerMemoryTrace data', 'find_optimal_activation_checkpoints': 'use find_best_reset_points to compute ideal checkpoint placement given a list of per-layer activation sizes', 'track_process_group_allgather': 'wrap a ProcessGroup with ProcessGroupTracker to monitor allgather calls and correlate them with memory traces'}
```

