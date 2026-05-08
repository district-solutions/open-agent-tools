# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/data/datasets/builtin.py

Prompts

```
['register all ImageNet dataset splits with self-training rounds as COCO instances under a root path', 'register all COCO semi-supervised dataset splits with varying annotation percentages as COCO instances', 'register all COCO class-agnostic dataset splits as COCO instances under a root path', 'register the Pascal VOC class-agnostic dataset split as a COCO instance under a root path', 'register all cross-domain class-agnostic dataset splits including clipart, watercolor, and comic as COCO instances', 'load a COCO JSON annotation file into Detectron2 standard dataset dict format with bounding boxes and segmentation masks', 'load semantic segmentation ground truth images matched by filename from a directory into Detectron2 dataset dict format', 'convert a Detectron2 registered dataset into COCO JSON format and cache the output to a file', 'register a COCO JSON annotation dataset with Detectron2 DatasetCatalog and MetadataCatalog for training', 'review the load_coco_json function to understand how COCO annotations are parsed and category IDs are remapped']
```

Usage

```
{'register_all_imagenet': 'register all ImageNet dataset splits with self-training rounds as COCO instances under a root path', 'register_all_coco_semi': 'register all COCO semi-supervised dataset splits with varying annotation percentages as COCO instances', 'register_all_coco_ca': 'register all COCO class-agnostic dataset splits as COCO instances under a root path', 'register_all_voc': 'register the Pascal VOC class-agnostic dataset split as a COCO instance under a root path', 'register_all_cross_domain': 'register all cross-domain class-agnostic dataset splits including clipart, watercolor, and comic as COCO instances'}
```

## File: facebookresearch_cutler/cutler/data/datasets/coco.py

Prompts

```
['register all ImageNet dataset splits with self-training rounds as COCO instances under a root path', 'register all COCO semi-supervised dataset splits with varying annotation percentages as COCO instances', 'register all COCO class-agnostic dataset splits as COCO instances under a root path', 'register the Pascal VOC class-agnostic dataset split as a COCO instance under a root path', 'register all cross-domain class-agnostic dataset splits including clipart, watercolor, and comic as COCO instances', 'load a COCO JSON annotation file into Detectron2 standard dataset dict format with bounding boxes and segmentation masks', 'load semantic segmentation ground truth images matched by filename from a directory into Detectron2 dataset dict format', 'convert a Detectron2 registered dataset into COCO JSON format and cache the output to a file', 'register a COCO JSON annotation dataset with Detectron2 DatasetCatalog and MetadataCatalog for training', 'review the load_coco_json function to understand how COCO annotations are parsed and category IDs are remapped']
```

Usage

```
{'load_coco_json': 'load a COCO JSON annotation file into Detectron2 standard dataset dict format with bounding boxes and segmentation masks', 'load_sem_seg': 'load semantic segmentation ground truth images matched by filename from a directory into Detectron2 dataset dict format', 'convert_to_coco_json': 'convert a Detectron2 registered dataset into COCO JSON format and cache the output to a file', 'register_coco_instances': 'register a COCO JSON annotation dataset with Detectron2 DatasetCatalog and MetadataCatalog for training', 'review_load_coco_json': 'review the load_coco_json function to understand how COCO annotations are parsed and category IDs are remapped'}
```

