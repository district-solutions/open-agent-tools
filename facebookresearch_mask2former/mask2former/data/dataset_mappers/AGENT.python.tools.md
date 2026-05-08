# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/data/dataset_mappers/coco_instance_new_baseline_dataset_mapper.py

Prompts

```
['convert COCO polygon segmentations to binary mask tensors given height and width dimensions', 'build a list of image augmentation transforms including resize, scale, and flip from a Detectron2 config', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format for training or inference', 'build a COCOInstanceNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'map a Detectron2 dataset dict to MaskFormer format by applying transforms and converting annotations to instance tensors', 'create a COCOPanopticNewBaselineDatasetMapper instance with transform generators and image format for COCO panoptic segmentation', 'map a Detectron2 dataset dict into MaskFormer format by reading images, applying transforms, and preparing tensors', 'build a COCOPanopticNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'review the COCOPanopticNewBaselineDatasetMapper class and its panoptic segmentation transformation logic for COCO dataset', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method to transform a Detectron2 dataset dict into tensors', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic for polygon, RLE, and numpy array types', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different padding strategy', 'create a MaskFormerSemanticDatasetMapper instance with augmentations, image format, and ignore label for training', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config with resize, crop, flip augmentations', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip', 'summarize how the mapper generates per-category binary masks from semantic segmentation ground truth']
```

Usage

```
{'convert_coco_poly_to_mask': 'convert COCO polygon segmentations to binary mask tensors given height and width dimensions', 'build_transform_gen': 'build a list of image augmentation transforms including resize, scale, and flip from a Detectron2 config', 'COCOInstanceNewBaselineDatasetMapper_init': 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format for training or inference', 'COCOInstanceNewBaselineDatasetMapper_from_config': 'build a COCOInstanceNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'COCOInstanceNewBaselineDatasetMapper_call': 'map a Detectron2 dataset dict to MaskFormer format by applying transforms and converting annotations to instance tensors'}
```

## File: facebookresearch_mask2former/mask2former/data/dataset_mappers/coco_panoptic_new_baseline_dataset_mapper.py

Prompts

```
['convert COCO polygon segmentations to binary mask tensors given height and width dimensions', 'build a list of image augmentation transforms including resize, scale, and flip from a Detectron2 config', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format for training or inference', 'build a COCOInstanceNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'map a Detectron2 dataset dict to MaskFormer format by applying transforms and converting annotations to instance tensors', 'create a COCOPanopticNewBaselineDatasetMapper instance with transform generators and image format for COCO panoptic segmentation', 'map a Detectron2 dataset dict into MaskFormer format by reading images, applying transforms, and preparing tensors', 'build a COCOPanopticNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'review the COCOPanopticNewBaselineDatasetMapper class and its panoptic segmentation transformation logic for COCO dataset', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method to transform a Detectron2 dataset dict into tensors', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic for polygon, RLE, and numpy array types', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different padding strategy', 'create a MaskFormerSemanticDatasetMapper instance with augmentations, image format, and ignore label for training', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config with resize, crop, flip augmentations', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip', 'summarize how the mapper generates per-category binary masks from semantic segmentation ground truth']
```

Usage

```
{'build_transform_gen': 'build a list of augmentation transforms including resize, scale, and flip from a Detectron2 config', 'create_dataset_mapper': 'create a COCOPanopticNewBaselineDatasetMapper instance with transform generators and image format for COCO panoptic segmentation', 'map_dataset_dict': 'map a Detectron2 dataset dict into MaskFormer format by reading images, applying transforms, and preparing tensors', 'from_config': 'build a COCOPanopticNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'review_COCOPanopticNewBaselineDatasetMapper': 'review the COCOPanopticNewBaselineDatasetMapper class and its panoptic segmentation transformation logic for COCO dataset'}
```

## File: facebookresearch_mask2former/mask2former/data/dataset_mappers/mask_former_instance_dataset_mapper.py

Prompts

```
['convert COCO polygon segmentations to binary mask tensors given height and width dimensions', 'build a list of image augmentation transforms including resize, scale, and flip from a Detectron2 config', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format for training or inference', 'build a COCOInstanceNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'map a Detectron2 dataset dict to MaskFormer format by applying transforms and converting annotations to instance tensors', 'create a COCOPanopticNewBaselineDatasetMapper instance with transform generators and image format for COCO panoptic segmentation', 'map a Detectron2 dataset dict into MaskFormer format by reading images, applying transforms, and preparing tensors', 'build a COCOPanopticNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'review the COCOPanopticNewBaselineDatasetMapper class and its panoptic segmentation transformation logic for COCO dataset', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method to transform a Detectron2 dataset dict into tensors', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic for polygon, RLE, and numpy array types', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different padding strategy', 'create a MaskFormerSemanticDatasetMapper instance with augmentations, image format, and ignore label for training', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config with resize, crop, flip augmentations', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip', 'summarize how the mapper generates per-category binary masks from semantic segmentation ground truth']
```

Usage

```
{'create_MaskFormerInstanceDatasetMapper': 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build_from_config': 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test_call_method': 'test the MaskFormerInstanceDatasetMapper call method to transform a Detectron2 dataset dict into tensors', 'review_mask_conversion': 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic for polygon, RLE, and numpy array types', 'refactor_padding_logic': 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different padding strategy'}
```

## File: facebookresearch_mask2former/mask2former/data/dataset_mappers/mask_former_semantic_dataset_mapper.py

Prompts

```
['convert COCO polygon segmentations to binary mask tensors given height and width dimensions', 'build a list of image augmentation transforms including resize, scale, and flip from a Detectron2 config', 'create a COCOInstanceNewBaselineDatasetMapper instance with transform generators and image format for training or inference', 'build a COCOInstanceNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'map a Detectron2 dataset dict to MaskFormer format by applying transforms and converting annotations to instance tensors', 'create a COCOPanopticNewBaselineDatasetMapper instance with transform generators and image format for COCO panoptic segmentation', 'map a Detectron2 dataset dict into MaskFormer format by reading images, applying transforms, and preparing tensors', 'build a COCOPanopticNewBaselineDatasetMapper from a Detectron2 config object with training mode and augmentation settings', 'review the COCOPanopticNewBaselineDatasetMapper class and its panoptic segmentation transformation logic for COCO dataset', 'create a MaskFormerInstanceDatasetMapper with augmentations, image format, and size divisibility for training', 'build a MaskFormerInstanceDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'test the MaskFormerInstanceDatasetMapper call method to transform a Detectron2 dataset dict into tensors', 'review the MaskFormerInstanceDatasetMapper segmentation mask conversion logic for polygon, RLE, and numpy array types', 'refactor the MaskFormerInstanceDatasetMapper image and mask padding logic to use a different padding strategy', 'create a MaskFormerSemanticDatasetMapper instance with augmentations, image format, and ignore label for training', 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config with resize, crop, flip augmentations', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip', 'summarize how the mapper generates per-category binary masks from semantic segmentation ground truth']
```

Usage

```
{'create_semantic_dataset_mapper': 'create a MaskFormerSemanticDatasetMapper instance with augmentations, image format, and ignore label for training', 'build_mapper_from_config': 'build a MaskFormerSemanticDatasetMapper from a Detectron2 config with resize, crop, flip augmentations', 'map_dataset_dict': 'map a Detectron2 dataset dict to MaskFormer semantic segmentation format with transforms and padding', 'review_augmentation_pipeline': 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip', 'summarize_binary_mask_generation': 'summarize how the mapper generates per-category binary masks from semantic segmentation ground truth'}
```

