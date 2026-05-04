# Agent Python Tools

- repo: google-deepmind/distributionshiftframework
- repo_uri: https://github.com/google-deepmind/distribution_shift_framework

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/datasets/data_loaders.py

Prompts

```
['load the 3D Shapes dataset with batching, shuffling, and preprocessing for training or evaluation', 'load the small NORB dataset with configurable batch sizes and preprocessing for image classification', 'load the dsprites dataset with batching, shuffling, and preprocessing for shape classification tasks', 'apply batching, shuffling, caching, and prefetching post-processing to a TensorFlow dataset', 'preprocess 3D Shapes dataset examples by converting images to float32 and extracting shape labels', 'get dataset constants like properties, num_channels, num_classes, variance, and image_size for a named dataset', 'check if a dataset name is one of the supported disentanglement datasets like shapes3d or dsprites', 'load a dataset using a config loader and return a generator of batched numpy arrays', 'transpose a batch dictionary image tensor from NHWC to NCHW layout for TPU performance', 'resize a batch of images to a target height and width using bilinear interpolation with JAX', 'create a filter function from a string like label_scale:3:equal to filter dataset samples', 'load a low data version of a tfds dataset with specified sample counts and filters', 'filter a disentanglement dataset by attribute comparisons using key:value:operator syntax with AND and OR logic', 'sample from multiple filtered datasets with equal or weighted probability using sample_from_datasets', 'batch dataset examples into nested shapes and transpose NHWC to HWCN for TPU performance']
```

Usage

```
{'load_shapes3d_dataset': 'load the 3D Shapes dataset with batching, shuffling, and preprocessing for training or evaluation', 'load_small_norb_dataset': 'load the small NORB dataset with configurable batch sizes and preprocessing for image classification', 'load_dsprites_dataset': 'load the dsprites dataset with batching, shuffling, and preprocessing for shape classification tasks', 'batch_and_shuffle_dataset': 'apply batching, shuffling, caching, and prefetching post-processing to a TensorFlow dataset', 'preprocess_shapes3d_examples': 'preprocess 3D Shapes dataset examples by converting images to float32 and extracting shape labels'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/datasets/data_utils.py

Prompts

```
['load the 3D Shapes dataset with batching, shuffling, and preprocessing for training or evaluation', 'load the small NORB dataset with configurable batch sizes and preprocessing for image classification', 'load the dsprites dataset with batching, shuffling, and preprocessing for shape classification tasks', 'apply batching, shuffling, caching, and prefetching post-processing to a TensorFlow dataset', 'preprocess 3D Shapes dataset examples by converting images to float32 and extracting shape labels', 'get dataset constants like properties, num_channels, num_classes, variance, and image_size for a named dataset', 'check if a dataset name is one of the supported disentanglement datasets like shapes3d or dsprites', 'load a dataset using a config loader and return a generator of batched numpy arrays', 'transpose a batch dictionary image tensor from NHWC to NCHW layout for TPU performance', 'resize a batch of images to a target height and width using bilinear interpolation with JAX', 'create a filter function from a string like label_scale:3:equal to filter dataset samples', 'load a low data version of a tfds dataset with specified sample counts and filters', 'filter a disentanglement dataset by attribute comparisons using key:value:operator syntax with AND and OR logic', 'sample from multiple filtered datasets with equal or weighted probability using sample_from_datasets', 'batch dataset examples into nested shapes and transpose NHWC to HWCN for TPU performance']
```

Usage

```
{'get_dataset_constants': 'get dataset constants like properties, num_channels, num_classes, variance, and image_size for a named dataset', 'is_disentanglement_dataset': 'check if a dataset name is one of the supported disentanglement datasets like shapes3d or dsprites', 'load_dataset': 'load a dataset using a config loader and return a generator of batched numpy arrays', 'transpose_fn': 'transpose a batch dictionary image tensor from NHWC to NCHW layout for TPU performance', 'resize': 'resize a batch of images to a target height and width using bilinear interpolation with JAX'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/datasets/lowdata_wrapper.py

Prompts

```
['load the 3D Shapes dataset with batching, shuffling, and preprocessing for training or evaluation', 'load the small NORB dataset with configurable batch sizes and preprocessing for image classification', 'load the dsprites dataset with batching, shuffling, and preprocessing for shape classification tasks', 'apply batching, shuffling, caching, and prefetching post-processing to a TensorFlow dataset', 'preprocess 3D Shapes dataset examples by converting images to float32 and extracting shape labels', 'get dataset constants like properties, num_channels, num_classes, variance, and image_size for a named dataset', 'check if a dataset name is one of the supported disentanglement datasets like shapes3d or dsprites', 'load a dataset using a config loader and return a generator of batched numpy arrays', 'transpose a batch dictionary image tensor from NHWC to NCHW layout for TPU performance', 'resize a batch of images to a target height and width using bilinear interpolation with JAX', 'create a filter function from a string like label_scale:3:equal to filter dataset samples', 'load a low data version of a tfds dataset with specified sample counts and filters', 'filter a disentanglement dataset by attribute comparisons using key:value:operator syntax with AND and OR logic', 'sample from multiple filtered datasets with equal or weighted probability using sample_from_datasets', 'batch dataset examples into nested shapes and transpose NHWC to HWCN for TPU performance']
```

Usage

```
{'create_filter_fn': 'create a filter function from a string like label_scale:3:equal to filter dataset samples', 'load_data_lowdata': 'load a low data version of a tfds dataset with specified sample counts and filters', 'filter_dataset_by_attributes': 'filter a disentanglement dataset by attribute comparisons using key:value:operator syntax with AND and OR logic', 'sample_from_datasets': 'sample from multiple filtered datasets with equal or weighted probability using sample_from_datasets', 'batch_and_transpose': 'batch dataset examples into nested shapes and transpose NHWC to HWCN for TPU performance'}
```

