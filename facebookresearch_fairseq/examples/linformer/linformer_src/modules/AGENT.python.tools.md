# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV layer for linear attention', 'review the LinformerTransformerEncoder class and its bi-directional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class that extends TransformerEncoder with compressed key-value linear attention', 'refactor the compress_layer initialization to support dynamic compression ratios or alternative initialization strategies', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer', 'build a MultiheadLinearAttention self-attention module using embed_dim and args for the Linformer encoder layer', 'upgrade an old checkpoint state dict to fix incorrect weight sharing in the Linformer encoder layer', 'review the LinformerTransformerEncoderLayer constructor to understand how shared_compress_layer is wrapped and version is registered', 'refactor the LinformerTransformerEncoderLayer to modify how the shared compression layer is initialized or shared across layers', 'create a MultiheadLinearAttention module with custom embed_dim, num_heads, and compression ratio for linformer self-attention', 'run forward pass on MultiheadLinearAttention with self-attention mode to compute compressed key-value attention on input queries', 'run forward pass on MultiheadLinearAttention in encoder-decoder mode with separate key and value tensors', 'reset all projection and compression layer weights in MultiheadLinearAttention using Xavier uniform initialization', 'upgrade a legacy state dict by splitting in_proj_weight into separate q_proj, k_proj, and v_proj weights']
```

Usage

```
{'build_LinformerTransformerEncoder': 'build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build_encoder_layer': 'build a LinformerTransformerEncoderLayer with optional shared compressed KV layer for linear attention', 'review_LinformerTransformerEncoder': 'review the LinformerTransformerEncoder class and its bi-directional Linformer-based sentence encoding implementation', 'summarize_LinformerTransformerEncoder': 'summarize the LinformerTransformerEncoder class that extends TransformerEncoder with compressed key-value linear attention', 'refactor_compress_layer': 'refactor the compress_layer initialization to support dynamic compression ratios or alternative initialization strategies'}
```

## File: facebookresearch_fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder_layer.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV layer for linear attention', 'review the LinformerTransformerEncoder class and its bi-directional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class that extends TransformerEncoder with compressed key-value linear attention', 'refactor the compress_layer initialization to support dynamic compression ratios or alternative initialization strategies', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer', 'build a MultiheadLinearAttention self-attention module using embed_dim and args for the Linformer encoder layer', 'upgrade an old checkpoint state dict to fix incorrect weight sharing in the Linformer encoder layer', 'review the LinformerTransformerEncoderLayer constructor to understand how shared_compress_layer is wrapped and version is registered', 'refactor the LinformerTransformerEncoderLayer to modify how the shared compression layer is initialized or shared across layers', 'create a MultiheadLinearAttention module with custom embed_dim, num_heads, and compression ratio for linformer self-attention', 'run forward pass on MultiheadLinearAttention with self-attention mode to compute compressed key-value attention on input queries', 'run forward pass on MultiheadLinearAttention in encoder-decoder mode with separate key and value tensors', 'reset all projection and compression layer weights in MultiheadLinearAttention using Xavier uniform initialization', 'upgrade a legacy state dict by splitting in_proj_weight into separate q_proj, k_proj, and v_proj weights']
```

Usage

```
{'build_LinformerTransformerEncoderLayer': 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer', 'build_self_attention_MultiheadLinearAttention': 'build a MultiheadLinearAttention self-attention module using embed_dim and args for the Linformer encoder layer', 'upgrade_state_dict_named_checkpoints': 'upgrade an old checkpoint state dict to fix incorrect weight sharing in the Linformer encoder layer', 'review_LinformerTransformerEncoderLayer_init': 'review the LinformerTransformerEncoderLayer constructor to understand how shared_compress_layer is wrapped and version is registered', 'refactor_LinformerTransformerEncoderLayer_compression': 'refactor the LinformerTransformerEncoderLayer to modify how the shared compression layer is initialized or shared across layers'}
```

## File: facebookresearch_fairseq/examples/linformer/linformer_src/modules/multihead_linear_attention.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV layer for linear attention', 'review the LinformerTransformerEncoder class and its bi-directional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class that extends TransformerEncoder with compressed key-value linear attention', 'refactor the compress_layer initialization to support dynamic compression ratios or alternative initialization strategies', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer', 'build a MultiheadLinearAttention self-attention module using embed_dim and args for the Linformer encoder layer', 'upgrade an old checkpoint state dict to fix incorrect weight sharing in the Linformer encoder layer', 'review the LinformerTransformerEncoderLayer constructor to understand how shared_compress_layer is wrapped and version is registered', 'refactor the LinformerTransformerEncoderLayer to modify how the shared compression layer is initialized or shared across layers', 'create a MultiheadLinearAttention module with custom embed_dim, num_heads, and compression ratio for linformer self-attention', 'run forward pass on MultiheadLinearAttention with self-attention mode to compute compressed key-value attention on input queries', 'run forward pass on MultiheadLinearAttention in encoder-decoder mode with separate key and value tensors', 'reset all projection and compression layer weights in MultiheadLinearAttention using Xavier uniform initialization', 'upgrade a legacy state dict by splitting in_proj_weight into separate q_proj, k_proj, and v_proj weights']
```

Usage

```
{'create_multihead_linear_attention': 'create a MultiheadLinearAttention module with custom embed_dim, num_heads, and compression ratio for linformer self-attention', 'run_forward_self_attention': 'run forward pass on MultiheadLinearAttention with self-attention mode to compute compressed key-value attention on input queries', 'run_forward_encoder_decoder_attention': 'run forward pass on MultiheadLinearAttention in encoder-decoder mode with separate key and value tensors', 'reset_parameters': 'reset all projection and compression layer weights in MultiheadLinearAttention using Xavier uniform initialization', 'upgrade_state_dict_named': 'upgrade a legacy state dict by splitting in_proj_weight into separate q_proj, k_proj, and v_proj weights'}
```

