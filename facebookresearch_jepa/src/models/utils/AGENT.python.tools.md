# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/src/models/utils/modules.py

Prompts

```
['build a two-layer MLP neural network module with configurable hidden features and GELU activation', 'create a multi-head self-attention module with optional SDPA and manual attention computation modes', 'build a transformer encoder block combining self-attention and MLP with residual connections and layer norm', 'create a cross-attention module that attends queries against separate key-value inputs using SDPA', 'build a cross-attention transformer block combining cross-attention and MLP with residual connections and layer norm', 'create a MultiMaskWrapper around a backbone model to apply multiple masks in forward pass', 'run the MultiMaskWrapper forward pass with input tensor and optional list of masks', 'create a PredictorMultiMaskWrapper around a backbone model for context-target multimask prediction', 'run the PredictorMultiMaskWrapper forward pass with context, target, and their respective masks', 'review the MultiMaskWrapper and PredictorMultiMaskWrapper classes for backbone wrapping and multimask forwarding patterns', 'create a PatchEmbed module that converts 2D image tensors into patch embeddings using a convolutional projection layer', 'create a PatchEmbed3D module that converts 3D video tensors into patch embeddings using a 3D convolutional projection layer', 'run the PatchEmbed forward pass on a batch of 2D image tensors to get flattened patch embeddings', 'run the PatchEmbed3D forward pass on a batch of 3D video tensors to get flattened tubelet embeddings', 'review the PatchEmbed class configuration for patch_size, in_chans, and embed_dim parameters', 'generate 3D sinusoidal positional embeddings for a grid with specified depth, height, and width dimensions', 'generate 2D sinusoidal positional embeddings for a square grid with optional class token support', 'generate 1D sinusoidal positional embeddings for a sequence of positions with optional class token', 'compute sinusoidal positional embeddings from arbitrary grid positions using sine and cosine basis functions', 'review the positional embedding utility functions for 1D, 2D, and 3D grid encoding']
```

Usage

```
{'build_MLP': 'build a two-layer MLP neural network module with configurable hidden features and GELU activation', 'create_Attention': 'create a multi-head self-attention module with optional SDPA and manual attention computation modes', 'build_Block': 'build a transformer encoder block combining self-attention and MLP with residual connections and layer norm', 'create_CrossAttention': 'create a cross-attention module that attends queries against separate key-value inputs using SDPA', 'build_CrossAttentionBlock': 'build a cross-attention transformer block combining cross-attention and MLP with residual connections and layer norm'}
```

## File: facebookresearch_jepa/src/models/utils/multimask.py

Prompts

```
['build a two-layer MLP neural network module with configurable hidden features and GELU activation', 'create a multi-head self-attention module with optional SDPA and manual attention computation modes', 'build a transformer encoder block combining self-attention and MLP with residual connections and layer norm', 'create a cross-attention module that attends queries against separate key-value inputs using SDPA', 'build a cross-attention transformer block combining cross-attention and MLP with residual connections and layer norm', 'create a MultiMaskWrapper around a backbone model to apply multiple masks in forward pass', 'run the MultiMaskWrapper forward pass with input tensor and optional list of masks', 'create a PredictorMultiMaskWrapper around a backbone model for context-target multimask prediction', 'run the PredictorMultiMaskWrapper forward pass with context, target, and their respective masks', 'review the MultiMaskWrapper and PredictorMultiMaskWrapper classes for backbone wrapping and multimask forwarding patterns', 'create a PatchEmbed module that converts 2D image tensors into patch embeddings using a convolutional projection layer', 'create a PatchEmbed3D module that converts 3D video tensors into patch embeddings using a 3D convolutional projection layer', 'run the PatchEmbed forward pass on a batch of 2D image tensors to get flattened patch embeddings', 'run the PatchEmbed3D forward pass on a batch of 3D video tensors to get flattened tubelet embeddings', 'review the PatchEmbed class configuration for patch_size, in_chans, and embed_dim parameters', 'generate 3D sinusoidal positional embeddings for a grid with specified depth, height, and width dimensions', 'generate 2D sinusoidal positional embeddings for a square grid with optional class token support', 'generate 1D sinusoidal positional embeddings for a sequence of positions with optional class token', 'compute sinusoidal positional embeddings from arbitrary grid positions using sine and cosine basis functions', 'review the positional embedding utility functions for 1D, 2D, and 3D grid encoding']
```

Usage

```
{'create_multimask_wrapper': 'create a MultiMaskWrapper around a backbone model to apply multiple masks in forward pass', 'run_multimask_forward': 'run the MultiMaskWrapper forward pass with input tensor and optional list of masks', 'create_predictor_multimask_wrapper': 'create a PredictorMultiMaskWrapper around a backbone model for context-target multimask prediction', 'run_predictor_multimask_forward': 'run the PredictorMultiMaskWrapper forward pass with context, target, and their respective masks', 'review_multimask_classes': 'review the MultiMaskWrapper and PredictorMultiMaskWrapper classes for backbone wrapping and multimask forwarding patterns'}
```

## File: facebookresearch_jepa/src/models/utils/patch_embed.py

Prompts

```
['build a two-layer MLP neural network module with configurable hidden features and GELU activation', 'create a multi-head self-attention module with optional SDPA and manual attention computation modes', 'build a transformer encoder block combining self-attention and MLP with residual connections and layer norm', 'create a cross-attention module that attends queries against separate key-value inputs using SDPA', 'build a cross-attention transformer block combining cross-attention and MLP with residual connections and layer norm', 'create a MultiMaskWrapper around a backbone model to apply multiple masks in forward pass', 'run the MultiMaskWrapper forward pass with input tensor and optional list of masks', 'create a PredictorMultiMaskWrapper around a backbone model for context-target multimask prediction', 'run the PredictorMultiMaskWrapper forward pass with context, target, and their respective masks', 'review the MultiMaskWrapper and PredictorMultiMaskWrapper classes for backbone wrapping and multimask forwarding patterns', 'create a PatchEmbed module that converts 2D image tensors into patch embeddings using a convolutional projection layer', 'create a PatchEmbed3D module that converts 3D video tensors into patch embeddings using a 3D convolutional projection layer', 'run the PatchEmbed forward pass on a batch of 2D image tensors to get flattened patch embeddings', 'run the PatchEmbed3D forward pass on a batch of 3D video tensors to get flattened tubelet embeddings', 'review the PatchEmbed class configuration for patch_size, in_chans, and embed_dim parameters', 'generate 3D sinusoidal positional embeddings for a grid with specified depth, height, and width dimensions', 'generate 2D sinusoidal positional embeddings for a square grid with optional class token support', 'generate 1D sinusoidal positional embeddings for a sequence of positions with optional class token', 'compute sinusoidal positional embeddings from arbitrary grid positions using sine and cosine basis functions', 'review the positional embedding utility functions for 1D, 2D, and 3D grid encoding']
```

Usage

```
{'create_PatchEmbed_2D': 'create a PatchEmbed module that converts 2D image tensors into patch embeddings using a convolutional projection layer', 'create_PatchEmbed3D': 'create a PatchEmbed3D module that converts 3D video tensors into patch embeddings using a 3D convolutional projection layer', 'run_PatchEmbed_forward': 'run the PatchEmbed forward pass on a batch of 2D image tensors to get flattened patch embeddings', 'run_PatchEmbed3D_forward': 'run the PatchEmbed3D forward pass on a batch of 3D video tensors to get flattened tubelet embeddings', 'review_PatchEmbed_config': 'review the PatchEmbed class configuration for patch_size, in_chans, and embed_dim parameters'}
```

## File: facebookresearch_jepa/src/models/utils/pos_embs.py

Prompts

```
['build a two-layer MLP neural network module with configurable hidden features and GELU activation', 'create a multi-head self-attention module with optional SDPA and manual attention computation modes', 'build a transformer encoder block combining self-attention and MLP with residual connections and layer norm', 'create a cross-attention module that attends queries against separate key-value inputs using SDPA', 'build a cross-attention transformer block combining cross-attention and MLP with residual connections and layer norm', 'create a MultiMaskWrapper around a backbone model to apply multiple masks in forward pass', 'run the MultiMaskWrapper forward pass with input tensor and optional list of masks', 'create a PredictorMultiMaskWrapper around a backbone model for context-target multimask prediction', 'run the PredictorMultiMaskWrapper forward pass with context, target, and their respective masks', 'review the MultiMaskWrapper and PredictorMultiMaskWrapper classes for backbone wrapping and multimask forwarding patterns', 'create a PatchEmbed module that converts 2D image tensors into patch embeddings using a convolutional projection layer', 'create a PatchEmbed3D module that converts 3D video tensors into patch embeddings using a 3D convolutional projection layer', 'run the PatchEmbed forward pass on a batch of 2D image tensors to get flattened patch embeddings', 'run the PatchEmbed3D forward pass on a batch of 3D video tensors to get flattened tubelet embeddings', 'review the PatchEmbed class configuration for patch_size, in_chans, and embed_dim parameters', 'generate 3D sinusoidal positional embeddings for a grid with specified depth, height, and width dimensions', 'generate 2D sinusoidal positional embeddings for a square grid with optional class token support', 'generate 1D sinusoidal positional embeddings for a sequence of positions with optional class token', 'compute sinusoidal positional embeddings from arbitrary grid positions using sine and cosine basis functions', 'review the positional embedding utility functions for 1D, 2D, and 3D grid encoding']
```

Usage

```
{'generate_3d_sincos_positional_embeddings': 'generate 3D sinusoidal positional embeddings for a grid with specified depth, height, and width dimensions', 'generate_2d_sincos_positional_embeddings': 'generate 2D sinusoidal positional embeddings for a square grid with optional class token support', 'generate_1d_sincos_positional_embeddings': 'generate 1D sinusoidal positional embeddings for a sequence of positions with optional class token', 'compute_sincos_embeddings_from_grid_positions': 'compute sinusoidal positional embeddings from arbitrary grid positions using sine and cosine basis functions', 'review_positional_embedding_functions': 'review the positional embedding utility functions for 1D, 2D, and 3D grid encoding'}
```

