# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/layers.py

Prompts

```
['build a 1x1 convolution layer with NCSN initialization for score network feature transformation', 'build a 3x3 convolution layer with DDPM variance scaling initialization for diffusion models', 'create a ResNet block with group normalization and time embedding support for DDPM architectures', 'create a channel-wise self-attention block with NIN layers for DDPM score networks', 'create a conditional residual block with class-based normalization for NCSN++ score networks', 'build a GaussianFourierProjection module to generate sinusoidal Fourier embeddings for noise levels in diffusion models', 'create an AttnBlockpp channel-wise self-attention block with group normalization and skip rescale for NCSN++ networks', 'build a ResnetBlockBigGANpp residual block with optional upsampling or downsampling and time embedding support', 'create a ResnetBlockDDPMpp residual block with group normalization dropout and optional time embedding conditioning', 'build a Combine module to merge skip connection features using concatenation or summation methods', 'build a python module that uses get_normalization to obtain a normalization layer from a config object', 'create a ConditionalBatchNorm2d layer with class-conditional gamma and beta embeddings for 2D feature maps', 'create an InstanceNorm2dPlus layer that normalizes features using instance norm with learnable alpha and gamma parameters', 'create a ConditionalInstanceNorm2dPlus layer that applies class-conditional instance normalization with embedded gamma, alpha, and beta', 'create a VarianceNorm2d layer that normalizes features by dividing by their per-feature variance with learnable alpha scaling', 'create a Conv2d layer with upsampling enabled for StyleGAN2-style image upscaling', 'create a Conv2d layer with downsampling enabled for StyleGAN2-style image downscaling', 'run naive_upsample_2d to upsample a PyTorch tensor by repeating pixels with a given factor', 'run naive_downsample_2d to downsample a PyTorch tensor by averaging pixel blocks with a given factor', 'run upsample_conv_2d to fuse upsampling and convolution on a tensor with an FIR filter']
```

Usage

```
{'build_ncsn_conv1x1': 'build a 1x1 convolution layer with NCSN initialization for score network feature transformation', 'build_ddpm_conv3x3': 'build a 3x3 convolution layer with DDPM variance scaling initialization for diffusion models', 'create_ResnetBlockDDPM': 'create a ResNet block with group normalization and time embedding support for DDPM architectures', 'create_AttnBlock': 'create a channel-wise self-attention block with NIN layers for DDPM score networks', 'create_ConditionalResidualBlock': 'create a conditional residual block with class-based normalization for NCSN++ score networks'}
```

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/layerspp.py

Prompts

```
['build a 1x1 convolution layer with NCSN initialization for score network feature transformation', 'build a 3x3 convolution layer with DDPM variance scaling initialization for diffusion models', 'create a ResNet block with group normalization and time embedding support for DDPM architectures', 'create a channel-wise self-attention block with NIN layers for DDPM score networks', 'create a conditional residual block with class-based normalization for NCSN++ score networks', 'build a GaussianFourierProjection module to generate sinusoidal Fourier embeddings for noise levels in diffusion models', 'create an AttnBlockpp channel-wise self-attention block with group normalization and skip rescale for NCSN++ networks', 'build a ResnetBlockBigGANpp residual block with optional upsampling or downsampling and time embedding support', 'create a ResnetBlockDDPMpp residual block with group normalization dropout and optional time embedding conditioning', 'build a Combine module to merge skip connection features using concatenation or summation methods', 'build a python module that uses get_normalization to obtain a normalization layer from a config object', 'create a ConditionalBatchNorm2d layer with class-conditional gamma and beta embeddings for 2D feature maps', 'create an InstanceNorm2dPlus layer that normalizes features using instance norm with learnable alpha and gamma parameters', 'create a ConditionalInstanceNorm2dPlus layer that applies class-conditional instance normalization with embedded gamma, alpha, and beta', 'create a VarianceNorm2d layer that normalizes features by dividing by their per-feature variance with learnable alpha scaling', 'create a Conv2d layer with upsampling enabled for StyleGAN2-style image upscaling', 'create a Conv2d layer with downsampling enabled for StyleGAN2-style image downscaling', 'run naive_upsample_2d to upsample a PyTorch tensor by repeating pixels with a given factor', 'run naive_downsample_2d to downsample a PyTorch tensor by averaging pixel blocks with a given factor', 'run upsample_conv_2d to fuse upsampling and convolution on a tensor with an FIR filter']
```

Usage

```
{'build_GaussianFourierProjection': 'build a GaussianFourierProjection module to generate sinusoidal Fourier embeddings for noise levels in diffusion models', 'create_AttnBlockpp': 'create an AttnBlockpp channel-wise self-attention block with group normalization and skip rescale for NCSN++ networks', 'build_ResnetBlockBigGANpp': 'build a ResnetBlockBigGANpp residual block with optional upsampling or downsampling and time embedding support', 'create_ResnetBlockDDPMpp': 'create a ResnetBlockDDPMpp residual block with group normalization dropout and optional time embedding conditioning', 'build_Combine': 'build a Combine module to merge skip connection features using concatenation or summation methods'}
```

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/normalization.py

Prompts

```
['build a 1x1 convolution layer with NCSN initialization for score network feature transformation', 'build a 3x3 convolution layer with DDPM variance scaling initialization for diffusion models', 'create a ResNet block with group normalization and time embedding support for DDPM architectures', 'create a channel-wise self-attention block with NIN layers for DDPM score networks', 'create a conditional residual block with class-based normalization for NCSN++ score networks', 'build a GaussianFourierProjection module to generate sinusoidal Fourier embeddings for noise levels in diffusion models', 'create an AttnBlockpp channel-wise self-attention block with group normalization and skip rescale for NCSN++ networks', 'build a ResnetBlockBigGANpp residual block with optional upsampling or downsampling and time embedding support', 'create a ResnetBlockDDPMpp residual block with group normalization dropout and optional time embedding conditioning', 'build a Combine module to merge skip connection features using concatenation or summation methods', 'build a python module that uses get_normalization to obtain a normalization layer from a config object', 'create a ConditionalBatchNorm2d layer with class-conditional gamma and beta embeddings for 2D feature maps', 'create an InstanceNorm2dPlus layer that normalizes features using instance norm with learnable alpha and gamma parameters', 'create a ConditionalInstanceNorm2dPlus layer that applies class-conditional instance normalization with embedded gamma, alpha, and beta', 'create a VarianceNorm2d layer that normalizes features by dividing by their per-feature variance with learnable alpha scaling', 'create a Conv2d layer with upsampling enabled for StyleGAN2-style image upscaling', 'create a Conv2d layer with downsampling enabled for StyleGAN2-style image downscaling', 'run naive_upsample_2d to upsample a PyTorch tensor by repeating pixels with a given factor', 'run naive_downsample_2d to downsample a PyTorch tensor by averaging pixel blocks with a given factor', 'run upsample_conv_2d to fuse upsampling and convolution on a tensor with an FIR filter']
```

Usage

```
{'build_normalization_from_config': 'build a python module that uses get_normalization to obtain a normalization layer from a config object', 'create_conditional_batch_norm': 'create a ConditionalBatchNorm2d layer with class-conditional gamma and beta embeddings for 2D feature maps', 'create_instance_norm_plus': 'create an InstanceNorm2dPlus layer that normalizes features using instance norm with learnable alpha and gamma parameters', 'create_conditional_instance_norm_plus': 'create a ConditionalInstanceNorm2dPlus layer that applies class-conditional instance normalization with embedded gamma, alpha, and beta', 'create_variance_norm': 'create a VarianceNorm2d layer that normalizes features by dividing by their per-feature variance with learnable alpha scaling'}
```

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/up_or_down_sampling.py

Prompts

```
['build a 1x1 convolution layer with NCSN initialization for score network feature transformation', 'build a 3x3 convolution layer with DDPM variance scaling initialization for diffusion models', 'create a ResNet block with group normalization and time embedding support for DDPM architectures', 'create a channel-wise self-attention block with NIN layers for DDPM score networks', 'create a conditional residual block with class-based normalization for NCSN++ score networks', 'build a GaussianFourierProjection module to generate sinusoidal Fourier embeddings for noise levels in diffusion models', 'create an AttnBlockpp channel-wise self-attention block with group normalization and skip rescale for NCSN++ networks', 'build a ResnetBlockBigGANpp residual block with optional upsampling or downsampling and time embedding support', 'create a ResnetBlockDDPMpp residual block with group normalization dropout and optional time embedding conditioning', 'build a Combine module to merge skip connection features using concatenation or summation methods', 'build a python module that uses get_normalization to obtain a normalization layer from a config object', 'create a ConditionalBatchNorm2d layer with class-conditional gamma and beta embeddings for 2D feature maps', 'create an InstanceNorm2dPlus layer that normalizes features using instance norm with learnable alpha and gamma parameters', 'create a ConditionalInstanceNorm2dPlus layer that applies class-conditional instance normalization with embedded gamma, alpha, and beta', 'create a VarianceNorm2d layer that normalizes features by dividing by their per-feature variance with learnable alpha scaling', 'create a Conv2d layer with upsampling enabled for StyleGAN2-style image upscaling', 'create a Conv2d layer with downsampling enabled for StyleGAN2-style image downscaling', 'run naive_upsample_2d to upsample a PyTorch tensor by repeating pixels with a given factor', 'run naive_downsample_2d to downsample a PyTorch tensor by averaging pixel blocks with a given factor', 'run upsample_conv_2d to fuse upsampling and convolution on a tensor with an FIR filter']
```

Usage

```
{'create_Conv2d_upsample': 'create a Conv2d layer with upsampling enabled for StyleGAN2-style image upscaling', 'create_Conv2d_downsample': 'create a Conv2d layer with downsampling enabled for StyleGAN2-style image downscaling', 'run_naive_upsample_2d': 'run naive_upsample_2d to upsample a PyTorch tensor by repeating pixels with a given factor', 'run_naive_downsample_2d': 'run naive_downsample_2d to downsample a PyTorch tensor by averaging pixel blocks with a given factor', 'run_upsample_conv_2d': 'run upsample_conv_2d to fuse upsampling and convolution on a tensor with an FIR filter'}
```

