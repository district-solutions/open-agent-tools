# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_prims/context.py

Prompts

```
['build a mapping of torch API functions to their torch._refs equivalents for decomposition', 'test the all_prims function returns a set of all torch._prims functions', 'create a TorchRefsMode context manager to redirect torch.* calls to torch._refs implementations', 'run TorchRefsMode with strict=True to raise an error when no _refs support exists', 'refactor TorchRefsMode to customize fallback behavior via should_fallback_fn callback', 'test the load_tensor_reader context manager that sets up a ContentStoreReader for loading tensors', 'test the register_debug_prims function that registers debugprims::load_tensor as a custom op', 'test the load_tensor custom op that loads a tensor by name with specified size, stride, dtype, and device', 'test the load_tensor_factory implementation that returns random strided tensors or reads from ContentStoreReader', 'build a debug tensor loader using load_tensor_reader context manager to load tensors from a content store location', 'execute a GraphModule using the aten executor with positional tensor arguments', 'wrap a callable with make_traced to trace torch operations to prims and execute them', 'run a traced torch function that executes prims on the requested trace executor', 'build a traced torch module that traces operations to prims and executes via aten', 'test make_traced by wrapping a torch function and verifying traced execution', 'register a philox-based stateless random number generation prim operator for CUDA devices', 'register a new rng prim by defining schema, aten implementation, meta implementation, and autograd behavior', 'run an operation while saving the current rng state and returning both the saved state and operation result', 'run an operation under a specified rng state while restoring the original state afterward', 'create a higher-order operator that saves and restores rng state across cpu and cuda backends']
```

Usage

```
{'build_torch_to_refs_map': 'build a mapping of torch API functions to their torch._refs equivalents for decomposition', 'test_all_prims': 'test the all_prims function returns a set of all torch._prims functions', 'create_torch_refs_mode': 'create a TorchRefsMode context manager to redirect torch.* calls to torch._refs implementations', 'run_torch_refs_mode_strict': 'run TorchRefsMode with strict=True to raise an error when no _refs support exists', 'refactor_torch_refs_mode_fallback': 'refactor TorchRefsMode to customize fallback behavior via should_fallback_fn callback'}
```

## File: pytorch_pytorch/torch/_prims/debug_prims.py

Prompts

```
['build a mapping of torch API functions to their torch._refs equivalents for decomposition', 'test the all_prims function returns a set of all torch._prims functions', 'create a TorchRefsMode context manager to redirect torch.* calls to torch._refs implementations', 'run TorchRefsMode with strict=True to raise an error when no _refs support exists', 'refactor TorchRefsMode to customize fallback behavior via should_fallback_fn callback', 'test the load_tensor_reader context manager that sets up a ContentStoreReader for loading tensors', 'test the register_debug_prims function that registers debugprims::load_tensor as a custom op', 'test the load_tensor custom op that loads a tensor by name with specified size, stride, dtype, and device', 'test the load_tensor_factory implementation that returns random strided tensors or reads from ContentStoreReader', 'build a debug tensor loader using load_tensor_reader context manager to load tensors from a content store location', 'execute a GraphModule using the aten executor with positional tensor arguments', 'wrap a callable with make_traced to trace torch operations to prims and execute them', 'run a traced torch function that executes prims on the requested trace executor', 'build a traced torch module that traces operations to prims and executes via aten', 'test make_traced by wrapping a torch function and verifying traced execution', 'register a philox-based stateless random number generation prim operator for CUDA devices', 'register a new rng prim by defining schema, aten implementation, meta implementation, and autograd behavior', 'run an operation while saving the current rng state and returning both the saved state and operation result', 'run an operation under a specified rng state while restoring the original state afterward', 'create a higher-order operator that saves and restores rng state across cpu and cuda backends']
```

Usage

```
{'test_load_tensor_reader': 'test the load_tensor_reader context manager that sets up a ContentStoreReader for loading tensors', 'test_register_debug_prims': 'test the register_debug_prims function that registers debugprims::load_tensor as a custom op', 'test_load_tensor': 'test the load_tensor custom op that loads a tensor by name with specified size, stride, dtype, and device', 'test_load_tensor_factory': 'test the load_tensor_factory implementation that returns random strided tensors or reads from ContentStoreReader', 'build_debug_tensor_loader': 'build a debug tensor loader using load_tensor_reader context manager to load tensors from a content store location'}
```

## File: pytorch_pytorch/torch/_prims/executor.py

Prompts

```
['build a mapping of torch API functions to their torch._refs equivalents for decomposition', 'test the all_prims function returns a set of all torch._prims functions', 'create a TorchRefsMode context manager to redirect torch.* calls to torch._refs implementations', 'run TorchRefsMode with strict=True to raise an error when no _refs support exists', 'refactor TorchRefsMode to customize fallback behavior via should_fallback_fn callback', 'test the load_tensor_reader context manager that sets up a ContentStoreReader for loading tensors', 'test the register_debug_prims function that registers debugprims::load_tensor as a custom op', 'test the load_tensor custom op that loads a tensor by name with specified size, stride, dtype, and device', 'test the load_tensor_factory implementation that returns random strided tensors or reads from ContentStoreReader', 'build a debug tensor loader using load_tensor_reader context manager to load tensors from a content store location', 'execute a GraphModule using the aten executor with positional tensor arguments', 'wrap a callable with make_traced to trace torch operations to prims and execute them', 'run a traced torch function that executes prims on the requested trace executor', 'build a traced torch module that traces operations to prims and executes via aten', 'test make_traced by wrapping a torch function and verifying traced execution', 'register a philox-based stateless random number generation prim operator for CUDA devices', 'register a new rng prim by defining schema, aten implementation, meta implementation, and autograd behavior', 'run an operation while saving the current rng state and returning both the saved state and operation result', 'run an operation under a specified rng state while restoring the original state afterward', 'create a higher-order operator that saves and restores rng state across cpu and cuda backends']
```

Usage

```
{'execute_graph': 'execute a GraphModule using the aten executor with positional tensor arguments', 'make_traced_function': 'wrap a callable with make_traced to trace torch operations to prims and execute them', 'run_traced_torch_ops': 'run a traced torch function that executes prims on the requested trace executor', 'build_traced_torch_module': 'build a traced torch module that traces operations to prims and executes via aten', 'test_make_traced': 'test make_traced by wrapping a torch function and verifying traced execution'}
```

## File: pytorch_pytorch/torch/_prims/rng_prims.py

Prompts

```
['build a mapping of torch API functions to their torch._refs equivalents for decomposition', 'test the all_prims function returns a set of all torch._prims functions', 'create a TorchRefsMode context manager to redirect torch.* calls to torch._refs implementations', 'run TorchRefsMode with strict=True to raise an error when no _refs support exists', 'refactor TorchRefsMode to customize fallback behavior via should_fallback_fn callback', 'test the load_tensor_reader context manager that sets up a ContentStoreReader for loading tensors', 'test the register_debug_prims function that registers debugprims::load_tensor as a custom op', 'test the load_tensor custom op that loads a tensor by name with specified size, stride, dtype, and device', 'test the load_tensor_factory implementation that returns random strided tensors or reads from ContentStoreReader', 'build a debug tensor loader using load_tensor_reader context manager to load tensors from a content store location', 'execute a GraphModule using the aten executor with positional tensor arguments', 'wrap a callable with make_traced to trace torch operations to prims and execute them', 'run a traced torch function that executes prims on the requested trace executor', 'build a traced torch module that traces operations to prims and executes via aten', 'test make_traced by wrapping a torch function and verifying traced execution', 'register a philox-based stateless random number generation prim operator for CUDA devices', 'register a new rng prim by defining schema, aten implementation, meta implementation, and autograd behavior', 'run an operation while saving the current rng state and returning both the saved state and operation result', 'run an operation under a specified rng state while restoring the original state afterward', 'create a higher-order operator that saves and restores rng state across cpu and cuda backends']
```

Usage

```
{'register_philox_rand': 'register a philox-based stateless random number generation prim operator for CUDA devices', 'register_rng_prim': 'register a new rng prim by defining schema, aten implementation, meta implementation, and autograd behavior', 'run_and_save_rng_state': 'run an operation while saving the current rng state and returning both the saved state and operation result', 'run_with_rng_state': 'run an operation under a specified rng state while restoring the original state afterward', 'register_run_and_save_rng_state_op': 'create a higher-order operator that saves and restores rng state across cpu and cuda backends'}
```

