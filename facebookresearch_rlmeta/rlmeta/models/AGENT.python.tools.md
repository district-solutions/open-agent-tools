# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/models/actor_critic.py

Prompts

```
['build a DiscreteActorCriticHead module with MLP policy and value heads for discrete action spaces', 'build a DiscreteActorCriticRNDHead module with separate extrinsic and intrinsic value heads for RND', 'run the forward pass of DiscreteActorCriticHead to get log-probabilities and value estimates', 'run the forward pass of DiscreteActorCriticRNDHead to get log-probabilities, extrinsic and intrinsic values', 'review the DiscreteActorCriticHead and DiscreteActorCriticRNDHead classes for RL policy and value network architecture', 'build a NatureCNNBackbone model for Atari with 3 conv layers and 3136 output features', 'build an ImpalaCNNBackbone model for Atari with residual conv blocks and 3872 output features', 'run a forward pass through the NatureCNNBackbone on a batch of 4-channel Atari frames', 'run a forward pass through the ImpalaCNNBackbone on a batch of 4-channel Atari frames', 'review the ImpalaCNNBackbone _conv_block method which combines Conv2d, MaxPool2d, and two ResidualBlocks', 'create a DQNHead module with input size, hidden sizes, and number of actions for Q-value prediction', 'create a DuelingDQNHead module that separates state value and advantage estimation for Q-learning', 'run forward pass through DQNHead to compute Q-values for a batch of state tensors', 'run forward pass through DuelingDQNHead to compute decomposed Q-values using value and advantage streams', 'review the DQNHead class which wraps an MLP network to output action Q-values', 'create a multi-layer perceptron with configurable hidden layer sizes and ReLU activations', 'build an MLP network with optional final layer activation for feature transformation', 'create a residual block with two conv layers and skip connection for image features', 'build a residual block with configurable kernel size for convolutional neural networks', 'review the MLP and ResidualBlock classes for use in reinforcement learning model architectures']
```

Usage

```
{'build_discrete_actor_critic_head': 'build a DiscreteActorCriticHead module with MLP policy and value heads for discrete action spaces', 'build_discrete_actor_critic_rnd_head': 'build a DiscreteActorCriticRNDHead module with separate extrinsic and intrinsic value heads for RND', 'run_forward_actor_critic': 'run the forward pass of DiscreteActorCriticHead to get log-probabilities and value estimates', 'run_forward_rnd_head': 'run the forward pass of DiscreteActorCriticRNDHead to get log-probabilities, extrinsic and intrinsic values', 'review_actor_critic_classes': 'review the DiscreteActorCriticHead and DiscreteActorCriticRNDHead classes for RL policy and value network architecture'}
```

## File: facebookresearch_rlmeta/rlmeta/models/atari.py

Prompts

```
['build a DiscreteActorCriticHead module with MLP policy and value heads for discrete action spaces', 'build a DiscreteActorCriticRNDHead module with separate extrinsic and intrinsic value heads for RND', 'run the forward pass of DiscreteActorCriticHead to get log-probabilities and value estimates', 'run the forward pass of DiscreteActorCriticRNDHead to get log-probabilities, extrinsic and intrinsic values', 'review the DiscreteActorCriticHead and DiscreteActorCriticRNDHead classes for RL policy and value network architecture', 'build a NatureCNNBackbone model for Atari with 3 conv layers and 3136 output features', 'build an ImpalaCNNBackbone model for Atari with residual conv blocks and 3872 output features', 'run a forward pass through the NatureCNNBackbone on a batch of 4-channel Atari frames', 'run a forward pass through the ImpalaCNNBackbone on a batch of 4-channel Atari frames', 'review the ImpalaCNNBackbone _conv_block method which combines Conv2d, MaxPool2d, and two ResidualBlocks', 'create a DQNHead module with input size, hidden sizes, and number of actions for Q-value prediction', 'create a DuelingDQNHead module that separates state value and advantage estimation for Q-learning', 'run forward pass through DQNHead to compute Q-values for a batch of state tensors', 'run forward pass through DuelingDQNHead to compute decomposed Q-values using value and advantage streams', 'review the DQNHead class which wraps an MLP network to output action Q-values', 'create a multi-layer perceptron with configurable hidden layer sizes and ReLU activations', 'build an MLP network with optional final layer activation for feature transformation', 'create a residual block with two conv layers and skip connection for image features', 'build a residual block with configurable kernel size for convolutional neural networks', 'review the MLP and ResidualBlock classes for use in reinforcement learning model architectures']
```

Usage

```
{'build_nature_cnn_backbone': 'build a NatureCNNBackbone model for Atari with 3 conv layers and 3136 output features', 'build_impala_cnn_backbone': 'build an ImpalaCNNBackbone model for Atari with residual conv blocks and 3872 output features', 'run_nature_cnn_forward': 'run a forward pass through the NatureCNNBackbone on a batch of 4-channel Atari frames', 'run_impala_cnn_forward': 'run a forward pass through the ImpalaCNNBackbone on a batch of 4-channel Atari frames', 'review_conv_block': 'review the ImpalaCNNBackbone _conv_block method which combines Conv2d, MaxPool2d, and two ResidualBlocks'}
```

## File: facebookresearch_rlmeta/rlmeta/models/dqn.py

Prompts

```
['build a DiscreteActorCriticHead module with MLP policy and value heads for discrete action spaces', 'build a DiscreteActorCriticRNDHead module with separate extrinsic and intrinsic value heads for RND', 'run the forward pass of DiscreteActorCriticHead to get log-probabilities and value estimates', 'run the forward pass of DiscreteActorCriticRNDHead to get log-probabilities, extrinsic and intrinsic values', 'review the DiscreteActorCriticHead and DiscreteActorCriticRNDHead classes for RL policy and value network architecture', 'build a NatureCNNBackbone model for Atari with 3 conv layers and 3136 output features', 'build an ImpalaCNNBackbone model for Atari with residual conv blocks and 3872 output features', 'run a forward pass through the NatureCNNBackbone on a batch of 4-channel Atari frames', 'run a forward pass through the ImpalaCNNBackbone on a batch of 4-channel Atari frames', 'review the ImpalaCNNBackbone _conv_block method which combines Conv2d, MaxPool2d, and two ResidualBlocks', 'create a DQNHead module with input size, hidden sizes, and number of actions for Q-value prediction', 'create a DuelingDQNHead module that separates state value and advantage estimation for Q-learning', 'run forward pass through DQNHead to compute Q-values for a batch of state tensors', 'run forward pass through DuelingDQNHead to compute decomposed Q-values using value and advantage streams', 'review the DQNHead class which wraps an MLP network to output action Q-values', 'create a multi-layer perceptron with configurable hidden layer sizes and ReLU activations', 'build an MLP network with optional final layer activation for feature transformation', 'create a residual block with two conv layers and skip connection for image features', 'build a residual block with configurable kernel size for convolutional neural networks', 'review the MLP and ResidualBlock classes for use in reinforcement learning model architectures']
```

Usage

```
{'create_dqn_head': 'create a DQNHead module with input size, hidden sizes, and number of actions for Q-value prediction', 'create_dueling_dqn_head': 'create a DuelingDQNHead module that separates state value and advantage estimation for Q-learning', 'run_dqn_head_forward': 'run forward pass through DQNHead to compute Q-values for a batch of state tensors', 'run_dueling_dqn_head_forward': 'run forward pass through DuelingDQNHead to compute decomposed Q-values using value and advantage streams', 'review_dqn_head_architecture': 'review the DQNHead class which wraps an MLP network to output action Q-values'}
```

## File: facebookresearch_rlmeta/rlmeta/models/utils.py

Prompts

```
['build a DiscreteActorCriticHead module with MLP policy and value heads for discrete action spaces', 'build a DiscreteActorCriticRNDHead module with separate extrinsic and intrinsic value heads for RND', 'run the forward pass of DiscreteActorCriticHead to get log-probabilities and value estimates', 'run the forward pass of DiscreteActorCriticRNDHead to get log-probabilities, extrinsic and intrinsic values', 'review the DiscreteActorCriticHead and DiscreteActorCriticRNDHead classes for RL policy and value network architecture', 'build a NatureCNNBackbone model for Atari with 3 conv layers and 3136 output features', 'build an ImpalaCNNBackbone model for Atari with residual conv blocks and 3872 output features', 'run a forward pass through the NatureCNNBackbone on a batch of 4-channel Atari frames', 'run a forward pass through the ImpalaCNNBackbone on a batch of 4-channel Atari frames', 'review the ImpalaCNNBackbone _conv_block method which combines Conv2d, MaxPool2d, and two ResidualBlocks', 'create a DQNHead module with input size, hidden sizes, and number of actions for Q-value prediction', 'create a DuelingDQNHead module that separates state value and advantage estimation for Q-learning', 'run forward pass through DQNHead to compute Q-values for a batch of state tensors', 'run forward pass through DuelingDQNHead to compute decomposed Q-values using value and advantage streams', 'review the DQNHead class which wraps an MLP network to output action Q-values', 'create a multi-layer perceptron with configurable hidden layer sizes and ReLU activations', 'build an MLP network with optional final layer activation for feature transformation', 'create a residual block with two conv layers and skip connection for image features', 'build a residual block with configurable kernel size for convolutional neural networks', 'review the MLP and ResidualBlock classes for use in reinforcement learning model architectures']
```

Usage

```
{'create_MLP_network': 'create a multi-layer perceptron with configurable hidden layer sizes and ReLU activations', 'build_MLP_with_activation': 'build an MLP network with optional final layer activation for feature transformation', 'create_ResidualBlock_conv': 'create a residual block with two conv layers and skip connection for image features', 'build_ResidualBlock_custom_kernel': 'build a residual block with configurable kernel size for convolutional neural networks', 'review_MLP_ResidualBlock': 'review the MLP and ResidualBlock classes for use in reinforcement learning model architectures'}
```

