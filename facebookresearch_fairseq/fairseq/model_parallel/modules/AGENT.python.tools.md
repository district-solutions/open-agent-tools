# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/model_parallel/modules/multihead_attention.py

Prompts

```
['build a ModelParallelMultiheadAttention module with embed_dim and num_heads for multi-GPU attention', 'run forward pass on ModelParallelMultiheadAttention with query, key, value tensors and optional masks', 'create incremental decoding state by passing incremental_state dict to the forward method', 'test reorder_incremental_state to reorder buffered keys and values during beam search generation', 'review the _append_prev_key_padding_mask static method for handling padding during incremental decoding', 'build a ModelParallelTransformerEncoderLayer that shards encoder FFN layers across multiple GPUs using Megatron-LM style parallelism', 'build a ModelParallelTransformerDecoderLayer that shards decoder FFN and attention layers across multiple GPUs', 'review the build_fc1 method that creates a ColumnParallelLinear layer for the first FFN projection', 'review the build_fc2 method that creates a RowParallelLinear layer for the second FFN projection', 'review the build_self_attention method that creates a ModelParallelMultiheadAttention module for self-attention across GPUs']
```

Usage

```
{'build_model_parallel_attention': 'build a ModelParallelMultiheadAttention module with embed_dim and num_heads for multi-GPU attention', 'run_forward_attention': 'run forward pass on ModelParallelMultiheadAttention with query, key, value tensors and optional masks', 'create_incremental_decoding_state': 'create incremental decoding state by passing incremental_state dict to the forward method', 'test_reorder_incremental_state': 'test reorder_incremental_state to reorder buffered keys and values during beam search generation', 'review_append_key_padding_mask': 'review the _append_prev_key_padding_mask static method for handling padding during incremental decoding'}
```

## File: facebookresearch_fairseq/fairseq/model_parallel/modules/transformer_layer.py

Prompts

```
['build a ModelParallelMultiheadAttention module with embed_dim and num_heads for multi-GPU attention', 'run forward pass on ModelParallelMultiheadAttention with query, key, value tensors and optional masks', 'create incremental decoding state by passing incremental_state dict to the forward method', 'test reorder_incremental_state to reorder buffered keys and values during beam search generation', 'review the _append_prev_key_padding_mask static method for handling padding during incremental decoding', 'build a ModelParallelTransformerEncoderLayer that shards encoder FFN layers across multiple GPUs using Megatron-LM style parallelism', 'build a ModelParallelTransformerDecoderLayer that shards decoder FFN and attention layers across multiple GPUs', 'review the build_fc1 method that creates a ColumnParallelLinear layer for the first FFN projection', 'review the build_fc2 method that creates a RowParallelLinear layer for the second FFN projection', 'review the build_self_attention method that creates a ModelParallelMultiheadAttention module for self-attention across GPUs']
```

Usage

```
{'build_model_parallel_encoder_layer': 'build a ModelParallelTransformerEncoderLayer that shards encoder FFN layers across multiple GPUs using Megatron-LM style parallelism', 'build_model_parallel_decoder_layer': 'build a ModelParallelTransformerDecoderLayer that shards decoder FFN and attention layers across multiple GPUs', 'review_build_fc1_column_parallel': 'review the build_fc1 method that creates a ColumnParallelLinear layer for the first FFN projection', 'review_build_fc2_row_parallel': 'review the build_fc2 method that creates a RowParallelLinear layer for the second FFN projection', 'review_build_self_attention_model_parallel': 'review the build_self_attention method that creates a ModelParallelMultiheadAttention module for self-attention across GPUs'}
```

