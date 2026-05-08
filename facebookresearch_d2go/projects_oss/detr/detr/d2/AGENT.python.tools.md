# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/projects_oss/detr/detr/d2/config.py

Prompts

```
['add DETR model configuration to a d2go CfgNode with default loss, transformer, and solver settings', 'review the add_detr_config function to understand default DETR loss weights and transformer hyperparameters', 'refactor add_detr_config to add a new config option for custom position encoding', 'summarize the add_detr_config function and list all DETR config fields it registers', 'test that add_detr_config correctly sets NUM_OBJECT_QUERIES to 100 on a fresh CfgNode', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with config and is_train flag to map dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and convert images and annotations to tensors', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation pipeline for training augmentations', 'build a DETR object detection model from a Detectron2 config with HungarianMatcher and SetCriterion', 'run the Detr forward pass on batched inputs to compute training losses or inference results', 'create object detection predictions by running inference on box classification and box regression outputs', 'refactor the Detr preprocess_image method to normalize, pad, and batch input images into an ImageList', 'review the Detr prepare_targets method that converts ground truth instances to normalized label and box tensors']
```

Usage

```
{'add_detr_config': 'add DETR model configuration to a d2go CfgNode with default loss, transformer, and solver settings', 'review_add_detr_config': 'review the add_detr_config function to understand default DETR loss weights and transformer hyperparameters', 'refactor_add_detr_config': 'refactor add_detr_config to add a new config option for custom position encoding', 'summarize_add_detr_config': 'summarize the add_detr_config function and list all DETR config fields it registers', 'test_add_detr_config': 'test that add_detr_config correctly sets NUM_OBJECT_QUERIES to 100 on a fresh CfgNode'}
```

## File: facebookresearch_d2go/projects_oss/detr/detr/d2/dataset_mapper.py

Prompts

```
['add DETR model configuration to a d2go CfgNode with default loss, transformer, and solver settings', 'review the add_detr_config function to understand default DETR loss weights and transformer hyperparameters', 'refactor add_detr_config to add a new config option for custom position encoding', 'summarize the add_detr_config function and list all DETR config fields it registers', 'test that add_detr_config correctly sets NUM_OBJECT_QUERIES to 100 on a fresh CfgNode', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with config and is_train flag to map dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and convert images and annotations to tensors', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation pipeline for training augmentations', 'build a DETR object detection model from a Detectron2 config with HungarianMatcher and SetCriterion', 'run the Detr forward pass on batched inputs to compute training losses or inference results', 'create object detection predictions by running inference on box classification and box regression outputs', 'refactor the Detr preprocess_image method to normalize, pad, and batch input images into an ImageList', 'review the Detr prepare_targets method that converts ground truth instances to normalized label and box tensors']
```

Usage

```
{'build_transform_gen': 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create_DetrDatasetMapper': 'create a DetrDatasetMapper instance with config and is_train flag to map dataset dicts for DETR', 'call_DetrDatasetMapper': 'call the DetrDatasetMapper on a dataset dict to read, transform, and convert images and annotations to tensors', 'review_DetrDatasetMapper_call': 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor_DetrDatasetMapper_crop': 'refactor the DetrDatasetMapper to customize the random crop generation pipeline for training augmentations'}
```

## File: facebookresearch_d2go/projects_oss/detr/detr/d2/detr.py

Prompts

```
['add DETR model configuration to a d2go CfgNode with default loss, transformer, and solver settings', 'review the add_detr_config function to understand default DETR loss weights and transformer hyperparameters', 'refactor add_detr_config to add a new config option for custom position encoding', 'summarize the add_detr_config function and list all DETR config fields it registers', 'test that add_detr_config correctly sets NUM_OBJECT_QUERIES to 100 on a fresh CfgNode', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with config and is_train flag to map dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and convert images and annotations to tensors', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation pipeline for training augmentations', 'build a DETR object detection model from a Detectron2 config with HungarianMatcher and SetCriterion', 'run the Detr forward pass on batched inputs to compute training losses or inference results', 'create object detection predictions by running inference on box classification and box regression outputs', 'refactor the Detr preprocess_image method to normalize, pad, and batch input images into an ImageList', 'review the Detr prepare_targets method that converts ground truth instances to normalized label and box tensors']
```

Usage

```
{'build_detr_model': 'build a DETR object detection model from a Detectron2 config with HungarianMatcher and SetCriterion', 'run_detr_forward': 'run the Detr forward pass on batched inputs to compute training losses or inference results', 'create_detr_inference': 'create object detection predictions by running inference on box classification and box regression outputs', 'refactor_detr_preprocess': 'refactor the Detr preprocess_image method to normalize, pad, and batch input images into an ImageList', 'review_detr_prepare_targets': 'review the Detr prepare_targets method that converts ground truth instances to normalized label and box tensors'}
```

