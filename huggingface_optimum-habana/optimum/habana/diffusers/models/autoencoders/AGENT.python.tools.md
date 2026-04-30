# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/models/autoencoders/autoencoder_kl_cogvideox.py

Prompts

```
['decode a batch of latent vectors into video frames using a tiled VAE decoder optimized for Gaudi', 'run the Gaudi pipelined tiled decode on latent tensors to reconstruct video samples with reduced memory', 'forward pass through a CogVideoX causal 3D convolution layer with conv cache reuse on Gaudi', 'optimize the CogVideoX causal conv3d forward pass by using copy_ instead of clone for the conv cache', 'review the tiled_decode_gaudi function for memory-efficient video decoding using overlapping tiles and blending', 'optimize the WanAvgDown3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'optimize the WanDupUp3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'add htcore mark_step calls to WanDecoder3dForwardGaudi for memory optimization on Habana Gaudi accelerators', 'add htcore mark_step calls to WanEncoder3dForwardGaudi to reduce graph build time in lazy mode', 'implement feature caching with CACHE_T temporal frames for chunked video encoding and decoding in Wan autoencoder']
```

Usage

```
{'tiled_decode_gaudi': 'decode a batch of latent vectors into video frames using a tiled VAE decoder optimized for Gaudi', 'run_tiled_decode': 'run the Gaudi pipelined tiled decode on latent tensors to reconstruct video samples with reduced memory', 'CogVideoXCausalConv3dforwardGaudi': 'forward pass through a CogVideoX causal 3D convolution layer with conv cache reuse on Gaudi', 'optimize_conv_cache': 'optimize the CogVideoX causal conv3d forward pass by using copy_ instead of clone for the conv cache', 'review_tiled_decode': 'review the tiled_decode_gaudi function for memory-efficient video decoding using overlapping tiles and blending'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/models/autoencoders/autoencoder_kl_wan.py

Prompts

```
['decode a batch of latent vectors into video frames using a tiled VAE decoder optimized for Gaudi', 'run the Gaudi pipelined tiled decode on latent tensors to reconstruct video samples with reduced memory', 'forward pass through a CogVideoX causal 3D convolution layer with conv cache reuse on Gaudi', 'optimize the CogVideoX causal conv3d forward pass by using copy_ instead of clone for the conv cache', 'review the tiled_decode_gaudi function for memory-efficient video decoding using overlapping tiles and blending', 'optimize the WanAvgDown3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'optimize the WanDupUp3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'add htcore mark_step calls to WanDecoder3dForwardGaudi for memory optimization on Habana Gaudi accelerators', 'add htcore mark_step calls to WanEncoder3dForwardGaudi to reduce graph build time in lazy mode', 'implement feature caching with CACHE_T temporal frames for chunked video encoding and decoding in Wan autoencoder']
```

Usage

```
{'optimize_WanAvgDown3DForwardGaudi': 'optimize the WanAvgDown3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'optimize_WanDupUp3DForwardGaudi': 'optimize the WanDupUp3DForwardGaudi function to fix G3 graph compiler issues using transpose instead of permute', 'add_mark_step_WanDecoder3dForwardGaudi': 'add htcore mark_step calls to WanDecoder3dForwardGaudi for memory optimization on Habana Gaudi accelerators', 'add_mark_step_WanEncoder3dForwardGaudi': 'add htcore mark_step calls to WanEncoder3dForwardGaudi to reduce graph build time in lazy mode', 'implement_feat_cache_autoencoder_kl_wan': 'implement feature caching with CACHE_T temporal frames for chunked video encoding and decoding in Wan autoencoder'}
```

