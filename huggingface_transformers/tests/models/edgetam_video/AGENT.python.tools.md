# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/edgetam_video/test_modeling_edgetam_video.py

Prompts

```
['run EdgeTamVideoModel inference on a video frame using a single point prompt to generate segmentation masks', 'run propagate_in_video_iterator to track object masks across multiple video frames after an initial point prompt', 'run EdgeTamVideoModel inference with multiple object IDs and point prompts to segment several objects in a video', 'run EdgeTamVideoModel inference using a bounding box input instead of points to generate video segmentation masks', 'run frame-by-frame inference on a streamed video by processing each frame individually with the processor and model']
```

Usage

```
{'run_video_mask_generation_with_point_prompt': 'run EdgeTamVideoModel inference on a video frame using a single point prompt to generate segmentation masks', 'run_video_mask_propagation_across_frames': 'run propagate_in_video_iterator to track object masks across multiple video frames after an initial point prompt', 'run_multi_object_video_segmentation': 'run EdgeTamVideoModel inference with multiple object IDs and point prompts to segment several objects in a video', 'run_video_segmentation_with_bounding_box': 'run EdgeTamVideoModel inference using a bounding box input instead of points to generate video segmentation masks', 'run_streamed_video_inference': 'run frame-by-frame inference on a streamed video by processing each frame individually with the processor and model'}
```

