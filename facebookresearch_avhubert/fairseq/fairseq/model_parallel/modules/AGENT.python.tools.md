# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/modules/multihead_attention.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU training', 'run the forward pass of ModelParallelMultiheadAttention with query, key, and value tensors', 'create a self-attention layer using ModelParallelMultiheadAttention with self_attention set to True', 'test incremental decoding by passing incremental_state dict to the forward method', 'review the reorder_incremental_state method to understand how it reorders buffered state for beam search', 'build a ModelParallelTransformerEncoderLayer to create an encoder block that distributes computation across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block that distributes computation across multiple GPUs', 'build the encoder layer fc1 and fc2 layers using ColumnParallelLinear and RowParallelLinear for model parallelism', 'build the decoder self-attention mechanism using ModelParallelMultiheadAttention with configurable cross-self-attention support', 'build the decoder encoder-attention mechanism using ModelParallelMultiheadAttention for encoder-decoder cross-attention across GPUs']
```

Usage

```
{'build_model_parallel_attention': 'build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU training', 'run_forward_attention': 'run the forward pass of ModelParallelMultiheadAttention with query, key, and value tensors', 'create_self_attention_layer': 'create a self-attention layer using ModelParallelMultiheadAttention with self_attention set to True', 'test_incremental_decoding': 'test incremental decoding by passing incremental_state dict to the forward method', 'review_reorder_incremental_state': 'review the reorder_incremental_state method to understand how it reorders buffered state for beam search'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/modules/transformer_layer.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU training', 'run the forward pass of ModelParallelMultiheadAttention with query, key, and value tensors', 'create a self-attention layer using ModelParallelMultiheadAttention with self_attention set to True', 'test incremental decoding by passing incremental_state dict to the forward method', 'review the reorder_incremental_state method to understand how it reorders buffered state for beam search', 'build a ModelParallelTransformerEncoderLayer to create an encoder block that distributes computation across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block that distributes computation across multiple GPUs', 'build the encoder layer fc1 and fc2 layers using ColumnParallelLinear and RowParallelLinear for model parallelism', 'build the decoder self-attention mechanism using ModelParallelMultiheadAttention with configurable cross-self-attention support', 'build the decoder encoder-attention mechanism using ModelParallelMultiheadAttention for encoder-decoder cross-attention across GPUs']
```

Usage

```
{'build_model_parallel_encoder_layer': 'build a ModelParallelTransformerEncoderLayer to create an encoder block that distributes computation across multiple GPUs', 'build_model_parallel_decoder_layer': 'build a ModelParallelTransformerDecoderLayer to create a decoder block that distributes computation across multiple GPUs', 'build_encoder_fc1_fc2': 'build the encoder layer fc1 and fc2 layers using ColumnParallelLinear and RowParallelLinear for model parallelism', 'build_decoder_self_attention': 'build the decoder self-attention mechanism using ModelParallelMultiheadAttention with configurable cross-self-attention support', 'build_decoder_encoder_attention': 'build the decoder encoder-attention mechanism using ModelParallelMultiheadAttention for encoder-decoder cross-attention across GPUs'}
```

