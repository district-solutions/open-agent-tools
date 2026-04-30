# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_tensor/experimental/tp_transform.py

Prompts

```
['transform an exported program into a tensor parallel graph using rank, world size, and parallel strategies', 'run the tensor parallel transform pass on a graph module to mark sharding and partition the graph', 'build parameter and buffer placements from a list of parameter names and parallel strategies', 'mark sharding strategies for each node in a graph module based on parameter placements and device mesh', 'partition a single-device graph into a distributed graph by inserting reshard operations where needed']
```

Usage

```
{'transform_exported_program_tensor_parallel': 'transform an exported program into a tensor parallel graph using rank, world size, and parallel strategies', 'run_tensor_parallel_transform_pass': 'run the tensor parallel transform pass on a graph module to mark sharding and partition the graph', 'build_parameter_buffer_placements': 'build parameter and buffer placements from a list of parameter names and parallel strategies', 'mark_graph_node_sharding': 'mark sharding strategies for each node in a graph module based on parameter placements and device mesh', 'partition_single_device_graph': 'partition a single-device graph into a distributed graph by inserting reshard operations where needed'}
```

