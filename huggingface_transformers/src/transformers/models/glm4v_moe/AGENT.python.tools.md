# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm4v_moe/convert_glm4v_moe_mgt_weights_to_hf.py

Prompts

```
['convert Megatron GLM4V-MoE model weights to HuggingFace format with tensor parallel merging', 'parse command-line arguments for Megatron to HuggingFace model conversion script', 'save a complete state dict as sharded safetensors files with an index JSON', 'merge tensor-parallel QKV projection weights into a single concatenated tensor', 'split GLU gate and up projection weights from concatenated tensor pairs', 'build a GLM-4V-MoE model for multimodal image and video conditional text generation', 'create a GLM-4V-MoE model that combines vision encoder and MoE language model for multimodal understanding', 'run the GLM-4V-MoE vision model to extract image and video features using patch embeddings and spatial merging', 'test the GLM-4V-MoE text model with MoE decoder layers, rotary embeddings, and causal attention', 'summarize the MoE load balancing loss function that penalizes unbalanced expert routing in GLM-4V-MoE', 'create a Glm4vMoeConfig instance to configure the GLM-4.5V MoE multimodal model', 'build a Glm4vMoeTextModel with Glm4vMoeTextConfig for text-only transformer inference', 'run Glm4vMoeForConditionalGeneration with pixel values and input IDs for multimodal generation', 'test Glm4vMoeTextAttention forward pass with hidden states and position embeddings', 'review Glm4vMoeTextMoE MoE layer with topk router and shared experts for expert routing']
```

Usage

```
{'merge_tp_weights': 'convert Megatron GLM4V-MoE model weights to HuggingFace format with tensor parallel merging', 'parse_args': 'parse command-line arguments for Megatron to HuggingFace model conversion script', 'save_sharded_model': 'save a complete state dict as sharded safetensors files with an index JSON', 'merge_qkv': 'merge tensor-parallel QKV projection weights into a single concatenated tensor', 'merge_glu_vit': 'split GLU gate and up projection weights from concatenated tensor pairs'}
```

## File: huggingface_transformers/src/transformers/models/glm4v_moe/modeling_glm4v_moe.py

Prompts

```
['convert Megatron GLM4V-MoE model weights to HuggingFace format with tensor parallel merging', 'parse command-line arguments for Megatron to HuggingFace model conversion script', 'save a complete state dict as sharded safetensors files with an index JSON', 'merge tensor-parallel QKV projection weights into a single concatenated tensor', 'split GLU gate and up projection weights from concatenated tensor pairs', 'build a GLM-4V-MoE model for multimodal image and video conditional text generation', 'create a GLM-4V-MoE model that combines vision encoder and MoE language model for multimodal understanding', 'run the GLM-4V-MoE vision model to extract image and video features using patch embeddings and spatial merging', 'test the GLM-4V-MoE text model with MoE decoder layers, rotary embeddings, and causal attention', 'summarize the MoE load balancing loss function that penalizes unbalanced expert routing in GLM-4V-MoE', 'create a Glm4vMoeConfig instance to configure the GLM-4.5V MoE multimodal model', 'build a Glm4vMoeTextModel with Glm4vMoeTextConfig for text-only transformer inference', 'run Glm4vMoeForConditionalGeneration with pixel values and input IDs for multimodal generation', 'test Glm4vMoeTextAttention forward pass with hidden states and position embeddings', 'review Glm4vMoeTextMoE MoE layer with topk router and shared experts for expert routing']
```

Usage

```
{'build_glm4v_moe_conditional_generation': 'build a GLM-4V-MoE model for multimodal image and video conditional text generation', 'create_glm4v_moe_multimodal_model': 'create a GLM-4V-MoE model that combines vision encoder and MoE language model for multimodal understanding', 'run_glm4v_moe_vision_features': 'run the GLM-4V-MoE vision model to extract image and video features using patch embeddings and spatial merging', 'test_glm4v_moe_text_model': 'test the GLM-4V-MoE text model with MoE decoder layers, rotary embeddings, and causal attention', 'summarize_load_balancing_loss': 'summarize the MoE load balancing loss function that penalizes unbalanced expert routing in GLM-4V-MoE'}
```

## File: huggingface_transformers/src/transformers/models/glm4v_moe/modular_glm4v_moe.py

Prompts

```
['convert Megatron GLM4V-MoE model weights to HuggingFace format with tensor parallel merging', 'parse command-line arguments for Megatron to HuggingFace model conversion script', 'save a complete state dict as sharded safetensors files with an index JSON', 'merge tensor-parallel QKV projection weights into a single concatenated tensor', 'split GLU gate and up projection weights from concatenated tensor pairs', 'build a GLM-4V-MoE model for multimodal image and video conditional text generation', 'create a GLM-4V-MoE model that combines vision encoder and MoE language model for multimodal understanding', 'run the GLM-4V-MoE vision model to extract image and video features using patch embeddings and spatial merging', 'test the GLM-4V-MoE text model with MoE decoder layers, rotary embeddings, and causal attention', 'summarize the MoE load balancing loss function that penalizes unbalanced expert routing in GLM-4V-MoE', 'create a Glm4vMoeConfig instance to configure the GLM-4.5V MoE multimodal model', 'build a Glm4vMoeTextModel with Glm4vMoeTextConfig for text-only transformer inference', 'run Glm4vMoeForConditionalGeneration with pixel values and input IDs for multimodal generation', 'test Glm4vMoeTextAttention forward pass with hidden states and position embeddings', 'review Glm4vMoeTextMoE MoE layer with topk router and shared experts for expert routing']
```

Usage

```
{'create_glm4v_moe_config': 'create a Glm4vMoeConfig instance to configure the GLM-4.5V MoE multimodal model', 'build_glm4v_moe_text_model': 'build a Glm4vMoeTextModel with Glm4vMoeTextConfig for text-only transformer inference', 'run_glm4v_moe_conditional_generation': 'run Glm4vMoeForConditionalGeneration with pixel values and input IDs for multimodal generation', 'test_glm4v_moe_text_attention': 'test Glm4vMoeTextAttention forward pass with hidden states and position embeddings', 'review_glm4v_moe_moe_layer': 'review Glm4vMoeTextMoE MoE layer with topk router and shared experts for expert routing'}
```

