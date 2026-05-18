# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/diffusionmodules/model.py

Prompts

```
['build a U-Net denoiser model with ResnetBlock, attention, and timestep embeddings for diffusion', 'create an Encoder to downsample input images into a compressed latent representation', 'create a Decoder to reconstruct output images from latent space representations', 'test the ResnetBlock forward pass with input tensor and timestep embedding', 'review the AttnBlock class and its self-attention computation on 2D feature maps', 'build a UNetModel with attention and timestep embedding for diffusion model inference', 'build an EncoderUNetModel with adaptive pooling for image classification and feature extraction', 'create a ResBlock with optional channel change and timestep conditioning for residual learning', 'create an AttentionBlock with QKV self-attention for spatial position attention in diffusion models', 'create a TimestepEmbedSequential module that passes timestep embeddings to child layers automatically', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt strategies', 'build DDIM timestep discretization for faster sampling from a DDPM model using uniform or quad methods', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension and max period', 'build a gradient checkpointing wrapper to reduce memory usage during model training by recomputing activations in the backward pass', 'create a 1D, 2D, or 3D convolution module dynamically based on the specified dimensionality parameter']
```

Usage

```
{'build_Model_denoiser': 'build a U-Net denoiser model with ResnetBlock, attention, and timestep embeddings for diffusion', 'create_Encoder_latent_space': 'create an Encoder to downsample input images into a compressed latent representation', 'create_Decoder_reconstruct': 'create a Decoder to reconstruct output images from latent space representations', 'test_ResnetBlock_forward': 'test the ResnetBlock forward pass with input tensor and timestep embedding', 'review_AttnBlock_self_attention': 'review the AttnBlock class and its self-attention computation on 2D feature maps'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/diffusionmodules/openaimodel.py

Prompts

```
['build a U-Net denoiser model with ResnetBlock, attention, and timestep embeddings for diffusion', 'create an Encoder to downsample input images into a compressed latent representation', 'create a Decoder to reconstruct output images from latent space representations', 'test the ResnetBlock forward pass with input tensor and timestep embedding', 'review the AttnBlock class and its self-attention computation on 2D feature maps', 'build a UNetModel with attention and timestep embedding for diffusion model inference', 'build an EncoderUNetModel with adaptive pooling for image classification and feature extraction', 'create a ResBlock with optional channel change and timestep conditioning for residual learning', 'create an AttentionBlock with QKV self-attention for spatial position attention in diffusion models', 'create a TimestepEmbedSequential module that passes timestep embeddings to child layers automatically', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt strategies', 'build DDIM timestep discretization for faster sampling from a DDPM model using uniform or quad methods', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension and max period', 'build a gradient checkpointing wrapper to reduce memory usage during model training by recomputing activations in the backward pass', 'create a 1D, 2D, or 3D convolution module dynamically based on the specified dimensionality parameter']
```

Usage

```
{'build_UNetModel': 'build a UNetModel with attention and timestep embedding for diffusion model inference', 'build_EncoderUNetModel': 'build an EncoderUNetModel with adaptive pooling for image classification and feature extraction', 'create_ResBlock': 'create a ResBlock with optional channel change and timestep conditioning for residual learning', 'create_AttentionBlock': 'create an AttentionBlock with QKV self-attention for spatial position attention in diffusion models', 'create_TimestepEmbedSequential': 'create a TimestepEmbedSequential module that passes timestep embeddings to child layers automatically'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/modules/diffusionmodules/util.py

Prompts

```
['build a U-Net denoiser model with ResnetBlock, attention, and timestep embeddings for diffusion', 'create an Encoder to downsample input images into a compressed latent representation', 'create a Decoder to reconstruct output images from latent space representations', 'test the ResnetBlock forward pass with input tensor and timestep embedding', 'review the AttnBlock class and its self-attention computation on 2D feature maps', 'build a UNetModel with attention and timestep embedding for diffusion model inference', 'build an EncoderUNetModel with adaptive pooling for image classification and feature extraction', 'create a ResBlock with optional channel change and timestep conditioning for residual learning', 'create an AttentionBlock with QKV self-attention for spatial position attention in diffusion models', 'create a TimestepEmbedSequential module that passes timestep embeddings to child layers automatically', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt strategies', 'build DDIM timestep discretization for faster sampling from a DDPM model using uniform or quad methods', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension and max period', 'build a gradient checkpointing wrapper to reduce memory usage during model training by recomputing activations in the backward pass', 'create a 1D, 2D, or 3D convolution module dynamically based on the specified dimensionality parameter']
```

Usage

```
{'make_beta_schedule': 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt strategies', 'make_ddim_timesteps': 'build DDIM timestep discretization for faster sampling from a DDPM model using uniform or quad methods', 'timestep_embedding': 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension and max period', 'checkpoint': 'build a gradient checkpointing wrapper to reduce memory usage during model training by recomputing activations in the backward pass', 'conv_nd': 'create a 1D, 2D, or 3D convolution module dynamically based on the specified dimensionality parameter'}
```

