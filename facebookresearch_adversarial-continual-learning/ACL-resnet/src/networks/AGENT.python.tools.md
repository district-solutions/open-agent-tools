# Agent Python Tools

- repo: facebookresearch/adversarial-continual-learning
- repo_uri: https://github.com/facebookresearch/adversarial-continual-learning

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/networks/alexnet_acl.py

Prompts

```
['build a Shared convolutional encoder module for adversarial continual learning with configurable hidden layers', 'build a Private convolutional encoder module for task-specific feature extraction in continual learning', 'build a Net model combining Shared and Private encoders with a classification head for ACL', 'run the Net forward pass with shared and private inputs to get concatenated feature outputs', 'print the total parameter count and memory size of the ACL network across all tasks', 'create a Discriminator network with gradient reversal for adversarial continual learning', 'run a forward pass through the Discriminator network on latent representations', 'create a GradientReversal layer that reverses gradients during backpropagation', 'get and print the number of trainable parameters in the Discriminator network', 'use the GradientReversalFunction autograd function to multiply upstream gradients by negative lambda', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Private module with per-task linear layers that map input to a latent dimension', 'create a Shared module with configurable 2 or 3 layer MLP for shared feature extraction', 'run a forward pass through Net using shared and private features concatenated for task classification', 'get encoded features from both the shared and private branches for a given task', 'build a small ResNet-18 model with configurable shared or private hidden dimensions for continual learning', 'create a Shared encoder module that extracts features using a small ResNet backbone and MLP head', 'create a Net model combining shared and private ResNet encoders with a classification head for adversarial continual learning', 'build a BasicBlock residual block with two 3x3 convolutions and batch normalization for ResNet architectures']
```

Usage

```
{'build_shared_encoder': 'build a Shared convolutional encoder module for adversarial continual learning with configurable hidden layers', 'build_private_encoder': 'build a Private convolutional encoder module for task-specific feature extraction in continual learning', 'build_acl_net': 'build a Net model combining Shared and Private encoders with a classification head for ACL', 'run_net_forward': 'run the Net forward pass with shared and private inputs to get concatenated feature outputs', 'print_model_size': 'print the total parameter count and memory size of the ACL network across all tasks'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/networks/discriminator.py

Prompts

```
['build a Shared convolutional encoder module for adversarial continual learning with configurable hidden layers', 'build a Private convolutional encoder module for task-specific feature extraction in continual learning', 'build a Net model combining Shared and Private encoders with a classification head for ACL', 'run the Net forward pass with shared and private inputs to get concatenated feature outputs', 'print the total parameter count and memory size of the ACL network across all tasks', 'create a Discriminator network with gradient reversal for adversarial continual learning', 'run a forward pass through the Discriminator network on latent representations', 'create a GradientReversal layer that reverses gradients during backpropagation', 'get and print the number of trainable parameters in the Discriminator network', 'use the GradientReversalFunction autograd function to multiply upstream gradients by negative lambda', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Private module with per-task linear layers that map input to a latent dimension', 'create a Shared module with configurable 2 or 3 layer MLP for shared feature extraction', 'run a forward pass through Net using shared and private features concatenated for task classification', 'get encoded features from both the shared and private branches for a given task', 'build a small ResNet-18 model with configurable shared or private hidden dimensions for continual learning', 'create a Shared encoder module that extracts features using a small ResNet backbone and MLP head', 'create a Net model combining shared and private ResNet encoders with a classification head for adversarial continual learning', 'build a BasicBlock residual block with two 3x3 convolutions and batch normalization for ResNet architectures']
```

Usage

```
{'create_discriminator': 'create a Discriminator network with gradient reversal for adversarial continual learning', 'run_discriminator_forward': 'run a forward pass through the Discriminator network on latent representations', 'create_gradient_reversal': 'create a GradientReversal layer that reverses gradients during backpropagation', 'get_discriminator_size': 'get and print the number of trainable parameters in the Discriminator network', 'use_gradient_reversal_function': 'use the GradientReversalFunction autograd function to multiply upstream gradients by negative lambda'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/networks/mlp_acl.py

Prompts

```
['build a Shared convolutional encoder module for adversarial continual learning with configurable hidden layers', 'build a Private convolutional encoder module for task-specific feature extraction in continual learning', 'build a Net model combining Shared and Private encoders with a classification head for ACL', 'run the Net forward pass with shared and private inputs to get concatenated feature outputs', 'print the total parameter count and memory size of the ACL network across all tasks', 'create a Discriminator network with gradient reversal for adversarial continual learning', 'run a forward pass through the Discriminator network on latent representations', 'create a GradientReversal layer that reverses gradients during backpropagation', 'get and print the number of trainable parameters in the Discriminator network', 'use the GradientReversalFunction autograd function to multiply upstream gradients by negative lambda', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Private module with per-task linear layers that map input to a latent dimension', 'create a Shared module with configurable 2 or 3 layer MLP for shared feature extraction', 'run a forward pass through Net using shared and private features concatenated for task classification', 'get encoded features from both the shared and private branches for a given task', 'build a small ResNet-18 model with configurable shared or private hidden dimensions for continual learning', 'create a Shared encoder module that extracts features using a small ResNet backbone and MLP head', 'create a Net model combining shared and private ResNet encoders with a classification head for adversarial continual learning', 'build a BasicBlock residual block with two 3x3 convolutions and batch normalization for ResNet architectures']
```

Usage

```
{'build_net_model': 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create_private_module': 'create a Private module with per-task linear layers that map input to a latent dimension', 'create_shared_module': 'create a Shared module with configurable 2 or 3 layer MLP for shared feature extraction', 'run_forward_pass': 'run a forward pass through Net using shared and private features concatenated for task classification', 'get_encoded_features': 'get encoded features from both the shared and private branches for a given task'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/networks/resnet_acl.py

Prompts

```
['build a Shared convolutional encoder module for adversarial continual learning with configurable hidden layers', 'build a Private convolutional encoder module for task-specific feature extraction in continual learning', 'build a Net model combining Shared and Private encoders with a classification head for ACL', 'run the Net forward pass with shared and private inputs to get concatenated feature outputs', 'print the total parameter count and memory size of the ACL network across all tasks', 'create a Discriminator network with gradient reversal for adversarial continual learning', 'run a forward pass through the Discriminator network on latent representations', 'create a GradientReversal layer that reverses gradients during backpropagation', 'get and print the number of trainable parameters in the Discriminator network', 'use the GradientReversalFunction autograd function to multiply upstream gradients by negative lambda', 'build a PyTorch Net model with shared and private MLP branches for adversarial continual learning', 'create a Private module with per-task linear layers that map input to a latent dimension', 'create a Shared module with configurable 2 or 3 layer MLP for shared feature extraction', 'run a forward pass through Net using shared and private features concatenated for task classification', 'get encoded features from both the shared and private branches for a given task', 'build a small ResNet-18 model with configurable shared or private hidden dimensions for continual learning', 'create a Shared encoder module that extracts features using a small ResNet backbone and MLP head', 'create a Net model combining shared and private ResNet encoders with a classification head for adversarial continual learning', 'build a BasicBlock residual block with two 3x3 convolutions and batch normalization for ResNet architectures']
```

Usage

```
{'build_resnet18_small': 'build a small ResNet-18 model with configurable shared or private hidden dimensions for continual learning', 'create_shared_encoder': 'create a Shared encoder module that extracts features using a small ResNet backbone and MLP head', 'create_net_model': 'create a Net model combining shared and private ResNet encoders with a classification head for adversarial continual learning', 'build_basicblock': 'build a BasicBlock residual block with two 3x3 convolutions and batch normalization for ResNet architectures', 'print_model_size': 'print the total parameter count and memory size of a Net model including shared, private, and head components'}
```

