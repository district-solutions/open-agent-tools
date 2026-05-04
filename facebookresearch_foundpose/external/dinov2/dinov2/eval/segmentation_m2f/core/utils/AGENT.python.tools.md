# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/utils/dist_utils.py

Prompts

```
['run reduce_mean to compute the mean of a tensor across multiple GPUs in a distributed setting', 'test reduce_mean to verify it returns the input tensor unchanged when distributed training is not initialized', 'review reduce_mean to understand how it uses dist.all_reduce with SUM and divides by world size', 'summarize reduce_mean which clones a tensor and performs distributed all-reduce to get the mean across GPUs', 'refactor reduce_mean to add support for additional reduction operations beyond mean across distributed GPUs', 'apply a function to multiple input arguments and collect grouped results into separate lists', 'apply a function with keyword arguments to multiple inputs and return transposed results', 'test the multi_apply function by applying a sample function to lists of arguments', 'add a dot-separated prefix to all keys in a dictionary', 'test the add_prefix function by prefixing keys in a sample dictionary']
```

Usage

```
{'run_reduce_mean': 'run reduce_mean to compute the mean of a tensor across multiple GPUs in a distributed setting', 'test_reduce_mean': 'test reduce_mean to verify it returns the input tensor unchanged when distributed training is not initialized', 'review_reduce_mean': 'review reduce_mean to understand how it uses dist.all_reduce with SUM and divides by world size', 'summarize_reduce_mean': 'summarize reduce_mean which clones a tensor and performs distributed all-reduce to get the mean across GPUs', 'refactor_reduce_mean': 'refactor reduce_mean to add support for additional reduction operations beyond mean across distributed GPUs'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/core/utils/misc.py

Prompts

```
['run reduce_mean to compute the mean of a tensor across multiple GPUs in a distributed setting', 'test reduce_mean to verify it returns the input tensor unchanged when distributed training is not initialized', 'review reduce_mean to understand how it uses dist.all_reduce with SUM and divides by world size', 'summarize reduce_mean which clones a tensor and performs distributed all-reduce to get the mean across GPUs', 'refactor reduce_mean to add support for additional reduction operations beyond mean across distributed GPUs', 'apply a function to multiple input arguments and collect grouped results into separate lists', 'apply a function with keyword arguments to multiple inputs and return transposed results', 'test the multi_apply function by applying a sample function to lists of arguments', 'add a dot-separated prefix to all keys in a dictionary', 'test the add_prefix function by prefixing keys in a sample dictionary']
```

Usage

```
{'apply_multi_apply': 'apply a function to multiple input arguments and collect grouped results into separate lists', 'apply_multi_apply_with_kwargs': 'apply a function with keyword arguments to multiple inputs and return transposed results', 'test_multi_apply': 'test the multi_apply function by applying a sample function to lists of arguments', 'add_prefix_to_dict': 'add a dot-separated prefix to all keys in a dictionary', 'test_add_prefix': 'test the add_prefix function by prefixing keys in a sample dictionary'}
```

