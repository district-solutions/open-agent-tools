# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/vaes/parallel/wan_common_utils.py

Prompts

```
['create a 3D average downsampling module that reduces spatial and temporal dimensions with configurable channel mapping', 'create a 3D duplication upsampling module that expands spatial and temporal dimensions with channel expansion', 'create a 3D causal convolution layer with feature caching for efficient autoregressive inference', 'create an RMS normalization layer with configurable channel-first layout and learnable scale bias', 'run 3D resampling with caching support for upsample3d and downsample3d modes in autoregressive generation', 'build a halo exchange function for sequence-parallel convolution with P2P neighbor communication', 'create a sequence-parallel 2D convolution class with halo exchange for height-distributed tensors', 'create a sequence-parallel causal 3D convolution class with halo exchange and cache support', 'create a causal self-attention block with all-gather and chunk for sequence-parallel execution', 'create a sequence-parallel residual block with causal 3D convolutions and RMS normalization']
```

Usage

```
{'create_AvgDown3D': 'create a 3D average downsampling module that reduces spatial and temporal dimensions with configurable channel mapping', 'create_DupUp3D': 'create a 3D duplication upsampling module that expands spatial and temporal dimensions with channel expansion', 'create_WanCausalConv3d': 'create a 3D causal convolution layer with feature caching for efficient autoregressive inference', 'create_WanRMS_norm': 'create an RMS normalization layer with configurable channel-first layout and learnable scale bias', 'run_resample_forward': 'run 3D resampling with caching support for upsample3d and downsample3d modes in autoregressive generation'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/vaes/parallel/wan_dist_utils.py

Prompts

```
['create a 3D average downsampling module that reduces spatial and temporal dimensions with configurable channel mapping', 'create a 3D duplication upsampling module that expands spatial and temporal dimensions with channel expansion', 'create a 3D causal convolution layer with feature caching for efficient autoregressive inference', 'create an RMS normalization layer with configurable channel-first layout and learnable scale bias', 'run 3D resampling with caching support for upsample3d and downsample3d modes in autoregressive generation', 'build a halo exchange function for sequence-parallel convolution with P2P neighbor communication', 'create a sequence-parallel 2D convolution class with halo exchange for height-distributed tensors', 'create a sequence-parallel causal 3D convolution class with halo exchange and cache support', 'create a causal self-attention block with all-gather and chunk for sequence-parallel execution', 'create a sequence-parallel residual block with causal 3D convolutions and RMS normalization']
```

Usage

```
{'build_halo_exchange': 'build a halo exchange function for sequence-parallel convolution with P2P neighbor communication', 'create_WanDistConv2d': 'create a sequence-parallel 2D convolution class with halo exchange for height-distributed tensors', 'create_WanDistCausalConv3d': 'create a sequence-parallel causal 3D convolution class with halo exchange and cache support', 'create_WanDistAttentionBlock': 'create a causal self-attention block with all-gather and chunk for sequence-parallel execution', 'create_WanDistResidualBlock': 'create a sequence-parallel residual block with causal 3D convolutions and RMS normalization'}
```

