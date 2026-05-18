# Agent Python Tools

- repo: facebookresearch/metaquery
- repo_uri: https://github.com/facebookresearch/metaquery

## File: facebookresearch_metaquery/models/metaquery.py

Prompts

```
['build a MetaQuery model from a MetaQueryConfig to generate images from text captions', 'create a MetaQueryConfig with custom vae_id, input_size, loss_type, and num_metaqueries parameters', 'run the MetaQuery forward pass with target images and input_ids to compute flow or diff loss', 'sample images from a text caption using MetaQuery sample_images with guidance scale and inference steps', 'decode latent tensors back to PIL images using MetaQuery decode_latents with normalization', 'build a MLLMInContext model from config to combine LLaVA or Qwen2.5-VL with Sana diffusion', 'create an MLLMInContextConfig with custom mllm_id, diffusion_model_id, and num_metaqueries parameters', 'run the tokenize static method to convert captions and images into tokenized inputs for the MLLM', 'run encode_condition to extract prompt embeddings from the MLLM backbone using input_ids and pixel values', 'run the forward pass through the SanaTransformer2DModel or UNet2DConditionModel with prompt embeddings and timestep', 'build a Qwen2Encoder transformer using a Qwen2Config to encode hidden states with bidirectional attention', 'create a Qwen2BidirectionalSdpaAttention module that performs non-causal SDPA attention with optional QK normalization', 'create a Qwen2EncoderLayer with pre-norm self-attention and MLP blocks using RMSNorm normalization', 'create a MultiHeadRMSNorm module that normalizes across the last dimension and scales by learnable gamma parameters', 'test the Qwen2Encoder forward pass by passing hidden states and verifying gradient checkpointing during training']
```

Usage

```
{'build_MetaQuery_model': 'build a MetaQuery model from a MetaQueryConfig to generate images from text captions', 'create_MetaQueryConfig': 'create a MetaQueryConfig with custom vae_id, input_size, loss_type, and num_metaqueries parameters', 'run_forward_training': 'run the MetaQuery forward pass with target images and input_ids to compute flow or diff loss', 'sample_images_from_caption': 'sample images from a text caption using MetaQuery sample_images with guidance scale and inference steps', 'decode_latents_to_images': 'decode latent tensors back to PIL images using MetaQuery decode_latents with normalization'}
```

## File: facebookresearch_metaquery/models/model.py

Prompts

```
['build a MetaQuery model from a MetaQueryConfig to generate images from text captions', 'create a MetaQueryConfig with custom vae_id, input_size, loss_type, and num_metaqueries parameters', 'run the MetaQuery forward pass with target images and input_ids to compute flow or diff loss', 'sample images from a text caption using MetaQuery sample_images with guidance scale and inference steps', 'decode latent tensors back to PIL images using MetaQuery decode_latents with normalization', 'build a MLLMInContext model from config to combine LLaVA or Qwen2.5-VL with Sana diffusion', 'create an MLLMInContextConfig with custom mllm_id, diffusion_model_id, and num_metaqueries parameters', 'run the tokenize static method to convert captions and images into tokenized inputs for the MLLM', 'run encode_condition to extract prompt embeddings from the MLLM backbone using input_ids and pixel values', 'run the forward pass through the SanaTransformer2DModel or UNet2DConditionModel with prompt embeddings and timestep', 'build a Qwen2Encoder transformer using a Qwen2Config to encode hidden states with bidirectional attention', 'create a Qwen2BidirectionalSdpaAttention module that performs non-causal SDPA attention with optional QK normalization', 'create a Qwen2EncoderLayer with pre-norm self-attention and MLP blocks using RMSNorm normalization', 'create a MultiHeadRMSNorm module that normalizes across the last dimension and scales by learnable gamma parameters', 'test the Qwen2Encoder forward pass by passing hidden states and verifying gradient checkpointing during training']
```

Usage

```
{'build_MLLMInContext_model': 'build a MLLMInContext model from config to combine LLaVA or Qwen2.5-VL with Sana diffusion', 'create_MLLMInContextConfig': 'create an MLLMInContextConfig with custom mllm_id, diffusion_model_id, and num_metaqueries parameters', 'run_tokenize': 'run the tokenize static method to convert captions and images into tokenized inputs for the MLLM', 'run_encode_condition': 'run encode_condition to extract prompt embeddings from the MLLM backbone using input_ids and pixel values', 'run_forward': 'run the forward pass through the SanaTransformer2DModel or UNet2DConditionModel with prompt embeddings and timestep'}
```

## File: facebookresearch_metaquery/models/transformer_encoder.py

Prompts

```
['build a MetaQuery model from a MetaQueryConfig to generate images from text captions', 'create a MetaQueryConfig with custom vae_id, input_size, loss_type, and num_metaqueries parameters', 'run the MetaQuery forward pass with target images and input_ids to compute flow or diff loss', 'sample images from a text caption using MetaQuery sample_images with guidance scale and inference steps', 'decode latent tensors back to PIL images using MetaQuery decode_latents with normalization', 'build a MLLMInContext model from config to combine LLaVA or Qwen2.5-VL with Sana diffusion', 'create an MLLMInContextConfig with custom mllm_id, diffusion_model_id, and num_metaqueries parameters', 'run the tokenize static method to convert captions and images into tokenized inputs for the MLLM', 'run encode_condition to extract prompt embeddings from the MLLM backbone using input_ids and pixel values', 'run the forward pass through the SanaTransformer2DModel or UNet2DConditionModel with prompt embeddings and timestep', 'build a Qwen2Encoder transformer using a Qwen2Config to encode hidden states with bidirectional attention', 'create a Qwen2BidirectionalSdpaAttention module that performs non-causal SDPA attention with optional QK normalization', 'create a Qwen2EncoderLayer with pre-norm self-attention and MLP blocks using RMSNorm normalization', 'create a MultiHeadRMSNorm module that normalizes across the last dimension and scales by learnable gamma parameters', 'test the Qwen2Encoder forward pass by passing hidden states and verifying gradient checkpointing during training']
```

Usage

```
{'build_encoder_with_qwen2config': 'build a Qwen2Encoder transformer using a Qwen2Config to encode hidden states with bidirectional attention', 'create_bidirectional_attention_layer': 'create a Qwen2BidirectionalSdpaAttention module that performs non-causal SDPA attention with optional QK normalization', 'create_encoder_layer': 'create a Qwen2EncoderLayer with pre-norm self-attention and MLP blocks using RMSNorm normalization', 'create_multiehead_rmsnorm': 'create a MultiHeadRMSNorm module that normalizes across the last dimension and scales by learnable gamma parameters', 'test_encoder_forward_pass': 'test the Qwen2Encoder forward pass by passing hidden states and verifying gradient checkpointing during training'}
```

