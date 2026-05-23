# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/modules/diffusionmodules/model.py

Prompts

```
['build a U-Net denoiser model with timestep embeddings and attention for diffusion', 'build an encoder to downsample images into a latent representation with resnet blocks', 'build a decoder to upsample latent representations back to image space with attention', 'create a self-attention block with optional xformers memory-efficient implementation', 'create a residual block with group normalization and timestep embedding projection', 'build a UNetModel with configurable attention, timestep embedding, and spatial transformer support for diffusion', 'create a ResBlock with optional channel change, upsampling, downsampling, and scale shift norm', 'create an AttentionBlock with configurable heads and QKV attention for spatial self-attention', 'create a TimestepEmbedSequential that routes timestep embeddings to child TimestepBlock layers', 'create a QKVAttention module that performs multi-head attention on query key value tensors', 'build a low scale model that registers diffusion noise schedules and buffers for image upscaling', 'build a simple image concatenation model that returns input with zero noise levels', 'build an image concatenation model with configurable noise augmentation and random noise levels', 'test the AbstractLowScaleModel register_schedule method to set up beta schedules and diffusion buffers', 'test the q_sample method to add noise to images at specified timesteps', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt methods', 'build DDIM timestep discretization for faster diffusion sampling using uniform or quad methods', 'compute DDIM sampling parameters including sigmas and alphas for a given eta value', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension', 'run gradient checkpointing on a function to reduce memory usage at the cost of extra compute']
```

Usage

```
{'build_Model_denoiser': 'build a U-Net denoiser model with timestep embeddings and attention for diffusion', 'build_Encoder_latent': 'build an encoder to downsample images into a latent representation with resnet blocks', 'build_Decoder_latent': 'build a decoder to upsample latent representations back to image space with attention', 'create_attn_block': 'create a self-attention block with optional xformers memory-efficient implementation', 'create_ResnetBlock': 'create a residual block with group normalization and timestep embedding projection'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/diffusionmodules/openaimodel.py

Prompts

```
['build a U-Net denoiser model with timestep embeddings and attention for diffusion', 'build an encoder to downsample images into a latent representation with resnet blocks', 'build a decoder to upsample latent representations back to image space with attention', 'create a self-attention block with optional xformers memory-efficient implementation', 'create a residual block with group normalization and timestep embedding projection', 'build a UNetModel with configurable attention, timestep embedding, and spatial transformer support for diffusion', 'create a ResBlock with optional channel change, upsampling, downsampling, and scale shift norm', 'create an AttentionBlock with configurable heads and QKV attention for spatial self-attention', 'create a TimestepEmbedSequential that routes timestep embeddings to child TimestepBlock layers', 'create a QKVAttention module that performs multi-head attention on query key value tensors', 'build a low scale model that registers diffusion noise schedules and buffers for image upscaling', 'build a simple image concatenation model that returns input with zero noise levels', 'build an image concatenation model with configurable noise augmentation and random noise levels', 'test the AbstractLowScaleModel register_schedule method to set up beta schedules and diffusion buffers', 'test the q_sample method to add noise to images at specified timesteps', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt methods', 'build DDIM timestep discretization for faster diffusion sampling using uniform or quad methods', 'compute DDIM sampling parameters including sigmas and alphas for a given eta value', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension', 'run gradient checkpointing on a function to reduce memory usage at the cost of extra compute']
```

Usage

```
{'build_UNetModel': 'build a UNetModel with configurable attention, timestep embedding, and spatial transformer support for diffusion', 'create_ResBlock': 'create a ResBlock with optional channel change, upsampling, downsampling, and scale shift norm', 'create_AttentionBlock': 'create an AttentionBlock with configurable heads and QKV attention for spatial self-attention', 'create_TimestepEmbedSequential': 'create a TimestepEmbedSequential that routes timestep embeddings to child TimestepBlock layers', 'create_QKVAttention': 'create a QKVAttention module that performs multi-head attention on query key value tensors'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/diffusionmodules/upscaling.py

Prompts

```
['build a U-Net denoiser model with timestep embeddings and attention for diffusion', 'build an encoder to downsample images into a latent representation with resnet blocks', 'build a decoder to upsample latent representations back to image space with attention', 'create a self-attention block with optional xformers memory-efficient implementation', 'create a residual block with group normalization and timestep embedding projection', 'build a UNetModel with configurable attention, timestep embedding, and spatial transformer support for diffusion', 'create a ResBlock with optional channel change, upsampling, downsampling, and scale shift norm', 'create an AttentionBlock with configurable heads and QKV attention for spatial self-attention', 'create a TimestepEmbedSequential that routes timestep embeddings to child TimestepBlock layers', 'create a QKVAttention module that performs multi-head attention on query key value tensors', 'build a low scale model that registers diffusion noise schedules and buffers for image upscaling', 'build a simple image concatenation model that returns input with zero noise levels', 'build an image concatenation model with configurable noise augmentation and random noise levels', 'test the AbstractLowScaleModel register_schedule method to set up beta schedules and diffusion buffers', 'test the q_sample method to add noise to images at specified timesteps', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt methods', 'build DDIM timestep discretization for faster diffusion sampling using uniform or quad methods', 'compute DDIM sampling parameters including sigmas and alphas for a given eta value', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension', 'run gradient checkpointing on a function to reduce memory usage at the cost of extra compute']
```

Usage

```
{'build_AbstractLowScaleModel': 'build a low scale model that registers diffusion noise schedules and buffers for image upscaling', 'build_SimpleImageConcat': 'build a simple image concatenation model that returns input with zero noise levels', 'build_ImageConcatWithNoiseAugmentation': 'build an image concatenation model with configurable noise augmentation and random noise levels', 'test_register_schedule': 'test the AbstractLowScaleModel register_schedule method to set up beta schedules and diffusion buffers', 'test_q_sample': 'test the q_sample method to add noise to images at specified timesteps'}
```

## File: facebookresearch_stablesignature/src/ldm/modules/diffusionmodules/util.py

Prompts

```
['build a U-Net denoiser model with timestep embeddings and attention for diffusion', 'build an encoder to downsample images into a latent representation with resnet blocks', 'build a decoder to upsample latent representations back to image space with attention', 'create a self-attention block with optional xformers memory-efficient implementation', 'create a residual block with group normalization and timestep embedding projection', 'build a UNetModel with configurable attention, timestep embedding, and spatial transformer support for diffusion', 'create a ResBlock with optional channel change, upsampling, downsampling, and scale shift norm', 'create an AttentionBlock with configurable heads and QKV attention for spatial self-attention', 'create a TimestepEmbedSequential that routes timestep embeddings to child TimestepBlock layers', 'create a QKVAttention module that performs multi-head attention on query key value tensors', 'build a low scale model that registers diffusion noise schedules and buffers for image upscaling', 'build a simple image concatenation model that returns input with zero noise levels', 'build an image concatenation model with configurable noise augmentation and random noise levels', 'test the AbstractLowScaleModel register_schedule method to set up beta schedules and diffusion buffers', 'test the q_sample method to add noise to images at specified timesteps', 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt methods', 'build DDIM timestep discretization for faster diffusion sampling using uniform or quad methods', 'compute DDIM sampling parameters including sigmas and alphas for a given eta value', 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension', 'run gradient checkpointing on a function to reduce memory usage at the cost of extra compute']
```

Usage

```
{'make_beta_schedule': 'create a beta noise schedule for diffusion models using linear, cosine, sqrt_linear, or sqrt methods', 'make_ddim_timesteps': 'build DDIM timestep discretization for faster diffusion sampling using uniform or quad methods', 'make_ddim_sampling_parameters': 'compute DDIM sampling parameters including sigmas and alphas for a given eta value', 'timestep_embedding': 'create sinusoidal timestep embeddings for diffusion model input conditioning with configurable dimension', 'checkpoint': 'run gradient checkpointing on a function to reduce memory usage at the cost of extra compute'}
```

