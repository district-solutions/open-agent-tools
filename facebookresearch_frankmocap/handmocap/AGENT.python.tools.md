# Agent Python Tools

- repo: facebookresearch/frankmocap
- repo_uri: https://github.com/facebookresearch/frankmocap

## File: facebookresearch_frankmocap/handmocap/hand_bbox_detector.py

Prompts

```
['detect hand bounding boxes in third-view images using a type-agnostic Detectron2 hand detector', 'detect hand bounding boxes in ego-centric images using a type-aware Faster R-CNN hand-object detector', 'detect body bounding boxes and poses from a BGR image using the underlying body pose estimator', 'initialize a HandBboxDetector with third_view mode to detect hands and body poses in third-person images', 'initialize a HandBboxDetector with ego_centric mode to detect left and right hands in first-person images', 'initialize a HandMocap instance with a regressor checkpoint path and SMPL model directory', 'run hand pose regression on an image with detected hand bounding boxes to get 3D vertices', 'crop and normalize a hand region from an image using a bounding box for left or right hand', 'pad a hand bounding box crop to a square and resize it to 224x224 pixels', 'convert predicted SMPL hand vertices from model space to original image pixel coordinates']
```

Usage

```
{'detect_hand_bbox_third_view': 'detect hand bounding boxes in third-view images using a type-agnostic Detectron2 hand detector', 'detect_hand_bbox_ego_centric': 'detect hand bounding boxes in ego-centric images using a type-aware Faster R-CNN hand-object detector', 'detect_body_bbox': 'detect body bounding boxes and poses from a BGR image using the underlying body pose estimator', 'init_hand_bbox_detector_third_view': 'initialize a HandBboxDetector with third_view mode to detect hands and body poses in third-person images', 'init_hand_bbox_detector_ego_centric': 'initialize a HandBboxDetector with ego_centric mode to detect left and right hands in first-person images'}
```

## File: facebookresearch_frankmocap/handmocap/hand_mocap_api.py

Prompts

```
['detect hand bounding boxes in third-view images using a type-agnostic Detectron2 hand detector', 'detect hand bounding boxes in ego-centric images using a type-aware Faster R-CNN hand-object detector', 'detect body bounding boxes and poses from a BGR image using the underlying body pose estimator', 'initialize a HandBboxDetector with third_view mode to detect hands and body poses in third-person images', 'initialize a HandBboxDetector with ego_centric mode to detect left and right hands in first-person images', 'initialize a HandMocap instance with a regressor checkpoint path and SMPL model directory', 'run hand pose regression on an image with detected hand bounding boxes to get 3D vertices', 'crop and normalize a hand region from an image using a bounding box for left or right hand', 'pad a hand bounding box crop to a square and resize it to 224x224 pixels', 'convert predicted SMPL hand vertices from model space to original image pixel coordinates']
```

Usage

```
{'init_hand_mocap': 'initialize a HandMocap instance with a regressor checkpoint path and SMPL model directory', 'regress_hand_pose': 'run hand pose regression on an image with detected hand bounding boxes to get 3D vertices', 'process_hand_bbox': 'crop and normalize a hand region from an image using a bounding box for left or right hand', 'pad_and_resize_hand_crop': 'pad a hand bounding box crop to a square and resize it to 224x224 pixels', 'get_hand_vertices_in_image_space': 'convert predicted SMPL hand vertices from model space to original image pixel coordinates'}
```

