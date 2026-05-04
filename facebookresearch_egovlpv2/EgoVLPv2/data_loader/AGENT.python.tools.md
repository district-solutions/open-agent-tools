# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoVLPv2/data_loader/EpicKitchens_MIR_dataset.py

Prompts

```
['build a MultiInstanceRetrieval dataset for EpicKitchens video-text retrieval with configurable split and video parameters', 'review the get_frame_ids method to sample frame IDs with jitter for training or uniform for evaluation', 'test the video_loader_by_frames method to load video frames using decord and return stacked tensors', 'refactor the __getitem__ method to load video frames, apply transforms, and return video-text pairs with metadata', 'summarize the datetime2sec method that converts HH:MM:SS timestamp strings to total seconds as a float', 'create a dataset instance for EgoClip, EpicKitchens_MIR, CharadesEgo, or Ego4D_MQ using dataset_loader', 'build a TextVideoDataLoader for text-video pairs with configurable transforms, batch size, and shuffle', 'build a distributed TextVideoDataLoader for multi-GPU training with cv2 reader and transform params', 'build a MultiDistTextVideoDataLoader that combines multiple datasets for distributed training with args', 'build a TextVideoMultiDataLoader that dynamically instantiates two data loaders from config dicts with type and args', 'build a python module that creates train, val, and test image transform pipelines using init_transform_dict', 'build a python module that creates train, val, and test video transform pipelines using init_video_transform_dict', 'create a function that returns torchvision image transforms for training validation and testing with normalization', 'create a function that returns torchvision video transforms with RandomResizedCropVideo and RandomHorizontalFlipVideo for training', 'refactor init_transform_dict to support custom normalization mean and std values for different datasets']
```

Usage

```
{'build_MultiInstanceRetrieval_dataset': 'build a MultiInstanceRetrieval dataset for EpicKitchens video-text retrieval with configurable split and video parameters', 'review_get_frame_ids': 'review the get_frame_ids method to sample frame IDs with jitter for training or uniform for evaluation', 'test_video_loader_by_frames': 'test the video_loader_by_frames method to load video frames using decord and return stacked tensors', 'refactor_getitem': 'refactor the __getitem__ method to load video frames, apply transforms, and return video-text pairs with metadata', 'summarize_datetime2sec': 'summarize the datetime2sec method that converts HH:MM:SS timestamp strings to total seconds as a float'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/data_loader/data_loader.py

Prompts

```
['build a MultiInstanceRetrieval dataset for EpicKitchens video-text retrieval with configurable split and video parameters', 'review the get_frame_ids method to sample frame IDs with jitter for training or uniform for evaluation', 'test the video_loader_by_frames method to load video frames using decord and return stacked tensors', 'refactor the __getitem__ method to load video frames, apply transforms, and return video-text pairs with metadata', 'summarize the datetime2sec method that converts HH:MM:SS timestamp strings to total seconds as a float', 'create a dataset instance for EgoClip, EpicKitchens_MIR, CharadesEgo, or Ego4D_MQ using dataset_loader', 'build a TextVideoDataLoader for text-video pairs with configurable transforms, batch size, and shuffle', 'build a distributed TextVideoDataLoader for multi-GPU training with cv2 reader and transform params', 'build a MultiDistTextVideoDataLoader that combines multiple datasets for distributed training with args', 'build a TextVideoMultiDataLoader that dynamically instantiates two data loaders from config dicts with type and args', 'build a python module that creates train, val, and test image transform pipelines using init_transform_dict', 'build a python module that creates train, val, and test video transform pipelines using init_video_transform_dict', 'create a function that returns torchvision image transforms for training validation and testing with normalization', 'create a function that returns torchvision video transforms with RandomResizedCropVideo and RandomHorizontalFlipVideo for training', 'refactor init_transform_dict to support custom normalization mean and std values for different datasets']
```

Usage

```
{'create_dataset_loader': 'create a dataset instance for EgoClip, EpicKitchens_MIR, CharadesEgo, or Ego4D_MQ using dataset_loader', 'build_TextVideoDataLoader': 'build a TextVideoDataLoader for text-video pairs with configurable transforms, batch size, and shuffle', 'build_DistTextVideoDataLoader': 'build a distributed TextVideoDataLoader for multi-GPU training with cv2 reader and transform params', 'build_MultiDistTextVideoDataLoader': 'build a MultiDistTextVideoDataLoader that combines multiple datasets for distributed training with args', 'build_TextVideoMultiDataLoader': 'build a TextVideoMultiDataLoader that dynamically instantiates two data loaders from config dicts with type and args'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/data_loader/transforms.py

Prompts

```
['build a MultiInstanceRetrieval dataset for EpicKitchens video-text retrieval with configurable split and video parameters', 'review the get_frame_ids method to sample frame IDs with jitter for training or uniform for evaluation', 'test the video_loader_by_frames method to load video frames using decord and return stacked tensors', 'refactor the __getitem__ method to load video frames, apply transforms, and return video-text pairs with metadata', 'summarize the datetime2sec method that converts HH:MM:SS timestamp strings to total seconds as a float', 'create a dataset instance for EgoClip, EpicKitchens_MIR, CharadesEgo, or Ego4D_MQ using dataset_loader', 'build a TextVideoDataLoader for text-video pairs with configurable transforms, batch size, and shuffle', 'build a distributed TextVideoDataLoader for multi-GPU training with cv2 reader and transform params', 'build a MultiDistTextVideoDataLoader that combines multiple datasets for distributed training with args', 'build a TextVideoMultiDataLoader that dynamically instantiates two data loaders from config dicts with type and args', 'build a python module that creates train, val, and test image transform pipelines using init_transform_dict', 'build a python module that creates train, val, and test video transform pipelines using init_video_transform_dict', 'create a function that returns torchvision image transforms for training validation and testing with normalization', 'create a function that returns torchvision video transforms with RandomResizedCropVideo and RandomHorizontalFlipVideo for training', 'refactor init_transform_dict to support custom normalization mean and std values for different datasets']
```

Usage

```
{'build_image_transform_dict': 'build a python module that creates train, val, and test image transform pipelines using init_transform_dict', 'build_video_transform_dict': 'build a python module that creates train, val, and test video transform pipelines using init_video_transform_dict', 'create_image_transforms': 'create a function that returns torchvision image transforms for training validation and testing with normalization', 'create_video_transforms': 'create a function that returns torchvision video transforms with RandomResizedCropVideo and RandomHorizontalFlipVideo for training', 'refactor_transform_dict': 'refactor init_transform_dict to support custom normalization mean and std values for different datasets'}
```

