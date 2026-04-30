# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mistral3/test_modeling_mistral3.py

Prompts

```
['test the Mistral3ModelTest class that validates Mistral3ForConditionalGeneration and Mistral3Model behavior', 'test the Mistral3Config class initialization and configuration validation with vision and text modality settings', "test the Mistral3ForConditionalGeneration model's text and image-text generation capabilities", 'test the Mistral3IntegrationTest class with real model checkpoint for text-only and image-text generation', 'test batched generation with single and multi-image inputs using Mistral3ForConditionalGeneration', 'test the Mistral3ProcessorTest class that validates PixtralProcessor behavior with Mistral3 spatial_merge_size', 'test the image token filling behavior by verifying the correct number of image tokens are generated for a non-square image', 'test the PixtralProcessor with a single image input and verify input_ids and pixel_values tensor shapes', 'test the PixtralProcessor with multiple images in a single list and verify token expansion for each image', 'test the PixtralProcessor with multiple images across multiple prompt batches with padding enabled', 'test that the processor returns full-length batches when processing multiple image prompts with padding', 'test that special multimodal vision tokens are not truncated when truncation=True is set with a small max_length', 'build a processor configuration dictionary containing chat_template, spatial_merge_size, and patch_size for Mistral3']
```

Usage

```
{'test_mistral3_model': 'test the Mistral3ModelTest class that validates Mistral3ForConditionalGeneration and Mistral3Model behavior', 'test_mistral3_config': 'test the Mistral3Config class initialization and configuration validation with vision and text modality settings', 'test_mistral3_generation': "test the Mistral3ForConditionalGeneration model's text and image-text generation capabilities", 'test_mistral3_integration': 'test the Mistral3IntegrationTest class with real model checkpoint for text-only and image-text generation', 'test_mistral3_batched_generate': 'test batched generation with single and multi-image inputs using Mistral3ForConditionalGeneration'}
```

## File: huggingface_transformers/tests/models/mistral3/test_processing_mistral3.py

Prompts

```
['test the Mistral3ModelTest class that validates Mistral3ForConditionalGeneration and Mistral3Model behavior', 'test the Mistral3Config class initialization and configuration validation with vision and text modality settings', "test the Mistral3ForConditionalGeneration model's text and image-text generation capabilities", 'test the Mistral3IntegrationTest class with real model checkpoint for text-only and image-text generation', 'test batched generation with single and multi-image inputs using Mistral3ForConditionalGeneration', 'test the Mistral3ProcessorTest class that validates PixtralProcessor behavior with Mistral3 spatial_merge_size', 'test the image token filling behavior by verifying the correct number of image tokens are generated for a non-square image', 'test the PixtralProcessor with a single image input and verify input_ids and pixel_values tensor shapes', 'test the PixtralProcessor with multiple images in a single list and verify token expansion for each image', 'test the PixtralProcessor with multiple images across multiple prompt batches with padding enabled', 'test that the processor returns full-length batches when processing multiple image prompts with padding', 'test that special multimodal vision tokens are not truncated when truncation=True is set with a small max_length', 'build a processor configuration dictionary containing chat_template, spatial_merge_size, and patch_size for Mistral3']
```

Usage

```
{'test_Mistral3ProcessorTest': 'test the Mistral3ProcessorTest class that validates PixtralProcessor behavior with Mistral3 spatial_merge_size', 'test_image_token_filling': 'test the image token filling behavior by verifying the correct number of image tokens are generated for a non-square image', 'test_processor_with_single_image': 'test the PixtralProcessor with a single image input and verify input_ids and pixel_values tensor shapes', 'test_processor_with_multiple_images_single_list': 'test the PixtralProcessor with multiple images in a single list and verify token expansion for each image', 'test_processor_with_multiple_images_multiple_lists': 'test the PixtralProcessor with multiple images across multiple prompt batches with padding enabled', 'test_processor_returns_full_length_batches': 'test that the processor returns full-length batches when processing multiple image prompts with padding', 'test_special_mm_token_truncation': 'test that special multimodal vision tokens are not truncated when truncation=True is set with a small max_length', 'prepare_processor_dict': 'build a processor configuration dictionary containing chat_template, spatial_merge_size, and patch_size for Mistral3'}
```

