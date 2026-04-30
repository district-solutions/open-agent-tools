# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/versatile_diffusion/modeling_text_unet.py

Prompts

```
['build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create a flat ResNet block with group normalization, time embedding projection, and skip connections', 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines', 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline', 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'validate that the input image, height, width, and callback steps meet the pipeline requirements', 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'swap Transformer2DModel attention blocks between the image and text UNets']
```

Usage

```
{'build_UNetFlatConditionModel': 'build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create_FourierEmbedder': 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create_GLIGENTextBoundingboxProjection': 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create_LinearMultiDim': 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create_ResnetBlockFlat': 'create a flat ResNet block with group normalization, time embedding projection, and skip connections'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/versatile_diffusion/pipeline_versatile_diffusion.py

Prompts

```
['build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create a flat ResNet block with group normalization, time embedding projection, and skip connections', 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines', 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline', 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'validate that the input image, height, width, and callback steps meet the pipeline requirements', 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'swap Transformer2DModel attention blocks between the image and text UNets']
```

Usage

```
{'run_text_to_image': 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run_image_variation': 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run_dual_guided': 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review_VersatileDiffusionPipeline': 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor_VersatileDiffusionPipeline': 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/versatile_diffusion/pipeline_versatile_diffusion_dual_guided.py

Prompts

```
['build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create a flat ResNet block with group normalization, time embedding projection, and skip connections', 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines', 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline', 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'validate that the input image, height, width, and callback steps meet the pipeline requirements', 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'swap Transformer2DModel attention blocks between the image and text UNets']
```

Usage

```
{'run_dual_guided_generation': 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove_unused_weights': 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert_to_dual_attention': 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode_text_prompt': 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode_image_prompt': 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/versatile_diffusion/pipeline_versatile_diffusion_image_variation.py

Prompts

```
['build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create a flat ResNet block with group normalization, time embedding projection, and skip connections', 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines', 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline', 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'validate that the input image, height, width, and callback steps meet the pipeline requirements', 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'swap Transformer2DModel attention blocks between the image and text UNets']
```

Usage

```
{'run_image_variation': 'run the VersatileDiffusionImageVariationPipeline to generate image variations from an input image using shi-labs/versatile-diffusion', 'encode_image_prompt': 'encode an input image into CLIP vision embeddings using the _encode_prompt method with classifier free guidance', 'prepare_latents': 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode_latents': 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'check_pipeline_inputs': 'validate that the input image, height, width, and callback steps meet the pipeline requirements'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/versatile_diffusion/pipeline_versatile_diffusion_text_to_image.py

Prompts

```
['build a conditional 2D UNet model for text-to-image diffusion with cross-attention and time embeddings', 'create a Fourier feature embedder that maps inputs to sin/cos frequency bands for neural networks', 'create a GLIGEN bounding box projection module that combines text embeddings with spatial position features', 'create a multi-dimensional linear layer that reshapes tensors before and after a linear transformation', 'create a flat ResNet block with group normalization, time embedding projection, and skip connections', 'run the VersatileDiffusionPipeline text_to_image method to generate an image from a text prompt', 'run the VersatileDiffusionPipeline image_variation method to generate image variations from an input image', 'run the VersatileDiffusionPipeline dual_guided method to generate images guided by both text and an image', 'review the VersatileDiffusionPipeline class and its image generation methods for text-to-image, image variation, and dual-guided modes', 'refactor the VersatileDiffusionPipeline to modify how it delegates to the text-to-image, image variation, or dual-guided sub-pipelines', 'run the VersatileDiffusionDualGuidedPipeline to generate images guided by both text prompts and input images', 'remove the text_unet module from the pipeline to reduce memory usage after loading', 'convert the image UNet transformer blocks to DualTransformer2DModel blocks that combine image and text UNet attention', 'encode a text prompt into CLIP text embeddings for use as conditional guidance in the diffusion pipeline', 'encode an input image into CLIP image embeddings for use as conditional guidance in the diffusion pipeline', 'prepare random Gaussian latents scaled by the scheduler init noise sigma for a given batch size and shape', 'decode latent tensors back to pixel-space images using the VAE decoder with scaling and clamping', 'validate that the input image, height, width, and callback steps meet the pipeline requirements', 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'swap Transformer2DModel attention blocks between the image and text UNets']
```

Usage

```
{'run_text_to_image': 'run the VersatileDiffusionTextToImagePipeline to generate an image from a text prompt', 'remove_unused_weights': 'remove the unused text_unet weights from the VersatileDiffusionTextToImagePipeline to save memory', 'encode_prompt': 'encode a text prompt into CLIP text embeddings using the pipeline text encoder', 'prepare_latents': 'prepare initial noisy latent tensors for the diffusion denoising process', 'swap_unet_attention_blocks': 'swap Transformer2DModel attention blocks between the image and text UNets'}
```

