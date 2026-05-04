# Agent Python Tools

- repo: google-deepmind/detcon
- repo_uri: https://github.com/google-deepmind/detcon

## File: google-deepmind_detcon/datasets/dataset_adapter.py

Prompts

```
['create a subclass of DatasetAdapter implementing num_examples, num_classes, _load, and preprocessing methods', 'load batches from a dataset split using the load method with a specified DatasetMode and batch dimensions', 'preprocess images for pretraining by generating two augmented views with random crops and segmentations', 'preprocess images for evaluation by generating a single center crop with labels', 'transpose a JAX batch from HWCN to NHWC format for TPU training using maybe_transpose_on_device', 'create an ImageDataset instance to load and preprocess ImageNet2012 data with TFDS or file handlers', 'normalize a batch of images using ImageNet mean and standard deviation color statistics', 'compute shard start and end indices for distributed dataset loading across multiple processes', 'get the number of examples for a given train, validation, or test split of the dataset', 'load a specific split of the ImageNet dataset using TFDS or a custom file handler', 'load an ImageNet dataset with Felzenszwalb-Huttenlocher segmentations from TFRecord shards for training or testing', 'parse a single ImageNet TFRecord example into image, label, and Felzenszwalb segmentation tensors', 'check that a dataset directory contains at least 2048 ImageNet training TFRecord shard files', 'load the ImageNet training split by sharding 2048 TFRecord files across multiple workers', 'load the ImageNet validation split by globbing all 256 validation TFRecord shard files']
```

Usage

```
{'create_dataset_adapter_subclass': 'create a subclass of DatasetAdapter implementing num_examples, num_classes, _load, and preprocessing methods', 'load_dataset_batches': 'load batches from a dataset split using the load method with a specified DatasetMode and batch dimensions', 'preprocess_images_for_pretrain': 'preprocess images for pretraining by generating two augmented views with random crops and segmentations', 'preprocess_images_for_eval': 'preprocess images for evaluation by generating a single center crop with labels', 'transpose_batch_for_tpu': 'transpose a JAX batch from HWCN to NHWC format for TPU training using maybe_transpose_on_device'}
```

## File: google-deepmind_detcon/datasets/image_dataset.py

Prompts

```
['create a subclass of DatasetAdapter implementing num_examples, num_classes, _load, and preprocessing methods', 'load batches from a dataset split using the load method with a specified DatasetMode and batch dimensions', 'preprocess images for pretraining by generating two augmented views with random crops and segmentations', 'preprocess images for evaluation by generating a single center crop with labels', 'transpose a JAX batch from HWCN to NHWC format for TPU training using maybe_transpose_on_device', 'create an ImageDataset instance to load and preprocess ImageNet2012 data with TFDS or file handlers', 'normalize a batch of images using ImageNet mean and standard deviation color statistics', 'compute shard start and end indices for distributed dataset loading across multiple processes', 'get the number of examples for a given train, validation, or test split of the dataset', 'load a specific split of the ImageNet dataset using TFDS or a custom file handler', 'load an ImageNet dataset with Felzenszwalb-Huttenlocher segmentations from TFRecord shards for training or testing', 'parse a single ImageNet TFRecord example into image, label, and Felzenszwalb segmentation tensors', 'check that a dataset directory contains at least 2048 ImageNet training TFRecord shard files', 'load the ImageNet training split by sharding 2048 TFRecord files across multiple workers', 'load the ImageNet validation split by globbing all 256 validation TFRecord shard files']
```

Usage

```
{'create_imagenet_dataset': 'create an ImageDataset instance to load and preprocess ImageNet2012 data with TFDS or file handlers', 'normalize_images': 'normalize a batch of images using ImageNet mean and standard deviation color statistics', 'shard_dataset_split': 'compute shard start and end indices for distributed dataset loading across multiple processes', 'get_num_examples': 'get the number of examples for a given train, validation, or test split of the dataset', 'load_dataset_split': 'load a specific split of the ImageNet dataset using TFDS or a custom file handler'}
```

## File: google-deepmind_detcon/datasets/imagenet_with_fh.py

Prompts

```
['create a subclass of DatasetAdapter implementing num_examples, num_classes, _load, and preprocessing methods', 'load batches from a dataset split using the load method with a specified DatasetMode and batch dimensions', 'preprocess images for pretraining by generating two augmented views with random crops and segmentations', 'preprocess images for evaluation by generating a single center crop with labels', 'transpose a JAX batch from HWCN to NHWC format for TPU training using maybe_transpose_on_device', 'create an ImageDataset instance to load and preprocess ImageNet2012 data with TFDS or file handlers', 'normalize a batch of images using ImageNet mean and standard deviation color statistics', 'compute shard start and end indices for distributed dataset loading across multiple processes', 'get the number of examples for a given train, validation, or test split of the dataset', 'load a specific split of the ImageNet dataset using TFDS or a custom file handler', 'load an ImageNet dataset with Felzenszwalb-Huttenlocher segmentations from TFRecord shards for training or testing', 'parse a single ImageNet TFRecord example into image, label, and Felzenszwalb segmentation tensors', 'check that a dataset directory contains at least 2048 ImageNet training TFRecord shard files', 'load the ImageNet training split by sharding 2048 TFRecord files across multiple workers', 'load the ImageNet validation split by globbing all 256 validation TFRecord shard files']
```

Usage

```
{'load_imagenet_fh_dataset': 'load an ImageNet dataset with Felzenszwalb-Huttenlocher segmentations from TFRecord shards for training or testing', 'parse_imagenet_example_proto': 'parse a single ImageNet TFRecord example into image, label, and Felzenszwalb segmentation tensors', 'check_train_dataset_directory': 'check that a dataset directory contains at least 2048 ImageNet training TFRecord shard files', 'load_dataset_train_split': 'load the ImageNet training split by sharding 2048 TFRecord files across multiple workers', 'load_dataset_test_split': 'load the ImageNet validation split by globbing all 256 validation TFRecord shard files'}
```

