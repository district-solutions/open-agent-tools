# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/tools/build_detector.py

Prompts

```
['create a HumanDetector instance using ViTDet for human detection on CUDA device', 'create a HumanDetector instance using SAM3 for human detection with text prompts', 'run human detection on an image using the configured detector and return bounding boxes', 'load a Detectron2 ViTDet model from a config file and checkpoint URL or local path', 'run Detectron2 ViTDet inference on an image and return sorted bounding boxes with confidence filtering', 'create a FOVEstimator instance using the MoGe2 model for camera field of view estimation', 'get camera intrinsics matrix from an RGB image using the FOVEstimator get_cam_intrinsics method', 'load a pretrained MoGe2 model from HuggingFace and move it to the specified device', 'run MoGe2 inference on an input image and return normalized camera intrinsics with batch dimension', 'denormalize a camera intrinsic matrix by scaling normalized focal length and principal point to absolute pixel values', 'create a HumanSegmentor instance using SAM2 or SAM3 model for human segmentation on CUDA', 'run the HumanSegmentor run_sam method with an image and bounding boxes to get segmentation masks', 'load a SAM2 image predictor from a checkpoint path and config for human segmentation', 'load a SAM3 image model and processor for text-prompted human segmentation inference', 'run SAM2 inference on an image with bounding boxes to return masks and confidence scores', "visualize each person's 2D keypoints, bounding boxes, and 3D mesh separately with front and side views", "visualize all persons' keypoints and meshes rendered together in a single composite image with front and side views", 'draw a skeleton overlay on an image using the module-level SkeletonVisualizer instance with MHR70 pose metadata', 'render a 3D body mesh onto an image using the Renderer with configurable focal length and mesh color', 'draw bounding box rectangles for body, left hand, and right hand regions on the visualization image']
```

Usage

```
{'create_HumanDetector_vitdet': 'create a HumanDetector instance using ViTDet for human detection on CUDA device', 'create_HumanDetector_sam3': 'create a HumanDetector instance using SAM3 for human detection with text prompts', 'run_human_detection': 'run human detection on an image using the configured detector and return bounding boxes', 'load_detectron2_vitdet': 'load a Detectron2 ViTDet model from a config file and checkpoint URL or local path', 'run_detectron2_vitdet': 'run Detectron2 ViTDet inference on an image and return sorted bounding boxes with confidence filtering'}
```

## File: facebookresearch_sam-3d-body/tools/build_fov_estimator.py

Prompts

```
['create a HumanDetector instance using ViTDet for human detection on CUDA device', 'create a HumanDetector instance using SAM3 for human detection with text prompts', 'run human detection on an image using the configured detector and return bounding boxes', 'load a Detectron2 ViTDet model from a config file and checkpoint URL or local path', 'run Detectron2 ViTDet inference on an image and return sorted bounding boxes with confidence filtering', 'create a FOVEstimator instance using the MoGe2 model for camera field of view estimation', 'get camera intrinsics matrix from an RGB image using the FOVEstimator get_cam_intrinsics method', 'load a pretrained MoGe2 model from HuggingFace and move it to the specified device', 'run MoGe2 inference on an input image and return normalized camera intrinsics with batch dimension', 'denormalize a camera intrinsic matrix by scaling normalized focal length and principal point to absolute pixel values', 'create a HumanSegmentor instance using SAM2 or SAM3 model for human segmentation on CUDA', 'run the HumanSegmentor run_sam method with an image and bounding boxes to get segmentation masks', 'load a SAM2 image predictor from a checkpoint path and config for human segmentation', 'load a SAM3 image model and processor for text-prompted human segmentation inference', 'run SAM2 inference on an image with bounding boxes to return masks and confidence scores', "visualize each person's 2D keypoints, bounding boxes, and 3D mesh separately with front and side views", "visualize all persons' keypoints and meshes rendered together in a single composite image with front and side views", 'draw a skeleton overlay on an image using the module-level SkeletonVisualizer instance with MHR70 pose metadata', 'render a 3D body mesh onto an image using the Renderer with configurable focal length and mesh color', 'draw bounding box rectangles for body, left hand, and right hand regions on the visualization image']
```

Usage

```
{'create_FOVEstimator': 'create a FOVEstimator instance using the MoGe2 model for camera field of view estimation', 'get_cam_intrinsics': 'get camera intrinsics matrix from an RGB image using the FOVEstimator get_cam_intrinsics method', 'load_moge': 'load a pretrained MoGe2 model from HuggingFace and move it to the specified device', 'run_moge': 'run MoGe2 inference on an input image and return normalized camera intrinsics with batch dimension', 'denormalize_f': 'denormalize a camera intrinsic matrix by scaling normalized focal length and principal point to absolute pixel values'}
```

## File: facebookresearch_sam-3d-body/tools/build_sam.py

Prompts

```
['create a HumanDetector instance using ViTDet for human detection on CUDA device', 'create a HumanDetector instance using SAM3 for human detection with text prompts', 'run human detection on an image using the configured detector and return bounding boxes', 'load a Detectron2 ViTDet model from a config file and checkpoint URL or local path', 'run Detectron2 ViTDet inference on an image and return sorted bounding boxes with confidence filtering', 'create a FOVEstimator instance using the MoGe2 model for camera field of view estimation', 'get camera intrinsics matrix from an RGB image using the FOVEstimator get_cam_intrinsics method', 'load a pretrained MoGe2 model from HuggingFace and move it to the specified device', 'run MoGe2 inference on an input image and return normalized camera intrinsics with batch dimension', 'denormalize a camera intrinsic matrix by scaling normalized focal length and principal point to absolute pixel values', 'create a HumanSegmentor instance using SAM2 or SAM3 model for human segmentation on CUDA', 'run the HumanSegmentor run_sam method with an image and bounding boxes to get segmentation masks', 'load a SAM2 image predictor from a checkpoint path and config for human segmentation', 'load a SAM3 image model and processor for text-prompted human segmentation inference', 'run SAM2 inference on an image with bounding boxes to return masks and confidence scores', "visualize each person's 2D keypoints, bounding boxes, and 3D mesh separately with front and side views", "visualize all persons' keypoints and meshes rendered together in a single composite image with front and side views", 'draw a skeleton overlay on an image using the module-level SkeletonVisualizer instance with MHR70 pose metadata', 'render a 3D body mesh onto an image using the Renderer with configurable focal length and mesh color', 'draw bounding box rectangles for body, left hand, and right hand regions on the visualization image']
```

Usage

```
{'create_HumanSegmentor': 'create a HumanSegmentor instance using SAM2 or SAM3 model for human segmentation on CUDA', 'run_sam_HumanSegmentor': 'run the HumanSegmentor run_sam method with an image and bounding boxes to get segmentation masks', 'load_sam2_predictor': 'load a SAM2 image predictor from a checkpoint path and config for human segmentation', 'load_sam3_predictor': 'load a SAM3 image model and processor for text-prompted human segmentation inference', 'run_sam2_inference': 'run SAM2 inference on an image with bounding boxes to return masks and confidence scores'}
```

## File: facebookresearch_sam-3d-body/tools/vis_utils.py

Prompts

```
['create a HumanDetector instance using ViTDet for human detection on CUDA device', 'create a HumanDetector instance using SAM3 for human detection with text prompts', 'run human detection on an image using the configured detector and return bounding boxes', 'load a Detectron2 ViTDet model from a config file and checkpoint URL or local path', 'run Detectron2 ViTDet inference on an image and return sorted bounding boxes with confidence filtering', 'create a FOVEstimator instance using the MoGe2 model for camera field of view estimation', 'get camera intrinsics matrix from an RGB image using the FOVEstimator get_cam_intrinsics method', 'load a pretrained MoGe2 model from HuggingFace and move it to the specified device', 'run MoGe2 inference on an input image and return normalized camera intrinsics with batch dimension', 'denormalize a camera intrinsic matrix by scaling normalized focal length and principal point to absolute pixel values', 'create a HumanSegmentor instance using SAM2 or SAM3 model for human segmentation on CUDA', 'run the HumanSegmentor run_sam method with an image and bounding boxes to get segmentation masks', 'load a SAM2 image predictor from a checkpoint path and config for human segmentation', 'load a SAM3 image model and processor for text-prompted human segmentation inference', 'run SAM2 inference on an image with bounding boxes to return masks and confidence scores', "visualize each person's 2D keypoints, bounding boxes, and 3D mesh separately with front and side views", "visualize all persons' keypoints and meshes rendered together in a single composite image with front and side views", 'draw a skeleton overlay on an image using the module-level SkeletonVisualizer instance with MHR70 pose metadata', 'render a 3D body mesh onto an image using the Renderer with configurable focal length and mesh color', 'draw bounding box rectangles for body, left hand, and right hand regions on the visualization image']
```

Usage

```
{'visualize_sample_per_person': "visualize each person's 2D keypoints, bounding boxes, and 3D mesh separately with front and side views", 'visualize_sample_together_all_persons': "visualize all persons' keypoints and meshes rendered together in a single composite image with front and side views", 'draw_skeleton_with_visualizer': 'draw a skeleton overlay on an image using the module-level SkeletonVisualizer instance with MHR70 pose metadata', 'render_mesh_with_renderer': 'render a 3D body mesh onto an image using the Renderer with configurable focal length and mesh color', 'draw_bbox_rectangles': 'draw bounding box rectangles for body, left hand, and right hand regions on the visualization image'}
```

