# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/eft/datasets/base_dataset.py

Prompts

```
['create a BaseDataset instance to load and augment human pose estimation data from a specified dataset', 'review the augm_params method to understand how flip, rotation, scale, and pixel noise augmentations are generated', 'test the rgb_processing method to verify image cropping, flipping, and channel-wise pixel noise augmentation', 'refactor the j2d_processing method to transform 2D keypoints into normalized bounding box coordinates with augmentation', 'summarize the __getitem__ method that loads images, processes SMPL parameters, keypoints, and applies all augmentations', 'create a VideoDataset instance with options and dataset name to load human pose estimation data from numpy files', 'build a VideoDataset with bEnforceUpperOnly to crop only upper body regions using 2D keypoint bounding boxes', 'test the VideoDataset getitem method to retrieve a sample with normalized image, SMPL pose, and keypoints', 'review the VideoDataset augm_params method that generates random flip, pixel noise, rotation, and scale augmentation parameters', 'summarize the VideoDataset rgb_processing and j2d_processing methods that crop, flip, and normalize images and 2D keypoints']
```

Usage

```
{'create_BaseDataset': 'create a BaseDataset instance to load and augment human pose estimation data from a specified dataset', 'review_BaseDataset_augm_params': 'review the augm_params method to understand how flip, rotation, scale, and pixel noise augmentations are generated', 'test_BaseDataset_rgb_processing': 'test the rgb_processing method to verify image cropping, flipping, and channel-wise pixel noise augmentation', 'refactor_BaseDataset_j2d_processing': 'refactor the j2d_processing method to transform 2D keypoints into normalized bounding box coordinates with augmentation', 'summarize_BaseDataset_getitem': 'summarize the __getitem__ method that loads images, processes SMPL parameters, keypoints, and applies all augmentations'}
```

## File: facebookresearch_eft/eft/datasets/video_dataset.py

Prompts

```
['create a BaseDataset instance to load and augment human pose estimation data from a specified dataset', 'review the augm_params method to understand how flip, rotation, scale, and pixel noise augmentations are generated', 'test the rgb_processing method to verify image cropping, flipping, and channel-wise pixel noise augmentation', 'refactor the j2d_processing method to transform 2D keypoints into normalized bounding box coordinates with augmentation', 'summarize the __getitem__ method that loads images, processes SMPL parameters, keypoints, and applies all augmentations', 'create a VideoDataset instance with options and dataset name to load human pose estimation data from numpy files', 'build a VideoDataset with bEnforceUpperOnly to crop only upper body regions using 2D keypoint bounding boxes', 'test the VideoDataset getitem method to retrieve a sample with normalized image, SMPL pose, and keypoints', 'review the VideoDataset augm_params method that generates random flip, pixel noise, rotation, and scale augmentation parameters', 'summarize the VideoDataset rgb_processing and j2d_processing methods that crop, flip, and normalize images and 2D keypoints']
```

Usage

```
{'create_VideoDataset': 'create a VideoDataset instance with options and dataset name to load human pose estimation data from numpy files', 'build_VideoDataset_upperbody': 'build a VideoDataset with bEnforceUpperOnly to crop only upper body regions using 2D keypoint bounding boxes', 'test_VideoDataset_getitem': 'test the VideoDataset getitem method to retrieve a sample with normalized image, SMPL pose, and keypoints', 'review_VideoDataset_augm_params': 'review the VideoDataset augm_params method that generates random flip, pixel noise, rotation, and scale augmentation parameters', 'summarize_VideoDataset_processing': 'summarize the VideoDataset rgb_processing and j2d_processing methods that crop, flip, and normalize images and 2D keypoints'}
```

