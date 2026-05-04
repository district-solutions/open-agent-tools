# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/QFVS/base/base_data_loader.py

Prompts

```
['create a BaseDataLoader with a dataset, batch size, shuffle flag, validation split ratio, and num workers', 'split a BaseDataLoader into a separate validation DataLoader using the split_validation method', 'create a BaseDataLoaderExplicitSplit for datasets where train and validation splits are handled externally', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU distributed training with pin memory enabled', 'create a BaseMultiDataLoader that round-robins across multiple dataloaders and undersamples to the smallest one', 'create a TextVideoDataset subclass that loads video-text pairs with configurable frame sampling and transforms', 'sample frame indices from a video using random, uniform, or fixed start strategies', 'read and decode video frames using Decord for efficient batch loading with frame sampling', 'read video frames using OpenCV with configurable frame sampling and tensor conversion', 'get the total frame count of a video file using OpenCV VideoCapture', 'create a subclass of BaseModel that implements the abstract forward method for a custom PyTorch model', 'review the BaseModel forward abstract method to understand the required interface for subclasses', 'test the BaseModel __str__ method to verify it prints trainable parameter counts correctly', 'refactor a subclass of BaseModel to accept typed inputs instead of variadic arguments in forward', 'summarize the BaseModel class and its abstract forward method and parameter counting __str__ override', 'build a python module subclassing BaseTrainer to train a PyTorch model with GPU support and checkpointing', 'run the BaseTrainer train method to execute full training loop with early stopping and metric monitoring', 'create a subclass of BaseTrainer implementing _train_epoch and _valid_epoch abstract methods for custom training logic', 'build a python module subclassing Multi_BaseTrainer_dist for distributed training with DDP and GradScaler support', 'resume training from a saved checkpoint using BaseTrainer _resume_checkpoint with automatic DataParallel key handling']
```

Usage

```
{'create_BaseDataLoader': 'create a BaseDataLoader with a dataset, batch size, shuffle flag, validation split ratio, and num workers', 'split_validation_split_validation': 'split a BaseDataLoader into a separate validation DataLoader using the split_validation method', 'create_BaseDataLoaderExplicitSplit': 'create a BaseDataLoaderExplicitSplit for datasets where train and validation splits are handled externally', 'create_DistBaseDataLoaderExplicitSplit': 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU distributed training with pin memory enabled', 'create_BaseMultiDataLoader': 'create a BaseMultiDataLoader that round-robins across multiple dataloaders and undersamples to the smallest one'}
```

## File: facebookresearch_egovlpv2/QFVS/base/base_dataset.py

Prompts

```
['create a BaseDataLoader with a dataset, batch size, shuffle flag, validation split ratio, and num workers', 'split a BaseDataLoader into a separate validation DataLoader using the split_validation method', 'create a BaseDataLoaderExplicitSplit for datasets where train and validation splits are handled externally', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU distributed training with pin memory enabled', 'create a BaseMultiDataLoader that round-robins across multiple dataloaders and undersamples to the smallest one', 'create a TextVideoDataset subclass that loads video-text pairs with configurable frame sampling and transforms', 'sample frame indices from a video using random, uniform, or fixed start strategies', 'read and decode video frames using Decord for efficient batch loading with frame sampling', 'read video frames using OpenCV with configurable frame sampling and tensor conversion', 'get the total frame count of a video file using OpenCV VideoCapture', 'create a subclass of BaseModel that implements the abstract forward method for a custom PyTorch model', 'review the BaseModel forward abstract method to understand the required interface for subclasses', 'test the BaseModel __str__ method to verify it prints trainable parameter counts correctly', 'refactor a subclass of BaseModel to accept typed inputs instead of variadic arguments in forward', 'summarize the BaseModel class and its abstract forward method and parameter counting __str__ override', 'build a python module subclassing BaseTrainer to train a PyTorch model with GPU support and checkpointing', 'run the BaseTrainer train method to execute full training loop with early stopping and metric monitoring', 'create a subclass of BaseTrainer implementing _train_epoch and _valid_epoch abstract methods for custom training logic', 'build a python module subclassing Multi_BaseTrainer_dist for distributed training with DDP and GradScaler support', 'resume training from a saved checkpoint using BaseTrainer _resume_checkpoint with automatic DataParallel key handling']
```

Usage

```
{'create_TextVideoDataset': 'create a TextVideoDataset subclass that loads video-text pairs with configurable frame sampling and transforms', 'sample_frames': 'sample frame indices from a video using random, uniform, or fixed start strategies', 'read_frames_decord': 'read and decode video frames using Decord for efficient batch loading with frame sampling', 'read_frames_cv2': 'read video frames using OpenCV with configurable frame sampling and tensor conversion', 'get_video_len': 'get the total frame count of a video file using OpenCV VideoCapture'}
```

## File: facebookresearch_egovlpv2/QFVS/base/base_model.py

Prompts

```
['create a BaseDataLoader with a dataset, batch size, shuffle flag, validation split ratio, and num workers', 'split a BaseDataLoader into a separate validation DataLoader using the split_validation method', 'create a BaseDataLoaderExplicitSplit for datasets where train and validation splits are handled externally', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU distributed training with pin memory enabled', 'create a BaseMultiDataLoader that round-robins across multiple dataloaders and undersamples to the smallest one', 'create a TextVideoDataset subclass that loads video-text pairs with configurable frame sampling and transforms', 'sample frame indices from a video using random, uniform, or fixed start strategies', 'read and decode video frames using Decord for efficient batch loading with frame sampling', 'read video frames using OpenCV with configurable frame sampling and tensor conversion', 'get the total frame count of a video file using OpenCV VideoCapture', 'create a subclass of BaseModel that implements the abstract forward method for a custom PyTorch model', 'review the BaseModel forward abstract method to understand the required interface for subclasses', 'test the BaseModel __str__ method to verify it prints trainable parameter counts correctly', 'refactor a subclass of BaseModel to accept typed inputs instead of variadic arguments in forward', 'summarize the BaseModel class and its abstract forward method and parameter counting __str__ override', 'build a python module subclassing BaseTrainer to train a PyTorch model with GPU support and checkpointing', 'run the BaseTrainer train method to execute full training loop with early stopping and metric monitoring', 'create a subclass of BaseTrainer implementing _train_epoch and _valid_epoch abstract methods for custom training logic', 'build a python module subclassing Multi_BaseTrainer_dist for distributed training with DDP and GradScaler support', 'resume training from a saved checkpoint using BaseTrainer _resume_checkpoint with automatic DataParallel key handling']
```

Usage

```
{'create_subclass_of_Basemodel': 'create a subclass of BaseModel that implements the abstract forward method for a custom PyTorch model', 'review_Basemodel_forward': 'review the BaseModel forward abstract method to understand the required interface for subclasses', 'test_Basemodel_str': 'test the BaseModel __str__ method to verify it prints trainable parameter counts correctly', 'refactor_Basemodel_forward': 'refactor a subclass of BaseModel to accept typed inputs instead of variadic arguments in forward', 'summarize_Basemodel': 'summarize the BaseModel class and its abstract forward method and parameter counting __str__ override'}
```

## File: facebookresearch_egovlpv2/QFVS/base/base_trainer.py

Prompts

```
['create a BaseDataLoader with a dataset, batch size, shuffle flag, validation split ratio, and num workers', 'split a BaseDataLoader into a separate validation DataLoader using the split_validation method', 'create a BaseDataLoaderExplicitSplit for datasets where train and validation splits are handled externally', 'create a DistBaseDataLoaderExplicitSplit using DistributedSampler for multi-GPU distributed training with pin memory enabled', 'create a BaseMultiDataLoader that round-robins across multiple dataloaders and undersamples to the smallest one', 'create a TextVideoDataset subclass that loads video-text pairs with configurable frame sampling and transforms', 'sample frame indices from a video using random, uniform, or fixed start strategies', 'read and decode video frames using Decord for efficient batch loading with frame sampling', 'read video frames using OpenCV with configurable frame sampling and tensor conversion', 'get the total frame count of a video file using OpenCV VideoCapture', 'create a subclass of BaseModel that implements the abstract forward method for a custom PyTorch model', 'review the BaseModel forward abstract method to understand the required interface for subclasses', 'test the BaseModel __str__ method to verify it prints trainable parameter counts correctly', 'refactor a subclass of BaseModel to accept typed inputs instead of variadic arguments in forward', 'summarize the BaseModel class and its abstract forward method and parameter counting __str__ override', 'build a python module subclassing BaseTrainer to train a PyTorch model with GPU support and checkpointing', 'run the BaseTrainer train method to execute full training loop with early stopping and metric monitoring', 'create a subclass of BaseTrainer implementing _train_epoch and _valid_epoch abstract methods for custom training logic', 'build a python module subclassing Multi_BaseTrainer_dist for distributed training with DDP and GradScaler support', 'resume training from a saved checkpoint using BaseTrainer _resume_checkpoint with automatic DataParallel key handling']
```

Usage

```
{'build_BaseTrainer_subclass': 'build a python module subclassing BaseTrainer to train a PyTorch model with GPU support and checkpointing', 'run_BaseTrainer_train': 'run the BaseTrainer train method to execute full training loop with early stopping and metric monitoring', 'create_BaseTrainer_subclass': 'create a subclass of BaseTrainer implementing _train_epoch and _valid_epoch abstract methods for custom training logic', 'build_Multi_BaseTrainer_dist_subclass': 'build a python module subclassing Multi_BaseTrainer_dist for distributed training with DDP and GradScaler support', 'resume_BaseTrainer_checkpoint': 'resume training from a saved checkpoint using BaseTrainer _resume_checkpoint with automatic DataParallel key handling'}
```

