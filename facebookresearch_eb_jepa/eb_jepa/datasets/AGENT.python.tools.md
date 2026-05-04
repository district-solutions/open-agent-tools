# Agent Python Tools

- repo: facebookresearch/eb/jepa
- repo_uri: https://github.com/facebookresearch/eb_jepa

## File: facebookresearch_eb_jepa/eb_jepa/datasets/moving_mnist.py

Prompts

```
['create a MovingMNIST PyTorch dataset for train or val split with greyscale video frames', 'create a MovingMNISTDet dataset that returns video frames and digit location heatmaps', 'run load_or_download to fetch mnist_test_seq.npy from URL if the file does not exist locally', 'run return_bbox on a numpy image array to extract bounding boxes via OpenCV contours', 'review the MovingMNIST __getitem__ method that returns normalized video frames as a torch tensor', 'create a subclass of TrajDataset that implements get_seq_length to return trajectory lengths', 'build a TrajSubset from an existing TrajDataset and a list of selected indices', 'create a TrajSlicerDataset that slices trajectories into fixed-length frame windows with configurable frameskip', 'run random_split_traj to split a TrajDataset into train and validation subsets by specified lengths', 'run get_train_val_sliced to split a trajectory dataset into sliced train and validation sets', 'init data loaders for the two_rooms environment with optional config overrides', 'load the base data config YAML for an environment and apply overrides', 'init train and validation data loaders with custom batch size and worker settings', 'load environment data config and merge custom override values into the base config', 'review the init_data function to understand how WallDataset and DataLoader are configured']
```

Usage

```
{'create_MovingMNIST_dataset': 'create a MovingMNIST PyTorch dataset for train or val split with greyscale video frames', 'create_MovingMNISTDet_dataset': 'create a MovingMNISTDet dataset that returns video frames and digit location heatmaps', 'run_load_or_download': 'run load_or_download to fetch mnist_test_seq.npy from URL if the file does not exist locally', 'run_return_bbox': 'run return_bbox on a numpy image array to extract bounding boxes via OpenCV contours', 'review_MovingMNIST_getitem': 'review the MovingMNIST __getitem__ method that returns normalized video frames as a torch tensor'}
```

## File: facebookresearch_eb_jepa/eb_jepa/datasets/traj_dset.py

Prompts

```
['create a MovingMNIST PyTorch dataset for train or val split with greyscale video frames', 'create a MovingMNISTDet dataset that returns video frames and digit location heatmaps', 'run load_or_download to fetch mnist_test_seq.npy from URL if the file does not exist locally', 'run return_bbox on a numpy image array to extract bounding boxes via OpenCV contours', 'review the MovingMNIST __getitem__ method that returns normalized video frames as a torch tensor', 'create a subclass of TrajDataset that implements get_seq_length to return trajectory lengths', 'build a TrajSubset from an existing TrajDataset and a list of selected indices', 'create a TrajSlicerDataset that slices trajectories into fixed-length frame windows with configurable frameskip', 'run random_split_traj to split a TrajDataset into train and validation subsets by specified lengths', 'run get_train_val_sliced to split a trajectory dataset into sliced train and validation sets', 'init data loaders for the two_rooms environment with optional config overrides', 'load the base data config YAML for an environment and apply overrides', 'init train and validation data loaders with custom batch size and worker settings', 'load environment data config and merge custom override values into the base config', 'review the init_data function to understand how WallDataset and DataLoader are configured']
```

Usage

```
{'create_TrajDataset_subclass': 'create a subclass of TrajDataset that implements get_seq_length to return trajectory lengths', 'build_TrajSubset': 'build a TrajSubset from an existing TrajDataset and a list of selected indices', 'create_TrajSlicerDataset': 'create a TrajSlicerDataset that slices trajectories into fixed-length frame windows with configurable frameskip', 'run_random_split_traj': 'run random_split_traj to split a TrajDataset into train and validation subsets by specified lengths', 'run_get_train_val_sliced': 'run get_train_val_sliced to split a trajectory dataset into sliced train and validation sets'}
```

## File: facebookresearch_eb_jepa/eb_jepa/datasets/utils.py

Prompts

```
['create a MovingMNIST PyTorch dataset for train or val split with greyscale video frames', 'create a MovingMNISTDet dataset that returns video frames and digit location heatmaps', 'run load_or_download to fetch mnist_test_seq.npy from URL if the file does not exist locally', 'run return_bbox on a numpy image array to extract bounding boxes via OpenCV contours', 'review the MovingMNIST __getitem__ method that returns normalized video frames as a torch tensor', 'create a subclass of TrajDataset that implements get_seq_length to return trajectory lengths', 'build a TrajSubset from an existing TrajDataset and a list of selected indices', 'create a TrajSlicerDataset that slices trajectories into fixed-length frame windows with configurable frameskip', 'run random_split_traj to split a TrajDataset into train and validation subsets by specified lengths', 'run get_train_val_sliced to split a trajectory dataset into sliced train and validation sets', 'init data loaders for the two_rooms environment with optional config overrides', 'load the base data config YAML for an environment and apply overrides', 'init train and validation data loaders with custom batch size and worker settings', 'load environment data config and merge custom override values into the base config', 'review the init_data function to understand how WallDataset and DataLoader are configured']
```

Usage

```
{'init_data_two_rooms': 'init data loaders for the two_rooms environment with optional config overrides', 'load_env_data_config': 'load the base data config YAML for an environment and apply overrides', 'init_data_custom_cfg': 'init train and validation data loaders with custom batch size and worker settings', 'load_env_data_config_overrides': 'load environment data config and merge custom override values into the base config', 'review_init_data': 'review the init_data function to understand how WallDataset and DataLoader are configured'}
```

