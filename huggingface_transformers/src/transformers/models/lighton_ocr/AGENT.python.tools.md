# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/lighton_ocr/modeling_lighton_ocr.py

Prompts

```
['build a LightOnOcrForConditionalGeneration model for image-to-text multimodal generation', 'create a LightOnOcrModel combining a vision encoder and language model without a language modeling head', 'extract and project image features from a vision encoder using LightOnOcrModel.get_image_features', 'build a LightOnOcrMultiModalProjector to merge patches and project vision features into text embedding space', 'create a LightOnOcrRMSNorm layer equivalent to T5LayerNorm for hidden state normalization', 'create a LightOnOcrConfig with custom vision and text settings for the LightOnOCR-1B model', 'build a LightOnOcrProcessor that tokenizes text prompts and processes input images for OCR', 'run the LightOnOcrModel forward pass to extract image features and generate language outputs', 'generate text from LightOnOcrForConditionalGeneration conditioned on input images', 'create a LightOnOcrProcessor instance with image_processor, tokenizer, patch_size, and spatial_merge_size parameters', 'call the LightOnOcrProcessor to process images and text, replacing image tokens with expanded token sequences', 'compute the number of image tokens given an image size and patch size using _num_image_tokens', 'get the target image dimensions after resizing to fit within a longest edge constraint and patch size alignment', 'get the number of multimodal tokens for given image sizes using _get_num_multimodal_tokens']
```

Usage

```
{'build_conditional_generation_model': 'build a LightOnOcrForConditionalGeneration model for image-to-text multimodal generation', 'create_multimodal_model': 'create a LightOnOcrModel combining a vision encoder and language model without a language modeling head', 'extract_image_features': 'extract and project image features from a vision encoder using LightOnOcrModel.get_image_features', 'build_multimodal_projector': 'build a LightOnOcrMultiModalProjector to merge patches and project vision features into text embedding space', 'create_rms_norm_layer': 'create a LightOnOcrRMSNorm layer equivalent to T5LayerNorm for hidden state normalization'}
```

## File: huggingface_transformers/src/transformers/models/lighton_ocr/modular_lighton_ocr.py

Prompts

```
['build a LightOnOcrForConditionalGeneration model for image-to-text multimodal generation', 'create a LightOnOcrModel combining a vision encoder and language model without a language modeling head', 'extract and project image features from a vision encoder using LightOnOcrModel.get_image_features', 'build a LightOnOcrMultiModalProjector to merge patches and project vision features into text embedding space', 'create a LightOnOcrRMSNorm layer equivalent to T5LayerNorm for hidden state normalization', 'create a LightOnOcrConfig with custom vision and text settings for the LightOnOCR-1B model', 'build a LightOnOcrProcessor that tokenizes text prompts and processes input images for OCR', 'run the LightOnOcrModel forward pass to extract image features and generate language outputs', 'generate text from LightOnOcrForConditionalGeneration conditioned on input images', 'create a LightOnOcrProcessor instance with image_processor, tokenizer, patch_size, and spatial_merge_size parameters', 'call the LightOnOcrProcessor to process images and text, replacing image tokens with expanded token sequences', 'compute the number of image tokens given an image size and patch size using _num_image_tokens', 'get the target image dimensions after resizing to fit within a longest edge constraint and patch size alignment', 'get the number of multimodal tokens for given image sizes using _get_num_multimodal_tokens']
```

Usage

```
{'create_lighton_ocr_config': 'create a LightOnOcrConfig with custom vision and text settings for the LightOnOCR-1B model', 'build_lighton_ocr_processor': 'build a LightOnOcrProcessor that tokenizes text prompts and processes input images for OCR', 'run_lighton_ocr_forward': 'run the LightOnOcrModel forward pass to extract image features and generate language outputs', 'generate_lighton_ocr_text': 'generate text from LightOnOcrForConditionalGeneration conditioned on input images', 'build_multimodal_projector': 'build a LightOnOcrMultiModalProjector that projects vision features into the text embedding space'}
```

## File: huggingface_transformers/src/transformers/models/lighton_ocr/processing_lighton_ocr.py

Prompts

```
['build a LightOnOcrForConditionalGeneration model for image-to-text multimodal generation', 'create a LightOnOcrModel combining a vision encoder and language model without a language modeling head', 'extract and project image features from a vision encoder using LightOnOcrModel.get_image_features', 'build a LightOnOcrMultiModalProjector to merge patches and project vision features into text embedding space', 'create a LightOnOcrRMSNorm layer equivalent to T5LayerNorm for hidden state normalization', 'create a LightOnOcrConfig with custom vision and text settings for the LightOnOCR-1B model', 'build a LightOnOcrProcessor that tokenizes text prompts and processes input images for OCR', 'run the LightOnOcrModel forward pass to extract image features and generate language outputs', 'generate text from LightOnOcrForConditionalGeneration conditioned on input images', 'create a LightOnOcrProcessor instance with image_processor, tokenizer, patch_size, and spatial_merge_size parameters', 'call the LightOnOcrProcessor to process images and text, replacing image tokens with expanded token sequences', 'compute the number of image tokens given an image size and patch size using _num_image_tokens', 'get the target image dimensions after resizing to fit within a longest edge constraint and patch size alignment', 'get the number of multimodal tokens for given image sizes using _get_num_multimodal_tokens']
```

Usage

```
{'create_lighton_ocr_processor': 'create a LightOnOcrProcessor instance with image_processor, tokenizer, patch_size, and spatial_merge_size parameters', 'call_processor_with_images_and_text': 'call the LightOnOcrProcessor to process images and text, replacing image tokens with expanded token sequences', 'compute_image_tokens_from_size': 'compute the number of image tokens given an image size and patch size using _num_image_tokens', 'get_resize_output_image_size': 'get the target image dimensions after resizing to fit within a longest edge constraint and patch size alignment', 'get_num_multimodal_tokens': 'get the number of multimodal tokens for given image sizes using _get_num_multimodal_tokens'}
```

