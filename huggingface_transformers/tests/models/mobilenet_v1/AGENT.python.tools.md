# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mobilenet_v1/test_image_processing_mobilenet_v1.py

Prompts

```
['test that MobileNetV1 image processor has do_resize, size, do_center_crop, and crop_size properties', 'test MobileNetV1 image processor from_dict method with size and crop_size keyword argument overrides', 'create a configuration dictionary for the MobileNetV1 image processor with resize and crop settings', 'prepare test image inputs with configurable batch size, channels, and resolution for MobileNetV1', 'get the expected output image shape tuple with channels, height, and width for MobileNetV1', 'test the MobileNetV1Model forward pass output shape with random pixel values', 'test MobileNetV1ForImageClassification model logits shape against expected batch and label dimensions', 'test MobileNetV1Config properties including tf_padding and depth_multiplier attributes', 'test MobileNetV1Model hidden states output returns expected number of stages', 'run inference with pretrained MobileNetV1ForImageClassification model on a sample cat image']
```

Usage

```
{'test_image_processor_properties': 'test that MobileNetV1 image processor has do_resize, size, do_center_crop, and crop_size properties', 'test_image_processor_from_dict_with_kwargs': 'test MobileNetV1 image processor from_dict method with size and crop_size keyword argument overrides', 'prepare_image_processor_dict': 'create a configuration dictionary for the MobileNetV1 image processor with resize and crop settings', 'prepare_image_inputs': 'prepare test image inputs with configurable batch size, channels, and resolution for MobileNetV1', 'expected_output_image_shape': 'get the expected output image shape tuple with channels, height, and width for MobileNetV1'}
```

## File: huggingface_transformers/tests/models/mobilenet_v1/test_modeling_mobilenet_v1.py

Prompts

```
['test that MobileNetV1 image processor has do_resize, size, do_center_crop, and crop_size properties', 'test MobileNetV1 image processor from_dict method with size and crop_size keyword argument overrides', 'create a configuration dictionary for the MobileNetV1 image processor with resize and crop settings', 'prepare test image inputs with configurable batch size, channels, and resolution for MobileNetV1', 'get the expected output image shape tuple with channels, height, and width for MobileNetV1', 'test the MobileNetV1Model forward pass output shape with random pixel values', 'test MobileNetV1ForImageClassification model logits shape against expected batch and label dimensions', 'test MobileNetV1Config properties including tf_padding and depth_multiplier attributes', 'test MobileNetV1Model hidden states output returns expected number of stages', 'run inference with pretrained MobileNetV1ForImageClassification model on a sample cat image']
```

Usage

```
{'test_mobilenetv1_model': 'test the MobileNetV1Model forward pass output shape with random pixel values', 'test_mobilenetv1_image_classification': 'test MobileNetV1ForImageClassification model logits shape against expected batch and label dimensions', 'test_mobilenetv1_config': 'test MobileNetV1Config properties including tf_padding and depth_multiplier attributes', 'test_mobilenetv1_hidden_states': 'test MobileNetV1Model hidden states output returns expected number of stages', 'run_mobilenetv1_integration_inference': 'run inference with pretrained MobileNetV1ForImageClassification model on a sample cat image'}
```

