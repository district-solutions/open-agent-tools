# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/data/dataset_mappers/coco_instance_new_baseline_dataset_mapper.py

Prompts

```
['build a list of image augmentation transforms from a Detectron2 config for training', 'convert COCO polygon segmentations to binary mask tensors for a given image size', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format', 'map a Detectron2 dataset dict through the COCOInstanceNewBaselineDatasetMapper for training or inference', 'review the COCOInstanceNewBaselineDatasetMapper from_config class method to build mapper from Detectron2 config', 'create a COCOPanopticNewBaselineDatasetMapper instance from a Detectron2 config with training augmentations', 'process panoptic segmentation ground truth by applying transforms and converting RGB to instance masks', 'review the COCOPanopticNewBaselineDatasetMapper call method to understand image reading, transforms, and panoptic annotation handling', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method on a Detectron2 dataset dict for instance segmentation', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic supporting polygons, RLE, and numpy arrays', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different divisibility value', 'build a MaskFormerSemanticDatasetMapper instance with custom augmentations, image format, ignore label, and size divisibility settings', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config object with automatic augmentation pipeline construction', 'run the MaskFormerSemanticDatasetMapper on a dataset dict to transform it into MaskFormer semantic segmentation format', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color augment, and flip transforms', 'review how the MaskFormerSemanticDatasetMapper creates per-category binary masks and Instances objects from semantic segmentation ground truth']
```

Usage

```
{'build_transform_gen': 'build a list of image augmentation transforms from a Detectron2 config for training', 'convert_coco_poly_to_mask': 'convert COCO polygon segmentations to binary mask tensors for a given image size', 'create_dataset_mapper': 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format', 'map_dataset_dict': 'map a Detectron2 dataset dict through the COCOInstanceNewBaselineDatasetMapper for training or inference', 'review_mapper_from_config': 'review the COCOInstanceNewBaselineDatasetMapper from_config class method to build mapper from Detectron2 config'}
```

## File: facebookresearch_cutler/videocutler/mask2former/data/dataset_mappers/coco_panoptic_new_baseline_dataset_mapper.py

Prompts

```
['build a list of image augmentation transforms from a Detectron2 config for training', 'convert COCO polygon segmentations to binary mask tensors for a given image size', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format', 'map a Detectron2 dataset dict through the COCOInstanceNewBaselineDatasetMapper for training or inference', 'review the COCOInstanceNewBaselineDatasetMapper from_config class method to build mapper from Detectron2 config', 'create a COCOPanopticNewBaselineDatasetMapper instance from a Detectron2 config with training augmentations', 'process panoptic segmentation ground truth by applying transforms and converting RGB to instance masks', 'review the COCOPanopticNewBaselineDatasetMapper call method to understand image reading, transforms, and panoptic annotation handling', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method on a Detectron2 dataset dict for instance segmentation', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic supporting polygons, RLE, and numpy arrays', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different divisibility value', 'build a MaskFormerSemanticDatasetMapper instance with custom augmentations, image format, ignore label, and size divisibility settings', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config object with automatic augmentation pipeline construction', 'run the MaskFormerSemanticDatasetMapper on a dataset dict to transform it into MaskFormer semantic segmentation format', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color augment, and flip transforms', 'review how the MaskFormerSemanticDatasetMapper creates per-category binary masks and Instances objects from semantic segmentation ground truth']
```

Usage

```
{'build_transform_gen': 'build a list of Detectron2 augmentation transforms from a config for training with resize and flip', 'create_mapper_from_config': 'create a COCOPanopticNewBaselineDatasetMapper instance from a Detectron2 config with training augmentations', 'map_dataset_dict': 'map a Detectron2 dataset dict to MaskFormer format by reading images and applying geometric transforms', 'process_panoptic_segmentation': 'process panoptic segmentation ground truth by applying transforms and converting RGB to instance masks', 'review_mapper_call': 'review the COCOPanopticNewBaselineDatasetMapper call method to understand image reading, transforms, and panoptic annotation handling'}
```

## File: facebookresearch_cutler/videocutler/mask2former/data/dataset_mappers/mask_former_instance_dataset_mapper.py

Prompts

```
['build a list of image augmentation transforms from a Detectron2 config for training', 'convert COCO polygon segmentations to binary mask tensors for a given image size', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format', 'map a Detectron2 dataset dict through the COCOInstanceNewBaselineDatasetMapper for training or inference', 'review the COCOInstanceNewBaselineDatasetMapper from_config class method to build mapper from Detectron2 config', 'create a COCOPanopticNewBaselineDatasetMapper instance from a Detectron2 config with training augmentations', 'process panoptic segmentation ground truth by applying transforms and converting RGB to instance masks', 'review the COCOPanopticNewBaselineDatasetMapper call method to understand image reading, transforms, and panoptic annotation handling', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method on a Detectron2 dataset dict for instance segmentation', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic supporting polygons, RLE, and numpy arrays', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different divisibility value', 'build a MaskFormerSemanticDatasetMapper instance with custom augmentations, image format, ignore label, and size divisibility settings', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config object with automatic augmentation pipeline construction', 'run the MaskFormerSemanticDatasetMapper on a dataset dict to transform it into MaskFormer semantic segmentation format', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color augment, and flip transforms', 'review how the MaskFormerSemanticDatasetMapper creates per-category binary masks and Instances objects from semantic segmentation ground truth']
```

Usage

```
{'create_MaskFormerInstanceDatasetMapper': 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build_from_config': 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test_call_dataset_dict': 'test the MaskFormerInstanceDatasetMapper call method on a Detectron2 dataset dict for instance segmentation', 'review_mask_conversion': 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic supporting polygons, RLE, and numpy arrays', 'refactor_padding_logic': 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different divisibility value'}
```

## File: facebookresearch_cutler/videocutler/mask2former/data/dataset_mappers/mask_former_semantic_dataset_mapper.py

Prompts

```
['build a list of image augmentation transforms from a Detectron2 config for training', 'convert COCO polygon segmentations to binary mask tensors for a given image size', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format', 'map a Detectron2 dataset dict through the COCOInstanceNewBaselineDatasetMapper for training or inference', 'review the COCOInstanceNewBaselineDatasetMapper from_config class method to build mapper from Detectron2 config', 'create a COCOPanopticNewBaselineDatasetMapper instance from a Detectron2 config with training augmentations', 'process panoptic segmentation ground truth by applying transforms and converting RGB to instance masks', 'review the COCOPanopticNewBaselineDatasetMapper call method to understand image reading, transforms, and panoptic annotation handling', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method on a Detectron2 dataset dict for instance segmentation', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic supporting polygons, RLE, and numpy arrays', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different divisibility value', 'build a MaskFormerSemanticDatasetMapper instance with custom augmentations, image format, ignore label, and size divisibility settings', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config object with automatic augmentation pipeline construction', 'run the MaskFormerSemanticDatasetMapper on a dataset dict to transform it into MaskFormer semantic segmentation format', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color augment, and flip transforms', 'review how the MaskFormerSemanticDatasetMapper creates per-category binary masks and Instances objects from semantic segmentation ground truth']
```

Usage

```
{'build_MaskFormerSemanticDatasetMapper': 'build a MaskFormerSemanticDatasetMapper instance with custom augmentations, image format, ignore label, and size divisibility settings', 'build_MaskFormerSemanticDatasetMapper_from_config': 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config object with automatic augmentation pipeline construction', 'run_MaskFormerSemanticDatasetMapper_call': 'run the MaskFormerSemanticDatasetMapper on a dataset dict to transform it into MaskFormer semantic segmentation format', 'review_MaskFormerSemanticDatasetMapper_augmentations': 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color augment, and flip transforms', 'review_MaskFormerSemanticDatasetMapper_instances': 'review how the MaskFormerSemanticDatasetMapper creates per-category binary masks and Instances objects from semantic segmentation ground truth'}
```

