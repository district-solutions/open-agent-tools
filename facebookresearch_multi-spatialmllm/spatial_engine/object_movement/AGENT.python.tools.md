# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_movement/single_object_movement_engine_coord.py

Prompts

```
['generate QA training data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with multiprocessing', 'generate QA evaluation data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with max samples', 'segment 3D point tracks into rigid body groups using hierarchical clustering on distance changes', 'smooth pairwise distance changes between consecutive time steps by filtering small changes below a threshold', 'filter rigid body groups to retain only those with more than a minimum number of points', 'format frame pairs and point displacements into conversation-style training samples with annotated images', 'project a 3D point into normalized 2D image coordinates using camera intrinsics']
```

Usage

```
{'generate_qa_training_data': 'generate QA training data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with multiprocessing', 'generate_qa_eval_data': 'generate QA evaluation data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with max samples', 'rigid_body_segmentation': 'segment 3D point tracks into rigid body groups using hierarchical clustering on distance changes', 'smooth_distance_changes': 'smooth pairwise distance changes between consecutive time steps by filtering small changes below a threshold', 'filter_large_groups': 'filter rigid body groups to retain only those with more than a minimum number of points'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_movement/single_object_movement_engine_dot.py

Prompts

```
['generate QA training data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with multiprocessing', 'generate QA evaluation data from TapVid3D NPZ scene files using TwoFrameVideoQAEngine with max samples', 'segment 3D point tracks into rigid body groups using hierarchical clustering on distance changes', 'smooth pairwise distance changes between consecutive time steps by filtering small changes below a threshold', 'filter rigid body groups to retain only those with more than a minimum number of points', 'format frame pairs and point displacements into conversation-style training samples with annotated images', 'project a 3D point into normalized 2D image coordinates using camera intrinsics']
```

Usage

```
{'generate_qa_training_data': 'generate QA training data from TapVid3D npz files for total distance or displacement vector question types', 'generate_qa_eval_data': 'generate QA evaluation data from TapVid3D npz files with subsampled max samples for validation', 'rigid_body_segmentation': 'segment 3D point tracks into rigid body groups using hierarchical clustering on smoothed distance changes', 'format_training_samples': 'format frame pairs and point displacements into conversation-style training samples with annotated images', 'project_point': 'project a 3D point into normalized 2D image coordinates using camera intrinsics'}
```

