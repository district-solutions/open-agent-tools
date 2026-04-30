# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vitpose/convert_vitpose_to_hf.py

Prompts

```
['convert a VitPose checkpoint from the original repository to Hugging Face Transformers format', 'run the VitPose conversion CLI script with model name and output path arguments', 'get the VitPose configuration for a specified model variant including backbone and decoder settings', 'convert original VitPose checkpoint keys to Hugging Face key naming convention using regex mappings', 'verify the converted VitPose model produces logits matching the original checkpoint within tolerance', 'build a VitPoseImageProcessorPil instance with custom affine transform and normalization settings', 'preprocess a batch of images with bounding boxes using the VitPoseImageProcessorPil', 'transform model heatmaps into keypoint predictions with center and scale', 'post-process VitPoseEstimatorOutput heatmaps into structured keypoint predictions with scores and bounding boxes', 'compute center and scale coordinates from a COCO-format bounding box for pose estimation', 'preprocess images with bounding boxes using VitPoseImageProcessor for pose estimation input', 'post_process pose estimation outputs from VitPose model into keypoint predictions with bounding boxes', 'extract keypoint predictions and scores from model heatmaps using DARK post-processing and coordinate transformation', 'convert a COCO-format bounding box into center coordinates and scale values for pose estimation', 'get keypoint coordinates and confidence scores from 4D heatmap tensors predicted by the pose model', 'run the VitPoseForPoseEstimation model to predict human pose heatmaps from input images', 'create a VitPoseSimpleDecoder with ReLU activation, upsampling and convolution to generate heatmaps', 'build a VitPoseClassicDecoder with deconvolutional blocks and batch normalization for heatmap generation', 'initialize a VitPosePreTrainedModel with truncated normal weight initialization for linear conv and layer norm modules', 'flip VitPose predicted heatmaps back to original orientation using flip pairs and target type']
```

Usage

```
{'convert_vitpose_model': 'convert a VitPose checkpoint from the original repository to Hugging Face Transformers format', 'run_vitpose_conversion_cli': 'run the VitPose conversion CLI script with model name and output path arguments', 'get_vitpose_config': 'get the VitPose configuration for a specified model variant including backbone and decoder settings', 'convert_weight_keys': 'convert original VitPose checkpoint keys to Hugging Face key naming convention using regex mappings', 'verify_vitpose_logits': 'verify the converted VitPose model produces logits matching the original checkpoint within tolerance'}
```

## File: huggingface_transformers/src/transformers/models/vitpose/image_processing_pil_vitpose.py

Prompts

```
['convert a VitPose checkpoint from the original repository to Hugging Face Transformers format', 'run the VitPose conversion CLI script with model name and output path arguments', 'get the VitPose configuration for a specified model variant including backbone and decoder settings', 'convert original VitPose checkpoint keys to Hugging Face key naming convention using regex mappings', 'verify the converted VitPose model produces logits matching the original checkpoint within tolerance', 'build a VitPoseImageProcessorPil instance with custom affine transform and normalization settings', 'preprocess a batch of images with bounding boxes using the VitPoseImageProcessorPil', 'transform model heatmaps into keypoint predictions with center and scale', 'post-process VitPoseEstimatorOutput heatmaps into structured keypoint predictions with scores and bounding boxes', 'compute center and scale coordinates from a COCO-format bounding box for pose estimation', 'preprocess images with bounding boxes using VitPoseImageProcessor for pose estimation input', 'post_process pose estimation outputs from VitPose model into keypoint predictions with bounding boxes', 'extract keypoint predictions and scores from model heatmaps using DARK post-processing and coordinate transformation', 'convert a COCO-format bounding box into center coordinates and scale values for pose estimation', 'get keypoint coordinates and confidence scores from 4D heatmap tensors predicted by the pose model', 'run the VitPoseForPoseEstimation model to predict human pose heatmaps from input images', 'create a VitPoseSimpleDecoder with ReLU activation, upsampling and convolution to generate heatmaps', 'build a VitPoseClassicDecoder with deconvolutional blocks and batch normalization for heatmap generation', 'initialize a VitPosePreTrainedModel with truncated normal weight initialization for linear conv and layer norm modules', 'flip VitPose predicted heatmaps back to original orientation using flip pairs and target type']
```

Usage

```
{'build_VitPoseImageProcessorPil': 'build a VitPoseImageProcessorPil instance with custom affine transform and normalization settings', 'preprocess_images_with_boxes': 'preprocess a batch of images with bounding boxes using the VitPoseImageProcessorPil', 'transform_heatmaps_to_keypoints': 'transform model heatmaps into keypoint predictions with center and scale', 'post_process_pose_estimation': 'post-process VitPoseEstimatorOutput heatmaps into structured keypoint predictions with scores and bounding boxes', 'compute_box_to_center_and_scale': 'compute center and scale coordinates from a COCO-format bounding box for pose estimation'}
```

## File: huggingface_transformers/src/transformers/models/vitpose/image_processing_vitpose.py

Prompts

```
['convert a VitPose checkpoint from the original repository to Hugging Face Transformers format', 'run the VitPose conversion CLI script with model name and output path arguments', 'get the VitPose configuration for a specified model variant including backbone and decoder settings', 'convert original VitPose checkpoint keys to Hugging Face key naming convention using regex mappings', 'verify the converted VitPose model produces logits matching the original checkpoint within tolerance', 'build a VitPoseImageProcessorPil instance with custom affine transform and normalization settings', 'preprocess a batch of images with bounding boxes using the VitPoseImageProcessorPil', 'transform model heatmaps into keypoint predictions with center and scale', 'post-process VitPoseEstimatorOutput heatmaps into structured keypoint predictions with scores and bounding boxes', 'compute center and scale coordinates from a COCO-format bounding box for pose estimation', 'preprocess images with bounding boxes using VitPoseImageProcessor for pose estimation input', 'post_process pose estimation outputs from VitPose model into keypoint predictions with bounding boxes', 'extract keypoint predictions and scores from model heatmaps using DARK post-processing and coordinate transformation', 'convert a COCO-format bounding box into center coordinates and scale values for pose estimation', 'get keypoint coordinates and confidence scores from 4D heatmap tensors predicted by the pose model', 'run the VitPoseForPoseEstimation model to predict human pose heatmaps from input images', 'create a VitPoseSimpleDecoder with ReLU activation, upsampling and convolution to generate heatmaps', 'build a VitPoseClassicDecoder with deconvolutional blocks and batch normalization for heatmap generation', 'initialize a VitPosePreTrainedModel with truncated normal weight initialization for linear conv and layer norm modules', 'flip VitPose predicted heatmaps back to original orientation using flip pairs and target type']
```

Usage

```
{'preprocess_VitPoseImageProcessor': 'preprocess images with bounding boxes using VitPoseImageProcessor for pose estimation input', 'post_process_VitPoseImageProcessor': 'post_process pose estimation outputs from VitPose model into keypoint predictions with bounding boxes', 'keypoints_from_heatmaps': 'extract keypoint predictions and scores from model heatmaps using DARK post-processing and coordinate transformation', 'box_to_center_and_scale': 'convert a COCO-format bounding box into center coordinates and scale values for pose estimation', 'get_keypoint_predictions': 'get keypoint coordinates and confidence scores from 4D heatmap tensors predicted by the pose model'}
```

## File: huggingface_transformers/src/transformers/models/vitpose/modeling_vitpose.py

Prompts

```
['convert a VitPose checkpoint from the original repository to Hugging Face Transformers format', 'run the VitPose conversion CLI script with model name and output path arguments', 'get the VitPose configuration for a specified model variant including backbone and decoder settings', 'convert original VitPose checkpoint keys to Hugging Face key naming convention using regex mappings', 'verify the converted VitPose model produces logits matching the original checkpoint within tolerance', 'build a VitPoseImageProcessorPil instance with custom affine transform and normalization settings', 'preprocess a batch of images with bounding boxes using the VitPoseImageProcessorPil', 'transform model heatmaps into keypoint predictions with center and scale', 'post-process VitPoseEstimatorOutput heatmaps into structured keypoint predictions with scores and bounding boxes', 'compute center and scale coordinates from a COCO-format bounding box for pose estimation', 'preprocess images with bounding boxes using VitPoseImageProcessor for pose estimation input', 'post_process pose estimation outputs from VitPose model into keypoint predictions with bounding boxes', 'extract keypoint predictions and scores from model heatmaps using DARK post-processing and coordinate transformation', 'convert a COCO-format bounding box into center coordinates and scale values for pose estimation', 'get keypoint coordinates and confidence scores from 4D heatmap tensors predicted by the pose model', 'run the VitPoseForPoseEstimation model to predict human pose heatmaps from input images', 'create a VitPoseSimpleDecoder with ReLU activation, upsampling and convolution to generate heatmaps', 'build a VitPoseClassicDecoder with deconvolutional blocks and batch normalization for heatmap generation', 'initialize a VitPosePreTrainedModel with truncated normal weight initialization for linear conv and layer norm modules', 'flip VitPose predicted heatmaps back to original orientation using flip pairs and target type']
```

Usage

```
{'run_VitPoseForPoseEstimation': 'run the VitPoseForPoseEstimation model to predict human pose heatmaps from input images', 'create_VitPoseSimpleDecoder': 'create a VitPoseSimpleDecoder with ReLU activation, upsampling and convolution to generate heatmaps', 'build_VitPoseClassicDecoder': 'build a VitPoseClassicDecoder with deconvolutional blocks and batch normalization for heatmap generation', 'initialize_VitPosePreTrainedModel': 'initialize a VitPosePreTrainedModel with truncated normal weight initialization for linear conv and layer norm modules', 'flip_VitPose_heatmaps': 'flip VitPose predicted heatmaps back to original orientation using flip pairs and target type'}
```

