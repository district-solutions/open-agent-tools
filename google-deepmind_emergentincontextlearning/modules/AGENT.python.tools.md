# Agent Python Tools

- repo: google-deepmind/emergentincontextlearning
- repo_uri: https://github.com/google-deepmind/emergent_in_context_learning

## File: google-deepmind_emergentincontextlearning/modules/losses.py

Prompts

```
['compute softmax cross entropy loss from logits and one-hot labels with configurable reduction', 'reduce an array of loss values using sum, mean, or no reduction mode', 'build a JAX loss module that wraps optax softmax cross entropy with custom reduction logic', 'test the reduce_fn function with sum, mean, and none reduction modes on JAX arrays', 'refactor the softmax_cross_entropy function to support additional reduction modes or label formats', 'build a SimpleResNet model with configurable blocks_per_group, channels_per_group, and stride settings', 'create a BlockV1 ResNet block with optional bottleneck and batch normalization layers', 'create a BlockV2 ResNet block with pre-activation residual connections and optional bottleneck', 'build a BlockGroup containing multiple ResNet blocks with shared channel and stride configuration', 'review the SimpleResNet forward pass including initial conv, max pool, block groups, and global pooling', 'build a TransformerBlock with causal self-attention, conditional attention, and dense feed-forward layers using Haiku', 'create an Attention module with multi-head attention, optional relative position embeddings, and caching support', 'build a CausalSelfAttention module that applies a causal mask to prevent attending to future tokens', 'create a SinusoidalPositionEmbedding or RelativePositionEmbedding module for encoding sequence positions into transformer inputs', 'implement tiled dropout that shares a random mask across trailing dimensions of a tensor']
```

Usage

```
{'compute_softmax_cross_entropy': 'compute softmax cross entropy loss from logits and one-hot labels with configurable reduction', 'reduce_loss_values': 'reduce an array of loss values using sum, mean, or no reduction mode', 'build_loss_module': 'build a JAX loss module that wraps optax softmax cross entropy with custom reduction logic', 'test_reduce_fn': 'test the reduce_fn function with sum, mean, and none reduction modes on JAX arrays', 'refactor_softmax_cross_entropy': 'refactor the softmax_cross_entropy function to support additional reduction modes or label formats'}
```

## File: google-deepmind_emergentincontextlearning/modules/resnet.py

Prompts

```
['compute softmax cross entropy loss from logits and one-hot labels with configurable reduction', 'reduce an array of loss values using sum, mean, or no reduction mode', 'build a JAX loss module that wraps optax softmax cross entropy with custom reduction logic', 'test the reduce_fn function with sum, mean, and none reduction modes on JAX arrays', 'refactor the softmax_cross_entropy function to support additional reduction modes or label formats', 'build a SimpleResNet model with configurable blocks_per_group, channels_per_group, and stride settings', 'create a BlockV1 ResNet block with optional bottleneck and batch normalization layers', 'create a BlockV2 ResNet block with pre-activation residual connections and optional bottleneck', 'build a BlockGroup containing multiple ResNet blocks with shared channel and stride configuration', 'review the SimpleResNet forward pass including initial conv, max pool, block groups, and global pooling', 'build a TransformerBlock with causal self-attention, conditional attention, and dense feed-forward layers using Haiku', 'create an Attention module with multi-head attention, optional relative position embeddings, and caching support', 'build a CausalSelfAttention module that applies a causal mask to prevent attending to future tokens', 'create a SinusoidalPositionEmbedding or RelativePositionEmbedding module for encoding sequence positions into transformer inputs', 'implement tiled dropout that shares a random mask across trailing dimensions of a tensor']
```

Usage

```
{'build_resnet_model': 'build a SimpleResNet model with configurable blocks_per_group, channels_per_group, and stride settings', 'create_resnet_v1_block': 'create a BlockV1 ResNet block with optional bottleneck and batch normalization layers', 'create_resnet_v2_block': 'create a BlockV2 ResNet block with pre-activation residual connections and optional bottleneck', 'build_block_group': 'build a BlockGroup containing multiple ResNet blocks with shared channel and stride configuration', 'review_resnet_architecture': 'review the SimpleResNet forward pass including initial conv, max pool, block groups, and global pooling'}
```

## File: google-deepmind_emergentincontextlearning/modules/transformer_core.py

Prompts

```
['compute softmax cross entropy loss from logits and one-hot labels with configurable reduction', 'reduce an array of loss values using sum, mean, or no reduction mode', 'build a JAX loss module that wraps optax softmax cross entropy with custom reduction logic', 'test the reduce_fn function with sum, mean, and none reduction modes on JAX arrays', 'refactor the softmax_cross_entropy function to support additional reduction modes or label formats', 'build a SimpleResNet model with configurable blocks_per_group, channels_per_group, and stride settings', 'create a BlockV1 ResNet block with optional bottleneck and batch normalization layers', 'create a BlockV2 ResNet block with pre-activation residual connections and optional bottleneck', 'build a BlockGroup containing multiple ResNet blocks with shared channel and stride configuration', 'review the SimpleResNet forward pass including initial conv, max pool, block groups, and global pooling', 'build a TransformerBlock with causal self-attention, conditional attention, and dense feed-forward layers using Haiku', 'create an Attention module with multi-head attention, optional relative position embeddings, and caching support', 'build a CausalSelfAttention module that applies a causal mask to prevent attending to future tokens', 'create a SinusoidalPositionEmbedding or RelativePositionEmbedding module for encoding sequence positions into transformer inputs', 'implement tiled dropout that shares a random mask across trailing dimensions of a tensor']
```

Usage

```
{'build_transformer_block': 'build a TransformerBlock with causal self-attention, conditional attention, and dense feed-forward layers using Haiku', 'create_attention_module': 'create an Attention module with multi-head attention, optional relative position embeddings, and caching support', 'build_causal_self_attention': 'build a CausalSelfAttention module that applies a causal mask to prevent attending to future tokens', 'create_positional_embedding': 'create a SinusoidalPositionEmbedding or RelativePositionEmbedding module for encoding sequence positions into transformer inputs', 'implement_tiled_dropout': 'implement tiled dropout that shares a random mask across trailing dimensions of a tensor'}
```

