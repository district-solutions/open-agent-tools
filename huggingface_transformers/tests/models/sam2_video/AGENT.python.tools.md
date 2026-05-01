# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam2_video/test_modeling_sam2_video.py

Prompts

```
['run SAM2 video model inference on a video frame using a single point prompt to generate segmentation masks', 'run SAM2 video model inference with multiple point prompts to segment objects and propagate masks across frames', 'run SAM2 video model inference using bounding box prompts to generate segmentation masks and track across video frames', 'run SAM2 video model to track multiple objects simultaneously using point prompts and propagate masks across frames', 'run SAM2 video model inference on streamed video frames one at a time with point prompts and mask propagation', 'test Sam2VideoProcessor with image inputs only and verify pixel values are resized to 1024x1024', 'test Sam2VideoProcessor with image and segmentation mask inputs and verify label shapes are 256x256', 'test post_process_masks method to resize dummy masks back to original image dimensions', 'create a Sam2VideoProcessor instance with image_processor and video_processor components for video segmentation', 'review the post_process_masks method that resizes masks to original sizes and validates input types']
```

Usage

```
{'run_sam2_video_single_point_inference': 'run SAM2 video model inference on a video frame using a single point prompt to generate segmentation masks', 'run_sam2_video_multi_point_inference': 'run SAM2 video model inference with multiple point prompts to segment objects and propagate masks across frames', 'run_sam2_video_bbox_inference': 'run SAM2 video model inference using bounding box prompts to generate segmentation masks and track across video frames', 'run_sam2_video_multi_object_tracking': 'run SAM2 video model to track multiple objects simultaneously using point prompts and propagate masks across frames', 'run_sam2_video_streamed_inference': 'run SAM2 video model inference on streamed video frames one at a time with point prompts and mask propagation'}
```

## File: huggingface_transformers/tests/models/sam2_video/test_processor_sam2_video.py

Prompts

```
['run SAM2 video model inference on a video frame using a single point prompt to generate segmentation masks', 'run SAM2 video model inference with multiple point prompts to segment objects and propagate masks across frames', 'run SAM2 video model inference using bounding box prompts to generate segmentation masks and track across video frames', 'run SAM2 video model to track multiple objects simultaneously using point prompts and propagate masks across frames', 'run SAM2 video model inference on streamed video frames one at a time with point prompts and mask propagation', 'test Sam2VideoProcessor with image inputs only and verify pixel values are resized to 1024x1024', 'test Sam2VideoProcessor with image and segmentation mask inputs and verify label shapes are 256x256', 'test post_process_masks method to resize dummy masks back to original image dimensions', 'create a Sam2VideoProcessor instance with image_processor and video_processor components for video segmentation', 'review the post_process_masks method that resizes masks to original sizes and validates input types']
```

Usage

```
{'test_sam2video_processor_no_masks': 'test Sam2VideoProcessor with image inputs only and verify pixel values are resized to 1024x1024', 'test_sam2video_processor_with_masks': 'test Sam2VideoProcessor with image and segmentation mask inputs and verify label shapes are 256x256', 'test_post_process_masks': 'test post_process_masks method to resize dummy masks back to original image dimensions', 'create_sam2video_processor': 'create a Sam2VideoProcessor instance with image_processor and video_processor components for video segmentation', 'review_post_process_masks': 'review the post_process_masks method that resizes masks to original sizes and validates input types'}
```

