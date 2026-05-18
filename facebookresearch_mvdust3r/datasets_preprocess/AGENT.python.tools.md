# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/datasets_preprocess/gather_metadata.py

Prompts

```
['run the script with --data-dir and --tgt-dir to gather metadata from *extra.pt files into train/test splits', 'run split_dps to split datapoints into train and test sets and dump them as JSON and HDF5 files', 'run extract_scene_name to parse a file path and return the scene name for scannet, gibson, or mp3d datasets', 'run tuple_n_general_new to collect metadata from *extra.pt files, extract scene info, and split into train/test HDF5', 'review split_dps to understand how datapoints are split into train/test and serialized to JSON samples and compressed HDF5', 'run the script to generate ScanNet trajectory tuples with specified views, hardness, and data type', 'run the script to generate ScanNet++ trajectory tuples using iPhone COLMAP poses and rendered depth', 'review the cover function that computes point cloud coverage ratio between two point clouds using KNN', 'review the get_score function that calculates bidirectional coverage score between two point clouds', 'review the ok function that validates score list against minimum and maximum hardness thresholds', 'run the script to generate ScanNet trajectory sequences with configurable views and hardness levels', 'run the script to generate ScanNet++ trajectory sequences using iPhone COLMAP poses and rendered depth', 'review the extract_image_txt function that parses COLMAP images.txt to extract camera poses and frame names']
```

Usage

```
{'run_gather_metadata': 'run the script with --data-dir and --tgt-dir to gather metadata from *extra.pt files into train/test splits', 'run_split_dps': 'run split_dps to split datapoints into train and test sets and dump them as JSON and HDF5 files', 'run_extract_scene_name': 'run extract_scene_name to parse a file path and return the scene name for scannet, gibson, or mp3d datasets', 'run_tuple_n_general_new': 'run tuple_n_general_new to collect metadata from *extra.pt files, extract scene info, and split into train/test HDF5', 'review_split_dps': 'review split_dps to understand how datapoints are split into train/test and serialized to JSON samples and compressed HDF5'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/scannet_traj_gen.py

Prompts

```
['run the script with --data-dir and --tgt-dir to gather metadata from *extra.pt files into train/test splits', 'run split_dps to split datapoints into train and test sets and dump them as JSON and HDF5 files', 'run extract_scene_name to parse a file path and return the scene name for scannet, gibson, or mp3d datasets', 'run tuple_n_general_new to collect metadata from *extra.pt files, extract scene info, and split into train/test HDF5', 'review split_dps to understand how datapoints are split into train/test and serialized to JSON samples and compressed HDF5', 'run the script to generate ScanNet trajectory tuples with specified views, hardness, and data type', 'run the script to generate ScanNet++ trajectory tuples using iPhone COLMAP poses and rendered depth', 'review the cover function that computes point cloud coverage ratio between two point clouds using KNN', 'review the get_score function that calculates bidirectional coverage score between two point clouds', 'review the ok function that validates score list against minimum and maximum hardness thresholds', 'run the script to generate ScanNet trajectory sequences with configurable views and hardness levels', 'run the script to generate ScanNet++ trajectory sequences using iPhone COLMAP poses and rendered depth', 'review the extract_image_txt function that parses COLMAP images.txt to extract camera poses and frame names']
```

Usage

```
{'run_scannet_traj_gen': 'run the script to generate ScanNet trajectory tuples with specified views, hardness, and data type', 'run_scannetpp_traj_gen': 'run the script to generate ScanNet++ trajectory tuples using iPhone COLMAP poses and rendered depth', 'review_cover_function': 'review the cover function that computes point cloud coverage ratio between two point clouds using KNN', 'review_get_score_function': 'review the get_score function that calculates bidirectional coverage score between two point clouds', 'review_ok_function': 'review the ok function that validates score list against minimum and maximum hardness thresholds'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/scannet_traj_seq_gen.py

Prompts

```
['run the script with --data-dir and --tgt-dir to gather metadata from *extra.pt files into train/test splits', 'run split_dps to split datapoints into train and test sets and dump them as JSON and HDF5 files', 'run extract_scene_name to parse a file path and return the scene name for scannet, gibson, or mp3d datasets', 'run tuple_n_general_new to collect metadata from *extra.pt files, extract scene info, and split into train/test HDF5', 'review split_dps to understand how datapoints are split into train/test and serialized to JSON samples and compressed HDF5', 'run the script to generate ScanNet trajectory tuples with specified views, hardness, and data type', 'run the script to generate ScanNet++ trajectory tuples using iPhone COLMAP poses and rendered depth', 'review the cover function that computes point cloud coverage ratio between two point clouds using KNN', 'review the get_score function that calculates bidirectional coverage score between two point clouds', 'review the ok function that validates score list against minimum and maximum hardness thresholds', 'run the script to generate ScanNet trajectory sequences with configurable views and hardness levels', 'run the script to generate ScanNet++ trajectory sequences using iPhone COLMAP poses and rendered depth', 'review the extract_image_txt function that parses COLMAP images.txt to extract camera poses and frame names']
```

Usage

```
{'run_scannet_traj_seq_gen': 'run the script to generate ScanNet trajectory sequences with configurable views and hardness levels', 'run_scannetpp_traj_seq_gen': 'run the script to generate ScanNet++ trajectory sequences using iPhone COLMAP poses and rendered depth', 'review_cover_function': 'review the cover function that computes point cloud coverage ratio using k-nearest neighbors on GPU', 'review_get_score_function': 'review the get_score function that calculates bidirectional coverage between two point clouds', 'review_extract_image_txt': 'review the extract_image_txt function that parses COLMAP images.txt to extract camera poses and frame names'}
```

