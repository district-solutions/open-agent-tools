# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/pipe/skip/layout.py

Prompts

```
['build a SkipLayout object from skip routes dict and number of partitions', 'inspect skip connection layout across a list of nn.Sequential partition modules', 'generate skip copy routes for a destination partition using SkipLayout copy_policy method', 'generate skip copy routes from a source partition using SkipLayout copy_policy_by_src method', 'review whether a skip connection requires partition-to-partition copy using SkipLayout requires_copy method', 'create a Portal instance to store a tensor with a specified life count and index', 'use Portal blue method to hide a tensor from the autograd engine and return a phony', 'use Portal orange method to retrieve a hidden tensor without losing backpropagation ability', 'use Portal copy method to copy a hidden tensor between two streams with backpropagation', 'review the PortalBlue, PortalOrange, and PortalCopy autograd functions for skip connection tensor handling', 'use the skippable decorator to define a PyTorch module with named stash and pop skip connections', 'yield a stash command to save a named skip tensor for later use by downstream layers', 'yield a pop command to retrieve a previously stashed skip tensor by its declared name', 'call isolate on a skippable module to assign skip tensors to a Namespace for reuse without conflict', 'run verify_skippables on an nn.Sequential module to check all stash and pop pairs are matched', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'create a SkipTrackerThroughPortals instance with a SkipLayout and index to track skip tensors through portals', 'use the use_skip_tracker context manager to register a skip tracker on the current thread', 'get the current skip tracker on the current thread using current_skip_tracker function', 'save a skip tensor with SkipTracker.save and retrieve it with SkipTracker.load using namespace and name']
```

Usage

```
{'build_skip_layout': 'build a SkipLayout object from skip routes dict and number of partitions', 'inspect_skip_layout_partitions': 'inspect skip connection layout across a list of nn.Sequential partition modules', 'copy_policy_by_dest': 'generate skip copy routes for a destination partition using SkipLayout copy_policy method', 'copy_policy_by_src': 'generate skip copy routes from a source partition using SkipLayout copy_policy_by_src method', 'review_requires_copy': 'review whether a skip connection requires partition-to-partition copy using SkipLayout requires_copy method'}
```

## File: facebookresearch_fairscale/fairscale/nn/pipe/skip/portal.py

Prompts

```
['build a SkipLayout object from skip routes dict and number of partitions', 'inspect skip connection layout across a list of nn.Sequential partition modules', 'generate skip copy routes for a destination partition using SkipLayout copy_policy method', 'generate skip copy routes from a source partition using SkipLayout copy_policy_by_src method', 'review whether a skip connection requires partition-to-partition copy using SkipLayout requires_copy method', 'create a Portal instance to store a tensor with a specified life count and index', 'use Portal blue method to hide a tensor from the autograd engine and return a phony', 'use Portal orange method to retrieve a hidden tensor without losing backpropagation ability', 'use Portal copy method to copy a hidden tensor between two streams with backpropagation', 'review the PortalBlue, PortalOrange, and PortalCopy autograd functions for skip connection tensor handling', 'use the skippable decorator to define a PyTorch module with named stash and pop skip connections', 'yield a stash command to save a named skip tensor for later use by downstream layers', 'yield a pop command to retrieve a previously stashed skip tensor by its declared name', 'call isolate on a skippable module to assign skip tensors to a Namespace for reuse without conflict', 'run verify_skippables on an nn.Sequential module to check all stash and pop pairs are matched', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'create a SkipTrackerThroughPortals instance with a SkipLayout and index to track skip tensors through portals', 'use the use_skip_tracker context manager to register a skip tracker on the current thread', 'get the current skip tracker on the current thread using current_skip_tracker function', 'save a skip tensor with SkipTracker.save and retrieve it with SkipTracker.load using namespace and name']
```

Usage

```
{'create_Portal': 'create a Portal instance to store a tensor with a specified life count and index', 'use_Portal_blue': 'use Portal blue method to hide a tensor from the autograd engine and return a phony', 'use_Portal_orange': 'use Portal orange method to retrieve a hidden tensor without losing backpropagation ability', 'use_Portal_copy': 'use Portal copy method to copy a hidden tensor between two streams with backpropagation', 'review_PortalBlue_PortalOrange_PortalCopy': 'review the PortalBlue, PortalOrange, and PortalCopy autograd functions for skip connection tensor handling'}
```

## File: facebookresearch_fairscale/fairscale/nn/pipe/skip/skippable.py

Prompts

```
['build a SkipLayout object from skip routes dict and number of partitions', 'inspect skip connection layout across a list of nn.Sequential partition modules', 'generate skip copy routes for a destination partition using SkipLayout copy_policy method', 'generate skip copy routes from a source partition using SkipLayout copy_policy_by_src method', 'review whether a skip connection requires partition-to-partition copy using SkipLayout requires_copy method', 'create a Portal instance to store a tensor with a specified life count and index', 'use Portal blue method to hide a tensor from the autograd engine and return a phony', 'use Portal orange method to retrieve a hidden tensor without losing backpropagation ability', 'use Portal copy method to copy a hidden tensor between two streams with backpropagation', 'review the PortalBlue, PortalOrange, and PortalCopy autograd functions for skip connection tensor handling', 'use the skippable decorator to define a PyTorch module with named stash and pop skip connections', 'yield a stash command to save a named skip tensor for later use by downstream layers', 'yield a pop command to retrieve a previously stashed skip tensor by its declared name', 'call isolate on a skippable module to assign skip tensors to a Namespace for reuse without conflict', 'run verify_skippables on an nn.Sequential module to check all stash and pop pairs are matched', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'create a SkipTrackerThroughPortals instance with a SkipLayout and index to track skip tensors through portals', 'use the use_skip_tracker context manager to register a skip tracker on the current thread', 'get the current skip tracker on the current thread using current_skip_tracker function', 'save a skip tensor with SkipTracker.save and retrieve it with SkipTracker.load using namespace and name']
```

Usage

```
{'define_skippable_module': 'use the skippable decorator to define a PyTorch module with named stash and pop skip connections', 'stash_skip_tensor': 'yield a stash command to save a named skip tensor for later use by downstream layers', 'pop_skip_tensor': 'yield a pop command to retrieve a previously stashed skip tensor by its declared name', 'isolate_skip_namespace': 'call isolate on a skippable module to assign skip tensors to a Namespace for reuse without conflict', 'verify_skippables_integrity': 'run verify_skippables on an nn.Sequential module to check all stash and pop pairs are matched'}
```

## File: facebookresearch_fairscale/fairscale/nn/pipe/skip/tracker.py

Prompts

```
['build a SkipLayout object from skip routes dict and number of partitions', 'inspect skip connection layout across a list of nn.Sequential partition modules', 'generate skip copy routes for a destination partition using SkipLayout copy_policy method', 'generate skip copy routes from a source partition using SkipLayout copy_policy_by_src method', 'review whether a skip connection requires partition-to-partition copy using SkipLayout requires_copy method', 'create a Portal instance to store a tensor with a specified life count and index', 'use Portal blue method to hide a tensor from the autograd engine and return a phony', 'use Portal orange method to retrieve a hidden tensor without losing backpropagation ability', 'use Portal copy method to copy a hidden tensor between two streams with backpropagation', 'review the PortalBlue, PortalOrange, and PortalCopy autograd functions for skip connection tensor handling', 'use the skippable decorator to define a PyTorch module with named stash and pop skip connections', 'yield a stash command to save a named skip tensor for later use by downstream layers', 'yield a pop command to retrieve a previously stashed skip tensor by its declared name', 'call isolate on a skippable module to assign skip tensors to a Namespace for reuse without conflict', 'run verify_skippables on an nn.Sequential module to check all stash and pop pairs are matched', 'create a SkipTracker instance to track saved skip tensors on the current thread', 'create a SkipTrackerThroughPortals instance with a SkipLayout and index to track skip tensors through portals', 'use the use_skip_tracker context manager to register a skip tracker on the current thread', 'get the current skip tracker on the current thread using current_skip_tracker function', 'save a skip tensor with SkipTracker.save and retrieve it with SkipTracker.load using namespace and name']
```

Usage

```
{'create_SkipTracker': 'create a SkipTracker instance to track saved skip tensors on the current thread', 'create_SkipTrackerThroughPortals': 'create a SkipTrackerThroughPortals instance with a SkipLayout and index to track skip tensors through portals', 'use_skip_tracker_context': 'use the use_skip_tracker context manager to register a skip tracker on the current thread', 'get_current_skip_tracker': 'get the current skip tracker on the current thread using current_skip_tracker function', 'save_and_load_skip_tensor': 'save a skip tensor with SkipTracker.save and retrieve it with SkipTracker.load using namespace and name'}
```

