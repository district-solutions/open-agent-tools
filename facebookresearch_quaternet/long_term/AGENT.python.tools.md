# Agent Python Tools

- repo: facebookresearch/quaternet
- repo_uri: https://github.com/facebookresearch/quaternet

## File: facebookresearch_quaternet/long_term/locomotion_utils.py

Prompts

```
['build a phase track signal from world positions by detecting footstep contacts and walking cycle state', 'extract translation and control features including longitudinal speed, height, and walking phase from motion data', 'build extra features for all subjects and actions in a motion capture dataset', 'extract amplitude, absolute phase, and angular velocity from a phase signal tensor', 'compute equal-segment-length splines with interpolated tracks for each animation in a motion capture dataset', 'train a PaceNetwork model on motion capture spline dataset sequences with configurable batch size and epochs', 'predict amplitude frequency and direction tracks on a spline using a trained PaceNetwork model', 'extract curvature and speed input features or amplitude frequency direction output features from a spline', 'save or load PaceNetwork model weights to and from a file using torch state dict', 'compute versor-based angle difference or angle sum between two 2D direction vectors using static methods', 'generate a locomotion sequence by following a spline path with an action prefix using PoseNetworkLongTerm', 'apply random rotation data augmentation to a batch of pose rotation and position buffers', 'compute positional loss with forward kinematics comparing predicted quaternions to expected 3D positions', 'prepare and yield augmented training batches of rotations and positions from a motion capture dataset', 'review the PoseNetworkLongTerm class that extends PoseNetwork for long-term human motion prediction']
```

Usage

```
{'build_phase_track': 'build a phase track signal from world positions by detecting footstep contacts and walking cycle state', 'extract_translations_controls': 'extract translation and control features including longitudinal speed, height, and walking phase from motion data', 'build_extra_features': 'build extra features for all subjects and actions in a motion capture dataset', 'phase_to_features': 'extract amplitude, absolute phase, and angular velocity from a phase signal tensor', 'compute_splines': 'compute equal-segment-length splines with interpolated tracks for each animation in a motion capture dataset'}
```

## File: facebookresearch_quaternet/long_term/pace_network.py

Prompts

```
['build a phase track signal from world positions by detecting footstep contacts and walking cycle state', 'extract translation and control features including longitudinal speed, height, and walking phase from motion data', 'build extra features for all subjects and actions in a motion capture dataset', 'extract amplitude, absolute phase, and angular velocity from a phase signal tensor', 'compute equal-segment-length splines with interpolated tracks for each animation in a motion capture dataset', 'train a PaceNetwork model on motion capture spline dataset sequences with configurable batch size and epochs', 'predict amplitude frequency and direction tracks on a spline using a trained PaceNetwork model', 'extract curvature and speed input features or amplitude frequency direction output features from a spline', 'save or load PaceNetwork model weights to and from a file using torch state dict', 'compute versor-based angle difference or angle sum between two 2D direction vectors using static methods', 'generate a locomotion sequence by following a spline path with an action prefix using PoseNetworkLongTerm', 'apply random rotation data augmentation to a batch of pose rotation and position buffers', 'compute positional loss with forward kinematics comparing predicted quaternions to expected 3D positions', 'prepare and yield augmented training batches of rotations and positions from a motion capture dataset', 'review the PoseNetworkLongTerm class that extends PoseNetwork for long-term human motion prediction']
```

Usage

```
{'train_pacenetwork': 'train a PaceNetwork model on motion capture spline dataset sequences with configurable batch size and epochs', 'predict_pacenetwork': 'predict amplitude frequency and direction tracks on a spline using a trained PaceNetwork model', 'extract_features_spline': 'extract curvature and speed input features or amplitude frequency direction output features from a spline', 'save_load_pacenetwork_weights': 'save or load PaceNetwork model weights to and from a file using torch state dict', 'compute_angle_operations': 'compute versor-based angle difference or angle sum between two 2D direction vectors using static methods'}
```

## File: facebookresearch_quaternet/long_term/pose_network_long_term.py

Prompts

```
['build a phase track signal from world positions by detecting footstep contacts and walking cycle state', 'extract translation and control features including longitudinal speed, height, and walking phase from motion data', 'build extra features for all subjects and actions in a motion capture dataset', 'extract amplitude, absolute phase, and angular velocity from a phase signal tensor', 'compute equal-segment-length splines with interpolated tracks for each animation in a motion capture dataset', 'train a PaceNetwork model on motion capture spline dataset sequences with configurable batch size and epochs', 'predict amplitude frequency and direction tracks on a spline using a trained PaceNetwork model', 'extract curvature and speed input features or amplitude frequency direction output features from a spline', 'save or load PaceNetwork model weights to and from a file using torch state dict', 'compute versor-based angle difference or angle sum between two 2D direction vectors using static methods', 'generate a locomotion sequence by following a spline path with an action prefix using PoseNetworkLongTerm', 'apply random rotation data augmentation to a batch of pose rotation and position buffers', 'compute positional loss with forward kinematics comparing predicted quaternions to expected 3D positions', 'prepare and yield augmented training batches of rotations and positions from a motion capture dataset', 'review the PoseNetworkLongTerm class that extends PoseNetwork for long-term human motion prediction']
```

Usage

```
{'generate_motion_along_spline': 'generate a locomotion sequence by following a spline path with an action prefix using PoseNetworkLongTerm', 'rotate_batch_augmentation': 'apply random rotation data augmentation to a batch of pose rotation and position buffers', 'compute_positional_loss': 'compute positional loss with forward kinematics comparing predicted quaternions to expected 3D positions', 'prepare_training_batch': 'prepare and yield augmented training batches of rotations and positions from a motion capture dataset', 'review_PoseNetworkLongTerm_class': 'review the PoseNetworkLongTerm class that extends PoseNetwork for long-term human motion prediction'}
```

