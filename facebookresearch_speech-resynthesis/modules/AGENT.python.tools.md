# Agent Python Tools

- repo: facebookresearch/speech-resynthesis
- repo_uri: https://github.com/facebookresearch/speech-resynthesis

## File: facebookresearch_speech-resynthesis/modules/dist.py

Prompts

```
['init a distributed process group with a given backend and init method for multi-GPU training', 'get the current process rank in the distributed process group or zero if unavailable', 'all_reduce a tensor across all processes using SUM, PRODUCT, MIN, or MAX operations', 'all_gather tensors from all processes into a list for cross-rank data collection', 'barrier all processes in the distributed group to synchronize execution across ranks', 'build a multi-level Encoder with downsampling strides to encode audio embeddings into hierarchical representations', 'build a multi-level Decoder with upsampling strides to decode hierarchical embeddings back to audio', 'create an EncoderConvBlock with configurable stride and downsampling for 1D audio feature extraction', 'create a DecoderConvBock with transposed convolutions and ResNet blocks for audio upsampling', 'test the assert_shape utility function to validate tensor dimensions match expected shapes', 'build a 2D residual convolutional network using Resnet with n_in channels and n_depth layers', 'build a 1D residual convolutional network using Resnet1D with configurable dilation growth rate and cycle', 'create a ResConvBlock with n_in input channels and n_state hidden state for 2D residual convolutions', 'create a ResConv1DBlock with configurable dilation, zero_out initialization, and res_scale for 1D residual convolutions', 'review the Resnet1D class and its dilation_growth_rate, dilation_cycle, and reverse_dilation parameters', 'create a BottleneckBlock with k_bins, emb_width, and mu parameters for vector quantization', 'encode input tensor through BottleneckBlock to get discrete latent codes via quantise', 'decode discrete latent codes back to continuous embeddings using BottleneckBlock dequantise', 'create a multi-level Bottleneck with l_bins, emb_width, mu, and levels for hierarchical quantization', 'run multi-level Bottleneck forward pass to get quantized codes, commit losses, and metrics']
```

Usage

```
{'init_process_group': 'init a distributed process group with a given backend and init method for multi-GPU training', 'get_rank': 'get the current process rank in the distributed process group or zero if unavailable', 'all_reduce': 'all_reduce a tensor across all processes using SUM, PRODUCT, MIN, or MAX operations', 'all_gather': 'all_gather tensors from all processes into a list for cross-rank data collection', 'barrier': 'barrier all processes in the distributed group to synchronize execution across ranks'}
```

## File: facebookresearch_speech-resynthesis/modules/jukebox.py

Prompts

```
['init a distributed process group with a given backend and init method for multi-GPU training', 'get the current process rank in the distributed process group or zero if unavailable', 'all_reduce a tensor across all processes using SUM, PRODUCT, MIN, or MAX operations', 'all_gather tensors from all processes into a list for cross-rank data collection', 'barrier all processes in the distributed group to synchronize execution across ranks', 'build a multi-level Encoder with downsampling strides to encode audio embeddings into hierarchical representations', 'build a multi-level Decoder with upsampling strides to decode hierarchical embeddings back to audio', 'create an EncoderConvBlock with configurable stride and downsampling for 1D audio feature extraction', 'create a DecoderConvBock with transposed convolutions and ResNet blocks for audio upsampling', 'test the assert_shape utility function to validate tensor dimensions match expected shapes', 'build a 2D residual convolutional network using Resnet with n_in channels and n_depth layers', 'build a 1D residual convolutional network using Resnet1D with configurable dilation growth rate and cycle', 'create a ResConvBlock with n_in input channels and n_state hidden state for 2D residual convolutions', 'create a ResConv1DBlock with configurable dilation, zero_out initialization, and res_scale for 1D residual convolutions', 'review the Resnet1D class and its dilation_growth_rate, dilation_cycle, and reverse_dilation parameters', 'create a BottleneckBlock with k_bins, emb_width, and mu parameters for vector quantization', 'encode input tensor through BottleneckBlock to get discrete latent codes via quantise', 'decode discrete latent codes back to continuous embeddings using BottleneckBlock dequantise', 'create a multi-level Bottleneck with l_bins, emb_width, mu, and levels for hierarchical quantization', 'run multi-level Bottleneck forward pass to get quantized codes, commit losses, and metrics']
```

Usage

```
{'build_encoder_multilevel': 'build a multi-level Encoder with downsampling strides to encode audio embeddings into hierarchical representations', 'build_decoder_multilevel': 'build a multi-level Decoder with upsampling strides to decode hierarchical embeddings back to audio', 'create_encoder_conv_block': 'create an EncoderConvBlock with configurable stride and downsampling for 1D audio feature extraction', 'create_decoder_conv_block': 'create a DecoderConvBock with transposed convolutions and ResNet blocks for audio upsampling', 'test_assert_shape': 'test the assert_shape utility function to validate tensor dimensions match expected shapes'}
```

## File: facebookresearch_speech-resynthesis/modules/resnet.py

Prompts

```
['init a distributed process group with a given backend and init method for multi-GPU training', 'get the current process rank in the distributed process group or zero if unavailable', 'all_reduce a tensor across all processes using SUM, PRODUCT, MIN, or MAX operations', 'all_gather tensors from all processes into a list for cross-rank data collection', 'barrier all processes in the distributed group to synchronize execution across ranks', 'build a multi-level Encoder with downsampling strides to encode audio embeddings into hierarchical representations', 'build a multi-level Decoder with upsampling strides to decode hierarchical embeddings back to audio', 'create an EncoderConvBlock with configurable stride and downsampling for 1D audio feature extraction', 'create a DecoderConvBock with transposed convolutions and ResNet blocks for audio upsampling', 'test the assert_shape utility function to validate tensor dimensions match expected shapes', 'build a 2D residual convolutional network using Resnet with n_in channels and n_depth layers', 'build a 1D residual convolutional network using Resnet1D with configurable dilation growth rate and cycle', 'create a ResConvBlock with n_in input channels and n_state hidden state for 2D residual convolutions', 'create a ResConv1DBlock with configurable dilation, zero_out initialization, and res_scale for 1D residual convolutions', 'review the Resnet1D class and its dilation_growth_rate, dilation_cycle, and reverse_dilation parameters', 'create a BottleneckBlock with k_bins, emb_width, and mu parameters for vector quantization', 'encode input tensor through BottleneckBlock to get discrete latent codes via quantise', 'decode discrete latent codes back to continuous embeddings using BottleneckBlock dequantise', 'create a multi-level Bottleneck with l_bins, emb_width, mu, and levels for hierarchical quantization', 'run multi-level Bottleneck forward pass to get quantized codes, commit losses, and metrics']
```

Usage

```
{'build_resnet_2d': 'build a 2D residual convolutional network using Resnet with n_in channels and n_depth layers', 'build_resnet_1d': 'build a 1D residual convolutional network using Resnet1D with configurable dilation growth rate and cycle', 'create_resconvblock': 'create a ResConvBlock with n_in input channels and n_state hidden state for 2D residual convolutions', 'create_resconv1dblock': 'create a ResConv1DBlock with configurable dilation, zero_out initialization, and res_scale for 1D residual convolutions', 'review_resnet1d_dilation': 'review the Resnet1D class and its dilation_growth_rate, dilation_cycle, and reverse_dilation parameters'}
```

## File: facebookresearch_speech-resynthesis/modules/vq.py

Prompts

```
['init a distributed process group with a given backend and init method for multi-GPU training', 'get the current process rank in the distributed process group or zero if unavailable', 'all_reduce a tensor across all processes using SUM, PRODUCT, MIN, or MAX operations', 'all_gather tensors from all processes into a list for cross-rank data collection', 'barrier all processes in the distributed group to synchronize execution across ranks', 'build a multi-level Encoder with downsampling strides to encode audio embeddings into hierarchical representations', 'build a multi-level Decoder with upsampling strides to decode hierarchical embeddings back to audio', 'create an EncoderConvBlock with configurable stride and downsampling for 1D audio feature extraction', 'create a DecoderConvBock with transposed convolutions and ResNet blocks for audio upsampling', 'test the assert_shape utility function to validate tensor dimensions match expected shapes', 'build a 2D residual convolutional network using Resnet with n_in channels and n_depth layers', 'build a 1D residual convolutional network using Resnet1D with configurable dilation growth rate and cycle', 'create a ResConvBlock with n_in input channels and n_state hidden state for 2D residual convolutions', 'create a ResConv1DBlock with configurable dilation, zero_out initialization, and res_scale for 1D residual convolutions', 'review the Resnet1D class and its dilation_growth_rate, dilation_cycle, and reverse_dilation parameters', 'create a BottleneckBlock with k_bins, emb_width, and mu parameters for vector quantization', 'encode input tensor through BottleneckBlock to get discrete latent codes via quantise', 'decode discrete latent codes back to continuous embeddings using BottleneckBlock dequantise', 'create a multi-level Bottleneck with l_bins, emb_width, mu, and levels for hierarchical quantization', 'run multi-level Bottleneck forward pass to get quantized codes, commit losses, and metrics']
```

Usage

```
{'create_bottleneckblock': 'create a BottleneckBlock with k_bins, emb_width, and mu parameters for vector quantization', 'encode_with_bottleneckblock': 'encode input tensor through BottleneckBlock to get discrete latent codes via quantise', 'decode_with_bottleneckblock': 'decode discrete latent codes back to continuous embeddings using BottleneckBlock dequantise', 'create_bottleneck': 'create a multi-level Bottleneck with l_bins, emb_width, mu, and levels for hierarchical quantization', 'forward_bottleneck': 'run multi-level Bottleneck forward pass to get quantized codes, commit losses, and metrics'}
```

