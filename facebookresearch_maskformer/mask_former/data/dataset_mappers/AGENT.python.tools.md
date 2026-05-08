# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/mask_former/data/dataset_mappers/detr_panoptic_dataset_mapper.py

Prompts

```
['build a list of TransformGen objects from a detectron2 config for training or inference', 'create a DETRPanopticDatasetMapper instance with crop and transform generators for COCO panoptic segmentation', 'review the DETRPanopticDatasetMapper from_config class method to build mapper kwargs from a detectron2 config', 'test the DETRPanopticDatasetMapper call method to transform a dataset dict with image reads and panoptic segmentation parsing', 'summarize the DETRPanopticDatasetMapper class that maps Detectron2 dataset dicts into MaskFormer format with geometric transforms and cropping', 'build a MaskFormerSemanticDatasetMapper to transform Detectron2 dataset dicts for semantic segmentation training', 'create a MaskFormerSemanticDatasetMapper from a Detectron2 config with augmentations and crop settings', 'test the MaskFormerSemanticDatasetMapper call method to map dataset dicts with semantic segmentation ground truth', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip transforms', 'refactor the MaskFormerSemanticDatasetMapper to customize per-category binary mask generation from semantic segmentation labels']
```

Usage

```
{'build_transform_gens': 'build a list of TransformGen objects from a detectron2 config for training or inference', 'create_DETRPanopticDatasetMapper': 'create a DETRPanopticDatasetMapper instance with crop and transform generators for COCO panoptic segmentation', 'review_DETRPanopticDatasetMapper_from_config': 'review the DETRPanopticDatasetMapper from_config class method to build mapper kwargs from a detectron2 config', 'test_DETRPanopticDatasetMapper_call': 'test the DETRPanopticDatasetMapper call method to transform a dataset dict with image reads and panoptic segmentation parsing', 'summarize_DETRPanopticDatasetMapper': 'summarize the DETRPanopticDatasetMapper class that maps Detectron2 dataset dicts into MaskFormer format with geometric transforms and cropping'}
```

## File: facebookresearch_maskformer/mask_former/data/dataset_mappers/mask_former_semantic_dataset_mapper.py

Prompts

```
['build a list of TransformGen objects from a detectron2 config for training or inference', 'create a DETRPanopticDatasetMapper instance with crop and transform generators for COCO panoptic segmentation', 'review the DETRPanopticDatasetMapper from_config class method to build mapper kwargs from a detectron2 config', 'test the DETRPanopticDatasetMapper call method to transform a dataset dict with image reads and panoptic segmentation parsing', 'summarize the DETRPanopticDatasetMapper class that maps Detectron2 dataset dicts into MaskFormer format with geometric transforms and cropping', 'build a MaskFormerSemanticDatasetMapper to transform Detectron2 dataset dicts for semantic segmentation training', 'create a MaskFormerSemanticDatasetMapper from a Detectron2 config with augmentations and crop settings', 'test the MaskFormerSemanticDatasetMapper call method to map dataset dicts with semantic segmentation ground truth', 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip transforms', 'refactor the MaskFormerSemanticDatasetMapper to customize per-category binary mask generation from semantic segmentation labels']
```

Usage

```
{'build_semantic_dataset_mapper': 'build a MaskFormerSemanticDatasetMapper to transform Detectron2 dataset dicts for semantic segmentation training', 'create_mapper_from_config': 'create a MaskFormerSemanticDatasetMapper from a Detectron2 config with augmentations and crop settings', 'test_call_method': 'test the MaskFormerSemanticDatasetMapper call method to map dataset dicts with semantic segmentation ground truth', 'review_augmentation_pipeline': 'review the MaskFormerSemanticDatasetMapper augmentation pipeline including resize, crop, color aug, and flip transforms', 'refactor_binary_mask_generation': 'refactor the MaskFormerSemanticDatasetMapper to customize per-category binary mask generation from semantic segmentation labels'}
```

