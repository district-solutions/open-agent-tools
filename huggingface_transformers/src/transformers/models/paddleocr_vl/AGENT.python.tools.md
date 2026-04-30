# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/paddleocr_vl/image_processing_paddleocr_vl.py

Prompts

```
['build a PaddleOCRVLImageProcessor instance with custom min_pixels, max_pixels, and size configuration', 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements', 'run PaddleOCR-VL for conditional text generation from image and text inputs', 'get image features from PaddleOCR-VL vision encoder and projector for a given pixel tensor', 'compute the 3D multimodal RoPE position index for mixed image-text input sequences', 'build the PaddleOCR-VL text decoder language model with rotary embeddings and causal attention', 'run the PaddleOCR-VL vision transformer to extract visual embeddings from pixel values', 'run PaddleOCR-VL for image OCR by passing images and text prompts through PaddleOCRVLForConditionalGeneration', 'create a PaddleOCRVLProcessor to tokenize text and preprocess images for the PaddleOCR-VL model', 'create a PaddleOCRVLImageProcessor to resize and patch images for the PaddleOCR-VL vision encoder', 'create a PaddleOCRVLModel that combines a Siglip-based vision encoder with an Ernie4_5-based text decoder for multimodal tasks', 'create a PaddleOCRProjector that merges spatial patches from the vision encoder into text-embedding dimensions']
```

Usage

```
{'build_paddleocrvl_image_processor': 'build a PaddleOCRVLImageProcessor instance with custom min_pixels, max_pixels, and size configuration', 'run_smart_resize': 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test_paddleocrvl_preprocess': 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get_paddleocrvl_patch_count': 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review_paddleocrvl_standardize_kwargs': 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements'}
```

## File: huggingface_transformers/src/transformers/models/paddleocr_vl/image_processing_pil_paddleocr_vl.py

Prompts

```
['build a PaddleOCRVLImageProcessor instance with custom min_pixels, max_pixels, and size configuration', 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements', 'run PaddleOCR-VL for conditional text generation from image and text inputs', 'get image features from PaddleOCR-VL vision encoder and projector for a given pixel tensor', 'compute the 3D multimodal RoPE position index for mixed image-text input sequences', 'build the PaddleOCR-VL text decoder language model with rotary embeddings and causal attention', 'run the PaddleOCR-VL vision transformer to extract visual embeddings from pixel values', 'run PaddleOCR-VL for image OCR by passing images and text prompts through PaddleOCRVLForConditionalGeneration', 'create a PaddleOCRVLProcessor to tokenize text and preprocess images for the PaddleOCR-VL model', 'create a PaddleOCRVLImageProcessor to resize and patch images for the PaddleOCR-VL vision encoder', 'create a PaddleOCRVLModel that combines a Siglip-based vision encoder with an Ernie4_5-based text decoder for multimodal tasks', 'create a PaddleOCRProjector that merges spatial patches from the vision encoder into text-embedding dimensions']
```

Usage

```
{'build_paddleocrvl_image_processor': 'build a PaddleOCRVLImageProcessorPil instance with custom min_pixels and max_pixels for image preprocessing', 'run_smart_resize': 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test_paddleocrvl_preprocess': 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get_paddleocrvl_patch_count': 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review_paddleocrvl_standardize_kwargs': 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements'}
```

## File: huggingface_transformers/src/transformers/models/paddleocr_vl/modeling_paddleocr_vl.py

Prompts

```
['build a PaddleOCRVLImageProcessor instance with custom min_pixels, max_pixels, and size configuration', 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements', 'run PaddleOCR-VL for conditional text generation from image and text inputs', 'get image features from PaddleOCR-VL vision encoder and projector for a given pixel tensor', 'compute the 3D multimodal RoPE position index for mixed image-text input sequences', 'build the PaddleOCR-VL text decoder language model with rotary embeddings and causal attention', 'run the PaddleOCR-VL vision transformer to extract visual embeddings from pixel values', 'run PaddleOCR-VL for image OCR by passing images and text prompts through PaddleOCRVLForConditionalGeneration', 'create a PaddleOCRVLProcessor to tokenize text and preprocess images for the PaddleOCR-VL model', 'create a PaddleOCRVLImageProcessor to resize and patch images for the PaddleOCR-VL vision encoder', 'create a PaddleOCRVLModel that combines a Siglip-based vision encoder with an Ernie4_5-based text decoder for multimodal tasks', 'create a PaddleOCRProjector that merges spatial patches from the vision encoder into text-embedding dimensions']
```

Usage

```
{'run_paddleocr_vl_conditional_generation': 'run PaddleOCR-VL for conditional text generation from image and text inputs', 'get_paddleocr_vl_image_features': 'get image features from PaddleOCR-VL vision encoder and projector for a given pixel tensor', 'compute_paddleocr_vl_rope_index': 'compute the 3D multimodal RoPE position index for mixed image-text input sequences', 'build_paddleocr_vl_language_model': 'build the PaddleOCR-VL text decoder language model with rotary embeddings and causal attention', 'run_paddleocr_vl_vision_transformer': 'run the PaddleOCR-VL vision transformer to extract visual embeddings from pixel values'}
```

## File: huggingface_transformers/src/transformers/models/paddleocr_vl/modular_paddleocr_vl.py

Prompts

```
['build a PaddleOCRVLImageProcessor instance with custom min_pixels, max_pixels, and size configuration', 'run smart_resize to compute optimal image dimensions respecting min_pixels, max_pixels, and grid factor constraints', 'test the preprocess method to convert images into pixel_values and image_grid_thw tensors', 'get the number of image patches for a given image height and width using smart_resize and grid division', 'review _standardize_kwargs to validate size dict with shortest_edge and longest_edge requirements', 'run PaddleOCR-VL for conditional text generation from image and text inputs', 'get image features from PaddleOCR-VL vision encoder and projector for a given pixel tensor', 'compute the 3D multimodal RoPE position index for mixed image-text input sequences', 'build the PaddleOCR-VL text decoder language model with rotary embeddings and causal attention', 'run the PaddleOCR-VL vision transformer to extract visual embeddings from pixel values', 'run PaddleOCR-VL for image OCR by passing images and text prompts through PaddleOCRVLForConditionalGeneration', 'create a PaddleOCRVLProcessor to tokenize text and preprocess images for the PaddleOCR-VL model', 'create a PaddleOCRVLImageProcessor to resize and patch images for the PaddleOCR-VL vision encoder', 'create a PaddleOCRVLModel that combines a Siglip-based vision encoder with an Ernie4_5-based text decoder for multimodal tasks', 'create a PaddleOCRProjector that merges spatial patches from the vision encoder into text-embedding dimensions']
```

Usage

```
{'run_paddleocrvl_ocr': 'run PaddleOCR-VL for image OCR by passing images and text prompts through PaddleOCRVLForConditionalGeneration', 'create_paddleocrvl_processor': 'create a PaddleOCRVLProcessor to tokenize text and preprocess images for the PaddleOCR-VL model', 'create_paddleocrvl_image_processor': 'create a PaddleOCRVLImageProcessor to resize and patch images for the PaddleOCR-VL vision encoder', 'create_paddleocrvl_model': 'create a PaddleOCRVLModel that combines a Siglip-based vision encoder with an Ernie4_5-based text decoder for multimodal tasks', 'create_paddleocrvl_projector': 'create a PaddleOCRProjector that merges spatial patches from the vision encoder into text-embedding dimensions'}
```

