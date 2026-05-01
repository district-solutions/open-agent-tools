# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/llava_next/test_image_processing_llava_next.py

Prompts

```
['test the select_best_resolution function to find the best resolution from a list of possible resolutions for a given aspect ratio', 'create a LlavaNextImageProcessingTester instance with configurable batch size, image channels, resolution, and preprocessing options', 'test the LlavaNext image processor has all expected properties like do_resize, size, crop_size, do_normalize, image_mean, image_std, and image_grid_pinpoints', 'test the LlavaNext image processor with PIL images in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNext image processor with numpy arrays in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNextForConditionalGeneration model with gradient checkpointing and flash attention', 'run integration test for LlavaNext model with 4-bit quantization using BitsAndBytesConfig', 'test batch image generation with LlavaNext model using multiple images and prompts', 'test LlavaNext model generation with batched images of different resolutions', 'test granite vision model using LlavaNext architecture with siglip encoder', 'test the LlavaNextProcessorTest class that validates LlavaNextProcessor behavior using ProcessorTesterMixin', 'test the _setup_tokenizer method that configures a Llama tokenizer with image token and pad token for LlavaNextProcessor', 'test the _setup_test_attributes method that extracts and stores the image token from a loaded processor', 'test the _get_num_multimodal_tokens method that computes the number of vision tokens for varying image sizes', "test the processor's image token filling by running a multimodal input through LlavaNextProcessor and counting image tokens"]
```

Usage

```
{'test_select_best_resolution': 'test the select_best_resolution function to find the best resolution from a list of possible resolutions for a given aspect ratio', 'create_LlavaNextImageProcessingTester': 'create a LlavaNextImageProcessingTester instance with configurable batch size, image channels, resolution, and preprocessing options', 'test_image_processor_properties': 'test the LlavaNext image processor has all expected properties like do_resize, size, crop_size, do_normalize, image_mean, image_std, and image_grid_pinpoints', 'test_call_pil': 'test the LlavaNext image processor with PIL images in both batched and unbatched modes returning correct pixel value shapes', 'test_call_numpy': 'test the LlavaNext image processor with numpy arrays in both batched and unbatched modes returning correct pixel value shapes'}
```

## File: huggingface_transformers/tests/models/llava_next/test_modeling_llava_next.py

Prompts

```
['test the select_best_resolution function to find the best resolution from a list of possible resolutions for a given aspect ratio', 'create a LlavaNextImageProcessingTester instance with configurable batch size, image channels, resolution, and preprocessing options', 'test the LlavaNext image processor has all expected properties like do_resize, size, crop_size, do_normalize, image_mean, image_std, and image_grid_pinpoints', 'test the LlavaNext image processor with PIL images in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNext image processor with numpy arrays in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNextForConditionalGeneration model with gradient checkpointing and flash attention', 'run integration test for LlavaNext model with 4-bit quantization using BitsAndBytesConfig', 'test batch image generation with LlavaNext model using multiple images and prompts', 'test LlavaNext model generation with batched images of different resolutions', 'test granite vision model using LlavaNext architecture with siglip encoder', 'test the LlavaNextProcessorTest class that validates LlavaNextProcessor behavior using ProcessorTesterMixin', 'test the _setup_tokenizer method that configures a Llama tokenizer with image token and pad token for LlavaNextProcessor', 'test the _setup_test_attributes method that extracts and stores the image token from a loaded processor', 'test the _get_num_multimodal_tokens method that computes the number of vision tokens for varying image sizes', "test the processor's image token filling by running a multimodal input through LlavaNextProcessor and counting image tokens"]
```

Usage

```
{'test_llava_next_model': 'test the LlavaNextForConditionalGeneration model with gradient checkpointing and flash attention', 'run_integration_test': 'run integration test for LlavaNext model with 4-bit quantization using BitsAndBytesConfig', 'test_batch_generation': 'test batch image generation with LlavaNext model using multiple images and prompts', 'test_different_resolutions': 'test LlavaNext model generation with batched images of different resolutions', 'test_granite_vision': 'test granite vision model using LlavaNext architecture with siglip encoder'}
```

## File: huggingface_transformers/tests/models/llava_next/test_processing_llava_next.py

Prompts

```
['test the select_best_resolution function to find the best resolution from a list of possible resolutions for a given aspect ratio', 'create a LlavaNextImageProcessingTester instance with configurable batch size, image channels, resolution, and preprocessing options', 'test the LlavaNext image processor has all expected properties like do_resize, size, crop_size, do_normalize, image_mean, image_std, and image_grid_pinpoints', 'test the LlavaNext image processor with PIL images in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNext image processor with numpy arrays in both batched and unbatched modes returning correct pixel value shapes', 'test the LlavaNextForConditionalGeneration model with gradient checkpointing and flash attention', 'run integration test for LlavaNext model with 4-bit quantization using BitsAndBytesConfig', 'test batch image generation with LlavaNext model using multiple images and prompts', 'test LlavaNext model generation with batched images of different resolutions', 'test granite vision model using LlavaNext architecture with siglip encoder', 'test the LlavaNextProcessorTest class that validates LlavaNextProcessor behavior using ProcessorTesterMixin', 'test the _setup_tokenizer method that configures a Llama tokenizer with image token and pad token for LlavaNextProcessor', 'test the _setup_test_attributes method that extracts and stores the image token from a loaded processor', 'test the _get_num_multimodal_tokens method that computes the number of vision tokens for varying image sizes', "test the processor's image token filling by running a multimodal input through LlavaNextProcessor and counting image tokens"]
```

Usage

```
{'test_LlavaNextProcessorTest': 'test the LlavaNextProcessorTest class that validates LlavaNextProcessor behavior using ProcessorTesterMixin', 'test_setup_tokenizer': 'test the _setup_tokenizer method that configures a Llama tokenizer with image token and pad token for LlavaNextProcessor', 'test_setup_test_attributes': 'test the _setup_test_attributes method that extracts and stores the image token from a loaded processor', 'test_get_num_vision_tokens': 'test the _get_num_multimodal_tokens method that computes the number of vision tokens for varying image sizes', 'test_image_token_filling': "test the processor's image token filling by running a multimodal input through LlavaNextProcessor and counting image tokens"}
```

