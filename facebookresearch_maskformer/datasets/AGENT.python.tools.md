# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/datasets/prepare_ade20k_full_sem_seg.py

Prompts

```
['run the script to convert ADE20K full dataset images and segmentation masks for Detectron2 training', 'load an ADE20K image and decode its RGB segmentation PNG into a class mask array', 'review the 847 ADE20K full semantic segmentation category definitions with original IDs and train IDs', 'refactor loadAde20K to support configurable resize dimensions instead of the hardcoded 512 pixel max size', 'test the loadAde20K function to verify it correctly decodes RGB segmentation masks into class ID arrays', 'run the script to convert ADE20K semantic segmentation annotations to Detectron2 format', 'run prepare_ade20k_sem_seg.py to convert training and validation annotation images for Detectron2', 'convert a single ADE20K annotation image by shifting pixel values for Detectron2 compatibility', 'review the convert function that shifts ADE20K annotation pixel values by subtracting 1', 'summarize the prepare_ade20k_sem_seg.py script that batch-converts ADE20K annotations for Detectron2']
```

Usage

```
{'run_prepare_ade20k_full_sem_seg': 'run the script to convert ADE20K full dataset images and segmentation masks for Detectron2 training', 'loadAde20K_decode_mask': 'load an ADE20K image and decode its RGB segmentation PNG into a class mask array', 'review_ADE20K_SEM_SEG_FULL_CATEGORIES': 'review the 847 ADE20K full semantic segmentation category definitions with original IDs and train IDs', 'refactor_loadAde20K_resize': 'refactor loadAde20K to support configurable resize dimensions instead of the hardcoded 512 pixel max size', 'test_loadAde20K_class_mask': 'test the loadAde20K function to verify it correctly decodes RGB segmentation masks into class ID arrays'}
```

## File: facebookresearch_maskformer/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['run the script to convert ADE20K full dataset images and segmentation masks for Detectron2 training', 'load an ADE20K image and decode its RGB segmentation PNG into a class mask array', 'review the 847 ADE20K full semantic segmentation category definitions with original IDs and train IDs', 'refactor loadAde20K to support configurable resize dimensions instead of the hardcoded 512 pixel max size', 'test the loadAde20K function to verify it correctly decodes RGB segmentation masks into class ID arrays', 'run the script to convert ADE20K semantic segmentation annotations to Detectron2 format', 'run prepare_ade20k_sem_seg.py to convert training and validation annotation images for Detectron2', 'convert a single ADE20K annotation image by shifting pixel values for Detectron2 compatibility', 'review the convert function that shifts ADE20K annotation pixel values by subtracting 1', 'summarize the prepare_ade20k_sem_seg.py script that batch-converts ADE20K annotations for Detectron2']
```

Usage

```
{'run_convert_ade20k_annotations': 'run the script to convert ADE20K semantic segmentation annotations to Detectron2 format', 'run_prepare_ade20k_sem_seg': 'run prepare_ade20k_sem_seg.py to convert training and validation annotation images for Detectron2', 'convert_ade20k_annotation': 'convert a single ADE20K annotation image by shifting pixel values for Detectron2 compatibility', 'review_convert_function': 'review the convert function that shifts ADE20K annotation pixel values by subtracting 1', 'summarize_prepare_ade20k_sem_seg': 'summarize the prepare_ade20k_sem_seg.py script that batch-converts ADE20K annotations for Detectron2'}
```

