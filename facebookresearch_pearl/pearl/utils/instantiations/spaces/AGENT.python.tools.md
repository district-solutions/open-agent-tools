# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/utils/instantiations/spaces/box.py

Prompts

```
['create a BoxSpace with low and high bounds for continuous action spaces', 'sample a random element uniformly from a BoxSpace continuous space', 'get the lower and upper bound tensors of a BoxSpace instance', 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check if a BoxSpace is a continuous space using the is_continuous property', 'create a BoxActionSpace with low and high bounds for continuous action space', 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions', 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate over all tensor elements in a DiscreteSpace or access by index', 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements', 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D']
```

Usage

```
{'create_BoxSpace': 'create a BoxSpace with low and high bounds for continuous action spaces', 'sample_BoxSpace': 'sample a random element uniformly from a BoxSpace continuous space', 'get_low_high_bounds': 'get the lower and upper bound tensors of a BoxSpace instance', 'convert_gym_to_BoxSpace': 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check_is_continuous': 'check if a BoxSpace is a continuous space using the is_continuous property'}
```

## File: facebookresearch_pearl/pearl/utils/instantiations/spaces/box_action.py

Prompts

```
['create a BoxSpace with low and high bounds for continuous action spaces', 'sample a random element uniformly from a BoxSpace continuous space', 'get the lower and upper bound tensors of a BoxSpace instance', 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check if a BoxSpace is a continuous space using the is_continuous property', 'create a BoxActionSpace with low and high bounds for continuous action space', 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions', 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate over all tensor elements in a DiscreteSpace or access by index', 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements', 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D']
```

Usage

```
{'create_box_action_space': 'create a BoxActionSpace with low and high bounds for continuous action space', 'create_box_action_space_with_tensor': 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get_action_dim': 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create_from_gym_space': 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review_box_action_space_class': 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions'}
```

## File: facebookresearch_pearl/pearl/utils/instantiations/spaces/discrete.py

Prompts

```
['create a BoxSpace with low and high bounds for continuous action spaces', 'sample a random element uniformly from a BoxSpace continuous space', 'get the lower and upper bound tensors of a BoxSpace instance', 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check if a BoxSpace is a continuous space using the is_continuous property', 'create a BoxActionSpace with low and high bounds for continuous action space', 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions', 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate over all tensor elements in a DiscreteSpace or access by index', 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements', 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D']
```

Usage

```
{'create_discrete_space': 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample_discrete_space': 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate_elements': 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert_gym_to_discrete_space': 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate_discrete_space': 'iterate over all tensor elements in a DiscreteSpace or access by index'}
```

## File: facebookresearch_pearl/pearl/utils/instantiations/spaces/discrete_action.py

Prompts

```
['create a BoxSpace with low and high bounds for continuous action spaces', 'sample a random element uniformly from a BoxSpace continuous space', 'get the lower and upper bound tensors of a BoxSpace instance', 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check if a BoxSpace is a continuous space using the is_continuous property', 'create a BoxActionSpace with low and high bounds for continuous action space', 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions', 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate over all tensor elements in a DiscreteSpace or access by index', 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements', 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D']
```

Usage

```
{'create_discrete_action_space': 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build_from_gym_space': 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get_actions_batch_tensor': 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move_actions_to_device': 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate_action_shapes': 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements'}
```

## File: facebookresearch_pearl/pearl/utils/instantiations/spaces/utils.py

Prompts

```
['create a BoxSpace with low and high bounds for continuous action spaces', 'sample a random element uniformly from a BoxSpace continuous space', 'get the lower and upper bound tensors of a BoxSpace instance', 'convert a Gymnasium Box space to a BoxSpace using the from_gym static method', 'check if a BoxSpace is a continuous space using the is_continuous property', 'create a BoxActionSpace with low and high bounds for continuous action space', 'create a BoxActionSpace using PyTorch tensors for low and high bounds', 'get the action dimensionality from a BoxActionSpace instance using the action_dim property', 'create a BoxActionSpace from an existing Gymnasium Box space using from_gym', 'review the BoxActionSpace class that extends BoxSpace and ActionSpace for continuous actions', 'create a DiscreteSpace from a list of PyTorch tensors with an optional random seed', 'sample a random element from a DiscreteSpace using an optional availability mask tensor', 'validate that all tensor elements in a DiscreteSpace share the same shape', 'convert a Gymnasium Discrete space into a DiscreteSpace with tensor elements', 'iterate over all tensor elements in a DiscreteSpace or access by index', 'create a DiscreteActionSpace from a list of PyTorch tensor Action objects with an optional seed', 'build a DiscreteActionSpace from a Gymnasium Discrete space using the from_gym static method', 'get a stacked tensor of shape (b, d) from all actions in the DiscreteActionSpace via actions_batch', 'move all action tensors in a DiscreteActionSpace to a specified PyTorch device using to()', 'validate that all actions in a DiscreteActionSpace share the same 1D tensor shape via _set_validated_elements', 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D']
```

Usage

```
{'build_reshape_to_1d_tensor': 'build a python module that reshapes a scalar or 1xN PyTorch tensor into a 1D tensor', 'test_reshape_to_1d_tensor_scalar': 'test reshape_to_1d_tensor with a scalar PyTorch tensor and verify it returns a 1D tensor', 'test_reshape_to_1d_tensor_2d': 'test reshape_to_1d_tensor with a 1xN PyTorch tensor and verify it returns a 1D tensor', 'test_reshape_to_1d_tensor_invalid': 'test reshape_to_1d_tensor with an unsupported tensor shape and verify it raises a ValueError', 'summarize_reshape_to_1d_tensor': 'summarize the reshape_to_1d_tensor function that normalizes scalar and 1xN tensors to 1D'}
```

