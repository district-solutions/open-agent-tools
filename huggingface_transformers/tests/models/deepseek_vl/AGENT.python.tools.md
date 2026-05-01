# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/deepseek_vl/test_image_processing_deepseek_vl.py

Prompts

```
['test the DeepseekVL image processor has required properties like image_mean and do_resize', 'test creating a DeepseekVL image processor from a dictionary with custom kwargs', 'create a configuration dictionary for the DeepseekVL image processor with normalization settings', 'generate test image inputs with configurable batch size and resolution for DeepseekVL', 'calculate the expected output shape for processed DeepseekVL images', 'test the DeepseekVLIntegrationTest.test_model_text_generation method to verify single-image text generation produces expected output', 'test the DeepseekVLIntegrationTest.test_model_text_generation_batched method to verify batched multi-input text generation with padding', 'test the DeepseekVLIntegrationTest.test_model_text_generation_with_multi_image method to verify generation with multiple images in one prompt', 'create a DeepseekVLForConditionalGeneration model from pretrained weights with auto dtype and device map for image-text-to-text tasks', 'test the DeepseekVLVisionText2TextModelTester class with DeepseekVLConfig, LlamaConfig, and SiglipVisionConfig for unit testing the VLM', 'test the DeepseekVLProcessor class using the ProcessorTesterMixin test suite', 'setup a tokenizer for DeepseekVLProcessor with pad_token and image_placeholder special tokens', 'prepare a processor dictionary with chat_template and num_image_tokens for DeepseekVLProcessor', 'run the unittest test suite for DeepseekVLProcessor using pytest or unittest', 'review the DeepseekVLProcessorTest class to understand the processor test configuration and chat template']
```

Usage

```
{'test_image_processor_properties': 'test the DeepseekVL image processor has required properties like image_mean and do_resize', 'test_image_processor_from_dict': 'test creating a DeepseekVL image processor from a dictionary with custom kwargs', 'prepare_image_processor_dict': 'create a configuration dictionary for the DeepseekVL image processor with normalization settings', 'prepare_image_inputs': 'generate test image inputs with configurable batch size and resolution for DeepseekVL', 'expected_output_image_shape': 'calculate the expected output shape for processed DeepseekVL images'}
```

## File: huggingface_transformers/tests/models/deepseek_vl/test_modeling_deepseek_vl.py

Prompts

```
['test the DeepseekVL image processor has required properties like image_mean and do_resize', 'test creating a DeepseekVL image processor from a dictionary with custom kwargs', 'create a configuration dictionary for the DeepseekVL image processor with normalization settings', 'generate test image inputs with configurable batch size and resolution for DeepseekVL', 'calculate the expected output shape for processed DeepseekVL images', 'test the DeepseekVLIntegrationTest.test_model_text_generation method to verify single-image text generation produces expected output', 'test the DeepseekVLIntegrationTest.test_model_text_generation_batched method to verify batched multi-input text generation with padding', 'test the DeepseekVLIntegrationTest.test_model_text_generation_with_multi_image method to verify generation with multiple images in one prompt', 'create a DeepseekVLForConditionalGeneration model from pretrained weights with auto dtype and device map for image-text-to-text tasks', 'test the DeepseekVLVisionText2TextModelTester class with DeepseekVLConfig, LlamaConfig, and SiglipVisionConfig for unit testing the VLM', 'test the DeepseekVLProcessor class using the ProcessorTesterMixin test suite', 'setup a tokenizer for DeepseekVLProcessor with pad_token and image_placeholder special tokens', 'prepare a processor dictionary with chat_template and num_image_tokens for DeepseekVLProcessor', 'run the unittest test suite for DeepseekVLProcessor using pytest or unittest', 'review the DeepseekVLProcessorTest class to understand the processor test configuration and chat template']
```

Usage

```
{'test_deepseek_vl_text_generation': 'test the DeepseekVLIntegrationTest.test_model_text_generation method to verify single-image text generation produces expected output', 'test_deepseek_vl_batched_generation': 'test the DeepseekVLIntegrationTest.test_model_text_generation_batched method to verify batched multi-input text generation with padding', 'test_deepseek_vl_multi_image': 'test the DeepseekVLIntegrationTest.test_model_text_generation_with_multi_image method to verify generation with multiple images in one prompt', 'create_deepseek_vl_model': 'create a DeepseekVLForConditionalGeneration model from pretrained weights with auto dtype and device map for image-text-to-text tasks', 'test_deepseek_vl_config': 'test the DeepseekVLVisionText2TextModelTester class with DeepseekVLConfig, LlamaConfig, and SiglipVisionConfig for unit testing the VLM'}
```

## File: huggingface_transformers/tests/models/deepseek_vl/test_processing_deepseek_vl.py

Prompts

```
['test the DeepseekVL image processor has required properties like image_mean and do_resize', 'test creating a DeepseekVL image processor from a dictionary with custom kwargs', 'create a configuration dictionary for the DeepseekVL image processor with normalization settings', 'generate test image inputs with configurable batch size and resolution for DeepseekVL', 'calculate the expected output shape for processed DeepseekVL images', 'test the DeepseekVLIntegrationTest.test_model_text_generation method to verify single-image text generation produces expected output', 'test the DeepseekVLIntegrationTest.test_model_text_generation_batched method to verify batched multi-input text generation with padding', 'test the DeepseekVLIntegrationTest.test_model_text_generation_with_multi_image method to verify generation with multiple images in one prompt', 'create a DeepseekVLForConditionalGeneration model from pretrained weights with auto dtype and device map for image-text-to-text tasks', 'test the DeepseekVLVisionText2TextModelTester class with DeepseekVLConfig, LlamaConfig, and SiglipVisionConfig for unit testing the VLM', 'test the DeepseekVLProcessor class using the ProcessorTesterMixin test suite', 'setup a tokenizer for DeepseekVLProcessor with pad_token and image_placeholder special tokens', 'prepare a processor dictionary with chat_template and num_image_tokens for DeepseekVLProcessor', 'run the unittest test suite for DeepseekVLProcessor using pytest or unittest', 'review the DeepseekVLProcessorTest class to understand the processor test configuration and chat template']
```

Usage

```
{'test_DeepseekVLProcessor': 'test the DeepseekVLProcessor class using the ProcessorTesterMixin test suite', 'setup_tokenizer_DeepseekVLProcessor': 'setup a tokenizer for DeepseekVLProcessor with pad_token and image_placeholder special tokens', 'prepare_processor_dict_DeepseekVLProcessor': 'prepare a processor dictionary with chat_template and num_image_tokens for DeepseekVLProcessor', 'run_DeepseekVLProcessor_tests': 'run the unittest test suite for DeepseekVLProcessor using pytest or unittest', 'review_DeepseekVLProcessorTest': 'review the DeepseekVLProcessorTest class to understand the processor test configuration and chat template'}
```

