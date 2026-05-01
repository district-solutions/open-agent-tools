# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/llava/test_configuration_llava.py

Prompts

```
['test the LlavaConfig class saves and reloads default configuration correctly', 'test the LlavaConfig class with Pixtral vision and Mistral text configs saves and reloads correctly', 'test the LlavaConfig class with arbitrary subconfig compositions saves and reloads correctly', 'review the LlavaConfig class for saving and reloading multimodal model configurations', 'summarize the LlavaConfig class capabilities for vision-language model configuration management', 'test the LlavaImageProcessingTest to verify image processor properties like do_pad and do_resize', 'test the pad_to_square method against the original LLaVA implementation with different background colors', 'test the image processor from_dict method with kwargs override for size and crop_size', 'review the LlavaImageProcessingTester class to understand image processing configuration parameters and defaults', 'summarize the LlavaImageProcessingTest class and its test methods for image padding and processor validation', 'test the LlavaForConditionalGeneration model with unit tests for forward pass and generation', 'test LlavaConfig creation and validation with vision and text modalities', 'test multi-image and multi-prompt batched generation with LlavaForConditionalGeneration', 'test single and list vision feature layer configurations in LlavaModel', 'test Pixtral model integration with batched generation and 4-bit quantization', 'test the LlavaProcessor _get_num_multimodal_tokens method with various image sizes', 'test that the LlavaProcessor chat template is saved and loaded correctly', 'test that LlavaProcessor can load various tokenizer checkpoints like llava-gemma-2b', 'test that special multimodal tokens are not truncated when truncation is enabled', 'review the LlavaProcessorTest class setup methods for image processor and tokenizer configuration']
```

Usage

```
{'test_llava_reload': 'test the LlavaConfig class saves and reloads default configuration correctly', 'test_pixtral_reload': 'test the LlavaConfig class with Pixtral vision and Mistral text configs saves and reloads correctly', 'test_arbitrary_reload': 'test the LlavaConfig class with arbitrary subconfig compositions saves and reloads correctly', 'review_LlavaConfig': 'review the LlavaConfig class for saving and reloading multimodal model configurations', 'summarize_LlavaConfig': 'summarize the LlavaConfig class capabilities for vision-language model configuration management'}
```

## File: huggingface_transformers/tests/models/llava/test_image_processing_llava.py

Prompts

```
['test the LlavaConfig class saves and reloads default configuration correctly', 'test the LlavaConfig class with Pixtral vision and Mistral text configs saves and reloads correctly', 'test the LlavaConfig class with arbitrary subconfig compositions saves and reloads correctly', 'review the LlavaConfig class for saving and reloading multimodal model configurations', 'summarize the LlavaConfig class capabilities for vision-language model configuration management', 'test the LlavaImageProcessingTest to verify image processor properties like do_pad and do_resize', 'test the pad_to_square method against the original LLaVA implementation with different background colors', 'test the image processor from_dict method with kwargs override for size and crop_size', 'review the LlavaImageProcessingTester class to understand image processing configuration parameters and defaults', 'summarize the LlavaImageProcessingTest class and its test methods for image padding and processor validation', 'test the LlavaForConditionalGeneration model with unit tests for forward pass and generation', 'test LlavaConfig creation and validation with vision and text modalities', 'test multi-image and multi-prompt batched generation with LlavaForConditionalGeneration', 'test single and list vision feature layer configurations in LlavaModel', 'test Pixtral model integration with batched generation and 4-bit quantization', 'test the LlavaProcessor _get_num_multimodal_tokens method with various image sizes', 'test that the LlavaProcessor chat template is saved and loaded correctly', 'test that LlavaProcessor can load various tokenizer checkpoints like llava-gemma-2b', 'test that special multimodal tokens are not truncated when truncation is enabled', 'review the LlavaProcessorTest class setup methods for image processor and tokenizer configuration']
```

Usage

```
{'test_llava_image_processor_properties': 'test the LlavaImageProcessingTest to verify image processor properties like do_pad and do_resize', 'test_llava_pad_to_square': 'test the pad_to_square method against the original LLaVA implementation with different background colors', 'test_llava_from_dict_with_kwargs': 'test the image processor from_dict method with kwargs override for size and crop_size', 'review_llava_image_processing_tester': 'review the LlavaImageProcessingTester class to understand image processing configuration parameters and defaults', 'summarize_llava_image_processing_test': 'summarize the LlavaImageProcessingTest class and its test methods for image padding and processor validation'}
```

## File: huggingface_transformers/tests/models/llava/test_modeling_llava.py

Prompts

```
['test the LlavaConfig class saves and reloads default configuration correctly', 'test the LlavaConfig class with Pixtral vision and Mistral text configs saves and reloads correctly', 'test the LlavaConfig class with arbitrary subconfig compositions saves and reloads correctly', 'review the LlavaConfig class for saving and reloading multimodal model configurations', 'summarize the LlavaConfig class capabilities for vision-language model configuration management', 'test the LlavaImageProcessingTest to verify image processor properties like do_pad and do_resize', 'test the pad_to_square method against the original LLaVA implementation with different background colors', 'test the image processor from_dict method with kwargs override for size and crop_size', 'review the LlavaImageProcessingTester class to understand image processing configuration parameters and defaults', 'summarize the LlavaImageProcessingTest class and its test methods for image padding and processor validation', 'test the LlavaForConditionalGeneration model with unit tests for forward pass and generation', 'test LlavaConfig creation and validation with vision and text modalities', 'test multi-image and multi-prompt batched generation with LlavaForConditionalGeneration', 'test single and list vision feature layer configurations in LlavaModel', 'test Pixtral model integration with batched generation and 4-bit quantization', 'test the LlavaProcessor _get_num_multimodal_tokens method with various image sizes', 'test that the LlavaProcessor chat template is saved and loaded correctly', 'test that LlavaProcessor can load various tokenizer checkpoints like llava-gemma-2b', 'test that special multimodal tokens are not truncated when truncation is enabled', 'review the LlavaProcessorTest class setup methods for image processor and tokenizer configuration']
```

Usage

```
{'test_LlavaForConditionalGeneration_model': 'test the LlavaForConditionalGeneration model with unit tests for forward pass and generation', 'test_LlavaVisionText2TextModelTester_config': 'test LlavaConfig creation and validation with vision and text modalities', 'test_multi_image_handling': 'test multi-image and multi-prompt batched generation with LlavaForConditionalGeneration', 'test_vision_feature_layers': 'test single and list vision feature layer configurations in LlavaModel', 'test_pixtral_model_integration': 'test Pixtral model integration with batched generation and 4-bit quantization'}
```

## File: huggingface_transformers/tests/models/llava/test_processing_llava.py

Prompts

```
['test the LlavaConfig class saves and reloads default configuration correctly', 'test the LlavaConfig class with Pixtral vision and Mistral text configs saves and reloads correctly', 'test the LlavaConfig class with arbitrary subconfig compositions saves and reloads correctly', 'review the LlavaConfig class for saving and reloading multimodal model configurations', 'summarize the LlavaConfig class capabilities for vision-language model configuration management', 'test the LlavaImageProcessingTest to verify image processor properties like do_pad and do_resize', 'test the pad_to_square method against the original LLaVA implementation with different background colors', 'test the image processor from_dict method with kwargs override for size and crop_size', 'review the LlavaImageProcessingTester class to understand image processing configuration parameters and defaults', 'summarize the LlavaImageProcessingTest class and its test methods for image padding and processor validation', 'test the LlavaForConditionalGeneration model with unit tests for forward pass and generation', 'test LlavaConfig creation and validation with vision and text modalities', 'test multi-image and multi-prompt batched generation with LlavaForConditionalGeneration', 'test single and list vision feature layer configurations in LlavaModel', 'test Pixtral model integration with batched generation and 4-bit quantization', 'test the LlavaProcessor _get_num_multimodal_tokens method with various image sizes', 'test that the LlavaProcessor chat template is saved and loaded correctly', 'test that LlavaProcessor can load various tokenizer checkpoints like llava-gemma-2b', 'test that special multimodal tokens are not truncated when truncation is enabled', 'review the LlavaProcessorTest class setup methods for image processor and tokenizer configuration']
```

Usage

```
{'test_llava_processor_vision_tokens': 'test the LlavaProcessor _get_num_multimodal_tokens method with various image sizes', 'test_llava_processor_chat_template': 'test that the LlavaProcessor chat template is saved and loaded correctly', 'test_llava_processor_tokenizer_loading': 'test that LlavaProcessor can load various tokenizer checkpoints like llava-gemma-2b', 'test_llava_processor_truncation': 'test that special multimodal tokens are not truncated when truncation is enabled', 'review_llava_processor_test_class': 'review the LlavaProcessorTest class setup methods for image processor and tokenizer configuration'}
```

