# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/utils/dist_utils.py

Prompts

```
['run reduce_mean to compute the mean of a tensor across multiple GPUs', 'test reduce_mean returns the original tensor when distributed is not initialized', 'review reduce_mean to verify it correctly divides by world size before all_reduce', 'summarize reduce_mean which clones a tensor and performs distributed all_reduce to get the mean', 'refactor reduce_mean to support additional reduction operations beyond mean', 'build a python module that uses multi_apply to apply a function across multiple input arguments and collect grouped results', 'test the multi_apply function by applying a sample function to lists of arguments and verifying grouped output', 'refactor the multi_apply function to support additional keyword argument handling or custom result grouping', 'build a python module that uses add_prefix to prepend a string prefix to all keys in a dictionary', 'test the add_prefix function by prefixing dictionary keys and verifying the updated key names']
```

Usage

```
{'run_reduce_mean': 'run reduce_mean to compute the mean of a tensor across multiple GPUs', 'test_reduce_mean': 'test reduce_mean returns the original tensor when distributed is not initialized', 'review_reduce_mean': 'review reduce_mean to verify it correctly divides by world size before all_reduce', 'summarize_reduce_mean': 'summarize reduce_mean which clones a tensor and performs distributed all_reduce to get the mean', 'refactor_reduce_mean': 'refactor reduce_mean to support additional reduction operations beyond mean'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/utils/misc.py

Prompts

```
['run reduce_mean to compute the mean of a tensor across multiple GPUs', 'test reduce_mean returns the original tensor when distributed is not initialized', 'review reduce_mean to verify it correctly divides by world size before all_reduce', 'summarize reduce_mean which clones a tensor and performs distributed all_reduce to get the mean', 'refactor reduce_mean to support additional reduction operations beyond mean', 'build a python module that uses multi_apply to apply a function across multiple input arguments and collect grouped results', 'test the multi_apply function by applying a sample function to lists of arguments and verifying grouped output', 'refactor the multi_apply function to support additional keyword argument handling or custom result grouping', 'build a python module that uses add_prefix to prepend a string prefix to all keys in a dictionary', 'test the add_prefix function by prefixing dictionary keys and verifying the updated key names']
```

Usage

```
{'build_multi_apply': 'build a python module that uses multi_apply to apply a function across multiple input arguments and collect grouped results', 'test_multi_apply': 'test the multi_apply function by applying a sample function to lists of arguments and verifying grouped output', 'refactor_multi_apply': 'refactor the multi_apply function to support additional keyword argument handling or custom result grouping', 'build_add_prefix': 'build a python module that uses add_prefix to prepend a string prefix to all keys in a dictionary', 'test_add_prefix': 'test the add_prefix function by prefixing dictionary keys and verifying the updated key names'}
```

