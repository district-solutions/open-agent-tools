# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/model_parallel/models/transformer.py

Prompts

```
['build a model parallel Transformer model using VocabParallelEmbedding for distributed training across multiple GPUs', 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build a VocabParallelEmbedding with dictionary padding and custom vocabulary initialization for model parallel training', 'output the decoder features projected to vocabulary size with model parallel region gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure default language model architecture arguments using base_lm_architecture to set decoder dimensions and dropout', 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 6x FFN expansion ratio']
```

Usage

```
{'build_model_parallel_transformer_model': 'build a model parallel Transformer model using VocabParallelEmbedding for distributed training across multiple GPUs', 'build_model_parallel_encoder': 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build_model_parallel_decoder': 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build_embedding_vocab_parallel': 'build a VocabParallelEmbedding with dictionary padding and custom vocabulary initialization for model parallel training', 'output_decoder_layer_projection': 'output the decoder features projected to vocabulary size with model parallel region gathering'}
```

## File: facebookresearch_fairseq/fairseq/model_parallel/models/transformer_lm.py

Prompts

```
['build a model parallel Transformer model using VocabParallelEmbedding for distributed training across multiple GPUs', 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build a VocabParallelEmbedding with dictionary padding and custom vocabulary initialization for model parallel training', 'output the decoder features projected to vocabulary size with model parallel region gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure default language model architecture arguments using base_lm_architecture to set decoder dimensions and dropout', 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 6x FFN expansion ratio']
```

Usage

```
{'build_model_parallel_transformer_lm': 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build_vocab_parallel_embedding': 'build a VocabParallelEmbedding for the decoder using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure_base_lm_architecture': 'configure default language model architecture arguments using base_lm_architecture to set decoder dimensions and dropout', 'configure_megatron_architecture': 'configure the transformer_lm_megatron architecture with 72 layers, 3072 embed dim, and 32 attention heads', 'configure_megatron_11b_architecture': 'configure the transformer_lm_megatron_11b architecture with 72 layers and 6x FFN expansion ratio'}
```

