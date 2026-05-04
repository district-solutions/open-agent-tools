# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to Detectron2 format', 'create a function that converts a single ADE20K annotation image by shifting pixel values down by 1', 'build a python module to prepare ADE20K training and validation annotations for Detectron2 consumption', 'review the python convert function that shifts uint8 annotation image pixel values by subtracting 1', 'summarize the python script that iterates over ADE20K annotation directories and converts images for Detectron2', 'run cocofy_lvis to filter an LVIS JSON annotation file to only COCO-compatible categories and save the output', 'run the script to COCOfy LVIS v0.5 train and val JSON files using the DETECTRON2_DATASETS env var', 'review cocofy_lvis to understand how it maps LVIS synsets to COCO category IDs and filters annotations', 'refactor cocofy_lvis to support a custom synset-to-COCO mapping instead of the hardcoded COCO_SYNSET_CATEGORIES list', 'summarize the COCO_SYNSET_CATEGORIES constant which maps 80 WordNet synsets to their corresponding COCO category IDs', 'run separate_coco_semantic_from_panoptic to convert COCO panoptic annotations into semantic segmentation images', 'run the script to generate panoptic stuff annotations for COCO train2017 and val2017 splits', 'review separate_coco_semantic_from_panoptic which maps stuff categories to contiguous IDs and things to class 0', 'review _process_panoptic_to_semantic which converts a single panoptic PNG to semantic segmentation using rgb2id', 'summarize link_val100 which creates symlinks for a 100-image validation subset for quick testing']
```

Usage

```
{'run_convert_ade20k_annotations': 'run the script to convert ADE20K semantic segmentation annotations from original format to Detectron2 format', 'convert_annotation_image': 'create a function that converts a single ADE20K annotation image by shifting pixel values down by 1', 'build_ade20k_dataset_prep': 'build a python module to prepare ADE20K training and validation annotations for Detectron2 consumption', 'review_convert_function': 'review the python convert function that shifts uint8 annotation image pixel values by subtracting 1', 'summarize_ade20k_prep_script': 'summarize the python script that iterates over ADE20K annotation directories and converts images for Detectron2'}
```

## File: facebookresearch_detectron2/datasets/prepare_cocofied_lvis.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to Detectron2 format', 'create a function that converts a single ADE20K annotation image by shifting pixel values down by 1', 'build a python module to prepare ADE20K training and validation annotations for Detectron2 consumption', 'review the python convert function that shifts uint8 annotation image pixel values by subtracting 1', 'summarize the python script that iterates over ADE20K annotation directories and converts images for Detectron2', 'run cocofy_lvis to filter an LVIS JSON annotation file to only COCO-compatible categories and save the output', 'run the script to COCOfy LVIS v0.5 train and val JSON files using the DETECTRON2_DATASETS env var', 'review cocofy_lvis to understand how it maps LVIS synsets to COCO category IDs and filters annotations', 'refactor cocofy_lvis to support a custom synset-to-COCO mapping instead of the hardcoded COCO_SYNSET_CATEGORIES list', 'summarize the COCO_SYNSET_CATEGORIES constant which maps 80 WordNet synsets to their corresponding COCO category IDs', 'run separate_coco_semantic_from_panoptic to convert COCO panoptic annotations into semantic segmentation images', 'run the script to generate panoptic stuff annotations for COCO train2017 and val2017 splits', 'review separate_coco_semantic_from_panoptic which maps stuff categories to contiguous IDs and things to class 0', 'review _process_panoptic_to_semantic which converts a single panoptic PNG to semantic segmentation using rgb2id', 'summarize link_val100 which creates symlinks for a 100-image validation subset for quick testing']
```

Usage

```
{'run_cocofy_lvis': 'run cocofy_lvis to filter an LVIS JSON annotation file to only COCO-compatible categories and save the output', 'run_prepare_cocofied_lvis_main': 'run the script to COCOfy LVIS v0.5 train and val JSON files using the DETECTRON2_DATASETS env var', 'review_cocofy_lvis': 'review cocofy_lvis to understand how it maps LVIS synsets to COCO category IDs and filters annotations', 'refactor_cocofy_lvis': 'refactor cocofy_lvis to support a custom synset-to-COCO mapping instead of the hardcoded COCO_SYNSET_CATEGORIES list', 'summarize_COCO_SYNSET_CATEGORIES': 'summarize the COCO_SYNSET_CATEGORIES constant which maps 80 WordNet synsets to their corresponding COCO category IDs'}
```

## File: facebookresearch_detectron2/datasets/prepare_panoptic_fpn.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to Detectron2 format', 'create a function that converts a single ADE20K annotation image by shifting pixel values down by 1', 'build a python module to prepare ADE20K training and validation annotations for Detectron2 consumption', 'review the python convert function that shifts uint8 annotation image pixel values by subtracting 1', 'summarize the python script that iterates over ADE20K annotation directories and converts images for Detectron2', 'run cocofy_lvis to filter an LVIS JSON annotation file to only COCO-compatible categories and save the output', 'run the script to COCOfy LVIS v0.5 train and val JSON files using the DETECTRON2_DATASETS env var', 'review cocofy_lvis to understand how it maps LVIS synsets to COCO category IDs and filters annotations', 'refactor cocofy_lvis to support a custom synset-to-COCO mapping instead of the hardcoded COCO_SYNSET_CATEGORIES list', 'summarize the COCO_SYNSET_CATEGORIES constant which maps 80 WordNet synsets to their corresponding COCO category IDs', 'run separate_coco_semantic_from_panoptic to convert COCO panoptic annotations into semantic segmentation images', 'run the script to generate panoptic stuff annotations for COCO train2017 and val2017 splits', 'review separate_coco_semantic_from_panoptic which maps stuff categories to contiguous IDs and things to class 0', 'review _process_panoptic_to_semantic which converts a single panoptic PNG to semantic segmentation using rgb2id', 'summarize link_val100 which creates symlinks for a 100-image validation subset for quick testing']
```

Usage

```
{'run_separate_coco_semantic_from_panoptic': 'run separate_coco_semantic_from_panoptic to convert COCO panoptic annotations into semantic segmentation images', 'run_prepare_panoptic_fpn_main': 'run the script to generate panoptic stuff annotations for COCO train2017 and val2017 splits', 'review_separate_coco_semantic_from_panoptic': 'review separate_coco_semantic_from_panoptic which maps stuff categories to contiguous IDs and things to class 0', 'review_process_panoptic_to_semantic': 'review _process_panoptic_to_semantic which converts a single panoptic PNG to semantic segmentation using rgb2id', 'summarize_link_val100': 'summarize link_val100 which creates symlinks for a 100-image validation subset for quick testing'}
```

