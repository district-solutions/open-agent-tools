# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/app_server/vision/optical_flow.py

Prompts

```
['build a Ray Serve deployment that calculates optical flow and motion scores for video frames', 'run a POST request to the optical flow endpoint with a video file path and sampling parameters', 'calculate motion scores and optical flow vectors from video frames using Farneback algorithm', 'create a TorchCodecVideoDataset with configurable start, end, stride, and sampling rate for video processing', 'configure the optical flow deployment with custom torch batch size and return flow options', 'build a Ray Serve deployment that encodes images, videos, and text using a CLIP model', 'run inference on an image, video, or text input via the perception encoder POST endpoint', 'create a custom collate function that stacks video frame tensors and preserves metadata as a list', 'refactor the binary search method to find the largest GPU-memory-safe batch size for the model', 'review the FastAPI POST endpoint that handles image, video, and text encoding requests with timeout support', 'create a TorchCodecVideoDataset to load frames or clips from a video file with configurable window size and stride', 'create a TorchCodecVideoDataset in seconds mode to sample video windows by timestamp instead of frame index', 'build a torchvision transform pipeline that resizes, normalizes, and converts video frames to float tensors', 'build a torchvision transform pipeline with center crop that normalizes frames to the range [-1.0, 1.0]', 'create a retry wrapper that executes a function up to 4 times with 0.5 second delays between attempts']
```

Usage

```
{'build_optical_flow_deployment': 'build a Ray Serve deployment that calculates optical flow and motion scores for video frames', 'run_optical_flow_endpoint': 'run a POST request to the optical flow endpoint with a video file path and sampling parameters', 'calculate_motion_metrics': 'calculate motion scores and optical flow vectors from video frames using Farneback algorithm', 'create_torchcodec_video_dataset': 'create a TorchCodecVideoDataset with configurable start, end, stride, and sampling rate for video processing', 'configure_optical_flow_batch_size': 'configure the optical flow deployment with custom torch batch size and return flow options'}
```

## File: facebookresearch_matrix/matrix/app_server/vision/perception_encoder.py

Prompts

```
['build a Ray Serve deployment that calculates optical flow and motion scores for video frames', 'run a POST request to the optical flow endpoint with a video file path and sampling parameters', 'calculate motion scores and optical flow vectors from video frames using Farneback algorithm', 'create a TorchCodecVideoDataset with configurable start, end, stride, and sampling rate for video processing', 'configure the optical flow deployment with custom torch batch size and return flow options', 'build a Ray Serve deployment that encodes images, videos, and text using a CLIP model', 'run inference on an image, video, or text input via the perception encoder POST endpoint', 'create a custom collate function that stacks video frame tensors and preserves metadata as a list', 'refactor the binary search method to find the largest GPU-memory-safe batch size for the model', 'review the FastAPI POST endpoint that handles image, video, and text encoding requests with timeout support', 'create a TorchCodecVideoDataset to load frames or clips from a video file with configurable window size and stride', 'create a TorchCodecVideoDataset in seconds mode to sample video windows by timestamp instead of frame index', 'build a torchvision transform pipeline that resizes, normalizes, and converts video frames to float tensors', 'build a torchvision transform pipeline with center crop that normalizes frames to the range [-1.0, 1.0]', 'create a retry wrapper that executes a function up to 4 times with 0.5 second delays between attempts']
```

Usage

```
{'build_perception_encoder_deployment': 'build a Ray Serve deployment that encodes images, videos, and text using a CLIP model', 'run_perception_encoder_inference': 'run inference on an image, video, or text input via the perception encoder POST endpoint', 'create_custom_collate_fn': 'create a custom collate function that stacks video frame tensors and preserves metadata as a list', 'refactor_optimal_batch_size': 'refactor the binary search method to find the largest GPU-memory-safe batch size for the model', 'review_perception_encoder_api': 'review the FastAPI POST endpoint that handles image, video, and text encoding requests with timeout support'}
```

## File: facebookresearch_matrix/matrix/app_server/vision/utils.py

Prompts

```
['build a Ray Serve deployment that calculates optical flow and motion scores for video frames', 'run a POST request to the optical flow endpoint with a video file path and sampling parameters', 'calculate motion scores and optical flow vectors from video frames using Farneback algorithm', 'create a TorchCodecVideoDataset with configurable start, end, stride, and sampling rate for video processing', 'configure the optical flow deployment with custom torch batch size and return flow options', 'build a Ray Serve deployment that encodes images, videos, and text using a CLIP model', 'run inference on an image, video, or text input via the perception encoder POST endpoint', 'create a custom collate function that stacks video frame tensors and preserves metadata as a list', 'refactor the binary search method to find the largest GPU-memory-safe batch size for the model', 'review the FastAPI POST endpoint that handles image, video, and text encoding requests with timeout support', 'create a TorchCodecVideoDataset to load frames or clips from a video file with configurable window size and stride', 'create a TorchCodecVideoDataset in seconds mode to sample video windows by timestamp instead of frame index', 'build a torchvision transform pipeline that resizes, normalizes, and converts video frames to float tensors', 'build a torchvision transform pipeline with center crop that normalizes frames to the range [-1.0, 1.0]', 'create a retry wrapper that executes a function up to 4 times with 0.5 second delays between attempts']
```

Usage

```
{'create_video_dataset': 'create a TorchCodecVideoDataset to load frames or clips from a video file with configurable window size and stride', 'create_video_dataset_seconds': 'create a TorchCodecVideoDataset in seconds mode to sample video windows by timestamp instead of frame index', 'build_image_transform': 'build a torchvision transform pipeline that resizes, normalizes, and converts video frames to float tensors', 'build_image_transform_center_crop': 'build a torchvision transform pipeline with center crop that normalizes frames to the range [-1.0, 1.0]', 'create_retry_wrapper': 'create a retry wrapper that executes a function up to 4 times with 0.5 second delays between attempts'}
```

