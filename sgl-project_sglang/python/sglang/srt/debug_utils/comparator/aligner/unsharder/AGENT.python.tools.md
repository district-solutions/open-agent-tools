# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/unsharder/executor.py

Prompts

```
['run execute_unsharder_plan to apply unsharding operations on a list of tensors according to a plan', 'create an UnsharderResult containing unsharded tensors and replicated check results', 'run _apply_unshard to apply a single unshard operation such as pick, concat, or reduce sum on grouped tensors', 'test _verify_replicated_group to verify that tensors are identical across parallel ranks within a group', 'run _thd_concat to concatenate tensors in THD format by splitting per-sequence and interleaving across ranks', 'test the normalize_parallel_info function to extract unified parallel info from dump meta', 'test the _is_error_sentinel function to check if a parallel_info dict is an error sentinel', 'refactor the normalize_parallel_info function to support additional parallel_info key sources', 'review the normalize_parallel_info function and its fallback logic for pseudo-axis rank and size', 'summarize the normalize_parallel_info function and how it merges sglang and megatron parallel info', 'build a plan to unshard model weights by combining sharded tensors across TP, CP, and other parallel axes', 'test that explicitly declared replicated axes are valid against parallel infos and sharded axes', 'test that all explicitly replicated axes are fully orthogonal with no dependency between them', 'test that every world rank has all required axes, consistent sizes, and complete rank coverage', 'test whether a child axis rank is uniquely determined by the joint tuple of parent axis ranks']
```

Usage

```
{'run_execute_unsharder_plan': 'run execute_unsharder_plan to apply unsharding operations on a list of tensors according to a plan', 'create_UnsharderResult': 'create an UnsharderResult containing unsharded tensors and replicated check results', 'run_apply_unshard': 'run _apply_unshard to apply a single unshard operation such as pick, concat, or reduce sum on grouped tensors', 'test_verify_replicated_group': 'test _verify_replicated_group to verify that tensors are identical across parallel ranks within a group', 'run_thd_concat': 'run _thd_concat to concatenate tensors in THD format by splitting per-sequence and interleaving across ranks'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/unsharder/parallel_info.py

Prompts

```
['run execute_unsharder_plan to apply unsharding operations on a list of tensors according to a plan', 'create an UnsharderResult containing unsharded tensors and replicated check results', 'run _apply_unshard to apply a single unshard operation such as pick, concat, or reduce sum on grouped tensors', 'test _verify_replicated_group to verify that tensors are identical across parallel ranks within a group', 'run _thd_concat to concatenate tensors in THD format by splitting per-sequence and interleaving across ranks', 'test the normalize_parallel_info function to extract unified parallel info from dump meta', 'test the _is_error_sentinel function to check if a parallel_info dict is an error sentinel', 'refactor the normalize_parallel_info function to support additional parallel_info key sources', 'review the normalize_parallel_info function and its fallback logic for pseudo-axis rank and size', 'summarize the normalize_parallel_info function and how it merges sglang and megatron parallel info', 'build a plan to unshard model weights by combining sharded tensors across TP, CP, and other parallel axes', 'test that explicitly declared replicated axes are valid against parallel infos and sharded axes', 'test that all explicitly replicated axes are fully orthogonal with no dependency between them', 'test that every world rank has all required axes, consistent sizes, and complete rank coverage', 'test whether a child axis rank is uniquely determined by the joint tuple of parent axis ranks']
```

Usage

```
{'test_normalize_parallel_info': 'test the normalize_parallel_info function to extract unified parallel info from dump meta', 'test_is_error_sentinel': 'test the _is_error_sentinel function to check if a parallel_info dict is an error sentinel', 'refactor_normalize_parallel_info': 'refactor the normalize_parallel_info function to support additional parallel_info key sources', 'review_normalize_parallel_info': 'review the normalize_parallel_info function and its fallback logic for pseudo-axis rank and size', 'summarize_parallel_info': 'summarize the normalize_parallel_info function and how it merges sglang and megatron parallel info'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/unsharder/planner.py

Prompts

```
['run execute_unsharder_plan to apply unsharding operations on a list of tensors according to a plan', 'create an UnsharderResult containing unsharded tensors and replicated check results', 'run _apply_unshard to apply a single unshard operation such as pick, concat, or reduce sum on grouped tensors', 'test _verify_replicated_group to verify that tensors are identical across parallel ranks within a group', 'run _thd_concat to concatenate tensors in THD format by splitting per-sequence and interleaving across ranks', 'test the normalize_parallel_info function to extract unified parallel info from dump meta', 'test the _is_error_sentinel function to check if a parallel_info dict is an error sentinel', 'refactor the normalize_parallel_info function to support additional parallel_info key sources', 'review the normalize_parallel_info function and its fallback logic for pseudo-axis rank and size', 'summarize the normalize_parallel_info function and how it merges sglang and megatron parallel info', 'build a plan to unshard model weights by combining sharded tensors across TP, CP, and other parallel axes', 'test that explicitly declared replicated axes are valid against parallel infos and sharded axes', 'test that all explicitly replicated axes are fully orthogonal with no dependency between them', 'test that every world rank has all required axes, consistent sizes, and complete rank coverage', 'test whether a child axis rank is uniquely determined by the joint tuple of parent axis ranks']
```

Usage

```
{'build_compute_unsharder_plan': 'build a plan to unshard model weights by combining sharded tensors across TP, CP, and other parallel axes', 'test_validate_explicit_replicated': 'test that explicitly declared replicated axes are valid against parallel infos and sharded axes', 'test_validate_replicated_axes_orthogonal': 'test that all explicitly replicated axes are fully orthogonal with no dependency between them', 'test_validate_parallel_infos': 'test that every world rank has all required axes, consistent sizes, and complete rank coverage', 'test_is_jointly_determined': 'test whether a child axis rank is uniquely determined by the joint tuple of parent axis ranks'}
```

