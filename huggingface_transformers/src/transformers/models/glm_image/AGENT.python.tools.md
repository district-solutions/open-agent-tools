# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm_image/image_processing_glm_image.py

Prompts

```
['create a GlmImageImageProcessor instance with custom min_pixels and max_pixels for resizing images', 'build smart_resize dimensions from height and width constrained by factor, min_pixels, and max_pixels', 'preprocess a batch of images with GlmImageImageProcessor returning pixel_values and image_grid_thw tensors', 'get the number of image patches for a given height and width using smart_resize and patch_size', 'group images by shape for efficient batching and reorder them back to original order', 'standardize image processor kwargs with size, min_pixels, and max_pixels validation', 'create a GlmImageForConditionalGeneration model for image-to-image text generation with pixel values and input ids', 'run the GlmImageForConditionalGeneration model to generate text conditioned on input images and prompts', 'build a GlmImageVisionModel encoder that processes pixel values into hidden states using vision blocks and patch embeddings', 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'summarize the GlmImageVQVAE model that encodes images into discrete tokens using vector quantization', 'create a GlmImageConfig with vision, text, and VQVAE sub-configs for the GLM-Image multimodal model', 'build a GlmImageVisionModel that processes pixel values into hidden states using vision blocks and rotary position embeddings']
```

Usage

```
{'create_image_processor_glm_image': 'create a GlmImageImageProcessor instance with custom min_pixels and max_pixels for resizing images', 'build_smart_resize_dimensions': 'build smart_resize dimensions from height and width constrained by factor, min_pixels, and max_pixels', 'preprocess_images_glm_image': 'preprocess a batch of images with GlmImageImageProcessor returning pixel_values and image_grid_thw tensors', 'get_number_of_image_patches': 'get the number of image patches for a given height and width using smart_resize and patch_size', 'group_images_by_shape': 'group images by shape for efficient batching and reorder them back to original order'}
```

## File: huggingface_transformers/src/transformers/models/glm_image/image_processing_pil_glm_image.py

Prompts

```
['create a GlmImageImageProcessor instance with custom min_pixels and max_pixels for resizing images', 'build smart_resize dimensions from height and width constrained by factor, min_pixels, and max_pixels', 'preprocess a batch of images with GlmImageImageProcessor returning pixel_values and image_grid_thw tensors', 'get the number of image patches for a given height and width using smart_resize and patch_size', 'group images by shape for efficient batching and reorder them back to original order', 'standardize image processor kwargs with size, min_pixels, and max_pixels validation', 'create a GlmImageForConditionalGeneration model for image-to-image text generation with pixel values and input ids', 'run the GlmImageForConditionalGeneration model to generate text conditioned on input images and prompts', 'build a GlmImageVisionModel encoder that processes pixel values into hidden states using vision blocks and patch embeddings', 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'summarize the GlmImageVQVAE model that encodes images into discrete tokens using vector quantization', 'create a GlmImageConfig with vision, text, and VQVAE sub-configs for the GLM-Image multimodal model', 'build a GlmImageVisionModel that processes pixel values into hidden states using vision blocks and rotary position embeddings']
```

Usage

```
{'create_image_processor_glm_image': 'create a GlmImageImageProcessorPil instance with custom size, min_pixels, and max_pixels parameters', 'build_smart_resize_dimensions': 'build resized height and width from original dimensions constrained by factor, min_pixels, and max_pixels', 'preprocess_images_glm_image': 'preprocess images with GlmImageImageProcessorPil returning pixel_values and image_grid_thw tensors', 'get_number_of_image_patches': 'get the number of image patches for a given image height and width using smart_resize', 'standardize_image_processor_kwargs': 'standardize image processor kwargs with size, min_pixels, and max_pixels validation'}
```

## File: huggingface_transformers/src/transformers/models/glm_image/modeling_glm_image.py

Prompts

```
['create a GlmImageImageProcessor instance with custom min_pixels and max_pixels for resizing images', 'build smart_resize dimensions from height and width constrained by factor, min_pixels, and max_pixels', 'preprocess a batch of images with GlmImageImageProcessor returning pixel_values and image_grid_thw tensors', 'get the number of image patches for a given height and width using smart_resize and patch_size', 'group images by shape for efficient batching and reorder them back to original order', 'standardize image processor kwargs with size, min_pixels, and max_pixels validation', 'create a GlmImageForConditionalGeneration model for image-to-image text generation with pixel values and input ids', 'run the GlmImageForConditionalGeneration model to generate text conditioned on input images and prompts', 'build a GlmImageVisionModel encoder that processes pixel values into hidden states using vision blocks and patch embeddings', 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'summarize the GlmImageVQVAE model that encodes images into discrete tokens using vector quantization', 'create a GlmImageConfig with vision, text, and VQVAE sub-configs for the GLM-Image multimodal model', 'build a GlmImageVisionModel that processes pixel values into hidden states using vision blocks and rotary position embeddings']
```

Usage

```
{'create_glm_image_conditional_generation': 'create a GlmImageForConditionalGeneration model for image-to-image text generation with pixel values and input ids', 'run_glm_image_generate': 'run the GlmImageForConditionalGeneration model to generate text conditioned on input images and prompts', 'build_glm_image_vision_encoder': 'build a GlmImageVisionModel encoder that processes pixel values into hidden states using vision blocks and patch embeddings', 'test_glm_image_rope_index': 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'summarize_glm_image_vqvae': 'summarize the GlmImageVQVAE model that encodes images into discrete tokens using vector quantization'}
```

## File: huggingface_transformers/src/transformers/models/glm_image/modular_glm_image.py

Prompts

```
['create a GlmImageImageProcessor instance with custom min_pixels and max_pixels for resizing images', 'build smart_resize dimensions from height and width constrained by factor, min_pixels, and max_pixels', 'preprocess a batch of images with GlmImageImageProcessor returning pixel_values and image_grid_thw tensors', 'get the number of image patches for a given height and width using smart_resize and patch_size', 'group images by shape for efficient batching and reorder them back to original order', 'standardize image processor kwargs with size, min_pixels, and max_pixels validation', 'create a GlmImageForConditionalGeneration model for image-to-image text generation with pixel values and input ids', 'run the GlmImageForConditionalGeneration model to generate text conditioned on input images and prompts', 'build a GlmImageVisionModel encoder that processes pixel values into hidden states using vision blocks and patch embeddings', 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'summarize the GlmImageVQVAE model that encodes images into discrete tokens using vector quantization', 'create a GlmImageConfig with vision, text, and VQVAE sub-configs for the GLM-Image multimodal model', 'build a GlmImageVisionModel that processes pixel values into hidden states using vision blocks and rotary position embeddings']
```

Usage

```
{'create_glm_image_config': 'create a GlmImageConfig with vision, text, and VQVAE sub-configs for the GLM-Image multimodal model', 'build_glm_image_vision_model': 'build a GlmImageVisionModel that processes pixel values into hidden states using vision blocks and rotary position embeddings', 'test_glm_image_rope_index': 'test the get_rope_index method to compute 3D rotary position embeddings for multi-modal image and text inputs', 'run_glm_image_generate': 'run GlmImageForConditionalGeneration to generate text conditioned on input images and prompts', 'summarize_glm_image_vqvae': 'summarize the GlmImageVQVAE encoder that quantizes image features into discrete tokens using vector quantization'}
```

