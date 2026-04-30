# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/fx/passes/infra/partitioner.py

Prompts

```
['create a Partition object with an id and a set of graph nodes for grouping', 'build a CapabilityBasedPartitioner with a graph module and operator support to propose partitions', 'test the propose_partitions method to generate a list of node partitions from a graph module', 'refactor the fuse_partitions method to fuse partition nodes into a single GraphModule', 'summarize the partition_and_fuse method to propose and fuse partitions in one call', 'create a PassResult with a graph module and a modified flag', 'build a PassBase subclass that implements the call method for graph transformations', 'run a PassBase instance on a GraphModule to execute requires, call, and ensures', 'test a PassBase subclass requires method to check preconditions on a GraphModule', 'test a PassBase subclass ensures method to verify postconditions on a GraphModule', 'build a PassManager to execute a list of graph transformation passes on a PyTorch GraphModule', 'create a pass_result_wrapper to convert a pass function that returns a module into one returning PassResult', 'run a PassManager with multiple steps until the graph stops changing or the step limit is reached', 'add topological ordering constraints to a PassManager so certain passes execute before others', 'add graph validation checks to a PassManager that run before and after each pass execution']
```

Usage

```
{'create_partition': 'create a Partition object with an id and a set of graph nodes for grouping', 'build_partitioner': 'build a CapabilityBasedPartitioner with a graph module and operator support to propose partitions', 'test_propose_partitions': 'test the propose_partitions method to generate a list of node partitions from a graph module', 'refactor_fuse_partitions': 'refactor the fuse_partitions method to fuse partition nodes into a single GraphModule', 'summarize_partition_and_fuse': 'summarize the partition_and_fuse method to propose and fuse partitions in one call'}
```

## File: pytorch_pytorch/torch/fx/passes/infra/pass_base.py

Prompts

```
['create a Partition object with an id and a set of graph nodes for grouping', 'build a CapabilityBasedPartitioner with a graph module and operator support to propose partitions', 'test the propose_partitions method to generate a list of node partitions from a graph module', 'refactor the fuse_partitions method to fuse partition nodes into a single GraphModule', 'summarize the partition_and_fuse method to propose and fuse partitions in one call', 'create a PassResult with a graph module and a modified flag', 'build a PassBase subclass that implements the call method for graph transformations', 'run a PassBase instance on a GraphModule to execute requires, call, and ensures', 'test a PassBase subclass requires method to check preconditions on a GraphModule', 'test a PassBase subclass ensures method to verify postconditions on a GraphModule', 'build a PassManager to execute a list of graph transformation passes on a PyTorch GraphModule', 'create a pass_result_wrapper to convert a pass function that returns a module into one returning PassResult', 'run a PassManager with multiple steps until the graph stops changing or the step limit is reached', 'add topological ordering constraints to a PassManager so certain passes execute before others', 'add graph validation checks to a PassManager that run before and after each pass execution']
```

Usage

```
{'create_PassResult': 'create a PassResult with a graph module and a modified flag', 'build_PassBase_subclass': 'build a PassBase subclass that implements the call method for graph transformations', 'run_PassBase_call': 'run a PassBase instance on a GraphModule to execute requires, call, and ensures', 'test_PassBase_requires': 'test a PassBase subclass requires method to check preconditions on a GraphModule', 'test_PassBase_ensures': 'test a PassBase subclass ensures method to verify postconditions on a GraphModule'}
```

## File: pytorch_pytorch/torch/fx/passes/infra/pass_manager.py

Prompts

```
['create a Partition object with an id and a set of graph nodes for grouping', 'build a CapabilityBasedPartitioner with a graph module and operator support to propose partitions', 'test the propose_partitions method to generate a list of node partitions from a graph module', 'refactor the fuse_partitions method to fuse partition nodes into a single GraphModule', 'summarize the partition_and_fuse method to propose and fuse partitions in one call', 'create a PassResult with a graph module and a modified flag', 'build a PassBase subclass that implements the call method for graph transformations', 'run a PassBase instance on a GraphModule to execute requires, call, and ensures', 'test a PassBase subclass requires method to check preconditions on a GraphModule', 'test a PassBase subclass ensures method to verify postconditions on a GraphModule', 'build a PassManager to execute a list of graph transformation passes on a PyTorch GraphModule', 'create a pass_result_wrapper to convert a pass function that returns a module into one returning PassResult', 'run a PassManager with multiple steps until the graph stops changing or the step limit is reached', 'add topological ordering constraints to a PassManager so certain passes execute before others', 'add graph validation checks to a PassManager that run before and after each pass execution']
```

Usage

```
{'build_pass_manager': 'build a PassManager to execute a list of graph transformation passes on a PyTorch GraphModule', 'create_pass_result_wrapper': 'create a pass_result_wrapper to convert a pass function that returns a module into one returning PassResult', 'run_pass_manager_steps': 'run a PassManager with multiple steps until the graph stops changing or the step limit is reached', 'add_topological_constraints': 'add topological ordering constraints to a PassManager so certain passes execute before others', 'add_graph_checks': 'add graph validation checks to a PassManager that run before and after each pass execution'}
```

