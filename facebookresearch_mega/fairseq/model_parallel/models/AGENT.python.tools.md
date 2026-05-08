# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/model_parallel/models/transformer.py

Prompts

```
['build a model parallel Transformer model using ModelParallelTransformerModel with megatron submodule', 'build a VocabParallelEmbedding layer for model parallel training with custom initialization', 'build a ModelParallelTransformerEncoder with ModelParallelTransformerEncoderLayer instances', 'build a ModelParallelTransformerDecoder with ModelParallelTransformerDecoderLayer instances and optional cross attention', 'review the output_layer method that projects features to vocabulary size with model parallel gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 3072*6 FFN embed dim', 'register the model_parallel_transformer_lm model type with fairseq using the register_model decorator']
```

Usage

```
{'build_model_parallel_transformer': 'build a model parallel Transformer model using ModelParallelTransformerModel with megatron submodule', 'build_embedding_vocab_parallel': 'build a VocabParallelEmbedding layer for model parallel training with custom initialization', 'build_encoder_model_parallel': 'build a ModelParallelTransformerEncoder with ModelParallelTransformerEncoderLayer instances', 'build_decoder_model_parallel': 'build a ModelParallelTransformerDecoder with ModelParallelTransformerDecoderLayer instances and optional cross attention', 'review_output_layer_projection': 'review the output_layer method that projects features to vocabulary size with model parallel gathering'}
```

## File: facebookresearch_mega/fairseq/model_parallel/models/transformer_lm.py

Prompts

```
['build a model parallel Transformer model using ModelParallelTransformerModel with megatron submodule', 'build a VocabParallelEmbedding layer for model parallel training with custom initialization', 'build a ModelParallelTransformerEncoder with ModelParallelTransformerEncoderLayer instances', 'build a ModelParallelTransformerDecoder with ModelParallelTransformerDecoderLayer instances and optional cross attention', 'review the output_layer method that projects features to vocabulary size with model parallel gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 3072*6 FFN embed dim', 'register the model_parallel_transformer_lm model type with fairseq using the register_model decorator']
```

Usage

```
{'build_model_parallel_transformer_lm': 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build_vocab_parallel_embedding': 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure_transformer_lm_megatron_architecture': 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure_transformer_lm_megatron_11b_architecture': 'configure the transformer_lm_megatron_11b architecture with 72 layers and 3072*6 FFN embed dim', 'register_model_parallel_transformer_lm': 'register the model_parallel_transformer_lm model type with fairseq using the register_model decorator'}
```

