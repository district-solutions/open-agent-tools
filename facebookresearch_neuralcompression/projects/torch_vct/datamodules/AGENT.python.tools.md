# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/torch_vct/datamodules/kinetics.py

Prompts

```
['create a KineticsDataModule instance with a data directory, batch sizes, and clip duration for video data loading', 'setup the KineticsDataModule to initialize train and validation datasets with clip samplers and transforms', 'build a train dataloader from the KineticsDataModule with custom collation and video augmentation transforms', 'build a validation dataloader from the KineticsDataModule with center crop transforms and custom collation', 'review the _video_transform method to understand temporal subsampling, scaling, normalization, and augmentation pipeline', 'create a UVGDataModule instance to load the UVG evaluation dataset with configurable frame count and normalization', 'test the UVGDataModule by calling test_dataloader to get a PyTorch DataLoader for evaluation', 'build a custom collate function that transforms batched image tensors into a VideoDataset format', 'review the UVGDataModule _transforms method that converts images to tensors with optional normalization', 'run the UVG evaluation dataset datamodule with 13 videos of 300 frames each at 1080p resolution', 'create a random VideoDataset with specified batch size, frames, height, and width using make_random_video', 'validate a VideoDataset tensor has the expected shape of [B, T, 3, H, W] using validate_shape', 'get the batch size, number of frames, and spatial shape from a VideoDataset using its properties', 'validate a Scenes tensor is float32 with 5 dimensions using the validate_shapes method', 'iterate over scenes in a Scenes tensor and return individual scene batches using get_scenes_iter', 'create a VimeoDataModule instance to load Vimeo90k septuplet video data for training', 'build a video transform pipeline with random crop and horizontal flip augmentations for training', 'setup the VimeoDataModule to initialize train and validation datasets from the Vimeo90k dataset', 'run the train dataloater to yield shuffled batches of Vimeo90k video septuplets for training', 'review the custom collate function that wraps default collated batches into a VimeoDataset object']
```

Usage

```
{'create_KineticsDataModule': 'create a KineticsDataModule instance with a data directory, batch sizes, and clip duration for video data loading', 'setup_KineticsDataModule': 'setup the KineticsDataModule to initialize train and validation datasets with clip samplers and transforms', 'build_train_dataloader': 'build a train dataloader from the KineticsDataModule with custom collation and video augmentation transforms', 'build_val_dataloader': 'build a validation dataloader from the KineticsDataModule with center crop transforms and custom collation', 'review_video_transform': 'review the _video_transform method to understand temporal subsampling, scaling, normalization, and augmentation pipeline'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/datamodules/uvg.py

Prompts

```
['create a KineticsDataModule instance with a data directory, batch sizes, and clip duration for video data loading', 'setup the KineticsDataModule to initialize train and validation datasets with clip samplers and transforms', 'build a train dataloader from the KineticsDataModule with custom collation and video augmentation transforms', 'build a validation dataloader from the KineticsDataModule with center crop transforms and custom collation', 'review the _video_transform method to understand temporal subsampling, scaling, normalization, and augmentation pipeline', 'create a UVGDataModule instance to load the UVG evaluation dataset with configurable frame count and normalization', 'test the UVGDataModule by calling test_dataloader to get a PyTorch DataLoader for evaluation', 'build a custom collate function that transforms batched image tensors into a VideoDataset format', 'review the UVGDataModule _transforms method that converts images to tensors with optional normalization', 'run the UVG evaluation dataset datamodule with 13 videos of 300 frames each at 1080p resolution', 'create a random VideoDataset with specified batch size, frames, height, and width using make_random_video', 'validate a VideoDataset tensor has the expected shape of [B, T, 3, H, W] using validate_shape', 'get the batch size, number of frames, and spatial shape from a VideoDataset using its properties', 'validate a Scenes tensor is float32 with 5 dimensions using the validate_shapes method', 'iterate over scenes in a Scenes tensor and return individual scene batches using get_scenes_iter', 'create a VimeoDataModule instance to load Vimeo90k septuplet video data for training', 'build a video transform pipeline with random crop and horizontal flip augmentations for training', 'setup the VimeoDataModule to initialize train and validation datasets from the Vimeo90k dataset', 'run the train dataloater to yield shuffled batches of Vimeo90k video septuplets for training', 'review the custom collate function that wraps default collated batches into a VimeoDataset object']
```

Usage

```
{'create_UVGDataModule': 'create a UVGDataModule instance to load the UVG evaluation dataset with configurable frame count and normalization', 'test_UVGDataModule_dataloader': 'test the UVGDataModule by calling test_dataloader to get a PyTorch DataLoader for evaluation', 'build_UVGDataModule_custom_collate': 'build a custom collate function that transforms batched image tensors into a VideoDataset format', 'review_UVGDataModule_transforms': 'review the UVGDataModule _transforms method that converts images to tensors with optional normalization', 'run_UVGDataModule_evaluation': 'run the UVG evaluation dataset datamodule with 13 videos of 300 frames each at 1080p resolution'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/datamodules/video_data_api.py

Prompts

```
['create a KineticsDataModule instance with a data directory, batch sizes, and clip duration for video data loading', 'setup the KineticsDataModule to initialize train and validation datasets with clip samplers and transforms', 'build a train dataloader from the KineticsDataModule with custom collation and video augmentation transforms', 'build a validation dataloader from the KineticsDataModule with center crop transforms and custom collation', 'review the _video_transform method to understand temporal subsampling, scaling, normalization, and augmentation pipeline', 'create a UVGDataModule instance to load the UVG evaluation dataset with configurable frame count and normalization', 'test the UVGDataModule by calling test_dataloader to get a PyTorch DataLoader for evaluation', 'build a custom collate function that transforms batched image tensors into a VideoDataset format', 'review the UVGDataModule _transforms method that converts images to tensors with optional normalization', 'run the UVG evaluation dataset datamodule with 13 videos of 300 frames each at 1080p resolution', 'create a random VideoDataset with specified batch size, frames, height, and width using make_random_video', 'validate a VideoDataset tensor has the expected shape of [B, T, 3, H, W] using validate_shape', 'get the batch size, number of frames, and spatial shape from a VideoDataset using its properties', 'validate a Scenes tensor is float32 with 5 dimensions using the validate_shapes method', 'iterate over scenes in a Scenes tensor and return individual scene batches using get_scenes_iter', 'create a VimeoDataModule instance to load Vimeo90k septuplet video data for training', 'build a video transform pipeline with random crop and horizontal flip augmentations for training', 'setup the VimeoDataModule to initialize train and validation datasets from the Vimeo90k dataset', 'run the train dataloater to yield shuffled batches of Vimeo90k video septuplets for training', 'review the custom collate function that wraps default collated batches into a VimeoDataset object']
```

Usage

```
{'create_random_video_dataset': 'create a random VideoDataset with specified batch size, frames, height, and width using make_random_video', 'validate_video_dataset_shape': 'validate a VideoDataset tensor has the expected shape of [B, T, 3, H, W] using validate_shape', 'get_video_dataset_properties': 'get the batch size, number of frames, and spatial shape from a VideoDataset using its properties', 'validate_scenes_tensor': 'validate a Scenes tensor is float32 with 5 dimensions using the validate_shapes method', 'iterate_scenes_latents': 'iterate over scenes in a Scenes tensor and return individual scene batches using get_scenes_iter'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/datamodules/vimeo.py

Prompts

```
['create a KineticsDataModule instance with a data directory, batch sizes, and clip duration for video data loading', 'setup the KineticsDataModule to initialize train and validation datasets with clip samplers and transforms', 'build a train dataloader from the KineticsDataModule with custom collation and video augmentation transforms', 'build a validation dataloader from the KineticsDataModule with center crop transforms and custom collation', 'review the _video_transform method to understand temporal subsampling, scaling, normalization, and augmentation pipeline', 'create a UVGDataModule instance to load the UVG evaluation dataset with configurable frame count and normalization', 'test the UVGDataModule by calling test_dataloader to get a PyTorch DataLoader for evaluation', 'build a custom collate function that transforms batched image tensors into a VideoDataset format', 'review the UVGDataModule _transforms method that converts images to tensors with optional normalization', 'run the UVG evaluation dataset datamodule with 13 videos of 300 frames each at 1080p resolution', 'create a random VideoDataset with specified batch size, frames, height, and width using make_random_video', 'validate a VideoDataset tensor has the expected shape of [B, T, 3, H, W] using validate_shape', 'get the batch size, number of frames, and spatial shape from a VideoDataset using its properties', 'validate a Scenes tensor is float32 with 5 dimensions using the validate_shapes method', 'iterate over scenes in a Scenes tensor and return individual scene batches using get_scenes_iter', 'create a VimeoDataModule instance to load Vimeo90k septuplet video data for training', 'build a video transform pipeline with random crop and horizontal flip augmentations for training', 'setup the VimeoDataModule to initialize train and validation datasets from the Vimeo90k dataset', 'run the train dataloater to yield shuffled batches of Vimeo90k video septuplets for training', 'review the custom collate function that wraps default collated batches into a VimeoDataset object']
```

Usage

```
{'create_VimeoDataModule': 'create a VimeoDataModule instance to load Vimeo90k septuplet video data for training', 'build_VideoTransform': 'build a video transform pipeline with random crop and horizontal flip augmentations for training', 'setup_VimeoDataModule': 'setup the VimeoDataModule to initialize train and validation datasets from the Vimeo90k dataset', 'run_train_dataloader': 'run the train dataloater to yield shuffled batches of Vimeo90k video septuplets for training', 'review_custom_collate': 'review the custom collate function that wraps default collated batches into a VimeoDataset object'}
```

