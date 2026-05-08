# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/features/kinetic.py

Prompts

```
['create a KineticFeatures instance from motion data with frame time, thresholds, and up vector', 'compute the average kinetic energy for a specific joint across all frames in the motion', 'compute the average horizontal kinetic energy for a specific joint across all frames', 'compute the average vertical kinetic energy for a specific joint across all frames', 'compute the average energy expenditure for a specific joint using acceleration across all frames', 'create a ManualFeatures instance from a motion object to extract kinematic features for clustering', 'fetch the global 3D position of a named joint at the current frame using transform_and_fetch_position', "compute whether a joint's velocity exceeds a threshold using the f_fast method", 'compute whether the angle between four joints falls within a specified range using f_angle', 'compute the distance of a joint from a plane defined by three other joints using f_plane', 'build a PercentileThresholds object from a folder of BVH motion capture files to compute velocity thresholds', 'create a sliding window velocity collection across all joints and frames from BVH motion data', 'compute the 95th percentile velocity thresholds for each joint in the motion dataset', 'get the velocity threshold value for a specific joint by its index', 'summarize all computed joint velocity thresholds as a formatted string for inspection', 'calculate the average velocity of a skeleton joint over a sliding window of animation frames', 'calculate the average acceleration of a skeleton joint over a sliding window of animation frames', 'check if the velocity of a point between two frames exceeds a given threshold', 'compute the Euclidean distance between two 3D points represented as coordinate arrays', 'check if the angle between two 3D vectors falls within a specified degree range']
```

Usage

```
{'create_KineticFeatures': 'create a KineticFeatures instance from motion data with frame time, thresholds, and up vector', 'compute_average_kinetic_energy': 'compute the average kinetic energy for a specific joint across all frames in the motion', 'compute_average_kinetic_energy_horizontal': 'compute the average horizontal kinetic energy for a specific joint across all frames', 'compute_average_kinetic_energy_vertical': 'compute the average vertical kinetic energy for a specific joint across all frames', 'compute_average_energy_expenditure': 'compute the average energy expenditure for a specific joint using acceleration across all frames'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/features/manual.py

Prompts

```
['create a KineticFeatures instance from motion data with frame time, thresholds, and up vector', 'compute the average kinetic energy for a specific joint across all frames in the motion', 'compute the average horizontal kinetic energy for a specific joint across all frames', 'compute the average vertical kinetic energy for a specific joint across all frames', 'compute the average energy expenditure for a specific joint using acceleration across all frames', 'create a ManualFeatures instance from a motion object to extract kinematic features for clustering', 'fetch the global 3D position of a named joint at the current frame using transform_and_fetch_position', "compute whether a joint's velocity exceeds a threshold using the f_fast method", 'compute whether the angle between four joints falls within a specified range using f_angle', 'compute the distance of a joint from a plane defined by three other joints using f_plane', 'build a PercentileThresholds object from a folder of BVH motion capture files to compute velocity thresholds', 'create a sliding window velocity collection across all joints and frames from BVH motion data', 'compute the 95th percentile velocity thresholds for each joint in the motion dataset', 'get the velocity threshold value for a specific joint by its index', 'summarize all computed joint velocity thresholds as a formatted string for inspection', 'calculate the average velocity of a skeleton joint over a sliding window of animation frames', 'calculate the average acceleration of a skeleton joint over a sliding window of animation frames', 'check if the velocity of a point between two frames exceeds a given threshold', 'compute the Euclidean distance between two 3D points represented as coordinate arrays', 'check if the angle between two 3D vectors falls within a specified degree range']
```

Usage

```
{'create_ManualFeatures_instance': 'create a ManualFeatures instance from a motion object to extract kinematic features for clustering', 'fetch_joint_position': 'fetch the global 3D position of a named joint at the current frame using transform_and_fetch_position', 'compute_velocity_feature': "compute whether a joint's velocity exceeds a threshold using the f_fast method", 'compute_angle_feature': 'compute whether the angle between four joints falls within a specified range using f_angle', 'compute_plane_feature': 'compute the distance of a joint from a plane defined by three other joints using f_plane'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/features/thresholds.py

Prompts

```
['create a KineticFeatures instance from motion data with frame time, thresholds, and up vector', 'compute the average kinetic energy for a specific joint across all frames in the motion', 'compute the average horizontal kinetic energy for a specific joint across all frames', 'compute the average vertical kinetic energy for a specific joint across all frames', 'compute the average energy expenditure for a specific joint using acceleration across all frames', 'create a ManualFeatures instance from a motion object to extract kinematic features for clustering', 'fetch the global 3D position of a named joint at the current frame using transform_and_fetch_position', "compute whether a joint's velocity exceeds a threshold using the f_fast method", 'compute whether the angle between four joints falls within a specified range using f_angle', 'compute the distance of a joint from a plane defined by three other joints using f_plane', 'build a PercentileThresholds object from a folder of BVH motion capture files to compute velocity thresholds', 'create a sliding window velocity collection across all joints and frames from BVH motion data', 'compute the 95th percentile velocity thresholds for each joint in the motion dataset', 'get the velocity threshold value for a specific joint by its index', 'summarize all computed joint velocity thresholds as a formatted string for inspection', 'calculate the average velocity of a skeleton joint over a sliding window of animation frames', 'calculate the average acceleration of a skeleton joint over a sliding window of animation frames', 'check if the velocity of a point between two frames exceeds a given threshold', 'compute the Euclidean distance between two 3D points represented as coordinate arrays', 'check if the angle between two 3D vectors falls within a specified degree range']
```

Usage

```
{'build_percentile_thresholds': 'build a PercentileThresholds object from a folder of BVH motion capture files to compute velocity thresholds', 'create_velocity_collection': 'create a sliding window velocity collection across all joints and frames from BVH motion data', 'compute_p95_thresholds': 'compute the 95th percentile velocity thresholds for each joint in the motion dataset', 'get_threshold_for_joint': 'get the velocity threshold value for a specific joint by its index', 'summarize_thresholds': 'summarize all computed joint velocity thresholds as a formatted string for inspection'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/features/utils.py

Prompts

```
['create a KineticFeatures instance from motion data with frame time, thresholds, and up vector', 'compute the average kinetic energy for a specific joint across all frames in the motion', 'compute the average horizontal kinetic energy for a specific joint across all frames', 'compute the average vertical kinetic energy for a specific joint across all frames', 'compute the average energy expenditure for a specific joint using acceleration across all frames', 'create a ManualFeatures instance from a motion object to extract kinematic features for clustering', 'fetch the global 3D position of a named joint at the current frame using transform_and_fetch_position', "compute whether a joint's velocity exceeds a threshold using the f_fast method", 'compute whether the angle between four joints falls within a specified range using f_angle', 'compute the distance of a joint from a plane defined by three other joints using f_plane', 'build a PercentileThresholds object from a folder of BVH motion capture files to compute velocity thresholds', 'create a sliding window velocity collection across all joints and frames from BVH motion data', 'compute the 95th percentile velocity thresholds for each joint in the motion dataset', 'get the velocity threshold value for a specific joint by its index', 'summarize all computed joint velocity thresholds as a formatted string for inspection', 'calculate the average velocity of a skeleton joint over a sliding window of animation frames', 'calculate the average acceleration of a skeleton joint over a sliding window of animation frames', 'check if the velocity of a point between two frames exceeds a given threshold', 'compute the Euclidean distance between two 3D points represented as coordinate arrays', 'check if the angle between two 3D vectors falls within a specified degree range']
```

Usage

```
{'calc_average_velocity': 'calculate the average velocity of a skeleton joint over a sliding window of animation frames', 'calc_average_acceleration': 'calculate the average acceleration of a skeleton joint over a sliding window of animation frames', 'velocity_above_threshold': 'check if the velocity of a point between two frames exceeds a given threshold', 'distance_between_points': 'compute the Euclidean distance between two 3D points represented as coordinate arrays', 'angle_within_range': 'check if the angle between two 3D vectors falls within a specified degree range'}
```

