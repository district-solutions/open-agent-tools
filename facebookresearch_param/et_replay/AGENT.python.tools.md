# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/et_replay_utils.py

Prompts

```
["build a TorchScript function from an execution trace node's op schema and input/output types", 'build a compiled Triton kernel function from source code and an async compiler', "check if a node's input or output at a given index is a single Tensor type", 'check if an execution trace node is an operator node with optional strict parent validation', 'import a list of third party Python modules by name and raise on failure', 'parse a PyTorch execution trace JSON file and build an ExecutionTrace object with nodes and tensors', 'list all unique operators in an execution trace with their counts and input shapes', 'list all tensors in an execution trace with their data types and shapes', 'generate a GraphML or GraphViz SVG graph visualization of the execution trace', 'query a specific node or tensor by ID to show its input and output dependencies', 'load an execution trace from a JSON or gzipped JSON file into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a Python dictionary', 'write a Python dictionary to a JSON or gzipped JSON file with pretty formatting', 'generate a unique temporary trace filename using the current date, a UUID, and the process ID', 'export a Chrome profiling trace to a temporary JSON file using a profiler object']
```

Usage

```
{'build_torchscript_func': "build a TorchScript function from an execution trace node's op schema and input/output types", 'build_triton_func': 'build a compiled Triton kernel function from source code and an async compiler', 'is_tensor': "check if a node's input or output at a given index is a single Tensor type", 'is_op': 'check if an execution trace node is an operator node with optional strict parent validation', 'import_third_party_modules': 'import a list of third party Python modules by name and raise on failure'}
```

## File: facebookresearch_param/et_replay/execution_trace.py

Prompts

```
["build a TorchScript function from an execution trace node's op schema and input/output types", 'build a compiled Triton kernel function from source code and an async compiler', "check if a node's input or output at a given index is a single Tensor type", 'check if an execution trace node is an operator node with optional strict parent validation', 'import a list of third party Python modules by name and raise on failure', 'parse a PyTorch execution trace JSON file and build an ExecutionTrace object with nodes and tensors', 'list all unique operators in an execution trace with their counts and input shapes', 'list all tensors in an execution trace with their data types and shapes', 'generate a GraphML or GraphViz SVG graph visualization of the execution trace', 'query a specific node or tensor by ID to show its input and output dependencies', 'load an execution trace from a JSON or gzipped JSON file into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a Python dictionary', 'write a Python dictionary to a JSON or gzipped JSON file with pretty formatting', 'generate a unique temporary trace filename using the current date, a UUID, and the process ID', 'export a Chrome profiling trace to a temporary JSON file using a profiler object']
```

Usage

```
{'parse_execution_trace': 'parse a PyTorch execution trace JSON file and build an ExecutionTrace object with nodes and tensors', 'list_ops_in_trace': 'list all unique operators in an execution trace with their counts and input shapes', 'list_tensors_in_trace': 'list all tensors in an execution trace with their data types and shapes', 'generate_trace_graph': 'generate a GraphML or GraphViz SVG graph visualization of the execution trace', 'query_node_dependencies': 'query a specific node or tensor by ID to show its input and output dependencies'}
```

## File: facebookresearch_param/et_replay/utils.py

Prompts

```
["build a TorchScript function from an execution trace node's op schema and input/output types", 'build a compiled Triton kernel function from source code and an async compiler', "check if a node's input or output at a given index is a single Tensor type", 'check if an execution trace node is an operator node with optional strict parent validation', 'import a list of third party Python modules by name and raise on failure', 'parse a PyTorch execution trace JSON file and build an ExecutionTrace object with nodes and tensors', 'list all unique operators in an execution trace with their counts and input shapes', 'list all tensors in an execution trace with their data types and shapes', 'generate a GraphML or GraphViz SVG graph visualization of the execution trace', 'query a specific node or tensor by ID to show its input and output dependencies', 'load an execution trace from a JSON or gzipped JSON file into an ExecutionTrace object', 'read a JSON or gzipped JSON file and return its contents as a Python dictionary', 'write a Python dictionary to a JSON or gzipped JSON file with pretty formatting', 'generate a unique temporary trace filename using the current date, a UUID, and the process ID', 'export a Chrome profiling trace to a temporary JSON file using a profiler object']
```

Usage

```
{'load_execution_trace': 'load an execution trace from a JSON or gzipped JSON file into an ExecutionTrace object', 'read_json_file': 'read a JSON or gzipped JSON file and return its contents as a Python dictionary', 'write_json_file': 'write a Python dictionary to a JSON or gzipped JSON file with pretty formatting', 'generate_trace_filename': 'generate a unique temporary trace filename using the current date, a UUID, and the process ID', 'export_chrome_trace': 'export a Chrome profiling trace to a temporary JSON file using a profiler object'}
```

