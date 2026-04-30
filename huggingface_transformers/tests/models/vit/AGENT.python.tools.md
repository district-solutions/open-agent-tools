# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vit/test_image_processing_vit.py

Prompts

```
['test ViTImageProcessingTester to prepare an image processor configuration dictionary with normalization and resize settings', 'test ViTImageProcessingTester expected_output_image_shape method to return the correct channel height and width tuple', 'test ViTImageProcessingTester prepare_image_inputs method to generate test image batches with optional numpy or torch conversion', 'test ViTImageProcessingTest to verify image processor instances have image_mean image_std do_normalize do_resize and size attributes', 'test ViTImageProcessingTest from_dict method to create an image processor from a config dict with optional size override kwargs', 'run ViTModelTester to create and check ViTModel output shape for batched pixel values', 'run ViTModelTester to create and check ViTForImageClassification logits shape for labeled images', 'run ViTModelTester to create and check ViTForMaskedImageModeling reconstruction shape for pixel inputs', 'test ViTModel forward pass by preparing config and inputs via ViTModelTester', 'test ViTForImageClassification inference using pretrained google/vit-base-patch16-224 model on a sample image']
```

Usage

```
{'test_ViTImageProcessingTester_prepare_dict': 'test ViTImageProcessingTester to prepare an image processor configuration dictionary with normalization and resize settings', 'test_ViTImageProcessingTester_expected_shape': 'test ViTImageProcessingTester expected_output_image_shape method to return the correct channel height and width tuple', 'test_ViTImageProcessingTester_prepare_inputs': 'test ViTImageProcessingTester prepare_image_inputs method to generate test image batches with optional numpy or torch conversion', 'test_ViTImageProcessingTest_properties': 'test ViTImageProcessingTest to verify image processor instances have image_mean image_std do_normalize do_resize and size attributes', 'test_ViTImageProcessingTest_from_dict_kwargs': 'test ViTImageProcessingTest from_dict method to create an image processor from a config dict with optional size override kwargs'}
```

## File: huggingface_transformers/tests/models/vit/test_modeling_vit.py

Prompts

```
['test ViTImageProcessingTester to prepare an image processor configuration dictionary with normalization and resize settings', 'test ViTImageProcessingTester expected_output_image_shape method to return the correct channel height and width tuple', 'test ViTImageProcessingTester prepare_image_inputs method to generate test image batches with optional numpy or torch conversion', 'test ViTImageProcessingTest to verify image processor instances have image_mean image_std do_normalize do_resize and size attributes', 'test ViTImageProcessingTest from_dict method to create an image processor from a config dict with optional size override kwargs', 'run ViTModelTester to create and check ViTModel output shape for batched pixel values', 'run ViTModelTester to create and check ViTForImageClassification logits shape for labeled images', 'run ViTModelTester to create and check ViTForMaskedImageModeling reconstruction shape for pixel inputs', 'test ViTModel forward pass by preparing config and inputs via ViTModelTester', 'test ViTForImageClassification inference using pretrained google/vit-base-patch16-224 model on a sample image']
```

Usage

```
{'run_ViTModelTester_create_and_check_model': 'run ViTModelTester to create and check ViTModel output shape for batched pixel values', 'run_ViTModelTester_create_and_check_for_image_classification': 'run ViTModelTester to create and check ViTForImageClassification logits shape for labeled images', 'run_ViTModelTester_create_and_check_for_masked_image_modeling': 'run ViTModelTester to create and check ViTForMaskedImageModeling reconstruction shape for pixel inputs', 'test_ViTModelTest_test_model': 'test ViTModel forward pass by preparing config and inputs via ViTModelTester', 'test_ViTModelIntegrationTest_test_inference_image_classification_head': 'test ViTForImageClassification inference using pretrained google/vit-base-patch16-224 model on a sample image'}
```

