# Agent Python Tools

- repo: facebookresearch/adversarial-continual-learning
- repo_uri: https://github.com/facebookresearch/adversarial-continual-learning

## File: facebookresearch_adversarial-continual-learning/src/networks/alexnet_acl.py

Prompts

```
['build a Shared CNN encoder module for continual learning with configurable hidden layers per experiment', 'build a Private task-specific CNN encoder module with per-task convolutional and linear layers', 'build a Net model combining Shared and Private encoders with task-specific classification heads', 'run a forward pass through the ACL network with shared and private inputs for a given task', 'print the model parameter counts and memory size breakdown for shared, private, and head modules', 'create a Discriminator module with gradient reversal for adversarial continual learning', 'run the Discriminator forward pass on latent representations z with labels and task_id', 'build a GradientReversal layer that reverses upstream gradients by multiplying with negative lambda', 'get and print the number of trainable parameters in the Discriminator network', 'review the GradientReversalFunction autograd Function that implements identity forward and negated backward pass', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Shared encoder module with configurable layers and dropout for feature extraction', 'create a Private encoder module with per-task linear layers for task-specific feature extraction', 'run the Net forward pass with shared and private features concatenated through task heads', 'summarize the Net model size by printing parameter counts for shared, private, and head modules']
```

Usage

```
{'build_shared_encoder': 'build a Shared CNN encoder module for continual learning with configurable hidden layers per experiment', 'build_private_encoder': 'build a Private task-specific CNN encoder module with per-task convolutional and linear layers', 'build_acl_network': 'build a Net model combining Shared and Private encoders with task-specific classification heads', 'run_forward_pass': 'run a forward pass through the ACL network with shared and private inputs for a given task', 'print_model_size': 'print the model parameter counts and memory size breakdown for shared, private, and head modules'}
```

## File: facebookresearch_adversarial-continual-learning/src/networks/discriminator.py

Prompts

```
['build a Shared CNN encoder module for continual learning with configurable hidden layers per experiment', 'build a Private task-specific CNN encoder module with per-task convolutional and linear layers', 'build a Net model combining Shared and Private encoders with task-specific classification heads', 'run a forward pass through the ACL network with shared and private inputs for a given task', 'print the model parameter counts and memory size breakdown for shared, private, and head modules', 'create a Discriminator module with gradient reversal for adversarial continual learning', 'run the Discriminator forward pass on latent representations z with labels and task_id', 'build a GradientReversal layer that reverses upstream gradients by multiplying with negative lambda', 'get and print the number of trainable parameters in the Discriminator network', 'review the GradientReversalFunction autograd Function that implements identity forward and negated backward pass', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Shared encoder module with configurable layers and dropout for feature extraction', 'create a Private encoder module with per-task linear layers for task-specific feature extraction', 'run the Net forward pass with shared and private features concatenated through task heads', 'summarize the Net model size by printing parameter counts for shared, private, and head modules']
```

Usage

```
{'create_discriminator': 'create a Discriminator module with gradient reversal for adversarial continual learning', 'run_discriminator_forward': 'run the Discriminator forward pass on latent representations z with labels and task_id', 'build_gradient_reversal_layer': 'build a GradientReversal layer that reverses upstream gradients by multiplying with negative lambda', 'get_discriminator_size': 'get and print the number of trainable parameters in the Discriminator network', 'review_gradient_reversal_function': 'review the GradientReversalFunction autograd Function that implements identity forward and negated backward pass'}
```

## File: facebookresearch_adversarial-continual-learning/src/networks/mlp_acl.py

Prompts

```
['build a Shared CNN encoder module for continual learning with configurable hidden layers per experiment', 'build a Private task-specific CNN encoder module with per-task convolutional and linear layers', 'build a Net model combining Shared and Private encoders with task-specific classification heads', 'run a forward pass through the ACL network with shared and private inputs for a given task', 'print the model parameter counts and memory size breakdown for shared, private, and head modules', 'create a Discriminator module with gradient reversal for adversarial continual learning', 'run the Discriminator forward pass on latent representations z with labels and task_id', 'build a GradientReversal layer that reverses upstream gradients by multiplying with negative lambda', 'get and print the number of trainable parameters in the Discriminator network', 'review the GradientReversalFunction autograd Function that implements identity forward and negated backward pass', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Shared encoder module with configurable layers and dropout for feature extraction', 'create a Private encoder module with per-task linear layers for task-specific feature extraction', 'run the Net forward pass with shared and private features concatenated through task heads', 'summarize the Net model size by printing parameter counts for shared, private, and head modules']
```

Usage

```
{'build_Net_model': 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create_Shared_encoder': 'create a Shared encoder module with configurable layers and dropout for feature extraction', 'create_Private_encoder': 'create a Private encoder module with per-task linear layers for task-specific feature extraction', 'run_Net_forward': 'run the Net forward pass with shared and private features concatenated through task heads', 'summarize_print_model_size': 'summarize the Net model size by printing parameter counts for shared, private, and head modules'}
```

