# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/modules/attention.py

Prompts

```
['build a CrossAttention module with 8 heads and 64 dim_head for self-attention on query_dim 320', 'build a MemoryEfficientCrossAttention module using xformers for memory efficient attention with 8 heads', 'build a BasicTransformerBlock with self-attention, cross-attention, and feedforward layers for transformer processing', 'build a SpatialTransformer for image-like data with configurable depth, heads, and context dimensions', 'build a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'build a LitEma instance to maintain exponential moving average shadow parameters for a PyTorch model', 'run the LitEma forward pass to update shadow parameters with decay-weighted averages of model parameters', 'test the LitEma copy_to method to copy EMA shadow parameters back into the original model', 'review the LitEma store method to save current model parameters temporarily before applying EMA weights', 'refactor the LitEma restore method to recover previously stored model parameters after validation with EMA weights', 'build a TransformerWrapper with an Encoder to process token sequences and return logits', 'create an AttentionLayers module with configurable depth, heads, and causal attention', 'review the Attention class forward method for multi-head attention with masking and memory', 'test the FeedForward module with optional GEGLU activation and configurable dropout', 'summarize the AbsolutePositionalEmbedding and FixedPositionalEmbedding classes for sequence position encoding']
```

Usage

```
{'build_CrossAttention': 'build a CrossAttention module with 8 heads and 64 dim_head for self-attention on query_dim 320', 'build_MemoryEfficientCrossAttention': 'build a MemoryEfficientCrossAttention module using xformers for memory efficient attention with 8 heads', 'build_BasicTransformerBlock': 'build a BasicTransformerBlock with self-attention, cross-attention, and feedforward layers for transformer processing', 'build_SpatialTransformer': 'build a SpatialTransformer for image-like data with configurable depth, heads, and context dimensions', 'build_FeedForward': 'build a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/ema.py

Prompts

```
['build a CrossAttention module with 8 heads and 64 dim_head for self-attention on query_dim 320', 'build a MemoryEfficientCrossAttention module using xformers for memory efficient attention with 8 heads', 'build a BasicTransformerBlock with self-attention, cross-attention, and feedforward layers for transformer processing', 'build a SpatialTransformer for image-like data with configurable depth, heads, and context dimensions', 'build a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'build a LitEma instance to maintain exponential moving average shadow parameters for a PyTorch model', 'run the LitEma forward pass to update shadow parameters with decay-weighted averages of model parameters', 'test the LitEma copy_to method to copy EMA shadow parameters back into the original model', 'review the LitEma store method to save current model parameters temporarily before applying EMA weights', 'refactor the LitEma restore method to recover previously stored model parameters after validation with EMA weights', 'build a TransformerWrapper with an Encoder to process token sequences and return logits', 'create an AttentionLayers module with configurable depth, heads, and causal attention', 'review the Attention class forward method for multi-head attention with masking and memory', 'test the FeedForward module with optional GEGLU activation and configurable dropout', 'summarize the AbsolutePositionalEmbedding and FixedPositionalEmbedding classes for sequence position encoding']
```

Usage

```
{'build_LitEma': 'build a LitEma instance to maintain exponential moving average shadow parameters for a PyTorch model', 'run_LitEma_forward': 'run the LitEma forward pass to update shadow parameters with decay-weighted averages of model parameters', 'test_LitEma_copy_to': 'test the LitEma copy_to method to copy EMA shadow parameters back into the original model', 'review_LitEma_store': 'review the LitEma store method to save current model parameters temporarily before applying EMA weights', 'refactor_LitEma_restore': 'refactor the LitEma restore method to recover previously stored model parameters after validation with EMA weights'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/x_transformer.py

Prompts

```
['build a CrossAttention module with 8 heads and 64 dim_head for self-attention on query_dim 320', 'build a MemoryEfficientCrossAttention module using xformers for memory efficient attention with 8 heads', 'build a BasicTransformerBlock with self-attention, cross-attention, and feedforward layers for transformer processing', 'build a SpatialTransformer for image-like data with configurable depth, heads, and context dimensions', 'build a FeedForward module with optional GEGLU activation and configurable dropout for transformer blocks', 'build a LitEma instance to maintain exponential moving average shadow parameters for a PyTorch model', 'run the LitEma forward pass to update shadow parameters with decay-weighted averages of model parameters', 'test the LitEma copy_to method to copy EMA shadow parameters back into the original model', 'review the LitEma store method to save current model parameters temporarily before applying EMA weights', 'refactor the LitEma restore method to recover previously stored model parameters after validation with EMA weights', 'build a TransformerWrapper with an Encoder to process token sequences and return logits', 'create an AttentionLayers module with configurable depth, heads, and causal attention', 'review the Attention class forward method for multi-head attention with masking and memory', 'test the FeedForward module with optional GEGLU activation and configurable dropout', 'summarize the AbsolutePositionalEmbedding and FixedPositionalEmbedding classes for sequence position encoding']
```

Usage

```
{'build_TransformerWrapper': 'build a TransformerWrapper with an Encoder to process token sequences and return logits', 'create_AttentionLayers': 'create an AttentionLayers module with configurable depth, heads, and causal attention', 'review_Attention_forward': 'review the Attention class forward method for multi-head attention with masking and memory', 'test_FeedForward': 'test the FeedForward module with optional GEGLU activation and configurable dropout', 'summarize_PositionalEmbedding': 'summarize the AbsolutePositionalEmbedding and FixedPositionalEmbedding classes for sequence position encoding'}
```

