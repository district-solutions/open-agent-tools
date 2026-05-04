# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/models/utils/builder.py

Prompts

```
['build a Transformer model instance from a config dict using the TRANSFORMER registry', 'build a Position Encoding instance from a config dict using the POSITIONAL_ENCODING registry', 'register a custom Transformer class with the TRANSFORMER registry for use in config-driven builds', 'register a custom Position Encoding class with the POSITIONAL_ENCODING registry for config-driven builds', 'inspect the TRANSFORMER registry to list all registered Transformer module names', 'build a python module to generate a 2D gaussian kernel tensor with a given radius and sigma', 'create a function that generates a 2D gaussian heatmap by overlaying a gaussian kernel on an input heatmap', 'compute the optimal 2D gaussian radius for a detection box given a minimum IoU overlap threshold', 'test the gaussian2D function to verify it returns a correctly shaped tensor with proper gaussian distribution', 'review the gaussian_radius function and its three quadratic equation cases for computing optimal kernel radius', 'build a SinePositionalEncoding module with configurable num_feats, temperature, and normalization for transformer models', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for object detection', 'test SinePositionalEncoding forward pass with a binary mask tensor to verify output shape', 'test LearnedPositionalEncoding forward pass with a mask tensor to verify learned embeddings', 'review SinePositionalEncoding and LearnedPositionalEncoding classes to compare sine-based vs learnable position embedding approaches', 'build a DETR transformer model with configurable encoder and decoder layers for object detection', 'create a transformer encoder with stacked self-attention and feed-forward network layers', 'create a transformer decoder with self-attention, cross-attention, and feed-forward network layers', 'review the MultiheadAttention wrapper that adds residual connections and positional encoding support', 'refactor the feed-forward network to customize activation functions, dropout, or residual connection behavior']
```

Usage

```
{'build_transformer_from_cfg': 'build a Transformer model instance from a config dict using the TRANSFORMER registry', 'build_positional_encoding_from_cfg': 'build a Position Encoding instance from a config dict using the POSITIONAL_ENCODING registry', 'register_custom_transformer': 'register a custom Transformer class with the TRANSFORMER registry for use in config-driven builds', 'register_custom_positional_encoding': 'register a custom Position Encoding class with the POSITIONAL_ENCODING registry for config-driven builds', 'inspect_transformer_registry': 'inspect the TRANSFORMER registry to list all registered Transformer module names'}
```

## File: facebookresearch_generic-grouping/mmdet/models/utils/gaussian_target.py

Prompts

```
['build a Transformer model instance from a config dict using the TRANSFORMER registry', 'build a Position Encoding instance from a config dict using the POSITIONAL_ENCODING registry', 'register a custom Transformer class with the TRANSFORMER registry for use in config-driven builds', 'register a custom Position Encoding class with the POSITIONAL_ENCODING registry for config-driven builds', 'inspect the TRANSFORMER registry to list all registered Transformer module names', 'build a python module to generate a 2D gaussian kernel tensor with a given radius and sigma', 'create a function that generates a 2D gaussian heatmap by overlaying a gaussian kernel on an input heatmap', 'compute the optimal 2D gaussian radius for a detection box given a minimum IoU overlap threshold', 'test the gaussian2D function to verify it returns a correctly shaped tensor with proper gaussian distribution', 'review the gaussian_radius function and its three quadratic equation cases for computing optimal kernel radius', 'build a SinePositionalEncoding module with configurable num_feats, temperature, and normalization for transformer models', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for object detection', 'test SinePositionalEncoding forward pass with a binary mask tensor to verify output shape', 'test LearnedPositionalEncoding forward pass with a mask tensor to verify learned embeddings', 'review SinePositionalEncoding and LearnedPositionalEncoding classes to compare sine-based vs learnable position embedding approaches', 'build a DETR transformer model with configurable encoder and decoder layers for object detection', 'create a transformer encoder with stacked self-attention and feed-forward network layers', 'create a transformer decoder with self-attention, cross-attention, and feed-forward network layers', 'review the MultiheadAttention wrapper that adds residual connections and positional encoding support', 'refactor the feed-forward network to customize activation functions, dropout, or residual connection behavior']
```

Usage

```
{'build_gaussian2D_kernel': 'build a python module to generate a 2D gaussian kernel tensor with a given radius and sigma', 'create_gaussian_heatmap': 'create a function that generates a 2D gaussian heatmap by overlaying a gaussian kernel on an input heatmap', 'compute_gaussian_radius': 'compute the optimal 2D gaussian radius for a detection box given a minimum IoU overlap threshold', 'test_gaussian2D': 'test the gaussian2D function to verify it returns a correctly shaped tensor with proper gaussian distribution', 'review_gaussian_radius': 'review the gaussian_radius function and its three quadratic equation cases for computing optimal kernel radius'}
```

## File: facebookresearch_generic-grouping/mmdet/models/utils/positional_encoding.py

Prompts

```
['build a Transformer model instance from a config dict using the TRANSFORMER registry', 'build a Position Encoding instance from a config dict using the POSITIONAL_ENCODING registry', 'register a custom Transformer class with the TRANSFORMER registry for use in config-driven builds', 'register a custom Position Encoding class with the POSITIONAL_ENCODING registry for config-driven builds', 'inspect the TRANSFORMER registry to list all registered Transformer module names', 'build a python module to generate a 2D gaussian kernel tensor with a given radius and sigma', 'create a function that generates a 2D gaussian heatmap by overlaying a gaussian kernel on an input heatmap', 'compute the optimal 2D gaussian radius for a detection box given a minimum IoU overlap threshold', 'test the gaussian2D function to verify it returns a correctly shaped tensor with proper gaussian distribution', 'review the gaussian_radius function and its three quadratic equation cases for computing optimal kernel radius', 'build a SinePositionalEncoding module with configurable num_feats, temperature, and normalization for transformer models', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for object detection', 'test SinePositionalEncoding forward pass with a binary mask tensor to verify output shape', 'test LearnedPositionalEncoding forward pass with a mask tensor to verify learned embeddings', 'review SinePositionalEncoding and LearnedPositionalEncoding classes to compare sine-based vs learnable position embedding approaches', 'build a DETR transformer model with configurable encoder and decoder layers for object detection', 'create a transformer encoder with stacked self-attention and feed-forward network layers', 'create a transformer decoder with self-attention, cross-attention, and feed-forward network layers', 'review the MultiheadAttention wrapper that adds residual connections and positional encoding support', 'refactor the feed-forward network to customize activation functions, dropout, or residual connection behavior']
```

Usage

```
{'build_sine_positional_encoding': 'build a SinePositionalEncoding module with configurable num_feats, temperature, and normalization for transformer models', 'build_learned_positional_encoding': 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for object detection', 'test_sine_positional_encoding_forward': 'test SinePositionalEncoding forward pass with a binary mask tensor to verify output shape', 'test_learned_positional_encoding_forward': 'test LearnedPositionalEncoding forward pass with a mask tensor to verify learned embeddings', 'review_positional_encoding_classes': 'review SinePositionalEncoding and LearnedPositionalEncoding classes to compare sine-based vs learnable position embedding approaches'}
```

## File: facebookresearch_generic-grouping/mmdet/models/utils/transformer.py

Prompts

```
['build a Transformer model instance from a config dict using the TRANSFORMER registry', 'build a Position Encoding instance from a config dict using the POSITIONAL_ENCODING registry', 'register a custom Transformer class with the TRANSFORMER registry for use in config-driven builds', 'register a custom Position Encoding class with the POSITIONAL_ENCODING registry for config-driven builds', 'inspect the TRANSFORMER registry to list all registered Transformer module names', 'build a python module to generate a 2D gaussian kernel tensor with a given radius and sigma', 'create a function that generates a 2D gaussian heatmap by overlaying a gaussian kernel on an input heatmap', 'compute the optimal 2D gaussian radius for a detection box given a minimum IoU overlap threshold', 'test the gaussian2D function to verify it returns a correctly shaped tensor with proper gaussian distribution', 'review the gaussian_radius function and its three quadratic equation cases for computing optimal kernel radius', 'build a SinePositionalEncoding module with configurable num_feats, temperature, and normalization for transformer models', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for object detection', 'test SinePositionalEncoding forward pass with a binary mask tensor to verify output shape', 'test LearnedPositionalEncoding forward pass with a mask tensor to verify learned embeddings', 'review SinePositionalEncoding and LearnedPositionalEncoding classes to compare sine-based vs learnable position embedding approaches', 'build a DETR transformer model with configurable encoder and decoder layers for object detection', 'create a transformer encoder with stacked self-attention and feed-forward network layers', 'create a transformer decoder with self-attention, cross-attention, and feed-forward network layers', 'review the MultiheadAttention wrapper that adds residual connections and positional encoding support', 'refactor the feed-forward network to customize activation functions, dropout, or residual connection behavior']
```

Usage

```
{'build_Transformer': 'build a DETR transformer model with configurable encoder and decoder layers for object detection', 'create_TransformerEncoder': 'create a transformer encoder with stacked self-attention and feed-forward network layers', 'create_TransformerDecoder': 'create a transformer decoder with self-attention, cross-attention, and feed-forward network layers', 'review_MultiheadAttention': 'review the MultiheadAttention wrapper that adds residual connections and positional encoding support', 'refactor_FFN': 'refactor the feed-forward network to customize activation functions, dropout, or residual connection behavior'}
```

