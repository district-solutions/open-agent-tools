# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unclip/pipeline_unclip.py

Prompts

```
['run the UnCLIPPipeline to generate images from text prompts using prior, decoder, and super resolution stages', 'create an UnCLIPPipeline instance by registering prior, decoder, text encoder, tokenizer, text projection, and super resolution models', 'test the _encode_prompt method to verify CLIP text embeddings and attention mask generation for classifier free guidance', 'refactor the prepare_latents method to support custom noise tensor initialization with shape and dtype validation', 'review the UnCLIPPipeline call method super resolution stage that uses bicubic interpolation and two UNet models for upscaling', 'run the UnCLIPImageVariationPipeline to generate image variations from an input PIL image', 'create random noise latents with a given shape dtype and device for the decoder or super resolution scheduler', 'encode a text prompt into CLIP text embeddings and hidden states with optional classifier free guidance', 'encode an input image into CLIP image embeddings using the vision model and feature extractor', 'build an UnCLIPImageVariationPipeline by registering the decoder text encoder image encoder and super resolution UNets', 'create a UnCLIPTextProjModel instance to project CLIP image and text embeddings for the decoder', 'run the forward pass of UnCLIPTextProjModel with image embeddings, prompt embeds, and text encoder hidden states', 'project CLIP image embeddings into extra context tokens concatenated to the text encoder output', 'compute additive CLIP time embeddings by projecting and adding image and prompt embeddings', 'enable classifier free guidance by adding learned embeddings to image embeddings during the forward pass']
```

Usage

```
{'run_UnCLIPPipeline_call': 'run the UnCLIPPipeline to generate images from text prompts using prior, decoder, and super resolution stages', 'create_UnCLIPPipeline_init': 'create an UnCLIPPipeline instance by registering prior, decoder, text encoder, tokenizer, text projection, and super resolution models', 'test_UnCLIPPipeline_encode_prompt': 'test the _encode_prompt method to verify CLIP text embeddings and attention mask generation for classifier free guidance', 'refactor_UnCLIPPipeline_prepare_latents': 'refactor the prepare_latents method to support custom noise tensor initialization with shape and dtype validation', 'review_UnCLIPPipeline_call_super_res': 'review the UnCLIPPipeline call method super resolution stage that uses bicubic interpolation and two UNet models for upscaling'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unclip/pipeline_unclip_image_variation.py

Prompts

```
['run the UnCLIPPipeline to generate images from text prompts using prior, decoder, and super resolution stages', 'create an UnCLIPPipeline instance by registering prior, decoder, text encoder, tokenizer, text projection, and super resolution models', 'test the _encode_prompt method to verify CLIP text embeddings and attention mask generation for classifier free guidance', 'refactor the prepare_latents method to support custom noise tensor initialization with shape and dtype validation', 'review the UnCLIPPipeline call method super resolution stage that uses bicubic interpolation and two UNet models for upscaling', 'run the UnCLIPImageVariationPipeline to generate image variations from an input PIL image', 'create random noise latents with a given shape dtype and device for the decoder or super resolution scheduler', 'encode a text prompt into CLIP text embeddings and hidden states with optional classifier free guidance', 'encode an input image into CLIP image embeddings using the vision model and feature extractor', 'build an UnCLIPImageVariationPipeline by registering the decoder text encoder image encoder and super resolution UNets', 'create a UnCLIPTextProjModel instance to project CLIP image and text embeddings for the decoder', 'run the forward pass of UnCLIPTextProjModel with image embeddings, prompt embeds, and text encoder hidden states', 'project CLIP image embeddings into extra context tokens concatenated to the text encoder output', 'compute additive CLIP time embeddings by projecting and adding image and prompt embeddings', 'enable classifier free guidance by adding learned embeddings to image embeddings during the forward pass']
```

Usage

```
{'generate_image_variations': 'run the UnCLIPImageVariationPipeline to generate image variations from an input PIL image', 'prepare_latents': 'create random noise latents with a given shape dtype and device for the decoder or super resolution scheduler', 'encode_prompt': 'encode a text prompt into CLIP text embeddings and hidden states with optional classifier free guidance', 'encode_image': 'encode an input image into CLIP image embeddings using the vision model and feature extractor', 'initialize_pipeline': 'build an UnCLIPImageVariationPipeline by registering the decoder text encoder image encoder and super resolution UNets'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/unclip/text_proj.py

Prompts

```
['run the UnCLIPPipeline to generate images from text prompts using prior, decoder, and super resolution stages', 'create an UnCLIPPipeline instance by registering prior, decoder, text encoder, tokenizer, text projection, and super resolution models', 'test the _encode_prompt method to verify CLIP text embeddings and attention mask generation for classifier free guidance', 'refactor the prepare_latents method to support custom noise tensor initialization with shape and dtype validation', 'review the UnCLIPPipeline call method super resolution stage that uses bicubic interpolation and two UNet models for upscaling', 'run the UnCLIPImageVariationPipeline to generate image variations from an input PIL image', 'create random noise latents with a given shape dtype and device for the decoder or super resolution scheduler', 'encode a text prompt into CLIP text embeddings and hidden states with optional classifier free guidance', 'encode an input image into CLIP image embeddings using the vision model and feature extractor', 'build an UnCLIPImageVariationPipeline by registering the decoder text encoder image encoder and super resolution UNets', 'create a UnCLIPTextProjModel instance to project CLIP image and text embeddings for the decoder', 'run the forward pass of UnCLIPTextProjModel with image embeddings, prompt embeds, and text encoder hidden states', 'project CLIP image embeddings into extra context tokens concatenated to the text encoder output', 'compute additive CLIP time embeddings by projecting and adding image and prompt embeddings', 'enable classifier free guidance by adding learned embeddings to image embeddings during the forward pass']
```

Usage

```
{'create_UnCLIPTextProjModel': 'create a UnCLIPTextProjModel instance to project CLIP image and text embeddings for the decoder', 'forward_UnCLIPTextProjModel': 'run the forward pass of UnCLIPTextProjModel with image embeddings, prompt embeds, and text encoder hidden states', 'project_clip_embeddings': 'project CLIP image embeddings into extra context tokens concatenated to the text encoder output', 'compute_additive_time_embeddings': 'compute additive CLIP time embeddings by projecting and adding image and prompt embeddings', 'enable_classifier_free_guidance': 'enable classifier free guidance by adding learned embeddings to image embeddings during the forward pass'}
```

