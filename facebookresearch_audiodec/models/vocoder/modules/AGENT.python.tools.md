# Agent Python Tools

- repo: facebookresearch/audiodec
- repo_uri: https://github.com/facebookresearch/audiodec

## File: facebookresearch_audiodec/models/vocoder/modules/discriminator.py

Prompts

```
['build a HiFiGAN period discriminator with custom period and kernel sizes for audio GAN training', 'build a multi-period discriminator with periods 2,3,5,7,11 for HiFiGAN vocoder adversarial training', 'build a HiFiGAN scale discriminator with configurable downsampling scales and group convolutions', 'build a multi-scale discriminator that applies AvgPool1d downsampling across multiple scale levels', 'build a multi-resolution spectral discriminator with FFT sizes 1024,2048,512 for UnivNet vocoder training', 'build a MultiReceptiveField module with custom kernel sizes and dilations for HiFiGAN vocoder', 'run forward propagation through a MultiReceptiveField module on an input tensor', 'run inference through a MultiReceptiveField module averaging outputs from multiple residual blocks', 'build a MultiGroupConv1d module with configurable groups for multi-group convolution in vocoder', 'run forward propagation through a MultiGroupConv1d module on an input tensor', 'build a HiFiGANResidualBlock with custom kernel size, channels, and dilation factors for audio vocoding', 'create a HiFiGANResidualBlock with additional convolution layers enabled for deeper feature extraction', 'run a forward pass through a HiFiGANResidualBlock with a batch of audio feature tensors', 'run inference through a HiFiGANResidualBlock using causal convolution for real-time audio generation', 'review the HiFiGANResidualBlock class and its causal convolution layers with residual skip connections']
```

Usage

```
{'build_HiFiGANPeriodDiscriminator': 'build a HiFiGAN period discriminator with custom period and kernel sizes for audio GAN training', 'build_HiFiGANMultiPeriodDiscriminator': 'build a multi-period discriminator with periods 2,3,5,7,11 for HiFiGAN vocoder adversarial training', 'build_HiFiGANScaleDiscriminator': 'build a HiFiGAN scale discriminator with configurable downsampling scales and group convolutions', 'build_HiFiGANMultiScaleDiscriminator': 'build a multi-scale discriminator that applies AvgPool1d downsampling across multiple scale levels', 'build_UnivNetMultiResolutionSpectralDiscriminator': 'build a multi-resolution spectral discriminator with FFT sizes 1024,2048,512 for UnivNet vocoder training'}
```

## File: facebookresearch_audiodec/models/vocoder/modules/multi_fusion.py

Prompts

```
['build a HiFiGAN period discriminator with custom period and kernel sizes for audio GAN training', 'build a multi-period discriminator with periods 2,3,5,7,11 for HiFiGAN vocoder adversarial training', 'build a HiFiGAN scale discriminator with configurable downsampling scales and group convolutions', 'build a multi-scale discriminator that applies AvgPool1d downsampling across multiple scale levels', 'build a multi-resolution spectral discriminator with FFT sizes 1024,2048,512 for UnivNet vocoder training', 'build a MultiReceptiveField module with custom kernel sizes and dilations for HiFiGAN vocoder', 'run forward propagation through a MultiReceptiveField module on an input tensor', 'run inference through a MultiReceptiveField module averaging outputs from multiple residual blocks', 'build a MultiGroupConv1d module with configurable groups for multi-group convolution in vocoder', 'run forward propagation through a MultiGroupConv1d module on an input tensor', 'build a HiFiGANResidualBlock with custom kernel size, channels, and dilation factors for audio vocoding', 'create a HiFiGANResidualBlock with additional convolution layers enabled for deeper feature extraction', 'run a forward pass through a HiFiGANResidualBlock with a batch of audio feature tensors', 'run inference through a HiFiGANResidualBlock using causal convolution for real-time audio generation', 'review the HiFiGANResidualBlock class and its causal convolution layers with residual skip connections']
```

Usage

```
{'build_multi_receptive_field_module': 'build a MultiReceptiveField module with custom kernel sizes and dilations for HiFiGAN vocoder', 'run_multi_receptive_field_forward': 'run forward propagation through a MultiReceptiveField module on an input tensor', 'run_multi_receptive_field_inference': 'run inference through a MultiReceptiveField module averaging outputs from multiple residual blocks', 'build_multi_group_conv1d_module': 'build a MultiGroupConv1d module with configurable groups for multi-group convolution in vocoder', 'run_multi_group_conv1d_forward': 'run forward propagation through a MultiGroupConv1d module on an input tensor'}
```

## File: facebookresearch_audiodec/models/vocoder/modules/residual_block.py

Prompts

```
['build a HiFiGAN period discriminator with custom period and kernel sizes for audio GAN training', 'build a multi-period discriminator with periods 2,3,5,7,11 for HiFiGAN vocoder adversarial training', 'build a HiFiGAN scale discriminator with configurable downsampling scales and group convolutions', 'build a multi-scale discriminator that applies AvgPool1d downsampling across multiple scale levels', 'build a multi-resolution spectral discriminator with FFT sizes 1024,2048,512 for UnivNet vocoder training', 'build a MultiReceptiveField module with custom kernel sizes and dilations for HiFiGAN vocoder', 'run forward propagation through a MultiReceptiveField module on an input tensor', 'run inference through a MultiReceptiveField module averaging outputs from multiple residual blocks', 'build a MultiGroupConv1d module with configurable groups for multi-group convolution in vocoder', 'run forward propagation through a MultiGroupConv1d module on an input tensor', 'build a HiFiGANResidualBlock with custom kernel size, channels, and dilation factors for audio vocoding', 'create a HiFiGANResidualBlock with additional convolution layers enabled for deeper feature extraction', 'run a forward pass through a HiFiGANResidualBlock with a batch of audio feature tensors', 'run inference through a HiFiGANResidualBlock using causal convolution for real-time audio generation', 'review the HiFiGANResidualBlock class and its causal convolution layers with residual skip connections']
```

Usage

```
{'build_hifigan_residual_block': 'build a HiFiGANResidualBlock with custom kernel size, channels, and dilation factors for audio vocoding', 'create_residual_block_with_additional_convs': 'create a HiFiGANResidualBlock with additional convolution layers enabled for deeper feature extraction', 'run_forward_pass_residual_block': 'run a forward pass through a HiFiGANResidualBlock with a batch of audio feature tensors', 'run_inference_residual_block': 'run inference through a HiFiGANResidualBlock using causal convolution for real-time audio generation', 'review_hifigan_residual_block_architecture': 'review the HiFiGANResidualBlock class and its causal convolution layers with residual skip connections'}
```

