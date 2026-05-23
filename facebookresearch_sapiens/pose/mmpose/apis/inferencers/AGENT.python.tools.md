# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/apis/inferencers/base_mmpose_inferencer.py

Prompts

```
['load model weights and dataset metadata from a checkpoint file into an MMPose model', 'convert image paths, video files, directories, or numpy arrays into a list for batch inference', 'set up a webcam generator that yields frames from a camera device for real-time pose inference', 'visualize pose estimation predictions with configurable keypoints, bounding boxes, and output directory', 'finalize video processing by releasing the video writer and saving frame predictions to a JSON file', 'run the MMPoseInferencer class to perform 2D keypoint detection on images using a pretrained pose2d model', 'run the MMPoseInferencer class to perform 3D pose estimation by providing both pose2d and pose3d model configs', 'call the MMPoseInferencer with inputs to get pose predictions and visualization results with optional batch processing', 'visualize pose estimation predictions using the visualize method with configurable radius, thickness, and keypoint threshold', 'preprocess input images or video frames into a model-feedable format using the preprocess method with collate function', 'run 2D pose estimation on images or videos using a pretrained MMPose model with optional human detection', 'run real-time 2D pose estimation from a webcam feed with automatic visualization display enabled', 'run top-down 2D pose estimation with an integrated MMDetection object detector for bounding boxes', 'run bottom-up 2D pose estimation on images without requiring a separate human detection model', 'run 2D pose estimation and visualize predicted heatmaps with mmpose or openpose skeleton style', 'run the Pose3DInferencer on an image or video to estimate 3D human pose keypoints', 'create a Pose3DInferencer instance with a 3D pose model and optional 2D pose detection model', 'preprocess a single input image to extract 2D keypoints and prepare data for 3D pose lifting', 'perform a forward pass through the 3D pose model and post-process the lifted keypoints', 'visualize 3D pose estimation predictions on input images with optional bounding boxes and keypoints']
```

Usage

```
{'load_weights_to_model': 'load model weights and dataset metadata from a checkpoint file into an MMPose model', 'inputs_to_list': 'convert image paths, video files, directories, or numpy arrays into a list for batch inference', 'get_webcam_inputs': 'set up a webcam generator that yields frames from a camera device for real-time pose inference', 'visualize_predictions': 'visualize pose estimation predictions with configurable keypoints, bounding boxes, and output directory', 'finalize_video_processing': 'finalize video processing by releasing the video writer and saving frame predictions to a JSON file'}
```

## File: facebookresearch_sapiens/pose/mmpose/apis/inferencers/mmpose_inferencer.py

Prompts

```
['load model weights and dataset metadata from a checkpoint file into an MMPose model', 'convert image paths, video files, directories, or numpy arrays into a list for batch inference', 'set up a webcam generator that yields frames from a camera device for real-time pose inference', 'visualize pose estimation predictions with configurable keypoints, bounding boxes, and output directory', 'finalize video processing by releasing the video writer and saving frame predictions to a JSON file', 'run the MMPoseInferencer class to perform 2D keypoint detection on images using a pretrained pose2d model', 'run the MMPoseInferencer class to perform 3D pose estimation by providing both pose2d and pose3d model configs', 'call the MMPoseInferencer with inputs to get pose predictions and visualization results with optional batch processing', 'visualize pose estimation predictions using the visualize method with configurable radius, thickness, and keypoint threshold', 'preprocess input images or video frames into a model-feedable format using the preprocess method with collate function', 'run 2D pose estimation on images or videos using a pretrained MMPose model with optional human detection', 'run real-time 2D pose estimation from a webcam feed with automatic visualization display enabled', 'run top-down 2D pose estimation with an integrated MMDetection object detector for bounding boxes', 'run bottom-up 2D pose estimation on images without requiring a separate human detection model', 'run 2D pose estimation and visualize predicted heatmaps with mmpose or openpose skeleton style', 'run the Pose3DInferencer on an image or video to estimate 3D human pose keypoints', 'create a Pose3DInferencer instance with a 3D pose model and optional 2D pose detection model', 'preprocess a single input image to extract 2D keypoints and prepare data for 3D pose lifting', 'perform a forward pass through the 3D pose model and post-process the lifted keypoints', 'visualize 3D pose estimation predictions on input images with optional bounding boxes and keypoints']
```

Usage

```
{'run_MMPoseInferencer_2D_pose': 'run the MMPoseInferencer class to perform 2D keypoint detection on images using a pretrained pose2d model', 'run_MMPoseInferencer_3D_pose': 'run the MMPoseInferencer class to perform 3D pose estimation by providing both pose2d and pose3d model configs', 'call_MMPoseInferencer_predict': 'call the MMPoseInferencer with inputs to get pose predictions and visualization results with optional batch processing', 'visualize_MMPoseInferencer_predictions': 'visualize pose estimation predictions using the visualize method with configurable radius, thickness, and keypoint threshold', 'preprocess_MMPoseInferencer_inputs': 'preprocess input images or video frames into a model-feedable format using the preprocess method with collate function'}
```

## File: facebookresearch_sapiens/pose/mmpose/apis/inferencers/pose2d_inferencer.py

Prompts

```
['load model weights and dataset metadata from a checkpoint file into an MMPose model', 'convert image paths, video files, directories, or numpy arrays into a list for batch inference', 'set up a webcam generator that yields frames from a camera device for real-time pose inference', 'visualize pose estimation predictions with configurable keypoints, bounding boxes, and output directory', 'finalize video processing by releasing the video writer and saving frame predictions to a JSON file', 'run the MMPoseInferencer class to perform 2D keypoint detection on images using a pretrained pose2d model', 'run the MMPoseInferencer class to perform 3D pose estimation by providing both pose2d and pose3d model configs', 'call the MMPoseInferencer with inputs to get pose predictions and visualization results with optional batch processing', 'visualize pose estimation predictions using the visualize method with configurable radius, thickness, and keypoint threshold', 'preprocess input images or video frames into a model-feedable format using the preprocess method with collate function', 'run 2D pose estimation on images or videos using a pretrained MMPose model with optional human detection', 'run real-time 2D pose estimation from a webcam feed with automatic visualization display enabled', 'run top-down 2D pose estimation with an integrated MMDetection object detector for bounding boxes', 'run bottom-up 2D pose estimation on images without requiring a separate human detection model', 'run 2D pose estimation and visualize predicted heatmaps with mmpose or openpose skeleton style', 'run the Pose3DInferencer on an image or video to estimate 3D human pose keypoints', 'create a Pose3DInferencer instance with a 3D pose model and optional 2D pose detection model', 'preprocess a single input image to extract 2D keypoints and prepare data for 3D pose lifting', 'perform a forward pass through the 3D pose model and post-process the lifted keypoints', 'visualize 3D pose estimation predictions on input images with optional bounding boxes and keypoints']
```

Usage

```
{'run_pose2d_inference': 'run 2D pose estimation on images or videos using a pretrained MMPose model with optional human detection', 'run_pose2d_webcam': 'run real-time 2D pose estimation from a webcam feed with automatic visualization display enabled', 'run_pose2d_topdown': 'run top-down 2D pose estimation with an integrated MMDetection object detector for bounding boxes', 'run_pose2d_bottomup': 'run bottom-up 2D pose estimation on images without requiring a separate human detection model', 'run_pose2d_heatmap': 'run 2D pose estimation and visualize predicted heatmaps with mmpose or openpose skeleton style'}
```

## File: facebookresearch_sapiens/pose/mmpose/apis/inferencers/pose3d_inferencer.py

Prompts

```
['load model weights and dataset metadata from a checkpoint file into an MMPose model', 'convert image paths, video files, directories, or numpy arrays into a list for batch inference', 'set up a webcam generator that yields frames from a camera device for real-time pose inference', 'visualize pose estimation predictions with configurable keypoints, bounding boxes, and output directory', 'finalize video processing by releasing the video writer and saving frame predictions to a JSON file', 'run the MMPoseInferencer class to perform 2D keypoint detection on images using a pretrained pose2d model', 'run the MMPoseInferencer class to perform 3D pose estimation by providing both pose2d and pose3d model configs', 'call the MMPoseInferencer with inputs to get pose predictions and visualization results with optional batch processing', 'visualize pose estimation predictions using the visualize method with configurable radius, thickness, and keypoint threshold', 'preprocess input images or video frames into a model-feedable format using the preprocess method with collate function', 'run 2D pose estimation on images or videos using a pretrained MMPose model with optional human detection', 'run real-time 2D pose estimation from a webcam feed with automatic visualization display enabled', 'run top-down 2D pose estimation with an integrated MMDetection object detector for bounding boxes', 'run bottom-up 2D pose estimation on images without requiring a separate human detection model', 'run 2D pose estimation and visualize predicted heatmaps with mmpose or openpose skeleton style', 'run the Pose3DInferencer on an image or video to estimate 3D human pose keypoints', 'create a Pose3DInferencer instance with a 3D pose model and optional 2D pose detection model', 'preprocess a single input image to extract 2D keypoints and prepare data for 3D pose lifting', 'perform a forward pass through the 3D pose model and post-process the lifted keypoints', 'visualize 3D pose estimation predictions on input images with optional bounding boxes and keypoints']
```

Usage

```
{'run_Pose3DInferencer': 'run the Pose3DInferencer on an image or video to estimate 3D human pose keypoints', 'create_Pose3DInferencer': 'create a Pose3DInferencer instance with a 3D pose model and optional 2D pose detection model', 'preprocess_Pose3DInferencer_preprocess_single': 'preprocess a single input image to extract 2D keypoints and prepare data for 3D pose lifting', 'forward_Pose3DInferencer_forward': 'perform a forward pass through the 3D pose model and post-process the lifted keypoints', 'visualize_Pose3DInferencer_visualize': 'visualize 3D pose estimation predictions on input images with optional bounding boxes and keypoints'}
```

