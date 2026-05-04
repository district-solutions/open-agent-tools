# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/modules/multihead_attention.py

Prompts

```
['build a model parallel multihead attention module that distributes heads across multiple GPUs', 'create a self-attention layer using ModelParallelMultiheadAttention with query key and value from the same input', 'run encoder-decoder cross-attention by passing separate encoder key and value tensors to the forward method', 'test incremental decoding by passing incremental_state dict to cache previous key and value tensors', 'review the _append_prev_key_padding_mask method to understand how padding masks are concatenated during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block distributed across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block distributed across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the first feed-forward projection in a model parallel encoder or decoder layer', 'build a RowParallelLinear layer via build_fc2 for the second feed-forward projection in a model parallel encoder or decoder layer', 'build a ModelParallelMultiheadAttention module via build_self_attention for self-attention in a model parallel transformer layer', 'build a ModelParallelTransformerSentenceEncoder for BERT style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab size and embedding dim', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding strategy', 'check the has_megatron_submodule flag to verify Megatron submodule availability', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT/XLM style pre-trained models with model parallelism', 'build a ColumnParallelLinear layer for the first feed-forward network with gather_output disabled', 'build a RowParallelLinear layer for the second feed-forward network with input_is_parallel enabled', 'run a forward pass through the encoder layer with input tensor and optional attention masks']
```

Usage

```
{'build_model_parallel_attention': 'build a model parallel multihead attention module that distributes heads across multiple GPUs', 'create_self_attention_layer': 'create a self-attention layer using ModelParallelMultiheadAttention with query key and value from the same input', 'run_encoder_decoder_attention': 'run encoder-decoder cross-attention by passing separate encoder key and value tensors to the forward method', 'test_incremental_decoding': 'test incremental decoding by passing incremental_state dict to cache previous key and value tensors', 'review_padding_mask_handling': 'review the _append_prev_key_padding_mask method to understand how padding masks are concatenated during incremental decoding'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/modules/transformer_layer.py

Prompts

```
['build a model parallel multihead attention module that distributes heads across multiple GPUs', 'create a self-attention layer using ModelParallelMultiheadAttention with query key and value from the same input', 'run encoder-decoder cross-attention by passing separate encoder key and value tensors to the forward method', 'test incremental decoding by passing incremental_state dict to cache previous key and value tensors', 'review the _append_prev_key_padding_mask method to understand how padding masks are concatenated during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block distributed across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block distributed across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the first feed-forward projection in a model parallel encoder or decoder layer', 'build a RowParallelLinear layer via build_fc2 for the second feed-forward projection in a model parallel encoder or decoder layer', 'build a ModelParallelMultiheadAttention module via build_self_attention for self-attention in a model parallel transformer layer', 'build a ModelParallelTransformerSentenceEncoder for BERT style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab size and embedding dim', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding strategy', 'check the has_megatron_submodule flag to verify Megatron submodule availability', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT/XLM style pre-trained models with model parallelism', 'build a ColumnParallelLinear layer for the first feed-forward network with gather_output disabled', 'build a RowParallelLinear layer for the second feed-forward network with input_is_parallel enabled', 'run a forward pass through the encoder layer with input tensor and optional attention masks']
```

Usage

```
{'build_encoder_layer': 'build a ModelParallelTransformerEncoderLayer to create an encoder block distributed across multiple GPUs', 'build_decoder_layer': 'build a ModelParallelTransformerDecoderLayer to create a decoder block distributed across multiple GPUs', 'build_fc1_column_parallel': 'build a ColumnParallelLinear layer via build_fc1 for the first feed-forward projection in a model parallel encoder or decoder layer', 'build_fc2_row_parallel': 'build a RowParallelLinear layer via build_fc2 for the second feed-forward projection in a model parallel encoder or decoder layer', 'build_self_attention_model_parallel': 'build a ModelParallelMultiheadAttention module via build_self_attention for self-attention in a model parallel transformer layer'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/modules/transformer_sentence_encoder.py

Prompts

```
['build a model parallel multihead attention module that distributes heads across multiple GPUs', 'create a self-attention layer using ModelParallelMultiheadAttention with query key and value from the same input', 'run encoder-decoder cross-attention by passing separate encoder key and value tensors to the forward method', 'test incremental decoding by passing incremental_state dict to cache previous key and value tensors', 'review the _append_prev_key_padding_mask method to understand how padding masks are concatenated during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block distributed across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block distributed across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the first feed-forward projection in a model parallel encoder or decoder layer', 'build a RowParallelLinear layer via build_fc2 for the second feed-forward projection in a model parallel encoder or decoder layer', 'build a ModelParallelMultiheadAttention module via build_self_attention for self-attention in a model parallel transformer layer', 'build a ModelParallelTransformerSentenceEncoder for BERT style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab size and embedding dim', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding strategy', 'check the has_megatron_submodule flag to verify Megatron submodule availability', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT/XLM style pre-trained models with model parallelism', 'build a ColumnParallelLinear layer for the first feed-forward network with gather_output disabled', 'build a RowParallelLinear layer for the second feed-forward network with input_is_parallel enabled', 'run a forward pass through the encoder layer with input tensor and optional attention masks']
```

Usage

```
{'build_model_parallel_encoder': 'build a ModelParallelTransformerSentenceEncoder for BERT style model parallel sentence encoding', 'build_vocab_parallel_embedding': 'build a VocabParallelEmbedding by calling build_embedding with vocab size and embedding dim', 'build_transformer_encoder_layer': 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review_model_parallel_encoder_class': 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding strategy', 'check_megatron_submodule': 'check the has_megatron_submodule flag to verify Megatron submodule availability'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/modules/transformer_sentence_encoder_layer.py

Prompts

```
['build a model parallel multihead attention module that distributes heads across multiple GPUs', 'create a self-attention layer using ModelParallelMultiheadAttention with query key and value from the same input', 'run encoder-decoder cross-attention by passing separate encoder key and value tensors to the forward method', 'test incremental decoding by passing incremental_state dict to cache previous key and value tensors', 'review the _append_prev_key_padding_mask method to understand how padding masks are concatenated during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block distributed across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block distributed across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the first feed-forward projection in a model parallel encoder or decoder layer', 'build a RowParallelLinear layer via build_fc2 for the second feed-forward projection in a model parallel encoder or decoder layer', 'build a ModelParallelMultiheadAttention module via build_self_attention for self-attention in a model parallel transformer layer', 'build a ModelParallelTransformerSentenceEncoder for BERT style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab size and embedding dim', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding strategy', 'check the has_megatron_submodule flag to verify Megatron submodule availability', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT/XLM style pre-trained models with model parallelism', 'build a ColumnParallelLinear layer for the first feed-forward network with gather_output disabled', 'build a RowParallelLinear layer for the second feed-forward network with input_is_parallel enabled', 'run a forward pass through the encoder layer with input tensor and optional attention masks']
```

Usage

```
{'build_model_parallel_encoder_layer': 'build a ModelParallelTransformerSentenceEncoderLayer for BERT/XLM style pre-trained models with model parallelism', 'build_fc1_column_parallel_linear': 'build a ColumnParallelLinear layer for the first feed-forward network with gather_output disabled', 'build_fc2_row_parallel_linear': 'build a RowParallelLinear layer for the second feed-forward network with input_is_parallel enabled', 'build_self_attention_model_parallel': 'build a ModelParallelMultiheadAttention module for self-attention with specified embed_dim and num_attention_heads', 'run_forward_pass_encoder_layer': 'run a forward pass through the encoder layer with input tensor and optional attention masks'}
```

