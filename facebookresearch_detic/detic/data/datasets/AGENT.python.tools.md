# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/data/datasets/imagenet.py

Prompts

```
['register a custom ImageNet LVIS dataset split with Detectron2 DatasetCatalog and MetadataCatalog using custom_register_imagenet_instances', 'register the ImageNet LVIS 22K dataset split by importing the module which auto-registers imagenet_lvis-22k', 'customize ImageNet split image root and annotation JSON paths in _CUSTOM_SPLITS_IMAGENET before registration', 'review the custom_register_imagenet_instances function to understand how it registers datasets with evaluator_type imagenet', 'summarize how the module auto-registers ImageNet LVIS v1 and 22K splits on import via module-level loops', 'load an LVIS v1 JSON annotation file and return dataset dictionaries with bounding boxes and segmentation masks', 'register a custom LVIS instances dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root', 'get metadata for the LVIS 22K category set including thing class names from the 22K categories list', 'review the custom_load_lvis_json function that parses LVIS annotations, converts category IDs to 0-based, and handles negative and positive category IDs', 'refactor the custom_register_lvis_instances function to support additional metadata fields or custom evaluator types beyond LVIS', 'register an OID instances dataset to the Detectron2 DatasetCatalog with a COCO JSON file and image root path', 'load a COCO format JSON annotation file and return a list of dataset dicts with image records and annotations', 'map non-contiguous category IDs from a COCO JSON file to contiguous IDs starting from zero for the dataset metadata', 'filter out invalid polygon segmentations with fewer than 3 points when loading COCO annotation data', "handle negative category IDs in image metadata by mapping them through the dataset's contiguous ID mapping"]
```

Usage

```
{'register_imagenet_lvis_dataset': 'register a custom ImageNet LVIS dataset split with Detectron2 DatasetCatalog and MetadataCatalog using custom_register_imagenet_instances', 'register_imagenet_22k_dataset': 'register the ImageNet LVIS 22K dataset split by importing the module which auto-registers imagenet_lvis-22k', 'customize_imagenet_split_paths': 'customize ImageNet split image root and annotation JSON paths in _CUSTOM_SPLITS_IMAGENET before registration', 'review_custom_register_imagenet_instances': 'review the custom_register_imagenet_instances function to understand how it registers datasets with evaluator_type imagenet', 'summarize_imagenet_dataset_registration': 'summarize how the module auto-registers ImageNet LVIS v1 and 22K splits on import via module-level loops'}
```

## File: facebookresearch_detic/detic/data/datasets/lvis_v1.py

Prompts

```
['register a custom ImageNet LVIS dataset split with Detectron2 DatasetCatalog and MetadataCatalog using custom_register_imagenet_instances', 'register the ImageNet LVIS 22K dataset split by importing the module which auto-registers imagenet_lvis-22k', 'customize ImageNet split image root and annotation JSON paths in _CUSTOM_SPLITS_IMAGENET before registration', 'review the custom_register_imagenet_instances function to understand how it registers datasets with evaluator_type imagenet', 'summarize how the module auto-registers ImageNet LVIS v1 and 22K splits on import via module-level loops', 'load an LVIS v1 JSON annotation file and return dataset dictionaries with bounding boxes and segmentation masks', 'register a custom LVIS instances dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root', 'get metadata for the LVIS 22K category set including thing class names from the 22K categories list', 'review the custom_load_lvis_json function that parses LVIS annotations, converts category IDs to 0-based, and handles negative and positive category IDs', 'refactor the custom_register_lvis_instances function to support additional metadata fields or custom evaluator types beyond LVIS', 'register an OID instances dataset to the Detectron2 DatasetCatalog with a COCO JSON file and image root path', 'load a COCO format JSON annotation file and return a list of dataset dicts with image records and annotations', 'map non-contiguous category IDs from a COCO JSON file to contiguous IDs starting from zero for the dataset metadata', 'filter out invalid polygon segmentations with fewer than 3 points when loading COCO annotation data', "handle negative category IDs in image metadata by mapping them through the dataset's contiguous ID mapping"]
```

Usage

```
{'load_lvis_json_dataset': 'load an LVIS v1 JSON annotation file and return dataset dictionaries with bounding boxes and segmentation masks', 'register_lvis_instances': 'register a custom LVIS instances dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root', 'get_lvis_22k_meta': 'get metadata for the LVIS 22K category set including thing class names from the 22K categories list', 'review_custom_load_lvis_json': 'review the custom_load_lvis_json function that parses LVIS annotations, converts category IDs to 0-based, and handles negative and positive category IDs', 'refactor_custom_register_lvis_instances': 'refactor the custom_register_lvis_instances function to support additional metadata fields or custom evaluator types beyond LVIS'}
```

## File: facebookresearch_detic/detic/data/datasets/register_oid.py

Prompts

```
['register a custom ImageNet LVIS dataset split with Detectron2 DatasetCatalog and MetadataCatalog using custom_register_imagenet_instances', 'register the ImageNet LVIS 22K dataset split by importing the module which auto-registers imagenet_lvis-22k', 'customize ImageNet split image root and annotation JSON paths in _CUSTOM_SPLITS_IMAGENET before registration', 'review the custom_register_imagenet_instances function to understand how it registers datasets with evaluator_type imagenet', 'summarize how the module auto-registers ImageNet LVIS v1 and 22K splits on import via module-level loops', 'load an LVIS v1 JSON annotation file and return dataset dictionaries with bounding boxes and segmentation masks', 'register a custom LVIS instances dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root', 'get metadata for the LVIS 22K category set including thing class names from the 22K categories list', 'review the custom_load_lvis_json function that parses LVIS annotations, converts category IDs to 0-based, and handles negative and positive category IDs', 'refactor the custom_register_lvis_instances function to support additional metadata fields or custom evaluator types beyond LVIS', 'register an OID instances dataset to the Detectron2 DatasetCatalog with a COCO JSON file and image root path', 'load a COCO format JSON annotation file and return a list of dataset dicts with image records and annotations', 'map non-contiguous category IDs from a COCO JSON file to contiguous IDs starting from zero for the dataset metadata', 'filter out invalid polygon segmentations with fewer than 3 points when loading COCO annotation data', "handle negative category IDs in image metadata by mapping them through the dataset's contiguous ID mapping"]
```

Usage

```
{'register_oid_dataset': 'register an OID instances dataset to the Detectron2 DatasetCatalog with a COCO JSON file and image root path', 'load_coco_json': 'load a COCO format JSON annotation file and return a list of dataset dicts with image records and annotations', 'map_category_ids': 'map non-contiguous category IDs from a COCO JSON file to contiguous IDs starting from zero for the dataset metadata', 'filter_invalid_polygons': 'filter out invalid polygon segmentations with fewer than 3 points when loading COCO annotation data', 'handle_neg_category_ids': "handle negative category IDs in image metadata by mapping them through the dataset's contiguous ID mapping"}
```

