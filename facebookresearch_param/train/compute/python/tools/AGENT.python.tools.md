# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/compute/python/tools/nsys_analysis.py

Prompts

```
['run the nsys_analysis tool to parse an nsys sqlite file and output operator event analysis as JSON', 'parse CUDA kernel events from nsys sqlite query results into OperatorEvent objects with timing data', 'parse CUDA sync events from nsys sqlite query results into OperatorEvent objects with timing data', 'analyze OperatorEvent objects to compute T1 through T5 timing metrics for each operator range', 'find overlapping time intervals between two lists of start-end interval pairs']
```

Usage

```
{'run_nsys_analysis': 'run the nsys_analysis tool to parse an nsys sqlite file and output operator event analysis as JSON', 'parse_kernel_events': 'parse CUDA kernel events from nsys sqlite query results into OperatorEvent objects with timing data', 'parse_sync_events': 'parse CUDA sync events from nsys sqlite query results into OperatorEvent objects with timing data', 'analyze_events': 'analyze OperatorEvent objects to compute T1 through T5 timing metrics for each operator range', 'find_overlap_intervals': 'find overlapping time intervals between two lists of start-end interval pairs'}
```

