# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/nn/transformer/attention.py

Prompts

```
['create a QKNormMultiheadAttention module with model_dim and num_heads for transformer attention', 'build a QKNormMultiheadAttention with enable_qk_layernorm to normalize queries and keys', 'run the forward pass of QKNormMultiheadAttention with seqs, keys, and values tensors', 'review the _project_q method that projects and normalizes query sequences', 'test QKNormMultiheadAttention with num_key_value_heads for grouped query attention support', 'create an LCMTransformerDecoder with transformer layers, layer norm factory, and self attention mask factory', 'build an LCMStandardTransformerDecoderLayer that extends StandardTransformerDecoderLayer with incremental state bag support', 'run the LCMTransformerDecoder forward pass with sequences, padding mask, and optional encoder output', 'review the LCMStandardTransformerDecoderLayer _forward_self_attn method for residual connections and norm order handling', 'test the LCMTransformerDecoder layer output hooks that execute after each decoder layer forward pass', 'build a Transformer decoder layer using TransformerFactory with a custom TransformerConfig', 'build a QKNormMultiheadAttention layer with optional RoPE positional encoding via the factory', 'build a feed-forward network with SwiGLU or standard activation using the factory', 'create a TransformerConfig dataclass to set dropout, FFN dim, and normalization hyperparameters', 'build a learned, sinusoidal, or rotary positional encoder using the factory methods']
```

Usage

```
{'create_QKNormMultiheadAttention': 'create a QKNormMultiheadAttention module with model_dim and num_heads for transformer attention', 'build_QKNormMultiheadAttention_with_qk_layernorm': 'build a QKNormMultiheadAttention with enable_qk_layernorm to normalize queries and keys', 'run_QKNormMultiheadAttention_forward': 'run the forward pass of QKNormMultiheadAttention with seqs, keys, and values tensors', 'review_QKNormMultiheadAttention_project_q': 'review the _project_q method that projects and normalizes query sequences', 'test_QKNormMultiheadAttention_grouped_query': 'test QKNormMultiheadAttention with num_key_value_heads for grouped query attention support'}
```

## File: facebookresearch_largeconceptmodel/lcm/nn/transformer/decoder.py

Prompts

```
['create a QKNormMultiheadAttention module with model_dim and num_heads for transformer attention', 'build a QKNormMultiheadAttention with enable_qk_layernorm to normalize queries and keys', 'run the forward pass of QKNormMultiheadAttention with seqs, keys, and values tensors', 'review the _project_q method that projects and normalizes query sequences', 'test QKNormMultiheadAttention with num_key_value_heads for grouped query attention support', 'create an LCMTransformerDecoder with transformer layers, layer norm factory, and self attention mask factory', 'build an LCMStandardTransformerDecoderLayer that extends StandardTransformerDecoderLayer with incremental state bag support', 'run the LCMTransformerDecoder forward pass with sequences, padding mask, and optional encoder output', 'review the LCMStandardTransformerDecoderLayer _forward_self_attn method for residual connections and norm order handling', 'test the LCMTransformerDecoder layer output hooks that execute after each decoder layer forward pass', 'build a Transformer decoder layer using TransformerFactory with a custom TransformerConfig', 'build a QKNormMultiheadAttention layer with optional RoPE positional encoding via the factory', 'build a feed-forward network with SwiGLU or standard activation using the factory', 'create a TransformerConfig dataclass to set dropout, FFN dim, and normalization hyperparameters', 'build a learned, sinusoidal, or rotary positional encoder using the factory methods']
```

Usage

```
{'create_LCMTransformerDecoder': 'create an LCMTransformerDecoder with transformer layers, layer norm factory, and self attention mask factory', 'build_LCMStandardTransformerDecoderLayer': 'build an LCMStandardTransformerDecoderLayer that extends StandardTransformerDecoderLayer with incremental state bag support', 'run_LCMTransformerDecoder_forward': 'run the LCMTransformerDecoder forward pass with sequences, padding mask, and optional encoder output', 'review_LCMStandardTransformerDecoderLayer_forward_self_attn': 'review the LCMStandardTransformerDecoderLayer _forward_self_attn method for residual connections and norm order handling', 'test_LCMTransformerDecoder_layer_hooks': 'test the LCMTransformerDecoder layer output hooks that execute after each decoder layer forward pass'}
```

## File: facebookresearch_largeconceptmodel/lcm/nn/transformer/factory.py

Prompts

```
['create a QKNormMultiheadAttention module with model_dim and num_heads for transformer attention', 'build a QKNormMultiheadAttention with enable_qk_layernorm to normalize queries and keys', 'run the forward pass of QKNormMultiheadAttention with seqs, keys, and values tensors', 'review the _project_q method that projects and normalizes query sequences', 'test QKNormMultiheadAttention with num_key_value_heads for grouped query attention support', 'create an LCMTransformerDecoder with transformer layers, layer norm factory, and self attention mask factory', 'build an LCMStandardTransformerDecoderLayer that extends StandardTransformerDecoderLayer with incremental state bag support', 'run the LCMTransformerDecoder forward pass with sequences, padding mask, and optional encoder output', 'review the LCMStandardTransformerDecoderLayer _forward_self_attn method for residual connections and norm order handling', 'test the LCMTransformerDecoder layer output hooks that execute after each decoder layer forward pass', 'build a Transformer decoder layer using TransformerFactory with a custom TransformerConfig', 'build a QKNormMultiheadAttention layer with optional RoPE positional encoding via the factory', 'build a feed-forward network with SwiGLU or standard activation using the factory', 'create a TransformerConfig dataclass to set dropout, FFN dim, and normalization hyperparameters', 'build a learned, sinusoidal, or rotary positional encoder using the factory methods']
```

Usage

```
{'build_transformer_decoder_layer': 'build a Transformer decoder layer using TransformerFactory with a custom TransformerConfig', 'build_multihead_attention': 'build a QKNormMultiheadAttention layer with optional RoPE positional encoding via the factory', 'build_feed_forward_network': 'build a feed-forward network with SwiGLU or standard activation using the factory', 'create_transformer_config': 'create a TransformerConfig dataclass to set dropout, FFN dim, and normalization hyperparameters', 'build_positional_encoder': 'build a learned, sinusoidal, or rotary positional encoder using the factory methods'}
```

