# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/test/unit/manual/bench_patch_embed.py

Prompts

```
['run the Conv3d vs F.linear PatchEmbed benchmark with configurable warmup and iteration counts', 'create a Conv3d-based PatchEmbed module with configurable patch size, input channels, and embedding dimension', 'create a reshape + F.linear PatchEmbed module optimized for performance with configurable patch dimensions', 'bench the forward pass latency of a module using CUDA events with warmup and timed iterations', "copy weights and bias from a source Conv3d projection to a destination model's projection layer", 'test that the optimized PatchEmbed reshape+F.linear is equivalent to the Conv3d-based PatchEmbed3D', 'test the optimized PatchEmbed for Wan2.1/Wan2.2/CausalWan/Helios with patch_size (1,2,2) and flatten=False', 'test the optimized PatchEmbed for HunyuanVideo with patch_size [1,2,2] and flatten=True', 'test the optimized PatchEmbed without bias for both Wan and HunyuanVideo variants', 'test the optimized PatchEmbed with fp32, bf16, and fp16 weight and input dtypes']
```

Usage

```
{'run_bench_patch_embed': 'run the Conv3d vs F.linear PatchEmbed benchmark with configurable warmup and iteration counts', 'create_patch_embed_3d': 'create a Conv3d-based PatchEmbed module with configurable patch size, input channels, and embedding dimension', 'create_patch_embed': 'create a reshape + F.linear PatchEmbed module optimized for performance with configurable patch dimensions', 'bench_forward_latency': 'bench the forward pass latency of a module using CUDA events with warmup and timed iterations', 'copy_weights_between_models': "copy weights and bias from a source Conv3d projection to a destination model's projection layer"}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/test/unit/manual/test_patch_embed.py

Prompts

```
['run the Conv3d vs F.linear PatchEmbed benchmark with configurable warmup and iteration counts', 'create a Conv3d-based PatchEmbed module with configurable patch size, input channels, and embedding dimension', 'create a reshape + F.linear PatchEmbed module optimized for performance with configurable patch dimensions', 'bench the forward pass latency of a module using CUDA events with warmup and timed iterations', "copy weights and bias from a source Conv3d projection to a destination model's projection layer", 'test that the optimized PatchEmbed reshape+F.linear is equivalent to the Conv3d-based PatchEmbed3D', 'test the optimized PatchEmbed for Wan2.1/Wan2.2/CausalWan/Helios with patch_size (1,2,2) and flatten=False', 'test the optimized PatchEmbed for HunyuanVideo with patch_size [1,2,2] and flatten=True', 'test the optimized PatchEmbed without bias for both Wan and HunyuanVideo variants', 'test the optimized PatchEmbed with fp32, bf16, and fp16 weight and input dtypes']
```

Usage

```
{'test_patch_embed_equivalence': 'test that the optimized PatchEmbed reshape+F.linear is equivalent to the Conv3d-based PatchEmbed3D', 'test_wan_helios_patch_embed': 'test the optimized PatchEmbed for Wan2.1/Wan2.2/CausalWan/Helios with patch_size (1,2,2) and flatten=False', 'test_hunyuanvideo_patch_embed': 'test the optimized PatchEmbed for HunyuanVideo with patch_size [1,2,2] and flatten=True', 'test_patch_embed_no_bias': 'test the optimized PatchEmbed without bias for both Wan and HunyuanVideo variants', 'test_patch_embed_dtypes': 'test the optimized PatchEmbed with fp32, bf16, and fp16 weight and input dtypes'}
```

