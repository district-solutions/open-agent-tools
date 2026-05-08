# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/speech_dlm/modules/speech_dlm_decoder.py

Prompts

```
['build a CrossChannelTransformerDecoder with args, dictionary, embed_tokens, and channel list for parallel spoken dialogue', 'extract features from prev_output_tokens dict through the decoder layers and return channel-wise embeddings', 'project decoder features to vocabulary size with optional cross-channel prediction and duration prediction', 'get normalized softmax or log-softmax probabilities from the decoder net output logits dictionary', 'build a StandardTransformerDecoderLayer or CrossChannelTransformerDecoderLayer with optional checkpoint activation wrapping', 'build a CrossChannelTransformerDecoderLayer with shared attention weights across multiple input channels', 'build a StandardTransformerDecoderLayer for multi-channel transformer decoder processing', 'run forward pass on CrossChannelTransformerDecoderLayer with a list of multi-channel tensors', 'run forward pass on StandardTransformerDecoderLayer with encoder output and padding masks', 'build a MultiheadAttention module for self-attention with configurable heads and dropout']
```

Usage

```
{'build_cross_channel_decoder': 'build a CrossChannelTransformerDecoder with args, dictionary, embed_tokens, and channel list for parallel spoken dialogue', 'extract_decoder_features': 'extract features from prev_output_tokens dict through the decoder layers and return channel-wise embeddings', 'project_output_layer': 'project decoder features to vocabulary size with optional cross-channel prediction and duration prediction', 'get_normalized_probs': 'get normalized softmax or log-softmax probabilities from the decoder net output logits dictionary', 'build_decoder_layer': 'build a StandardTransformerDecoderLayer or CrossChannelTransformerDecoderLayer with optional checkpoint activation wrapping'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_dlm/modules/speech_dlm_decoder_layer.py

Prompts

```
['build a CrossChannelTransformerDecoder with args, dictionary, embed_tokens, and channel list for parallel spoken dialogue', 'extract features from prev_output_tokens dict through the decoder layers and return channel-wise embeddings', 'project decoder features to vocabulary size with optional cross-channel prediction and duration prediction', 'get normalized softmax or log-softmax probabilities from the decoder net output logits dictionary', 'build a StandardTransformerDecoderLayer or CrossChannelTransformerDecoderLayer with optional checkpoint activation wrapping', 'build a CrossChannelTransformerDecoderLayer with shared attention weights across multiple input channels', 'build a StandardTransformerDecoderLayer for multi-channel transformer decoder processing', 'run forward pass on CrossChannelTransformerDecoderLayer with a list of multi-channel tensors', 'run forward pass on StandardTransformerDecoderLayer with encoder output and padding masks', 'build a MultiheadAttention module for self-attention with configurable heads and dropout']
```

Usage

```
{'build_cross_channel_decoder_layer': 'build a CrossChannelTransformerDecoderLayer with shared attention weights across multiple input channels', 'build_standard_decoder_layer': 'build a StandardTransformerDecoderLayer for multi-channel transformer decoder processing', 'forward_cross_channel_layer': 'run forward pass on CrossChannelTransformerDecoderLayer with a list of multi-channel tensors', 'forward_standard_layer': 'run forward pass on StandardTransformerDecoderLayer with encoder output and padding masks', 'build_self_attention': 'build a MultiheadAttention module for self-attention with configurable heads and dropout'}
```

