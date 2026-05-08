# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/pipe/balance/blockpartition.py

Prompts

```
['split a sequence of integers into balanced partitions minimizing variance between partition sums', 'partition a list of numbers into k groups with approximately equal normalized sums', 'divide a sequence into N partitions where each partition sum is as close as possible', 'review the Block Partitions of Sequences algorithm by Imre Barany for balancing partition sums', 'test the solve function with edge cases like single element sequences or equal partitions', 'profile elapsed times per layer of an nn.Sequential module using forward and backward passes', 'profile CUDA memory usage per layer of an nn.Sequential module including parameters and activations', 'create deep copies of each layer in an nn.Sequential module for safe profiling without modifying the original', 'detach all tensors in a Batch from the autograd graph while preserving requires_grad flags', 'review the per-layer profiler module that measures timing and memory usage for pipeline parallel balancing']
```

Usage

```
{'solve_sequence_partitions': 'split a sequence of integers into balanced partitions minimizing variance between partition sums', 'solve_balanced_split': 'partition a list of numbers into k groups with approximately equal normalized sums', 'solve_minimize_variance': 'divide a sequence into N partitions where each partition sum is as close as possible', 'review_solve_algorithm': 'review the Block Partitions of Sequences algorithm by Imre Barany for balancing partition sums', 'test_solve_edge_cases': 'test the solve function with edge cases like single element sequences or equal partitions'}
```

## File: facebookresearch_fairscale/fairscale/nn/pipe/balance/profile.py

Prompts

```
['split a sequence of integers into balanced partitions minimizing variance between partition sums', 'partition a list of numbers into k groups with approximately equal normalized sums', 'divide a sequence into N partitions where each partition sum is as close as possible', 'review the Block Partitions of Sequences algorithm by Imre Barany for balancing partition sums', 'test the solve function with edge cases like single element sequences or equal partitions', 'profile elapsed times per layer of an nn.Sequential module using forward and backward passes', 'profile CUDA memory usage per layer of an nn.Sequential module including parameters and activations', 'create deep copies of each layer in an nn.Sequential module for safe profiling without modifying the original', 'detach all tensors in a Batch from the autograd graph while preserving requires_grad flags', 'review the per-layer profiler module that measures timing and memory usage for pipeline parallel balancing']
```

Usage

```
{'profile_times_per_layer': 'profile elapsed times per layer of an nn.Sequential module using forward and backward passes', 'profile_sizes_per_layer': 'profile CUDA memory usage per layer of an nn.Sequential module including parameters and activations', 'create_layerwise_sandbox': 'create deep copies of each layer in an nn.Sequential module for safe profiling without modifying the original', 'detach_batch_from_autograd': 'detach all tensors in a Batch from the autograd graph while preserving requires_grad flags', 'review_profile_module': 'review the per-layer profiler module that measures timing and memory usage for pipeline parallel balancing'}
```

