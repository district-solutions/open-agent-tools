# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/misc/flatten_params_wrapper.py

Prompts

```
['create a FlatParameter from a list of nn.Parameters to flatten them into a single tensor', 'wrap a PyTorch module with FlattenParamsWrapper to transparently flatten its parameters into flat tensors', 'get parameter views from a FlatParameter by calling get_param_views to reconstruct original shaped tensors', 'use the unflatten_params context manager to temporarily restore original parameters from flattened state', 'get the flattened state dict of a FlattenParamsWrapper using flat_state_dict instead of the default unflattened version', 'create a ParamBucket to store multiple PyTorch parameters as views into a shared flat buffer', 'add a PyTorch parameter tensor to a ParamBucket so its data becomes a view of the bucket buffer', 'create a GradBucket to manage gradient tensors as views into a shared flat buffer for communication', 'add a parameter gradient to a GradBucket so param.grad becomes a view of the bucket buffer', 'collapse a GradBucket to release memory then rebuild it to restore gradient views']
```

Usage

```
{'create_flat_parameter': 'create a FlatParameter from a list of nn.Parameters to flatten them into a single tensor', 'wrap_module_with_flatten_params_wrapper': 'wrap a PyTorch module with FlattenParamsWrapper to transparently flatten its parameters into flat tensors', 'get_param_views_from_flat_parameter': 'get parameter views from a FlatParameter by calling get_param_views to reconstruct original shaped tensors', 'unflatten_params_context_manager': 'use the unflatten_params context manager to temporarily restore original parameters from flattened state', 'get_flat_state_dict': 'get the flattened state dict of a FlattenParamsWrapper using flat_state_dict instead of the default unflattened version'}
```

## File: facebookresearch_fairscale/fairscale/nn/misc/param_bucket.py

Prompts

```
['create a FlatParameter from a list of nn.Parameters to flatten them into a single tensor', 'wrap a PyTorch module with FlattenParamsWrapper to transparently flatten its parameters into flat tensors', 'get parameter views from a FlatParameter by calling get_param_views to reconstruct original shaped tensors', 'use the unflatten_params context manager to temporarily restore original parameters from flattened state', 'get the flattened state dict of a FlattenParamsWrapper using flat_state_dict instead of the default unflattened version', 'create a ParamBucket to store multiple PyTorch parameters as views into a shared flat buffer', 'add a PyTorch parameter tensor to a ParamBucket so its data becomes a view of the bucket buffer', 'create a GradBucket to manage gradient tensors as views into a shared flat buffer for communication', 'add a parameter gradient to a GradBucket so param.grad becomes a view of the bucket buffer', 'collapse a GradBucket to release memory then rebuild it to restore gradient views']
```

Usage

```
{'create_param_bucket': 'create a ParamBucket to store multiple PyTorch parameters as views into a shared flat buffer', 'add_param_to_bucket': 'add a PyTorch parameter tensor to a ParamBucket so its data becomes a view of the bucket buffer', 'create_grad_bucket': 'create a GradBucket to manage gradient tensors as views into a shared flat buffer for communication', 'add_grad_to_bucket': 'add a parameter gradient to a GradBucket so param.grad becomes a view of the bucket buffer', 'collapse_and_rebuild_grad_bucket': 'collapse a GradBucket to release memory then rebuild it to restore gradient views'}
```

