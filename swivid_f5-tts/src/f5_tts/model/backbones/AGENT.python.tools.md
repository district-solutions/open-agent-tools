# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/model/backbones/dit.py

Prompts

```
['create a DiT model with configurable depth, heads, and text embedding for audio generation', 'build a TextEmbedding module with positional encoding and optional ConvNeXtV2 blocks for text processing', 'configure DiT for classifier-free guidance inference by packing conditional and unconditional branches', 'cache text conditional and unconditional embeddings in DiT for repeated inference without recomputation', 'apply InputEmbedding to combine noised audio, conditioning audio, and text embeddings with position encoding', 'create an MMDiT transformer model with configurable depth, heads, and dimension for audio generation', 'create an AudioEmbedding module that concatenates noised audio and conditioned audio with convolutional position embedding', 'run an MMDiT forward pass with noisy audio, masked condition, text tokens, and timestep for diffusion inference', 'test MMDiT caching of text condition and uncondition embeddings via thread-local storage for inference reuse', 'create a UNetT transformer model with specified dimensions, depth, and skip connection type', 'create an InputEmbedding module that concatenates noised audio, conditioning audio, and text embeddings into a unified representation', 'run the UNetT forward pass with noisy audio, masked conditioning audio, text tokens, and timestep for diffusion denoising', 'test UNetT classifier-free guidance inference by packing conditioned and unconditioned inputs for parallel forward pass']
```

Usage

```
{'create_dit_model': 'create a DiT model with configurable depth, heads, and text embedding for audio generation', 'build_text_embedding': 'build a TextEmbedding module with positional encoding and optional ConvNeXtV2 blocks for text processing', 'configure_cfg_inference': 'configure DiT for classifier-free guidance inference by packing conditional and unconditional branches', 'cache_text_embeddings': 'cache text conditional and unconditional embeddings in DiT for repeated inference without recomputation', 'apply_input_embedding': 'apply InputEmbedding to combine noised audio, conditioning audio, and text embeddings with position encoding'}
```

## File: swivid_f5-tts/src/f5_tts/model/backbones/mmdit.py

Prompts

```
['create a DiT model with configurable depth, heads, and text embedding for audio generation', 'build a TextEmbedding module with positional encoding and optional ConvNeXtV2 blocks for text processing', 'configure DiT for classifier-free guidance inference by packing conditional and unconditional branches', 'cache text conditional and unconditional embeddings in DiT for repeated inference without recomputation', 'apply InputEmbedding to combine noised audio, conditioning audio, and text embeddings with position encoding', 'create an MMDiT transformer model with configurable depth, heads, and dimension for audio generation', 'create an AudioEmbedding module that concatenates noised audio and conditioned audio with convolutional position embedding', 'run an MMDiT forward pass with noisy audio, masked condition, text tokens, and timestep for diffusion inference', 'test MMDiT caching of text condition and uncondition embeddings via thread-local storage for inference reuse', 'create a UNetT transformer model with specified dimensions, depth, and skip connection type', 'create an InputEmbedding module that concatenates noised audio, conditioning audio, and text embeddings into a unified representation', 'run the UNetT forward pass with noisy audio, masked conditioning audio, text tokens, and timestep for diffusion denoising', 'test UNetT classifier-free guidance inference by packing conditioned and unconditioned inputs for parallel forward pass']
```

Usage

```
{'create_mmdit_model': 'create an MMDiT transformer model with configurable depth, heads, and dimension for audio generation', 'build_text_embedding': 'build a TextEmbedding module that converts token sequences into dimensioned embeddings with sinusoidal position encoding', 'create_audio_embedding': 'create an AudioEmbedding module that concatenates noised audio and conditioned audio with convolutional position embedding', 'run_mmdit_forward': 'run an MMDiT forward pass with noisy audio, masked condition, text tokens, and timestep for diffusion inference', 'test_mmdit_cache': 'test MMDiT caching of text condition and uncondition embeddings via thread-local storage for inference reuse'}
```

## File: swivid_f5-tts/src/f5_tts/model/backbones/unett.py

Prompts

```
['create a DiT model with configurable depth, heads, and text embedding for audio generation', 'build a TextEmbedding module with positional encoding and optional ConvNeXtV2 blocks for text processing', 'configure DiT for classifier-free guidance inference by packing conditional and unconditional branches', 'cache text conditional and unconditional embeddings in DiT for repeated inference without recomputation', 'apply InputEmbedding to combine noised audio, conditioning audio, and text embeddings with position encoding', 'create an MMDiT transformer model with configurable depth, heads, and dimension for audio generation', 'create an AudioEmbedding module that concatenates noised audio and conditioned audio with convolutional position embedding', 'run an MMDiT forward pass with noisy audio, masked condition, text tokens, and timestep for diffusion inference', 'test MMDiT caching of text condition and uncondition embeddings via thread-local storage for inference reuse', 'create a UNetT transformer model with specified dimensions, depth, and skip connection type', 'create an InputEmbedding module that concatenates noised audio, conditioning audio, and text embeddings into a unified representation', 'run the UNetT forward pass with noisy audio, masked conditioning audio, text tokens, and timestep for diffusion denoising', 'test UNetT classifier-free guidance inference by packing conditioned and unconditioned inputs for parallel forward pass']
```

Usage

```
{'create_unett_model': 'create a UNetT transformer model with specified dimensions, depth, and skip connection type', 'build_text_embedding': 'build a TextEmbedding module that converts text token indices into contextual embeddings with optional convnextv2 blocks', 'create_input_embedding': 'create an InputEmbedding module that concatenates noised audio, conditioning audio, and text embeddings into a unified representation', 'run_unett_forward': 'run the UNetT forward pass with noisy audio, masked conditioning audio, text tokens, and timestep for diffusion denoising', 'test_cfg_inference': 'test UNetT classifier-free guidance inference by packing conditioned and unconditioned inputs for parallel forward pass'}
```

