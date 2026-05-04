# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/tools/convert_datasets/cityscapes.py

Prompts

```
['run the python module to convert Cityscapes annotations to COCO JSON format for train val and test splits', 'run the collect_files function to gather image instance and segmentation file tuples from Cityscapes directories', 'run the load_img_info function to parse instance ID images and extract annotation info with masks and bboxes', 'run the cvt_annotations function to transform image info dicts into a COCO-style JSON and dump to file', 'run the parse_args function to build an argparse parser for Cityscapes path img-dir gt-dir out-dir and nproc', 'run the pascal_voc script to convert PASCAL VOC annotations to mmdetection format', 'run parse_xml to extract bounding boxes and labels from a PASCAL VOC XML annotation file', 'run cvt_annotations to convert PASCAL VOC dataset annotations for a specific year and split to pickle', 'run main to auto-detect VOC2007 and VOC2012 folders and convert all splits to pickle files', 'run parse_args to build an argument parser accepting devkit_path and optional output directory']
```

Usage

```
{'convert_cityscapes_to_coco': 'run the python module to convert Cityscapes annotations to COCO JSON format for train val and test splits', 'collect_cityscapes_files': 'run the collect_files function to gather image instance and segmentation file tuples from Cityscapes directories', 'load_cityscapes_annotations': 'run the load_img_info function to parse instance ID images and extract annotation info with masks and bboxes', 'convert_annotations_to_json': 'run the cvt_annotations function to transform image info dicts into a COCO-style JSON and dump to file', 'parse_cityscapes_cli_args': 'run the parse_args function to build an argparse parser for Cityscapes path img-dir gt-dir out-dir and nproc'}
```

## File: facebookresearch_generic-grouping/tools/convert_datasets/pascal_voc.py

Prompts

```
['run the python module to convert Cityscapes annotations to COCO JSON format for train val and test splits', 'run the collect_files function to gather image instance and segmentation file tuples from Cityscapes directories', 'run the load_img_info function to parse instance ID images and extract annotation info with masks and bboxes', 'run the cvt_annotations function to transform image info dicts into a COCO-style JSON and dump to file', 'run the parse_args function to build an argparse parser for Cityscapes path img-dir gt-dir out-dir and nproc', 'run the pascal_voc script to convert PASCAL VOC annotations to mmdetection format', 'run parse_xml to extract bounding boxes and labels from a PASCAL VOC XML annotation file', 'run cvt_annotations to convert PASCAL VOC dataset annotations for a specific year and split to pickle', 'run main to auto-detect VOC2007 and VOC2012 folders and convert all splits to pickle files', 'run parse_args to build an argument parser accepting devkit_path and optional output directory']
```

Usage

```
{'run_pascal_voc_conversion': 'run the pascal_voc script to convert PASCAL VOC annotations to mmdetection format', 'run_parse_xml': 'run parse_xml to extract bounding boxes and labels from a PASCAL VOC XML annotation file', 'run_cvt_annotations': 'run cvt_annotations to convert PASCAL VOC dataset annotations for a specific year and split to pickle', 'run_main': 'run main to auto-detect VOC2007 and VOC2012 folders and convert all splits to pickle files', 'run_parse_args': 'run parse_args to build an argument parser accepting devkit_path and optional output directory'}
```

