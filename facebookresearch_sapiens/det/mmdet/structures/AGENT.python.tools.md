# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/structures/det_data_sample.py

Prompts

```
['create a DetDataSample and set ground truth instances with bounding boxes and labels', 'create a DetDataSample with predicted instances containing bounding boxes and confidence scores', 'create a DetDataSample and attach ground truth panoptic segmentation data', 'create a DetDataSample and attach ground truth semantic segmentation data', 'create a DetDataSample with predicted tracking instances for object tracking tasks', 'convert numpy array, tensor, or int label values to mmengine LabelData with optional num_classes validation', 'instantiate a ReIDDataSample to manage ground truth labels, predicted features, and scores for person ReID tasks', 'set the ground truth label on a ReIDDataSample from a tensor, numpy array, list, or integer value', 'set the ground truth score tensor on a ReIDDataSample with automatic num_classes validation', 'set the predicted feature tensor on a ReIDDataSample for storing model output embeddings', 'create a TrackDataSample instance to wrap multiple DetDataSample frames for video tracking', 'set video_data_samples property with a list of DetDataSample objects for each frame', 'get key frame DetDataSample objects from a TrackDataSample using key_frames_inds metainfo', 'get reference frame DetDataSample objects from a TrackDataSample using ref_frames_inds metainfo', 'move a TrackDataSample and all its tensors to cuda, cpu, or npu device']
```

Usage

```
{'create_det_data_sample_with_gt_instances': 'create a DetDataSample and set ground truth instances with bounding boxes and labels', 'create_det_data_sample_with_pred_instances': 'create a DetDataSample with predicted instances containing bounding boxes and confidence scores', 'create_det_data_sample_with_panoptic_seg': 'create a DetDataSample and attach ground truth panoptic segmentation data', 'create_det_data_sample_with_semantic_seg': 'create a DetDataSample and attach ground truth semantic segmentation data', 'create_det_data_sample_with_track_instances': 'create a DetDataSample with predicted tracking instances for object tracking tasks'}
```

## File: facebookresearch_sapiens/det/mmdet/structures/reid_data_sample.py

Prompts

```
['create a DetDataSample and set ground truth instances with bounding boxes and labels', 'create a DetDataSample with predicted instances containing bounding boxes and confidence scores', 'create a DetDataSample and attach ground truth panoptic segmentation data', 'create a DetDataSample and attach ground truth semantic segmentation data', 'create a DetDataSample with predicted tracking instances for object tracking tasks', 'convert numpy array, tensor, or int label values to mmengine LabelData with optional num_classes validation', 'instantiate a ReIDDataSample to manage ground truth labels, predicted features, and scores for person ReID tasks', 'set the ground truth label on a ReIDDataSample from a tensor, numpy array, list, or integer value', 'set the ground truth score tensor on a ReIDDataSample with automatic num_classes validation', 'set the predicted feature tensor on a ReIDDataSample for storing model output embeddings', 'create a TrackDataSample instance to wrap multiple DetDataSample frames for video tracking', 'set video_data_samples property with a list of DetDataSample objects for each frame', 'get key frame DetDataSample objects from a TrackDataSample using key_frames_inds metainfo', 'get reference frame DetDataSample objects from a TrackDataSample using ref_frames_inds metainfo', 'move a TrackDataSample and all its tensors to cuda, cpu, or npu device']
```

Usage

```
{'format_label_to_LabelData': 'convert numpy array, tensor, or int label values to mmengine LabelData with optional num_classes validation', 'create_ReIDDataSample_for_ReID_task': 'instantiate a ReIDDataSample to manage ground truth labels, predicted features, and scores for person ReID tasks', 'set_gt_label_on_ReIDDataSample': 'set the ground truth label on a ReIDDataSample from a tensor, numpy array, list, or integer value', 'set_gt_score_on_ReIDDataSample': 'set the ground truth score tensor on a ReIDDataSample with automatic num_classes validation', 'set_pred_feature_on_ReIDDataSample': 'set the predicted feature tensor on a ReIDDataSample for storing model output embeddings'}
```

## File: facebookresearch_sapiens/det/mmdet/structures/track_data_sample.py

Prompts

```
['create a DetDataSample and set ground truth instances with bounding boxes and labels', 'create a DetDataSample with predicted instances containing bounding boxes and confidence scores', 'create a DetDataSample and attach ground truth panoptic segmentation data', 'create a DetDataSample and attach ground truth semantic segmentation data', 'create a DetDataSample with predicted tracking instances for object tracking tasks', 'convert numpy array, tensor, or int label values to mmengine LabelData with optional num_classes validation', 'instantiate a ReIDDataSample to manage ground truth labels, predicted features, and scores for person ReID tasks', 'set the ground truth label on a ReIDDataSample from a tensor, numpy array, list, or integer value', 'set the ground truth score tensor on a ReIDDataSample with automatic num_classes validation', 'set the predicted feature tensor on a ReIDDataSample for storing model output embeddings', 'create a TrackDataSample instance to wrap multiple DetDataSample frames for video tracking', 'set video_data_samples property with a list of DetDataSample objects for each frame', 'get key frame DetDataSample objects from a TrackDataSample using key_frames_inds metainfo', 'get reference frame DetDataSample objects from a TrackDataSample using ref_frames_inds metainfo', 'move a TrackDataSample and all its tensors to cuda, cpu, or npu device']
```

Usage

```
{'create_TrackDataSample': 'create a TrackDataSample instance to wrap multiple DetDataSample frames for video tracking', 'set_video_data_samples': 'set video_data_samples property with a list of DetDataSample objects for each frame', 'get_key_frames': 'get key frame DetDataSample objects from a TrackDataSample using key_frames_inds metainfo', 'get_ref_frames': 'get reference frame DetDataSample objects from a TrackDataSample using ref_frames_inds metainfo', 'move_TrackDataSample_to_device': 'move a TrackDataSample and all its tensors to cuda, cpu, or npu device'}
```

