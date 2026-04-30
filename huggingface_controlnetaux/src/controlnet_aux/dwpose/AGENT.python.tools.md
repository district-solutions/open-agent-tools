# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/dwpose/util.py

Prompts

```
['resize a numpy image array to target dimensions using smart interpolation based on scale factor', 'resize a numpy image array by fx and fy scale factors using smart interpolation', 'draw body pose keypoints and limb connections on a canvas image using candidate and subset arrays', 'detect hand bounding box regions from body pose keypoints and subset for each person', 'detect face bounding box regions from body pose keypoints using head and facial landmark positions', 'build a Wholebody instance with default YOLOX detector and DWpose estimator for human pose estimation', 'build a Wholebody instance with custom detector and pose estimator config paths and checkpoint files', 'run the Wholebody callable on an image to detect human keypoints and confidence scores', 'move the Wholebody detector and pose estimator models to a specified device like GPU', 'review the Wholebody class to understand how MMPose keypoints are remapped to OpenPose format']
```

Usage

```
{'smart_resize_image': 'resize a numpy image array to target dimensions using smart interpolation based on scale factor', 'smart_resize_k_image': 'resize a numpy image array by fx and fy scale factors using smart interpolation', 'draw_bodypose_on_canvas': 'draw body pose keypoints and limb connections on a canvas image using candidate and subset arrays', 'detect_hand_regions': 'detect hand bounding box regions from body pose keypoints and subset for each person', 'detect_face_regions': 'detect face bounding box regions from body pose keypoints using head and facial landmark positions'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/dwpose/wholebody.py

Prompts

```
['resize a numpy image array to target dimensions using smart interpolation based on scale factor', 'resize a numpy image array by fx and fy scale factors using smart interpolation', 'draw body pose keypoints and limb connections on a canvas image using candidate and subset arrays', 'detect hand bounding box regions from body pose keypoints and subset for each person', 'detect face bounding box regions from body pose keypoints using head and facial landmark positions', 'build a Wholebody instance with default YOLOX detector and DWpose estimator for human pose estimation', 'build a Wholebody instance with custom detector and pose estimator config paths and checkpoint files', 'run the Wholebody callable on an image to detect human keypoints and confidence scores', 'move the Wholebody detector and pose estimator models to a specified device like GPU', 'review the Wholebody class to understand how MMPose keypoints are remapped to OpenPose format']
```

Usage

```
{'build_wholebody_pose_estimator': 'build a Wholebody instance with default YOLOX detector and DWpose estimator for human pose estimation', 'build_wholebody_custom_config': 'build a Wholebody instance with custom detector and pose estimator config paths and checkpoint files', 'run_wholebody_inference': 'run the Wholebody callable on an image to detect human keypoints and confidence scores', 'move_wholebody_to_device': 'move the Wholebody detector and pose estimator models to a specified device like GPU', 'review_wholebody_keypoint_mapping': 'review the Wholebody class to understand how MMPose keypoints are remapped to OpenPose format'}
```

