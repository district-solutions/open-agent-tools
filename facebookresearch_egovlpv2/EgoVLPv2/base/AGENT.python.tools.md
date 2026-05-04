# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoVLPv2/base/base_data_loader.py

Prompts

```
['build a BaseDataLoader with a dataset, batch size, shuffle flag, validation split, and num workers', 'create a validation DataLoader from a BaseDataLoader using the split_validation method with optional diff_kwargs', 'build a BaseDataLoaderExplicitSplit for datasets with pre-split train and validation without auto splitting', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU training with pin memory enabled', 'build a BaseMultiDataLoader that undersamples multiple dataloaders and returns batches by cycling through them', 'create a subclass of TextVideoDataset that implements _load_metadata, _get_video_path, and _get_caption for a custom video-text dataset', 'use read_frames_decord to read and sample N frames from a video file using decord with random or uniform sampling', 'use read_frames_cv2 to read and sample N frames from a video file using OpenCV with random or uniform sampling', 'use sample_frames to compute frame indices for sampling N frames from a video of given length with rand, uniform, or fixed start', 'use get_video_len to get the total frame count of a video file using OpenCV', 'review the BaseModel class forward method that defines the abstract forward pass logic for all models', 'review the BaseModel class __str__ method that prints the model with its trainable parameter count', 'build a PyTorch model subclass that inherits BaseModel and implements the abstract forward method', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'refactor the BaseModel forward method to accept specific input types instead of variadic arguments', 'build a subclass of BaseTrainer implementing _train_epoch and _valid_epoch for custom model training', 'run the BaseTrainer train method to execute full training loop with early stopping and checkpointing', 'create a checkpoint by calling _save_checkpoint to persist model state, optimizer, and config', 'resume training from a saved checkpoint using _resume_checkpoint with automatic DataParallel key handling', 'review the Multi_BaseTrainer_dist class for distributed training with DDP and GradScaler support']
```

Usage

```
{'build_base_dataloader': 'build a BaseDataLoader with a dataset, batch size, shuffle flag, validation split, and num workers', 'create_validation_split': 'create a validation DataLoader from a BaseDataLoader using the split_validation method with optional diff_kwargs', 'build_explicit_split_dataloader': 'build a BaseDataLoaderExplicitSplit for datasets with pre-split train and validation without auto splitting', 'create_distributed_dataloader': 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU training with pin memory enabled', 'build_multi_dataloader': 'build a BaseMultiDataLoader that undersamples multiple dataloaders and returns batches by cycling through them'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/base/base_dataset.py

Prompts

```
['build a BaseDataLoader with a dataset, batch size, shuffle flag, validation split, and num workers', 'create a validation DataLoader from a BaseDataLoader using the split_validation method with optional diff_kwargs', 'build a BaseDataLoaderExplicitSplit for datasets with pre-split train and validation without auto splitting', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU training with pin memory enabled', 'build a BaseMultiDataLoader that undersamples multiple dataloaders and returns batches by cycling through them', 'create a subclass of TextVideoDataset that implements _load_metadata, _get_video_path, and _get_caption for a custom video-text dataset', 'use read_frames_decord to read and sample N frames from a video file using decord with random or uniform sampling', 'use read_frames_cv2 to read and sample N frames from a video file using OpenCV with random or uniform sampling', 'use sample_frames to compute frame indices for sampling N frames from a video of given length with rand, uniform, or fixed start', 'use get_video_len to get the total frame count of a video file using OpenCV', 'review the BaseModel class forward method that defines the abstract forward pass logic for all models', 'review the BaseModel class __str__ method that prints the model with its trainable parameter count', 'build a PyTorch model subclass that inherits BaseModel and implements the abstract forward method', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'refactor the BaseModel forward method to accept specific input types instead of variadic arguments', 'build a subclass of BaseTrainer implementing _train_epoch and _valid_epoch for custom model training', 'run the BaseTrainer train method to execute full training loop with early stopping and checkpointing', 'create a checkpoint by calling _save_checkpoint to persist model state, optimizer, and config', 'resume training from a saved checkpoint using _resume_checkpoint with automatic DataParallel key handling', 'review the Multi_BaseTrainer_dist class for distributed training with DDP and GradScaler support']
```

Usage

```
{'create_TextVideoDataset_subclass': 'create a subclass of TextVideoDataset that implements _load_metadata, _get_video_path, and _get_caption for a custom video-text dataset', 'use_read_frames_decord': 'use read_frames_decord to read and sample N frames from a video file using decord with random or uniform sampling', 'use_read_frames_cv2': 'use read_frames_cv2 to read and sample N frames from a video file using OpenCV with random or uniform sampling', 'use_sample_frames': 'use sample_frames to compute frame indices for sampling N frames from a video of given length with rand, uniform, or fixed start', 'use_get_video_len': 'use get_video_len to get the total frame count of a video file using OpenCV'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/base/base_model.py

Prompts

```
['build a BaseDataLoader with a dataset, batch size, shuffle flag, validation split, and num workers', 'create a validation DataLoader from a BaseDataLoader using the split_validation method with optional diff_kwargs', 'build a BaseDataLoaderExplicitSplit for datasets with pre-split train and validation without auto splitting', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU training with pin memory enabled', 'build a BaseMultiDataLoader that undersamples multiple dataloaders and returns batches by cycling through them', 'create a subclass of TextVideoDataset that implements _load_metadata, _get_video_path, and _get_caption for a custom video-text dataset', 'use read_frames_decord to read and sample N frames from a video file using decord with random or uniform sampling', 'use read_frames_cv2 to read and sample N frames from a video file using OpenCV with random or uniform sampling', 'use sample_frames to compute frame indices for sampling N frames from a video of given length with rand, uniform, or fixed start', 'use get_video_len to get the total frame count of a video file using OpenCV', 'review the BaseModel class forward method that defines the abstract forward pass logic for all models', 'review the BaseModel class __str__ method that prints the model with its trainable parameter count', 'build a PyTorch model subclass that inherits BaseModel and implements the abstract forward method', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'refactor the BaseModel forward method to accept specific input types instead of variadic arguments', 'build a subclass of BaseTrainer implementing _train_epoch and _valid_epoch for custom model training', 'run the BaseTrainer train method to execute full training loop with early stopping and checkpointing', 'create a checkpoint by calling _save_checkpoint to persist model state, optimizer, and config', 'resume training from a saved checkpoint using _resume_checkpoint with automatic DataParallel key handling', 'review the Multi_BaseTrainer_dist class for distributed training with DDP and GradScaler support']
```

Usage

```
{'review_BASEMODEL_forward': 'review the BaseModel class forward method that defines the abstract forward pass logic for all models', 'review_BASEMODEL_str': 'review the BaseModel class __str__ method that prints the model with its trainable parameter count', 'build_subclass_BASEMODEL': 'build a PyTorch model subclass that inherits BaseModel and implements the abstract forward method', 'test_BASEMODEL_trainable_params': 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'refactor_BASEMODEL_forward': 'refactor the BaseModel forward method to accept specific input types instead of variadic arguments'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/base/base_trainer.py

Prompts

```
['build a BaseDataLoader with a dataset, batch size, shuffle flag, validation split, and num workers', 'create a validation DataLoader from a BaseDataLoader using the split_validation method with optional diff_kwargs', 'build a BaseDataLoaderExplicitSplit for datasets with pre-split train and validation without auto splitting', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU training with pin memory enabled', 'build a BaseMultiDataLoader that undersamples multiple dataloaders and returns batches by cycling through them', 'create a subclass of TextVideoDataset that implements _load_metadata, _get_video_path, and _get_caption for a custom video-text dataset', 'use read_frames_decord to read and sample N frames from a video file using decord with random or uniform sampling', 'use read_frames_cv2 to read and sample N frames from a video file using OpenCV with random or uniform sampling', 'use sample_frames to compute frame indices for sampling N frames from a video of given length with rand, uniform, or fixed start', 'use get_video_len to get the total frame count of a video file using OpenCV', 'review the BaseModel class forward method that defines the abstract forward pass logic for all models', 'review the BaseModel class __str__ method that prints the model with its trainable parameter count', 'build a PyTorch model subclass that inherits BaseModel and implements the abstract forward method', 'test the BaseModel __str__ method to verify it correctly counts trainable parameters', 'refactor the BaseModel forward method to accept specific input types instead of variadic arguments', 'build a subclass of BaseTrainer implementing _train_epoch and _valid_epoch for custom model training', 'run the BaseTrainer train method to execute full training loop with early stopping and checkpointing', 'create a checkpoint by calling _save_checkpoint to persist model state, optimizer, and config', 'resume training from a saved checkpoint using _resume_checkpoint with automatic DataParallel key handling', 'review the Multi_BaseTrainer_dist class for distributed training with DDP and GradScaler support']
```

Usage

```
{'build_BaseTrainer_subclass': 'build a subclass of BaseTrainer implementing _train_epoch and _valid_epoch for custom model training', 'run_BaseTrainer_train': 'run the BaseTrainer train method to execute full training loop with early stopping and checkpointing', 'create_BaseTrainer_checkpoint': 'create a checkpoint by calling _save_checkpoint to persist model state, optimizer, and config', 'resume_BaseTrainer_checkpoint': 'resume training from a saved checkpoint using _resume_checkpoint with automatic DataParallel key handling', 'review_Multi_BaseTrainer_dist': 'review the Multi_BaseTrainer_dist class for distributed training with DDP and GradScaler support'}
```

