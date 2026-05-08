# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/model/parallelize_transformer.py

Prompts

```
['apply tensor parallelism to a transformer model and cast parameters to the specified dtype', 'cast all model parameters to a specified torch dtype like float16 or bfloat16', 'apply tensor and sequence parallelism to a single transformer block with attention and feed-forward layers', 'apply tensor parallelism to a model including embedding, norm, output layer, and all transformer blocks', 'review the parallelize_transformer module to understand tensor parallelism strategies for decoder-only transformer models', 'build a decoder-only transformer language model using TransformerArgs to configure dim, n_layers, n_heads, and vocab_size', 'create a TransformerArgs dataclass to configure model dimensions, attention heads, sequence length, and positional encoding', 'configure sliding window attention with WindowAttentionArgs to set local and global window sizes and layer patterns', 'build an Attention module with configurable QKV projections, grouped query attention via n_kv_heads, and optional biases', 'review the TransformerBlock class that combines Attention, FeedForward with SwiGLU, and RMSNorm layers per transformer layer']
```

Usage

```
{'parallelize_model': 'apply tensor parallelism to a transformer model and cast parameters to the specified dtype', 'cast_model_parameters': 'cast all model parameters to a specified torch dtype like float16 or bfloat16', 'apply_tp_to_block': 'apply tensor and sequence parallelism to a single transformer block with attention and feed-forward layers', 'apply_tp': 'apply tensor parallelism to a model including embedding, norm, output layer, and all transformer blocks', 'review_parallelize_transformer': 'review the parallelize_transformer module to understand tensor parallelism strategies for decoder-only transformer models'}
```

## File: facebookresearch_cwm/cwm/model/transformer.py

Prompts

```
['apply tensor parallelism to a transformer model and cast parameters to the specified dtype', 'cast all model parameters to a specified torch dtype like float16 or bfloat16', 'apply tensor and sequence parallelism to a single transformer block with attention and feed-forward layers', 'apply tensor parallelism to a model including embedding, norm, output layer, and all transformer blocks', 'review the parallelize_transformer module to understand tensor parallelism strategies for decoder-only transformer models', 'build a decoder-only transformer language model using TransformerArgs to configure dim, n_layers, n_heads, and vocab_size', 'create a TransformerArgs dataclass to configure model dimensions, attention heads, sequence length, and positional encoding', 'configure sliding window attention with WindowAttentionArgs to set local and global window sizes and layer patterns', 'build an Attention module with configurable QKV projections, grouped query attention via n_kv_heads, and optional biases', 'review the TransformerBlock class that combines Attention, FeedForward with SwiGLU, and RMSNorm layers per transformer layer']
```

Usage

```
{'build_transformer_model': 'build a decoder-only transformer language model using TransformerArgs to configure dim, n_layers, n_heads, and vocab_size', 'create_transformer_args': 'create a TransformerArgs dataclass to configure model dimensions, attention heads, sequence length, and positional encoding', 'configure_window_attention': 'configure sliding window attention with WindowAttentionArgs to set local and global window sizes and layer patterns', 'build_attention_module': 'build an Attention module with configurable QKV projections, grouped query attention via n_kv_heads, and optional biases', 'review_transformerblock': 'review the TransformerBlock class that combines Attention, FeedForward with SwiGLU, and RMSNorm layers per transformer layer'}
```

