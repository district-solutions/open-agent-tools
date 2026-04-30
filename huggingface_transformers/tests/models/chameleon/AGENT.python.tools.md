# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/chameleon/test_image_processing_chameleon.py

Prompts

```
['test the ChameleonImageProcessingTest class verifies image processor attributes like do_resize, size, crop_size, and normalization settings', 'test the ChameleonImageProcessingTest class constructs image processors from a dict and overridden kwargs for size and crop_size', 'test the ChameleonImageProcessingTest class processes PIL images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes NumPy array images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes PyTorch tensor images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonModel class with dummy config and input tensors for forward pass validation', 'test the ChameleonVision2SeqModelTest class with pixel values and image tokens for vision-language forward pass', 'test the ChameleonConfig class using ConfigTester for common configuration validation', 'test the ChameleonForConditionalGeneration 7b model with 4-bit quantization for image-text generation', 'test the ChameleonForConditionalGeneration model with multiple images and multiple image tokens in a single prompt', 'test the ChameleonProcessor class and its multimodal text-image processing capabilities', 'test that special vision tokens do not get truncated when truncation is enabled with max_length', 'test the _get_num_multimodal_tokens helper that returns num_image_tokens and num_image_patches for given image sizes', 'setup a tokenizer for Chameleon with special multimodal tokens like <image>, <racm3:break>, and <eoss>', 'prepare a processor dictionary configuration with image_seq_length parameter for Chameleon']
```

Usage

```
{'test_image_processor_properties': 'test the ChameleonImageProcessingTest class verifies image processor attributes like do_resize, size, crop_size, and normalization settings', 'test_image_processor_from_dict_with_kwargs': 'test the ChameleonImageProcessingTest class constructs image processors from a dict and overridden kwargs for size and crop_size', 'test_call_pil': 'test the ChameleonImageProcessingTest class processes PIL images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test_call_numpy': 'test the ChameleonImageProcessingTest class processes NumPy array images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test_call_pytorch': 'test the ChameleonImageProcessingTest class processes PyTorch tensor images and verifies output pixel value tensor shapes for batched and unbatched inputs'}
```

## File: huggingface_transformers/tests/models/chameleon/test_modeling_chameleon.py

Prompts

```
['test the ChameleonImageProcessingTest class verifies image processor attributes like do_resize, size, crop_size, and normalization settings', 'test the ChameleonImageProcessingTest class constructs image processors from a dict and overridden kwargs for size and crop_size', 'test the ChameleonImageProcessingTest class processes PIL images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes NumPy array images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes PyTorch tensor images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonModel class with dummy config and input tensors for forward pass validation', 'test the ChameleonVision2SeqModelTest class with pixel values and image tokens for vision-language forward pass', 'test the ChameleonConfig class using ConfigTester for common configuration validation', 'test the ChameleonForConditionalGeneration 7b model with 4-bit quantization for image-text generation', 'test the ChameleonForConditionalGeneration model with multiple images and multiple image tokens in a single prompt', 'test the ChameleonProcessor class and its multimodal text-image processing capabilities', 'test that special vision tokens do not get truncated when truncation is enabled with max_length', 'test the _get_num_multimodal_tokens helper that returns num_image_tokens and num_image_patches for given image sizes', 'setup a tokenizer for Chameleon with special multimodal tokens like <image>, <racm3:break>, and <eoss>', 'prepare a processor dictionary configuration with image_seq_length parameter for Chameleon']
```

Usage

```
{'test_chameleon_model': 'test the ChameleonModel class with dummy config and input tensors for forward pass validation', 'test_chameleon_vision2seq_model': 'test the ChameleonVision2SeqModelTest class with pixel values and image tokens for vision-language forward pass', 'test_chameleon_config': 'test the ChameleonConfig class using ConfigTester for common configuration validation', 'test_chameleon_integration_7b': 'test the ChameleonForConditionalGeneration 7b model with 4-bit quantization for image-text generation', 'test_chameleon_multi_image': 'test the ChameleonForConditionalGeneration model with multiple images and multiple image tokens in a single prompt'}
```

## File: huggingface_transformers/tests/models/chameleon/test_processing_chameleon.py

Prompts

```
['test the ChameleonImageProcessingTest class verifies image processor attributes like do_resize, size, crop_size, and normalization settings', 'test the ChameleonImageProcessingTest class constructs image processors from a dict and overridden kwargs for size and crop_size', 'test the ChameleonImageProcessingTest class processes PIL images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes NumPy array images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonImageProcessingTest class processes PyTorch tensor images and verifies output pixel value tensor shapes for batched and unbatched inputs', 'test the ChameleonModel class with dummy config and input tensors for forward pass validation', 'test the ChameleonVision2SeqModelTest class with pixel values and image tokens for vision-language forward pass', 'test the ChameleonConfig class using ConfigTester for common configuration validation', 'test the ChameleonForConditionalGeneration 7b model with 4-bit quantization for image-text generation', 'test the ChameleonForConditionalGeneration model with multiple images and multiple image tokens in a single prompt', 'test the ChameleonProcessor class and its multimodal text-image processing capabilities', 'test that special vision tokens do not get truncated when truncation is enabled with max_length', 'test the _get_num_multimodal_tokens helper that returns num_image_tokens and num_image_patches for given image sizes', 'setup a tokenizer for Chameleon with special multimodal tokens like <image>, <racm3:break>, and <eoss>', 'prepare a processor dictionary configuration with image_seq_length parameter for Chameleon']
```

Usage

```
{'test_chameleon_processor': 'test the ChameleonProcessor class and its multimodal text-image processing capabilities', 'test_special_mm_token_truncation': 'test that special vision tokens do not get truncated when truncation is enabled with max_length', 'test_get_num_vision_tokens': 'test the _get_num_multimodal_tokens helper that returns num_image_tokens and num_image_patches for given image sizes', 'setup_tokenizer_chameleon': 'setup a tokenizer for Chameleon with special multimodal tokens like <image>, <racm3:break>, and <eoss>', 'prepare_processor_dict': 'prepare a processor dictionary configuration with image_seq_length parameter for Chameleon'}
```

