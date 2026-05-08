# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/speech_to_text/modules/augmented_memory_attention.py

Prompts

```
['build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create an AugmentedMemoryMultiheadAttention module with memory banks and tanh squashing for streaming attention', 'run the SequenceEncoder to encode complete speech sequences by breaking them into segments with context', 'test the AugmentedMemoryTransformerEncoderLayer forward pass with memory bank state and summarization query', 'apply the augmented_memory decorator to a Seq2Seq model class to add segment size and context arguments', 'build a Conv1dSubsampler module with configurable in_channels, mid_channels, out_channels, and kernel_sizes for 1D temporal subsampling', 'run the Conv1dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and output sequence lengths', 'test the Conv1dSubsampler get_out_seq_lens_tensor method to compute output sequence lengths from input lengths', 'build a Conv2dSubsampler module with input_channels, input_feat_per_channel, conv_out_channels, and encoder_embed_dim for 2D subsampling', 'run the Conv2dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and clamped output lengths', 'build a speech-to-text encoder using the emformer_encoder decorator to wrap a FairseqEncoder class with augmented memory transformer layers', 'create a RelativePositionEmbedding module with a given head dimension and max position for learnable relative positional encoding', 'create a PositionwiseFF feed-forward network layer with configurable input dimension, FFN dimension, dropout, and activation function', 'create a SummarizationLayer to reduce segment sequences using mean pooling, max pooling, linear projection, or nonlinear methods']
```

Usage

```
{'build_augmented_memory_encoder': 'build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create_augmented_memory_attention': 'create an AugmentedMemoryMultiheadAttention module with memory banks and tanh squashing for streaming attention', 'run_sequence_encoder': 'run the SequenceEncoder to encode complete speech sequences by breaking them into segments with context', 'test_transformer_encoder_layer': 'test the AugmentedMemoryTransformerEncoderLayer forward pass with memory bank state and summarization query', 'apply_augmented_memory_decorator': 'apply the augmented_memory decorator to a Seq2Seq model class to add segment size and context arguments'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_text/modules/convolution.py

Prompts

```
['build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create an AugmentedMemoryMultiheadAttention module with memory banks and tanh squashing for streaming attention', 'run the SequenceEncoder to encode complete speech sequences by breaking them into segments with context', 'test the AugmentedMemoryTransformerEncoderLayer forward pass with memory bank state and summarization query', 'apply the augmented_memory decorator to a Seq2Seq model class to add segment size and context arguments', 'build a Conv1dSubsampler module with configurable in_channels, mid_channels, out_channels, and kernel_sizes for 1D temporal subsampling', 'run the Conv1dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and output sequence lengths', 'test the Conv1dSubsampler get_out_seq_lens_tensor method to compute output sequence lengths from input lengths', 'build a Conv2dSubsampler module with input_channels, input_feat_per_channel, conv_out_channels, and encoder_embed_dim for 2D subsampling', 'run the Conv2dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and clamped output lengths', 'build a speech-to-text encoder using the emformer_encoder decorator to wrap a FairseqEncoder class with augmented memory transformer layers', 'create a RelativePositionEmbedding module with a given head dimension and max position for learnable relative positional encoding', 'create a PositionwiseFF feed-forward network layer with configurable input dimension, FFN dimension, dropout, and activation function', 'create a SummarizationLayer to reduce segment sequences using mean pooling, max pooling, linear projection, or nonlinear methods']
```

Usage

```
{'build_Conv1dSubsampler': 'build a Conv1dSubsampler module with configurable in_channels, mid_channels, out_channels, and kernel_sizes for 1D temporal subsampling', 'run_Conv1dSubsampler_forward': 'run the Conv1dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and output sequence lengths', 'test_Conv1dSubsampler_get_out_seq_lens_tensor': 'test the Conv1dSubsampler get_out_seq_lens_tensor method to compute output sequence lengths from input lengths', 'build_Conv2dSubsampler': 'build a Conv2dSubsampler module with input_channels, input_feat_per_channel, conv_out_channels, and encoder_embed_dim for 2D subsampling', 'run_Conv2dSubsampler_forward': 'run the Conv2dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and clamped output lengths'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_text/modules/emformer.py

Prompts

```
['build a streaming speech encoder using AugmentedMemoryConvTransformerEncoder with left and right context windows', 'create an AugmentedMemoryMultiheadAttention module with memory banks and tanh squashing for streaming attention', 'run the SequenceEncoder to encode complete speech sequences by breaking them into segments with context', 'test the AugmentedMemoryTransformerEncoderLayer forward pass with memory bank state and summarization query', 'apply the augmented_memory decorator to a Seq2Seq model class to add segment size and context arguments', 'build a Conv1dSubsampler module with configurable in_channels, mid_channels, out_channels, and kernel_sizes for 1D temporal subsampling', 'run the Conv1dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and output sequence lengths', 'test the Conv1dSubsampler get_out_seq_lens_tensor method to compute output sequence lengths from input lengths', 'build a Conv2dSubsampler module with input_channels, input_feat_per_channel, conv_out_channels, and encoder_embed_dim for 2D subsampling', 'run the Conv2dSubsampler forward pass on src_tokens and src_lengths to get subsampled features and clamped output lengths', 'build a speech-to-text encoder using the emformer_encoder decorator to wrap a FairseqEncoder class with augmented memory transformer layers', 'create a RelativePositionEmbedding module with a given head dimension and max position for learnable relative positional encoding', 'create a PositionwiseFF feed-forward network layer with configurable input dimension, FFN dimension, dropout, and activation function', 'create a SummarizationLayer to reduce segment sequences using mean pooling, max pooling, linear projection, or nonlinear methods']
```

Usage

```
{'build_emformer_encoder': 'build a speech-to-text encoder using the emformer_encoder decorator to wrap a FairseqEncoder class with augmented memory transformer layers', 'create_relative_position_embedding': 'create a RelativePositionEmbedding module with a given head dimension and max position for learnable relative positional encoding', 'create_positionwise_ff': 'create a PositionwiseFF feed-forward network layer with configurable input dimension, FFN dimension, dropout, and activation function', 'create_summarization_layer': 'create a SummarizationLayer to reduce segment sequences using mean pooling, max pooling, linear projection, or nonlinear methods', 'create_augmented_memory_attention': 'create a NoSegAugmentedMemoryMultiheadAttentionBmm module for whole utterance augmented memory multi-head attention with optional relative position embedding'}
```

