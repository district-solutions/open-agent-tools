# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/idefics2/test_modeling_idefics2.py

Prompts

```
['test the Idefics2Model class forward pass with vision and text inputs using small configs', 'test resizing token embeddings for Idefics2Model with vocabulary size changes and pad_to_multiple_of', 'test Idefics2Config initialization with vision, perceiver, and text configuration dictionaries', 'test Idefics2ForConditionalGeneration model generation with image and text inputs', 'test Idefics2ForConditionalGeneration integration by generating text from images with the 8b-base model', 'test Idefics2Processor processes interleaved image-text prompts with image splitting disabled', 'test Idefics2Processor processes interleaved image-text prompts with image splitting enabled', 'test Idefics2Processor apply_chat_template renders messages with images and text into prompt format', 'test Idefics2Processor raises ValueError for mismatched image-text inputs', 'test Idefics2Processor handles add_special_tokens flag correctly in processor calls']
```

Usage

```
{'test_Idefics2Model_forward_pass': 'test the Idefics2Model class forward pass with vision and text inputs using small configs', 'test_resize_tokens_embeddings': 'test resizing token embeddings for Idefics2Model with vocabulary size changes and pad_to_multiple_of', 'test_Idefics2Config_initialization': 'test Idefics2Config initialization with vision, perceiver, and text configuration dictionaries', 'test_Idefics2ForConditionalGeneration_generation': 'test Idefics2ForConditionalGeneration model generation with image and text inputs', 'test_integration_idefics2_generate': 'test Idefics2ForConditionalGeneration integration by generating text from images with the 8b-base model'}
```

## File: huggingface_transformers/tests/models/idefics2/test_processing_idefics2.py

Prompts

```
['test the Idefics2Model class forward pass with vision and text inputs using small configs', 'test resizing token embeddings for Idefics2Model with vocabulary size changes and pad_to_multiple_of', 'test Idefics2Config initialization with vision, perceiver, and text configuration dictionaries', 'test Idefics2ForConditionalGeneration model generation with image and text inputs', 'test Idefics2ForConditionalGeneration integration by generating text from images with the 8b-base model', 'test Idefics2Processor processes interleaved image-text prompts with image splitting disabled', 'test Idefics2Processor processes interleaved image-text prompts with image splitting enabled', 'test Idefics2Processor apply_chat_template renders messages with images and text into prompt format', 'test Idefics2Processor raises ValueError for mismatched image-text inputs', 'test Idefics2Processor handles add_special_tokens flag correctly in processor calls']
```

Usage

```
{'test_Idefics2Processor_interleaved_images_no_splitting': 'test Idefics2Processor processes interleaved image-text prompts with image splitting disabled', 'test_Idefics2Processor_interleaved_images_with_splitting': 'test Idefics2Processor processes interleaved image-text prompts with image splitting enabled', 'test_Idefics2Processor_apply_chat_template': 'test Idefics2Processor apply_chat_template renders messages with images and text into prompt format', 'test_Idefics2Processor_error_handling': 'test Idefics2Processor raises ValueError for mismatched image-text inputs', 'test_Idefics2Processor_special_tokens': 'test Idefics2Processor handles add_special_tokens flag correctly in processor calls'}
```

