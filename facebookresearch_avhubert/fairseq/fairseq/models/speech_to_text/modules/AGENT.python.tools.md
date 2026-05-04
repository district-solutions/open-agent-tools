# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/models/speech_to_text/modules/augmented_memory_attention.py

Prompts

```
['build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create an AugmentedMemoryTransformerEncoderLayer that maintains memory banks and summarization queries for streaming inference', 'build an AugmentedMemoryMultiheadAttention module with memory banks and attention suppression for streaming self-attention', 'create a SequenceEncoder that breaks input sequences into segments and encodes them with augmented memory', 'review the augmented_memory decorator that adds segment-size and context arguments to a streaming model class', 'build a speech-to-text encoder using NoSegAugmentedMemoryTransformerEncoderLayer with augmented memory multihead attention', 'create a RelativePositionEmbedding module with learnable embeddings for a given head dimension and max position', 'build a PositionwiseFF feed-forward network layer with configurable activation function and dropout rates', 'create a SummarizationLayer to reduce segment embeddings using mean, max, linear, or nonlinear methods']
```

Usage

```
{'build_augmented_memory_encoder': 'build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create_augmented_memory_layer': 'create an AugmentedMemoryTransformerEncoderLayer that maintains memory banks and summarization queries for streaming inference', 'build_augmented_memory_attention': 'build an AugmentedMemoryMultiheadAttention module with memory banks and attention suppression for streaming self-attention', 'create_sequence_encoder': 'create a SequenceEncoder that breaks input sequences into segments and encodes them with augmented memory', 'review_augmented_memory_decorator': 'review the augmented_memory decorator that adds segment-size and context arguments to a streaming model class'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/models/speech_to_text/modules/emformer.py

Prompts

```
['build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create an AugmentedMemoryTransformerEncoderLayer that maintains memory banks and summarization queries for streaming inference', 'build an AugmentedMemoryMultiheadAttention module with memory banks and attention suppression for streaming self-attention', 'create a SequenceEncoder that breaks input sequences into segments and encodes them with augmented memory', 'review the augmented_memory decorator that adds segment-size and context arguments to a streaming model class', 'build a speech-to-text encoder using NoSegAugmentedMemoryTransformerEncoderLayer with augmented memory multihead attention', 'create a RelativePositionEmbedding module with learnable embeddings for a given head dimension and max position', 'build a PositionwiseFF feed-forward network layer with configurable activation function and dropout rates', 'create a SummarizationLayer to reduce segment embeddings using mean, max, linear, or nonlinear methods']
```

Usage

```
{'build_emformer_encoder': 'build a speech-to-text encoder using NoSegAugmentedMemoryTransformerEncoderLayer with augmented memory multihead attention', 'create_relative_position_embedding': 'create a RelativePositionEmbedding module with learnable embeddings for a given head dimension and max position', 'build_positionwise_ffn': 'build a PositionwiseFF feed-forward network layer with configurable activation function and dropout rates', 'create_summarization_layer': 'create a SummarizationLayer to reduce segment embeddings using mean, max, linear, or nonlinear methods', 'build_augmented_memory_attention': 'build a NoSegAugmentedMemoryMultiheadAttentionBmm layer with memory bank, right context, and relative position embedding'}
```

