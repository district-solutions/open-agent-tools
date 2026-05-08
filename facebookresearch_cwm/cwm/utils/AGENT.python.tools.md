# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/utils/distributed.py

Prompts

```
['create a decorator that restricts a function to execute only on rank zero in distributed training', 'use dist_max to compute the maximum value of a scalar across all GPUs in a device mesh', 'use dist_sum_list to coalesced-sum a list of float values across all ranks in a device mesh', 'use all_gather_object to collect arbitrary Python objects from all processes in a process group', 'use the Metrics class to track sums, maxima, and counts of training metrics across distributed ranks']
```

Usage

```
{'create_rank_zero_only_decorator': 'create a decorator that restricts a function to execute only on rank zero in distributed training', 'use_dist_max_reduce': 'use dist_max to compute the maximum value of a scalar across all GPUs in a device mesh', 'use_dist_sum_list_reduce': 'use dist_sum_list to coalesced-sum a list of float values across all ranks in a device mesh', 'use_all_gather_object': 'use all_gather_object to collect arbitrary Python objects from all processes in a process group', 'use_metrics_class': 'use the Metrics class to track sums, maxima, and counts of training metrics across distributed ranks'}
```

