# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder.py

Prompts

```
['build a LinformerSentenceEncoder with configurable compression ratio and shared KV for BERT-style pre-training', 'create a LinformerSentenceEncoderLayer with compressed attention via build_transformer_sentence_encoder_layer method', 'upgrade the model state dict to map compress_layer keys to shared_compress_layer per layer', 'configure the LinformerSentenceEncoder with compressed attention dimension and optional shared layer KV compression', 'freeze the compress layer weights by setting freeze_compress to 1 in the encoder constructor', 'create a LinformerSentenceEncoderLayer with custom embedding_dim and num_attention_heads for BERT models', 'build a LinformerSentenceEncoderLayer with compressed attention using compressed and max_seq_len parameters', 'build a LinformerSentenceEncoderLayer with shared key-value compression via shared_kv_compressed and shared_compress_layer', 'review the LinformerSentenceEncoderLayer __init__ to understand linformer parameter initialization and defaults', 'review the build_self_attention method to see how MultiheadLinearAttention is instantiated with compression settings', 'build a MultiheadLinearAttention module with configurable embed_dim, num_heads, and compression ratio for linear complexity self-attention', 'create a forward pass through MultiheadLinearAttention with query, key, value tensors and optional key_padding_mask', 'test the reset_parameters method to verify Xavier initialization of projection and compression layer weights', 'review the upgrade_state_dict_named method that migrates legacy in_proj_weight into separate q_proj, k_proj, v_proj weights', 'refactor the reorder_incremental_state method to reorder buffered key-value states for beam search incremental generation']
```

Usage

```
{'build_linformer_encoder': 'build a LinformerSentenceEncoder with configurable compression ratio and shared KV for BERT-style pre-training', 'create_encoder_layer': 'create a LinformerSentenceEncoderLayer with compressed attention via build_transformer_sentence_encoder_layer method', 'upgrade_state_dict': 'upgrade the model state dict to map compress_layer keys to shared_compress_layer per layer', 'configure_compression': 'configure the LinformerSentenceEncoder with compressed attention dimension and optional shared layer KV compression', 'freeze_compress_layer': 'freeze the compress layer weights by setting freeze_compress to 1 in the encoder constructor'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder_layer.py

Prompts

```
['build a LinformerSentenceEncoder with configurable compression ratio and shared KV for BERT-style pre-training', 'create a LinformerSentenceEncoderLayer with compressed attention via build_transformer_sentence_encoder_layer method', 'upgrade the model state dict to map compress_layer keys to shared_compress_layer per layer', 'configure the LinformerSentenceEncoder with compressed attention dimension and optional shared layer KV compression', 'freeze the compress layer weights by setting freeze_compress to 1 in the encoder constructor', 'create a LinformerSentenceEncoderLayer with custom embedding_dim and num_attention_heads for BERT models', 'build a LinformerSentenceEncoderLayer with compressed attention using compressed and max_seq_len parameters', 'build a LinformerSentenceEncoderLayer with shared key-value compression via shared_kv_compressed and shared_compress_layer', 'review the LinformerSentenceEncoderLayer __init__ to understand linformer parameter initialization and defaults', 'review the build_self_attention method to see how MultiheadLinearAttention is instantiated with compression settings', 'build a MultiheadLinearAttention module with configurable embed_dim, num_heads, and compression ratio for linear complexity self-attention', 'create a forward pass through MultiheadLinearAttention with query, key, value tensors and optional key_padding_mask', 'test the reset_parameters method to verify Xavier initialization of projection and compression layer weights', 'review the upgrade_state_dict_named method that migrates legacy in_proj_weight into separate q_proj, k_proj, v_proj weights', 'refactor the reorder_incremental_state method to reorder buffered key-value states for beam search incremental generation']
```

Usage

```
{'create_LinformerSentenceEncoderLayer': 'create a LinformerSentenceEncoderLayer with custom embedding_dim and num_attention_heads for BERT models', 'build_LinformerSentenceEncoderLayer_with_compression': 'build a LinformerSentenceEncoderLayer with compressed attention using compressed and max_seq_len parameters', 'build_LinformerSentenceEncoderLayer_with_shared_kv': 'build a LinformerSentenceEncoderLayer with shared key-value compression via shared_kv_compressed and shared_compress_layer', 'review_LinformerSentenceEncoderLayer_init': 'review the LinformerSentenceEncoderLayer __init__ to understand linformer parameter initialization and defaults', 'review_build_self_attention': 'review the build_self_attention method to see how MultiheadLinearAttention is instantiated with compression settings'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/linformer/linformer_src/modules/multihead_linear_attention.py

Prompts

```
['build a LinformerSentenceEncoder with configurable compression ratio and shared KV for BERT-style pre-training', 'create a LinformerSentenceEncoderLayer with compressed attention via build_transformer_sentence_encoder_layer method', 'upgrade the model state dict to map compress_layer keys to shared_compress_layer per layer', 'configure the LinformerSentenceEncoder with compressed attention dimension and optional shared layer KV compression', 'freeze the compress layer weights by setting freeze_compress to 1 in the encoder constructor', 'create a LinformerSentenceEncoderLayer with custom embedding_dim and num_attention_heads for BERT models', 'build a LinformerSentenceEncoderLayer with compressed attention using compressed and max_seq_len parameters', 'build a LinformerSentenceEncoderLayer with shared key-value compression via shared_kv_compressed and shared_compress_layer', 'review the LinformerSentenceEncoderLayer __init__ to understand linformer parameter initialization and defaults', 'review the build_self_attention method to see how MultiheadLinearAttention is instantiated with compression settings', 'build a MultiheadLinearAttention module with configurable embed_dim, num_heads, and compression ratio for linear complexity self-attention', 'create a forward pass through MultiheadLinearAttention with query, key, value tensors and optional key_padding_mask', 'test the reset_parameters method to verify Xavier initialization of projection and compression layer weights', 'review the upgrade_state_dict_named method that migrates legacy in_proj_weight into separate q_proj, k_proj, v_proj weights', 'refactor the reorder_incremental_state method to reorder buffered key-value states for beam search incremental generation']
```

Usage

```
{'build_MultiheadLinearAttention': 'build a MultiheadLinearAttention module with configurable embed_dim, num_heads, and compression ratio for linear complexity self-attention', 'create_forward_pass': 'create a forward pass through MultiheadLinearAttention with query, key, value tensors and optional key_padding_mask', 'test_reset_parameters': 'test the reset_parameters method to verify Xavier initialization of projection and compression layer weights', 'review_upgrade_state_dict_named': 'review the upgrade_state_dict_named method that migrates legacy in_proj_weight into separate q_proj, k_proj, v_proj weights', 'refactor_reorder_incremental_state': 'refactor the reorder_incremental_state method to reorder buffered key-value states for beam search incremental generation'}
```

