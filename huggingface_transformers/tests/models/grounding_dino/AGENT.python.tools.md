# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/grounding_dino/test_image_processing_grounding_dino.py

Prompts

```
['test the GroundingDinoImageProcessingTester class that generates fake image inputs and expected output shapes for unit testing', 'test the GroundingDinoImageProcessingTest class with AnnotationFormatTestMixin and ImageProcessingTestMixin for GroundingDino image processing', 'test post_process_object_detection method that filters GroundingDinoObjectDetectionOutput predictions by threshold and returns scores, labels, and boxes', 'test encoding images with COCO detection annotations using GroundingDinoImageProcessor with return_tensors pt', 'test batched image processing with COCO detection annotations including padding and bounding box adjustment for multiple images', 'test the GroundingDinoForObjectDetection model forward pass and loss computation with pixel values and input ids', 'test the GroundingDinoModel encoder output shape for vision and text inputs', 'test encoder, decoder, and cross attention output shapes and layer counts for GroundingDino models', 'run inference on a GroundingDinoForObjectDetection model with an image and text prompt for zero-shot object detection', 'test that batched text inputs produce equivalent logits to individual text inputs via cross attention masking']
```

Usage

```
{'test_GroundingDinoImageProcessingTester': 'test the GroundingDinoImageProcessingTester class that generates fake image inputs and expected output shapes for unit testing', 'test_GroundingDinoImageProcessingTest': 'test the GroundingDinoImageProcessingTest class with AnnotationFormatTestMixin and ImageProcessingTestMixin for GroundingDino image processing', 'test_post_process_object_detection': 'test post_process_object_detection method that filters GroundingDinoObjectDetectionOutput predictions by threshold and returns scores, labels, and boxes', 'test_call_pytorch_with_coco_detection_annotations': 'test encoding images with COCO detection annotations using GroundingDinoImageProcessor with return_tensors pt', 'test_batched_coco_detection_annotations': 'test batched image processing with COCO detection annotations including padding and bounding box adjustment for multiple images'}
```

## File: huggingface_transformers/tests/models/grounding_dino/test_modeling_grounding_dino.py

Prompts

```
['test the GroundingDinoImageProcessingTester class that generates fake image inputs and expected output shapes for unit testing', 'test the GroundingDinoImageProcessingTest class with AnnotationFormatTestMixin and ImageProcessingTestMixin for GroundingDino image processing', 'test post_process_object_detection method that filters GroundingDinoObjectDetectionOutput predictions by threshold and returns scores, labels, and boxes', 'test encoding images with COCO detection annotations using GroundingDinoImageProcessor with return_tensors pt', 'test batched image processing with COCO detection annotations including padding and bounding box adjustment for multiple images', 'test the GroundingDinoForObjectDetection model forward pass and loss computation with pixel values and input ids', 'test the GroundingDinoModel encoder output shape for vision and text inputs', 'test encoder, decoder, and cross attention output shapes and layer counts for GroundingDino models', 'run inference on a GroundingDinoForObjectDetection model with an image and text prompt for zero-shot object detection', 'test that batched text inputs produce equivalent logits to individual text inputs via cross attention masking']
```

Usage

```
{'test_GroundingDinoForObjectDetection': 'test the GroundingDinoForObjectDetection model forward pass and loss computation with pixel values and input ids', 'test_GroundingDinoModel': 'test the GroundingDinoModel encoder output shape for vision and text inputs', 'test_attention_outputs': 'test encoder, decoder, and cross attention output shapes and layer counts for GroundingDino models', 'test_inference_object_detection_head': 'run inference on a GroundingDinoForObjectDetection model with an image and text prompt for zero-shot object detection', 'test_cross_attention_mask': 'test that batched text inputs produce equivalent logits to individual text inputs via cross attention masking'}
```

