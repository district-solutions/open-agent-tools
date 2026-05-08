# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/et_replay_utils.py

Prompts

```
['build an fbgemm embedding lookup operation from an execution trace node for a given device and rows per table', 'generate input tensors and kwargs for an fbgemm forward operation using a data generator config', "build a TorchScript function from an execution trace node's op schema and input/output types", 'generate a Python script prefix for replaying execution trace operators with fbgemm and TorchScript functions', 'generate a Python script suffix for running warmup and replay iterations with optional CUDA profiling', 'run the execution trace CLI to list ops, tensors, or generate graphs from a PyTorch trace JSON file', 'build an ExecutionTrace object from a PyTorch profiler JSON file to analyze nodes, tensors, and operator statistics', 'generate a Graphviz SVG or GraphML file visualizing the execution trace node and tensor dependency graph', 'query a specific node or tensor ID to print its input and output tensor dependencies in the execution trace', 'clone one training iteration from a multi-iteration execution trace to isolate and analyze a single step', 'generate a temporary trace filename using the current date, a UUID, and the process ID', 'export a chrome trace from a profiler object to a temporary JSON file', 'load an execution trace from a JSON file and parse it into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a dictionary', 'write a dictionary to a JSON or gzipped JSON file with pretty-printed indentation']
```

Usage

```
{'build_fbgemm_func': 'build an fbgemm embedding lookup operation from an execution trace node for a given device and rows per table', 'generate_fbgemm_tensors': 'generate input tensors and kwargs for an fbgemm forward operation using a data generator config', 'build_torchscript_func': "build a TorchScript function from an execution trace node's op schema and input/output types", 'generate_prefix': 'generate a Python script prefix for replaying execution trace operators with fbgemm and TorchScript functions', 'generate_suffix': 'generate a Python script suffix for running warmup and replay iterations with optional CUDA profiling'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/execution_trace.py

Prompts

```
['build an fbgemm embedding lookup operation from an execution trace node for a given device and rows per table', 'generate input tensors and kwargs for an fbgemm forward operation using a data generator config', "build a TorchScript function from an execution trace node's op schema and input/output types", 'generate a Python script prefix for replaying execution trace operators with fbgemm and TorchScript functions', 'generate a Python script suffix for running warmup and replay iterations with optional CUDA profiling', 'run the execution trace CLI to list ops, tensors, or generate graphs from a PyTorch trace JSON file', 'build an ExecutionTrace object from a PyTorch profiler JSON file to analyze nodes, tensors, and operator statistics', 'generate a Graphviz SVG or GraphML file visualizing the execution trace node and tensor dependency graph', 'query a specific node or tensor ID to print its input and output tensor dependencies in the execution trace', 'clone one training iteration from a multi-iteration execution trace to isolate and analyze a single step', 'generate a temporary trace filename using the current date, a UUID, and the process ID', 'export a chrome trace from a profiler object to a temporary JSON file', 'load an execution trace from a JSON file and parse it into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a dictionary', 'write a dictionary to a JSON or gzipped JSON file with pretty-printed indentation']
```

Usage

```
{'run_execution_trace_analysis': 'run the execution trace CLI to list ops, tensors, or generate graphs from a PyTorch trace JSON file', 'build_execution_trace_from_json': 'build an ExecutionTrace object from a PyTorch profiler JSON file to analyze nodes, tensors, and operator statistics', 'generate_graphviz_or_graphml': 'generate a Graphviz SVG or GraphML file visualizing the execution trace node and tensor dependency graph', 'query_node_dependencies': 'query a specific node or tensor ID to print its input and output tensor dependencies in the execution trace', 'clone_single_iteration': 'clone one training iteration from a multi-iteration execution trace to isolate and analyze a single step'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/utils.py

Prompts

```
['build an fbgemm embedding lookup operation from an execution trace node for a given device and rows per table', 'generate input tensors and kwargs for an fbgemm forward operation using a data generator config', "build a TorchScript function from an execution trace node's op schema and input/output types", 'generate a Python script prefix for replaying execution trace operators with fbgemm and TorchScript functions', 'generate a Python script suffix for running warmup and replay iterations with optional CUDA profiling', 'run the execution trace CLI to list ops, tensors, or generate graphs from a PyTorch trace JSON file', 'build an ExecutionTrace object from a PyTorch profiler JSON file to analyze nodes, tensors, and operator statistics', 'generate a Graphviz SVG or GraphML file visualizing the execution trace node and tensor dependency graph', 'query a specific node or tensor ID to print its input and output tensor dependencies in the execution trace', 'clone one training iteration from a multi-iteration execution trace to isolate and analyze a single step', 'generate a temporary trace filename using the current date, a UUID, and the process ID', 'export a chrome trace from a profiler object to a temporary JSON file', 'load an execution trace from a JSON file and parse it into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a dictionary', 'write a dictionary to a JSON or gzipped JSON file with pretty-printed indentation']
```

Usage

```
{'generate_tmp_trace_filename': 'generate a temporary trace filename using the current date, a UUID, and the process ID', 'export_chrome_trace': 'export a chrome trace from a profiler object to a temporary JSON file', 'load_execution_trace': 'load an execution trace from a JSON file and parse it into an ExecutionTrace object', 'read_json_file': 'read a JSON or gzipped JSON file and return its contents as a dictionary', 'write_json_file': 'write a dictionary to a JSON or gzipped JSON file with pretty-printed indentation'}
```

