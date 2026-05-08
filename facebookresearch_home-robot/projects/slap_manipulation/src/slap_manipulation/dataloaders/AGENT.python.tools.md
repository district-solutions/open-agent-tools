# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/dataloaders/annotations.py

Prompts

```
['load annotations from a YAML file and return a dictionary mapping skill names to their labels and alt names', 'run the module to load and print annotations from a YAML file like assets/language_variations/v0.yml', 'review the load_annotations_dict function that parses YAML entries into a labels dictionary with name and alt_name keys', 'refactor load_annotations_dict to handle missing alt_name keys or empty YAML entries gracefully', 'test load_annotations_dict by passing a YAML file path and verifying the returned labels dictionary structure', 'create a PerActRobotDataset instance to load robot manipulation data with CLIP encoding and voxel grid support', 'run the debug_get_datum CLI command to inspect datum samples from a robot dataset directory', 'run the show_all_keypoints CLI command to visualize keypoints overlaid on initial frames with voxel grid', 'test the is_action_valid method to check if end-effector positions fall within PerAct scene bounds', 'review the get_per_waypoint_batch method to extract input and output tensors for a single waypoint from a batch', 'create an RLBenchDataset instance to load RLBench HDF5 data with configurable data augmentation and point cloud settings', 'get a single training datum dict with point clouds, gripper poses, and commands from an RLBench trial', 'get the 6D gripper pose as a 4x4 homogeneous transformation matrix at a given trial timestep', 'get position, rotation matrix, and RPY/quaternion angles for one or more end-effector keyframes', 'voxelize a point cloud and find the closest point to a given end-effector keyframe using KDTree search', 'create a RobotDataset instance to load robot manipulation data from H5 files with domain randomization and point cloud processing', 'get a single training datum from a trial with keypoint index including point cloud, gripper pose, and proprioceptive data', 'process RGB and depth images from a camera view into a structured point cloud with semantic features', "extract indices of all user-tagged keyframes from a trial's user_keyframe array"]
```

Usage

```
{'load_annotations_dict': 'load annotations from a YAML file and return a dictionary mapping skill names to their labels and alt names', 'run_load_annotations': 'run the module to load and print annotations from a YAML file like assets/language_variations/v0.yml', 'review_load_annotations_dict': 'review the load_annotations_dict function that parses YAML entries into a labels dictionary with name and alt_name keys', 'refactor_load_annotations_dict': 'refactor load_annotations_dict to handle missing alt_name keys or empty YAML entries gracefully', 'test_load_annotations_dict': 'test load_annotations_dict by passing a YAML file path and verifying the returned labels dictionary structure'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/dataloaders/peract_loader.py

Prompts

```
['load annotations from a YAML file and return a dictionary mapping skill names to their labels and alt names', 'run the module to load and print annotations from a YAML file like assets/language_variations/v0.yml', 'review the load_annotations_dict function that parses YAML entries into a labels dictionary with name and alt_name keys', 'refactor load_annotations_dict to handle missing alt_name keys or empty YAML entries gracefully', 'test load_annotations_dict by passing a YAML file path and verifying the returned labels dictionary structure', 'create a PerActRobotDataset instance to load robot manipulation data with CLIP encoding and voxel grid support', 'run the debug_get_datum CLI command to inspect datum samples from a robot dataset directory', 'run the show_all_keypoints CLI command to visualize keypoints overlaid on initial frames with voxel grid', 'test the is_action_valid method to check if end-effector positions fall within PerAct scene bounds', 'review the get_per_waypoint_batch method to extract input and output tensors for a single waypoint from a batch', 'create an RLBenchDataset instance to load RLBench HDF5 data with configurable data augmentation and point cloud settings', 'get a single training datum dict with point clouds, gripper poses, and commands from an RLBench trial', 'get the 6D gripper pose as a 4x4 homogeneous transformation matrix at a given trial timestep', 'get position, rotation matrix, and RPY/quaternion angles for one or more end-effector keyframes', 'voxelize a point cloud and find the closest point to a given end-effector keyframe using KDTree search', 'create a RobotDataset instance to load robot manipulation data from H5 files with domain randomization and point cloud processing', 'get a single training datum from a trial with keypoint index including point cloud, gripper pose, and proprioceptive data', 'process RGB and depth images from a camera view into a structured point cloud with semantic features', "extract indices of all user-tagged keyframes from a trial's user_keyframe array"]
```

Usage

```
{'create_PerActRobotDataset': 'create a PerActRobotDataset instance to load robot manipulation data with CLIP encoding and voxel grid support', 'run_debug_get_datum': 'run the debug_get_datum CLI command to inspect datum samples from a robot dataset directory', 'run_show_all_keypoints': 'run the show_all_keypoints CLI command to visualize keypoints overlaid on initial frames with voxel grid', 'test_is_action_valid': 'test the is_action_valid method to check if end-effector positions fall within PerAct scene bounds', 'review_get_per_waypoint_batch': 'review the get_per_waypoint_batch method to extract input and output tensors for a single waypoint from a batch'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/dataloaders/rlbench_loader.py

Prompts

```
['load annotations from a YAML file and return a dictionary mapping skill names to their labels and alt names', 'run the module to load and print annotations from a YAML file like assets/language_variations/v0.yml', 'review the load_annotations_dict function that parses YAML entries into a labels dictionary with name and alt_name keys', 'refactor load_annotations_dict to handle missing alt_name keys or empty YAML entries gracefully', 'test load_annotations_dict by passing a YAML file path and verifying the returned labels dictionary structure', 'create a PerActRobotDataset instance to load robot manipulation data with CLIP encoding and voxel grid support', 'run the debug_get_datum CLI command to inspect datum samples from a robot dataset directory', 'run the show_all_keypoints CLI command to visualize keypoints overlaid on initial frames with voxel grid', 'test the is_action_valid method to check if end-effector positions fall within PerAct scene bounds', 'review the get_per_waypoint_batch method to extract input and output tensors for a single waypoint from a batch', 'create an RLBenchDataset instance to load RLBench HDF5 data with configurable data augmentation and point cloud settings', 'get a single training datum dict with point clouds, gripper poses, and commands from an RLBench trial', 'get the 6D gripper pose as a 4x4 homogeneous transformation matrix at a given trial timestep', 'get position, rotation matrix, and RPY/quaternion angles for one or more end-effector keyframes', 'voxelize a point cloud and find the closest point to a given end-effector keyframe using KDTree search', 'create a RobotDataset instance to load robot manipulation data from H5 files with domain randomization and point cloud processing', 'get a single training datum from a trial with keypoint index including point cloud, gripper pose, and proprioceptive data', 'process RGB and depth images from a camera view into a structured point cloud with semantic features', "extract indices of all user-tagged keyframes from a trial's user_keyframe array"]
```

Usage

```
{'create_RLBenchDataset': 'create an RLBenchDataset instance to load RLBench HDF5 data with configurable data augmentation and point cloud settings', 'get_datum': 'get a single training datum dict with point clouds, gripper poses, and commands from an RLBench trial', 'get_gripper_pose': 'get the 6D gripper pose as a 4x4 homogeneous transformation matrix at a given trial timestep', 'get_commands': 'get position, rotation matrix, and RPY/quaternion angles for one or more end-effector keyframes', 'voxelize_and_get_interaction_point': 'voxelize a point cloud and find the closest point to a given end-effector keyframe using KDTree search'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/dataloaders/robot_loader.py

Prompts

```
['load annotations from a YAML file and return a dictionary mapping skill names to their labels and alt names', 'run the module to load and print annotations from a YAML file like assets/language_variations/v0.yml', 'review the load_annotations_dict function that parses YAML entries into a labels dictionary with name and alt_name keys', 'refactor load_annotations_dict to handle missing alt_name keys or empty YAML entries gracefully', 'test load_annotations_dict by passing a YAML file path and verifying the returned labels dictionary structure', 'create a PerActRobotDataset instance to load robot manipulation data with CLIP encoding and voxel grid support', 'run the debug_get_datum CLI command to inspect datum samples from a robot dataset directory', 'run the show_all_keypoints CLI command to visualize keypoints overlaid on initial frames with voxel grid', 'test the is_action_valid method to check if end-effector positions fall within PerAct scene bounds', 'review the get_per_waypoint_batch method to extract input and output tensors for a single waypoint from a batch', 'create an RLBenchDataset instance to load RLBench HDF5 data with configurable data augmentation and point cloud settings', 'get a single training datum dict with point clouds, gripper poses, and commands from an RLBench trial', 'get the 6D gripper pose as a 4x4 homogeneous transformation matrix at a given trial timestep', 'get position, rotation matrix, and RPY/quaternion angles for one or more end-effector keyframes', 'voxelize a point cloud and find the closest point to a given end-effector keyframe using KDTree search', 'create a RobotDataset instance to load robot manipulation data from H5 files with domain randomization and point cloud processing', 'get a single training datum from a trial with keypoint index including point cloud, gripper pose, and proprioceptive data', 'process RGB and depth images from a camera view into a structured point cloud with semantic features', "extract indices of all user-tagged keyframes from a trial's user_keyframe array"]
```

Usage

```
{'create_robot_dataset': 'create a RobotDataset instance to load robot manipulation data from H5 files with domain randomization and point cloud processing', 'get_datum_from_trial': 'get a single training datum from a trial with keypoint index including point cloud, gripper pose, and proprioceptive data', 'process_images_from_view': 'process RGB and depth images from a camera view into a structured point cloud with semantic features', 'get_gripper_pose': 'transform end-effector pose to gripper-end position with grasp offset and return 6D pose matrix', 'extract_manual_keyframes': "extract indices of all user-tagged keyframes from a trial's user_keyframe array"}
```

