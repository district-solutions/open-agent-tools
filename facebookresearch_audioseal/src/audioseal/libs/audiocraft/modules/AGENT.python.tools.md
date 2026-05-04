# Agent Python Tools

- repo: facebookresearch/audioseal
- repo_uri: https://github.com/facebookresearch/audioseal

## File: facebookresearch_audioseal/src/audioseal/libs/audiocraft/modules/conv.py

Prompts

```
['build a causal or symmetric Conv1d layer with built-in padding and normalization support', 'build a transposed Conv1d layer with causal padding and configurable right trim ratio', 'build a Conv1d layer wrapped with weight_norm, spectral_norm, or time_group_norm', 'build a transposed Conv1d layer with optional normalization applied to weights', 'use pad1d to pad a 1D tensor with reflect mode and unpad1d to remove padding', 'build a StreamableLSTM module with a given dimension and number of layers for audio processing', 'create a StreamableLSTM with skip connections enabled for residual learning in audio models', 'run a forward pass through StreamableLSTM on convolutional layout tensor input', 'review the StreamableLSTM forward method that permutes data for LSTM processing and back', 'test the StreamableLSTM module to verify input and output tensor dimension handling', 'build a SEANet encoder model to encode audio waveforms into latent representations with configurable downsampling ratios', 'build a SEANet decoder model to decode latent representations back into audio waveforms with configurable upsampling ratios', 'build a SEANet residual block with configurable kernel sizes, dilations, and optional true skip connections', 'build a SEANet encoder that keeps output dimension matching input by adding a reverse transposed convolution layer', 'review the SEANet encoder forward pass to understand how audio is downsampled through residual blocks and convolutions']
```

Usage

```
{'build_StreamableConv1d': 'build a causal or symmetric Conv1d layer with built-in padding and normalization support', 'build_StreamableConvTranspose1d': 'build a transposed Conv1d layer with causal padding and configurable right trim ratio', 'build_NormConv1d': 'build a Conv1d layer wrapped with weight_norm, spectral_norm, or time_group_norm', 'build_NormConvTranspose1d': 'build a transposed Conv1d layer with optional normalization applied to weights', 'use_pad1d_and_unpad1d': 'use pad1d to pad a 1D tensor with reflect mode and unpad1d to remove padding'}
```

## File: facebookresearch_audioseal/src/audioseal/libs/audiocraft/modules/lstm.py

Prompts

```
['build a causal or symmetric Conv1d layer with built-in padding and normalization support', 'build a transposed Conv1d layer with causal padding and configurable right trim ratio', 'build a Conv1d layer wrapped with weight_norm, spectral_norm, or time_group_norm', 'build a transposed Conv1d layer with optional normalization applied to weights', 'use pad1d to pad a 1D tensor with reflect mode and unpad1d to remove padding', 'build a StreamableLSTM module with a given dimension and number of layers for audio processing', 'create a StreamableLSTM with skip connections enabled for residual learning in audio models', 'run a forward pass through StreamableLSTM on convolutional layout tensor input', 'review the StreamableLSTM forward method that permutes data for LSTM processing and back', 'test the StreamableLSTM module to verify input and output tensor dimension handling', 'build a SEANet encoder model to encode audio waveforms into latent representations with configurable downsampling ratios', 'build a SEANet decoder model to decode latent representations back into audio waveforms with configurable upsampling ratios', 'build a SEANet residual block with configurable kernel sizes, dilations, and optional true skip connections', 'build a SEANet encoder that keeps output dimension matching input by adding a reverse transposed convolution layer', 'review the SEANet encoder forward pass to understand how audio is downsampled through residual blocks and convolutions']
```

Usage

```
{'build_streamable_lstm': 'build a StreamableLSTM module with a given dimension and number of layers for audio processing', 'create_lstm_with_skip_connection': 'create a StreamableLSTM with skip connections enabled for residual learning in audio models', 'run_lstm_forward_pass': 'run a forward pass through StreamableLSTM on convolutional layout tensor input', 'review_streamable_lstm_forward': 'review the StreamableLSTM forward method that permutes data for LSTM processing and back', 'test_streamable_lstm_dimensions': 'test the StreamableLSTM module to verify input and output tensor dimension handling'}
```

## File: facebookresearch_audioseal/src/audioseal/libs/audiocraft/modules/seanet.py

Prompts

```
['build a causal or symmetric Conv1d layer with built-in padding and normalization support', 'build a transposed Conv1d layer with causal padding and configurable right trim ratio', 'build a Conv1d layer wrapped with weight_norm, spectral_norm, or time_group_norm', 'build a transposed Conv1d layer with optional normalization applied to weights', 'use pad1d to pad a 1D tensor with reflect mode and unpad1d to remove padding', 'build a StreamableLSTM module with a given dimension and number of layers for audio processing', 'create a StreamableLSTM with skip connections enabled for residual learning in audio models', 'run a forward pass through StreamableLSTM on convolutional layout tensor input', 'review the StreamableLSTM forward method that permutes data for LSTM processing and back', 'test the StreamableLSTM module to verify input and output tensor dimension handling', 'build a SEANet encoder model to encode audio waveforms into latent representations with configurable downsampling ratios', 'build a SEANet decoder model to decode latent representations back into audio waveforms with configurable upsampling ratios', 'build a SEANet residual block with configurable kernel sizes, dilations, and optional true skip connections', 'build a SEANet encoder that keeps output dimension matching input by adding a reverse transposed convolution layer', 'review the SEANet encoder forward pass to understand how audio is downsampled through residual blocks and convolutions']
```

Usage

```
{'build_SEANetEncoder': 'build a SEANet encoder model to encode audio waveforms into latent representations with configurable downsampling ratios', 'build_SEANetDecoder': 'build a SEANet decoder model to decode latent representations back into audio waveforms with configurable upsampling ratios', 'build_SEANetResnetBlock': 'build a SEANet residual block with configurable kernel sizes, dilations, and optional true skip connections', 'build_SEANetEncoderKeepDimension': 'build a SEANet encoder that keeps output dimension matching input by adding a reverse transposed convolution layer', 'review_SEANetEncoder_forward': 'review the SEANet encoder forward pass to understand how audio is downsampled through residual blocks and convolutions'}
```

