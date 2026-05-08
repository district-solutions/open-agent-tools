# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/src/datasets/data_manager.py

Prompts

```
['init a data loader and distributed sampler for ImageNet with a given batch size and transform', 'init a data loader and distributed sampler for iNat21 image dataset with custom num workers', 'init a data loader and distributed sampler for Places205 dataset with a subset file', 'init a data loader and distributed sampler for a video dataset with clip length and frame sample rate', 'review the init_data function to understand supported dataset types and parameter defaults', 'create a distributed DataLoader and sampler for an ImageFolder dataset with configurable batch size and workers', 'build an ImageFolder dataset from a root path with optional transform and train or val split', 'review the ImageFolder class that extends torchvision ImageFolder and constructs data paths from root and image_folder', 'refactor the make_imagedataset function to support additional sampler types or custom collation logic', 'summarize the ImageFolder init method that joins root, image_folder, and train or val suffix into a data path', 'create a VideoDataset from CSV or NPY data paths with configurable frames per clip and frame step', 'build a distributed DataLoader with VideoDataset using make_videodataset and optional weighted sampling', 'load video frames from a file using Decord VideoReader with configurable clip sampling and overlap', 'filter short or long videos by size or frame count when loading video data', 'sample multiple random clips from a video with configurable partitioning and frame indexing']
```

Usage

```
{'init_imagenet_dataloader': 'init a data loader and distributed sampler for ImageNet with a given batch size and transform', 'init_inat21_dataloader': 'init a data loader and distributed sampler for iNat21 image dataset with custom num workers', 'init_places205_dataloader': 'init a data loader and distributed sampler for Places205 dataset with a subset file', 'init_videodataset_dataloader': 'init a data loader and distributed sampler for a video dataset with clip length and frame sample rate', 'review_init_data': 'review the init_data function to understand supported dataset types and parameter defaults'}
```

## File: facebookresearch_jepa/src/datasets/image_dataset.py

Prompts

```
['init a data loader and distributed sampler for ImageNet with a given batch size and transform', 'init a data loader and distributed sampler for iNat21 image dataset with custom num workers', 'init a data loader and distributed sampler for Places205 dataset with a subset file', 'init a data loader and distributed sampler for a video dataset with clip length and frame sample rate', 'review the init_data function to understand supported dataset types and parameter defaults', 'create a distributed DataLoader and sampler for an ImageFolder dataset with configurable batch size and workers', 'build an ImageFolder dataset from a root path with optional transform and train or val split', 'review the ImageFolder class that extends torchvision ImageFolder and constructs data paths from root and image_folder', 'refactor the make_imagedataset function to support additional sampler types or custom collation logic', 'summarize the ImageFolder init method that joins root, image_folder, and train or val suffix into a data path', 'create a VideoDataset from CSV or NPY data paths with configurable frames per clip and frame step', 'build a distributed DataLoader with VideoDataset using make_videodataset and optional weighted sampling', 'load video frames from a file using Decord VideoReader with configurable clip sampling and overlap', 'filter short or long videos by size or frame count when loading video data', 'sample multiple random clips from a video with configurable partitioning and frame indexing']
```

Usage

```
{'create_imagedataset_loader': 'create a distributed DataLoader and sampler for an ImageFolder dataset with configurable batch size and workers', 'build_imagefolder_dataset': 'build an ImageFolder dataset from a root path with optional transform and train or val split', 'review_ImageFolder_class': 'review the ImageFolder class that extends torchvision ImageFolder and constructs data paths from root and image_folder', 'refactor_make_imagedataset': 'refactor the make_imagedataset function to support additional sampler types or custom collation logic', 'summarize_ImageFolder_init': 'summarize the ImageFolder init method that joins root, image_folder, and train or val suffix into a data path'}
```

## File: facebookresearch_jepa/src/datasets/video_dataset.py

Prompts

```
['init a data loader and distributed sampler for ImageNet with a given batch size and transform', 'init a data loader and distributed sampler for iNat21 image dataset with custom num workers', 'init a data loader and distributed sampler for Places205 dataset with a subset file', 'init a data loader and distributed sampler for a video dataset with clip length and frame sample rate', 'review the init_data function to understand supported dataset types and parameter defaults', 'create a distributed DataLoader and sampler for an ImageFolder dataset with configurable batch size and workers', 'build an ImageFolder dataset from a root path with optional transform and train or val split', 'review the ImageFolder class that extends torchvision ImageFolder and constructs data paths from root and image_folder', 'refactor the make_imagedataset function to support additional sampler types or custom collation logic', 'summarize the ImageFolder init method that joins root, image_folder, and train or val suffix into a data path', 'create a VideoDataset from CSV or NPY data paths with configurable frames per clip and frame step', 'build a distributed DataLoader with VideoDataset using make_videodataset and optional weighted sampling', 'load video frames from a file using Decord VideoReader with configurable clip sampling and overlap', 'filter short or long videos by size or frame count when loading video data', 'sample multiple random clips from a video with configurable partitioning and frame indexing']
```

Usage

```
{'create_videodataset': 'create a VideoDataset from CSV or NPY data paths with configurable frames per clip and frame step', 'build_dataloader': 'build a distributed DataLoader with VideoDataset using make_videodataset and optional weighted sampling', 'load_video_frames': 'load video frames from a file using Decord VideoReader with configurable clip sampling and overlap', 'filter_videos': 'filter short or long videos by size or frame count when loading video data', 'sample_clips': 'sample multiple random clips from a video with configurable partitioning and frame indexing'}
```

