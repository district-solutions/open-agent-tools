# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/qwen3_vl_moe/modeling_qwen3_vl_moe.py

Prompts

```
['create a Qwen3-VL-MoE multimodal model with vision and text encoders for conditional generation', 'run autoregressive text generation on Qwen3-VL-MoE with image or video inputs and beam search', 'build a forward pass through Qwen3-VL-MoE that processes images, videos, and text with 3D RoPE position encoding', 'test the 3D multi-modal RoPE position index computation for image and video token grids', 'review the sparse Mixture-of-Experts routing with top-k expert selection and load balancing loss', 'create a Qwen3-VL-MOE conditional generation model for multimodal image and video understanding', 'run the Qwen3-VL-MOE text decoder forward pass with position embeddings and deepstack visual features', 'build a sparse mixture-of-experts block with top-k routing for the Qwen3-VL-MOE text layers', 'test the top-k expert router that computes softmax probabilities and selects top experts per token', 'summarize the vision encoder model that processes image and video pixel inputs for multimodal fusion']
```

Usage

```
{'create_qwen3vlmoe_model': 'create a Qwen3-VL-MoE multimodal model with vision and text encoders for conditional generation', 'run_qwen3vlmoe_generation': 'run autoregressive text generation on Qwen3-VL-MoE with image or video inputs and beam search', 'build_qwen3vlmoe_forward_pass': 'build a forward pass through Qwen3-VL-MoE that processes images, videos, and text with 3D RoPE position encoding', 'test_qwen3vlmoe_mrope_index': 'test the 3D multi-modal RoPE position index computation for image and video token grids', 'review_qwen3vlmoe_sparse_moe': 'review the sparse Mixture-of-Experts routing with top-k expert selection and load balancing loss'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_vl_moe/modular_qwen3_vl_moe.py

Prompts

```
['create a Qwen3-VL-MoE multimodal model with vision and text encoders for conditional generation', 'run autoregressive text generation on Qwen3-VL-MoE with image or video inputs and beam search', 'build a forward pass through Qwen3-VL-MoE that processes images, videos, and text with 3D RoPE position encoding', 'test the 3D multi-modal RoPE position index computation for image and video token grids', 'review the sparse Mixture-of-Experts routing with top-k expert selection and load balancing loss', 'create a Qwen3-VL-MOE conditional generation model for multimodal image and video understanding', 'run the Qwen3-VL-MOE text decoder forward pass with position embeddings and deepstack visual features', 'build a sparse mixture-of-experts block with top-k routing for the Qwen3-VL-MOE text layers', 'test the top-k expert router that computes softmax probabilities and selects top experts per token', 'summarize the vision encoder model that processes image and video pixel inputs for multimodal fusion']
```

Usage

```
{'create_Qwen3VLMoeForConditionalGeneration': 'create a Qwen3-VL-MOE conditional generation model for multimodal image and video understanding', 'run_Qwen3VLMoeTextModel_forward': 'run the Qwen3-VL-MOE text decoder forward pass with position embeddings and deepstack visual features', 'build_Qwen3VLMoeTextSparseMoeBlock': 'build a sparse mixture-of-experts block with top-k routing for the Qwen3-VL-MOE text layers', 'test_Qwen3VLMoeTextTopKRouter': 'test the top-k expert router that computes softmax probabilities and selects top experts per token', 'summarize_Qwen3VLMoeVisionModel': 'summarize the vision encoder model that processes image and video pixel inputs for multimodal fusion'}
```

