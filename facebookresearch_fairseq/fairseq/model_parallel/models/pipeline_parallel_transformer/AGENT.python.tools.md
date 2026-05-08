# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/model_parallel/models/pipeline_parallel_transformer/layers.py

Prompts

```
['build a TransformerEncoderEmbedding module that embeds source tokens with positional embeddings and padding masks', 'build a TransformerDecoderEmbedding module that embeds target tokens with positional embeddings for the decoder', 'build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build a TransformerDecoderLayer with self-attention, encoder-attention, and feed-forward network for sequence decoding', 'build a TransformerDecoderOutputLayer that projects decoder features to vocabulary logits with optional adaptive softmax', 'build a PipelineParallelTransformerModel with encoder, decoder, balance, devices, chunks, and checkpoint arguments', 'build a TransformerEncoder with args, dictionary, and embed_tokens for pipeline parallel training', 'build a TransformerDecoder with args, dictionary, embed_tokens, and optional no_encoder_attn flag', 'prepare a PipelineParallelTransformerModel for inference by calling prepare_for_inference_ with a config object', 'convert a regular transformer state dict to pipeline parallel format using convert_to_pipeline_parallel_state_dict']
```

Usage

```
{'build_encoder_embedding': 'build a TransformerEncoderEmbedding module that embeds source tokens with positional embeddings and padding masks', 'build_decoder_embedding': 'build a TransformerDecoderEmbedding module that embeds target tokens with positional embeddings for the decoder', 'build_encoder_layer': 'build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build_decoder_layer': 'build a TransformerDecoderLayer with self-attention, encoder-attention, and feed-forward network for sequence decoding', 'build_decoder_output_layer': 'build a TransformerDecoderOutputLayer that projects decoder features to vocabulary logits with optional adaptive softmax'}
```

## File: facebookresearch_fairseq/fairseq/model_parallel/models/pipeline_parallel_transformer/model.py

Prompts

```
['build a TransformerEncoderEmbedding module that embeds source tokens with positional embeddings and padding masks', 'build a TransformerDecoderEmbedding module that embeds target tokens with positional embeddings for the decoder', 'build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build a TransformerDecoderLayer with self-attention, encoder-attention, and feed-forward network for sequence decoding', 'build a TransformerDecoderOutputLayer that projects decoder features to vocabulary logits with optional adaptive softmax', 'build a PipelineParallelTransformerModel with encoder, decoder, balance, devices, chunks, and checkpoint arguments', 'build a TransformerEncoder with args, dictionary, and embed_tokens for pipeline parallel training', 'build a TransformerDecoder with args, dictionary, embed_tokens, and optional no_encoder_attn flag', 'prepare a PipelineParallelTransformerModel for inference by calling prepare_for_inference_ with a config object', 'convert a regular transformer state dict to pipeline parallel format using convert_to_pipeline_parallel_state_dict']
```

Usage

```
{'build_pipeline_parallel_transformer_model': 'build a PipelineParallelTransformerModel with encoder, decoder, balance, devices, chunks, and checkpoint arguments', 'build_transformer_encoder': 'build a TransformerEncoder with args, dictionary, and embed_tokens for pipeline parallel training', 'build_transformer_decoder': 'build a TransformerDecoder with args, dictionary, embed_tokens, and optional no_encoder_attn flag', 'prepare_for_inference_pipeline_model': 'prepare a PipelineParallelTransformerModel for inference by calling prepare_for_inference_ with a config object', 'convert_state_dict_to_pipeline_parallel': 'convert a regular transformer state dict to pipeline parallel format using convert_to_pipeline_parallel_state_dict'}
```

