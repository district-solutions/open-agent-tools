# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/models/adm_unet/adm.py

Prompts

```
['build a conditional ADM U-Net diffusion model using the adm_unet factory function with CLIP image embeddings', 'create an ADMUNet instance with custom channels per layer, residual blocks, and attention configuration', 'run the ADMUNet forward pass with a noised input tensor, timestep, and optional conditional inputs', 'create an ADMStack container to stack residual blocks, attention blocks, and simple blocks together', 'build an ADM stack with a residual block followed by an attention block using adm_stack_res_attn', 'build an ADMAttentionBlock with group norm, multihead attention, and residual connection for diffusion models', 'create an ADMCrossAttention module that concatenates projected conditioning inputs with key and value vectors', 'build an adm_attention module combining ADMCrossAttention with MultiHeadAttention for a given number of channels and heads', 'create an ADMAttentionBlock via the adm_attn_block factory function with specified channels and optional conditioning dimension', 'review the ADMCrossAttention forward pass that flattens spatial dims, concatenates conditional embeddings, and runs scaled dot product attention', 'build an ADMResBlock residual block with conditional embedding for a diffusion model', 'create a downsample ADMResBlock using adm_res_downsample_block with specified channels and condition dimension', 'create an upsample ADMResBlock using adm_res_upsample_block with specified channels and condition dimension', 'create an ADMResBlock with skip convolution using adm_res_skipconv_block for mismatched channel dimensions', 'test the ADMResBlock forward pass with input tensor and conditional embedding tensor']
```

Usage

```
{'build_adm_unet': 'build a conditional ADM U-Net diffusion model using the adm_unet factory function with CLIP image embeddings', 'create_admunet_instance': 'create an ADMUNet instance with custom channels per layer, residual blocks, and attention configuration', 'run_admunet_forward': 'run the ADMUNet forward pass with a noised input tensor, timestep, and optional conditional inputs', 'create_admstack': 'create an ADMStack container to stack residual blocks, attention blocks, and simple blocks together', 'build_adm_stack_res_attn': 'build an ADM stack with a residual block followed by an attention block using adm_stack_res_attn'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/models/adm_unet/attention_block.py

Prompts

```
['build a conditional ADM U-Net diffusion model using the adm_unet factory function with CLIP image embeddings', 'create an ADMUNet instance with custom channels per layer, residual blocks, and attention configuration', 'run the ADMUNet forward pass with a noised input tensor, timestep, and optional conditional inputs', 'create an ADMStack container to stack residual blocks, attention blocks, and simple blocks together', 'build an ADM stack with a residual block followed by an attention block using adm_stack_res_attn', 'build an ADMAttentionBlock with group norm, multihead attention, and residual connection for diffusion models', 'create an ADMCrossAttention module that concatenates projected conditioning inputs with key and value vectors', 'build an adm_attention module combining ADMCrossAttention with MultiHeadAttention for a given number of channels and heads', 'create an ADMAttentionBlock via the adm_attn_block factory function with specified channels and optional conditioning dimension', 'review the ADMCrossAttention forward pass that flattens spatial dims, concatenates conditional embeddings, and runs scaled dot product attention', 'build an ADMResBlock residual block with conditional embedding for a diffusion model', 'create a downsample ADMResBlock using adm_res_downsample_block with specified channels and condition dimension', 'create an upsample ADMResBlock using adm_res_upsample_block with specified channels and condition dimension', 'create an ADMResBlock with skip convolution using adm_res_skipconv_block for mismatched channel dimensions', 'test the ADMResBlock forward pass with input tensor and conditional embedding tensor']
```

Usage

```
{'build_adm_attention_block': 'build an ADMAttentionBlock with group norm, multihead attention, and residual connection for diffusion models', 'create_adm_cross_attention': 'create an ADMCrossAttention module that concatenates projected conditioning inputs with key and value vectors', 'build_adm_attention_module': 'build an adm_attention module combining ADMCrossAttention with MultiHeadAttention for a given number of channels and heads', 'create_adm_attn_block_factory': 'create an ADMAttentionBlock via the adm_attn_block factory function with specified channels and optional conditioning dimension', 'review_adm_cross_attention_forward': 'review the ADMCrossAttention forward pass that flattens spatial dims, concatenates conditional embeddings, and runs scaled dot product attention'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/models/adm_unet/res_block.py

Prompts

```
['build a conditional ADM U-Net diffusion model using the adm_unet factory function with CLIP image embeddings', 'create an ADMUNet instance with custom channels per layer, residual blocks, and attention configuration', 'run the ADMUNet forward pass with a noised input tensor, timestep, and optional conditional inputs', 'create an ADMStack container to stack residual blocks, attention blocks, and simple blocks together', 'build an ADM stack with a residual block followed by an attention block using adm_stack_res_attn', 'build an ADMAttentionBlock with group norm, multihead attention, and residual connection for diffusion models', 'create an ADMCrossAttention module that concatenates projected conditioning inputs with key and value vectors', 'build an adm_attention module combining ADMCrossAttention with MultiHeadAttention for a given number of channels and heads', 'create an ADMAttentionBlock via the adm_attn_block factory function with specified channels and optional conditioning dimension', 'review the ADMCrossAttention forward pass that flattens spatial dims, concatenates conditional embeddings, and runs scaled dot product attention', 'build an ADMResBlock residual block with conditional embedding for a diffusion model', 'create a downsample ADMResBlock using adm_res_downsample_block with specified channels and condition dimension', 'create an upsample ADMResBlock using adm_res_upsample_block with specified channels and condition dimension', 'create an ADMResBlock with skip convolution using adm_res_skipconv_block for mismatched channel dimensions', 'test the ADMResBlock forward pass with input tensor and conditional embedding tensor']
```

Usage

```
{'build_adm_res_block': 'build an ADMResBlock residual block with conditional embedding for a diffusion model', 'create_adm_res_downsample_block': 'create a downsample ADMResBlock using adm_res_downsample_block with specified channels and condition dimension', 'create_adm_res_upsample_block': 'create an upsample ADMResBlock using adm_res_upsample_block with specified channels and condition dimension', 'create_adm_res_skipconv_block': 'create an ADMResBlock with skip convolution using adm_res_skipconv_block for mismatched channel dimensions', 'test_adm_res_block_forward': 'test the ADMResBlock forward pass with input tensor and conditional embedding tensor'}
```

