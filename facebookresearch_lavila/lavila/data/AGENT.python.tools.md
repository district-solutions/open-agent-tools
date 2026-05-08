# Agent Python Tools

- repo: facebookresearch/lavila
- repo_uri: https://github.com/facebookresearch/lavila

## File: facebookresearch_lavila/lavila/data/datasets.py

Prompts

```
['use video_loader to extract frames from a video file between start and end timestamps with configurable FPS and clip length', 'use get_frame_ids to uniformly sample frame IDs between a start and end frame with optional jitter for training augmentation', 'use video_loader_by_frames to load specific frames from a video given a list of frame IDs and return a stacked tensor', 'use VideoCaptionDatasetCLIP to create a PyTorch dataset for video-caption pairs with CLIP-style transforms and tokenization for training', 'use get_downstream_dataset to create a VideoClassyDataset for video classification tasks with label mapping and configurable clip sampling', 'create a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'create a SpatialCrop module to generate multiple spatial crops from a list of video tensors', 'build a uniform crop function to perform spatial sampling on images with optional bounding box adjustment', 'create a Permute nn.Module to reorder tensor dimensions for video frame tensors', 'refactor bounding box coordinates by applying x and y offset adjustments for cropping']
```

Usage

```
{'load_video_frames_by_time': 'use video_loader to extract frames from a video file between start and end timestamps with configurable FPS and clip length', 'sample_frame_ids_uniformly': 'use get_frame_ids to uniformly sample frame IDs between a start and end frame with optional jitter for training augmentation', 'load_video_frames_by_frame_ids': 'use video_loader_by_frames to load specific frames from a video given a list of frame IDs and return a stacked tensor', 'create_clip_video_dataset': 'use VideoCaptionDatasetCLIP to create a PyTorch dataset for video-caption pairs with CLIP-style transforms and tokenization for training', 'create_downstream_classification_dataset': 'use get_downstream_dataset to create a VideoClassyDataset for video classification tasks with label mapping and configurable clip sampling'}
```

## File: facebookresearch_lavila/lavila/data/video_transforms.py

Prompts

```
['use video_loader to extract frames from a video file between start and end timestamps with configurable FPS and clip length', 'use get_frame_ids to uniformly sample frame IDs between a start and end frame with optional jitter for training augmentation', 'use video_loader_by_frames to load specific frames from a video given a list of frame IDs and return a stacked tensor', 'use VideoCaptionDatasetCLIP to create a PyTorch dataset for video-caption pairs with CLIP-style transforms and tokenization for training', 'use get_downstream_dataset to create a VideoClassyDataset for video classification tasks with label mapping and configurable clip sampling', 'create a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'create a SpatialCrop module to generate multiple spatial crops from a list of video tensors', 'build a uniform crop function to perform spatial sampling on images with optional bounding box adjustment', 'create a Permute nn.Module to reorder tensor dimensions for video frame tensors', 'refactor bounding box coordinates by applying x and y offset adjustments for cropping']
```

Usage

```
{'create_temporal_crop': 'create a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'create_spatial_crop': 'create a SpatialCrop module to generate multiple spatial crops from a list of video tensors', 'build_uniform_crop': 'build a uniform crop function to perform spatial sampling on images with optional bounding box adjustment', 'create_permute_op': 'create a Permute nn.Module to reorder tensor dimensions for video frame tensors', 'refactor_crop_boxes': 'refactor bounding box coordinates by applying x and y offset adjustments for cropping'}
```

