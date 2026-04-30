# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/modules/deepseek_v2_attention_mla_npu.py

Prompts

```
['run MHA prepare for DeepSeek V2 attention on NPU with positions, hidden states, and forward batch', 'run MHA core attention computation on NPU with precomputed q, k, v tensors and forward batch', 'run MLA prepare for DeepSeek V2 attention on NPU with fused preprocess and rotary embeddings', 'run MLA core attention on NPU with q_pe, k_pe, q_nope_out, k_nope tensors and topk indices', 'run DSA prepare for DeepSeek V2 attention on NPU with alt stream overlap and topk indexing', 'run DSA core attention on NPU with topk indices and conditional w_vc matmul for extend mode', 'run NPU MLA preprocess helper with NPUFusedMLAPreprocess and optional q_lora extraction for decode mode', 'build a function that flattens image or video patches into a 2D tensor for NPU processing', 'create a wrapper that preprocesses Qwen2VL image tensors with NPU-optimized patch flattening', 'create a wrapper that preprocesses Qwen3VL video tensors with NPU-optimized patch flattening', 'run the patch function to apply NPU-optimized preprocessing to Qwen2VL and Qwen3VL transformers', 'test the transform_patches_to_flatten function with batched image tensor inputs and grid dimensions']
```

Usage

```
{'run_forward_mha_prepare_npu': 'run MHA prepare for DeepSeek V2 attention on NPU with positions, hidden states, and forward batch', 'run_forward_mha_core_npu': 'run MHA core attention computation on NPU with precomputed q, k, v tensors and forward batch', 'run_forward_mla_prepare_npu': 'run MLA prepare for DeepSeek V2 attention on NPU with fused preprocess and rotary embeddings', 'run_forward_mla_core_npu': 'run MLA core attention on NPU with q_pe, k_pe, q_nope_out, k_nope tensors and topk indices', 'run_forward_dsa_prepare_npu': 'run DSA prepare for DeepSeek V2 attention on NPU with alt stream overlap and topk indexing', 'run_forward_dsa_core_npu': 'run DSA core attention on NPU with topk indices and conditional w_vc matmul for extend mode', 'run_npu_mla_preprocess': 'run NPU MLA preprocess helper with NPUFusedMLAPreprocess and optional q_lora extraction for decode mode'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/modules/qwen_vl_processor.py

Prompts

```
['run MHA prepare for DeepSeek V2 attention on NPU with positions, hidden states, and forward batch', 'run MHA core attention computation on NPU with precomputed q, k, v tensors and forward batch', 'run MLA prepare for DeepSeek V2 attention on NPU with fused preprocess and rotary embeddings', 'run MLA core attention on NPU with q_pe, k_pe, q_nope_out, k_nope tensors and topk indices', 'run DSA prepare for DeepSeek V2 attention on NPU with alt stream overlap and topk indexing', 'run DSA core attention on NPU with topk indices and conditional w_vc matmul for extend mode', 'run NPU MLA preprocess helper with NPUFusedMLAPreprocess and optional q_lora extraction for decode mode', 'build a function that flattens image or video patches into a 2D tensor for NPU processing', 'create a wrapper that preprocesses Qwen2VL image tensors with NPU-optimized patch flattening', 'create a wrapper that preprocesses Qwen3VL video tensors with NPU-optimized patch flattening', 'run the patch function to apply NPU-optimized preprocessing to Qwen2VL and Qwen3VL transformers', 'test the transform_patches_to_flatten function with batched image tensor inputs and grid dimensions']
```

Usage

```
{'build_transform_patches_to_flatten': 'build a function that flattens image or video patches into a 2D tensor for NPU processing', 'create_npu_wrapper_preprocess': 'create a wrapper that preprocesses Qwen2VL image tensors with NPU-optimized patch flattening', 'create_npu_wrapper_video_preprocess': 'create a wrapper that preprocesses Qwen3VL video tensors with NPU-optimized patch flattening', 'run_npu_apply_qwen_image_preprocess_patch': 'run the patch function to apply NPU-optimized preprocessing to Qwen2VL and Qwen3VL transformers', 'test_transform_patches_to_flatten': 'test the transform_patches_to_flatten function with batched image tensor inputs and grid dimensions'}
```

