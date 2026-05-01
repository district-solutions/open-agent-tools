# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mobilenet_v2/test_image_processing_mobilenet_v2.py

Prompts

```
['test the MobileNetV2 image processor properties including do_resize, size, do_center_crop, crop_size, and do_reduce_labels', 'test creating a MobileNetV2 image processor from a dictionary with override kwargs for size and crop_size', 'test processing segmentation maps with the MobileNetV2 image processor for single and batched inputs', 'test the do_reduce_labels feature to remap ADE20k semantic labels from 150 classes to 255 range', 'test that different image processing backends produce equivalent pixel values and labels for MobileNetV2', 'test the MobileNetV2Model by running create_and_check_model to verify last_hidden_state and pooler_output shapes', 'test the MobileNetV2ForImageClassification model by running create_and_check_for_image_classification to verify logits shape', 'test the MobileNetV2ForSemanticSegmentation model by running create_and_check_for_semantic_segmentation to verify logits shape', 'test the MobileNetV2Config by running create_and_test_config_common_properties to verify tf_padding and depth_multiplier attributes', 'test inference with pretrained MobileNetV2 models for image classification and semantic segmentation using expected logits']
```

Usage

```
{'test_mobilenetv2_image_processor_properties': 'test the MobileNetV2 image processor properties including do_resize, size, do_center_crop, crop_size, and do_reduce_labels', 'test_mobilenetv2_from_dict_with_kwargs': 'test creating a MobileNetV2 image processor from a dictionary with override kwargs for size and crop_size', 'test_mobilenetv2_segmentation_maps': 'test processing segmentation maps with the MobileNetV2 image processor for single and batched inputs', 'test_mobilenetv2_reduce_labels': 'test the do_reduce_labels feature to remap ADE20k semantic labels from 150 classes to 255 range', 'test_mobilenetv2_backends_equivalence': 'test that different image processing backends produce equivalent pixel values and labels for MobileNetV2'}
```

## File: huggingface_transformers/tests/models/mobilenet_v2/test_modeling_mobilenet_v2.py

Prompts

```
['test the MobileNetV2 image processor properties including do_resize, size, do_center_crop, crop_size, and do_reduce_labels', 'test creating a MobileNetV2 image processor from a dictionary with override kwargs for size and crop_size', 'test processing segmentation maps with the MobileNetV2 image processor for single and batched inputs', 'test the do_reduce_labels feature to remap ADE20k semantic labels from 150 classes to 255 range', 'test that different image processing backends produce equivalent pixel values and labels for MobileNetV2', 'test the MobileNetV2Model by running create_and_check_model to verify last_hidden_state and pooler_output shapes', 'test the MobileNetV2ForImageClassification model by running create_and_check_for_image_classification to verify logits shape', 'test the MobileNetV2ForSemanticSegmentation model by running create_and_check_for_semantic_segmentation to verify logits shape', 'test the MobileNetV2Config by running create_and_test_config_common_properties to verify tf_padding and depth_multiplier attributes', 'test inference with pretrained MobileNetV2 models for image classification and semantic segmentation using expected logits']
```

Usage

```
{'test_MobileNetV2Model': 'test the MobileNetV2Model by running create_and_check_model to verify last_hidden_state and pooler_output shapes', 'test_MobileNetV2ForImageClassification': 'test the MobileNetV2ForImageClassification model by running create_and_check_for_image_classification to verify logits shape', 'test_MobileNetV2ForSemanticSegmentation': 'test the MobileNetV2ForSemanticSegmentation model by running create_and_check_for_semantic_segmentation to verify logits shape', 'test_MobileNetV2ConfigTester': 'test the MobileNetV2Config by running create_and_test_config_common_properties to verify tf_padding and depth_multiplier attributes', 'test_MobileNetV2ModelIntegrationTest': 'test inference with pretrained MobileNetV2 models for image classification and semantic segmentation using expected logits'}
```

