# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/action_representation_modules/action_representation_module.py

Prompts

```
['create a subclass of ActionRepresentationModule implementing max_number_actions, representation_dim, forward, and compare', 'implement the forward method in a subclass to transform input tensors into action representations', 'implement the compare method to check equality between two action representation module instances', 'define the max_number_actions property in a subclass to return the maximum number of actions', 'define the representation_dim property in a subclass to return the dimension of the action representation', 'create a BinaryActionTensorRepresentationModule instance with a specified number of bits for action representation', 'run the forward pass to transform a tensor of action indices into binary representation', 'build a binary mask and convert tensor values to their binary float32 representation', 'retrieve the maximum number of actions supported based on the configured bits number', 'review two BinaryActionTensorRepresentationModule instances and return a string describing their differences', 'create an IdentityActionRepresentationModule with max_number_actions and representation_dim parameters', 'run the forward method to pass a torch tensor through unchanged as identity', 'get the representation_dim property value from an IdentityActionRepresentationModule instance', 'create a OneHotActionTensorRepresentationModule with a specified maximum number of actions', 'forward a tensor through the module to get one-hot encoded action representations', 'compare two OneHotActionTensorRepresentationModule instances and return differences in max_number_actions', 'get the maximum number of actions configured in the one-hot representation module']
```

Usage

```
{'create_subclass_action_representation_module': 'create a subclass of ActionRepresentationModule implementing max_number_actions, representation_dim, forward, and compare', 'implement_forward_method': 'implement the forward method in a subclass to transform input tensors into action representations', 'implement_compare_method': 'implement the compare method to check equality between two action representation module instances', 'define_max_number_actions_property': 'define the max_number_actions property in a subclass to return the maximum number of actions', 'define_representation_dim_property': 'define the representation_dim property in a subclass to return the dimension of the action representation'}
```

## File: facebookresearch_pearl/pearl/action_representation_modules/binary_action_representation_module.py

Prompts

```
['create a subclass of ActionRepresentationModule implementing max_number_actions, representation_dim, forward, and compare', 'implement the forward method in a subclass to transform input tensors into action representations', 'implement the compare method to check equality between two action representation module instances', 'define the max_number_actions property in a subclass to return the maximum number of actions', 'define the representation_dim property in a subclass to return the dimension of the action representation', 'create a BinaryActionTensorRepresentationModule instance with a specified number of bits for action representation', 'run the forward pass to transform a tensor of action indices into binary representation', 'build a binary mask and convert tensor values to their binary float32 representation', 'retrieve the maximum number of actions supported based on the configured bits number', 'review two BinaryActionTensorRepresentationModule instances and return a string describing their differences', 'create an IdentityActionRepresentationModule with max_number_actions and representation_dim parameters', 'run the forward method to pass a torch tensor through unchanged as identity', 'get the representation_dim property value from an IdentityActionRepresentationModule instance', 'create a OneHotActionTensorRepresentationModule with a specified maximum number of actions', 'forward a tensor through the module to get one-hot encoded action representations', 'compare two OneHotActionTensorRepresentationModule instances and return differences in max_number_actions', 'get the maximum number of actions configured in the one-hot representation module']
```

Usage

```
{'create_binary_action_module': 'create a BinaryActionTensorRepresentationModule instance with a specified number of bits for action representation', 'forward_binary_transform': 'run the forward pass to transform a tensor of action indices into binary representation', 'binary_convert_tensor': 'build a binary mask and convert tensor values to their binary float32 representation', 'get_max_number_actions': 'retrieve the maximum number of actions supported based on the configured bits number', 'compare_action_modules': 'review two BinaryActionTensorRepresentationModule instances and return a string describing their differences'}
```

## File: facebookresearch_pearl/pearl/action_representation_modules/identity_action_representation_module.py

Prompts

```
['create a subclass of ActionRepresentationModule implementing max_number_actions, representation_dim, forward, and compare', 'implement the forward method in a subclass to transform input tensors into action representations', 'implement the compare method to check equality between two action representation module instances', 'define the max_number_actions property in a subclass to return the maximum number of actions', 'define the representation_dim property in a subclass to return the dimension of the action representation', 'create a BinaryActionTensorRepresentationModule instance with a specified number of bits for action representation', 'run the forward pass to transform a tensor of action indices into binary representation', 'build a binary mask and convert tensor values to their binary float32 representation', 'retrieve the maximum number of actions supported based on the configured bits number', 'review two BinaryActionTensorRepresentationModule instances and return a string describing their differences', 'create an IdentityActionRepresentationModule with max_number_actions and representation_dim parameters', 'run the forward method to pass a torch tensor through unchanged as identity', 'get the representation_dim property value from an IdentityActionRepresentationModule instance', 'create a OneHotActionTensorRepresentationModule with a specified maximum number of actions', 'forward a tensor through the module to get one-hot encoded action representations', 'compare two OneHotActionTensorRepresentationModule instances and return differences in max_number_actions', 'get the maximum number of actions configured in the one-hot representation module']
```

Usage

```
{'create_identity_action_module': 'create an IdentityActionRepresentationModule with max_number_actions and representation_dim parameters', 'run_forward_pass': 'run the forward method to pass a torch tensor through unchanged as identity', 'get_max_number_actions': 'get the max_number_actions property value from an IdentityActionRepresentationModule instance', 'get_representation_dim': 'get the representation_dim property value from an IdentityActionRepresentationModule instance', 'compare_action_modules': 'compare two IdentityActionRepresentationModule instances and return a string describing their differences'}
```

## File: facebookresearch_pearl/pearl/action_representation_modules/one_hot_action_representation_module.py

Prompts

```
['create a subclass of ActionRepresentationModule implementing max_number_actions, representation_dim, forward, and compare', 'implement the forward method in a subclass to transform input tensors into action representations', 'implement the compare method to check equality between two action representation module instances', 'define the max_number_actions property in a subclass to return the maximum number of actions', 'define the representation_dim property in a subclass to return the dimension of the action representation', 'create a BinaryActionTensorRepresentationModule instance with a specified number of bits for action representation', 'run the forward pass to transform a tensor of action indices into binary representation', 'build a binary mask and convert tensor values to their binary float32 representation', 'retrieve the maximum number of actions supported based on the configured bits number', 'review two BinaryActionTensorRepresentationModule instances and return a string describing their differences', 'create an IdentityActionRepresentationModule with max_number_actions and representation_dim parameters', 'run the forward method to pass a torch tensor through unchanged as identity', 'get the representation_dim property value from an IdentityActionRepresentationModule instance', 'create a OneHotActionTensorRepresentationModule with a specified maximum number of actions', 'forward a tensor through the module to get one-hot encoded action representations', 'compare two OneHotActionTensorRepresentationModule instances and return differences in max_number_actions', 'get the maximum number of actions configured in the one-hot representation module']
```

Usage

```
{'create_one_hot_module': 'create a OneHotActionTensorRepresentationModule with a specified maximum number of actions', 'forward_one_hot_encoding': 'forward a tensor through the module to get one-hot encoded action representations', 'get_representation_dim': 'get the representation dimension which equals the max number of actions', 'compare_modules': 'compare two OneHotActionTensorRepresentationModule instances and return differences in max_number_actions', 'get_max_actions': 'get the maximum number of actions configured in the one-hot representation module'}
```

