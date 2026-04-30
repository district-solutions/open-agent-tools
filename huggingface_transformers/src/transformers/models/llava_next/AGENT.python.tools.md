# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/llava_next/convert_llava_next_weights_to_hf.py

Prompts

```
['convert a LLaVa-NeXT original checkpoint to HuggingFace format and save to a local directory', 'run the LLaVa-NeXT weight conversion CLI tool to transform a model checkpoint to HuggingFace format', 'convert original LLaVa-NeXT state dict keys to HuggingFace model key naming convention', 'load original LLaVa-NeXT safetensors checkpoint weights from HuggingFace Hub', 'convert a LLaVa-NeXT checkpoint and push the resulting model and processor to HuggingFace Hub', 'create a LlavaNextImageProcessor instance for preprocessing images for the LLaVA-NeXT multimodal model', 'preprocess a batch of images for LLaVA-NeXT by dividing into patches, resizing, padding, and normalizing with OPENAI_CLIP mean/std', 'get image patches from an image using variable resolutions selected from grid_pinpoints and divided by patch_size', 'resize an image tensor to a target resolution while maintaining aspect ratio for LLaVA-NeXT patch processing', 'pad a list of image patch batches to the same number of patches for uniform batching', 'create a LlavaNextImageProcessorPil instance for preprocessing multimodal images with patch-based resolution handling', 'call LlavaNextImageProcessorPil preprocess to process images into pixel_values and image_sizes with patch division', 'call LlavaNextImageProcessorPil get_image_patches to divide an image into patches at the best selected resolution', 'configure LlavaNextImageProcessorKwargs with image_grid_pinpoints for variable resolution patch processing', 'call LlavaNextImageProcessorPil _pad_for_batching to pad variable-length patch lists into a uniform batch', 'create a LlavaNextForConditionalGeneration model for multimodal image-text understanding and generation', 'run image feature extraction from pixel values using the vision tower and multi-modal projector', 'build packed image features from per-image patch grids with anyres resolution handling and spatial unpading', 'test multimodal placeholder mask validation to ensure image token count matches feature length', 'generate text autoregressively conditioned on input images and text using LlavaNextForConditionalGeneration']
```

Usage

```
{'convert_llava_checkpoint_to_hf': 'convert a LLaVa-NeXT original checkpoint to HuggingFace format and save to a local directory', 'run_llava_conversion_cli': 'run the LLaVa-NeXT weight conversion CLI tool to transform a model checkpoint to HuggingFace format', 'convert_state_dict_keys_to_hf': 'convert original LLaVa-NeXT state dict keys to HuggingFace model key naming convention', 'load_original_safetensors_state_dict': 'load original LLaVa-NeXT safetensors checkpoint weights from HuggingFace Hub', 'push_converted_llava_model_to_hub': 'convert a LLaVa-NeXT checkpoint and push the resulting model and processor to HuggingFace Hub'}
```

## File: huggingface_transformers/src/transformers/models/llava_next/image_processing_llava_next.py

Prompts

```
['convert a LLaVa-NeXT original checkpoint to HuggingFace format and save to a local directory', 'run the LLaVa-NeXT weight conversion CLI tool to transform a model checkpoint to HuggingFace format', 'convert original LLaVa-NeXT state dict keys to HuggingFace model key naming convention', 'load original LLaVa-NeXT safetensors checkpoint weights from HuggingFace Hub', 'convert a LLaVa-NeXT checkpoint and push the resulting model and processor to HuggingFace Hub', 'create a LlavaNextImageProcessor instance for preprocessing images for the LLaVA-NeXT multimodal model', 'preprocess a batch of images for LLaVA-NeXT by dividing into patches, resizing, padding, and normalizing with OPENAI_CLIP mean/std', 'get image patches from an image using variable resolutions selected from grid_pinpoints and divided by patch_size', 'resize an image tensor to a target resolution while maintaining aspect ratio for LLaVA-NeXT patch processing', 'pad a list of image patch batches to the same number of patches for uniform batching', 'create a LlavaNextImageProcessorPil instance for preprocessing multimodal images with patch-based resolution handling', 'call LlavaNextImageProcessorPil preprocess to process images into pixel_values and image_sizes with patch division', 'call LlavaNextImageProcessorPil get_image_patches to divide an image into patches at the best selected resolution', 'configure LlavaNextImageProcessorKwargs with image_grid_pinpoints for variable resolution patch processing', 'call LlavaNextImageProcessorPil _pad_for_batching to pad variable-length patch lists into a uniform batch', 'create a LlavaNextForConditionalGeneration model for multimodal image-text understanding and generation', 'run image feature extraction from pixel values using the vision tower and multi-modal projector', 'build packed image features from per-image patch grids with anyres resolution handling and spatial unpading', 'test multimodal placeholder mask validation to ensure image token count matches feature length', 'generate text autoregressively conditioned on input images and text using LlavaNextForConditionalGeneration']
```

Usage

```
{'create_llava_next_image_processor': 'create a LlavaNextImageProcessor instance for preprocessing images for the LLaVA-NeXT multimodal model', 'preprocess_llava_next_images': 'preprocess a batch of images for LLaVA-NeXT by dividing into patches, resizing, padding, and normalizing with OPENAI_CLIP mean/std', 'get_image_patches_llava_next': 'get image patches from an image using variable resolutions selected from grid_pinpoints and divided by patch_size', 'resize_for_patching_llava_next': 'resize an image tensor to a target resolution while maintaining aspect ratio for LLaVA-NeXT patch processing', 'pad_for_batching_llava_next': 'pad a list of image patch batches to the same number of patches for uniform batching'}
```

## File: huggingface_transformers/src/transformers/models/llava_next/image_processing_pil_llava_next.py

Prompts

```
['convert a LLaVa-NeXT original checkpoint to HuggingFace format and save to a local directory', 'run the LLaVa-NeXT weight conversion CLI tool to transform a model checkpoint to HuggingFace format', 'convert original LLaVa-NeXT state dict keys to HuggingFace model key naming convention', 'load original LLaVa-NeXT safetensors checkpoint weights from HuggingFace Hub', 'convert a LLaVa-NeXT checkpoint and push the resulting model and processor to HuggingFace Hub', 'create a LlavaNextImageProcessor instance for preprocessing images for the LLaVA-NeXT multimodal model', 'preprocess a batch of images for LLaVA-NeXT by dividing into patches, resizing, padding, and normalizing with OPENAI_CLIP mean/std', 'get image patches from an image using variable resolutions selected from grid_pinpoints and divided by patch_size', 'resize an image tensor to a target resolution while maintaining aspect ratio for LLaVA-NeXT patch processing', 'pad a list of image patch batches to the same number of patches for uniform batching', 'create a LlavaNextImageProcessorPil instance for preprocessing multimodal images with patch-based resolution handling', 'call LlavaNextImageProcessorPil preprocess to process images into pixel_values and image_sizes with patch division', 'call LlavaNextImageProcessorPil get_image_patches to divide an image into patches at the best selected resolution', 'configure LlavaNextImageProcessorKwargs with image_grid_pinpoints for variable resolution patch processing', 'call LlavaNextImageProcessorPil _pad_for_batching to pad variable-length patch lists into a uniform batch', 'create a LlavaNextForConditionalGeneration model for multimodal image-text understanding and generation', 'run image feature extraction from pixel values using the vision tower and multi-modal projector', 'build packed image features from per-image patch grids with anyres resolution handling and spatial unpading', 'test multimodal placeholder mask validation to ensure image token count matches feature length', 'generate text autoregressively conditioned on input images and text using LlavaNextForConditionalGeneration']
```

Usage

```
{'create_LlavaNextImageProcessorPil': 'create a LlavaNextImageProcessorPil instance for preprocessing multimodal images with patch-based resolution handling', 'call_LlavaNextImageProcessorPil_preprocess': 'call LlavaNextImageProcessorPil preprocess to process images into pixel_values and image_sizes with patch division', 'call_LlavaNextImageProcessorPil_get_image_patches': 'call LlavaNextImageProcessorPil get_image_patches to divide an image into patches at the best selected resolution', 'configure_LlavaNextImageProcessorKwargs': 'configure LlavaNextImageProcessorKwargs with image_grid_pinpoints for variable resolution patch processing', 'call_LlavaNextImageProcessorPil__pad_for_batching': 'call LlavaNextImageProcessorPil _pad_for_batching to pad variable-length patch lists into a uniform batch'}
```

## File: huggingface_transformers/src/transformers/models/llava_next/modeling_llava_next.py

Prompts

```
['convert a LLaVa-NeXT original checkpoint to HuggingFace format and save to a local directory', 'run the LLaVa-NeXT weight conversion CLI tool to transform a model checkpoint to HuggingFace format', 'convert original LLaVa-NeXT state dict keys to HuggingFace model key naming convention', 'load original LLaVa-NeXT safetensors checkpoint weights from HuggingFace Hub', 'convert a LLaVa-NeXT checkpoint and push the resulting model and processor to HuggingFace Hub', 'create a LlavaNextImageProcessor instance for preprocessing images for the LLaVA-NeXT multimodal model', 'preprocess a batch of images for LLaVA-NeXT by dividing into patches, resizing, padding, and normalizing with OPENAI_CLIP mean/std', 'get image patches from an image using variable resolutions selected from grid_pinpoints and divided by patch_size', 'resize an image tensor to a target resolution while maintaining aspect ratio for LLaVA-NeXT patch processing', 'pad a list of image patch batches to the same number of patches for uniform batching', 'create a LlavaNextImageProcessorPil instance for preprocessing multimodal images with patch-based resolution handling', 'call LlavaNextImageProcessorPil preprocess to process images into pixel_values and image_sizes with patch division', 'call LlavaNextImageProcessorPil get_image_patches to divide an image into patches at the best selected resolution', 'configure LlavaNextImageProcessorKwargs with image_grid_pinpoints for variable resolution patch processing', 'call LlavaNextImageProcessorPil _pad_for_batching to pad variable-length patch lists into a uniform batch', 'create a LlavaNextForConditionalGeneration model for multimodal image-text understanding and generation', 'run image feature extraction from pixel values using the vision tower and multi-modal projector', 'build packed image features from per-image patch grids with anyres resolution handling and spatial unpading', 'test multimodal placeholder mask validation to ensure image token count matches feature length', 'generate text autoregressively conditioned on input images and text using LlavaNextForConditionalGeneration']
```

Usage

```
{'create_llava_next_model': 'create a LlavaNextForConditionalGeneration model for multimodal image-text understanding and generation', 'run_image_feature_extraction': 'run image feature extraction from pixel values using the vision tower and multi-modal projector', 'build_image_feature_packing': 'build packed image features from per-image patch grids with anyres resolution handling and spatial unpading', 'test_placeholder_mask_validation': 'test multimodal placeholder mask validation to ensure image token count matches feature length', 'generate_text_with_images': 'generate text autoregressively conditioned on input images and text using LlavaNextForConditionalGeneration'}
```

