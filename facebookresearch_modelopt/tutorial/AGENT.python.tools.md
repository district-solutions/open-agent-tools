# Agent Python Tools

- repo: facebookresearch/modelopt
- repo_uri: https://github.com/facebookresearch/model_opt

## File: facebookresearch_modelopt/tutorial/_memory_viz.py

Prompts

```
['generate a flamegraph SVG visualizing CUDA memory allocations per allocator segment from a snapshot', 'generate a flamegraph SVG showing program locations contributing to CUDA memory usage from a snapshot', 'compare two CUDA memory snapshots and generate a flamegraph showing segments added or removed', 'print a visual summary of how the CUDA allocator has filled its segments to debug fragmentation', 'generate an HTML visualization over time of CUDA memory usage recorded by a trace']
```

Usage

```
{'generate_segments_flamegraph': 'generate a flamegraph SVG visualizing CUDA memory allocations per allocator segment from a snapshot', 'generate_memory_flamegraph': 'generate a flamegraph SVG showing program locations contributing to CUDA memory usage from a snapshot', 'compare_memory_snapshots': 'compare two CUDA memory snapshots and generate a flamegraph showing segments added or removed', 'print_allocator_stats': 'print a visual summary of how the CUDA allocator has filled its segments to debug fragmentation', 'generate_trace_plot': 'generate an HTML visualization over time of CUDA memory usage recorded by a trace'}
```

