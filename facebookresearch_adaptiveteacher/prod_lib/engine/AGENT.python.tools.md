# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/prod_lib/engine/probe.py

Prompts

```
['initialize an OpenMatchTrainerProbe with a Detectron2 config to set BOX_AP and NUM_CLASSES', 'run bbox_stat to compute multiple bounding box metrics across unlabeled ground truth and pseudo labels', 'compute false positive and OOD ground-truth outlier statistics for predicted or pseudo bounding boxes', 'compute bounding box count, average size, inlier, outlier, and confidence statistics for ROI predictions', 'compute OOD detection accuracy and recall for foreground and all bounding boxes using pairwise IoU', 'run a single training step of the DAobjTrainer for teacher-student mutual learning', 'run the burn-in stage to supervisedly train the student model with labeled data', 'run teacher-student mutual learning with labeled and unlabeled data using pseudo-labels', 'review the weight_losses method to understand how supervised and unsupervised losses are weighted', 'review the threshold_bbox method to understand how proposals are filtered by confidence thresholds']
```

Usage

```
{'init_OpenMatchTrainerProbe': 'initialize an OpenMatchTrainerProbe with a Detectron2 config to set BOX_AP and NUM_CLASSES', 'run_bbox_stat': 'run bbox_stat to compute multiple bounding box metrics across unlabeled ground truth and pseudo labels', 'compute_fp_gtoutlier': 'compute false positive and OOD ground-truth outlier statistics for predicted or pseudo bounding boxes', 'compute_num_box': 'compute bounding box count, average size, inlier, outlier, and confidence statistics for ROI predictions', 'compute_ood_acc': 'compute OOD detection accuracy and recall for foreground and all bounding boxes using pairwise IoU'}
```

## File: facebookresearch_adaptiveteacher/prod_lib/engine/trainer.py

Prompts

```
['initialize an OpenMatchTrainerProbe with a Detectron2 config to set BOX_AP and NUM_CLASSES', 'run bbox_stat to compute multiple bounding box metrics across unlabeled ground truth and pseudo labels', 'compute false positive and OOD ground-truth outlier statistics for predicted or pseudo bounding boxes', 'compute bounding box count, average size, inlier, outlier, and confidence statistics for ROI predictions', 'compute OOD detection accuracy and recall for foreground and all bounding boxes using pairwise IoU', 'run a single training step of the DAobjTrainer for teacher-student mutual learning', 'run the burn-in stage to supervisedly train the student model with labeled data', 'run teacher-student mutual learning with labeled and unlabeled data using pseudo-labels', 'review the weight_losses method to understand how supervised and unsupervised losses are weighted', 'review the threshold_bbox method to understand how proposals are filtered by confidence thresholds']
```

Usage

```
{'run_DAobjTrainer_step': 'run a single training step of the DAobjTrainer for teacher-student mutual learning', 'run_DAobjTrainer_burn_in': 'run the burn-in stage to supervisedly train the student model with labeled data', 'run_DAobjTrainer_teacher_student_learning': 'run teacher-student mutual learning with labeled and unlabeled data using pseudo-labels', 'review_DAobjTrainer_weight_losses': 'review the weight_losses method to understand how supervised and unsupervised losses are weighted', 'review_DAobjTrainer_threshold_bbox': 'review the threshold_bbox method to understand how proposals are filtered by confidence thresholds'}
```

