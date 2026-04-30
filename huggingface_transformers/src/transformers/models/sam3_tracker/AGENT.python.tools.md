# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sam3_tracker/modeling_sam3_tracker.py

Prompts

```
['run SAM3 Tracker to generate segmentation masks from input image and point prompts', 'get image embeddings from pixel values using the SAM3 Tracker vision encoder', 'get prompt embeddings from input points, labels, boxes, or masks for the mask decoder', 'build a SAM3 Tracker model from config for image segmentation with points and boxes', 'test dynamic multimask selection via stability scoring in the SAM3 Tracker mask decoder', 'build a Sam3TrackerProcessor instance with an image processor and target size for segment-anything-3 tracking', 'run the Sam3TrackerProcessor.__call__ method to process images, points, labels, and bounding boxes into normalized tensors', 'test the _normalize_coordinates method to scale point or bounding-box coordinates from original image size to target size', 'test the _validate_single_input method to validate nested list or tensor inputs for points, labels, and boxes with expected depth and coordinate size', 'summarize the post_process_masks method to remove padding and upscale predicted masks back to original image dimensions']
```

Usage

```
{'run_sam3_tracker_segmentation': 'run SAM3 Tracker to generate segmentation masks from input image and point prompts', 'get_image_embeddings': 'get image embeddings from pixel values using the SAM3 Tracker vision encoder', 'get_prompt_embeddings': 'get prompt embeddings from input points, labels, boxes, or masks for the mask decoder', 'build_sam3_tracker_model': 'build a SAM3 Tracker model from config for image segmentation with points and boxes', 'test_dynamic_multimask': 'test dynamic multimask selection via stability scoring in the SAM3 Tracker mask decoder'}
```

## File: huggingface_transformers/src/transformers/models/sam3_tracker/processing_sam3_tracker.py

Prompts

```
['run SAM3 Tracker to generate segmentation masks from input image and point prompts', 'get image embeddings from pixel values using the SAM3 Tracker vision encoder', 'get prompt embeddings from input points, labels, boxes, or masks for the mask decoder', 'build a SAM3 Tracker model from config for image segmentation with points and boxes', 'test dynamic multimask selection via stability scoring in the SAM3 Tracker mask decoder', 'build a Sam3TrackerProcessor instance with an image processor and target size for segment-anything-3 tracking', 'run the Sam3TrackerProcessor.__call__ method to process images, points, labels, and bounding boxes into normalized tensors', 'test the _normalize_coordinates method to scale point or bounding-box coordinates from original image size to target size', 'test the _validate_single_input method to validate nested list or tensor inputs for points, labels, and boxes with expected depth and coordinate size', 'summarize the post_process_masks method to remove padding and upscale predicted masks back to original image dimensions']
```

Usage

```
{'build_sam3_processor': 'build a Sam3TrackerProcessor instance with an image processor and target size for segment-anything-3 tracking', 'run_sam3_processor_call': 'run the Sam3TrackerProcessor.__call__ method to process images, points, labels, and bounding boxes into normalized tensors', 'test_normalize_coordinates': 'test the _normalize_coordinates method to scale point or bounding-box coordinates from original image size to target size', 'test_validate_single_input': 'test the _validate_single_input method to validate nested list or tensor inputs for points, labels, and boxes with expected depth and coordinate size', 'summarize_post_process_masks': 'summarize the post_process_masks method to remove padding and upscale predicted masks back to original image dimensions'}
```

