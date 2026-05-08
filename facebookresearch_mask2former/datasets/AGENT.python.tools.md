# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['convert a single ADE20K annotation image to detectron2 format by shifting pixel values by minus one', 'run the script to convert all ADE20K training annotation images to detectron2 format', 'run the script to convert all ADE20K validation annotation images to detectron2 format', 'review the convert function that remaps ADE20K label values for detectron2 compatibility', 'summarize the prepare_ade20k_sem_seg script that converts ADE20K annotations to detectron2 format', 'run the script to convert COCO panoptic annotations to semantic segmentation annotations for train and val splits', 'create semantic segmentation annotations from panoptic segmentation annotations using a multiprocessing pool', 'process a single panoptic image to semantic segmentation using an id map and segment info', 'review the separate_coco_semantic_from_panoptic function that maps COCO categories to contiguous semantic ids', 'summarize the _process_panoptic_to_semantic function that converts RGB-encoded panoptic images to uint8 semantic masks']
```

Usage

```
{'convert_ade20k_annotation': 'convert a single ADE20K annotation image to detectron2 format by shifting pixel values by minus one', 'run_ade20k_training_conversion': 'run the script to convert all ADE20K training annotation images to detectron2 format', 'run_ade20k_validation_conversion': 'run the script to convert all ADE20K validation annotation images to detectron2 format', 'review_convert_function': 'review the convert function that remaps ADE20K label values for detectron2 compatibility', 'summarize_ade20k_prep_script': 'summarize the prepare_ade20k_sem_seg script that converts ADE20K annotations to detectron2 format'}
```

## File: facebookresearch_mask2former/datasets/prepare_coco_semantic_annos_from_panoptic_annos.py

Prompts

```
['convert a single ADE20K annotation image to detectron2 format by shifting pixel values by minus one', 'run the script to convert all ADE20K training annotation images to detectron2 format', 'run the script to convert all ADE20K validation annotation images to detectron2 format', 'review the convert function that remaps ADE20K label values for detectron2 compatibility', 'summarize the prepare_ade20k_sem_seg script that converts ADE20K annotations to detectron2 format', 'run the script to convert COCO panoptic annotations to semantic segmentation annotations for train and val splits', 'create semantic segmentation annotations from panoptic segmentation annotations using a multiprocessing pool', 'process a single panoptic image to semantic segmentation using an id map and segment info', 'review the separate_coco_semantic_from_panoptic function that maps COCO categories to contiguous semantic ids', 'summarize the _process_panoptic_to_semantic function that converts RGB-encoded panoptic images to uint8 semantic masks']
```

Usage

```
{'run_separate_coco_semantic_from_panoptic': 'run the script to convert COCO panoptic annotations to semantic segmentation annotations for train and val splits', 'create_semantic_from_panoptic': 'create semantic segmentation annotations from panoptic segmentation annotations using a multiprocessing pool', 'process_panoptic_to_semantic': 'process a single panoptic image to semantic segmentation using an id map and segment info', 'review_separate_coco_semantic_from_panoptic': 'review the separate_coco_semantic_from_panoptic function that maps COCO categories to contiguous semantic ids', 'summarize_process_panoptic_to_semantic': 'summarize the _process_panoptic_to_semantic function that converts RGB-encoded panoptic images to uint8 semantic masks'}
```

