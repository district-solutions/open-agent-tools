# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/scannet/referit3d_data.py

Prompts

```
['load the ReferIt3D dataset from a CSV file with optional SR3D augmentation and token length filtering', 'decode a stimulus string into scene_id, instance_label, object count, target_id, and distractor IDs', 'create a ReferIt3dDataConfig dataclass with CSV paths, target class filtering, and max sequence length', 'filter ReferIt3D utterances to keep only those that explicitly mention the target object class', 'augment the NR3D dataset by concatenating SR3D data from a separate CSV file', 'create a ScanNetDataset instance to load RGB, depth, pose, and 3D bounding box data from a ScanNet scene directory', 'load a specific ScanNet scene by index or scan name using the dataset getitem method', 'load 3D bounding box coordinates, class labels, and object IDs from a ScanNet aligned or unaligned bbox numpy file', 'load and resize a depth image from a PNG or NPY file and return it as a scaled PyTorch tensor', 'create a PyTorch lookup table tensor that maps key indices to values with a configurable missing key fill value', 'load a ScanRefer JSON file into a pandas DataFrame with renamed columns matching referit3d format', 'create a stimulus_id column by combining scan_id, target_id, and ann_id from ScanRefer data', 'review the ScanReferDataConfig class and its json_dir default path setting', 'refactor load_scanrefer_data to also load annotated viewpoints with position and rotation data', 'summarize the get_num_distractor placeholder function and its intended distractor counting logic']
```

Usage

```
{'load_referit3d_dataset': 'load the ReferIt3D dataset from a CSV file with optional SR3D augmentation and token length filtering', 'decode_stimulus_string': 'decode a stimulus string into scene_id, instance_label, object count, target_id, and distractor IDs', 'create_referit3d_config': 'create a ReferIt3dDataConfig dataclass with CSV paths, target class filtering, and max sequence length', 'filter_utterances_by_target_class': 'filter ReferIt3D utterances to keep only those that explicitly mention the target object class', 'augment_with_sr3d_data': 'augment the NR3D dataset by concatenating SR3D data from a separate CSV file'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/scannet/scannet_dataset.py

Prompts

```
['load the ReferIt3D dataset from a CSV file with optional SR3D augmentation and token length filtering', 'decode a stimulus string into scene_id, instance_label, object count, target_id, and distractor IDs', 'create a ReferIt3dDataConfig dataclass with CSV paths, target class filtering, and max sequence length', 'filter ReferIt3D utterances to keep only those that explicitly mention the target object class', 'augment the NR3D dataset by concatenating SR3D data from a separate CSV file', 'create a ScanNetDataset instance to load RGB, depth, pose, and 3D bounding box data from a ScanNet scene directory', 'load a specific ScanNet scene by index or scan name using the dataset getitem method', 'load 3D bounding box coordinates, class labels, and object IDs from a ScanNet aligned or unaligned bbox numpy file', 'load and resize a depth image from a PNG or NPY file and return it as a scaled PyTorch tensor', 'create a PyTorch lookup table tensor that maps key indices to values with a configurable missing key fill value', 'load a ScanRefer JSON file into a pandas DataFrame with renamed columns matching referit3d format', 'create a stimulus_id column by combining scan_id, target_id, and ann_id from ScanRefer data', 'review the ScanReferDataConfig class and its json_dir default path setting', 'refactor load_scanrefer_data to also load annotated viewpoints with position and rotation data', 'summarize the get_num_distractor placeholder function and its intended distractor counting logic']
```

Usage

```
{'create_scannet_dataset': 'create a ScanNetDataset instance to load RGB, depth, pose, and 3D bounding box data from a ScanNet scene directory', 'load_scene_by_index': 'load a specific ScanNet scene by index or scan name using the dataset getitem method', 'load_3d_bboxes': 'load 3D bounding box coordinates, class labels, and object IDs from a ScanNet aligned or unaligned bbox numpy file', 'get_depth_image_from_path': 'load and resize a depth image from a PNG or NPY file and return it as a scaled PyTorch tensor', 'make_lookup_table': 'create a PyTorch lookup table tensor that maps key indices to values with a configurable missing key fill value'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/datasets/scannet/scanrefer_data.py

Prompts

```
['load the ReferIt3D dataset from a CSV file with optional SR3D augmentation and token length filtering', 'decode a stimulus string into scene_id, instance_label, object count, target_id, and distractor IDs', 'create a ReferIt3dDataConfig dataclass with CSV paths, target class filtering, and max sequence length', 'filter ReferIt3D utterances to keep only those that explicitly mention the target object class', 'augment the NR3D dataset by concatenating SR3D data from a separate CSV file', 'create a ScanNetDataset instance to load RGB, depth, pose, and 3D bounding box data from a ScanNet scene directory', 'load a specific ScanNet scene by index or scan name using the dataset getitem method', 'load 3D bounding box coordinates, class labels, and object IDs from a ScanNet aligned or unaligned bbox numpy file', 'load and resize a depth image from a PNG or NPY file and return it as a scaled PyTorch tensor', 'create a PyTorch lookup table tensor that maps key indices to values with a configurable missing key fill value', 'load a ScanRefer JSON file into a pandas DataFrame with renamed columns matching referit3d format', 'create a stimulus_id column by combining scan_id, target_id, and ann_id from ScanRefer data', 'review the ScanReferDataConfig class and its json_dir default path setting', 'refactor load_scanrefer_data to also load annotated viewpoints with position and rotation data', 'summarize the get_num_distractor placeholder function and its intended distractor counting logic']
```

Usage

```
{'load_scanrefer_data': 'load a ScanRefer JSON file into a pandas DataFrame with renamed columns matching referit3d format', 'create_stimulus_id': 'create a stimulus_id column by combining scan_id, target_id, and ann_id from ScanRefer data', 'review_ScanReferDataConfig': 'review the ScanReferDataConfig class and its json_dir default path setting', 'refactor_load_scanrefer_data': 'refactor load_scanrefer_data to also load annotated viewpoints with position and rotation data', 'summarize_get_num_distractor': 'summarize the get_num_distractor placeholder function and its intended distractor counting logic'}
```

