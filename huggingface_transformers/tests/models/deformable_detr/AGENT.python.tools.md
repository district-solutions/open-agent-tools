# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/deformable_detr/test_image_processing_deformable_detr.py

Prompts

```
['test the DeformableDetrImageProcessor class properties like image_mean, image_std, do_resize, and do_pad', 'test encoding COCO detection annotations with DeformableDetrImageProcessor and verify pixel values and bounding boxes', 'test encoding COCO panoptic segmentation annotations with masks and verify class labels and mask sums', 'test batched COCO detection annotation processing with multiple images and verify padded bounding boxes', 'test longest_edge shortest_edge resizing and max_width max_height padding strategies for image preprocessing', 'test the DeformableDetrModel class with configurable encoder-decoder architecture and attention outputs', 'test the DeformableDetrForObjectDetection head model for logits and predicted bounding box outputs', 'test encoder, decoder, and cross attention output shapes and layer counts for Deformable DETR models', 'test tuple and dict model output equivalence across all Deformable DETR model classes', 'run inference on DeformableDetrForObjectDetection with image preprocessing and post-processing for object detection']
```

Usage

```
{'test_deformable_detr_image_processor_properties': 'test the DeformableDetrImageProcessor class properties like image_mean, image_std, do_resize, and do_pad', 'test_coco_detection_annotations_encoding': 'test encoding COCO detection annotations with DeformableDetrImageProcessor and verify pixel values and bounding boxes', 'test_coco_panoptic_annotations_encoding': 'test encoding COCO panoptic segmentation annotations with masks and verify class labels and mask sums', 'test_batched_coco_detection_annotations': 'test batched COCO detection annotation processing with multiple images and verify padded bounding boxes', 'test_resizing_and_padding_strategies': 'test longest_edge shortest_edge resizing and max_width max_height padding strategies for image preprocessing'}
```

## File: huggingface_transformers/tests/models/deformable_detr/test_modeling_deformable_detr.py

Prompts

```
['test the DeformableDetrImageProcessor class properties like image_mean, image_std, do_resize, and do_pad', 'test encoding COCO detection annotations with DeformableDetrImageProcessor and verify pixel values and bounding boxes', 'test encoding COCO panoptic segmentation annotations with masks and verify class labels and mask sums', 'test batched COCO detection annotation processing with multiple images and verify padded bounding boxes', 'test longest_edge shortest_edge resizing and max_width max_height padding strategies for image preprocessing', 'test the DeformableDetrModel class with configurable encoder-decoder architecture and attention outputs', 'test the DeformableDetrForObjectDetection head model for logits and predicted bounding box outputs', 'test encoder, decoder, and cross attention output shapes and layer counts for Deformable DETR models', 'test tuple and dict model output equivalence across all Deformable DETR model classes', 'run inference on DeformableDetrForObjectDetection with image preprocessing and post-processing for object detection']
```

Usage

```
{'test_deformable_detr_model': 'test the DeformableDetrModel class with configurable encoder-decoder architecture and attention outputs', 'test_deformable_detr_object_detection': 'test the DeformableDetrForObjectDetection head model for logits and predicted bounding box outputs', 'test_attention_outputs': 'test encoder, decoder, and cross attention output shapes and layer counts for Deformable DETR models', 'test_model_outputs_equivalence': 'test tuple and dict model output equivalence across all Deformable DETR model classes', 'test_inference_object_detection': 'run inference on DeformableDetrForObjectDetection with image preprocessing and post-processing for object detection'}
```

