# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/pretraining/datasets/imagenet.py

Prompts

```
['build a WebDataset-based ImageNet training data loader with random crop and normalization transforms', 'create a dataloader from tar files using webdataset with shuffling and batching for ImageNet training', 'test the make_imagenet_loader function to verify it returns a valid WebLoader from tar shards', 'refactor the make_sample inner function to support additional image formats beyond jpg', 'review the transform_train pipeline to check RandomResizedCrop and Normalize parameters for ImageNet', 'create a WebDataset instance from tar shards with image transforms and optional JSON metadata filtering', 'create a PyTorch DataLoader for WebDataset with configurable batch size and num workers', 'shuffle WebDataset shard order by calling set_epoch with an epoch seed value', 'filter images by histogram score threshold using hist_thresh parameter in WebDataset', 'apply soft sampling to skip images based on mae_loss hardness values in JSON metadata']
```

Usage

```
{'build_imagenet_loader': 'build a WebDataset-based ImageNet training data loader with random crop and normalization transforms', 'create_imagenet_dataloader': 'create a dataloader from tar files using webdataset with shuffling and batching for ImageNet training', 'test_make_imagenet_loader': 'test the make_imagenet_loader function to verify it returns a valid WebLoader from tar shards', 'refactor_make_sample': 'refactor the make_sample inner function to support additional image formats beyond jpg', 'review_transform_train': 'review the transform_train pipeline to check RandomResizedCrop and Normalize parameters for ImageNet'}
```

## File: facebookresearch_pixio/pretraining/datasets/webdataset.py

Prompts

```
['build a WebDataset-based ImageNet training data loader with random crop and normalization transforms', 'create a dataloader from tar files using webdataset with shuffling and batching for ImageNet training', 'test the make_imagenet_loader function to verify it returns a valid WebLoader from tar shards', 'refactor the make_sample inner function to support additional image formats beyond jpg', 'review the transform_train pipeline to check RandomResizedCrop and Normalize parameters for ImageNet', 'create a WebDataset instance from tar shards with image transforms and optional JSON metadata filtering', 'create a PyTorch DataLoader for WebDataset with configurable batch size and num workers', 'shuffle WebDataset shard order by calling set_epoch with an epoch seed value', 'filter images by histogram score threshold using hist_thresh parameter in WebDataset', 'apply soft sampling to skip images based on mae_loss hardness values in JSON metadata']
```

Usage

```
{'create_webdataset': 'create a WebDataset instance from tar shards with image transforms and optional JSON metadata filtering', 'create_webdata_loader': 'create a PyTorch DataLoader for WebDataset with configurable batch size and num workers', 'set_epoch_shuffle': 'shuffle WebDataset shard order by calling set_epoch with an epoch seed value', 'filter_by_histogram': 'filter images by histogram score threshold using hist_thresh parameter in WebDataset', 'soft_sampling_by_mae': 'apply soft sampling to skip images based on mae_loss hardness values in JSON metadata'}
```

