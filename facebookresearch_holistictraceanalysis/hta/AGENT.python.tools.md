# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/hta/memory_analysis.py

Prompts

```
['create a MemoryAnalysis instance from a gzipped memory trace file path', 'process raw memory events from a gzipped trace into timestamps and per-category byte sizes', 'generate a stacked area plot of memory usage over time across categories like parameters and activations', 'save the memory timeline plot as a PNG image to the images directory', 'review the Category enum that defines memory types like INPUT, TEMPORARY, ACTIVATION, GRADIENT, and PARAMETER', 'build a python module to analyze GPU kernel time breakdown and visualize top time-consuming kernels per rank', 'build a python module to detect potential straggler ranks in distributed training from a PyTorch profiler trace', 'build a python module to perform critical path analysis on GPU kernels within a specific profiler step', 'build a python module to break down GPU idle time into host wait, kernel wait, and other wait categories', 'build a python module to compute the communication-computation overlap percentage for each rank in a distributed training trace', 'compare operator counts and total duration between two PyTorch profiler traces', 'get added, deleted, increased, decreased, and unchanged operators between two traces', 'visualize operator count differences between two traces as a grouped bar chart', 'visualize operator duration differences between two traces as a grouped bar chart', 'extract operators or kernels from a labeled trace filtered by rank, iteration, and device type']
```

Usage

```
{'create_memory_analysis': 'create a MemoryAnalysis instance from a gzipped memory trace file path', 'process_raw_events': 'process raw memory events from a gzipped trace into timestamps and per-category byte sizes', 'plot_memory_timeline': 'generate a stacked area plot of memory usage over time across categories like parameters and activations', 'save_memory_plot': 'save the memory timeline plot as a PNG image to the images directory', 'review_Category_enum': 'review the Category enum that defines memory types like INPUT, TEMPORARY, ACTIVATION, GRADIENT, and PARAMETER'}
```

## File: facebookresearch_holistictraceanalysis/hta/trace_analysis.py

Prompts

```
['create a MemoryAnalysis instance from a gzipped memory trace file path', 'process raw memory events from a gzipped trace into timestamps and per-category byte sizes', 'generate a stacked area plot of memory usage over time across categories like parameters and activations', 'save the memory timeline plot as a PNG image to the images directory', 'review the Category enum that defines memory types like INPUT, TEMPORARY, ACTIVATION, GRADIENT, and PARAMETER', 'build a python module to analyze GPU kernel time breakdown and visualize top time-consuming kernels per rank', 'build a python module to detect potential straggler ranks in distributed training from a PyTorch profiler trace', 'build a python module to perform critical path analysis on GPU kernels within a specific profiler step', 'build a python module to break down GPU idle time into host wait, kernel wait, and other wait categories', 'build a python module to compute the communication-computation overlap percentage for each rank in a distributed training trace', 'compare operator counts and total duration between two PyTorch profiler traces', 'get added, deleted, increased, decreased, and unchanged operators between two traces', 'visualize operator count differences between two traces as a grouped bar chart', 'visualize operator duration differences between two traces as a grouped bar chart', 'extract operators or kernels from a labeled trace filtered by rank, iteration, and device type']
```

Usage

```
{'analyze_gpu_kernel_breakdown': 'build a python module to analyze GPU kernel time breakdown and visualize top time-consuming kernels per rank', 'detect_potential_stragglers': 'build a python module to detect potential straggler ranks in distributed training from a PyTorch profiler trace', 'run_critical_path_analysis': 'build a python module to perform critical path analysis on GPU kernels within a specific profiler step', 'analyze_gpu_idle_time': 'build a python module to break down GPU idle time into host wait, kernel wait, and other wait categories', 'compute_comm_comp_overlap': 'build a python module to compute the communication-computation overlap percentage for each rank in a distributed training trace'}
```

## File: facebookresearch_holistictraceanalysis/hta/trace_diff.py

Prompts

```
['create a MemoryAnalysis instance from a gzipped memory trace file path', 'process raw memory events from a gzipped trace into timestamps and per-category byte sizes', 'generate a stacked area plot of memory usage over time across categories like parameters and activations', 'save the memory timeline plot as a PNG image to the images directory', 'review the Category enum that defines memory types like INPUT, TEMPORARY, ACTIVATION, GRADIENT, and PARAMETER', 'build a python module to analyze GPU kernel time breakdown and visualize top time-consuming kernels per rank', 'build a python module to detect potential straggler ranks in distributed training from a PyTorch profiler trace', 'build a python module to perform critical path analysis on GPU kernels within a specific profiler step', 'build a python module to break down GPU idle time into host wait, kernel wait, and other wait categories', 'build a python module to compute the communication-computation overlap percentage for each rank in a distributed training trace', 'compare operator counts and total duration between two PyTorch profiler traces', 'get added, deleted, increased, decreased, and unchanged operators between two traces', 'visualize operator count differences between two traces as a grouped bar chart', 'visualize operator duration differences between two traces as a grouped bar chart', 'extract operators or kernels from a labeled trace filtered by rank, iteration, and device type']
```

Usage

```
{'compare_traces': 'compare operator counts and total duration between two PyTorch profiler traces', 'ops_diff': 'get added, deleted, increased, decreased, and unchanged operators between two traces', 'visualize_counts_diff': 'visualize operator count differences between two traces as a grouped bar chart', 'visualize_duration_diff': 'visualize operator duration differences between two traces as a grouped bar chart', 'extract_ops': 'extract operators or kernels from a labeled trace filtered by rank, iteration, and device type'}
```

