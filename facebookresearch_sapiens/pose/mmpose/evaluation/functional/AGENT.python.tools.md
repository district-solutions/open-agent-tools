# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/evaluation/functional/keypoint_eval.py

Prompts

```
['calculate the PCK accuracy for predicted vs ground truth keypoints with a distance threshold', 'calculate the area under curve of keypoint PCK accuracy across multiple thresholds', 'calculate the normalized mean error between predicted and ground truth keypoints', 'calculate the mean per-joint position error with optional procrustes or scale alignment', 'calculate the PCK accuracy from model output heatmaps and ground truth heatmaps', 'compute a similarity transform (scale, rotation, translation) that aligns source 3D points to target 3D points', 'run a similarity transform on two sets of 3D mesh vertices to align them', 'test the compute_similarity_transform function with two numpy arrays of 3D points', 'review the compute_similarity_transform function which solves the orthogonal Procrustes problem', 'summarize the compute_similarity_transform function that computes scale, rotation, and translation for 3D point alignment', 'run non-maximum suppression on bounding box detections with a given overlap threshold', 'calculate OKS IOU between a ground truth instance and multiple detected keypoint instances', 'apply OKS-based non-maximum suppression on a list of keypoint detection results', 'apply soft OKS NMS with Gaussian rescoring on keypoint detections keeping up to max_dets', 'apply nearby joints NMS to suppress instances with too many close joints to others']
```

Usage

```
{'calculate_keypoint_pck_accuracy': 'calculate the PCK accuracy for predicted vs ground truth keypoints with a distance threshold', 'calculate_keypoint_auc': 'calculate the area under curve of keypoint PCK accuracy across multiple thresholds', 'calculate_keypoint_nme': 'calculate the normalized mean error between predicted and ground truth keypoints', 'calculate_keypoint_mpjpe': 'calculate the mean per-joint position error with optional procrustes or scale alignment', 'calculate_pose_pck_from_heatmaps': 'calculate the PCK accuracy from model output heatmaps and ground truth heatmaps'}
```

## File: facebookresearch_sapiens/pose/mmpose/evaluation/functional/mesh_eval.py

Prompts

```
['calculate the PCK accuracy for predicted vs ground truth keypoints with a distance threshold', 'calculate the area under curve of keypoint PCK accuracy across multiple thresholds', 'calculate the normalized mean error between predicted and ground truth keypoints', 'calculate the mean per-joint position error with optional procrustes or scale alignment', 'calculate the PCK accuracy from model output heatmaps and ground truth heatmaps', 'compute a similarity transform (scale, rotation, translation) that aligns source 3D points to target 3D points', 'run a similarity transform on two sets of 3D mesh vertices to align them', 'test the compute_similarity_transform function with two numpy arrays of 3D points', 'review the compute_similarity_transform function which solves the orthogonal Procrustes problem', 'summarize the compute_similarity_transform function that computes scale, rotation, and translation for 3D point alignment', 'run non-maximum suppression on bounding box detections with a given overlap threshold', 'calculate OKS IOU between a ground truth instance and multiple detected keypoint instances', 'apply OKS-based non-maximum suppression on a list of keypoint detection results', 'apply soft OKS NMS with Gaussian rescoring on keypoint detections keeping up to max_dets', 'apply nearby joints NMS to suppress instances with too many close joints to others']
```

Usage

```
{'compute_similarity_transform': 'compute a similarity transform (scale, rotation, translation) that aligns source 3D points to target 3D points', 'run_similarity_transform_on_mesh_vertices': 'run a similarity transform on two sets of 3D mesh vertices to align them', 'test_compute_similarity_transform': 'test the compute_similarity_transform function with two numpy arrays of 3D points', 'review_compute_similarity_transform': 'review the compute_similarity_transform function which solves the orthogonal Procrustes problem', 'summarize_compute_similarity_transform': 'summarize the compute_similarity_transform function that computes scale, rotation, and translation for 3D point alignment'}
```

## File: facebookresearch_sapiens/pose/mmpose/evaluation/functional/nms.py

Prompts

```
['calculate the PCK accuracy for predicted vs ground truth keypoints with a distance threshold', 'calculate the area under curve of keypoint PCK accuracy across multiple thresholds', 'calculate the normalized mean error between predicted and ground truth keypoints', 'calculate the mean per-joint position error with optional procrustes or scale alignment', 'calculate the PCK accuracy from model output heatmaps and ground truth heatmaps', 'compute a similarity transform (scale, rotation, translation) that aligns source 3D points to target 3D points', 'run a similarity transform on two sets of 3D mesh vertices to align them', 'test the compute_similarity_transform function with two numpy arrays of 3D points', 'review the compute_similarity_transform function which solves the orthogonal Procrustes problem', 'summarize the compute_similarity_transform function that computes scale, rotation, and translation for 3D point alignment', 'run non-maximum suppression on bounding box detections with a given overlap threshold', 'calculate OKS IOU between a ground truth instance and multiple detected keypoint instances', 'apply OKS-based non-maximum suppression on a list of keypoint detection results', 'apply soft OKS NMS with Gaussian rescoring on keypoint detections keeping up to max_dets', 'apply nearby joints NMS to suppress instances with too many close joints to others']
```

Usage

```
{'run_nms': 'run non-maximum suppression on bounding box detections with a given overlap threshold', 'run_oks_iou': 'calculate OKS IOU between a ground truth instance and multiple detected keypoint instances', 'run_oks_nms': 'apply OKS-based non-maximum suppression on a list of keypoint detection results', 'run_soft_oks_nms': 'apply soft OKS NMS with Gaussian rescoring on keypoint detections keeping up to max_dets', 'run_nearby_joints_nms': 'apply nearby joints NMS to suppress instances with too many close joints to others'}
```

