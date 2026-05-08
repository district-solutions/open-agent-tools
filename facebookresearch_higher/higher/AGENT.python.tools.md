# Agent Python Tools

- repo: facebookresearch/higher
- repo_uri: https://github.com/facebookresearch/higher

## File: facebookresearch_higher/higher/optim.py

Prompts

```
['create a differentiable optimizer from an existing torch.optim.Optimizer using get_diff_optim', 'create a new differentiable optimizer from an optimizer type using create_diff_optim', 'register a custom optimizer type for use with higher using register_optim', 'get an override dictionary of trainable hyperparameters from an optimizer using get_trainable_opt_params', 'apply learned hyperparameters back to the original optimizer using apply_trainable_opt_params', 'create a stateless version of a torch.nn.Module using make_functional for meta-learning', 'create a monkey-patched stateless module with fast weights using monkeypatch for MAML training', 'update the fast parameters of a monkey-patched module using update_params after an optimizer step', 'sync buffers from an original module to its monkey-patched counterpart using buffer_sync', 'get the current fast parameters of a patched module using the fast_params property', "get a detached copy of a PyTorch module's parameters that require gradient", 'flatten a nested dict, list, set, or tuple into a flat list of objects', 'clone and detach a PyTorch tensor while preserving its requires_grad setting', 'recursively apply a function to all elements of a nested list, dict, tuple, or set', 'recursively copy and move all tensors in a nested structure to a target device']
```

Usage

```
{'create_diff_optim_from_existing': 'create a differentiable optimizer from an existing torch.optim.Optimizer using get_diff_optim', 'create_diff_optim_from_type': 'create a new differentiable optimizer from an optimizer type using create_diff_optim', 'register_custom_optim': 'register a custom optimizer type for use with higher using register_optim', 'get_trainable_opt_params': 'get an override dictionary of trainable hyperparameters from an optimizer using get_trainable_opt_params', 'apply_trainable_opt_params': 'apply learned hyperparameters back to the original optimizer using apply_trainable_opt_params'}
```

## File: facebookresearch_higher/higher/patch.py

Prompts

```
['create a differentiable optimizer from an existing torch.optim.Optimizer using get_diff_optim', 'create a new differentiable optimizer from an optimizer type using create_diff_optim', 'register a custom optimizer type for use with higher using register_optim', 'get an override dictionary of trainable hyperparameters from an optimizer using get_trainable_opt_params', 'apply learned hyperparameters back to the original optimizer using apply_trainable_opt_params', 'create a stateless version of a torch.nn.Module using make_functional for meta-learning', 'create a monkey-patched stateless module with fast weights using monkeypatch for MAML training', 'update the fast parameters of a monkey-patched module using update_params after an optimizer step', 'sync buffers from an original module to its monkey-patched counterpart using buffer_sync', 'get the current fast parameters of a patched module using the fast_params property', "get a detached copy of a PyTorch module's parameters that require gradient", 'flatten a nested dict, list, set, or tuple into a flat list of objects', 'clone and detach a PyTorch tensor while preserving its requires_grad setting', 'recursively apply a function to all elements of a nested list, dict, tuple, or set', 'recursively copy and move all tensors in a nested structure to a target device']
```

Usage

```
{'create_functional_module': 'create a stateless version of a torch.nn.Module using make_functional for meta-learning', 'create_monkeypatched_module': 'create a monkey-patched stateless module with fast weights using monkeypatch for MAML training', 'update_fast_params': 'update the fast parameters of a monkey-patched module using update_params after an optimizer step', 'sync_buffers': 'sync buffers from an original module to its monkey-patched counterpart using buffer_sync', 'get_fast_params': 'get the current fast parameters of a patched module using the fast_params property'}
```

## File: facebookresearch_higher/higher/utils.py

Prompts

```
['create a differentiable optimizer from an existing torch.optim.Optimizer using get_diff_optim', 'create a new differentiable optimizer from an optimizer type using create_diff_optim', 'register a custom optimizer type for use with higher using register_optim', 'get an override dictionary of trainable hyperparameters from an optimizer using get_trainable_opt_params', 'apply learned hyperparameters back to the original optimizer using apply_trainable_opt_params', 'create a stateless version of a torch.nn.Module using make_functional for meta-learning', 'create a monkey-patched stateless module with fast weights using monkeypatch for MAML training', 'update the fast parameters of a monkey-patched module using update_params after an optimizer step', 'sync buffers from an original module to its monkey-patched counterpart using buffer_sync', 'get the current fast parameters of a patched module using the fast_params property', "get a detached copy of a PyTorch module's parameters that require gradient", 'flatten a nested dict, list, set, or tuple into a flat list of objects', 'clone and detach a PyTorch tensor while preserving its requires_grad setting', 'recursively apply a function to all elements of a nested list, dict, tuple, or set', 'recursively copy and move all tensors in a nested structure to a target device']
```

Usage

```
{'get_func_params': "get a detached copy of a PyTorch module's parameters that require gradient", 'flatten': 'flatten a nested dict, list, set, or tuple into a flat list of objects', 'copy_tensor': 'clone and detach a PyTorch tensor while preserving its requires_grad setting', 'recursive_map': 'recursively apply a function to all elements of a nested list, dict, tuple, or set', 'recursive_copy_and_cast': 'recursively copy and move all tensors in a nested structure to a target device'}
```

