# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/levit/test_image_processing_levit.py

Prompts

```
['test LevitImageProcessingTester to prepare an image processor configuration dictionary with resize, crop, and normalize settings', 'test LevitImageProcessingTester to prepare batch image inputs with configurable resolution and tensor format', 'test LevitImageProcessingTester to compute the expected output image shape from crop size and channel count', 'test LevitImageProcessingTest to verify the image processor has all required properties like image_mean and do_resize', 'test LevitImageProcessingTest to verify from_dict creates a processor and allows size and crop_size kwargs overrides', 'test the LevitModel forward pass with pixel values and verify output shape', 'test the LevitForImageClassification model with pixel values and labels', 'test the LevitModel hidden states output with all layers and verify dimensions', 'test the Levit model training loop with backward pass and gradient computation', 'test loading the LeViT model from pretrained weights with facebook/levit-128S']
```

Usage

```
{'test_LevitImageProcessingTester_prepare_processor_dict': 'test LevitImageProcessingTester to prepare an image processor configuration dictionary with resize, crop, and normalize settings', 'test_LevitImageProcessingTester_prepare_image_inputs': 'test LevitImageProcessingTester to prepare batch image inputs with configurable resolution and tensor format', 'test_LevitImageProcessingTester_expected_output_shape': 'test LevitImageProcessingTester to compute the expected output image shape from crop size and channel count', 'test_LevitImageProcessingTest_processor_properties': 'test LevitImageProcessingTest to verify the image processor has all required properties like image_mean and do_resize', 'test_LevitImageProcessingTest_from_dict_with_kwargs': 'test LevitImageProcessingTest to verify from_dict creates a processor and allows size and crop_size kwargs overrides'}
```

## File: huggingface_transformers/tests/models/levit/test_modeling_levit.py

Prompts

```
['test LevitImageProcessingTester to prepare an image processor configuration dictionary with resize, crop, and normalize settings', 'test LevitImageProcessingTester to prepare batch image inputs with configurable resolution and tensor format', 'test LevitImageProcessingTester to compute the expected output image shape from crop size and channel count', 'test LevitImageProcessingTest to verify the image processor has all required properties like image_mean and do_resize', 'test LevitImageProcessingTest to verify from_dict creates a processor and allows size and crop_size kwargs overrides', 'test the LevitModel forward pass with pixel values and verify output shape', 'test the LevitForImageClassification model with pixel values and labels', 'test the LevitModel hidden states output with all layers and verify dimensions', 'test the Levit model training loop with backward pass and gradient computation', 'test loading the LeViT model from pretrained weights with facebook/levit-128S']
```

Usage

```
{'test_LevitModel_forward': 'test the LevitModel forward pass with pixel values and verify output shape', 'test_LevitForImageClassification': 'test the LevitForImageClassification model with pixel values and labels', 'test_LevitModel_hidden_states': 'test the LevitModel hidden states output with all layers and verify dimensions', 'test_LevitModel_training': 'test the Levit model training loop with backward pass and gradient computation', 'test_LevitModel_from_pretrained': 'test loading the LeViT model from pretrained weights with facebook/levit-128S'}
```

