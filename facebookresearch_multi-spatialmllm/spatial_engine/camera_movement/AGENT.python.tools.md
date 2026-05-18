# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/camera_movement/calculate_frames_relations.py

Prompts

```
['run the main function to calculate camera overlap for all ScanNet train and val scenes', 'calculate the field of view overlap percentage between two cameras using precomputed in-bounds point masks', 'extract yaw and pitch angles in degrees from a 3x3 or 4x4 rotation matrix', 'save camera pair overlap, distance, yaw, and pitch data from a nested dictionary to a Parquet file', 'process a single ScanNet scene to compute pairwise camera overlap, distance, yaw, and pitch for all image pairs', 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build a training sample from a DataFrame row with camera extrinsics and movement question templates', 'convert a training sample with conversations to an evaluation sample with text field', 'build a training dataset from a parquet file sampling rows and writing JSONL output', 'build a validation dataset from a parquet file sampling rows and converting to eval format']
```

Usage

```
{'run_camera_overlap_pipeline': 'run the main function to calculate camera overlap for all ScanNet train and val scenes', 'calculate_camera_overlap': 'calculate the field of view overlap percentage between two cameras using precomputed in-bounds point masks', 'extract_yaw_pitch': 'extract yaw and pitch angles in degrees from a 3x3 or 4x4 rotation matrix', 'save_overlap_info': 'save camera pair overlap, distance, yaw, and pitch data from a nested dictionary to a Parquet file', 'process_scene': 'process a single ScanNet scene to compute pairwise camera overlap, distance, yaw, and pitch for all image pairs'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/camera_movement/camera_movement_engine_train_val.py

Prompts

```
['run the main function to calculate camera overlap for all ScanNet train and val scenes', 'calculate the field of view overlap percentage between two cameras using precomputed in-bounds point masks', 'extract yaw and pitch angles in degrees from a 3x3 or 4x4 rotation matrix', 'save camera pair overlap, distance, yaw, and pitch data from a nested dictionary to a Parquet file', 'process a single ScanNet scene to compute pairwise camera overlap, distance, yaw, and pitch for all image pairs', 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build a training sample from a DataFrame row with camera extrinsics and movement question templates', 'convert a training sample with conversations to an evaluation sample with text field', 'build a training dataset from a parquet file sampling rows and writing JSONL output', 'build a validation dataset from a parquet file sampling rows and converting to eval format']
```

Usage

```
{'sample_dataframe': 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build_training_sample': 'build a training sample from a DataFrame row with camera extrinsics and movement question templates', 'convert_train_sample_to_eval_sample': 'convert a training sample with conversations to an evaluation sample with text field', 'build_train_dataset': 'build a training dataset from a parquet file sampling rows and writing JSONL output', 'build_val_dataset': 'build a validation dataset from a parquet file sampling rows and converting to eval format'}
```

