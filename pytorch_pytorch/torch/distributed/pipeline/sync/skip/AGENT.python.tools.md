# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/pipeline/sync/skip/layout.py

Prompts

```
['build a SkipLayout instance from partitioned nn.Sequential modules using skip_routes mapping', 'create an inspect_skip_layout call that analyzes partitions and returns skip connection routes', 'test the copy_policy method to determine which skip tensors require cross-partition copy', 'review the requires_copy method to check if a namespace and name needs partition-to-partition copy', 'summarize the SkipLayout class and its by_ns_name and by_partition indexing structures', 'create a Portal instance to store a tensor with a limited number of retrievals before automatic deallocation', 'build a PortalBlue autograd function to hide a tensor from the autograd engine while preserving backpropagation', 'run a PortalOrange autograd function to retrieve a hidden tensor from a Portal without losing backpropagation', 'test a PortalCopy autograd function to copy a hidden tensor across CUDA streams using a phony tensor', 'refactor the Portal use_tensor method to retrieve a tensor and decrement its remaining life count', 'create a skippable PyTorch module with stash and pop skip connections using the @skippable decorator', 'build skip connections between layers using stash to store and pop to retrieve tensors across modules', 'test a PyTorch Sequential module to verify all stash and pop skip connections are properly matched', 'refactor skippable modules to isolate skip tensors with the same name using different namespaces via isolate()', 'review the Skippable class forward and dispatch methods for handling stash and pop command generators', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'build a SkipTrackerThroughPortals to track skip tensors through portals for torchpipe.Pipe wrapped modules', 'test the use_skip_tracker context manager to register a skip tracker on the current thread', 'refactor SkipTracker save and load methods to manage skip tensors with namespace and name keys', 'review the current_skip_tracker function to get or create the skip tracker on the current thread']
```

Usage

```
{'build_skip_layout': 'build a SkipLayout instance from partitioned nn.Sequential modules using skip_routes mapping', 'create_inspect_skip_layout': 'create an inspect_skip_layout call that analyzes partitions and returns skip connection routes', 'test_copy_policy': 'test the copy_policy method to determine which skip tensors require cross-partition copy', 'review_requires_copy': 'review the requires_copy method to check if a namespace and name needs partition-to-partition copy', 'summarize_skip_layout': 'summarize the SkipLayout class and its by_ns_name and by_partition indexing structures'}
```

## File: pytorch_pytorch/torch/distributed/pipeline/sync/skip/portal.py

Prompts

```
['build a SkipLayout instance from partitioned nn.Sequential modules using skip_routes mapping', 'create an inspect_skip_layout call that analyzes partitions and returns skip connection routes', 'test the copy_policy method to determine which skip tensors require cross-partition copy', 'review the requires_copy method to check if a namespace and name needs partition-to-partition copy', 'summarize the SkipLayout class and its by_ns_name and by_partition indexing structures', 'create a Portal instance to store a tensor with a limited number of retrievals before automatic deallocation', 'build a PortalBlue autograd function to hide a tensor from the autograd engine while preserving backpropagation', 'run a PortalOrange autograd function to retrieve a hidden tensor from a Portal without losing backpropagation', 'test a PortalCopy autograd function to copy a hidden tensor across CUDA streams using a phony tensor', 'refactor the Portal use_tensor method to retrieve a tensor and decrement its remaining life count', 'create a skippable PyTorch module with stash and pop skip connections using the @skippable decorator', 'build skip connections between layers using stash to store and pop to retrieve tensors across modules', 'test a PyTorch Sequential module to verify all stash and pop skip connections are properly matched', 'refactor skippable modules to isolate skip tensors with the same name using different namespaces via isolate()', 'review the Skippable class forward and dispatch methods for handling stash and pop command generators', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'build a SkipTrackerThroughPortals to track skip tensors through portals for torchpipe.Pipe wrapped modules', 'test the use_skip_tracker context manager to register a skip tracker on the current thread', 'refactor SkipTracker save and load methods to manage skip tensors with namespace and name keys', 'review the current_skip_tracker function to get or create the skip tracker on the current thread']
```

Usage

```
{'create_Portal': 'create a Portal instance to store a tensor with a limited number of retrievals before automatic deallocation', 'build_PortalBlue': 'build a PortalBlue autograd function to hide a tensor from the autograd engine while preserving backpropagation', 'run_PortalOrange': 'run a PortalOrange autograd function to retrieve a hidden tensor from a Portal without losing backpropagation', 'test_PortalCopy': 'test a PortalCopy autograd function to copy a hidden tensor across CUDA streams using a phony tensor', 'refactor_Portal_use_tensor': 'refactor the Portal use_tensor method to retrieve a tensor and decrement its remaining life count'}
```

## File: pytorch_pytorch/torch/distributed/pipeline/sync/skip/skippable.py

Prompts

```
['build a SkipLayout instance from partitioned nn.Sequential modules using skip_routes mapping', 'create an inspect_skip_layout call that analyzes partitions and returns skip connection routes', 'test the copy_policy method to determine which skip tensors require cross-partition copy', 'review the requires_copy method to check if a namespace and name needs partition-to-partition copy', 'summarize the SkipLayout class and its by_ns_name and by_partition indexing structures', 'create a Portal instance to store a tensor with a limited number of retrievals before automatic deallocation', 'build a PortalBlue autograd function to hide a tensor from the autograd engine while preserving backpropagation', 'run a PortalOrange autograd function to retrieve a hidden tensor from a Portal without losing backpropagation', 'test a PortalCopy autograd function to copy a hidden tensor across CUDA streams using a phony tensor', 'refactor the Portal use_tensor method to retrieve a tensor and decrement its remaining life count', 'create a skippable PyTorch module with stash and pop skip connections using the @skippable decorator', 'build skip connections between layers using stash to store and pop to retrieve tensors across modules', 'test a PyTorch Sequential module to verify all stash and pop skip connections are properly matched', 'refactor skippable modules to isolate skip tensors with the same name using different namespaces via isolate()', 'review the Skippable class forward and dispatch methods for handling stash and pop command generators', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'build a SkipTrackerThroughPortals to track skip tensors through portals for torchpipe.Pipe wrapped modules', 'test the use_skip_tracker context manager to register a skip tracker on the current thread', 'refactor SkipTracker save and load methods to manage skip tensors with namespace and name keys', 'review the current_skip_tracker function to get or create the skip tracker on the current thread']
```

Usage

```
{'create_skippable_module': 'create a skippable PyTorch module with stash and pop skip connections using the @skippable decorator', 'build_skip_connection_stash_pop': 'build skip connections between layers using stash to store and pop to retrieve tensors across modules', 'test_verify_skippables': 'test a PyTorch Sequential module to verify all stash and pop skip connections are properly matched', 'refactor_isolate_skip_namespaces': 'refactor skippable modules to isolate skip tensors with the same name using different namespaces via isolate()', 'review_skippable_forward_dispatch': 'review the Skippable class forward and dispatch methods for handling stash and pop command generators'}
```

## File: pytorch_pytorch/torch/distributed/pipeline/sync/skip/tracker.py

Prompts

```
['build a SkipLayout instance from partitioned nn.Sequential modules using skip_routes mapping', 'create an inspect_skip_layout call that analyzes partitions and returns skip connection routes', 'test the copy_policy method to determine which skip tensors require cross-partition copy', 'review the requires_copy method to check if a namespace and name needs partition-to-partition copy', 'summarize the SkipLayout class and its by_ns_name and by_partition indexing structures', 'create a Portal instance to store a tensor with a limited number of retrievals before automatic deallocation', 'build a PortalBlue autograd function to hide a tensor from the autograd engine while preserving backpropagation', 'run a PortalOrange autograd function to retrieve a hidden tensor from a Portal without losing backpropagation', 'test a PortalCopy autograd function to copy a hidden tensor across CUDA streams using a phony tensor', 'refactor the Portal use_tensor method to retrieve a tensor and decrement its remaining life count', 'create a skippable PyTorch module with stash and pop skip connections using the @skippable decorator', 'build skip connections between layers using stash to store and pop to retrieve tensors across modules', 'test a PyTorch Sequential module to verify all stash and pop skip connections are properly matched', 'refactor skippable modules to isolate skip tensors with the same name using different namespaces via isolate()', 'review the Skippable class forward and dispatch methods for handling stash and pop command generators', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'build a SkipTrackerThroughPortals to track skip tensors through portals for torchpipe.Pipe wrapped modules', 'test the use_skip_tracker context manager to register a skip tracker on the current thread', 'refactor SkipTracker save and load methods to manage skip tensors with namespace and name keys', 'review the current_skip_tracker function to get or create the skip tracker on the current thread']
```

Usage

```
{'create_SkipTracker': 'create a SkipTracker instance to track saved skip tensors on the current thread', 'build_SkipTrackerThroughPotals': 'build a SkipTrackerThroughPortals to track skip tensors through portals for torchpipe.Pipe wrapped modules', 'test_use_skip_tracker': 'test the use_skip_tracker context manager to register a skip tracker on the current thread', 'refactor_SkipTracker_save_load': 'refactor SkipTracker save and load methods to manage skip tensors with namespace and name keys', 'review_current_skip_tracker': 'review the current_skip_tracker function to get or create the skip tracker on the current thread'}
```

