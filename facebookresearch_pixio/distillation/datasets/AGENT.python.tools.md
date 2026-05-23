# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/distillation/datasets/imagenet.py

Prompts

```
['build a python module to create an ImageNet training data loader using webdataset from tar files', 'create a webdataset pipeline that shuffles, decodes, and transforms ImageNet images for training', 'test the make_imagenet_loader function by passing args with data_path, batch_size, and num_workers', 'refactor the make_imagenet_loader function to support configurable normalization values and crop parameters', 'review the make_sample inner function that converts jpg samples to RGB tensors with augmentation', 'create a WebDataset instance from tar shards with configurable resolution, crop scale, and normalization parameters', 'set the epoch on a WebDataset to shuffle shard order using a random seed', 'iterate over a WebDataset to yield transformed RGB images from tar archives with optional filtering', 'build a PyTorch DataLoader from a WebDataset with configurable batch size and num workers', 'filter images in WebDataset by histogram score threshold, image resolution, or soft sampling hardness']
```

Usage

```
{'build_imagenet_loader': 'build a python module to create an ImageNet training data loader using webdataset from tar files', 'create_webdataset_pipeline': 'create a webdataset pipeline that shuffles, decodes, and transforms ImageNet images for training', 'test_make_imagenet_loader': 'test the make_imagenet_loader function by passing args with data_path, batch_size, and num_workers', 'refactor_transform_train': 'refactor the make_imagenet_loader function to support configurable normalization values and crop parameters', 'review_make_sample': 'review the make_sample inner function that converts jpg samples to RGB tensors with augmentation'}
```

## File: facebookresearch_pixio/distillation/datasets/webdataset.py

Prompts

```
['build a python module to create an ImageNet training data loader using webdataset from tar files', 'create a webdataset pipeline that shuffles, decodes, and transforms ImageNet images for training', 'test the make_imagenet_loader function by passing args with data_path, batch_size, and num_workers', 'refactor the make_imagenet_loader function to support configurable normalization values and crop parameters', 'review the make_sample inner function that converts jpg samples to RGB tensors with augmentation', 'create a WebDataset instance from tar shards with configurable resolution, crop scale, and normalization parameters', 'set the epoch on a WebDataset to shuffle shard order using a random seed', 'iterate over a WebDataset to yield transformed RGB images from tar archives with optional filtering', 'build a PyTorch DataLoader from a WebDataset with configurable batch size and num workers', 'filter images in WebDataset by histogram score threshold, image resolution, or soft sampling hardness']
```

Usage

```
{'create_webdataset_instance': 'create a WebDataset instance from tar shards with configurable resolution, crop scale, and normalization parameters', 'set_epoch_shuffle_shards': 'set the epoch on a WebDataset to shuffle shard order using a random seed', 'iterate_webdataset_images': 'iterate over a WebDataset to yield transformed RGB images from tar archives with optional filtering', 'build_webdata_loader': 'build a PyTorch DataLoader from a WebDataset with configurable batch size and num workers', 'filter_images_by_histogram': 'filter images in WebDataset by histogram score threshold, image resolution, or soft sampling hardness'}
```

