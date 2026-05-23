# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/pose_estimator/PoseEstimator.py

Prompts

```
['build a PoseEstimator with a 18-layer ResNet encoder for monocular pose estimation', 'run the PoseEstimator forward pass on stacked image frames to predict camera poses', 'create a ResnetEncoder with configurable layer depth for multi-image feature extraction', 'test the PoseDecoder to decode encoder features into axisangle and translation outputs', 'review the transformation_from_parameters utility to convert axisangle and translation into 4x4 matrices', 'build a PoseDecoder network from encoder channel configs and input feature counts', 'create a PoseDecoder with custom stride for pose estimation from multi-frame features', 'test the PoseDecoder forward pass with simulated multi-scale encoder feature lists', 'review the PoseDecoder conv layers and axisangle translation output structure', 'refactor the PoseDecoder to support a custom number of frames to predict for', 'build a ResnetEncoder with 18 or 50 layers to extract multi-scale feature maps from input images', 'create a ResNet model that accepts multiple stacked input images using resnet_multiimage_input function', 'test the ResnetEncoder forward pass by passing an input image tensor and retrieving feature pyramid outputs', 'review the ResNetMultiImageInput class to understand how it adapts the first conv layer for multi-image input', 'summarize the resnet_multiimage_input function which constructs ResNet-18 or ResNet-50 with optional ImageNet pretrained weights', 'build a python module to convert axisangle and translation into a 4x4 transformation matrix', 'create a function that converts a translation vector into a 4x4 transformation matrix', 'build a python module to convert an axisangle rotation vector into a 4x4 rotation matrix', 'test the transformation_from_parameters function with the invert flag to get the inverse matrix', 'review the pose estimator utility functions for converting axisangle and translation to transformation matrices']
```

Usage

```
{'build_pose_estimator_model': 'build a PoseEstimator with a 18-layer ResNet encoder for monocular pose estimation', 'run_pose_estimator_forward': 'run the PoseEstimator forward pass on stacked image frames to predict camera poses', 'create_resnet_encoder': 'create a ResnetEncoder with configurable layer depth for multi-image feature extraction', 'test_pose_decoder': 'test the PoseDecoder to decode encoder features into axisangle and translation outputs', 'review_transformation_from_parameters': 'review the transformation_from_parameters utility to convert axisangle and translation into 4x4 matrices'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/pose_estimator/pose_decoder.py

Prompts

```
['build a PoseEstimator with a 18-layer ResNet encoder for monocular pose estimation', 'run the PoseEstimator forward pass on stacked image frames to predict camera poses', 'create a ResnetEncoder with configurable layer depth for multi-image feature extraction', 'test the PoseDecoder to decode encoder features into axisangle and translation outputs', 'review the transformation_from_parameters utility to convert axisangle and translation into 4x4 matrices', 'build a PoseDecoder network from encoder channel configs and input feature counts', 'create a PoseDecoder with custom stride for pose estimation from multi-frame features', 'test the PoseDecoder forward pass with simulated multi-scale encoder feature lists', 'review the PoseDecoder conv layers and axisangle translation output structure', 'refactor the PoseDecoder to support a custom number of frames to predict for', 'build a ResnetEncoder with 18 or 50 layers to extract multi-scale feature maps from input images', 'create a ResNet model that accepts multiple stacked input images using resnet_multiimage_input function', 'test the ResnetEncoder forward pass by passing an input image tensor and retrieving feature pyramid outputs', 'review the ResNetMultiImageInput class to understand how it adapts the first conv layer for multi-image input', 'summarize the resnet_multiimage_input function which constructs ResNet-18 or ResNet-50 with optional ImageNet pretrained weights', 'build a python module to convert axisangle and translation into a 4x4 transformation matrix', 'create a function that converts a translation vector into a 4x4 transformation matrix', 'build a python module to convert an axisangle rotation vector into a 4x4 rotation matrix', 'test the transformation_from_parameters function with the invert flag to get the inverse matrix', 'review the pose estimator utility functions for converting axisangle and translation to transformation matrices']
```

Usage

```
{'build_pose_decoder_network': 'build a PoseDecoder network from encoder channel configs and input feature counts', 'create_pose_decoder_with_stride': 'create a PoseDecoder with custom stride for pose estimation from multi-frame features', 'test_pose_decoder_forward': 'test the PoseDecoder forward pass with simulated multi-scale encoder feature lists', 'review_pose_decoder_architecture': 'review the PoseDecoder conv layers and axisangle translation output structure', 'refactor_pose_decoder_frames': 'refactor the PoseDecoder to support a custom number of frames to predict for'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/pose_estimator/resnet_encoder.py

Prompts

```
['build a PoseEstimator with a 18-layer ResNet encoder for monocular pose estimation', 'run the PoseEstimator forward pass on stacked image frames to predict camera poses', 'create a ResnetEncoder with configurable layer depth for multi-image feature extraction', 'test the PoseDecoder to decode encoder features into axisangle and translation outputs', 'review the transformation_from_parameters utility to convert axisangle and translation into 4x4 matrices', 'build a PoseDecoder network from encoder channel configs and input feature counts', 'create a PoseDecoder with custom stride for pose estimation from multi-frame features', 'test the PoseDecoder forward pass with simulated multi-scale encoder feature lists', 'review the PoseDecoder conv layers and axisangle translation output structure', 'refactor the PoseDecoder to support a custom number of frames to predict for', 'build a ResnetEncoder with 18 or 50 layers to extract multi-scale feature maps from input images', 'create a ResNet model that accepts multiple stacked input images using resnet_multiimage_input function', 'test the ResnetEncoder forward pass by passing an input image tensor and retrieving feature pyramid outputs', 'review the ResNetMultiImageInput class to understand how it adapts the first conv layer for multi-image input', 'summarize the resnet_multiimage_input function which constructs ResNet-18 or ResNet-50 with optional ImageNet pretrained weights', 'build a python module to convert axisangle and translation into a 4x4 transformation matrix', 'create a function that converts a translation vector into a 4x4 transformation matrix', 'build a python module to convert an axisangle rotation vector into a 4x4 rotation matrix', 'test the transformation_from_parameters function with the invert flag to get the inverse matrix', 'review the pose estimator utility functions for converting axisangle and translation to transformation matrices']
```

Usage

```
{'build_resnet_encoder': 'build a ResnetEncoder with 18 or 50 layers to extract multi-scale feature maps from input images', 'create_multiimage_resnet': 'create a ResNet model that accepts multiple stacked input images using resnet_multiimage_input function', 'test_ResnetEncoder_forward': 'test the ResnetEncoder forward pass by passing an input image tensor and retrieving feature pyramid outputs', 'review_ResNetMultiImageInput': 'review the ResNetMultiImageInput class to understand how it adapts the first conv layer for multi-image input', 'summarize_resnet_multiimage_input': 'summarize the resnet_multiimage_input function which constructs ResNet-18 or ResNet-50 with optional ImageNet pretrained weights'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/pose_estimator/utils.py

Prompts

```
['build a PoseEstimator with a 18-layer ResNet encoder for monocular pose estimation', 'run the PoseEstimator forward pass on stacked image frames to predict camera poses', 'create a ResnetEncoder with configurable layer depth for multi-image feature extraction', 'test the PoseDecoder to decode encoder features into axisangle and translation outputs', 'review the transformation_from_parameters utility to convert axisangle and translation into 4x4 matrices', 'build a PoseDecoder network from encoder channel configs and input feature counts', 'create a PoseDecoder with custom stride for pose estimation from multi-frame features', 'test the PoseDecoder forward pass with simulated multi-scale encoder feature lists', 'review the PoseDecoder conv layers and axisangle translation output structure', 'refactor the PoseDecoder to support a custom number of frames to predict for', 'build a ResnetEncoder with 18 or 50 layers to extract multi-scale feature maps from input images', 'create a ResNet model that accepts multiple stacked input images using resnet_multiimage_input function', 'test the ResnetEncoder forward pass by passing an input image tensor and retrieving feature pyramid outputs', 'review the ResNetMultiImageInput class to understand how it adapts the first conv layer for multi-image input', 'summarize the resnet_multiimage_input function which constructs ResNet-18 or ResNet-50 with optional ImageNet pretrained weights', 'build a python module to convert axisangle and translation into a 4x4 transformation matrix', 'create a function that converts a translation vector into a 4x4 transformation matrix', 'build a python module to convert an axisangle rotation vector into a 4x4 rotation matrix', 'test the transformation_from_parameters function with the invert flag to get the inverse matrix', 'review the pose estimator utility functions for converting axisangle and translation to transformation matrices']
```

Usage

```
{'build_transformation_matrix': 'build a python module to convert axisangle and translation into a 4x4 transformation matrix', 'create_translation_matrix': 'create a function that converts a translation vector into a 4x4 transformation matrix', 'build_rotation_matrix': 'build a python module to convert an axisangle rotation vector into a 4x4 rotation matrix', 'test_transformation_invert': 'test the transformation_from_parameters function with the invert flag to get the inverse matrix', 'review_pose_estimator_utils': 'review the pose estimator utility functions for converting axisangle and translation to transformation matrices'}
```

