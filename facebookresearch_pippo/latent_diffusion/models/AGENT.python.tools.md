# Agent Python Tools

- repo: facebookresearch/pippo
- repo_uri: https://github.com/facebookresearch/pippo

## File: facebookresearch_pippo/latent_diffusion/models/control_mlp.py

Prompts

```
['build a ControlMLP module with ControlEncoder and ZeroControlBlocks for DiT-style control conditioning', 'create a ControlEncoder that downsamples dense control signals 16x through conv blocks', 'create a ControlEncoderLatent that encodes control signals without a hidden size bottleneck', 'test the ZeroControlBlock forward pass with modulated hidden states and timestep conditioning', 'review the modulate function that applies AdaLN-style shift and scale to input tensors', 'build a Diffusion Transformer model with configurable depth, dimension, and number of heads for image generation', 'create a DiTBlock with self-attention, cross-attention conditioning, and AdaLN modulation for transformer layers', 'run a forward pass through DiT with spatial inputs, timesteps, and optional conditioning tensors', 'refactor DiT to switch between sincos, learnable, or old positional encoding schemes via pos_embed_kind', 'review the modulate function and DiTBlock forward pass for attention biasing and multi-view token handling', 'build a Pippo multiview diffusion transformer model with configurable compressor, generator, schedule, and conditioning encoders', 'run the Pippo forward pass with image, keypoints, reference image, camera poses, and plucker coordinates for training', 'create a RefEncoder module to encode reference images with patchify and 2D sinusoidal positional embeddings', 'test the Pippo encode_image and decode_image methods to verify VAE compression and reconstruction', 'review the Pippo get_conds method to understand how reference image, camera pose, plucker, and keypoints conditioning are assembled']
```

Usage

```
{'build_ControlMLP': 'build a ControlMLP module with ControlEncoder and ZeroControlBlocks for DiT-style control conditioning', 'create_ControlEncoder': 'create a ControlEncoder that downsamples dense control signals 16x through conv blocks', 'create_ControlEncoderLatent': 'create a ControlEncoderLatent that encodes control signals without a hidden size bottleneck', 'test_ZeroControlBlock': 'test the ZeroControlBlock forward pass with modulated hidden states and timestep conditioning', 'review_modulate': 'review the modulate function that applies AdaLN-style shift and scale to input tensors'}
```

## File: facebookresearch_pippo/latent_diffusion/models/dit.py

Prompts

```
['build a ControlMLP module with ControlEncoder and ZeroControlBlocks for DiT-style control conditioning', 'create a ControlEncoder that downsamples dense control signals 16x through conv blocks', 'create a ControlEncoderLatent that encodes control signals without a hidden size bottleneck', 'test the ZeroControlBlock forward pass with modulated hidden states and timestep conditioning', 'review the modulate function that applies AdaLN-style shift and scale to input tensors', 'build a Diffusion Transformer model with configurable depth, dimension, and number of heads for image generation', 'create a DiTBlock with self-attention, cross-attention conditioning, and AdaLN modulation for transformer layers', 'run a forward pass through DiT with spatial inputs, timesteps, and optional conditioning tensors', 'refactor DiT to switch between sincos, learnable, or old positional encoding schemes via pos_embed_kind', 'review the modulate function and DiTBlock forward pass for attention biasing and multi-view token handling', 'build a Pippo multiview diffusion transformer model with configurable compressor, generator, schedule, and conditioning encoders', 'run the Pippo forward pass with image, keypoints, reference image, camera poses, and plucker coordinates for training', 'create a RefEncoder module to encode reference images with patchify and 2D sinusoidal positional embeddings', 'test the Pippo encode_image and decode_image methods to verify VAE compression and reconstruction', 'review the Pippo get_conds method to understand how reference image, camera pose, plucker, and keypoints conditioning are assembled']
```

Usage

```
{'build_DiT_model': 'build a Diffusion Transformer model with configurable depth, dimension, and number of heads for image generation', 'create_DiTBlock': 'create a DiTBlock with self-attention, cross-attention conditioning, and AdaLN modulation for transformer layers', 'run_DiT_forward_pass': 'run a forward pass through DiT with spatial inputs, timesteps, and optional conditioning tensors', 'refactor_DiT_positional_encoding': 'refactor DiT to switch between sincos, learnable, or old positional encoding schemes via pos_embed_kind', 'review_DiTBlock_modulate': 'review the modulate function and DiTBlock forward pass for attention biasing and multi-view token handling'}
```

## File: facebookresearch_pippo/latent_diffusion/models/pippo.py

Prompts

```
['build a ControlMLP module with ControlEncoder and ZeroControlBlocks for DiT-style control conditioning', 'create a ControlEncoder that downsamples dense control signals 16x through conv blocks', 'create a ControlEncoderLatent that encodes control signals without a hidden size bottleneck', 'test the ZeroControlBlock forward pass with modulated hidden states and timestep conditioning', 'review the modulate function that applies AdaLN-style shift and scale to input tensors', 'build a Diffusion Transformer model with configurable depth, dimension, and number of heads for image generation', 'create a DiTBlock with self-attention, cross-attention conditioning, and AdaLN modulation for transformer layers', 'run a forward pass through DiT with spatial inputs, timesteps, and optional conditioning tensors', 'refactor DiT to switch between sincos, learnable, or old positional encoding schemes via pos_embed_kind', 'review the modulate function and DiTBlock forward pass for attention biasing and multi-view token handling', 'build a Pippo multiview diffusion transformer model with configurable compressor, generator, schedule, and conditioning encoders', 'run the Pippo forward pass with image, keypoints, reference image, camera poses, and plucker coordinates for training', 'create a RefEncoder module to encode reference images with patchify and 2D sinusoidal positional embeddings', 'test the Pippo encode_image and decode_image methods to verify VAE compression and reconstruction', 'review the Pippo get_conds method to understand how reference image, camera pose, plucker, and keypoints conditioning are assembled']
```

Usage

```
{'build_Pippo_multiview_diffusion_model': 'build a Pippo multiview diffusion transformer model with configurable compressor, generator, schedule, and conditioning encoders', 'run_Pippo_forward': 'run the Pippo forward pass with image, keypoints, reference image, camera poses, and plucker coordinates for training', 'create_RefEncoder': 'create a RefEncoder module to encode reference images with patchify and 2D sinusoidal positional embeddings', 'test_Pippo_encode_decode': 'test the Pippo encode_image and decode_image methods to verify VAE compression and reconstruction', 'review_Pippo_get_conds': 'review the Pippo get_conds method to understand how reference image, camera pose, plucker, and keypoints conditioning are assembled'}
```

