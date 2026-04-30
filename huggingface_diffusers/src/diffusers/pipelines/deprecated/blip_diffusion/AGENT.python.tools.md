# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/blip_diffusion/blip_image_processing.py

Prompts

```
['create a BlipImageProcessor instance with custom resize, rescale, and normalization settings', 'preprocess a list of images by resizing, rescaling, normalizing, and center cropping for BLIP', 'resize a numpy array image to a target height and width using bicubic resampling', 'postprocess a torch tensor by denormalizing and converting to PIL, numpy, or PyTorch format', 'review the BlipImageProcessor preprocess method to understand the resize, rescale, normalize, and center crop pipeline', 'build a Blip2QFormerModel to get multimodal embeddings from text and image inputs', 'create a Blip2VisionModel to encode pixel values into vision embeddings', 'run the Blip2QFormerModel forward pass with text_input and image_input tensors', 'review the Blip2QFormerLayer cross-attention and feed-forward chunk logic', 'refactor the Blip2TextEmbeddings class to support custom query embedding concatenation', 'build a ContextCLIPTextModel from a CLIPTextConfig to process text with context embeddings', 'run the ContextCLIPTextModel forward pass with input_ids and context embeddings for text encoding', 'build a ContextCLIPTextTransformer with embeddings, encoder, and layer norm for context-aware text processing', 'run the ContextCLIPTextEmbeddings forward pass to merge token embeddings with context embeddings at specified positions', 'review the _expand_mask function that expands attention masks from 2D to 4D tensor shape', 'run the BlipDiffusionPipeline to generate a zero-shot subject-driven image from a reference image and text prompt', 'build an amplified prompt by repeating a subject-driven prompt N times using the _build_prompt method', 'encode a text prompt with QFormer query embeddings as context tokens using the encode_prompt method', 'get multi-modal query embeddings from a reference image and source subject using the QFormer model', 'prepare initial noisy latents scaled by the scheduler init noise sigma for the diffusion process']
```

Usage

```
{'create_blip_image_processor': 'create a BlipImageProcessor instance with custom resize, rescale, and normalization settings', 'preprocess_images_for_blip': 'preprocess a list of images by resizing, rescaling, normalizing, and center cropping for BLIP', 'resize_image_bicubic': 'resize a numpy array image to a target height and width using bicubic resampling', 'postprocess_blip_output_tensor': 'postprocess a torch tensor by denormalizing and converting to PIL, numpy, or PyTorch format', 'review_blip_preprocessing_pipeline': 'review the BlipImageProcessor preprocess method to understand the resize, rescale, normalize, and center crop pipeline'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/blip_diffusion/modeling_blip2.py

Prompts

```
['create a BlipImageProcessor instance with custom resize, rescale, and normalization settings', 'preprocess a list of images by resizing, rescaling, normalizing, and center cropping for BLIP', 'resize a numpy array image to a target height and width using bicubic resampling', 'postprocess a torch tensor by denormalizing and converting to PIL, numpy, or PyTorch format', 'review the BlipImageProcessor preprocess method to understand the resize, rescale, normalize, and center crop pipeline', 'build a Blip2QFormerModel to get multimodal embeddings from text and image inputs', 'create a Blip2VisionModel to encode pixel values into vision embeddings', 'run the Blip2QFormerModel forward pass with text_input and image_input tensors', 'review the Blip2QFormerLayer cross-attention and feed-forward chunk logic', 'refactor the Blip2TextEmbeddings class to support custom query embedding concatenation', 'build a ContextCLIPTextModel from a CLIPTextConfig to process text with context embeddings', 'run the ContextCLIPTextModel forward pass with input_ids and context embeddings for text encoding', 'build a ContextCLIPTextTransformer with embeddings, encoder, and layer norm for context-aware text processing', 'run the ContextCLIPTextEmbeddings forward pass to merge token embeddings with context embeddings at specified positions', 'review the _expand_mask function that expands attention masks from 2D to 4D tensor shape', 'run the BlipDiffusionPipeline to generate a zero-shot subject-driven image from a reference image and text prompt', 'build an amplified prompt by repeating a subject-driven prompt N times using the _build_prompt method', 'encode a text prompt with QFormer query embeddings as context tokens using the encode_prompt method', 'get multi-modal query embeddings from a reference image and source subject using the QFormer model', 'prepare initial noisy latents scaled by the scheduler init noise sigma for the diffusion process']
```

Usage

```
{'build_blip2_qformer_model': 'build a Blip2QFormerModel to get multimodal embeddings from text and image inputs', 'create_blip2_vision_model': 'create a Blip2VisionModel to encode pixel values into vision embeddings', 'run_blip2_qformer_forward': 'run the Blip2QFormerModel forward pass with text_input and image_input tensors', 'review_blip2_qformer_layer': 'review the Blip2QFormerLayer cross-attention and feed-forward chunk logic', 'refactor_blip2_text_embeddings': 'refactor the Blip2TextEmbeddings class to support custom query embedding concatenation'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/blip_diffusion/modeling_ctx_clip.py

Prompts

```
['create a BlipImageProcessor instance with custom resize, rescale, and normalization settings', 'preprocess a list of images by resizing, rescaling, normalizing, and center cropping for BLIP', 'resize a numpy array image to a target height and width using bicubic resampling', 'postprocess a torch tensor by denormalizing and converting to PIL, numpy, or PyTorch format', 'review the BlipImageProcessor preprocess method to understand the resize, rescale, normalize, and center crop pipeline', 'build a Blip2QFormerModel to get multimodal embeddings from text and image inputs', 'create a Blip2VisionModel to encode pixel values into vision embeddings', 'run the Blip2QFormerModel forward pass with text_input and image_input tensors', 'review the Blip2QFormerLayer cross-attention and feed-forward chunk logic', 'refactor the Blip2TextEmbeddings class to support custom query embedding concatenation', 'build a ContextCLIPTextModel from a CLIPTextConfig to process text with context embeddings', 'run the ContextCLIPTextModel forward pass with input_ids and context embeddings for text encoding', 'build a ContextCLIPTextTransformer with embeddings, encoder, and layer norm for context-aware text processing', 'run the ContextCLIPTextEmbeddings forward pass to merge token embeddings with context embeddings at specified positions', 'review the _expand_mask function that expands attention masks from 2D to 4D tensor shape', 'run the BlipDiffusionPipeline to generate a zero-shot subject-driven image from a reference image and text prompt', 'build an amplified prompt by repeating a subject-driven prompt N times using the _build_prompt method', 'encode a text prompt with QFormer query embeddings as context tokens using the encode_prompt method', 'get multi-modal query embeddings from a reference image and source subject using the QFormer model', 'prepare initial noisy latents scaled by the scheduler init noise sigma for the diffusion process']
```

Usage

```
{'build_ContextCLIPTextModel': 'build a ContextCLIPTextModel from a CLIPTextConfig to process text with context embeddings', 'run_ContextCLIPTextModel_forward': 'run the ContextCLIPTextModel forward pass with input_ids and context embeddings for text encoding', 'build_ContextCLIPTextTransformer': 'build a ContextCLIPTextTransformer with embeddings, encoder, and layer norm for context-aware text processing', 'run_ContextCLIPTextEmbeddings_forward': 'run the ContextCLIPTextEmbeddings forward pass to merge token embeddings with context embeddings at specified positions', 'review_expand_mask': 'review the _expand_mask function that expands attention masks from 2D to 4D tensor shape'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/blip_diffusion/pipeline_blip_diffusion.py

Prompts

```
['create a BlipImageProcessor instance with custom resize, rescale, and normalization settings', 'preprocess a list of images by resizing, rescaling, normalizing, and center cropping for BLIP', 'resize a numpy array image to a target height and width using bicubic resampling', 'postprocess a torch tensor by denormalizing and converting to PIL, numpy, or PyTorch format', 'review the BlipImageProcessor preprocess method to understand the resize, rescale, normalize, and center crop pipeline', 'build a Blip2QFormerModel to get multimodal embeddings from text and image inputs', 'create a Blip2VisionModel to encode pixel values into vision embeddings', 'run the Blip2QFormerModel forward pass with text_input and image_input tensors', 'review the Blip2QFormerLayer cross-attention and feed-forward chunk logic', 'refactor the Blip2TextEmbeddings class to support custom query embedding concatenation', 'build a ContextCLIPTextModel from a CLIPTextConfig to process text with context embeddings', 'run the ContextCLIPTextModel forward pass with input_ids and context embeddings for text encoding', 'build a ContextCLIPTextTransformer with embeddings, encoder, and layer norm for context-aware text processing', 'run the ContextCLIPTextEmbeddings forward pass to merge token embeddings with context embeddings at specified positions', 'review the _expand_mask function that expands attention masks from 2D to 4D tensor shape', 'run the BlipDiffusionPipeline to generate a zero-shot subject-driven image from a reference image and text prompt', 'build an amplified prompt by repeating a subject-driven prompt N times using the _build_prompt method', 'encode a text prompt with QFormer query embeddings as context tokens using the encode_prompt method', 'get multi-modal query embeddings from a reference image and source subject using the QFormer model', 'prepare initial noisy latents scaled by the scheduler init noise sigma for the diffusion process']
```

Usage

```
{'run_blip_diffusion_pipeline': 'run the BlipDiffusionPipeline to generate a zero-shot subject-driven image from a reference image and text prompt', 'build_prompt_with_subject_repetition': 'build an amplified prompt by repeating a subject-driven prompt N times using the _build_prompt method', 'encode_prompt_with_query_embeddings': 'encode a text prompt with QFormer query embeddings as context tokens using the encode_prompt method', 'get_query_embeddings_from_image': 'get multi-modal query embeddings from a reference image and source subject using the QFormer model', 'prepare_latents_for_diffusion': 'prepare initial noisy latents scaled by the scheduler init noise sigma for the diffusion process'}
```

