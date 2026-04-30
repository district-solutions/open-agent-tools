# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unidiffuser/modeling_text_decoder.py

Prompts

```
['create a UniDiffuserTextDecoder model with prefix_length and prefix_inner_dim parameters for text decoding', 'run the forward pass of UniDiffuserTextDecoder with input_ids and prefix_embeds tensors', 'generate captions from text embedding features using the UniDiffuserTextDecoder model', 'generate text using beam search with configurable beam_size and temperature via UniDiffuserTextDecoder', 'encode prefix embeddings using the UniDiffuserTextDecoder encode method', 'build a U-ViT transformer model with skip connections for image generation using UTransformer2DModel', 'build a UniDiffuser model that processes VAE latent, CLIP image, and CLIP text embeddings together', 'create a PatchEmbed layer to convert 2D image tensors into patch embeddings with positional encoding', 'create a UniDiffuserBlock transformer block with LayerNorms on the residual backbone for post-LayerNorm', 'create a UTransformerBlock transformer block supporting both pre-LayerNorm and post-LayerNorm configurations', 'run the UniDiffuserPipeline to generate images from a text prompt using text2img mode', 'run the UniDiffuserPipeline to generate text captions from an input image using img2text mode', 'run the UniDiffuserPipeline to jointly generate paired images and text using joint mode', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'encode an input image into VAE and CLIP latent representations using encode_image_vae_latents and encode_image_clip_latents']
```

Usage

```
{'create_UniDiffuserTextDecoder': 'create a UniDiffuserTextDecoder model with prefix_length and prefix_inner_dim parameters for text decoding', 'forward_UniDiffuserTextDecoder': 'run the forward pass of UniDiffuserTextDecoder with input_ids and prefix_embeds tensors', 'generate_captions_UniDiffuserTextDecoder': 'generate captions from text embedding features using the UniDiffuserTextDecoder model', 'generate_beam_UniDiffuserTextDecoder': 'generate text using beam search with configurable beam_size and temperature via UniDiffuserTextDecoder', 'encode_UniDiffuserTextDecoder': 'encode prefix embeddings using the UniDiffuserTextDecoder encode method'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unidiffuser/modeling_uvit.py

Prompts

```
['create a UniDiffuserTextDecoder model with prefix_length and prefix_inner_dim parameters for text decoding', 'run the forward pass of UniDiffuserTextDecoder with input_ids and prefix_embeds tensors', 'generate captions from text embedding features using the UniDiffuserTextDecoder model', 'generate text using beam search with configurable beam_size and temperature via UniDiffuserTextDecoder', 'encode prefix embeddings using the UniDiffuserTextDecoder encode method', 'build a U-ViT transformer model with skip connections for image generation using UTransformer2DModel', 'build a UniDiffuser model that processes VAE latent, CLIP image, and CLIP text embeddings together', 'create a PatchEmbed layer to convert 2D image tensors into patch embeddings with positional encoding', 'create a UniDiffuserBlock transformer block with LayerNorms on the residual backbone for post-LayerNorm', 'create a UTransformerBlock transformer block supporting both pre-LayerNorm and post-LayerNorm configurations', 'run the UniDiffuserPipeline to generate images from a text prompt using text2img mode', 'run the UniDiffuserPipeline to generate text captions from an input image using img2text mode', 'run the UniDiffuserPipeline to jointly generate paired images and text using joint mode', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'encode an input image into VAE and CLIP latent representations using encode_image_vae_latents and encode_image_clip_latents']
```

Usage

```
{'build_UTransformer2DModel': 'build a U-ViT transformer model with skip connections for image generation using UTransformer2DModel', 'build_UniDiffuserModel': 'build a UniDiffuser model that processes VAE latent, CLIP image, and CLIP text embeddings together', 'create_PatchEmbed': 'create a PatchEmbed layer to convert 2D image tensors into patch embeddings with positional encoding', 'create_UniDiffuserBlock': 'create a UniDiffuserBlock transformer block with LayerNorms on the residual backbone for post-LayerNorm', 'create_UTransformerBlock': 'create a UTransformerBlock transformer block supporting both pre-LayerNorm and post-LayerNorm configurations'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unidiffuser/pipeline_unidiffuser.py

Prompts

```
['create a UniDiffuserTextDecoder model with prefix_length and prefix_inner_dim parameters for text decoding', 'run the forward pass of UniDiffuserTextDecoder with input_ids and prefix_embeds tensors', 'generate captions from text embedding features using the UniDiffuserTextDecoder model', 'generate text using beam search with configurable beam_size and temperature via UniDiffuserTextDecoder', 'encode prefix embeddings using the UniDiffuserTextDecoder encode method', 'build a U-ViT transformer model with skip connections for image generation using UTransformer2DModel', 'build a UniDiffuser model that processes VAE latent, CLIP image, and CLIP text embeddings together', 'create a PatchEmbed layer to convert 2D image tensors into patch embeddings with positional encoding', 'create a UniDiffuserBlock transformer block with LayerNorms on the residual backbone for post-LayerNorm', 'create a UTransformerBlock transformer block supporting both pre-LayerNorm and post-LayerNorm configurations', 'run the UniDiffuserPipeline to generate images from a text prompt using text2img mode', 'run the UniDiffuserPipeline to generate text captions from an input image using img2text mode', 'run the UniDiffuserPipeline to jointly generate paired images and text using joint mode', 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'encode an input image into VAE and CLIP latent representations using encode_image_vae_latents and encode_image_clip_latents']
```

Usage

```
{'run_text_to_image_generation': 'run the UniDiffuserPipeline to generate images from a text prompt using text2img mode', 'run_image_to_text_generation': 'run the UniDiffuserPipeline to generate text captions from an input image using img2text mode', 'run_joint_image_text_generation': 'run the UniDiffuserPipeline to jointly generate paired images and text using joint mode', 'encode_prompt_embeddings': 'encode a text prompt into CLIP text embeddings using the encode_prompt method', 'encode_image_latents': 'encode an input image into VAE and CLIP latent representations using encode_image_vae_latents and encode_image_clip_latents'}
```

