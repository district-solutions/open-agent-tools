# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV linear layer and Xavier initialization', 'review the LinformerTransformerEncoder class and its bidirectional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class which extends TransformerEncoder for efficient attention via compression', 'test the build_encoder_layer method to verify compress layer creation and freezing logic', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer for BERT-style models', 'build a MultiheadLinearAttention self-attention module with compressed key-value projections and configurable quantization noise', 'upgrade a state dict to version 2 and fix incorrect weight sharing from old checkpoints', 'review the LinformerTransformerEncoderLayer constructor to understand shared compression layer wrapping and version buffer registration', 'refactor the LinformerTransformerEncoderLayer self-attention to adjust compression dimensions, head count, or freeze settings', 'build a linformer multi-head linear attention module with compressed key and value projections for linear complexity self-attention', 'create a forward pass through the multihead linear attention layer with query key and value tensors', 'test the multihead linear attention module in self-attention mode with sequence compression via linear projections', 'review the reset_parameters method that initializes projection and compression weights with Xavier uniform initialization', 'summarize the incremental state management methods for buffered key value and padding mask during autoregressive decoding']
```

Usage

```
{'build_LinformerTransformerEncoder': 'build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build_encoder_layer': 'build a LinformerTransformerEncoderLayer with optional shared compressed KV linear layer and Xavier initialization', 'review_LinformerTransformerEncoder': 'review the LinformerTransformerEncoder class and its bidirectional Linformer-based sentence encoding implementation', 'summarize_LinformerTransformerEncoder': 'summarize the LinformerTransformerEncoder class which extends TransformerEncoder for efficient attention via compression', 'test_build_encoder_layer': 'test the build_encoder_layer method to verify compress layer creation and freezing logic'}
```

## File: facebookresearch_avhubert/fairseq/examples/linformer/linformer_src/modules/linformer_sentence_encoder_layer.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV linear layer and Xavier initialization', 'review the LinformerTransformerEncoder class and its bidirectional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class which extends TransformerEncoder for efficient attention via compression', 'test the build_encoder_layer method to verify compress layer creation and freezing logic', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer for BERT-style models', 'build a MultiheadLinearAttention self-attention module with compressed key-value projections and configurable quantization noise', 'upgrade a state dict to version 2 and fix incorrect weight sharing from old checkpoints', 'review the LinformerTransformerEncoderLayer constructor to understand shared compression layer wrapping and version buffer registration', 'refactor the LinformerTransformerEncoderLayer self-attention to adjust compression dimensions, head count, or freeze settings', 'build a linformer multi-head linear attention module with compressed key and value projections for linear complexity self-attention', 'create a forward pass through the multihead linear attention layer with query key and value tensors', 'test the multihead linear attention module in self-attention mode with sequence compression via linear projections', 'review the reset_parameters method that initializes projection and compression weights with Xavier uniform initialization', 'summarize the incremental state management methods for buffered key value and padding mask during autoregressive decoding']
```

Usage

```
{'build_LinformerTransformerEncoderLayer': 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer for BERT-style models', 'build_self_attention_MultiheadLinearAttention': 'build a MultiheadLinearAttention self-attention module with compressed key-value projections and configurable quantization noise', 'upgrade_state_dict_named_version_migration': 'upgrade a state dict to version 2 and fix incorrect weight sharing from old checkpoints', 'review_LinformerTransformerEncoderLayer_init': 'review the LinformerTransformerEncoderLayer constructor to understand shared compression layer wrapping and version buffer registration', 'refactor_LinformerTransformerEncoderLayer_attention': 'refactor the LinformerTransformerEncoderLayer self-attention to adjust compression dimensions, head count, or freeze settings'}
```

## File: facebookresearch_avhubert/fairseq/examples/linformer/linformer_src/modules/multihead_linear_attention.py

Prompts

```
['build a LinformerTransformerEncoder with args, dictionary, and embed_tokens for BERT-style sentence encoding', 'build a LinformerTransformerEncoderLayer with optional shared compressed KV linear layer and Xavier initialization', 'review the LinformerTransformerEncoder class and its bidirectional Linformer-based sentence encoding implementation', 'summarize the LinformerTransformerEncoder class which extends TransformerEncoder for efficient attention via compression', 'test the build_encoder_layer method to verify compress layer creation and freezing logic', 'build a LinformerTransformerEncoderLayer instance with args and a shared compression layer for BERT-style models', 'build a MultiheadLinearAttention self-attention module with compressed key-value projections and configurable quantization noise', 'upgrade a state dict to version 2 and fix incorrect weight sharing from old checkpoints', 'review the LinformerTransformerEncoderLayer constructor to understand shared compression layer wrapping and version buffer registration', 'refactor the LinformerTransformerEncoderLayer self-attention to adjust compression dimensions, head count, or freeze settings', 'build a linformer multi-head linear attention module with compressed key and value projections for linear complexity self-attention', 'create a forward pass through the multihead linear attention layer with query key and value tensors', 'test the multihead linear attention module in self-attention mode with sequence compression via linear projections', 'review the reset_parameters method that initializes projection and compression weights with Xavier uniform initialization', 'summarize the incremental state management methods for buffered key value and padding mask during autoregressive decoding']
```

Usage

```
{'build_MultiheadLinearAttention': 'build a linformer multi-head linear attention module with compressed key and value projections for linear complexity self-attention', 'create_MultiheadLinearAttention_forward': 'create a forward pass through the multihead linear attention layer with query key and value tensors', 'test_MultiheadLinearAttention_self_attention': 'test the multihead linear attention module in self-attention mode with sequence compression via linear projections', 'review_MultiheadLinearAttention_reset_parameters': 'review the reset_parameters method that initializes projection and compression weights with Xavier uniform initialization', 'summarize_MultiheadLinearAttention_incremental_state': 'summarize the incremental state management methods for buffered key value and padding mask during autoregressive decoding'}
```

