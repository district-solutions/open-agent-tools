# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations to detectron2 format', 'convert a single ADE20K annotation image by shifting pixel values down by 1', 'build a pipeline to process ADE20K training and validation annotation directories', 'refactor the convert function to support additional image format transformations', 'review the convert function that shifts ADE20K annotation pixel values for detectron2 compatibility', 'run the script to COCOfy LVIS v0.5 train and val JSON annotation files', 'run cocofy_lvis on a custom LVIS JSON file to filter and remap categories to COCO IDs', 'create a COCOfied LVIS JSON by filtering annotations to only COCO-compatible categories via synset mapping', 'review the cocofy_lvis function that filters LVIS annotations and remaps category IDs to COCO IDs', 'summarize the COCO_SYNSET_CATEGORIES constant mapping 90 WordNet synsets to their corresponding COCO category IDs', 'create semantic segmentation annotations from COCO panoptic segmentation annotations for PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to generate semantic annotations from COCO panoptic data for train and val splits', 'create symbolic links for a 100-image subset of panoptic validation data for quick testing', 'download the panoptic val2017_100 annotation JSON file from the Detectron2 public file server']
```

Usage

```
{'run_convert_ade20k_annotations': 'run the script to convert ADE20K semantic segmentation annotations to detectron2 format', 'convert_single_annotation': 'convert a single ADE20K annotation image by shifting pixel values down by 1', 'build_ade20k_dataset_pipeline': 'build a pipeline to process ADE20K training and validation annotation directories', 'refactor_convert_function': 'refactor the convert function to support additional image format transformations', 'review_convert_ade20k': 'review the convert function that shifts ADE20K annotation pixel values for detectron2 compatibility'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/datasets/prepare_cocofied_lvis.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations to detectron2 format', 'convert a single ADE20K annotation image by shifting pixel values down by 1', 'build a pipeline to process ADE20K training and validation annotation directories', 'refactor the convert function to support additional image format transformations', 'review the convert function that shifts ADE20K annotation pixel values for detectron2 compatibility', 'run the script to COCOfy LVIS v0.5 train and val JSON annotation files', 'run cocofy_lvis on a custom LVIS JSON file to filter and remap categories to COCO IDs', 'create a COCOfied LVIS JSON by filtering annotations to only COCO-compatible categories via synset mapping', 'review the cocofy_lvis function that filters LVIS annotations and remaps category IDs to COCO IDs', 'summarize the COCO_SYNSET_CATEGORIES constant mapping 90 WordNet synsets to their corresponding COCO category IDs', 'create semantic segmentation annotations from COCO panoptic segmentation annotations for PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to generate semantic annotations from COCO panoptic data for train and val splits', 'create symbolic links for a 100-image subset of panoptic validation data for quick testing', 'download the panoptic val2017_100 annotation JSON file from the Detectron2 public file server']
```

Usage

```
{'run_cocofy_lvis_cli': 'run the script to COCOfy LVIS v0.5 train and val JSON annotation files', 'run_cocofy_lvis_custom': 'run cocofy_lvis on a custom LVIS JSON file to filter and remap categories to COCO IDs', 'create_cocofied_lvis': 'create a COCOfied LVIS JSON by filtering annotations to only COCO-compatible categories via synset mapping', 'review_cocofy_lvis': 'review the cocofy_lvis function that filters LVIS annotations and remaps category IDs to COCO IDs', 'summarize_COCO_SYNSET_CATEGORIES': 'summarize the COCO_SYNSET_CATEGORIES constant mapping 90 WordNet synsets to their corresponding COCO category IDs'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/datasets/prepare_panoptic_fpn.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations to detectron2 format', 'convert a single ADE20K annotation image by shifting pixel values down by 1', 'build a pipeline to process ADE20K training and validation annotation directories', 'refactor the convert function to support additional image format transformations', 'review the convert function that shifts ADE20K annotation pixel values for detectron2 compatibility', 'run the script to COCOfy LVIS v0.5 train and val JSON annotation files', 'run cocofy_lvis on a custom LVIS JSON file to filter and remap categories to COCO IDs', 'create a COCOfied LVIS JSON by filtering annotations to only COCO-compatible categories via synset mapping', 'review the cocofy_lvis function that filters LVIS annotations and remaps category IDs to COCO IDs', 'summarize the COCO_SYNSET_CATEGORIES constant mapping 90 WordNet synsets to their corresponding COCO category IDs', 'create semantic segmentation annotations from COCO panoptic segmentation annotations for PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to generate semantic annotations from COCO panoptic data for train and val splits', 'create symbolic links for a 100-image subset of panoptic validation data for quick testing', 'download the panoptic val2017_100 annotation JSON file from the Detectron2 public file server']
```

Usage

```
{'separate_coco_semantic_from_panoptic': 'create semantic segmentation annotations from COCO panoptic segmentation annotations for PanopticFPN', 'process_panoptic_to_semantic': 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run_prepare_panoptic_fpn': 'run the script to generate semantic annotations from COCO panoptic data for train and val splits', 'link_val100': 'create symbolic links for a 100-image subset of panoptic validation data for quick testing', 'download_panoptic_val2017_100': 'download the panoptic val2017_100 annotation JSON file from the Detectron2 public file server'}
```

