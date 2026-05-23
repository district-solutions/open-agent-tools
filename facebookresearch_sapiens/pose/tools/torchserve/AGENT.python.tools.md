# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/tools/torchserve/mmpose2torchserve.py

Prompts

```
['convert an MMPose model config and checkpoint to a TorchServe .mar archive file', 'run the CLI tool to convert an MMPose model to TorchServe format with output folder', 'parse command line arguments for config, checkpoint, output folder, model name, version, and force flags', 'package an MMPose model with config and checkpoint into a TorchServe deployable archive', 'load a non-local MMPose checkpoint using mmcv CheckpointLoader and save it locally', 'initialize the MMPoseHandler with a TorchServe context to load the pose estimation model', 'preprocess base64 encoded image data into OpenCV images for pose model inference', 'run pose estimation inference on images using top-down or bottom-up model detection', 'postprocess pose estimation results to extract keypoints as a list of dictionaries', 'review the MMPoseHandler class and its TorchServe handler methods for pose estimation', 'run pose model inference on an image using both native PyTorch and TorchServe and compare results', 'run top-down pose estimation inference on an image using an MMPose model and save visualization', 'run bottom-up pose estimation inference on an image using an AssociativeEmbedding model and save visualization', 'test a TorchServe endpoint by sending an image and comparing server results against native PyTorch inference', 'visualize pose estimation results from both PyTorch and TorchServe inference and save as PNG images']
```

Usage

```
{'convert_mmpose_to_torchserve': 'convert an MMPose model config and checkpoint to a TorchServe .mar archive file', 'run_mmpose2torchserve_cli': 'run the CLI tool to convert an MMPose model to TorchServe format with output folder', 'parse_args_mmpose2torchserve': 'parse command line arguments for config, checkpoint, output folder, model name, version, and force flags', 'package_mmpose_model': 'package an MMPose model with config and checkpoint into a TorchServe deployable archive', 'load_remote_checkpoint': 'load a non-local MMPose checkpoint using mmcv CheckpointLoader and save it locally'}
```

## File: facebookresearch_sapiens/pose/tools/torchserve/mmpose_handler.py

Prompts

```
['convert an MMPose model config and checkpoint to a TorchServe .mar archive file', 'run the CLI tool to convert an MMPose model to TorchServe format with output folder', 'parse command line arguments for config, checkpoint, output folder, model name, version, and force flags', 'package an MMPose model with config and checkpoint into a TorchServe deployable archive', 'load a non-local MMPose checkpoint using mmcv CheckpointLoader and save it locally', 'initialize the MMPoseHandler with a TorchServe context to load the pose estimation model', 'preprocess base64 encoded image data into OpenCV images for pose model inference', 'run pose estimation inference on images using top-down or bottom-up model detection', 'postprocess pose estimation results to extract keypoints as a list of dictionaries', 'review the MMPoseHandler class and its TorchServe handler methods for pose estimation', 'run pose model inference on an image using both native PyTorch and TorchServe and compare results', 'run top-down pose estimation inference on an image using an MMPose model and save visualization', 'run bottom-up pose estimation inference on an image using an AssociativeEmbedding model and save visualization', 'test a TorchServe endpoint by sending an image and comparing server results against native PyTorch inference', 'visualize pose estimation results from both PyTorch and TorchServe inference and save as PNG images']
```

Usage

```
{'initialize_MMPoseHandler': 'initialize the MMPoseHandler with a TorchServe context to load the pose estimation model', 'preprocess_MMPoseHandler': 'preprocess base64 encoded image data into OpenCV images for pose model inference', 'inference_MMPoseHandler': 'run pose estimation inference on images using top-down or bottom-up model detection', 'postprocess_MMPoseHandler': 'postprocess pose estimation results to extract keypoints as a list of dictionaries', 'review_MMPoseHandler': 'review the MMPoseHandler class and its TorchServe handler methods for pose estimation'}
```

## File: facebookresearch_sapiens/pose/tools/torchserve/test_torchserver.py

Prompts

```
['convert an MMPose model config and checkpoint to a TorchServe .mar archive file', 'run the CLI tool to convert an MMPose model to TorchServe format with output folder', 'parse command line arguments for config, checkpoint, output folder, model name, version, and force flags', 'package an MMPose model with config and checkpoint into a TorchServe deployable archive', 'load a non-local MMPose checkpoint using mmcv CheckpointLoader and save it locally', 'initialize the MMPoseHandler with a TorchServe context to load the pose estimation model', 'preprocess base64 encoded image data into OpenCV images for pose model inference', 'run pose estimation inference on images using top-down or bottom-up model detection', 'postprocess pose estimation results to extract keypoints as a list of dictionaries', 'review the MMPoseHandler class and its TorchServe handler methods for pose estimation', 'run pose model inference on an image using both native PyTorch and TorchServe and compare results', 'run top-down pose estimation inference on an image using an MMPose model and save visualization', 'run bottom-up pose estimation inference on an image using an AssociativeEmbedding model and save visualization', 'test a TorchServe endpoint by sending an image and comparing server results against native PyTorch inference', 'visualize pose estimation results from both PyTorch and TorchServe inference and save as PNG images']
```

Usage

```
{'run_pose_inference_torchserve': 'run pose model inference on an image using both native PyTorch and TorchServe and compare results', 'run_top_down_pose_inference': 'run top-down pose estimation inference on an image using an MMPose model and save visualization', 'run_bottom_up_pose_inference': 'run bottom-up pose estimation inference on an image using an AssociativeEmbedding model and save visualization', 'test_torchserve_endpoint': 'test a TorchServe endpoint by sending an image and comparing server results against native PyTorch inference', 'visualize_pose_results': 'visualize pose estimation results from both PyTorch and TorchServe inference and save as PNG images'}
```

