# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to detectron2 format', 'create a function call to convert a single ADE20K annotation image by shifting pixel values down by 1', 'run the prepare_ade20k_sem_seg script to process training and validation annotation directories', 'review the convert function that shifts ADE20K annotation pixel values and saves the output image', 'summarize the prepare_ade20k_sem_seg script that batch converts ADE20K annotations for detectron2 compatibility', 'run the script to convert LVIS annotations to COCO-compatible format for train and val splits', 'filter LVIS instance segmentation annotations to keep only COCO categories and rewrite category IDs', 'convert an LVIS JSON annotation file to COCOfied format with COCO category IDs via synset mapping', 'review the list of 90 COCO synset to category ID mappings used for LVIS filtering', 'summarize how cocofy_lvis filters annotations, remaps category IDs, and updates image-level category lists', 'create semantic segmentation annotations from panoptic segmentation annotations for use by PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to prepare COCO panoptic and semantic segmentation datasets for train and val splits', 'create symlinks for a subset of 100 validation panoptic images for quick testing', 'review the separate_coco_semantic_from_panoptic function to understand how it maps stuff and thing categories']
```

Usage

```
{'convert_ade20k_annotations': 'run the script to convert ADE20K semantic segmentation annotations from original format to detectron2 format', 'convert_single_annotation': 'create a function call to convert a single ADE20K annotation image by shifting pixel values down by 1', 'run_prepare_ade20k': 'run the prepare_ade20k_sem_seg script to process training and validation annotation directories', 'review_convert_function': 'review the convert function that shifts ADE20K annotation pixel values and saves the output image', 'summarize_ade20k_prep': 'summarize the prepare_ade20k_sem_seg script that batch converts ADE20K annotations for detectron2 compatibility'}
```

## File: facebookresearch_banmo/third_party/detectron2/datasets/prepare_cocofied_lvis.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to detectron2 format', 'create a function call to convert a single ADE20K annotation image by shifting pixel values down by 1', 'run the prepare_ade20k_sem_seg script to process training and validation annotation directories', 'review the convert function that shifts ADE20K annotation pixel values and saves the output image', 'summarize the prepare_ade20k_sem_seg script that batch converts ADE20K annotations for detectron2 compatibility', 'run the script to convert LVIS annotations to COCO-compatible format for train and val splits', 'filter LVIS instance segmentation annotations to keep only COCO categories and rewrite category IDs', 'convert an LVIS JSON annotation file to COCOfied format with COCO category IDs via synset mapping', 'review the list of 90 COCO synset to category ID mappings used for LVIS filtering', 'summarize how cocofy_lvis filters annotations, remaps category IDs, and updates image-level category lists', 'create semantic segmentation annotations from panoptic segmentation annotations for use by PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to prepare COCO panoptic and semantic segmentation datasets for train and val splits', 'create symlinks for a subset of 100 validation panoptic images for quick testing', 'review the separate_coco_semantic_from_panoptic function to understand how it maps stuff and thing categories']
```

Usage

```
{'run_cocofy_lvis': 'run the script to convert LVIS annotations to COCO-compatible format for train and val splits', 'cocofy_lvis_function': 'filter LVIS instance segmentation annotations to keep only COCO categories and rewrite category IDs', 'convert_lvis_to_coco': 'convert an LVIS JSON annotation file to COCOfied format with COCO category IDs via synset mapping', 'review_COCO_SYNSET_CATEGORIES': 'review the list of 90 COCO synset to category ID mappings used for LVIS filtering', 'summarize_cocofy_lvis': 'summarize how cocofy_lvis filters annotations, remaps category IDs, and updates image-level category lists'}
```

## File: facebookresearch_banmo/third_party/detectron2/datasets/prepare_panoptic_fpn.py

Prompts

```
['run the script to convert ADE20K semantic segmentation annotations from original format to detectron2 format', 'create a function call to convert a single ADE20K annotation image by shifting pixel values down by 1', 'run the prepare_ade20k_sem_seg script to process training and validation annotation directories', 'review the convert function that shifts ADE20K annotation pixel values and saves the output image', 'summarize the prepare_ade20k_sem_seg script that batch converts ADE20K annotations for detectron2 compatibility', 'run the script to convert LVIS annotations to COCO-compatible format for train and val splits', 'filter LVIS instance segmentation annotations to keep only COCO categories and rewrite category IDs', 'convert an LVIS JSON annotation file to COCOfied format with COCO category IDs via synset mapping', 'review the list of 90 COCO synset to category ID mappings used for LVIS filtering', 'summarize how cocofy_lvis filters annotations, remaps category IDs, and updates image-level category lists', 'create semantic segmentation annotations from panoptic segmentation annotations for use by PanopticFPN', 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run the script to prepare COCO panoptic and semantic segmentation datasets for train and val splits', 'create symlinks for a subset of 100 validation panoptic images for quick testing', 'review the separate_coco_semantic_from_panoptic function to understand how it maps stuff and thing categories']
```

Usage

```
{'separate_coco_semantic_from_panoptic': 'create semantic segmentation annotations from panoptic segmentation annotations for use by PanopticFPN', 'process_panoptic_to_semantic': 'convert a single panoptic PNG image to a semantic segmentation image using an id map', 'run_prepare_panoptic_fpn': 'run the script to prepare COCO panoptic and semantic segmentation datasets for train and val splits', 'link_val100': 'create symlinks for a subset of 100 validation panoptic images for quick testing', 'review_separate_coco_semantic_from_panoptic': 'review the separate_coco_semantic_from_panoptic function to understand how it maps stuff and thing categories'}
```

