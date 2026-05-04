# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/data/build.py

Prompts

```
['build a python module to create a DensePose training data loader from a Detectron2 config node', 'build a python module to create a DensePose test data loader for a given dataset name', 'create a function that loads and merges dataset dicts from multiple datasets with category mapping and filtering', 'build a python module to create a DensePose data sampler with uniform or confidence-based sampling strategies', 'build a python module to construct a data loader from model inference results with configurable sampling and filtering', 'build a DatasetMapper instance with a Detectron2 config to map dataset dicts for DensePose training', 'build an augmentation list with random rotation for DensePose training using a Detectron2 config', 'run the DatasetMapper on a dataset dict to transform images and DensePose annotations for model input', 'review the DatasetMapper _transform_densepose method to understand how DensePose annotations are validated and transformed', 'review the DatasetMapper _add_densepose_masks_as_segmentation method to understand how DensePose masks are converted to segmentation bitmasks', 'check if a given file path is a relative local path without a URL scheme', 'prepend a base directory path to a relative local path when the base path is provided', 'get a dictionary mapping class IDs to mesh names from a Detectron2 config node', 'get a dictionary mapping category names to class IDs from a dataset config node', 'review the DensePose data utility functions for path handling and config mapping logic']
```

Usage

```
{'build_detection_train_loader': 'build a python module to create a DensePose training data loader from a Detectron2 config node', 'build_detection_test_loader': 'build a python module to create a DensePose test data loader for a given dataset name', 'combine_detection_dataset_dicts': 'create a function that loads and merges dataset dicts from multiple datasets with category mapping and filtering', 'build_data_sampler': 'build a python module to create a DensePose data sampler with uniform or confidence-based sampling strategies', 'build_inference_based_loader': 'build a python module to construct a data loader from model inference results with configurable sampling and filtering'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/data/dataset_mapper.py

Prompts

```
['build a python module to create a DensePose training data loader from a Detectron2 config node', 'build a python module to create a DensePose test data loader for a given dataset name', 'create a function that loads and merges dataset dicts from multiple datasets with category mapping and filtering', 'build a python module to create a DensePose data sampler with uniform or confidence-based sampling strategies', 'build a python module to construct a data loader from model inference results with configurable sampling and filtering', 'build a DatasetMapper instance with a Detectron2 config to map dataset dicts for DensePose training', 'build an augmentation list with random rotation for DensePose training using a Detectron2 config', 'run the DatasetMapper on a dataset dict to transform images and DensePose annotations for model input', 'review the DatasetMapper _transform_densepose method to understand how DensePose annotations are validated and transformed', 'review the DatasetMapper _add_densepose_masks_as_segmentation method to understand how DensePose masks are converted to segmentation bitmasks', 'check if a given file path is a relative local path without a URL scheme', 'prepend a base directory path to a relative local path when the base path is provided', 'get a dictionary mapping class IDs to mesh names from a Detectron2 config node', 'get a dictionary mapping category names to class IDs from a dataset config node', 'review the DensePose data utility functions for path handling and config mapping logic']
```

Usage

```
{'build_DatasetMapper': 'build a DatasetMapper instance with a Detectron2 config to map dataset dicts for DensePose training', 'build_build_augmentation': 'build an augmentation list with random rotation for DensePose training using a Detectron2 config', 'run_DatasetMapper_call': 'run the DatasetMapper on a dataset dict to transform images and DensePose annotations for model input', 'review_DatasetMapper_transform_densepose': 'review the DatasetMapper _transform_densepose method to understand how DensePose annotations are validated and transformed', 'review_DatasetMapper_add_masks': 'review the DatasetMapper _add_densepose_masks_as_segmentation method to understand how DensePose masks are converted to segmentation bitmasks'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/data/utils.py

Prompts

```
['build a python module to create a DensePose training data loader from a Detectron2 config node', 'build a python module to create a DensePose test data loader for a given dataset name', 'create a function that loads and merges dataset dicts from multiple datasets with category mapping and filtering', 'build a python module to create a DensePose data sampler with uniform or confidence-based sampling strategies', 'build a python module to construct a data loader from model inference results with configurable sampling and filtering', 'build a DatasetMapper instance with a Detectron2 config to map dataset dicts for DensePose training', 'build an augmentation list with random rotation for DensePose training using a Detectron2 config', 'run the DatasetMapper on a dataset dict to transform images and DensePose annotations for model input', 'review the DatasetMapper _transform_densepose method to understand how DensePose annotations are validated and transformed', 'review the DatasetMapper _add_densepose_masks_as_segmentation method to understand how DensePose masks are converted to segmentation bitmasks', 'check if a given file path is a relative local path without a URL scheme', 'prepend a base directory path to a relative local path when the base path is provided', 'get a dictionary mapping class IDs to mesh names from a Detectron2 config node', 'get a dictionary mapping category names to class IDs from a dataset config node', 'review the DensePose data utility functions for path handling and config mapping logic']
```

Usage

```
{'check_is_relative_local_path': 'check if a given file path is a relative local path without a URL scheme', 'prepend_base_path_to_relative': 'prepend a base directory path to a relative local path when the base path is provided', 'get_class_to_mesh_name_mapping': 'get a dictionary mapping class IDs to mesh names from a Detectron2 config node', 'get_category_to_class_mapping': 'get a dictionary mapping category names to class IDs from a dataset config node', 'review_utils_functions': 'review the DensePose data utility functions for path handling and config mapping logic'}
```

