# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/models/pipeline_parallel_transformer/layers.py

Prompts

```
['build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build a TransformerDecoderLayer with self-attention, encoder-decoder attention, and feed-forward network for sequence decoding', 'create a TransformerEncoderEmbedding module that combines token embeddings with learned positional embeddings', 'create a TransformerDecoderOutputLayer with optional adaptive softmax and tied input-output embeddings for final projection', 'create an initialized nn.Embedding layer with normal weight initialization and zero padding using the Embedding factory function', 'build a pipeline parallel transformer model using fairscale Pipe for distributed training across multiple GPUs', 'build a TransformerEncoder with pipeline parallel support for encoding source tokens in machine translation', 'build a TransformerDecoder with pipeline parallel support for decoding target tokens in machine translation', 'prepare the PipelineParallelTransformerModel for inference by splitting partitions into separate encoder and decoder modules', 'convert a regular transformer state dict to pipeline parallel format for loading pretrained checkpoints']
```

Usage

```
{'build_transformer_encoder_layer': 'build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build_transformer_decoder_layer': 'build a TransformerDecoderLayer with self-attention, encoder-decoder attention, and feed-forward network for sequence decoding', 'create_encoder_embedding_module': 'create a TransformerEncoderEmbedding module that combines token embeddings with learned positional embeddings', 'create_decoder_output_layer': 'create a TransformerDecoderOutputLayer with optional adaptive softmax and tied input-output embeddings for final projection', 'create_embedding_factory': 'create an initialized nn.Embedding layer with normal weight initialization and zero padding using the Embedding factory function'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/models/pipeline_parallel_transformer/model.py

Prompts

```
['build a TransformerEncoderLayer with multi-head self-attention and feed-forward network for sequence encoding', 'build a TransformerDecoderLayer with self-attention, encoder-decoder attention, and feed-forward network for sequence decoding', 'create a TransformerEncoderEmbedding module that combines token embeddings with learned positional embeddings', 'create a TransformerDecoderOutputLayer with optional adaptive softmax and tied input-output embeddings for final projection', 'create an initialized nn.Embedding layer with normal weight initialization and zero padding using the Embedding factory function', 'build a pipeline parallel transformer model using fairscale Pipe for distributed training across multiple GPUs', 'build a TransformerEncoder with pipeline parallel support for encoding source tokens in machine translation', 'build a TransformerDecoder with pipeline parallel support for decoding target tokens in machine translation', 'prepare the PipelineParallelTransformerModel for inference by splitting partitions into separate encoder and decoder modules', 'convert a regular transformer state dict to pipeline parallel format for loading pretrained checkpoints']
```

Usage

```
{'build_pipeline_parallel_transformer': 'build a pipeline parallel transformer model using fairscale Pipe for distributed training across multiple GPUs', 'build_transformer_encoder': 'build a TransformerEncoder with pipeline parallel support for encoding source tokens in machine translation', 'build_transformer_decoder': 'build a TransformerDecoder with pipeline parallel support for decoding target tokens in machine translation', 'prepare_for_inference': 'prepare the PipelineParallelTransformerModel for inference by splitting partitions into separate encoder and decoder modules', 'convert_state_dict': 'convert a regular transformer state dict to pipeline parallel format for loading pretrained checkpoints'}
```

