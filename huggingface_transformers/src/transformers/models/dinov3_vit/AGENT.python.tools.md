# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dinov3_vit/convert_dinov3_vit_to_hf.py

Prompts

```
["convert a DINOv3 checkpoint from Facebook's repository to Hugging Face format", 'split concatenated QKV weight tensors into separate q_proj, k_proj, and v_proj tensors', 'rename original DINOv3 state dict keys to Hugging Face DINOv3ViT key names using regex mappings', 'get a DINOv3ViTConfig for a specified model variant like vits16, vitb16, vitl16, or vit7b16', 'test the converted model forward pass output against expected values for cls and patch tokens', 'create a DINOv3ViTModel for image feature extraction with configurable hidden size and attention heads', 'build a DINOv3ViTBackbone to extract multi-stage feature maps from input images', 'run a forward pass on DINOv3ViTModel to get pooled CLS output and last hidden state', 'test DINOv3ViTRopePositionEmbedding rotary position encoding with dynamic image sizes', 'review DINOv3ViTAttention multi-headed attention with rotary position embedding application', 'create a DINOv3ViTBackbone to extract multi-stage feature maps from image inputs', 'build a DINOv3ViTAttention module with rotary position embeddings for self-attention', 'build a DINOv3ViTLayer with attention, gated or standard MLP, and layer scale', 'test the apply_rotary_pos_emb function to rotate query and key patch tokens only']
```

Usage

```
{'convert_dinov3_checkpoint': "convert a DINOv3 checkpoint from Facebook's repository to Hugging Face format", 'split_qkv_weights': 'split concatenated QKV weight tensors into separate q_proj, k_proj, and v_proj tensors', 'rename_state_dict_keys': 'rename original DINOv3 state dict keys to Hugging Face DINOv3ViT key names using regex mappings', 'get_dinov3_config': 'get a DINOv3ViTConfig for a specified model variant like vits16, vitb16, vitl16, or vit7b16', 'test_converted_output': 'test the converted model forward pass output against expected values for cls and patch tokens'}
```

## File: huggingface_transformers/src/transformers/models/dinov3_vit/modeling_dinov3_vit.py

Prompts

```
["convert a DINOv3 checkpoint from Facebook's repository to Hugging Face format", 'split concatenated QKV weight tensors into separate q_proj, k_proj, and v_proj tensors', 'rename original DINOv3 state dict keys to Hugging Face DINOv3ViT key names using regex mappings', 'get a DINOv3ViTConfig for a specified model variant like vits16, vitb16, vitl16, or vit7b16', 'test the converted model forward pass output against expected values for cls and patch tokens', 'create a DINOv3ViTModel for image feature extraction with configurable hidden size and attention heads', 'build a DINOv3ViTBackbone to extract multi-stage feature maps from input images', 'run a forward pass on DINOv3ViTModel to get pooled CLS output and last hidden state', 'test DINOv3ViTRopePositionEmbedding rotary position encoding with dynamic image sizes', 'review DINOv3ViTAttention multi-headed attention with rotary position embedding application', 'create a DINOv3ViTBackbone to extract multi-stage feature maps from image inputs', 'build a DINOv3ViTAttention module with rotary position embeddings for self-attention', 'build a DINOv3ViTLayer with attention, gated or standard MLP, and layer scale', 'test the apply_rotary_pos_emb function to rotate query and key patch tokens only']
```

Usage

```
{'create_dinov3_vit_model': 'create a DINOv3ViTModel for image feature extraction with configurable hidden size and attention heads', 'build_dinov3_vit_backbone': 'build a DINOv3ViTBackbone to extract multi-stage feature maps from input images', 'run_dinov3_vit_forward': 'run a forward pass on DINOv3ViTModel to get pooled CLS output and last hidden state', 'test_rope_position_embedding': 'test DINOv3ViTRopePositionEmbedding rotary position encoding with dynamic image sizes', 'review_dinov3_vit_attention': 'review DINOv3ViTAttention multi-headed attention with rotary position embedding application'}
```

## File: huggingface_transformers/src/transformers/models/dinov3_vit/modular_dinov3_vit.py

Prompts

```
["convert a DINOv3 checkpoint from Facebook's repository to Hugging Face format", 'split concatenated QKV weight tensors into separate q_proj, k_proj, and v_proj tensors', 'rename original DINOv3 state dict keys to Hugging Face DINOv3ViT key names using regex mappings', 'get a DINOv3ViTConfig for a specified model variant like vits16, vitb16, vitl16, or vit7b16', 'test the converted model forward pass output against expected values for cls and patch tokens', 'create a DINOv3ViTModel for image feature extraction with configurable hidden size and attention heads', 'build a DINOv3ViTBackbone to extract multi-stage feature maps from input images', 'run a forward pass on DINOv3ViTModel to get pooled CLS output and last hidden state', 'test DINOv3ViTRopePositionEmbedding rotary position encoding with dynamic image sizes', 'review DINOv3ViTAttention multi-headed attention with rotary position embedding application', 'create a DINOv3ViTBackbone to extract multi-stage feature maps from image inputs', 'build a DINOv3ViTAttention module with rotary position embeddings for self-attention', 'build a DINOv3ViTLayer with attention, gated or standard MLP, and layer scale', 'test the apply_rotary_pos_emb function to rotate query and key patch tokens only']
```

Usage

```
{'create_dinov3_vit_model': 'create a DINOv3ViTModel with config and pixel values to get pooled hidden state outputs', 'create_dinov3_vit_backbone': 'create a DINOv3ViTBackbone to extract multi-stage feature maps from image inputs', 'build_dinov3_vit_attention': 'build a DINOv3ViTAttention module with rotary position embeddings for self-attention', 'build_dinov3_vit_layer': 'build a DINOv3ViTLayer with attention, gated or standard MLP, and layer scale', 'test_apply_rotary_pos_emb': 'test the apply_rotary_pos_emb function to rotate query and key patch tokens only'}
```

