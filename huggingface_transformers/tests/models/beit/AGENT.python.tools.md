# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/beit/test_image_processing_beit.py

Prompts

```
['test the BeitImageProcessingTest class verifies image processor has all expected attributes like do_resize, size, crop_size, and normalization settings', 'test loading an image processor from a dictionary with optional kwargs overriding size, crop_size, and do_reduce_labels', 'test calling the image processor with PyTorch tensors and PIL images to verify pixel_values and labels output shapes and dtypes', 'test the reduce_labels flag shifts ADE20k label range from 0-150 to 0-255 and preserves the number of segmentation masks', 'test that multiple image processing backend implementations produce equivalent pixel_values and labels tensors for single and batched inputs', 'test the BEiT model classes including BeitModel, BeitBackbone, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation', 'create a BeitConfig with model hyperparameters such as hidden_size, num_hidden_layers, patch_size, and image_size', 'test the forward pass of BeitModel, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation with pixel inputs', 'test BeitBackbone to produce feature maps with correct batch, channel, height, and width dimensions', 'test training mode forward and backward pass for loss computation and gradient flow across BEiT model classes']
```

Usage

```
{'test_image_processor_properties': 'test the BeitImageProcessingTest class verifies image processor has all expected attributes like do_resize, size, crop_size, and normalization settings', 'test_image_processor_from_dict_with_kwargs': 'test loading an image processor from a dictionary with optional kwargs overriding size, crop_size, and do_reduce_labels', 'test_call_segmentation_maps': 'test calling the image processor with PyTorch tensors and PIL images to verify pixel_values and labels output shapes and dtypes', 'test_reduce_labels': 'test the reduce_labels flag shifts ADE20k label range from 0-150 to 0-255 and preserves the number of segmentation masks', 'test_backends_equivalence': 'test that multiple image processing backend implementations produce equivalent pixel_values and labels tensors for single and batched inputs'}
```

## File: huggingface_transformers/tests/models/beit/test_modeling_beit.py

Prompts

```
['test the BeitImageProcessingTest class verifies image processor has all expected attributes like do_resize, size, crop_size, and normalization settings', 'test loading an image processor from a dictionary with optional kwargs overriding size, crop_size, and do_reduce_labels', 'test calling the image processor with PyTorch tensors and PIL images to verify pixel_values and labels output shapes and dtypes', 'test the reduce_labels flag shifts ADE20k label range from 0-150 to 0-255 and preserves the number of segmentation masks', 'test that multiple image processing backend implementations produce equivalent pixel_values and labels tensors for single and batched inputs', 'test the BEiT model classes including BeitModel, BeitBackbone, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation', 'create a BeitConfig with model hyperparameters such as hidden_size, num_hidden_layers, patch_size, and image_size', 'test the forward pass of BeitModel, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation with pixel inputs', 'test BeitBackbone to produce feature maps with correct batch, channel, height, and width dimensions', 'test training mode forward and backward pass for loss computation and gradient flow across BEiT model classes']
```

Usage

```
{'test_MODEL_BEiT': 'test the BEiT model classes including BeitModel, BeitBackbone, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation', 'create_config_BEiT': 'create a BeitConfig with model hyperparameters such as hidden_size, num_hidden_layers, patch_size, and image_size', 'test_model_forward_pass': 'test the forward pass of BeitModel, BeitForImageClassification, BeitForMaskedImageModeling, and BeitForSemanticSegmentation with pixel inputs', 'test_backbone_feature_maps': 'test BeitBackbone to produce feature maps with correct batch, channel, height, and width dimensions', 'test_training_gradient_flow': 'test training mode forward and backward pass for loss computation and gradient flow across BEiT model classes'}
```

