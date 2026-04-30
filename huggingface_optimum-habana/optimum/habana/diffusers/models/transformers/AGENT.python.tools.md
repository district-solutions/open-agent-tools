# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/models/transformers/cogvideox_transformer_3d.py

Prompts

```
['run the cogvideoXTransformerForwardGaudi forward pass on a CogVideoX 3D transformer model with Habana Gaudi acceleration', 'review the cogvideoXTransformerForwardGaudi function to understand how htcore.mark_step is inserted between transformer blocks for Gaudi graph optimization', 'refactor the cogvideoXTransformerForwardGaudi function to support a new CogVideoX model variant with different patch sizes', 'summarize the cogvideoXTransformerForwardGaudi function and its handling of time embeddings, patch embedding, and unpatchify for CogVideoX-2B and CogVideoX-5B', 'test the cogvideoXTransformerForwardGaudi function with gradient checkpointing enabled and disabled to verify correct output shapes', 'create sinusoidal timestep embeddings for diffusion models using get_timestep_embedding with configurable scale and period', 'apply rotary position embeddings to query or key tensors using apply_rotary_emb_qwen with cos and sin frequencies', 'build a GaudiQwenTimestepProjEmbeddings module to project timesteps into embedding space for the Qwen image transformer', 'compute 3D rotary position embeddings for video frames using GaudiQwenEmbedRope with frame height and width dimensions', 'run joint text-image attention using GaudiQwenDoubleStreamAttnProcessor2_0 to process image and text streams together']
```

Usage

```
{'run_cogvideox_forward_gaudi': 'run the cogvideoXTransformerForwardGaudi forward pass on a CogVideoX 3D transformer model with Habana Gaudi acceleration', 'review_cogvideox_forward_gaudi': 'review the cogvideoXTransformerForwardGaudi function to understand how htcore.mark_step is inserted between transformer blocks for Gaudi graph optimization', 'refactor_cogvideox_forward_gaudi': 'refactor the cogvideoXTransformerForwardGaudi function to support a new CogVideoX model variant with different patch sizes', 'summarize_cogvideox_forward_gaudi': 'summarize the cogvideoXTransformerForwardGaudi function and its handling of time embeddings, patch embedding, and unpatchify for CogVideoX-2B and CogVideoX-5B', 'test_cogvideox_forward_gaudi': 'test the cogvideoXTransformerForwardGaudi function with gradient checkpointing enabled and disabled to verify correct output shapes'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/models/transformers/transformer_qwenimage.py

Prompts

```
['run the cogvideoXTransformerForwardGaudi forward pass on a CogVideoX 3D transformer model with Habana Gaudi acceleration', 'review the cogvideoXTransformerForwardGaudi function to understand how htcore.mark_step is inserted between transformer blocks for Gaudi graph optimization', 'refactor the cogvideoXTransformerForwardGaudi function to support a new CogVideoX model variant with different patch sizes', 'summarize the cogvideoXTransformerForwardGaudi function and its handling of time embeddings, patch embedding, and unpatchify for CogVideoX-2B and CogVideoX-5B', 'test the cogvideoXTransformerForwardGaudi function with gradient checkpointing enabled and disabled to verify correct output shapes', 'create sinusoidal timestep embeddings for diffusion models using get_timestep_embedding with configurable scale and period', 'apply rotary position embeddings to query or key tensors using apply_rotary_emb_qwen with cos and sin frequencies', 'build a GaudiQwenTimestepProjEmbeddings module to project timesteps into embedding space for the Qwen image transformer', 'compute 3D rotary position embeddings for video frames using GaudiQwenEmbedRope with frame height and width dimensions', 'run joint text-image attention using GaudiQwenDoubleStreamAttnProcessor2_0 to process image and text streams together']
```

Usage

```
{'create_timestep_embeddings': 'create sinusoidal timestep embeddings for diffusion models using get_timestep_embedding with configurable scale and period', 'apply_rotary_embeddings': 'apply rotary position embeddings to query or key tensors using apply_rotary_emb_qwen with cos and sin frequencies', 'build_timestep_proj_module': 'build a GaudiQwenTimestepProjEmbeddings module to project timesteps into embedding space for the Qwen image transformer', 'compute_video_rope_embeddings': 'compute 3D rotary position embeddings for video frames using GaudiQwenEmbedRope with frame height and width dimensions', 'run_double_stream_attention': 'run joint text-image attention using GaudiQwenDoubleStreamAttnProcessor2_0 to process image and text streams together'}
```

