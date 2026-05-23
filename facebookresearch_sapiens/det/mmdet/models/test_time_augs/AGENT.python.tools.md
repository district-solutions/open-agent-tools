# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/test_time_augs/det_tta.py

Prompts

```
['build a python module to create a DetTTAModel for merging augmented detection results with NMS configuration', 'create a function to merge augmented detection bounding boxes and scores from multiple image views', 'test the DetTTAModel merge_preds method to merge batch predictions of enhanced detection data', 'refactor the DetTTAModel _merge_single_sample method to support instance segmentation TTA processing', 'review the DetTTAModel class initialization and tta_cfg configuration for detection test time augmentation', 'merge augmented RPN proposals from multiscale and flip test-time augmentations using NMS and score sorting', 'merge augmented detection bounding boxes and scores by mapping back to original image scale and averaging', 'merge augmented InstanceData detection results across multiple test-time augmentations for a batch of images', 'merge augmented bounding box scores by computing the mean across all augmentation variants', 'merge augmented mask predictions with optional flip handling and weighted averaging across augmentation variants']
```

Usage

```
{'build_DetTTAModel': 'build a python module to create a DetTTAModel for merging augmented detection results with NMS configuration', 'create_merge_aug_bboxes': 'create a function to merge augmented detection bounding boxes and scores from multiple image views', 'test_merge_preds': 'test the DetTTAModel merge_preds method to merge batch predictions of enhanced detection data', 'refactor_merge_single_sample': 'refactor the DetTTAModel _merge_single_sample method to support instance segmentation TTA processing', 'review_DetTTAModel_init': 'review the DetTTAModel class initialization and tta_cfg configuration for detection test time augmentation'}
```

## File: facebookresearch_sapiens/det/mmdet/models/test_time_augs/merge_augs.py

Prompts

```
['build a python module to create a DetTTAModel for merging augmented detection results with NMS configuration', 'create a function to merge augmented detection bounding boxes and scores from multiple image views', 'test the DetTTAModel merge_preds method to merge batch predictions of enhanced detection data', 'refactor the DetTTAModel _merge_single_sample method to support instance segmentation TTA processing', 'review the DetTTAModel class initialization and tta_cfg configuration for detection test time augmentation', 'merge augmented RPN proposals from multiscale and flip test-time augmentations using NMS and score sorting', 'merge augmented detection bounding boxes and scores by mapping back to original image scale and averaging', 'merge augmented InstanceData detection results across multiple test-time augmentations for a batch of images', 'merge augmented bounding box scores by computing the mean across all augmentation variants', 'merge augmented mask predictions with optional flip handling and weighted averaging across augmentation variants']
```

Usage

```
{'merge_aug_proposals': 'merge augmented RPN proposals from multiscale and flip test-time augmentations using NMS and score sorting', 'merge_aug_bboxes': 'merge augmented detection bounding boxes and scores by mapping back to original image scale and averaging', 'merge_aug_results': 'merge augmented InstanceData detection results across multiple test-time augmentations for a batch of images', 'merge_aug_scores': 'merge augmented bounding box scores by computing the mean across all augmentation variants', 'merge_aug_masks': 'merge augmented mask predictions with optional flip handling and weighted averaging across augmentation variants'}
```

