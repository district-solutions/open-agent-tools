# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/idefics/test_image_processing_idefics.py

Prompts

```
['test the IdeficsImageProcessingTest class that validates image processor properties and backend equivalence', 'create an IdeficsImageProcessingTester instance to prepare image processor configuration dictionaries and test inputs', 'test that Idefics image processors expose image_mean, image_std, and image_size attributes', 'test the from_dict factory method with keyword argument overrides for image_size', 'test that default inference transforms match an equivalent torchvision.Compose pipeline with resize, to_tensor, and normalize', 'test the IdeficsModelTest class that validates model outputs, generation, and training for Idefics', 'create an IdeficsModelTester instance to prepare model configs, input tensors, and expected sequence lengths', 'test that cross-attention gates produce different outputs when image_attention_mask is zeroed versus filled', 'test that generation can continue from past key values with proper image_attention_mask handling', 'test loading the IdeficsModel from pretrained checkpoint HuggingFaceM4/idefics-9b', 'test the IdeficsProcessor class with image and text inputs for multimodal processing', 'test the IdeficsProcessor tokenizer padding behavior with max_length and longest padding modes', 'test the IdeficsProcessor tokenizer left padding behavior with attention masks', 'test saving and loading IdeficsProcessor with custom bos_token, eos_token, and image_processor settings', 'test IdeficsProcessor default encoding matches tokenizer with bos_token prefix']
```

Usage

```
{'test_IdeficsImageProcessingTest': 'test the IdeficsImageProcessingTest class that validates image processor properties and backend equivalence', 'create_IdeficsImageProcessingTester': 'create an IdeficsImageProcessingTester instance to prepare image processor configuration dictionaries and test inputs', 'test_image_processor_properties': 'test that Idefics image processors expose image_mean, image_std, and image_size attributes', 'test_image_processor_from_dict_with_kwargs': 'test the from_dict factory method with keyword argument overrides for image_size', 'test_torchvision_numpy_transforms_equivalency': 'test that default inference transforms match an equivalent torchvision.Compose pipeline with resize, to_tensor, and normalize'}
```

## File: huggingface_transformers/tests/models/idefics/test_modeling_idefics.py

Prompts

```
['test the IdeficsImageProcessingTest class that validates image processor properties and backend equivalence', 'create an IdeficsImageProcessingTester instance to prepare image processor configuration dictionaries and test inputs', 'test that Idefics image processors expose image_mean, image_std, and image_size attributes', 'test the from_dict factory method with keyword argument overrides for image_size', 'test that default inference transforms match an equivalent torchvision.Compose pipeline with resize, to_tensor, and normalize', 'test the IdeficsModelTest class that validates model outputs, generation, and training for Idefics', 'create an IdeficsModelTester instance to prepare model configs, input tensors, and expected sequence lengths', 'test that cross-attention gates produce different outputs when image_attention_mask is zeroed versus filled', 'test that generation can continue from past key values with proper image_attention_mask handling', 'test loading the IdeficsModel from pretrained checkpoint HuggingFaceM4/idefics-9b', 'test the IdeficsProcessor class with image and text inputs for multimodal processing', 'test the IdeficsProcessor tokenizer padding behavior with max_length and longest padding modes', 'test the IdeficsProcessor tokenizer left padding behavior with attention masks', 'test saving and loading IdeficsProcessor with custom bos_token, eos_token, and image_processor settings', 'test IdeficsProcessor default encoding matches tokenizer with bos_token prefix']
```

Usage

```
{'test_IdeficsModelTest': 'test the IdeficsModelTest class that validates model outputs, generation, and training for Idefics', 'create_IdeficsModelTester': 'create an IdeficsModelTester instance to prepare model configs, input tensors, and expected sequence lengths', 'test_cross_attention_gates': 'test that cross-attention gates produce different outputs when image_attention_mask is zeroed versus filled', 'test_generate_continue_from_past_key_values': 'test that generation can continue from past key values with proper image_attention_mask handling', 'test_model_from_pretrained': 'test loading the IdeficsModel from pretrained checkpoint HuggingFaceM4/idefics-9b'}
```

## File: huggingface_transformers/tests/models/idefics/test_processing_idefics.py

Prompts

```
['test the IdeficsImageProcessingTest class that validates image processor properties and backend equivalence', 'create an IdeficsImageProcessingTester instance to prepare image processor configuration dictionaries and test inputs', 'test that Idefics image processors expose image_mean, image_std, and image_size attributes', 'test the from_dict factory method with keyword argument overrides for image_size', 'test that default inference transforms match an equivalent torchvision.Compose pipeline with resize, to_tensor, and normalize', 'test the IdeficsModelTest class that validates model outputs, generation, and training for Idefics', 'create an IdeficsModelTester instance to prepare model configs, input tensors, and expected sequence lengths', 'test that cross-attention gates produce different outputs when image_attention_mask is zeroed versus filled', 'test that generation can continue from past key values with proper image_attention_mask handling', 'test loading the IdeficsModel from pretrained checkpoint HuggingFaceM4/idefics-9b', 'test the IdeficsProcessor class with image and text inputs for multimodal processing', 'test the IdeficsProcessor tokenizer padding behavior with max_length and longest padding modes', 'test the IdeficsProcessor tokenizer left padding behavior with attention masks', 'test saving and loading IdeficsProcessor with custom bos_token, eos_token, and image_processor settings', 'test IdeficsProcessor default encoding matches tokenizer with bos_token prefix']
```

Usage

```
{'test_idefics_processor': 'test the IdeficsProcessor class with image and text inputs for multimodal processing', 'test_processor_padding': 'test the IdeficsProcessor tokenizer padding behavior with max_length and longest padding modes', 'test_processor_left_padding': 'test the IdeficsProcessor tokenizer left padding behavior with attention masks', 'test_processor_save_load': 'test saving and loading IdeficsProcessor with custom bos_token, eos_token, and image_processor settings', 'test_processor_defaults': 'test IdeficsProcessor default encoding matches tokenizer with bos_token prefix'}
```

