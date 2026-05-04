# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/data/datasets/builtin.py

Prompts

```
['register a COCO format dataset with a json annotation file and image root directory into the DatasetCatalog', 'load unlabelled COCO json annotations and return a list of image record dicts with file paths and dimensions', 'register all predefined COCO unlabelled dataset splits from a given root directory into the DatasetCatalog', 'register all Cityscapes foggy image dataset splits for train val and test into the DatasetCatalog', 'register all Clipart1k dataset splits in PASCAL VOC format into the DatasetCatalog with pascal_voc evaluator', 'load cityscapes instance segmentation annotations from json polygon files into Detectron2 format', 'load cityscapes instance segmentation annotations from png instance id files with polygon or mask output', 'load cityscapes semantic segmentation labels and image metadata into Detectron2 dataset format', 'scan cityscapes image and ground truth directories to collect matching file tuples for foggy variants', 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dictionary with bounding boxes and segmentation']
```

Usage

```
{'register_coco_unlabel_instances': 'register a COCO format dataset with a json annotation file and image root directory into the DatasetCatalog', 'load_coco_unlabel_json': 'load unlabelled COCO json annotations and return a list of image record dicts with file paths and dimensions', 'register_coco_unlabel': 'register all predefined COCO unlabelled dataset splits from a given root directory into the DatasetCatalog', 'register_all_cityscapes_foggy': 'register all Cityscapes foggy image dataset splits for train val and test into the DatasetCatalog', 'register_all_clipart': 'register all Clipart1k dataset splits in PASCAL VOC format into the DatasetCatalog with pascal_voc evaluator'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/data/datasets/cityscapes_foggy.py

Prompts

```
['register a COCO format dataset with a json annotation file and image root directory into the DatasetCatalog', 'load unlabelled COCO json annotations and return a list of image record dicts with file paths and dimensions', 'register all predefined COCO unlabelled dataset splits from a given root directory into the DatasetCatalog', 'register all Cityscapes foggy image dataset splits for train val and test into the DatasetCatalog', 'register all Clipart1k dataset splits in PASCAL VOC format into the DatasetCatalog with pascal_voc evaluator', 'load cityscapes instance segmentation annotations from json polygon files into Detectron2 format', 'load cityscapes instance segmentation annotations from png instance id files with polygon or mask output', 'load cityscapes semantic segmentation labels and image metadata into Detectron2 dataset format', 'scan cityscapes image and ground truth directories to collect matching file tuples for foggy variants', 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dictionary with bounding boxes and segmentation']
```

Usage

```
{'load_cityscapes_instances_from_json': 'load cityscapes instance segmentation annotations from json polygon files into Detectron2 format', 'load_cityscapes_instances_from_png': 'load cityscapes instance segmentation annotations from png instance id files with polygon or mask output', 'load_cityscapes_semantic': 'load cityscapes semantic segmentation labels and image metadata into Detectron2 dataset format', 'get_cityscapes_files': 'scan cityscapes image and ground truth directories to collect matching file tuples for foggy variants', 'parse_cityscapes_to_dict': 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dictionary with bounding boxes and segmentation'}
```

