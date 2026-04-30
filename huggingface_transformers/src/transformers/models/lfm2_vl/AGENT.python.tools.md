# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/lfm2_vl/image_processing_lfm2_vl.py

Prompts

```
['create an Lfm2VlImageProcessor instance with configurable tile splitting, patch sizing, and normalization settings', 'resize and split large images into a grid of tiles with optional thumbnail for multi-scale processing', 'smart-resize image dimensions to meet minimum and maximum token constraints while preserving aspect ratio', 'crop a high-resolution image into a grid of patches with configurable tile count and aspect ratio matching', 'convert a batch of images into flattened patch tensors for vision encoder input', 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel and text inputs', 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space', 'create an Lfm2VlProcessor instance with an image processor and tokenizer for multimodal text-image processing', 'call the Lfm2VlProcessor with images and text to tokenize and encode multimodal inputs for model consumption', 'expand text with image placeholders by replacing image tokens with tile-based token sequences and optional thumbnails', 'build an expanded token string for a single image including row-column markers, tile tokens, and optional thumbnail', 'compute the number of tokens per tile and per image for a given image size, tile size, and encoder patch configuration']
```

Usage

```
{'create_Lfm2VlImageProcessor': 'create an Lfm2VlImageProcessor instance with configurable tile splitting, patch sizing, and normalization settings', 'resize_and_split_images': 'resize and split large images into a grid of tiles with optional thumbnail for multi-scale processing', 'smart_resize_image_dimensions': 'smart-resize image dimensions to meet minimum and maximum token constraints while preserving aspect ratio', 'crop_image_to_patches': 'crop a high-resolution image into a grid of patches with configurable tile count and aspect ratio matching', 'convert_image_to_patches': 'convert a batch of images into flattened patch tensors for vision encoder input'}
```

## File: huggingface_transformers/src/transformers/models/lfm2_vl/modeling_lfm2_vl.py

Prompts

```
['create an Lfm2VlImageProcessor instance with configurable tile splitting, patch sizing, and normalization settings', 'resize and split large images into a grid of tiles with optional thumbnail for multi-scale processing', 'smart-resize image dimensions to meet minimum and maximum token constraints while preserving aspect ratio', 'crop a high-resolution image into a grid of patches with configurable tile count and aspect ratio matching', 'convert a batch of images into flattened patch tensors for vision encoder input', 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel and text inputs', 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space', 'create an Lfm2VlProcessor instance with an image processor and tokenizer for multimodal text-image processing', 'call the Lfm2VlProcessor with images and text to tokenize and encode multimodal inputs for model consumption', 'expand text with image placeholders by replacing image tokens with tile-based token sequences and optional thumbnails', 'build an expanded token string for a single image including row-column markers, tile tokens, and optional thumbnail', 'compute the number of tokens per tile and per image for a given image size, tile size, and encoder patch configuration']
```

Usage

```
{'create_lfm2vl_model': 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel and text inputs', 'build_lfm2vl_conditional_lm': 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run_lfm2vl_forward': 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get_image_features_lfm2vl': 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review_lfm2vl_multi_modal_projector': 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space'}
```

## File: huggingface_transformers/src/transformers/models/lfm2_vl/modular_lfm2_vl.py

Prompts

```
['create an Lfm2VlImageProcessor instance with configurable tile splitting, patch sizing, and normalization settings', 'resize and split large images into a grid of tiles with optional thumbnail for multi-scale processing', 'smart-resize image dimensions to meet minimum and maximum token constraints while preserving aspect ratio', 'crop a high-resolution image into a grid of patches with configurable tile count and aspect ratio matching', 'convert a batch of images into flattened patch tensors for vision encoder input', 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel and text inputs', 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space', 'create an Lfm2VlProcessor instance with an image processor and tokenizer for multimodal text-image processing', 'call the Lfm2VlProcessor with images and text to tokenize and encode multimodal inputs for model consumption', 'expand text with image placeholders by replacing image tokens with tile-based token sequences and optional thumbnails', 'build an expanded token string for a single image including row-column markers, tile tokens, and optional thumbnail', 'compute the number of tokens per tile and per image for a given image size, tile size, and encoder patch configuration']
```

Usage

```
{'create_lfm2vl_model': 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel inputs', 'build_lfm2vl_conditional_lm': 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run_lfm2vl_forward': 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get_image_features_lfm2vl': 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review_lfm2vl_multi_modal_projector': 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space'}
```

## File: huggingface_transformers/src/transformers/models/lfm2_vl/processing_lfm2_vl.py

Prompts

```
['create an Lfm2VlImageProcessor instance with configurable tile splitting, patch sizing, and normalization settings', 'resize and split large images into a grid of tiles with optional thumbnail for multi-scale processing', 'smart-resize image dimensions to meet minimum and maximum token constraints while preserving aspect ratio', 'crop a high-resolution image into a grid of patches with configurable tile count and aspect ratio matching', 'convert a batch of images into flattened patch tensors for vision encoder input', 'create an Lfm2VlModel instance for multimodal vision-language processing with pixel and text inputs', 'build an Lfm2VlForConditionalGeneration model for image-text conditional text generation', 'run the Lfm2VlForConditionalGeneration forward pass with input_ids, pixel_values, and labels', 'get image features from the vision tower and apply multimodal projection via Lfm2VlModel.get_image_features', 'review the Lfm2VlMultiModalProjector class that projects vision tower features into text embedding space', 'create an Lfm2VlProcessor instance with an image processor and tokenizer for multimodal text-image processing', 'call the Lfm2VlProcessor with images and text to tokenize and encode multimodal inputs for model consumption', 'expand text with image placeholders by replacing image tokens with tile-based token sequences and optional thumbnails', 'build an expanded token string for a single image including row-column markers, tile tokens, and optional thumbnail', 'compute the number of tokens per tile and per image for a given image size, tile size, and encoder patch configuration']
```

Usage

```
{'create_Lfm2VlProcessor': 'create an Lfm2VlProcessor instance with an image processor and tokenizer for multimodal text-image processing', 'call_Lfm2VlProcessor': 'call the Lfm2VlProcessor with images and text to tokenize and encode multimodal inputs for model consumption', 'expand_text_with_placeholders': 'expand text with image placeholders by replacing image tokens with tile-based token sequences and optional thumbnails', 'build_image_tokens': 'build an expanded token string for a single image including row-column markers, tile tokens, and optional thumbnail', 'get_image_num_tokens': 'compute the number of tokens per tile and per image for a given image size, tile size, and encoder patch configuration'}
```

