# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/yolos/test_image_processing_yolos.py

Prompts

```
['test the YolosImageProcessingTest class to verify image processor properties like image_mean and do_normalize', 'test the YolosImageProcessingTest resize method to ensure max size constraints are respected for various image dimensions', 'test the YolosImageProcessingTest with COCO detection annotations to verify pixel values and bounding box encoding', 'test the YolosImageProcessingTest with COCO panoptic annotations to verify masks and segment info encoding', 'test the YolosImageProcessingTest batched COCO detection and panoptic annotations to verify padding and box adjustments', 'test the YolosModel class forward pass and verify output shapes for batched image inputs', 'test the YolosForObjectDetection class inference and training modes with labels', 'test that attention outputs are returned correctly across all transformer layers', 'test that hidden states are returned correctly across all transformer layers', 'test loading and running inference with a pretrained YOLOS model on a sample image']
```

Usage

```
{'test_yolos_image_processor_properties': 'test the YolosImageProcessingTest class to verify image processor properties like image_mean and do_normalize', 'test_yolos_resize_max_size': 'test the YolosImageProcessingTest resize method to ensure max size constraints are respected for various image dimensions', 'test_yolos_coco_detection_annotations': 'test the YolosImageProcessingTest with COCO detection annotations to verify pixel values and bounding box encoding', 'test_yolos_coco_panoptic_annotations': 'test the YolosImageProcessingTest with COCO panoptic annotations to verify masks and segment info encoding', 'test_yolos_batched_annotations': 'test the YolosImageProcessingTest batched COCO detection and panoptic annotations to verify padding and box adjustments'}
```

## File: huggingface_transformers/tests/models/yolos/test_modeling_yolos.py

Prompts

```
['test the YolosImageProcessingTest class to verify image processor properties like image_mean and do_normalize', 'test the YolosImageProcessingTest resize method to ensure max size constraints are respected for various image dimensions', 'test the YolosImageProcessingTest with COCO detection annotations to verify pixel values and bounding box encoding', 'test the YolosImageProcessingTest with COCO panoptic annotations to verify masks and segment info encoding', 'test the YolosImageProcessingTest batched COCO detection and panoptic annotations to verify padding and box adjustments', 'test the YolosModel class forward pass and verify output shapes for batched image inputs', 'test the YolosForObjectDetection class inference and training modes with labels', 'test that attention outputs are returned correctly across all transformer layers', 'test that hidden states are returned correctly across all transformer layers', 'test loading and running inference with a pretrained YOLOS model on a sample image']
```

Usage

```
{'test_model_yolos': 'test the YolosModel class forward pass and verify output shapes for batched image inputs', 'test_model_object_detection': 'test the YolosForObjectDetection class inference and training modes with labels', 'test_attention_outputs': 'test that attention outputs are returned correctly across all transformer layers', 'test_hidden_states_output': 'test that hidden states are returned correctly across all transformer layers', 'test_model_inference_pretrained': 'test loading and running inference with a pretrained YOLOS model on a sample image'}
```

