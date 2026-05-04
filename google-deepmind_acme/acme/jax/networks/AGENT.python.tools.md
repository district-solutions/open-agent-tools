# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/jax/networks/atari.py

Prompts

```
['build a DQN feed-forward network for Ape-X using AtariTorso and a duelling MLP head', 'create a simple convolutional stack with three Conv2D layers for Atari image feature extraction', 'create a ResNet-based deep torso with configurable channels, blocks, and downsampling strategies for Atari', 'build a recurrent GRU-based IMPALA network with policy-value head for Atari reinforcement learning', 'build a recurrent LSTM-based duelling network for Atari using the R2D2 architecture', 'create a FeedForwardNetwork dataclass with init and apply pure functions for a JAX network', 'create a TypedFeedForwardNetwork with typed init and apply functions following the ApplyFn protocol', 'create an UnrollableNetwork dataclass with init, apply, unroll, and init_recurrent_state functions', 'convert a non-stochastic FeedForwardNetwork to a TypedFeedForwardNetwork using non_stochastic_network_to_typed', 'build an UnrollableNetwork from a Haiku RNNCore module factory using make_unrollable_network', 'build a Haiku module that outputs a categorical distribution with configurable number of values', 'build a Gaussian mixture distribution head with configurable components and multivariate support', 'build a TanhTransformedDistribution head for bounded continuous action spaces', 'build a C51-style discrete valued distribution head for distributional RL value estimation', 'build a categorical critic head that represents action values as a discrete distribution', 'build a ResNetTorso Haiku module for visual inputs with configurable channels and blocks per group', 'create a ResidualBlock with a custom inner operation factory and optional layer normalization', 'create a downsampling layer using make_downsampling_layer with a strategy like CONV_MAX or AVG_POOL', 'review the DownsamplingStrategy enum values AVG_POOL, CONV_MAX, LAYERNORM_RELU_CONV, and CONV', 'refactor the ResidualBlock to swap the non_linearity from relu to a different activation function']
```

Usage

```
{'build_dqn_atari_network': 'build a DQN feed-forward network for Ape-X using AtariTorso and a duelling MLP head', 'create_atari_torso': 'create a simple convolutional stack with three Conv2D layers for Atari image feature extraction', 'create_deep_atari_torso': 'create a ResNet-based deep torso with configurable channels, blocks, and downsampling strategies for Atari', 'build_impala_atari_network': 'build a recurrent GRU-based IMPALA network with policy-value head for Atari reinforcement learning', 'build_r2d2_atari_network': 'build a recurrent LSTM-based duelling network for Atari using the R2D2 architecture'}
```

## File: google-deepmind_acme/acme/jax/networks/base.py

Prompts

```
['build a DQN feed-forward network for Ape-X using AtariTorso and a duelling MLP head', 'create a simple convolutional stack with three Conv2D layers for Atari image feature extraction', 'create a ResNet-based deep torso with configurable channels, blocks, and downsampling strategies for Atari', 'build a recurrent GRU-based IMPALA network with policy-value head for Atari reinforcement learning', 'build a recurrent LSTM-based duelling network for Atari using the R2D2 architecture', 'create a FeedForwardNetwork dataclass with init and apply pure functions for a JAX network', 'create a TypedFeedForwardNetwork with typed init and apply functions following the ApplyFn protocol', 'create an UnrollableNetwork dataclass with init, apply, unroll, and init_recurrent_state functions', 'convert a non-stochastic FeedForwardNetwork to a TypedFeedForwardNetwork using non_stochastic_network_to_typed', 'build an UnrollableNetwork from a Haiku RNNCore module factory using make_unrollable_network', 'build a Haiku module that outputs a categorical distribution with configurable number of values', 'build a Gaussian mixture distribution head with configurable components and multivariate support', 'build a TanhTransformedDistribution head for bounded continuous action spaces', 'build a C51-style discrete valued distribution head for distributional RL value estimation', 'build a categorical critic head that represents action values as a discrete distribution', 'build a ResNetTorso Haiku module for visual inputs with configurable channels and blocks per group', 'create a ResidualBlock with a custom inner operation factory and optional layer normalization', 'create a downsampling layer using make_downsampling_layer with a strategy like CONV_MAX or AVG_POOL', 'review the DownsamplingStrategy enum values AVG_POOL, CONV_MAX, LAYERNORM_RELU_CONV, and CONV', 'refactor the ResidualBlock to swap the non_linearity from relu to a different activation function']
```

Usage

```
{'build_feedforward_network': 'create a FeedForwardNetwork dataclass with init and apply pure functions for a JAX network', 'build_typed_feedforward_network': 'create a TypedFeedForwardNetwork with typed init and apply functions following the ApplyFn protocol', 'build_unrollable_network': 'create an UnrollableNetwork dataclass with init, apply, unroll, and init_recurrent_state functions', 'convert_non_stochastic_to_typed': 'convert a non-stochastic FeedForwardNetwork to a TypedFeedForwardNetwork using non_stochastic_network_to_typed', 'make_unrollable_network_from_rnn': 'build an UnrollableNetwork from a Haiku RNNCore module factory using make_unrollable_network'}
```

## File: google-deepmind_acme/acme/jax/networks/distributional.py

Prompts

```
['build a DQN feed-forward network for Ape-X using AtariTorso and a duelling MLP head', 'create a simple convolutional stack with three Conv2D layers for Atari image feature extraction', 'create a ResNet-based deep torso with configurable channels, blocks, and downsampling strategies for Atari', 'build a recurrent GRU-based IMPALA network with policy-value head for Atari reinforcement learning', 'build a recurrent LSTM-based duelling network for Atari using the R2D2 architecture', 'create a FeedForwardNetwork dataclass with init and apply pure functions for a JAX network', 'create a TypedFeedForwardNetwork with typed init and apply functions following the ApplyFn protocol', 'create an UnrollableNetwork dataclass with init, apply, unroll, and init_recurrent_state functions', 'convert a non-stochastic FeedForwardNetwork to a TypedFeedForwardNetwork using non_stochastic_network_to_typed', 'build an UnrollableNetwork from a Haiku RNNCore module factory using make_unrollable_network', 'build a Haiku module that outputs a categorical distribution with configurable number of values', 'build a Gaussian mixture distribution head with configurable components and multivariate support', 'build a TanhTransformedDistribution head for bounded continuous action spaces', 'build a C51-style discrete valued distribution head for distributional RL value estimation', 'build a categorical critic head that represents action values as a discrete distribution', 'build a ResNetTorso Haiku module for visual inputs with configurable channels and blocks per group', 'create a ResidualBlock with a custom inner operation factory and optional layer normalization', 'create a downsampling layer using make_downsampling_layer with a strategy like CONV_MAX or AVG_POOL', 'review the DownsamplingStrategy enum values AVG_POOL, CONV_MAX, LAYERNORM_RELU_CONV, and CONV', 'refactor the ResidualBlock to swap the non_linearity from relu to a different activation function']
```

Usage

```
{'build_categorical_head': 'build a Haiku module that outputs a categorical distribution with configurable number of values', 'build_gaussian_mixture': 'build a Gaussian mixture distribution head with configurable components and multivariate support', 'build_normal_tanh_distribution': 'build a TanhTransformedDistribution head for bounded continuous action spaces', 'build_discrete_valued_head': 'build a C51-style discrete valued distribution head for distributional RL value estimation', 'build_categorical_critic_head': 'build a categorical critic head that represents action values as a discrete distribution'}
```

## File: google-deepmind_acme/acme/jax/networks/resnet.py

Prompts

```
['build a DQN feed-forward network for Ape-X using AtariTorso and a duelling MLP head', 'create a simple convolutional stack with three Conv2D layers for Atari image feature extraction', 'create a ResNet-based deep torso with configurable channels, blocks, and downsampling strategies for Atari', 'build a recurrent GRU-based IMPALA network with policy-value head for Atari reinforcement learning', 'build a recurrent LSTM-based duelling network for Atari using the R2D2 architecture', 'create a FeedForwardNetwork dataclass with init and apply pure functions for a JAX network', 'create a TypedFeedForwardNetwork with typed init and apply functions following the ApplyFn protocol', 'create an UnrollableNetwork dataclass with init, apply, unroll, and init_recurrent_state functions', 'convert a non-stochastic FeedForwardNetwork to a TypedFeedForwardNetwork using non_stochastic_network_to_typed', 'build an UnrollableNetwork from a Haiku RNNCore module factory using make_unrollable_network', 'build a Haiku module that outputs a categorical distribution with configurable number of values', 'build a Gaussian mixture distribution head with configurable components and multivariate support', 'build a TanhTransformedDistribution head for bounded continuous action spaces', 'build a C51-style discrete valued distribution head for distributional RL value estimation', 'build a categorical critic head that represents action values as a discrete distribution', 'build a ResNetTorso Haiku module for visual inputs with configurable channels and blocks per group', 'create a ResidualBlock with a custom inner operation factory and optional layer normalization', 'create a downsampling layer using make_downsampling_layer with a strategy like CONV_MAX or AVG_POOL', 'review the DownsamplingStrategy enum values AVG_POOL, CONV_MAX, LAYERNORM_RELU_CONV, and CONV', 'refactor the ResidualBlock to swap the non_linearity from relu to a different activation function']
```

Usage

```
{'build_resnet_torso': 'build a ResNetTorso Haiku module for visual inputs with configurable channels and blocks per group', 'create_residual_block': 'create a ResidualBlock with a custom inner operation factory and optional layer normalization', 'create_downsampling_layer': 'create a downsampling layer using make_downsampling_layer with a strategy like CONV_MAX or AVG_POOL', 'review_downsampling_strategy_enum': 'review the DownsamplingStrategy enum values AVG_POOL, CONV_MAX, LAYERNORM_RELU_CONV, and CONV', 'refactor_residual_block': 'refactor the ResidualBlock to swap the non_linearity from relu to a different activation function'}
```

