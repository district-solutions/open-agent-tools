# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/deepseek_vl_hybrid/test_image_processing_deepseek_vl_hybrid.py

Prompts

```
['test the image processor from_dict method with default and overridden size kwargs', 'test the image processor class has all expected attributes like image_mean, image_std, high_res_size', 'test the image processor call method with PIL image inputs for high_res_pixel_values output', 'test the image processor call method with numpy array inputs for high_res_pixel_values output', 'test the image processor call method with pytorch tensor inputs for high_res_pixel_values output', 'test the DeepseekVLHybridProcessorTest class that inherits from ProcessorTesterMixin and unittest.TestCase', 'test the _setup_tokenizer classmethod that returns a tokenizer with pad_token and image_token special tokens', 'test the prepare_processor_dict staticmethod that returns processor config with chat_template and num_image_tokens', 'test the processor_class class attribute that references DeepseekVLHybridProcessor', 'test the SAMPLE_VOCAB constant that points to the test_sentencepiece.model fixture path']
```

Usage

```
{'test_image_processor_from_dict_with_kwargs': 'test the image processor from_dict method with default and overridden size kwargs', 'test_image_processor_properties': 'test the image processor class has all expected attributes like image_mean, image_std, high_res_size', 'test_call_pil_high_res': 'test the image processor call method with PIL image inputs for high_res_pixel_values output', 'test_call_numpy_high_res': 'test the image processor call method with numpy array inputs for high_res_pixel_values output', 'test_call_pytorch_high_res': 'test the image processor call method with pytorch tensor inputs for high_res_pixel_values output'}
```

## File: huggingface_transformers/tests/models/deepseek_vl_hybrid/test_processing_deepseek_vl_hybrid.py

Prompts

```
['test the image processor from_dict method with default and overridden size kwargs', 'test the image processor class has all expected attributes like image_mean, image_std, high_res_size', 'test the image processor call method with PIL image inputs for high_res_pixel_values output', 'test the image processor call method with numpy array inputs for high_res_pixel_values output', 'test the image processor call method with pytorch tensor inputs for high_res_pixel_values output', 'test the DeepseekVLHybridProcessorTest class that inherits from ProcessorTesterMixin and unittest.TestCase', 'test the _setup_tokenizer classmethod that returns a tokenizer with pad_token and image_token special tokens', 'test the prepare_processor_dict staticmethod that returns processor config with chat_template and num_image_tokens', 'test the processor_class class attribute that references DeepseekVLHybridProcessor', 'test the SAMPLE_VOCAB constant that points to the test_sentencepiece.model fixture path']
```

Usage

```
{'test_DeepseekVLHybridProcessor': 'test the DeepseekVLHybridProcessorTest class that inherits from ProcessorTesterMixin and unittest.TestCase', 'test__setup_tokenizer': 'test the _setup_tokenizer classmethod that returns a tokenizer with pad_token and image_token special tokens', 'test_prepare_processor_dict': 'test the prepare_processor_dict staticmethod that returns processor config with chat_template and num_image_tokens', 'test_processor_class_attribute': 'test the processor_class class attribute that references DeepseekVLHybridProcessor', 'test_SAMPLE_VOCAB_fixture': 'test the SAMPLE_VOCAB constant that points to the test_sentencepiece.model fixture path'}
```

