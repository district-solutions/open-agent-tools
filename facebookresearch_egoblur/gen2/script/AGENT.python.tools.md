# Agent Python Tools

- repo: facebookresearch/egoblur
- repo_uri: https://github.com/facebookresearch/egoblur

## File: facebookresearch_egoblur/gen2/script/demo_ego_blur_gen2.py

Prompts

```
['run the ego blur demo to detect and blur faces in an input image', 'run the ego blur demo to detect and blur faces and license plates in a video', 'run the ego blur demo with custom face and license plate score thresholds', 'run the ego blur demo with a camera name to auto-select detection thresholds', 'run the ego blur demo with a scale factor to expand detection bounding boxes', 'create an EgoblurDetector instance with a TorchScript model path to detect faces in video frames', 'create an EgoblurDetector instance with a TorchScript model path to detect license plates in video frames', 'run the EgoblurDetector on a batched image tensor and return bounding boxes in XYXY format', 'review the GPUResizeShortestEdge class that resizes batched GPU tensors using F.interpolate without CPU round-trips', 'test the FrameDetections dataclass to store face and license plate bounding boxes with scores and classes', 'apply gaussian blur to bounding box regions on an image using detection coordinates', 'validate argparse namespace inputs for face model paths, thresholds, and I/O file existence', 'scale a bounding box by a factor while keeping it centered and clamped to image bounds', 'read an image from disk with OpenCV and convert it to a PyTorch tensor on GPU', 'create the parent directory for an output file path if it does not already exist', 'run the vrs_blur_gen2 CLI to blur faces and license plates in a VRS file camera streams', 'run the workflow function to process VRS camera streams with face and license plate detection and blur', 'create an H265Decoder instance to decode H.265 byte buffers from VRS camera streams into numpy images', 'create an H265Encoder instance to encode numpy frames to H.265 bytes with automatic GPU or CPU fallback', 'run batched face and license plate detection then blur on a list of BGR images']
```

Usage

```
{'run_ego_blur_on_image': 'run the ego blur demo to detect and blur faces in an input image', 'run_ego_blur_on_video': 'run the ego blur demo to detect and blur faces and license plates in a video', 'run_ego_blur_with_custom_thresholds': 'run the ego blur demo with custom face and license plate score thresholds', 'run_ego_blur_with_camera_name': 'run the ego blur demo with a camera name to auto-select detection thresholds', 'run_ego_blur_with_scale_factor': 'run the ego blur demo with a scale factor to expand detection bounding boxes'}
```

## File: facebookresearch_egoblur/gen2/script/predictor.py

Prompts

```
['run the ego blur demo to detect and blur faces in an input image', 'run the ego blur demo to detect and blur faces and license plates in a video', 'run the ego blur demo with custom face and license plate score thresholds', 'run the ego blur demo with a camera name to auto-select detection thresholds', 'run the ego blur demo with a scale factor to expand detection bounding boxes', 'create an EgoblurDetector instance with a TorchScript model path to detect faces in video frames', 'create an EgoblurDetector instance with a TorchScript model path to detect license plates in video frames', 'run the EgoblurDetector on a batched image tensor and return bounding boxes in XYXY format', 'review the GPUResizeShortestEdge class that resizes batched GPU tensors using F.interpolate without CPU round-trips', 'test the FrameDetections dataclass to store face and license plate bounding boxes with scores and classes', 'apply gaussian blur to bounding box regions on an image using detection coordinates', 'validate argparse namespace inputs for face model paths, thresholds, and I/O file existence', 'scale a bounding box by a factor while keeping it centered and clamped to image bounds', 'read an image from disk with OpenCV and convert it to a PyTorch tensor on GPU', 'create the parent directory for an output file path if it does not already exist', 'run the vrs_blur_gen2 CLI to blur faces and license plates in a VRS file camera streams', 'run the workflow function to process VRS camera streams with face and license plate detection and blur', 'create an H265Decoder instance to decode H.265 byte buffers from VRS camera streams into numpy images', 'create an H265Encoder instance to encode numpy frames to H.265 bytes with automatic GPU or CPU fallback', 'run batched face and license plate detection then blur on a list of BGR images']
```

Usage

```
{'create_face_detector': 'create an EgoblurDetector instance with a TorchScript model path to detect faces in video frames', 'create_license_plate_detector': 'create an EgoblurDetector instance with a TorchScript model path to detect license plates in video frames', 'run_detection_inference': 'run the EgoblurDetector on a batched image tensor and return bounding boxes in XYXY format', 'review_gpu_resize': 'review the GPUResizeShortestEdge class that resizes batched GPU tensors using F.interpolate without CPU round-trips', 'test_frame_detections': 'test the FrameDetections dataclass to store face and license plate bounding boxes with scores and classes'}
```

## File: facebookresearch_egoblur/gen2/script/utils.py

Prompts

```
['run the ego blur demo to detect and blur faces in an input image', 'run the ego blur demo to detect and blur faces and license plates in a video', 'run the ego blur demo with custom face and license plate score thresholds', 'run the ego blur demo with a camera name to auto-select detection thresholds', 'run the ego blur demo with a scale factor to expand detection bounding boxes', 'create an EgoblurDetector instance with a TorchScript model path to detect faces in video frames', 'create an EgoblurDetector instance with a TorchScript model path to detect license plates in video frames', 'run the EgoblurDetector on a batched image tensor and return bounding boxes in XYXY format', 'review the GPUResizeShortestEdge class that resizes batched GPU tensors using F.interpolate without CPU round-trips', 'test the FrameDetections dataclass to store face and license plate bounding boxes with scores and classes', 'apply gaussian blur to bounding box regions on an image using detection coordinates', 'validate argparse namespace inputs for face model paths, thresholds, and I/O file existence', 'scale a bounding box by a factor while keeping it centered and clamped to image bounds', 'read an image from disk with OpenCV and convert it to a PyTorch tensor on GPU', 'create the parent directory for an output file path if it does not already exist', 'run the vrs_blur_gen2 CLI to blur faces and license plates in a VRS file camera streams', 'run the workflow function to process VRS camera streams with face and license plate detection and blur', 'create an H265Decoder instance to decode H.265 byte buffers from VRS camera streams into numpy images', 'create an H265Encoder instance to encode numpy frames to H.265 bytes with automatic GPU or CPU fallback', 'run batched face and license plate detection then blur on a list of BGR images']
```

Usage

```
{'visualize_detections_with_blur': 'apply gaussian blur to bounding box regions on an image using detection coordinates', 'validate_cli_args': 'validate argparse namespace inputs for face model paths, thresholds, and I/O file existence', 'scale_bounding_box': 'scale a bounding box by a factor while keeping it centered and clamped to image bounds', 'read_and_convert_image': 'read an image from disk with OpenCV and convert it to a PyTorch tensor on GPU', 'create_output_directory': 'create the parent directory for an output file path if it does not already exist'}
```

## File: facebookresearch_egoblur/gen2/script/vrs_blur_gen2.py

Prompts

```
['run the ego blur demo to detect and blur faces in an input image', 'run the ego blur demo to detect and blur faces and license plates in a video', 'run the ego blur demo with custom face and license plate score thresholds', 'run the ego blur demo with a camera name to auto-select detection thresholds', 'run the ego blur demo with a scale factor to expand detection bounding boxes', 'create an EgoblurDetector instance with a TorchScript model path to detect faces in video frames', 'create an EgoblurDetector instance with a TorchScript model path to detect license plates in video frames', 'run the EgoblurDetector on a batched image tensor and return bounding boxes in XYXY format', 'review the GPUResizeShortestEdge class that resizes batched GPU tensors using F.interpolate without CPU round-trips', 'test the FrameDetections dataclass to store face and license plate bounding boxes with scores and classes', 'apply gaussian blur to bounding box regions on an image using detection coordinates', 'validate argparse namespace inputs for face model paths, thresholds, and I/O file existence', 'scale a bounding box by a factor while keeping it centered and clamped to image bounds', 'read an image from disk with OpenCV and convert it to a PyTorch tensor on GPU', 'create the parent directory for an output file path if it does not already exist', 'run the vrs_blur_gen2 CLI to blur faces and license plates in a VRS file camera streams', 'run the workflow function to process VRS camera streams with face and license plate detection and blur', 'create an H265Decoder instance to decode H.265 byte buffers from VRS camera streams into numpy images', 'create an H265Encoder instance to encode numpy frames to H.265 bytes with automatic GPU or CPU fallback', 'run batched face and license plate detection then blur on a list of BGR images']
```

Usage

```
{'run_vrs_blur_cli': 'run the vrs_blur_gen2 CLI to blur faces and license plates in a VRS file camera streams', 'run_workflow_function': 'run the workflow function to process VRS camera streams with face and license plate detection and blur', 'create_h265_decoder': 'create an H265Decoder instance to decode H.265 byte buffers from VRS camera streams into numpy images', 'create_h265_encoder': 'create an H265Encoder instance to encode numpy frames to H.265 bytes with automatic GPU or CPU fallback', 'run_detect_and_blur_batch': 'run batched face and license plate detection then blur on a list of BGR images'}
```

