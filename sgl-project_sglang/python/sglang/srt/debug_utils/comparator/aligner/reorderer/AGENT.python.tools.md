# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/reorderer/executor.py

Prompts

```
['execute a reorderer plan to transform zigzag-interleaved tensors back to natural order', 'reorder a tensor from zigzag chunk interleaving to natural sequential order along a given dimension', 'reorder packed-sequence tensors from zigzag interleaving to natural order with per-segment lengths', 'resolve a dimension index from a tensor by its string name for dimension-aware reordering', 'strip dimension names from a tensor to enable chunking and concatenation operations', 'build reorderer plans from dim specs and parallel infos for zigzag-to-natural tensor dimension reordering', 'test the ZigzagToNaturalParams class for sequence and token dimension zigzag reordering', 'test the ZigzagToNaturalThdParams class for thd-based zigzag reordering with per-sequence token lengths', 'test the ReordererPlan class that wraps reorderer parameters into a plan', 'test compute_reorderer_plans with natural ordering, zigzag ordering, and unsupported dim names']
```

Usage

```
{'execute_reorderer_plan': 'execute a reorderer plan to transform zigzag-interleaved tensors back to natural order', 'reorder_zigzag_to_natural': 'reorder a tensor from zigzag chunk interleaving to natural sequential order along a given dimension', 'reorder_zigzag_to_natural_thd': 'reorder packed-sequence tensors from zigzag interleaving to natural order with per-segment lengths', 'resolve_dim_by_name': 'resolve a dimension index from a tensor by its string name for dimension-aware reordering', 'strip_dim_names': 'strip dimension names from a tensor to enable chunking and concatenation operations'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/reorderer/planner.py

Prompts

```
['execute a reorderer plan to transform zigzag-interleaved tensors back to natural order', 'reorder a tensor from zigzag chunk interleaving to natural sequential order along a given dimension', 'reorder packed-sequence tensors from zigzag interleaving to natural order with per-segment lengths', 'resolve a dimension index from a tensor by its string name for dimension-aware reordering', 'strip dimension names from a tensor to enable chunking and concatenation operations', 'build reorderer plans from dim specs and parallel infos for zigzag-to-natural tensor dimension reordering', 'test the ZigzagToNaturalParams class for sequence and token dimension zigzag reordering', 'test the ZigzagToNaturalThdParams class for thd-based zigzag reordering with per-sequence token lengths', 'test the ReordererPlan class that wraps reorderer parameters into a plan', 'test compute_reorderer_plans with natural ordering, zigzag ordering, and unsupported dim names']
```

Usage

```
{'build_reorderer_plans': 'build reorderer plans from dim specs and parallel infos for zigzag-to-natural tensor dimension reordering', 'test_zigzag_to_natural_params': 'test the ZigzagToNaturalParams class for sequence and token dimension zigzag reordering', 'test_zigzag_to_natural_thd_params': 'test the ZigzagToNaturalThdParams class for thd-based zigzag reordering with per-sequence token lengths', 'test_reorderer_plan': 'test the ReordererPlan class that wraps reorderer parameters into a plan', 'test_compute_reorderer_plans': 'test compute_reorderer_plans with natural ordering, zigzag ordering, and unsupported dim names'}
```

