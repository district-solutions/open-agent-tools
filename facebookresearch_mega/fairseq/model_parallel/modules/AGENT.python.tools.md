# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/model_parallel/modules/multihead_attention.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU inference', 'run the forward pass of ModelParallelMultiheadAttention with self-attention mode on query tensors', 'run the forward pass of ModelParallelMultiheadAttention with encoder-decoder attention using separate key and value tensors', 'test the ModelParallelMultiheadAttention incremental state caching and key-value reuse during decoding', 'review the _append_prev_key_padding_mask static method for handling padding masks during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the encoder or decoder', 'build a RowParallelLinear layer via build_fc2 for the encoder or decoder', 'build a ModelParallelMultiheadAttention self-attention layer for the encoder or decoder', 'build a ModelParallelTransformerSentenceEncoder for BERT-style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab_size, embedding_dim, and padding_idx', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding and layer builder methods', 'summarize the has_megatron_submodule import check and VocabParallelEmbedding availability in the module', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT style model parallel training', 'build a ColumnParallelLinear fc1 layer with gather_output set to False', 'build a RowParallelLinear fc2 layer with input_is_parallel set to True', 'build a ModelParallelMultiheadAttention module for self attention in the encoder layer', 'run the forward pass of the encoder layer with input tensor and attention masks']
```

Usage

```
{'build_model_parallel_attention': 'build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU inference', 'run_forward_self_attention': 'run the forward pass of ModelParallelMultiheadAttention with self-attention mode on query tensors', 'run_forward_encoder_decoder_attention': 'run the forward pass of ModelParallelMultiheadAttention with encoder-decoder attention using separate key and value tensors', 'test_incremental_decoding': 'test the ModelParallelMultiheadAttention incremental state caching and key-value reuse during decoding', 'review_padding_mask_handling': 'review the _append_prev_key_padding_mask static method for handling padding masks during incremental decoding'}
```

## File: facebookresearch_mega/fairseq/model_parallel/modules/transformer_layer.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU inference', 'run the forward pass of ModelParallelMultiheadAttention with self-attention mode on query tensors', 'run the forward pass of ModelParallelMultiheadAttention with encoder-decoder attention using separate key and value tensors', 'test the ModelParallelMultiheadAttention incremental state caching and key-value reuse during decoding', 'review the _append_prev_key_padding_mask static method for handling padding masks during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the encoder or decoder', 'build a RowParallelLinear layer via build_fc2 for the encoder or decoder', 'build a ModelParallelMultiheadAttention self-attention layer for the encoder or decoder', 'build a ModelParallelTransformerSentenceEncoder for BERT-style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab_size, embedding_dim, and padding_idx', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding and layer builder methods', 'summarize the has_megatron_submodule import check and VocabParallelEmbedding availability in the module', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT style model parallel training', 'build a ColumnParallelLinear fc1 layer with gather_output set to False', 'build a RowParallelLinear fc2 layer with input_is_parallel set to True', 'build a ModelParallelMultiheadAttention module for self attention in the encoder layer', 'run the forward pass of the encoder layer with input tensor and attention masks']
```

Usage

```
{'build_encoder_layer': 'build a ModelParallelTransformerEncoderLayer to create an encoder block across multiple GPUs', 'build_decoder_layer': 'build a ModelParallelTransformerDecoderLayer to create a decoder block across multiple GPUs', 'build_fc1_column_parallel': 'build a ColumnParallelLinear layer via build_fc1 for the encoder or decoder', 'build_fc2_row_parallel': 'build a RowParallelLinear layer via build_fc2 for the encoder or decoder', 'build_self_attention': 'build a ModelParallelMultiheadAttention self-attention layer for the encoder or decoder'}
```

## File: facebookresearch_mega/fairseq/model_parallel/modules/transformer_sentence_encoder.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU inference', 'run the forward pass of ModelParallelMultiheadAttention with self-attention mode on query tensors', 'run the forward pass of ModelParallelMultiheadAttention with encoder-decoder attention using separate key and value tensors', 'test the ModelParallelMultiheadAttention incremental state caching and key-value reuse during decoding', 'review the _append_prev_key_padding_mask static method for handling padding masks during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the encoder or decoder', 'build a RowParallelLinear layer via build_fc2 for the encoder or decoder', 'build a ModelParallelMultiheadAttention self-attention layer for the encoder or decoder', 'build a ModelParallelTransformerSentenceEncoder for BERT-style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab_size, embedding_dim, and padding_idx', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding and layer builder methods', 'summarize the has_megatron_submodule import check and VocabParallelEmbedding availability in the module', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT style model parallel training', 'build a ColumnParallelLinear fc1 layer with gather_output set to False', 'build a RowParallelLinear fc2 layer with input_is_parallel set to True', 'build a ModelParallelMultiheadAttention module for self attention in the encoder layer', 'run the forward pass of the encoder layer with input tensor and attention masks']
```

Usage

```
{'build_model_parallel_sentence_encoder': 'build a ModelParallelTransformerSentenceEncoder for BERT-style model parallel sentence encoding', 'build_vocab_parallel_embedding': 'build a VocabParallelEmbedding by calling build_embedding with vocab_size, embedding_dim, and padding_idx', 'build_transformer_encoder_layer': 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review_model_parallel_encoder_class': 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding and layer builder methods', 'summarize_megatron_submodule_check': 'summarize the has_megatron_submodule import check and VocabParallelEmbedding availability in the module'}
```

## File: facebookresearch_mega/fairseq/model_parallel/modules/transformer_sentence_encoder_layer.py

Prompts

```
['build a ModelParallelMultiheadAttention module with specified embed_dim and num_heads for multi-GPU inference', 'run the forward pass of ModelParallelMultiheadAttention with self-attention mode on query tensors', 'run the forward pass of ModelParallelMultiheadAttention with encoder-decoder attention using separate key and value tensors', 'test the ModelParallelMultiheadAttention incremental state caching and key-value reuse during decoding', 'review the _append_prev_key_padding_mask static method for handling padding masks during incremental decoding', 'build a ModelParallelTransformerEncoderLayer to create an encoder block across multiple GPUs', 'build a ModelParallelTransformerDecoderLayer to create a decoder block across multiple GPUs', 'build a ColumnParallelLinear layer via build_fc1 for the encoder or decoder', 'build a RowParallelLinear layer via build_fc2 for the encoder or decoder', 'build a ModelParallelMultiheadAttention self-attention layer for the encoder or decoder', 'build a ModelParallelTransformerSentenceEncoder for BERT-style model parallel sentence encoding', 'build a VocabParallelEmbedding by calling build_embedding with vocab_size, embedding_dim, and padding_idx', 'build a ModelParallelTransformerSentenceEncoderLayer via build_transformer_sentence_encoder_layer with attention heads and dropout', 'review the ModelParallelTransformerSentenceEncoder class and its model parallel embedding and layer builder methods', 'summarize the has_megatron_submodule import check and VocabParallelEmbedding availability in the module', 'build a ModelParallelTransformerSentenceEncoderLayer for BERT style model parallel training', 'build a ColumnParallelLinear fc1 layer with gather_output set to False', 'build a RowParallelLinear fc2 layer with input_is_parallel set to True', 'build a ModelParallelMultiheadAttention module for self attention in the encoder layer', 'run the forward pass of the encoder layer with input tensor and attention masks']
```

Usage

```
{'build_model_parallel_encoder_layer': 'build a ModelParallelTransformerSentenceEncoderLayer for BERT style model parallel training', 'build_fc1_column_parallel_linear': 'build a ColumnParallelLinear fc1 layer with gather_output set to False', 'build_fc2_row_parallel_linear': 'build a RowParallelLinear fc2 layer with input_is_parallel set to True', 'build_model_parallel_self_attention': 'build a ModelParallelMultiheadAttention module for self attention in the encoder layer', 'run_forward_pass_encoder_layer': 'run the forward pass of the encoder layer with input tensor and attention masks'}
```

