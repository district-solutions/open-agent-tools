# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/structures/multilevel_pixel_data.py

Prompts

```
['create a MultilevelPixelData instance with heatmaps and masks across multiple resolution levels', 'get a single level PixelData from MultilevelPixelData using integer index or string key', 'convert all tensors in MultilevelPixelData to CPU using the cpu method', 'convert all tensors in MultilevelPixelData to numpy arrays using the numpy method', 'set or update data fields in MultilevelPixelData using the set_data method with a dict', 'create a PoseDataSample with gt_instances, gt_fields, and metainfo for pose estimation', 'set ground truth instances with keypoints and bboxes on a PoseDataSample', 'set predicted instances with keypoint predictions on a PoseDataSample', 'set ground truth heatmaps and spatial fields on a PoseDataSample', 'set predicted heatmaps and spatial distributions on a PoseDataSample', 'merge a list of PoseDataSample objects into a single combined data sample with concatenated instances', 'revert a predicted heatmap from a cropped bounding box back to the original image coordinates', 'split an InstanceData object into a list of dicts each containing one instance keypoints and scores', 'merge ground truth heatmaps from multiple PoseDataSample objects by reverting and taking the max', 'merge predicted heatmaps from multiple PoseDataSample objects by reverting and taking the max']
```

Usage

```
{'create_multilevel_pixel_data': 'create a MultilevelPixelData instance with heatmaps and masks across multiple resolution levels', 'get_pixel_data_by_level': 'get a single level PixelData from MultilevelPixelData using integer index or string key', 'convert_tensors_to_cpu': 'convert all tensors in MultilevelPixelData to CPU using the cpu method', 'convert_tensors_to_numpy': 'convert all tensors in MultilevelPixelData to numpy arrays using the numpy method', 'set_multilevel_data_fields': 'set or update data fields in MultilevelPixelData using the set_data method with a dict'}
```

## File: facebookresearch_sapiens/pose/mmpose/structures/pose_data_sample.py

Prompts

```
['create a MultilevelPixelData instance with heatmaps and masks across multiple resolution levels', 'get a single level PixelData from MultilevelPixelData using integer index or string key', 'convert all tensors in MultilevelPixelData to CPU using the cpu method', 'convert all tensors in MultilevelPixelData to numpy arrays using the numpy method', 'set or update data fields in MultilevelPixelData using the set_data method with a dict', 'create a PoseDataSample with gt_instances, gt_fields, and metainfo for pose estimation', 'set ground truth instances with keypoints and bboxes on a PoseDataSample', 'set predicted instances with keypoint predictions on a PoseDataSample', 'set ground truth heatmaps and spatial fields on a PoseDataSample', 'set predicted heatmaps and spatial distributions on a PoseDataSample', 'merge a list of PoseDataSample objects into a single combined data sample with concatenated instances', 'revert a predicted heatmap from a cropped bounding box back to the original image coordinates', 'split an InstanceData object into a list of dicts each containing one instance keypoints and scores', 'merge ground truth heatmaps from multiple PoseDataSample objects by reverting and taking the max', 'merge predicted heatmaps from multiple PoseDataSample objects by reverting and taking the max']
```

Usage

```
{'create_pose_data_sample': 'create a PoseDataSample with gt_instances, gt_fields, and metainfo for pose estimation', 'set_gt_instances': 'set ground truth instances with keypoints and bboxes on a PoseDataSample', 'set_pred_instances': 'set predicted instances with keypoint predictions on a PoseDataSample', 'set_gt_fields': 'set ground truth heatmaps and spatial fields on a PoseDataSample', 'set_pred_fields': 'set predicted heatmaps and spatial distributions on a PoseDataSample'}
```

## File: facebookresearch_sapiens/pose/mmpose/structures/utils.py

Prompts

```
['create a MultilevelPixelData instance with heatmaps and masks across multiple resolution levels', 'get a single level PixelData from MultilevelPixelData using integer index or string key', 'convert all tensors in MultilevelPixelData to CPU using the cpu method', 'convert all tensors in MultilevelPixelData to numpy arrays using the numpy method', 'set or update data fields in MultilevelPixelData using the set_data method with a dict', 'create a PoseDataSample with gt_instances, gt_fields, and metainfo for pose estimation', 'set ground truth instances with keypoints and bboxes on a PoseDataSample', 'set predicted instances with keypoint predictions on a PoseDataSample', 'set ground truth heatmaps and spatial fields on a PoseDataSample', 'set predicted heatmaps and spatial distributions on a PoseDataSample', 'merge a list of PoseDataSample objects into a single combined data sample with concatenated instances', 'revert a predicted heatmap from a cropped bounding box back to the original image coordinates', 'split an InstanceData object into a list of dicts each containing one instance keypoints and scores', 'merge ground truth heatmaps from multiple PoseDataSample objects by reverting and taking the max', 'merge predicted heatmaps from multiple PoseDataSample objects by reverting and taking the max']
```

Usage

```
{'merge_pose_data_samples': 'merge a list of PoseDataSample objects into a single combined data sample with concatenated instances', 'revert_heatmap_to_original_image': 'revert a predicted heatmap from a cropped bounding box back to the original image coordinates', 'split_instances_to_dicts': 'split an InstanceData object into a list of dicts each containing one instance keypoints and scores', 'merge_ground_truth_heatmaps': 'merge ground truth heatmaps from multiple PoseDataSample objects by reverting and taking the max', 'merge_predicted_heatmaps': 'merge predicted heatmaps from multiple PoseDataSample objects by reverting and taking the max'}
```

