# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/florence2/test_modeling_florence2.py

Prompts

```
['test Florence2ForConditionalGeneration model inference using eager attention implementation with detailed caption task', 'test Florence2ForConditionalGeneration model inference using SDPA attention implementation with referring expression segmentation task', 'test Florence2 model batched inference with multiple images and prompts using region proposal and detection tasks', 'test Florence2 large model inference with OCR with region and caption tasks using SDPA attention', 'review the Florence2VisionText2TextModelTester class that creates configs and input tensors for Florence2 model tests', 'test the Florence2Processor _construct_prompts method with task tokens like OCR and CAPTION', 'test the post_processor quantize and dequantize methods for bounding boxes and points', 'test parse_description_with_bboxes_from_text_and_spans to extract bounding boxes from Florence2 output text', 'test parse_description_with_polygons_from_text_and_spans to extract polygon coordinates from Florence2 output text', 'test post_process_generation for pure text, object detection bboxes, and OCR with region tasks']
```

Usage

```
{'test_Florence2ForConditionalGeneration_eager': 'test Florence2ForConditionalGeneration model inference using eager attention implementation with detailed caption task', 'test_Florence2ForConditionalGeneration_sdpa': 'test Florence2ForConditionalGeneration model inference using SDPA attention implementation with referring expression segmentation task', 'test_Florence2_batching_inference': 'test Florence2 model batched inference with multiple images and prompts using region proposal and detection tasks', 'test_Florence2_large_model': 'test Florence2 large model inference with OCR with region and caption tasks using SDPA attention', 'review_Florence2VisionText2TextModelTester': 'review the Florence2VisionText2TextModelTester class that creates configs and input tensors for Florence2 model tests'}
```

## File: huggingface_transformers/tests/models/florence2/test_processing_florence2.py

Prompts

```
['test Florence2ForConditionalGeneration model inference using eager attention implementation with detailed caption task', 'test Florence2ForConditionalGeneration model inference using SDPA attention implementation with referring expression segmentation task', 'test Florence2 model batched inference with multiple images and prompts using region proposal and detection tasks', 'test Florence2 large model inference with OCR with region and caption tasks using SDPA attention', 'review the Florence2VisionText2TextModelTester class that creates configs and input tensors for Florence2 model tests', 'test the Florence2Processor _construct_prompts method with task tokens like OCR and CAPTION', 'test the post_processor quantize and dequantize methods for bounding boxes and points', 'test parse_description_with_bboxes_from_text_and_spans to extract bounding boxes from Florence2 output text', 'test parse_description_with_polygons_from_text_and_spans to extract polygon coordinates from Florence2 output text', 'test post_process_generation for pure text, object detection bboxes, and OCR with region tasks']
```

Usage

```
{'test_construct_prompts': 'test the Florence2Processor _construct_prompts method with task tokens like OCR and CAPTION', 'test_quantize_dequantize': 'test the post_processor quantize and dequantize methods for bounding boxes and points', 'test_parse_description_with_bboxes': 'test parse_description_with_bboxes_from_text_and_spans to extract bounding boxes from Florence2 output text', 'test_parse_description_with_polygons': 'test parse_description_with_polygons_from_text_and_spans to extract polygon coordinates from Florence2 output text', 'test_post_process_generation': 'test post_process_generation for pure text, object detection bboxes, and OCR with region tasks'}
```

