# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/convnext/test_image_processing_convnext.py

Prompts

```
['test the ConvNextImageProcessingTest class verifies image processor has do_resize, size, crop_pct, do_normalize, image_mean, and image_std attributes', 'test the ConvNextImageProcessingTest class creates image processors from dict and overrides size via kwargs', 'build a ConvNextImageProcessingTester instance that prepares image processor configuration dict with mean, std, normalize, resize, size, and crop_pct settings', 'prepare image inputs with configurable batch size, channels, resolution range, and optional numpify or torchify conversion', 'test the expected output image shape is num_channels by size shortest_edge by size shortest_edge after resizing', 'test the ConvNext model with config, pixel values, and labels to verify last hidden state shapes', 'test ConvNextForImageClassification model to verify logits output shape matches batch size and number of labels', 'test ConvNextBackbone to verify feature maps, channels, and out_features=None behavior', 'test that output_hidden_states returns expected number of stages and feature map dimensions for all ConvNext model classes', 'test ConvNextForImageClassification inference on a sample image and verify logits shape and slice values']
```

Usage

```
{'test_image_processor_properties': 'test the ConvNextImageProcessingTest class verifies image processor has do_resize, size, crop_pct, do_normalize, image_mean, and image_std attributes', 'test_image_processor_from_dict_with_kwargs': 'test the ConvNextImageProcessingTest class creates image processors from dict and overrides size via kwargs', 'build_image_processor_dict': 'build a ConvNextImageProcessingTester instance that prepares image processor configuration dict with mean, std, normalize, resize, size, and crop_pct settings', 'prepare_image_inputs': 'prepare image inputs with configurable batch size, channels, resolution range, and optional numpify or torchify conversion', 'test_expected_output_image_shape': 'test the expected output image shape is num_channels by size shortest_edge by size shortest_edge after resizing'}
```

## File: huggingface_transformers/tests/models/convnext/test_modeling_convnext.py

Prompts

```
['test the ConvNextImageProcessingTest class verifies image processor has do_resize, size, crop_pct, do_normalize, image_mean, and image_std attributes', 'test the ConvNextImageProcessingTest class creates image processors from dict and overrides size via kwargs', 'build a ConvNextImageProcessingTester instance that prepares image processor configuration dict with mean, std, normalize, resize, size, and crop_pct settings', 'prepare image inputs with configurable batch size, channels, resolution range, and optional numpify or torchify conversion', 'test the expected output image shape is num_channels by size shortest_edge by size shortest_edge after resizing', 'test the ConvNext model with config, pixel values, and labels to verify last hidden state shapes', 'test ConvNextForImageClassification model to verify logits output shape matches batch size and number of labels', 'test ConvNextBackbone to verify feature maps, channels, and out_features=None behavior', 'test that output_hidden_states returns expected number of stages and feature map dimensions for all ConvNext model classes', 'test ConvNextForImageClassification inference on a sample image and verify logits shape and slice values']
```

Usage

```
{'test_modeling_convnext': 'test the ConvNext model with config, pixel values, and labels to verify last hidden state shapes', 'test_convnext_for_image_classification': 'test ConvNextForImageClassification model to verify logits output shape matches batch size and number of labels', 'test_convnext_backbone': 'test ConvNextBackbone to verify feature maps, channels, and out_features=None behavior', 'test_hidden_states_output': 'test that output_hidden_states returns expected number of stages and feature map dimensions for all ConvNext model classes', 'test_convnext_inference_image_classification': 'test ConvNextForImageClassification inference on a sample image and verify logits shape and slice values'}
```

