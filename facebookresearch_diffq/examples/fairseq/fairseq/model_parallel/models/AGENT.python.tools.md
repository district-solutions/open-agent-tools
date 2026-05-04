# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/models/transformer.py

Prompts

```
['build a model parallel transformer model using the ModelParallelTransformerModel class registered as model_parallel_transformer', 'build a VocabParallelEmbedding for model parallel training by calling ModelParallelTransformerModel.build_embedding with args and dictionary', 'build a ModelParallelTransformerEncoder by calling ModelParallelTransformerModel.build_encoder with args, source dictionary, and embed tokens', 'build a ModelParallelTransformerDecoder by calling ModelParallelTransformerModel.build_decoder with args, target dictionary, and embed tokens', 'review the ModelParallelTransformerDecoder output_layer method that projects features to vocabulary size using model parallel region utilities', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a vocab parallel embedding using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure base language model architecture defaults using base_lm_architecture with args object', 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure the transformer_lm_megatron_11b architecture with 72 layers and wider FFN using transformer_lm_megatron_11b']
```

Usage

```
{'build_model_parallel_transformer': 'build a model parallel transformer model using the ModelParallelTransformerModel class registered as model_parallel_transformer', 'build_embedding_vocab_parallel': 'build a VocabParallelEmbedding for model parallel training by calling ModelParallelTransformerModel.build_embedding with args and dictionary', 'build_encoder_model_parallel': 'build a ModelParallelTransformerEncoder by calling ModelParallelTransformerModel.build_encoder with args, source dictionary, and embed tokens', 'build_decoder_model_parallel': 'build a ModelParallelTransformerDecoder by calling ModelParallelTransformerModel.build_decoder with args, target dictionary, and embed tokens', 'review_output_layer_projection': 'review the ModelParallelTransformerDecoder output_layer method that projects features to vocabulary size using model parallel region utilities'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/models/transformer_lm.py

Prompts

```
['build a model parallel transformer model using the ModelParallelTransformerModel class registered as model_parallel_transformer', 'build a VocabParallelEmbedding for model parallel training by calling ModelParallelTransformerModel.build_embedding with args and dictionary', 'build a ModelParallelTransformerEncoder by calling ModelParallelTransformerModel.build_encoder with args, source dictionary, and embed tokens', 'build a ModelParallelTransformerDecoder by calling ModelParallelTransformerModel.build_decoder with args, target dictionary, and embed tokens', 'review the ModelParallelTransformerDecoder output_layer method that projects features to vocabulary size using model parallel region utilities', 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build a vocab parallel embedding using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure base language model architecture defaults using base_lm_architecture with args object', 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure the transformer_lm_megatron_11b architecture with 72 layers and wider FFN using transformer_lm_megatron_11b']
```

Usage

```
{'build_model_parallel_transformer_lm': 'build a model parallel transformer language model using ModelParallelTransformerLanguageModel.build_model with args and task', 'build_vocab_parallel_embedding': 'build a vocab parallel embedding using ModelParallelTransformerLanguageModel.build_embedding with dictionary and embed_dim', 'configure_base_lm_architecture': 'configure base language model architecture defaults using base_lm_architecture with args object', 'configure_megatron_architecture': 'configure the transformer_lm_megatron architecture with 72 layers and 3072 embed dim using transformer_lm_megatron', 'configure_megatron_11b_architecture': 'configure the transformer_lm_megatron_11b architecture with 72 layers and wider FFN using transformer_lm_megatron_11b'}
```

