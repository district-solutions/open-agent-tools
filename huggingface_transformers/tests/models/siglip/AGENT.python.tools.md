# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/siglip/test_image_processing_siglip.py

Prompts

```
['test the SiglipImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test the SiglipImageProcessingTest from_dict method with custom size kwargs override', 'build a SiglipImageProcessingTester to prepare an image processor configuration dictionary with resize and normalize settings', 'create a SiglipImageProcessingTester to prepare synthetic image inputs with configurable batch size and resolution', 'review the SiglipImageProcessingTester class and its image preprocessing configuration parameters', 'test the SiglipVisionModelTest class to verify vision encoder forward pass and output shapes', 'test the SiglipTextModelTest class to verify text encoder forward pass and output shapes', 'test the SiglipModelTest class to verify multimodal image-text contrastive inference', 'test the SiglipForImageClassificationModelTest class to verify image classification pipeline', 'test the SiglipModelTesterMixin class to verify SDPA and eager attention implementation loading', 'test the SiglipModelIntegrationTest class to verify end-to-end inference with real images', 'test the test_vision_transformer_get_set_input_embeddings method to verify conv2d embedding replacement', 'test the test_load_vision_text_config method to verify saving and loading vision and text configs', 'test the SiglipTokenizer class for sentencepiece-based tokenization with special token handling', 'test that SiglipTokenizer treats explicit </s> tokens identically to implicit end-of-sequence', 'test batch tokenization with padding and return_tensors for SiglipTokenizer input encoding', 'test SiglipTokenizer edge cases including empty strings, whitespace, and malformed special tokens', 'test adding and encoding custom special tokens with lstrip/rstrip behavior in SiglipTokenizer']
```

Usage

```
{'test_siglip_image_processor_properties': 'test the SiglipImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test_siglip_from_dict_with_kwargs': 'test the SiglipImageProcessingTest from_dict method with custom size kwargs override', 'prepare_siglip_image_processor_dict': 'build a SiglipImageProcessingTester to prepare an image processor configuration dictionary with resize and normalize settings', 'prepare_siglip_image_inputs': 'create a SiglipImageProcessingTester to prepare synthetic image inputs with configurable batch size and resolution', 'review_siglip_image_processing_tester': 'review the SiglipImageProcessingTester class and its image preprocessing configuration parameters'}
```

## File: huggingface_transformers/tests/models/siglip/test_modeling_siglip.py

Prompts

```
['test the SiglipImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test the SiglipImageProcessingTest from_dict method with custom size kwargs override', 'build a SiglipImageProcessingTester to prepare an image processor configuration dictionary with resize and normalize settings', 'create a SiglipImageProcessingTester to prepare synthetic image inputs with configurable batch size and resolution', 'review the SiglipImageProcessingTester class and its image preprocessing configuration parameters', 'test the SiglipVisionModelTest class to verify vision encoder forward pass and output shapes', 'test the SiglipTextModelTest class to verify text encoder forward pass and output shapes', 'test the SiglipModelTest class to verify multimodal image-text contrastive inference', 'test the SiglipForImageClassificationModelTest class to verify image classification pipeline', 'test the SiglipModelTesterMixin class to verify SDPA and eager attention implementation loading', 'test the SiglipModelIntegrationTest class to verify end-to-end inference with real images', 'test the test_vision_transformer_get_set_input_embeddings method to verify conv2d embedding replacement', 'test the test_load_vision_text_config method to verify saving and loading vision and text configs', 'test the SiglipTokenizer class for sentencepiece-based tokenization with special token handling', 'test that SiglipTokenizer treats explicit </s> tokens identically to implicit end-of-sequence', 'test batch tokenization with padding and return_tensors for SiglipTokenizer input encoding', 'test SiglipTokenizer edge cases including empty strings, whitespace, and malformed special tokens', 'test adding and encoding custom special tokens with lstrip/rstrip behavior in SiglipTokenizer']
```

Usage

```
{'test_modeling_siglip_vision': 'test the SiglipVisionModelTest class to verify vision encoder forward pass and output shapes', 'test_modeling_siglip_text': 'test the SiglipTextModelTest class to verify text encoder forward pass and output shapes', 'test_modeling_siglip_multimodal': 'test the SiglipModelTest class to verify multimodal image-text contrastive inference', 'test_modeling_siglip_classification': 'test the SiglipForImageClassificationModelTest class to verify image classification pipeline', 'test_siglip_sdpa_attention': 'test the SiglipModelTesterMixin class to verify SDPA and eager attention implementation loading', 'test_siglip_integration_inference': 'test the SiglipModelIntegrationTest class to verify end-to-end inference with real images', 'test_siglip_vision_embeddings': 'test the test_vision_transformer_get_set_input_embeddings method to verify conv2d embedding replacement', 'test_siglip_config_loading': 'test the test_load_vision_text_config method to verify saving and loading vision and text configs'}
```

## File: huggingface_transformers/tests/models/siglip/test_tokenization_siglip.py

Prompts

```
['test the SiglipImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test the SiglipImageProcessingTest from_dict method with custom size kwargs override', 'build a SiglipImageProcessingTester to prepare an image processor configuration dictionary with resize and normalize settings', 'create a SiglipImageProcessingTester to prepare synthetic image inputs with configurable batch size and resolution', 'review the SiglipImageProcessingTester class and its image preprocessing configuration parameters', 'test the SiglipVisionModelTest class to verify vision encoder forward pass and output shapes', 'test the SiglipTextModelTest class to verify text encoder forward pass and output shapes', 'test the SiglipModelTest class to verify multimodal image-text contrastive inference', 'test the SiglipForImageClassificationModelTest class to verify image classification pipeline', 'test the SiglipModelTesterMixin class to verify SDPA and eager attention implementation loading', 'test the SiglipModelIntegrationTest class to verify end-to-end inference with real images', 'test the test_vision_transformer_get_set_input_embeddings method to verify conv2d embedding replacement', 'test the test_load_vision_text_config method to verify saving and loading vision and text configs', 'test the SiglipTokenizer class for sentencepiece-based tokenization with special token handling', 'test that SiglipTokenizer treats explicit </s> tokens identically to implicit end-of-sequence', 'test batch tokenization with padding and return_tensors for SiglipTokenizer input encoding', 'test SiglipTokenizer edge cases including empty strings, whitespace, and malformed special tokens', 'test adding and encoding custom special tokens with lstrip/rstrip behavior in SiglipTokenizer']
```

Usage

```
{'test_SiglipTokenizer': 'test the SiglipTokenizer class for sentencepiece-based tokenization with special token handling', 'test_tokenizer_eos_treatment': 'test that SiglipTokenizer treats explicit </s> tokens identically to implicit end-of-sequence', 'test_tokenizer_prepare_batch': 'test batch tokenization with padding and return_tensors for SiglipTokenizer input encoding', 'test_tokenizer_edge_cases': 'test SiglipTokenizer edge cases including empty strings, whitespace, and malformed special tokens', 'test_special_tokens_initialization': 'test adding and encoding custom special tokens with lstrip/rstrip behavior in SiglipTokenizer'}
```

