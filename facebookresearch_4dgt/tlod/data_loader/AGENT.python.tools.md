# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/data_loader/mvaria_dataset.py

Prompts

```
['create an AriaDataset instance in TEST mode to load multi-view Aria sequences for inference', 'build an AriaDataset with novel view interpolation enabled to generate novel camera viewpoints', 'run the AriaDataset getitem method to retrieve a batch of RGB images and camera poses', 'review the AriaDataset novel time sampling logic that subsamples frames with configurable stride', 'refactor the AriaDataset camera alignment to use average c2w pose for consistent multi-view results', 'load camera poses and metadata from a NeRF-style transforms.json file with frame subsampling', 'save camera poses, intrinsics, and timestamps to a JSON file in NeRF-style format', 'compute ray origins and directions from a camera matrix, field of view, and image resolution', 'distribute sequences across k workers using a greedy load-balancing algorithm based on duration', 'extract and sample frames from a video file or load pre-existing images from a directory']
```

Usage

```
{'create_AriaDataset_for_inference': 'create an AriaDataset instance in TEST mode to load multi-view Aria sequences for inference', 'build_AriaDataset_with_novel_view_sampling': 'build an AriaDataset with novel view interpolation enabled to generate novel camera viewpoints', 'run_AriaDataset_getitem': 'run the AriaDataset getitem method to retrieve a batch of RGB images and camera poses', 'review_AriaDataset_novel_time_sampling': 'review the AriaDataset novel time sampling logic that subsamples frames with configurable stride', 'refactor_AriaDataset_camera_alignment': 'refactor the AriaDataset camera alignment to use average c2w pose for consistent multi-view results'}
```

## File: facebookresearch_4dgt/tlod/data_loader/utils.py

Prompts

```
['create an AriaDataset instance in TEST mode to load multi-view Aria sequences for inference', 'build an AriaDataset with novel view interpolation enabled to generate novel camera viewpoints', 'run the AriaDataset getitem method to retrieve a batch of RGB images and camera poses', 'review the AriaDataset novel time sampling logic that subsamples frames with configurable stride', 'refactor the AriaDataset camera alignment to use average c2w pose for consistent multi-view results', 'load camera poses and metadata from a NeRF-style transforms.json file with frame subsampling', 'save camera poses, intrinsics, and timestamps to a JSON file in NeRF-style format', 'compute ray origins and directions from a camera matrix, field of view, and image resolution', 'distribute sequences across k workers using a greedy load-balancing algorithm based on duration', 'extract and sample frames from a video file or load pre-existing images from a directory']
```

Usage

```
{'load_camera_poses': 'load camera poses and metadata from a NeRF-style transforms.json file with frame subsampling', 'save_camera_poses': 'save camera poses, intrinsics, and timestamps to a JSON file in NeRF-style format', 'compute_rays': 'compute ray origins and directions from a camera matrix, field of view, and image resolution', 'segment_times_vectorized': 'distribute sequences across k workers using a greedy load-balancing algorithm based on duration', 'prepare_images': 'extract and sample frames from a video file or load pre-existing images from a directory'}
```

