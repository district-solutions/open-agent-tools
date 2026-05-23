# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/data/vision_based_forces_slip_probes.py

Prompts

```
['create a VisionForceSlipDataset instance from an OmegaConf config and dataset name to load tactile force and slip data', 'review the get_map_idx2traj method that builds index-to-trajectory mappings and computes slip horizon labels for all samples', 'review the _get_force_slip_labels method that computes debounced slip labels and normalized absolute and delta forces', 'review the _get_tactile_images method that loads and transforms tactile images into video, concatenated, or single image format', 'review the _getitem_trajectory method that retrieves a single trajectory sample with its tactile image, delta force, and slip label', 'create a DemoForceFieldData instance with config, digit serial, and gelsight device id to connect tactile sensors', 'connect to a Digit tactile sensor device by serial number and configure QVGA resolution at 30fps', 'connect to a Gelsight tactile sensor using OpenCV VideoCapture with the specified device id', 'get model inputs dictionary with image tensors, background images, and current color image from tactile sensor', 'process a tactile image by converting to RGB, rotating if needed, and cropping to 4:3 aspect ratio', 'create a PoseDataset from a DictConfig to load tactile images and discretized pose labels for a finger type', 'discretize continuous 6D poses into bin-based class labels for translation X, Y and rotation Yaw', 'get a sample from the PoseDataset returning tactile images and pose labels for a given index', 'get tactile images for a sample index formatted as video, concatenated channels, or single image', 'plot and save a tactile image clip as a PNG figure for debugging purposes', 'create a DigitSlipDataset instance from an OmegaConf config and dataset name for tactile slip detection', 'build a mapping from sample indices to trajectory IDs with slip horizon labels for the dataset', 'test the DigitSlipDataset __getitem__ method to retrieve tactile images, delta force, and slip labels', 'review the _get_tactile_images method that loads and transforms tactile images in video or concatenated format', 'summarize the _get_trajectory_pose_force method that returns pose and force data for a given trajectory']
```

Usage

```
{'create_VisionForceSlipDataset': 'create a VisionForceSlipDataset instance from an OmegaConf config and dataset name to load tactile force and slip data', 'review_get_map_idx2traj': 'review the get_map_idx2traj method that builds index-to-trajectory mappings and computes slip horizon labels for all samples', 'review__get_force_slip_labels': 'review the _get_force_slip_labels method that computes debounced slip labels and normalized absolute and delta forces', 'review__get_tactile_images': 'review the _get_tactile_images method that loads and transforms tactile images into video, concatenated, or single image format', 'review__getitem_trajectory': 'review the _getitem_trajectory method that retrieves a single trajectory sample with its tactile image, delta force, and slip label'}
```

## File: facebookresearch_sparsh/tactile_ssl/data/vision_based_interactive.py

Prompts

```
['create a VisionForceSlipDataset instance from an OmegaConf config and dataset name to load tactile force and slip data', 'review the get_map_idx2traj method that builds index-to-trajectory mappings and computes slip horizon labels for all samples', 'review the _get_force_slip_labels method that computes debounced slip labels and normalized absolute and delta forces', 'review the _get_tactile_images method that loads and transforms tactile images into video, concatenated, or single image format', 'review the _getitem_trajectory method that retrieves a single trajectory sample with its tactile image, delta force, and slip label', 'create a DemoForceFieldData instance with config, digit serial, and gelsight device id to connect tactile sensors', 'connect to a Digit tactile sensor device by serial number and configure QVGA resolution at 30fps', 'connect to a Gelsight tactile sensor using OpenCV VideoCapture with the specified device id', 'get model inputs dictionary with image tensors, background images, and current color image from tactile sensor', 'process a tactile image by converting to RGB, rotating if needed, and cropping to 4:3 aspect ratio', 'create a PoseDataset from a DictConfig to load tactile images and discretized pose labels for a finger type', 'discretize continuous 6D poses into bin-based class labels for translation X, Y and rotation Yaw', 'get a sample from the PoseDataset returning tactile images and pose labels for a given index', 'get tactile images for a sample index formatted as video, concatenated channels, or single image', 'plot and save a tactile image clip as a PNG figure for debugging purposes', 'create a DigitSlipDataset instance from an OmegaConf config and dataset name for tactile slip detection', 'build a mapping from sample indices to trajectory IDs with slip horizon labels for the dataset', 'test the DigitSlipDataset __getitem__ method to retrieve tactile images, delta force, and slip labels', 'review the _get_tactile_images method that loads and transforms tactile images in video or concatenated format', 'summarize the _get_trajectory_pose_force method that returns pose and force data for a given trajectory']
```

Usage

```
{'create_DemoForceFieldData': 'create a DemoForceFieldData instance with config, digit serial, and gelsight device id to connect tactile sensors', 'connect_digit_sensor': 'connect to a Digit tactile sensor device by serial number and configure QVGA resolution at 30fps', 'connect_gelsight_sensor': 'connect to a Gelsight tactile sensor using OpenCV VideoCapture with the specified device id', 'get_model_inputs': 'get model inputs dictionary with image tensors, background images, and current color image from tactile sensor', 'process_tactile_image': 'process a tactile image by converting to RGB, rotating if needed, and cropping to 4:3 aspect ratio'}
```

## File: facebookresearch_sparsh/tactile_ssl/data/vision_based_pose_probes.py

Prompts

```
['create a VisionForceSlipDataset instance from an OmegaConf config and dataset name to load tactile force and slip data', 'review the get_map_idx2traj method that builds index-to-trajectory mappings and computes slip horizon labels for all samples', 'review the _get_force_slip_labels method that computes debounced slip labels and normalized absolute and delta forces', 'review the _get_tactile_images method that loads and transforms tactile images into video, concatenated, or single image format', 'review the _getitem_trajectory method that retrieves a single trajectory sample with its tactile image, delta force, and slip label', 'create a DemoForceFieldData instance with config, digit serial, and gelsight device id to connect tactile sensors', 'connect to a Digit tactile sensor device by serial number and configure QVGA resolution at 30fps', 'connect to a Gelsight tactile sensor using OpenCV VideoCapture with the specified device id', 'get model inputs dictionary with image tensors, background images, and current color image from tactile sensor', 'process a tactile image by converting to RGB, rotating if needed, and cropping to 4:3 aspect ratio', 'create a PoseDataset from a DictConfig to load tactile images and discretized pose labels for a finger type', 'discretize continuous 6D poses into bin-based class labels for translation X, Y and rotation Yaw', 'get a sample from the PoseDataset returning tactile images and pose labels for a given index', 'get tactile images for a sample index formatted as video, concatenated channels, or single image', 'plot and save a tactile image clip as a PNG figure for debugging purposes', 'create a DigitSlipDataset instance from an OmegaConf config and dataset name for tactile slip detection', 'build a mapping from sample indices to trajectory IDs with slip horizon labels for the dataset', 'test the DigitSlipDataset __getitem__ method to retrieve tactile images, delta force, and slip labels', 'review the _get_tactile_images method that loads and transforms tactile images in video or concatenated format', 'summarize the _get_trajectory_pose_force method that returns pose and force data for a given trajectory']
```

Usage

```
{'create_PoseDataset': 'create a PoseDataset from a DictConfig to load tactile images and discretized pose labels for a finger type', 'discretize_poses_PoseDataset': 'discretize continuous 6D poses into bin-based class labels for translation X, Y and rotation Yaw', 'get_item_PoseDataset': 'get a sample from the PoseDataset returning tactile images and pose labels for a given index', 'get_tactile_images_PoseDataset': 'get tactile images for a sample index formatted as video, concatenated channels, or single image', 'plot_tactile_clip_PoseDataset': 'plot and save a tactile image clip as a PNG figure for debugging purposes'}
```

## File: facebookresearch_sparsh/tactile_ssl/data/vision_based_slip_probes.py

Prompts

```
['create a VisionForceSlipDataset instance from an OmegaConf config and dataset name to load tactile force and slip data', 'review the get_map_idx2traj method that builds index-to-trajectory mappings and computes slip horizon labels for all samples', 'review the _get_force_slip_labels method that computes debounced slip labels and normalized absolute and delta forces', 'review the _get_tactile_images method that loads and transforms tactile images into video, concatenated, or single image format', 'review the _getitem_trajectory method that retrieves a single trajectory sample with its tactile image, delta force, and slip label', 'create a DemoForceFieldData instance with config, digit serial, and gelsight device id to connect tactile sensors', 'connect to a Digit tactile sensor device by serial number and configure QVGA resolution at 30fps', 'connect to a Gelsight tactile sensor using OpenCV VideoCapture with the specified device id', 'get model inputs dictionary with image tensors, background images, and current color image from tactile sensor', 'process a tactile image by converting to RGB, rotating if needed, and cropping to 4:3 aspect ratio', 'create a PoseDataset from a DictConfig to load tactile images and discretized pose labels for a finger type', 'discretize continuous 6D poses into bin-based class labels for translation X, Y and rotation Yaw', 'get a sample from the PoseDataset returning tactile images and pose labels for a given index', 'get tactile images for a sample index formatted as video, concatenated channels, or single image', 'plot and save a tactile image clip as a PNG figure for debugging purposes', 'create a DigitSlipDataset instance from an OmegaConf config and dataset name for tactile slip detection', 'build a mapping from sample indices to trajectory IDs with slip horizon labels for the dataset', 'test the DigitSlipDataset __getitem__ method to retrieve tactile images, delta force, and slip labels', 'review the _get_tactile_images method that loads and transforms tactile images in video or concatenated format', 'summarize the _get_trajectory_pose_force method that returns pose and force data for a given trajectory']
```

Usage

```
{'create_DigitSlipDataset': 'create a DigitSlipDataset instance from an OmegaConf config and dataset name for tactile slip detection', 'build_get_map_idx2traj': 'build a mapping from sample indices to trajectory IDs with slip horizon labels for the dataset', 'test_getitem': 'test the DigitSlipDataset __getitem__ method to retrieve tactile images, delta force, and slip labels', 'review_get_tactile_images': 'review the _get_tactile_images method that loads and transforms tactile images in video or concatenated format', 'summarize_get_trajectory_pose_force': 'summarize the _get_trajectory_pose_force method that returns pose and force data for a given trajectory'}
```

