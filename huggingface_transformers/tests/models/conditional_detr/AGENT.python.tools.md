# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/conditional_detr/test_image_processing_conditional_detr.py

Prompts

```
['test the ConditionalDetrImageProcessingTest class for image processing correctness and properties', 'test ConditionalDetr image processor with COCO detection annotations and verify pixel values, boxes, and labels', 'test ConditionalDetr image processor with COCO panoptic annotations and verify masks, boxes, and segmentation output', 'test ConditionalDetr image processor with batched COCO detection and panoptic annotations including padding and box normalization', 'test ConditionalDetr image processor resizing and padding strategies with max_height/max_width and longest_edge/shortest_edge configurations', 'test the ConditionalDetrModel forward pass and verify output tensor shapes', 'test ConditionalDetrForObjectDetection inference with pixel values and verify logits and box predictions', 'test encoder and decoder attention outputs and verify attention tensor shapes across all model classes', 'test the reverse weight-loading mapping for model serialization and deserialization round-trips', 'test pretrained ConditionalDetrForObjectDetection inference on an image and verify post-processed detection results', 'test that auxiliary loss outputs are produced when auxiliary_loss config flag is enabled', 'test backbone configuration with timm and pretrained HF resnet backbones', 'test gradient retention on encoder hidden states, encoder attentions, decoder attentions, and cross attentions']
```

Usage

```
{'test_image_processor_conditional_detr': 'test the ConditionalDetrImageProcessingTest class for image processing correctness and properties', 'test_conditional_detr_coco_detection': 'test ConditionalDetr image processor with COCO detection annotations and verify pixel values, boxes, and labels', 'test_conditional_detr_coco_panoptic': 'test ConditionalDetr image processor with COCO panoptic annotations and verify masks, boxes, and segmentation output', 'test_conditional_detr_batched_annotations': 'test ConditionalDetr image processor with batched COCO detection and panoptic annotations including padding and box normalization', 'test_conditional_detr_resize_pad_strategy': 'test ConditionalDetr image processor resizing and padding strategies with max_height/max_width and longest_edge/shortest_edge configurations'}
```

## File: huggingface_transformers/tests/models/conditional_detr/test_modeling_conditional_detr.py

Prompts

```
['test the ConditionalDetrImageProcessingTest class for image processing correctness and properties', 'test ConditionalDetr image processor with COCO detection annotations and verify pixel values, boxes, and labels', 'test ConditionalDetr image processor with COCO panoptic annotations and verify masks, boxes, and segmentation output', 'test ConditionalDetr image processor with batched COCO detection and panoptic annotations including padding and box normalization', 'test ConditionalDetr image processor resizing and padding strategies with max_height/max_width and longest_edge/shortest_edge configurations', 'test the ConditionalDetrModel forward pass and verify output tensor shapes', 'test ConditionalDetrForObjectDetection inference with pixel values and verify logits and box predictions', 'test encoder and decoder attention outputs and verify attention tensor shapes across all model classes', 'test the reverse weight-loading mapping for model serialization and deserialization round-trips', 'test pretrained ConditionalDetrForObjectDetection inference on an image and verify post-processed detection results', 'test that auxiliary loss outputs are produced when auxiliary_loss config flag is enabled', 'test backbone configuration with timm and pretrained HF resnet backbones', 'test gradient retention on encoder hidden states, encoder attentions, decoder attentions, and cross attentions']
```

Usage

```
{'test_conditional_detr_model': 'test the ConditionalDetrModel forward pass and verify output tensor shapes', 'test_conditional_detr_object_detection': 'test ConditionalDetrForObjectDetection inference with pixel values and verify logits and box predictions', 'test_attention_outputs': 'test encoder and decoder attention outputs and verify attention tensor shapes across all model classes', 'test_reverse_loading_mapping': 'test the reverse weight-loading mapping for model serialization and deserialization round-trips', 'test_inference_object_detection': 'test pretrained ConditionalDetrForObjectDetection inference on an image and verify post-processed detection results', 'test_forward_auxiliary_loss': 'test that auxiliary loss outputs are produced when auxiliary_loss config flag is enabled', 'test_backbone_selection': 'test backbone configuration with timm and pretrained HF resnet backbones', 'test_retain_grad_hidden_states_attentions': 'test gradient retention on encoder hidden states, encoder attentions, decoder attentions, and cross attentions'}
```

