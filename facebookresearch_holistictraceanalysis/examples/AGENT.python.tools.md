# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/examples/cupti_profiler_demo.py

Prompts

```
['run the train_xor function to train an XOR neural network with CUPTI GPU profiling enabled', 'create an Xor neural network module with two linear layers for binary XOR classification', 'configure torch.profiler.profile with CUPTI metrics like tensor_core_insts and dram bytes read and write', 'export the profiler results to a Chrome trace JSON file using export_chrome_trace', 'summarize the _ExperimentalConfig class used to set profiler_metrics and profiler_measure_per_kernel options', 'run the symbol table demo to analyze kernel statistics across GPU ranks in a trace directory', 'load and parse traces from a directory using multiprocessing for up to a specified number of ranks', 'compute top-k kernel duration statistics including sum, max, min, mean, std, count, and percent of total time', 'visualize kernel duration data as a bar chart or print a formatted summary table to logs', 'inspect trace dataframe info including event counts, categories, and streams for a given rank']
```

Usage

```
{'run_train_xor': 'run the train_xor function to train an XOR neural network with CUPTI GPU profiling enabled', 'create_Xor_model': 'create an Xor neural network module with two linear layers for binary XOR classification', 'configure_cupti_profiler': 'configure torch.profiler.profile with CUPTI metrics like tensor_core_insts and dram bytes read and write', 'export_chrome_trace': 'export the profiler results to a Chrome trace JSON file using export_chrome_trace', 'summarize_ExperimentalConfig': 'summarize the _ExperimentalConfig class used to set profiler_metrics and profiler_measure_per_kernel options'}
```

## File: facebookresearch_holistictraceanalysis/examples/symbol_table_demo.py

Prompts

```
['run the train_xor function to train an XOR neural network with CUPTI GPU profiling enabled', 'create an Xor neural network module with two linear layers for binary XOR classification', 'configure torch.profiler.profile with CUPTI metrics like tensor_core_insts and dram bytes read and write', 'export the profiler results to a Chrome trace JSON file using export_chrome_trace', 'summarize the _ExperimentalConfig class used to set profiler_metrics and profiler_measure_per_kernel options', 'run the symbol table demo to analyze kernel statistics across GPU ranks in a trace directory', 'load and parse traces from a directory using multiprocessing for up to a specified number of ranks', 'compute top-k kernel duration statistics including sum, max, min, mean, std, count, and percent of total time', 'visualize kernel duration data as a bar chart or print a formatted summary table to logs', 'inspect trace dataframe info including event counts, categories, and streams for a given rank']
```

Usage

```
{'run_trace_analysis_demo': 'run the symbol table demo to analyze kernel statistics across GPU ranks in a trace directory', 'load_trace_from_directory': 'load and parse traces from a directory using multiprocessing for up to a specified number of ranks', 'compute_kernel_statistics': 'compute top-k kernel duration statistics including sum, max, min, mean, std, count, and percent of total time', 'visualize_kernel_data': 'visualize kernel duration data as a bar chart or print a formatted summary table to logs', 'inspect_trace_info': 'inspect trace dataframe info including event counts, categories, and streams for a given rank'}
```

