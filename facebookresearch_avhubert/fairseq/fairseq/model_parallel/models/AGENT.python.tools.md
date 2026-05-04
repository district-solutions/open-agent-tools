# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/models/transformer.py

Prompts

```
['build a model parallel transformer model using ModelParallelTransformerModel with megatron vocab parallel embedding', 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build a VocabParallelEmbedding for model parallel training with dictionary padding and custom initialization', 'project decoder features to vocabulary size using output_layer with model parallel region gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding using ModelParallelTransformerLanguageModel.build_embedding with args, dictionary, and embed_dim', 'configure default language model architecture arguments using base_lm_architecture with an args namespace', 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 18432 FFN dim using transformer_lm_megatron_11b']
```

Usage

```
{'build_model_parallel_transformer_model': 'build a model parallel transformer model using ModelParallelTransformerModel with megatron vocab parallel embedding', 'build_model_parallel_encoder': 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build_model_parallel_decoder': 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build_embedding_vocab_parallel': 'build a VocabParallelEmbedding for model parallel training with dictionary padding and custom initialization', 'output_layer_projection': 'project decoder features to vocabulary size using output_layer with model parallel region gathering'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/models/transformer_lm.py

Prompts

```
['build a model parallel transformer model using ModelParallelTransformerModel with megatron vocab parallel embedding', 'build a ModelParallelTransformerEncoder with configurable encoder layers and optional final layer norm', 'build a ModelParallelTransformerDecoder with configurable decoder layers and optional cross attention', 'build a VocabParallelEmbedding for model parallel training with dictionary padding and custom initialization', 'project decoder features to vocabulary size using output_layer with model parallel region gathering', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a VocabParallelEmbedding using ModelParallelTransformerLanguageModel.build_embedding with args, dictionary, and embed_dim', 'configure default language model architecture arguments using base_lm_architecture with an args namespace', 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure the transformer_lm_megatron_11b architecture with 72 layers and 18432 FFN dim using transformer_lm_megatron_11b']
```

Usage

```
{'build_model_parallel_transformer_lm': 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build_vocab_parallel_embedding': 'build a VocabParallelEmbedding using ModelParallelTransformerLanguageModel.build_embedding with args, dictionary, and embed_dim', 'configure_base_lm_architecture': 'configure default language model architecture arguments using base_lm_architecture with an args namespace', 'configure_megatron_architecture': 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure_megatron_11b_architecture': 'configure the transformer_lm_megatron_11b architecture with 72 layers and 18432 FFN dim using transformer_lm_megatron_11b'}
```

