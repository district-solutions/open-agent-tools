# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cohere2_vision/image_processing_cohere2_vision.py

Prompts

```
['create a Cohere2VisionImageProcessor instance with custom crop_to_patches, min_patches, and max_patches settings', 'crop a torch.Tensor image into a grid of patches using optimal aspect ratio and configurable patch size', 'preprocess a list of images by resizing, rescaling, and normalizing with optional patch cropping and batch grouping', 'get the optimal tile grid dimensions (width, height) that best fits an image within min and max tile constraints', 'get all supported aspect ratio tile configurations up to a maximum number of image tiles', 'build a Cohere2VisionMultiModalProjector to downsample and project image features into text embedding space', 'create a Cohere2VisionModel that combines a vision backbone with a language model for multimodal understanding', 'run conditional text generation from images using Cohere2VisionForConditionalGeneration with pixel values and input tokens', 'test the get_image_features method to extract and project image hidden states from a vision tower', 'review the get_placeholder_mask method to validate image token count matches image feature dimensions', 'build a Cohere2VisionForConditionalGeneration model to generate text from images with pixel values and input tokens', 'create a Cohere2VisionModel that obtains image features and runs multimodal forward pass with inputs and pixel values', 'create a Cohere2VisionImageProcessor that preprocesses images with configurable patches and tile sizes', 'create a Cohere2VisionMultiModalProjector that projects image features through pixel shuffle and SwiGLU layers', 'build get_optimal_tiled_canvas to find the best tile grid resolution for an image given min and max tile constraints', 'create a Cohere2VisionProcessor instance with an image processor and tokenizer for multimodal text processing', 'call the processor with images and text to produce input_ids, attention_mask, and pixel_values as a BatchFeature', 'compute the number of placeholder tokens needed for multimodal inputs given a list of image sizes', 'batch decode a list of token id sequences using the underlying tokenizer', 'decode a single token id sequence into text using the underlying tokenizer']
```

Usage

```
{'create_image_processor': 'create a Cohere2VisionImageProcessor instance with custom crop_to_patches, min_patches, and max_patches settings', 'crop_image_to_patches': 'crop a torch.Tensor image into a grid of patches using optimal aspect ratio and configurable patch size', 'preprocess_images': 'preprocess a list of images by resizing, rescaling, and normalizing with optional patch cropping and batch grouping', 'get_optimal_tiled_canvas': 'get the optimal tile grid dimensions (width, height) that best fits an image within min and max tile constraints', 'get_all_supported_aspect_ratios': 'get all supported aspect ratio tile configurations up to a maximum number of image tiles'}
```

## File: huggingface_transformers/src/transformers/models/cohere2_vision/modeling_cohere2_vision.py

Prompts

```
['create a Cohere2VisionImageProcessor instance with custom crop_to_patches, min_patches, and max_patches settings', 'crop a torch.Tensor image into a grid of patches using optimal aspect ratio and configurable patch size', 'preprocess a list of images by resizing, rescaling, and normalizing with optional patch cropping and batch grouping', 'get the optimal tile grid dimensions (width, height) that best fits an image within min and max tile constraints', 'get all supported aspect ratio tile configurations up to a maximum number of image tiles', 'build a Cohere2VisionMultiModalProjector to downsample and project image features into text embedding space', 'create a Cohere2VisionModel that combines a vision backbone with a language model for multimodal understanding', 'run conditional text generation from images using Cohere2VisionForConditionalGeneration with pixel values and input tokens', 'test the get_image_features method to extract and project image hidden states from a vision tower', 'review the get_placeholder_mask method to validate image token count matches image feature dimensions', 'build a Cohere2VisionForConditionalGeneration model to generate text from images with pixel values and input tokens', 'create a Cohere2VisionModel that obtains image features and runs multimodal forward pass with inputs and pixel values', 'create a Cohere2VisionImageProcessor that preprocesses images with configurable patches and tile sizes', 'create a Cohere2VisionMultiModalProjector that projects image features through pixel shuffle and SwiGLU layers', 'build get_optimal_tiled_canvas to find the best tile grid resolution for an image given min and max tile constraints', 'create a Cohere2VisionProcessor instance with an image processor and tokenizer for multimodal text processing', 'call the processor with images and text to produce input_ids, attention_mask, and pixel_values as a BatchFeature', 'compute the number of placeholder tokens needed for multimodal inputs given a list of image sizes', 'batch decode a list of token id sequences using the underlying tokenizer', 'decode a single token id sequence into text using the underlying tokenizer']
```

Usage

```
{'build_multimodal_projector': 'build a Cohere2VisionMultiModalProjector to downsample and project image features into text embedding space', 'create_vision_model': 'create a Cohere2VisionModel that combines a vision backbone with a language model for multimodal understanding', 'run_conditional_generation': 'run conditional text generation from images using Cohere2VisionForConditionalGeneration with pixel values and input tokens', 'test_image_features': 'test the get_image_features method to extract and project image hidden states from a vision tower', 'review_placeholder_mask': 'review the get_placeholder_mask method to validate image token count matches image feature dimensions'}
```

## File: huggingface_transformers/src/transformers/models/cohere2_vision/modular_cohere2_vision.py

Prompts

```
['create a Cohere2VisionImageProcessor instance with custom crop_to_patches, min_patches, and max_patches settings', 'crop a torch.Tensor image into a grid of patches using optimal aspect ratio and configurable patch size', 'preprocess a list of images by resizing, rescaling, and normalizing with optional patch cropping and batch grouping', 'get the optimal tile grid dimensions (width, height) that best fits an image within min and max tile constraints', 'get all supported aspect ratio tile configurations up to a maximum number of image tiles', 'build a Cohere2VisionMultiModalProjector to downsample and project image features into text embedding space', 'create a Cohere2VisionModel that combines a vision backbone with a language model for multimodal understanding', 'run conditional text generation from images using Cohere2VisionForConditionalGeneration with pixel values and input tokens', 'test the get_image_features method to extract and project image hidden states from a vision tower', 'review the get_placeholder_mask method to validate image token count matches image feature dimensions', 'build a Cohere2VisionForConditionalGeneration model to generate text from images with pixel values and input tokens', 'create a Cohere2VisionModel that obtains image features and runs multimodal forward pass with inputs and pixel values', 'create a Cohere2VisionImageProcessor that preprocesses images with configurable patches and tile sizes', 'create a Cohere2VisionMultiModalProjector that projects image features through pixel shuffle and SwiGLU layers', 'build get_optimal_tiled_canvas to find the best tile grid resolution for an image given min and max tile constraints', 'create a Cohere2VisionProcessor instance with an image processor and tokenizer for multimodal text processing', 'call the processor with images and text to produce input_ids, attention_mask, and pixel_values as a BatchFeature', 'compute the number of placeholder tokens needed for multimodal inputs given a list of image sizes', 'batch decode a list of token id sequences using the underlying tokenizer', 'decode a single token id sequence into text using the underlying tokenizer']
```

Usage

```
{'build_cohere2_vision_for_conditional_generation': 'build a Cohere2VisionForConditionalGeneration model to generate text from images with pixel values and input tokens', 'create_cohere2_vision_model': 'create a Cohere2VisionModel that obtains image features and runs multimodal forward pass with inputs and pixel values', 'create_cohere2_vision_image_processor': 'create a Cohere2VisionImageProcessor that preprocesses images with configurable patches and tile sizes', 'create_cohere2_vision_multi_modal_projector': 'create a Cohere2VisionMultiModalProjector that projects image features through pixel shuffle and SwiGLU layers', 'build_get_optimal_tiled_canvas': 'build get_optimal_tiled_canvas to find the best tile grid resolution for an image given min and max tile constraints'}
```

## File: huggingface_transformers/src/transformers/models/cohere2_vision/processing_cohere2_vision.py

Prompts

```
['create a Cohere2VisionImageProcessor instance with custom crop_to_patches, min_patches, and max_patches settings', 'crop a torch.Tensor image into a grid of patches using optimal aspect ratio and configurable patch size', 'preprocess a list of images by resizing, rescaling, and normalizing with optional patch cropping and batch grouping', 'get the optimal tile grid dimensions (width, height) that best fits an image within min and max tile constraints', 'get all supported aspect ratio tile configurations up to a maximum number of image tiles', 'build a Cohere2VisionMultiModalProjector to downsample and project image features into text embedding space', 'create a Cohere2VisionModel that combines a vision backbone with a language model for multimodal understanding', 'run conditional text generation from images using Cohere2VisionForConditionalGeneration with pixel values and input tokens', 'test the get_image_features method to extract and project image hidden states from a vision tower', 'review the get_placeholder_mask method to validate image token count matches image feature dimensions', 'build a Cohere2VisionForConditionalGeneration model to generate text from images with pixel values and input tokens', 'create a Cohere2VisionModel that obtains image features and runs multimodal forward pass with inputs and pixel values', 'create a Cohere2VisionImageProcessor that preprocesses images with configurable patches and tile sizes', 'create a Cohere2VisionMultiModalProjector that projects image features through pixel shuffle and SwiGLU layers', 'build get_optimal_tiled_canvas to find the best tile grid resolution for an image given min and max tile constraints', 'create a Cohere2VisionProcessor instance with an image processor and tokenizer for multimodal text processing', 'call the processor with images and text to produce input_ids, attention_mask, and pixel_values as a BatchFeature', 'compute the number of placeholder tokens needed for multimodal inputs given a list of image sizes', 'batch decode a list of token id sequences using the underlying tokenizer', 'decode a single token id sequence into text using the underlying tokenizer']
```

Usage

```
{'create_cohere2_vision_processor': 'create a Cohere2VisionProcessor instance with an image processor and tokenizer for multimodal text processing', 'call_processor_with_images_and_text': 'call the processor with images and text to produce input_ids, attention_mask, and pixel_values as a BatchFeature', 'compute_multimodal_token_count': 'compute the number of placeholder tokens needed for multimodal inputs given a list of image sizes', 'batch_decode_token_ids': 'batch decode a list of token id sequences using the underlying tokenizer', 'decode_single_token_sequence': 'decode a single token id sequence into text using the underlying tokenizer'}
```

