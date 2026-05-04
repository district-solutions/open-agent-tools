# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/prod_lib/data/builtin.py

Prompts

```
['register a COCO unlabeled dataset with a name, metadata dict, json annotation file, and image root path', 'load a COCO format json annotation file into a list of Detectron2 standard dataset dicts', 'load and return the contents of a json file using PathManager for remote or local paths', 'register all Cityscapes foggy dataset splits including train, val, and test into the DatasetCatalog', 'register all Clipart PASCAL VOC format dataset splits including train and test into the DatasetCatalog', 'load cityscapes instance segmentation annotations from JSON polygon files into Detectron2 format', 'load cityscapes instance segmentation annotations from PNG instance ID files using multiprocessing', 'load cityscapes semantic segmentation labels and image metadata into a list of dicts', 'scan cityscapes image and ground truth directories to collect tuples of matching annotation file paths', 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dict with bounding boxes and segmentation']
```

Usage

```
{'register_coco_unlabel_instances': 'register a COCO unlabeled dataset with a name, metadata dict, json annotation file, and image root path', 'load_coco_unlabel_json': 'load a COCO format json annotation file into a list of Detectron2 standard dataset dicts', 'load_json': 'load and return the contents of a json file using PathManager for remote or local paths', 'register_all_cityscapes_foggy': 'register all Cityscapes foggy dataset splits including train, val, and test into the DatasetCatalog', 'register_all_clipart': 'register all Clipart PASCAL VOC format dataset splits including train and test into the DatasetCatalog'}
```

## File: facebookresearch_adaptiveteacher/prod_lib/data/cityscapes_foggy.py

Prompts

```
['register a COCO unlabeled dataset with a name, metadata dict, json annotation file, and image root path', 'load a COCO format json annotation file into a list of Detectron2 standard dataset dicts', 'load and return the contents of a json file using PathManager for remote or local paths', 'register all Cityscapes foggy dataset splits including train, val, and test into the DatasetCatalog', 'register all Clipart PASCAL VOC format dataset splits including train and test into the DatasetCatalog', 'load cityscapes instance segmentation annotations from JSON polygon files into Detectron2 format', 'load cityscapes instance segmentation annotations from PNG instance ID files using multiprocessing', 'load cityscapes semantic segmentation labels and image metadata into a list of dicts', 'scan cityscapes image and ground truth directories to collect tuples of matching annotation file paths', 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dict with bounding boxes and segmentation']
```

Usage

```
{'load_cityscapes_instances_from_json': 'load cityscapes instance segmentation annotations from JSON polygon files into Detectron2 format', 'load_cityscapes_instances_from_png': 'load cityscapes instance segmentation annotations from PNG instance ID files using multiprocessing', 'load_cityscapes_semantic': 'load cityscapes semantic segmentation labels and image metadata into a list of dicts', 'get_cityscapes_files': 'scan cityscapes image and ground truth directories to collect tuples of matching annotation file paths', 'cityscapes_files_to_dict': 'parse a single cityscapes annotation file tuple into a Detectron2 dataset dict with bounding boxes and segmentation'}
```

