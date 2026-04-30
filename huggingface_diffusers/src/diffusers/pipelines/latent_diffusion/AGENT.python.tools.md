# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/latent_diffusion/pipeline_latent_diffusion.py

Prompts

```
['run the LDMTextToImagePipeline to generate images from text prompts using latent diffusion', 'build an LDMBertConfig to set vocab size, encoder layers, attention heads, and dropout for the text encoder', 'create an LDMBertEncoder with token embeddings, position embeddings, and self-attention layers for text encoding', 'test the LDMBertAttention multi-headed attention layer with query, key, and value projections', 'review the LDMBertEncoderLayer combining self-attention and feed-forward network with layer normalization', 'run the LDMSuperResolutionPipeline on a PIL image to generate a super-resolved output image', 'load a pretrained LDMSuperResolutionPipeline from a Hugging Face model checkpoint using from_pretrained', 'preprocess a PIL image by resizing to 32-pixel multiples and normalizing to a tensor for latent diffusion', 'run the LDMSuperResolutionPipeline with custom num_inference_steps and eta parameters for DDIM scheduling', 'run the LDMSuperResolutionPipeline with a torch Generator for deterministic super-resolution output']
```

Usage

```
{'run_LDMTextToImagePipeline': 'run the LDMTextToImagePipeline to generate images from text prompts using latent diffusion', 'build_LDMBertConfig': 'build an LDMBertConfig to set vocab size, encoder layers, attention heads, and dropout for the text encoder', 'create_LDMBertEncoder': 'create an LDMBertEncoder with token embeddings, position embeddings, and self-attention layers for text encoding', 'test_LDMBertAttention': 'test the LDMBertAttention multi-headed attention layer with query, key, and value projections', 'review_LDMBertEncoderLayer': 'review the LDMBertEncoderLayer combining self-attention and feed-forward network with layer normalization'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/latent_diffusion/pipeline_latent_diffusion_superresolution.py

Prompts

```
['run the LDMTextToImagePipeline to generate images from text prompts using latent diffusion', 'build an LDMBertConfig to set vocab size, encoder layers, attention heads, and dropout for the text encoder', 'create an LDMBertEncoder with token embeddings, position embeddings, and self-attention layers for text encoding', 'test the LDMBertAttention multi-headed attention layer with query, key, and value projections', 'review the LDMBertEncoderLayer combining self-attention and feed-forward network with layer normalization', 'run the LDMSuperResolutionPipeline on a PIL image to generate a super-resolved output image', 'load a pretrained LDMSuperResolutionPipeline from a Hugging Face model checkpoint using from_pretrained', 'preprocess a PIL image by resizing to 32-pixel multiples and normalizing to a tensor for latent diffusion', 'run the LDMSuperResolutionPipeline with custom num_inference_steps and eta parameters for DDIM scheduling', 'run the LDMSuperResolutionPipeline with a torch Generator for deterministic super-resolution output']
```

Usage

```
{'run_superresolution_inference': 'run the LDMSuperResolutionPipeline on a PIL image to generate a super-resolved output image', 'load_pretrained_superresolution_pipeline': 'load a pretrained LDMSuperResolutionPipeline from a Hugging Face model checkpoint using from_pretrained', 'preprocess_image_for_ldm': 'preprocess a PIL image by resizing to 32-pixel multiples and normalizing to a tensor for latent diffusion', 'run_superresolution_with_custom_steps': 'run the LDMSuperResolutionPipeline with custom num_inference_steps and eta parameters for DDIM scheduling', 'run_superresolution_deterministic': 'run the LDMSuperResolutionPipeline with a torch Generator for deterministic super-resolution output'}
```

