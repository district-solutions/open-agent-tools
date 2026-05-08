# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/data/build.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation and semantic segmentation tasks', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'create a DatasetMapper instance with augmentations and image format for training or inference', 'build a DatasetMapper from a Detectron2 config object with augmentation and mask settings', 'run the DatasetMapper on a dataset dict to transform images and annotations into model input', 'review the DatasetMapper _transform_annotations method that converts annotations to Instances with optional box recomputation', 'refactor the DatasetMapper to customize augmentation pipelines for training or inference modes', 'read an image file into a numpy array with optional BGR or YUV format conversion', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object with gt_boxes, gt_classes, and gt_masks from annotation dicts', 'apply transforms to bounding box, segmentation polygons, and keypoints in instance annotations', 'build a list of resize and flip augmentation transforms from a detectron2 config object']
```

Usage

```
{'build_detection_train_loader': 'build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build_detection_test_loader': 'build a dataloader for object detection inference with default batch size of one', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for detection segmentation and semantic segmentation tasks', 'load_proposals_into_dataset': 'load precomputed object proposals from a pickle file into the dataset dicts', 'print_instances_class_histogram': 'print a histogram showing the distribution of instances across all categories'}
```

## File: facebookresearch_cutler/cutler/data/dataset_mapper.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation and semantic segmentation tasks', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'create a DatasetMapper instance with augmentations and image format for training or inference', 'build a DatasetMapper from a Detectron2 config object with augmentation and mask settings', 'run the DatasetMapper on a dataset dict to transform images and annotations into model input', 'review the DatasetMapper _transform_annotations method that converts annotations to Instances with optional box recomputation', 'refactor the DatasetMapper to customize augmentation pipelines for training or inference modes', 'read an image file into a numpy array with optional BGR or YUV format conversion', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object with gt_boxes, gt_classes, and gt_masks from annotation dicts', 'apply transforms to bounding box, segmentation polygons, and keypoints in instance annotations', 'build a list of resize and flip augmentation transforms from a detectron2 config object']
```

Usage

```
{'create_DatasetMapper': 'create a DatasetMapper instance with augmentations and image format for training or inference', 'build_DatasetMapper_from_config': 'build a DatasetMapper from a Detectron2 config object with augmentation and mask settings', 'run_DatasetMapper_call': 'run the DatasetMapper on a dataset dict to transform images and annotations into model input', 'review_DatasetMapper_transform_annotations': 'review the DatasetMapper _transform_annotations method that converts annotations to Instances with optional box recomputation', 'refactor_DatasetMapper_augmentations': 'refactor the DatasetMapper to customize augmentation pipelines for training or inference modes'}
```

## File: facebookresearch_cutler/cutler/data/detection_utils.py

Prompts

```
['build a dataloader for object detection training with configurable mapper, sampler, and batch size', 'build a dataloader for object detection inference with default batch size of one', 'load and prepare dataset dicts for detection segmentation and semantic segmentation tasks', 'load precomputed object proposals from a pickle file into the dataset dicts', 'print a histogram showing the distribution of instances across all categories', 'create a DatasetMapper instance with augmentations and image format for training or inference', 'build a DatasetMapper from a Detectron2 config object with augmentation and mask settings', 'run the DatasetMapper on a dataset dict to transform images and annotations into model input', 'review the DatasetMapper _transform_annotations method that converts annotations to Instances with optional box recomputation', 'refactor the DatasetMapper to customize augmentation pipelines for training or inference modes', 'read an image file into a numpy array with optional BGR or YUV format conversion', 'convert a BGR or YUV numpy image array to RGB format for model input', 'create an Instances object with gt_boxes, gt_classes, and gt_masks from annotation dicts', 'apply transforms to bounding box, segmentation polygons, and keypoints in instance annotations', 'build a list of resize and flip augmentation transforms from a detectron2 config object']
```

Usage

```
{'read_image': 'read an image file into a numpy array with optional BGR or YUV format conversion', 'convert_image_to_rgb': 'convert a BGR or YUV numpy image array to RGB format for model input', 'annotations_to_instances': 'create an Instances object with gt_boxes, gt_classes, and gt_masks from annotation dicts', 'transform_instance_annotations': 'apply transforms to bounding box, segmentation polygons, and keypoints in instance annotations', 'build_augmentation': 'build a list of resize and flip augmentation transforms from a detectron2 config object'}
```

