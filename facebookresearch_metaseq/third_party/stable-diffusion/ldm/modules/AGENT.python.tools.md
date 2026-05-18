# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/attention.py

Prompts

```
['build a multi-head cross-attention module with query, key, value projections and optional masking', 'build a transformer block for image-like data that projects spatial features and applies transformer layers', 'build a transformer block with self-attention, cross-attention, and gated feed-forward with layer normalization', 'build a feed-forward network with optional GEGLU activation and configurable hidden dimension multiplier', 'build a linear-time attention module using softmax-normalized keys for efficient 2D feature processing', 'build a LitEma wrapper for a PyTorch model with configurable decay and shadow parameter tracking', 'run the LitEma forward pass to update shadow parameters using exponential moving average', 'create a copy of EMA shadow parameters back into the original model using copy_to', 'test the LitEma store and restore methods to temporarily save and recover model parameters', 'review the LitEma class initialization to understand decay validation and buffer registration for shadow parameters', 'build a TransformerWrapper with AttentionLayers to process token sequences and return logits', 'create an AttentionLayers module with configurable depth heads and causal attention for sequence modeling', 'build an Attention module with multi-head self-attention talking heads and sparse top-k support', 'create a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'review the Encoder class which wraps AttentionLayers with causal disabled for bidirectional encoding']
```

Usage

```
{'build_CrossAttention': 'build a multi-head cross-attention module with query, key, value projections and optional masking', 'build_SpatialTransformer': 'build a transformer block for image-like data that projects spatial features and applies transformer layers', 'build_BasicTransformerBlock': 'build a transformer block with self-attention, cross-attention, and gated feed-forward with layer normalization', 'build_FeedForward': 'build a feed-forward network with optional GEGLU activation and configurable hidden dimension multiplier', 'build_LinearAttention': 'build a linear-time attention module using softmax-normalized keys for efficient 2D feature processing'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/ema.py

Prompts

```
['build a multi-head cross-attention module with query, key, value projections and optional masking', 'build a transformer block for image-like data that projects spatial features and applies transformer layers', 'build a transformer block with self-attention, cross-attention, and gated feed-forward with layer normalization', 'build a feed-forward network with optional GEGLU activation and configurable hidden dimension multiplier', 'build a linear-time attention module using softmax-normalized keys for efficient 2D feature processing', 'build a LitEma wrapper for a PyTorch model with configurable decay and shadow parameter tracking', 'run the LitEma forward pass to update shadow parameters using exponential moving average', 'create a copy of EMA shadow parameters back into the original model using copy_to', 'test the LitEma store and restore methods to temporarily save and recover model parameters', 'review the LitEma class initialization to understand decay validation and buffer registration for shadow parameters', 'build a TransformerWrapper with AttentionLayers to process token sequences and return logits', 'create an AttentionLayers module with configurable depth heads and causal attention for sequence modeling', 'build an Attention module with multi-head self-attention talking heads and sparse top-k support', 'create a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'review the Encoder class which wraps AttentionLayers with causal disabled for bidirectional encoding']
```

Usage

```
{'build_LitEma_ema_wrapper': 'build a LitEma wrapper for a PyTorch model with configurable decay and shadow parameter tracking', 'run_LitEma_forward_update': 'run the LitEma forward pass to update shadow parameters using exponential moving average', 'create_LitEma_copy_to': 'create a copy of EMA shadow parameters back into the original model using copy_to', 'test_LitEma_store_restore': 'test the LitEma store and restore methods to temporarily save and recover model parameters', 'review_LitEma_initialization': 'review the LitEma class initialization to understand decay validation and buffer registration for shadow parameters'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/x_transformer.py

Prompts

```
['build a multi-head cross-attention module with query, key, value projections and optional masking', 'build a transformer block for image-like data that projects spatial features and applies transformer layers', 'build a transformer block with self-attention, cross-attention, and gated feed-forward with layer normalization', 'build a feed-forward network with optional GEGLU activation and configurable hidden dimension multiplier', 'build a linear-time attention module using softmax-normalized keys for efficient 2D feature processing', 'build a LitEma wrapper for a PyTorch model with configurable decay and shadow parameter tracking', 'run the LitEma forward pass to update shadow parameters using exponential moving average', 'create a copy of EMA shadow parameters back into the original model using copy_to', 'test the LitEma store and restore methods to temporarily save and recover model parameters', 'review the LitEma class initialization to understand decay validation and buffer registration for shadow parameters', 'build a TransformerWrapper with AttentionLayers to process token sequences and return logits', 'create an AttentionLayers module with configurable depth heads and causal attention for sequence modeling', 'build an Attention module with multi-head self-attention talking heads and sparse top-k support', 'create a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'review the Encoder class which wraps AttentionLayers with causal disabled for bidirectional encoding']
```

Usage

```
{'build_transformer_wrapper': 'build a TransformerWrapper with AttentionLayers to process token sequences and return logits', 'create_attention_layers': 'create an AttentionLayers module with configurable depth heads and causal attention for sequence modeling', 'build_attention_module': 'build an Attention module with multi-head self-attention talking heads and sparse top-k support', 'create_feedforward_module': 'create a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'review_encoder_class': 'review the Encoder class which wraps AttentionLayers with causal disabled for bidirectional encoding'}
```

