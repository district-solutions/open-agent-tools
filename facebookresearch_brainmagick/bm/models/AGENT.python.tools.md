# Agent Python Tools

- repo: facebookresearch/brainmagick
- repo_uri: https://github.com/facebookresearch/brainmagick

## File: facebookresearch_brainmagick/bm/models/common.py

Prompts

```
['build a ConvSequence module with configurable channels, kernel size, stride, dropout, and skip connections for 1D convolutions', 'create a ScaledEmbedding layer that scales up the learning rate for embeddings to prevent slow convergence', 'build a SubjectLayers module with per-subject linear transformation weights for multi-subject neural data processing', 'create a ChannelMerger module that merges MEG channels using Fourier positional embeddings and softmax attention weights', 'build a FourierEmb layer that generates Fourier positional embeddings from 2D normalized sensor coordinates', 'build a ConvRNN model with configurable conv depth, LSTM layers, and attention heads for MEG signal processing', 'create an LSTM wrapper that normalizes bidirectional output dimensions via a linear projection layer', 'create a multi-head attention module with relative positional embeddings and radius-limited temporal attention', 'run the ConvRNN forward pass with MEG inputs and subject batch to produce decoded temporal outputs', 'test the ConvRNN valid_length method to compute nearest valid input length for clean convolutions', 'build a SimpleConv neural network model with configurable depth, kernel size, and channel dimensions', 'create a SimpleConv model with STFT spectrogram transform for MEG signal processing', 'run the SimpleConv forward pass with input tensors and batch subject index data', 'review the SimpleConv model to add DualPathRNN layers for sequential feature processing', 'refactor the SimpleConv model to enable subject-specific layers for multi-subject MEG data']
```

Usage

```
{'build_convsequence_module': 'build a ConvSequence module with configurable channels, kernel size, stride, dropout, and skip connections for 1D convolutions', 'create_scaledembedding_layer': 'create a ScaledEmbedding layer that scales up the learning rate for embeddings to prevent slow convergence', 'build_subjectlayers_module': 'build a SubjectLayers module with per-subject linear transformation weights for multi-subject neural data processing', 'create_channelmerger_module': 'create a ChannelMerger module that merges MEG channels using Fourier positional embeddings and softmax attention weights', 'build_fourieremb_layer': 'build a FourierEmb layer that generates Fourier positional embeddings from 2D normalized sensor coordinates'}
```

## File: facebookresearch_brainmagick/bm/models/convrnn.py

Prompts

```
['build a ConvSequence module with configurable channels, kernel size, stride, dropout, and skip connections for 1D convolutions', 'create a ScaledEmbedding layer that scales up the learning rate for embeddings to prevent slow convergence', 'build a SubjectLayers module with per-subject linear transformation weights for multi-subject neural data processing', 'create a ChannelMerger module that merges MEG channels using Fourier positional embeddings and softmax attention weights', 'build a FourierEmb layer that generates Fourier positional embeddings from 2D normalized sensor coordinates', 'build a ConvRNN model with configurable conv depth, LSTM layers, and attention heads for MEG signal processing', 'create an LSTM wrapper that normalizes bidirectional output dimensions via a linear projection layer', 'create a multi-head attention module with relative positional embeddings and radius-limited temporal attention', 'run the ConvRNN forward pass with MEG inputs and subject batch to produce decoded temporal outputs', 'test the ConvRNN valid_length method to compute nearest valid input length for clean convolutions', 'build a SimpleConv neural network model with configurable depth, kernel size, and channel dimensions', 'create a SimpleConv model with STFT spectrogram transform for MEG signal processing', 'run the SimpleConv forward pass with input tensors and batch subject index data', 'review the SimpleConv model to add DualPathRNN layers for sequential feature processing', 'refactor the SimpleConv model to enable subject-specific layers for multi-subject MEG data']
```

Usage

```
{'build_ConvRNN_model': 'build a ConvRNN model with configurable conv depth, LSTM layers, and attention heads for MEG signal processing', 'create_LSTM_wrapper': 'create an LSTM wrapper that normalizes bidirectional output dimensions via a linear projection layer', 'create_Attention_module': 'create a multi-head attention module with relative positional embeddings and radius-limited temporal attention', 'run_ConvRNN_forward': 'run the ConvRNN forward pass with MEG inputs and subject batch to produce decoded temporal outputs', 'test_ConvRNN_valid_length': 'test the ConvRNN valid_length method to compute nearest valid input length for clean convolutions'}
```

## File: facebookresearch_brainmagick/bm/models/simpleconv.py

Prompts

```
['build a ConvSequence module with configurable channels, kernel size, stride, dropout, and skip connections for 1D convolutions', 'create a ScaledEmbedding layer that scales up the learning rate for embeddings to prevent slow convergence', 'build a SubjectLayers module with per-subject linear transformation weights for multi-subject neural data processing', 'create a ChannelMerger module that merges MEG channels using Fourier positional embeddings and softmax attention weights', 'build a FourierEmb layer that generates Fourier positional embeddings from 2D normalized sensor coordinates', 'build a ConvRNN model with configurable conv depth, LSTM layers, and attention heads for MEG signal processing', 'create an LSTM wrapper that normalizes bidirectional output dimensions via a linear projection layer', 'create a multi-head attention module with relative positional embeddings and radius-limited temporal attention', 'run the ConvRNN forward pass with MEG inputs and subject batch to produce decoded temporal outputs', 'test the ConvRNN valid_length method to compute nearest valid input length for clean convolutions', 'build a SimpleConv neural network model with configurable depth, kernel size, and channel dimensions', 'create a SimpleConv model with STFT spectrogram transform for MEG signal processing', 'run the SimpleConv forward pass with input tensors and batch subject index data', 'review the SimpleConv model to add DualPathRNN layers for sequential feature processing', 'refactor the SimpleConv model to enable subject-specific layers for multi-subject MEG data']
```

Usage

```
{'build_SimpleConv_model': 'build a SimpleConv neural network model with configurable depth, kernel size, and channel dimensions', 'create_SimpleConv_with_STFT': 'create a SimpleConv model with STFT spectrogram transform for MEG signal processing', 'run_SimpleConv_forward': 'run the SimpleConv forward pass with input tensors and batch subject index data', 'review_SimpleConv_dual_path': 'review the SimpleConv model to add DualPathRNN layers for sequential feature processing', 'refactor_SimpleConv_subject_layers': 'refactor the SimpleConv model to enable subject-specific layers for multi-subject MEG data'}
```

