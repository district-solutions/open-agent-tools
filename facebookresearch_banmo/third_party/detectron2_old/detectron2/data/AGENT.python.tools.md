# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/build.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with batch size 1 and InferenceSampler', 'load and prepare dataset dicts for detection with optional filtering and proposal loading', 'load precomputed object proposals from a pickle file into dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the dataset annotations by calling the registered function for a given dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'build a DatasetMapper instance from a Detectron2 config object for training or inference', 'create a DatasetMapper with custom augmentations, image format, and instance mask settings', 'test the DatasetMapper callable to transform a dataset dict into model-ready tensor format', 'review the DatasetMapper class and its image reading, augmentation, and annotation transformation logic', 'refactor the DatasetMapper from_config method to support additional config options like keypoint or proposal loading', 'read an image file into a numpy array in BGR or RGB format with EXIF orientation applied', 'convert a BGR or YUV image array to RGB format for model input', 'apply geometric transforms to bounding box, segmentation, and keypoint annotations of a single instance', 'convert a list of instance annotation dicts into an Instances object with gt_boxes, gt_classes, and gt_masks', 'build a list of augmentation transforms including resize and random flip from a Detectron2 config']
```

Usage

```
{'build_detection_train_loader': 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build_detection_test_loader': 'build a dataloader for object detection inference with batch size 1 and InferenceSampler', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for detection with optional filtering and proposal loading', 'load_proposals_into_dataset': 'load precomputed object proposals from a pickle file into dataset dicts', 'print_instances_class_histogram': 'print a histogram showing the distribution of instances across all categories'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/catalog.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with batch size 1 and InferenceSampler', 'load and prepare dataset dicts for detection with optional filtering and proposal loading', 'load precomputed object proposals from a pickle file into dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the dataset annotations by calling the registered function for a given dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'build a DatasetMapper instance from a Detectron2 config object for training or inference', 'create a DatasetMapper with custom augmentations, image format, and instance mask settings', 'test the DatasetMapper callable to transform a dataset dict into model-ready tensor format', 'review the DatasetMapper class and its image reading, augmentation, and annotation transformation logic', 'refactor the DatasetMapper from_config method to support additional config options like keypoint or proposal loading', 'read an image file into a numpy array in BGR or RGB format with EXIF orientation applied', 'convert a BGR or YUV image array to RGB format for model input', 'apply geometric transforms to bounding box, segmentation, and keypoint annotations of a single instance', 'convert a list of instance annotation dicts into an Instances object with gt_boxes, gt_classes, and gt_masks', 'build a list of augmentation transforms including resize and random flip from a Detectron2 config']
```

Usage

```
{'register_dataset': 'register a dataset by name with a callable function that returns a list of dicts', 'get_dataset': 'get the dataset annotations by calling the registered function for a given dataset name', 'list_datasets': 'list all registered dataset names in the DatasetCatalog singleton', 'get_metadata': 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set_metadata': 'set multiple metadata attributes on a dataset using keyword arguments via the set method'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/dataset_mapper.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with batch size 1 and InferenceSampler', 'load and prepare dataset dicts for detection with optional filtering and proposal loading', 'load precomputed object proposals from a pickle file into dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the dataset annotations by calling the registered function for a given dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'build a DatasetMapper instance from a Detectron2 config object for training or inference', 'create a DatasetMapper with custom augmentations, image format, and instance mask settings', 'test the DatasetMapper callable to transform a dataset dict into model-ready tensor format', 'review the DatasetMapper class and its image reading, augmentation, and annotation transformation logic', 'refactor the DatasetMapper from_config method to support additional config options like keypoint or proposal loading', 'read an image file into a numpy array in BGR or RGB format with EXIF orientation applied', 'convert a BGR or YUV image array to RGB format for model input', 'apply geometric transforms to bounding box, segmentation, and keypoint annotations of a single instance', 'convert a list of instance annotation dicts into an Instances object with gt_boxes, gt_classes, and gt_masks', 'build a list of augmentation transforms including resize and random flip from a Detectron2 config']
```

Usage

```
{'build_dataset_mapper_from_config': 'build a DatasetMapper instance from a Detectron2 config object for training or inference', 'create_dataset_mapper_with_augmentations': 'create a DatasetMapper with custom augmentations, image format, and instance mask settings', 'test_dataset_mapper_call': 'test the DatasetMapper callable to transform a dataset dict into model-ready tensor format', 'review_dataset_mapper_transforms': 'review the DatasetMapper class and its image reading, augmentation, and annotation transformation logic', 'refactor_dataset_mapper_from_config': 'refactor the DatasetMapper from_config method to support additional config options like keypoint or proposal loading'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/detection_utils.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with batch size 1 and InferenceSampler', 'load and prepare dataset dicts for detection with optional filtering and proposal loading', 'load precomputed object proposals from a pickle file into dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'register a dataset by name with a callable function that returns a list of dicts', 'get the dataset annotations by calling the registered function for a given dataset name', 'list all registered dataset names in the DatasetCatalog singleton', 'get or create a Metadata singleton for a named dataset to store class names and other attributes', 'set multiple metadata attributes on a dataset using keyword arguments via the set method', 'build a DatasetMapper instance from a Detectron2 config object for training or inference', 'create a DatasetMapper with custom augmentations, image format, and instance mask settings', 'test the DatasetMapper callable to transform a dataset dict into model-ready tensor format', 'review the DatasetMapper class and its image reading, augmentation, and annotation transformation logic', 'refactor the DatasetMapper from_config method to support additional config options like keypoint or proposal loading', 'read an image file into a numpy array in BGR or RGB format with EXIF orientation applied', 'convert a BGR or YUV image array to RGB format for model input', 'apply geometric transforms to bounding box, segmentation, and keypoint annotations of a single instance', 'convert a list of instance annotation dicts into an Instances object with gt_boxes, gt_classes, and gt_masks', 'build a list of augmentation transforms including resize and random flip from a Detectron2 config']
```

Usage

```
{'read_image': 'read an image file into a numpy array in BGR or RGB format with EXIF orientation applied', 'convert_image_to_rgb': 'convert a BGR or YUV image array to RGB format for model input', 'transform_instance_annotations': 'apply geometric transforms to bounding box, segmentation, and keypoint annotations of a single instance', 'annotations_to_instances': 'convert a list of instance annotation dicts into an Instances object with gt_boxes, gt_classes, and gt_masks', 'build_augmentation': 'build a list of augmentation transforms including resize and random flip from a Detectron2 config'}
```

