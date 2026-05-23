# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/model/checkpoint_utils.py

Prompts

```
['load a PyTorch checkpoint from a list of candidate file paths with optional recursive key extraction', 'load a checkpoint and apply a sequence of CkptIncludeKernel or CkptExcludeKernel transformations to its state dict', 'load a state dict into a PyTorch model and validate for missing or unexpected keys', 'initialize a model from consolidated weights with optional tensor inflation from image to video dimensions', 'create a CkptPrependKernel to prepend a prefix string to matching keys in a checkpoint state dict', "init a PyTorch model's parameters using a dictionary of parameter names to initialization functions", 'init model weights by passing custom initialization callables mapped to parameter names', 'init model parameters in place using functions that mutate tensors directly', 'init only specific named parameters of a model with targeted initialization strategies', 'init model parameters using Kaiming initialization functions mapped to parameter paths', 'build a MIMOHeadWrapper that attaches multiple heads to a trunk model using forward hooks', 'create a MIMOHeadWrapper with a list of head dicts specifying fork modules and input output keys', 'test the MIMOHeadWrapper forward method by passing a batch mapping and verifying output keys', 'refactor the MIMOHeadWrapper handle_list_inputs logic to support list inputs beyond the vision field', 'review the MIMOHeadWrapper HeadArgs and TrunkFieldArgs dataclasses to understand head and trunk field configuration']
```

Usage

```
{'load_checkpoint': 'load a PyTorch checkpoint from a list of candidate file paths with optional recursive key extraction', 'load_checkpoint_and_apply_kernels': 'load a checkpoint and apply a sequence of CkptIncludeKernel or CkptExcludeKernel transformations to its state dict', 'load_state_dict_into_model': 'load a state dict into a PyTorch model and validate for missing or unexpected keys', 'init_model_from_consolidated_weights': 'initialize a model from consolidated weights with optional tensor inflation from image to video dimensions', 'CkptPrependKernel': 'create a CkptPrependKernel to prepend a prefix string to matching keys in a checkpoint state dict'}
```

## File: facebookresearch_omnivore/omnivision/model/model_init_utils.py

Prompts

```
['load a PyTorch checkpoint from a list of candidate file paths with optional recursive key extraction', 'load a checkpoint and apply a sequence of CkptIncludeKernel or CkptExcludeKernel transformations to its state dict', 'load a state dict into a PyTorch model and validate for missing or unexpected keys', 'initialize a model from consolidated weights with optional tensor inflation from image to video dimensions', 'create a CkptPrependKernel to prepend a prefix string to matching keys in a checkpoint state dict', "init a PyTorch model's parameters using a dictionary of parameter names to initialization functions", 'init model weights by passing custom initialization callables mapped to parameter names', 'init model parameters in place using functions that mutate tensors directly', 'init only specific named parameters of a model with targeted initialization strategies', 'init model parameters using Kaiming initialization functions mapped to parameter paths', 'build a MIMOHeadWrapper that attaches multiple heads to a trunk model using forward hooks', 'create a MIMOHeadWrapper with a list of head dicts specifying fork modules and input output keys', 'test the MIMOHeadWrapper forward method by passing a batch mapping and verifying output keys', 'refactor the MIMOHeadWrapper handle_list_inputs logic to support list inputs beyond the vision field', 'review the MIMOHeadWrapper HeadArgs and TrunkFieldArgs dataclasses to understand head and trunk field configuration']
```

Usage

```
{'init_parameters_model': "init a PyTorch model's parameters using a dictionary of parameter names to initialization functions", 'init_parameters_custom_init': 'init model weights by passing custom initialization callables mapped to parameter names', 'init_parameters_in_place': 'init model parameters in place using functions that mutate tensors directly', 'init_parameters_selective': 'init only specific named parameters of a model with targeted initialization strategies', 'init_parameters_kaiming': 'init model parameters using Kaiming initialization functions mapped to parameter paths'}
```

## File: facebookresearch_omnivore/omnivision/model/model_wrappers.py

Prompts

```
['load a PyTorch checkpoint from a list of candidate file paths with optional recursive key extraction', 'load a checkpoint and apply a sequence of CkptIncludeKernel or CkptExcludeKernel transformations to its state dict', 'load a state dict into a PyTorch model and validate for missing or unexpected keys', 'initialize a model from consolidated weights with optional tensor inflation from image to video dimensions', 'create a CkptPrependKernel to prepend a prefix string to matching keys in a checkpoint state dict', "init a PyTorch model's parameters using a dictionary of parameter names to initialization functions", 'init model weights by passing custom initialization callables mapped to parameter names', 'init model parameters in place using functions that mutate tensors directly', 'init only specific named parameters of a model with targeted initialization strategies', 'init model parameters using Kaiming initialization functions mapped to parameter paths', 'build a MIMOHeadWrapper that attaches multiple heads to a trunk model using forward hooks', 'create a MIMOHeadWrapper with a list of head dicts specifying fork modules and input output keys', 'test the MIMOHeadWrapper forward method by passing a batch mapping and verifying output keys', 'refactor the MIMOHeadWrapper handle_list_inputs logic to support list inputs beyond the vision field', 'review the MIMOHeadWrapper HeadArgs and TrunkFieldArgs dataclasses to understand head and trunk field configuration']
```

Usage

```
{'build_MIMOHeadWrapper': 'build a MIMOHeadWrapper that attaches multiple heads to a trunk model using forward hooks', 'create_MIMOHeadWrapper_with_heads': 'create a MIMOHeadWrapper with a list of head dicts specifying fork modules and input output keys', 'test_MIMOHeadWrapper_forward': 'test the MIMOHeadWrapper forward method by passing a batch mapping and verifying output keys', 'refactor_MIMOHeadWrapper_handle_list_inputs': 'refactor the MIMOHeadWrapper handle_list_inputs logic to support list inputs beyond the vision field', 'review_MIMOHeadWrapper_head_args': 'review the MIMOHeadWrapper HeadArgs and TrunkFieldArgs dataclasses to understand head and trunk field configuration'}
```

