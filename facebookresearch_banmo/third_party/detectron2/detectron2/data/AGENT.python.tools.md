# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/benchmark.py

Prompts

```
['benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark the dataloader across distributed GPU workers and log per-GPU results', 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the registered dataset annotations by calling the function associated with a dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed', 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object from a list of bounding box and segmentation annotations', 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter out empty instances with zero-area boxes or empty masks from an Instances object']
```

Usage

```
{'benchmark_iterator': 'benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark_dataset_speed': 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark_mapper_speed': 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark_dataloader_workers': 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark_distributed_dataloader': 'benchmark the dataloader across distributed GPU workers and log per-GPU results'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/build.py

Prompts

```
['benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark the dataloader across distributed GPU workers and log per-GPU results', 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the registered dataset annotations by calling the function associated with a dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed', 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object from a list of bounding box and segmentation annotations', 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter out empty instances with zero-area boxes or empty masks from an Instances object']
```

Usage

```
{'build_detection_train_loader': 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build_detection_test_loader': 'build a dataloader for object detection inference with default batch size of one', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load_proposals_into_dataset': 'load precomputed object proposals from a pickle file into the dataset dicts', 'print_instances_class_histogram': 'print a histogram showing the distribution of instances across all categories'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/catalog.py

Prompts

```
['benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark the dataloader across distributed GPU workers and log per-GPU results', 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the registered dataset annotations by calling the function associated with a dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed', 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object from a list of bounding box and segmentation annotations', 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter out empty instances with zero-area boxes or empty masks from an Instances object']
```

Usage

```
{'register_dataset': 'register a dataset by name with a callable function that returns a list of dicts', 'get_dataset': 'get the registered dataset annotations by calling the function associated with a dataset name', 'list_datasets': 'list all registered dataset names in the DatasetCatalog singleton', 'get_metadata': 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set_metadata': 'set multiple metadata attributes on a dataset using keyword arguments via the set method'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/dataset_mapper.py

Prompts

```
['benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark the dataloader across distributed GPU workers and log per-GPU results', 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the registered dataset annotations by calling the function associated with a dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed', 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object from a list of bounding box and segmentation annotations', 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter out empty instances with zero-area boxes or empty masks from an Instances object']
```

Usage

```
{'create_DatasetMapper_for_training': 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create_DatasetMapper_for_inference': 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build_DatasetMapper_from_config': 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review_DatasetMapper_call_method': 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor_DatasetMapper_transform_annotations': 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/detection_utils.py

Prompts

```
['benchmark a python iterator for N iterations with warmup and max time seconds', 'benchmark the speed of taking raw samples from a detectron2 dataset', 'benchmark the speed of mapping raw dataset samples in a single process', 'benchmark the dataloader by tuning num_workers to different candidate values', 'benchmark the dataloader across distributed GPU workers and log per-GPU results', 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation with optional filtering and proposals', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the registered dataset annotations by calling the function associated with a dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'create a DatasetMapper instance with augmentations and image format for training detection models', 'create a DatasetMapper instance with is_train false to map dataset dicts for inference', 'build a DatasetMapper from a Detectron2 config object using the from_config class method', 'review the DatasetMapper call method that reads images, applies transforms, and converts to tensors', 'refactor the DatasetMapper _transform_annotations method to customize how instance masks and keypoints are processed', 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object from a list of bounding box and segmentation annotations', 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter out empty instances with zero-area boxes or empty masks from an Instances object']
```

Usage

```
{'read_image': 'read an image file into a numpy array in BGR or RGB format with exif orientation applied', 'convert_image_to_rgb': 'convert a BGR or YUV numpy image array to RGB format for model input', 'annotations_to_instances': 'create an Instances object from a list of bounding box and segmentation annotations', 'build_augmentation': 'build a list of resize and flip augmentations from a Detectron2 config for training or testing', 'filter_empty_instances': 'filter out empty instances with zero-area boxes or empty masks from an Instances object'}
```

