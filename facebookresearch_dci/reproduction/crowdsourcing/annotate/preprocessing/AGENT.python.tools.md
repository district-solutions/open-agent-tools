# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/preprocessing/display_utils.py

Prompts

```
['display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor show_mask to support additional color schemes or alpha blending options', 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract one EfficientMask from another to get the difference mask', 'check if two EfficientMask objects overlap above a threshold or are near equivalent', 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold', 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor the main function to accept command line arguments for image range and model path', 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks']
```

Usage

```
{'display_all_levels': 'display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show_mask': 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show_masks': 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show_points': 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor_show_mask': 'refactor show_mask to support additional color schemes or alpha blending options'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/preprocessing/efficient_mask.py

Prompts

```
['display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor show_mask to support additional color schemes or alpha blending options', 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract one EfficientMask from another to get the difference mask', 'check if two EfficientMask objects overlap above a threshold or are near equivalent', 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold', 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor the main function to accept command line arguments for image range and model path', 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks']
```

Usage

```
{'create_EfficientMask': 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union_EfficientMask': 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect_EfficientMask': 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract_EfficientMask': 'subtract one EfficientMask from another to get the difference mask', 'check_EfficientMask_overlap': 'check if two EfficientMask objects overlap above a threshold or are near equivalent'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/preprocessing/mask_creation_utils.py

Prompts

```
['display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor show_mask to support additional color schemes or alpha blending options', 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract one EfficientMask from another to get the difference mask', 'check if two EfficientMask objects overlap above a threshold or are near equivalent', 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold', 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor the main function to accept command line arguments for image range and model path', 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks']
```

Usage

```
{'compute_group_tree': 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'get_grid': 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'get_points_from_canny_greedy': 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'process_best_largest': 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'get_groups': 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/preprocessing/preprocess_assets.py

Prompts

```
['display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor show_mask to support additional color schemes or alpha blending options', 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract one EfficientMask from another to get the difference mask', 'check if two EfficientMask objects overlap above a threshold or are near equivalent', 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold', 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor the main function to accept command line arguments for image range and model path', 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks']
```

Usage

```
{'run_main': 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold_group_tree': 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'compute_group_tree': 'compute a hierarchical mask group tree from a SAM predictor and image array with configurable thresholds', 'review_fold_group_tree': 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor_main': 'refactor the main function to accept command line arguments for image range and model path'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/preprocessing/preprocess_assets_segev.py

Prompts

```
['display all submask depth levels from a FinalGrouping tree overlaid on an image', 'show a single segmentation mask on a matplotlib axis with a fixed or random color', 'show multiple segmentation masks sorted by area on a matplotlib axis with random colors', 'show positive and negative point coordinates as green and red star markers on a matplotlib axis', 'refactor show_mask to support additional color schemes or alpha blending options', 'create an EfficientMask from a numpy ndarray mask with an associated score value', 'union two EfficientMask objects together and return a new EfficientMask with averaged score', 'intersect two EfficientMask objects and return a new EfficientMask representing their overlap', 'subtract one EfficientMask from another to get the difference mask', 'check if two EfficientMask objects overlap above a threshold or are near equivalent', 'compute a full hierarchical mask tree for an image using SAM predictor and configurable similarity thresholds', 'generate a perturbed grid of candidate points within a bounding box with configurable step size and noise', 'detect candidate points from Canny edge detection output with distance thresholding and jitter for mask generation', 'select the best scoring and largest masks from SAM multimask results per point with a penalty gap filter', 'group overlapping SAM masks into clusters by merging groups that exceed an overlap threshold', 'run the main function to preprocess a batch of images using SAM and save mask JSON files', 'fold a FinalGrouping tree into a serializable dict with base64 encoded masks and bounds', 'review the fold_group_tree function that recursively serializes mask groups to base64 PNG strings', 'refactor the main function to accept command line arguments for image range and model path', 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks']
```

Usage

```
{'run_sam_segmentation_pipeline': 'run the SAM segmentation pipeline on a batch of images and save mask JSON files', 'fold_group_tree_serialize_masks': 'fold a FinalGrouping tree into base64-encoded mask strings with bounds and area metadata', 'group_outputs_sam_results': 'group a list of SAMResult masks into hierarchical groups sorted by area using EfficientMask', 'create_sam_mask_generator': 'create a SamAutomaticMaskGenerator with custom point grids from Canny edge detection results', 'refine_and_serialize_mask_groups': 'refine grouped SAM mask outputs and serialize them to JSON with base64 PNG masks'}
```

