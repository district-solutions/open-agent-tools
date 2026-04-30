# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/detr/test_image_processing_detr.py

Prompts

```
['test the DetrImageProcessingTest class verifies image processor properties like image_mean, image_std, and do_normalize', 'test the image processor with valid COCO detection annotations and verify expected tensor shapes and values', 'test batched COCO detection annotation processing with padding and bounding box normalization', 'test the image processor resizing and padding strategy with max_height and max_width size parameters', 'test the image processor resizing strategy with longest_edge and shortest_edge size parameters', 'test the DetrModel class with encoder-decoder forward pass and shape verification', 'test DetrForObjectDetection with pixel inputs and bounding box output shapes', 'test DETR encoder, decoder, and cross-attention output tensor shapes and layer counts', 'test reverse weight renaming mapping for DETR model state dict serialization and reload', 'test auxiliary loss outputs from DETR object detection and segmentation heads']
```

Usage

```
{'test_image_processor_properties': 'test the DetrImageProcessingTest class verifies image processor properties like image_mean, image_std, and do_normalize', 'test_valid_coco_detection_annotations': 'test the image processor with valid COCO detection annotations and verify expected tensor shapes and values', 'test_batched_coco_detection_annotations': 'test batched COCO detection annotation processing with padding and bounding box normalization', 'test_max_width_max_height_resizing_and_pad_strategy': 'test the image processor resizing and padding strategy with max_height and max_width size parameters', 'test_longest_edge_shortest_edge_resizing_strategy': 'test the image processor resizing strategy with longest_edge and shortest_edge size parameters'}
```

## File: huggingface_transformers/tests/models/detr/test_modeling_detr.py

Prompts

```
['test the DetrImageProcessingTest class verifies image processor properties like image_mean, image_std, and do_normalize', 'test the image processor with valid COCO detection annotations and verify expected tensor shapes and values', 'test batched COCO detection annotation processing with padding and bounding box normalization', 'test the image processor resizing and padding strategy with max_height and max_width size parameters', 'test the image processor resizing strategy with longest_edge and shortest_edge size parameters', 'test the DetrModel class with encoder-decoder forward pass and shape verification', 'test DetrForObjectDetection with pixel inputs and bounding box output shapes', 'test DETR encoder, decoder, and cross-attention output tensor shapes and layer counts', 'test reverse weight renaming mapping for DETR model state dict serialization and reload', 'test auxiliary loss outputs from DETR object detection and segmentation heads']
```

Usage

```
{'test_detr_model': 'test the DetrModel class with encoder-decoder forward pass and shape verification', 'test_detr_object_detection_head_model': 'test DetrForObjectDetection with pixel inputs and bounding box output shapes', 'test_attention_outputs': 'test DETR encoder, decoder, and cross-attention output tensor shapes and layer counts', 'test_reverse_loading_mapping': 'test reverse weight renaming mapping for DETR model state dict serialization and reload', 'test_forward_auxiliary_loss': 'test auxiliary loss outputs from DETR object detection and segmentation heads'}
```

