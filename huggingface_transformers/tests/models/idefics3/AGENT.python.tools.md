# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/idefics3/test_image_processing_idefics3.py

Prompts

```
['test the Idefics3ImageProcessor properties like do_resize, do_normalize, and do_image_splitting attributes', 'test the Idefics3ImageProcessor with numpy array inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PIL image inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PyTorch tensor inputs in batched and unbatched modes', 'test the get_number_of_image_patches method with various height, width, and splitting configurations', 'test the Idefics3Config vision and text configuration with custom hidden sizes and attention heads', 'test resizing token embeddings for Idefics3Model with larger and smaller vocabulary sizes', 'test resizing untied token embeddings for Idefics3Model with separate output embeddings', 'run integration test for Idefics3ForConditionalGeneration with image and text inputs using the pretrained 8B Llama3 model', 'run 4-bit quantized integration test for Idefics3ForConditionalGeneration using BitsAndBytesConfig with multiple images', 'test the Idefics3Processor with interleaved image and text prompts using image splitting enabled', 'test the apply_chat_template method with mixed text and image content messages', 'test the Idefics3Processor with text-only input to verify correct tokenization without images', 'test that Idefics3Processor raises ValueError when image tokens are present but no images provided', 'test the _get_num_multimodal_tokens helper matches processor call output for various image sizes']
```

Usage

```
{'test_image_processor_properties': 'test the Idefics3ImageProcessor properties like do_resize, do_normalize, and do_image_splitting attributes', 'test_call_numpy': 'test the Idefics3ImageProcessor with numpy array inputs in batched and unbatched modes', 'test_call_pil': 'test the Idefics3ImageProcessor with PIL image inputs in batched and unbatched modes', 'test_call_pytorch': 'test the Idefics3ImageProcessor with PyTorch tensor inputs in batched and unbatched modes', 'test_get_num_patches_without_images': 'test the get_number_of_image_patches method with various height, width, and splitting configurations'}
```

## File: huggingface_transformers/tests/models/idefics3/test_modeling_idefics3.py

Prompts

```
['test the Idefics3ImageProcessor properties like do_resize, do_normalize, and do_image_splitting attributes', 'test the Idefics3ImageProcessor with numpy array inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PIL image inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PyTorch tensor inputs in batched and unbatched modes', 'test the get_number_of_image_patches method with various height, width, and splitting configurations', 'test the Idefics3Config vision and text configuration with custom hidden sizes and attention heads', 'test resizing token embeddings for Idefics3Model with larger and smaller vocabulary sizes', 'test resizing untied token embeddings for Idefics3Model with separate output embeddings', 'run integration test for Idefics3ForConditionalGeneration with image and text inputs using the pretrained 8B Llama3 model', 'run 4-bit quantized integration test for Idefics3ForConditionalGeneration using BitsAndBytesConfig with multiple images', 'test the Idefics3Processor with interleaved image and text prompts using image splitting enabled', 'test the apply_chat_template method with mixed text and image content messages', 'test the Idefics3Processor with text-only input to verify correct tokenization without images', 'test that Idefics3Processor raises ValueError when image tokens are present but no images provided', 'test the _get_num_multimodal_tokens helper matches processor call output for various image sizes']
```

Usage

```
{'test_idefics3_model_config': 'test the Idefics3Config vision and text configuration with custom hidden sizes and attention heads', 'test_idefics3_resize_embeddings': 'test resizing token embeddings for Idefics3Model with larger and smaller vocabulary sizes', 'test_idefics3_resize_embeddings_untied': 'test resizing untied token embeddings for Idefics3Model with separate output embeddings', 'run_idefics3_integration_test': 'run integration test for Idefics3ForConditionalGeneration with image and text inputs using the pretrained 8B Llama3 model', 'run_idefics3_4bit_integration_test': 'run 4-bit quantized integration test for Idefics3ForConditionalGeneration using BitsAndBytesConfig with multiple images'}
```

## File: huggingface_transformers/tests/models/idefics3/test_processing_idefics3.py

Prompts

```
['test the Idefics3ImageProcessor properties like do_resize, do_normalize, and do_image_splitting attributes', 'test the Idefics3ImageProcessor with numpy array inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PIL image inputs in batched and unbatched modes', 'test the Idefics3ImageProcessor with PyTorch tensor inputs in batched and unbatched modes', 'test the get_number_of_image_patches method with various height, width, and splitting configurations', 'test the Idefics3Config vision and text configuration with custom hidden sizes and attention heads', 'test resizing token embeddings for Idefics3Model with larger and smaller vocabulary sizes', 'test resizing untied token embeddings for Idefics3Model with separate output embeddings', 'run integration test for Idefics3ForConditionalGeneration with image and text inputs using the pretrained 8B Llama3 model', 'run 4-bit quantized integration test for Idefics3ForConditionalGeneration using BitsAndBytesConfig with multiple images', 'test the Idefics3Processor with interleaved image and text prompts using image splitting enabled', 'test the apply_chat_template method with mixed text and image content messages', 'test the Idefics3Processor with text-only input to verify correct tokenization without images', 'test that Idefics3Processor raises ValueError when image tokens are present but no images provided', 'test the _get_num_multimodal_tokens helper matches processor call output for various image sizes']
```

Usage

```
{'test_Idefics3Processor_interleaved_images': 'test the Idefics3Processor with interleaved image and text prompts using image splitting enabled', 'test_Idefics3Processor_chat_template': 'test the apply_chat_template method with mixed text and image content messages', 'test_Idefics3Processor_text_only': 'test the Idefics3Processor with text-only input to verify correct tokenization without images', 'test_Idefics3Processor_missing_images_error': 'test that Idefics3Processor raises ValueError when image tokens are present but no images provided', 'test_Idefics3Processor_multimodal_tokens': 'test the _get_num_multimodal_tokens helper matches processor call output for various image sizes'}
```

