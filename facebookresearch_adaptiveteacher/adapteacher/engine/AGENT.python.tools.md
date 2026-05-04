# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/engine/hooks.py

Prompts

```
['create a LossEvalHook instance with eval_period, model, data_loader, and model_output parameters', 'run the LossEvalHook after_step method to trigger periodic loss evaluation during training', 'use the inference_context manager to temporarily set a model to eval mode then restore it', 'review the LossEvalHook _get_loss method to understand loss extraction for loss_only, loss_proposal, and meanteacher modes', 'refactor the LossEvalHook _detect_anomaly method to add custom handling for infinite or NaN loss values', 'compute false positive OOD object statistics by comparing ground truth and pseudo boxes using pairwise IoU', 'compute bounding box statistics including count, size, inlier, outlier, and background ratios for ROI proposals', 'compute OOD detection accuracy and recall metrics for foreground and all samples using OOD scores', 'aggregate multiple bounding box statistics by dispatching to named metric methods via getattr on the probe instance', 'probe ROI head bounding box proposals to compute average count, size, confidence, and majority class ratio', 'build a BaselineTrainer instance from a Detectron2 config for supervised object detection training', 'build an ATeacherTrainer instance from a config for semi-supervised teacher-student object detection training', 'run the training loop on a BaselineTrainer or ATeacherTrainer with a specified start and max iteration', 'run pseudo-label generation on unlabeled data using the teacher model with configurable thresholding', 'update the teacher model weights via exponential moving average from the student model']
```

Usage

```
{'create_LossEvalHook': 'create a LossEvalHook instance with eval_period, model, data_loader, and model_output parameters', 'run_LossEvalHook_after_step': 'run the LossEvalHook after_step method to trigger periodic loss evaluation during training', 'use_inference_context': 'use the inference_context manager to temporarily set a model to eval mode then restore it', 'review_LossEvalHook_get_loss': 'review the LossEvalHook _get_loss method to understand loss extraction for loss_only, loss_proposal, and meanteacher modes', 'refactor_LossEvalHook_detect_anomaly': 'refactor the LossEvalHook _detect_anomaly method to add custom handling for infinite or NaN loss values'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/engine/probe.py

Prompts

```
['create a LossEvalHook instance with eval_period, model, data_loader, and model_output parameters', 'run the LossEvalHook after_step method to trigger periodic loss evaluation during training', 'use the inference_context manager to temporarily set a model to eval mode then restore it', 'review the LossEvalHook _get_loss method to understand loss extraction for loss_only, loss_proposal, and meanteacher modes', 'refactor the LossEvalHook _detect_anomaly method to add custom handling for infinite or NaN loss values', 'compute false positive OOD object statistics by comparing ground truth and pseudo boxes using pairwise IoU', 'compute bounding box statistics including count, size, inlier, outlier, and background ratios for ROI proposals', 'compute OOD detection accuracy and recall metrics for foreground and all samples using OOD scores', 'aggregate multiple bounding box statistics by dispatching to named metric methods via getattr on the probe instance', 'probe ROI head bounding box proposals to compute average count, size, confidence, and majority class ratio', 'build a BaselineTrainer instance from a Detectron2 config for supervised object detection training', 'build an ATeacherTrainer instance from a config for semi-supervised teacher-student object detection training', 'run the training loop on a BaselineTrainer or ATeacherTrainer with a specified start and max iteration', 'run pseudo-label generation on unlabeled data using the teacher model with configurable thresholding', 'update the teacher model weights via exponential moving average from the student model']
```

Usage

```
{'compute_fp_gtoutlier': 'compute false positive OOD object statistics by comparing ground truth and pseudo boxes using pairwise IoU', 'compute_num_box': 'compute bounding box statistics including count, size, inlier, outlier, and background ratios for ROI proposals', 'compute_ood_acc': 'compute OOD detection accuracy and recall metrics for foreground and all samples using OOD scores', 'bbox_stat': 'aggregate multiple bounding box statistics by dispatching to named metric methods via getattr on the probe instance', 'probe_roih_bbox': 'probe ROI head bounding box proposals to compute average count, size, confidence, and majority class ratio'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/engine/trainer.py

Prompts

```
['create a LossEvalHook instance with eval_period, model, data_loader, and model_output parameters', 'run the LossEvalHook after_step method to trigger periodic loss evaluation during training', 'use the inference_context manager to temporarily set a model to eval mode then restore it', 'review the LossEvalHook _get_loss method to understand loss extraction for loss_only, loss_proposal, and meanteacher modes', 'refactor the LossEvalHook _detect_anomaly method to add custom handling for infinite or NaN loss values', 'compute false positive OOD object statistics by comparing ground truth and pseudo boxes using pairwise IoU', 'compute bounding box statistics including count, size, inlier, outlier, and background ratios for ROI proposals', 'compute OOD detection accuracy and recall metrics for foreground and all samples using OOD scores', 'aggregate multiple bounding box statistics by dispatching to named metric methods via getattr on the probe instance', 'probe ROI head bounding box proposals to compute average count, size, confidence, and majority class ratio', 'build a BaselineTrainer instance from a Detectron2 config for supervised object detection training', 'build an ATeacherTrainer instance from a config for semi-supervised teacher-student object detection training', 'run the training loop on a BaselineTrainer or ATeacherTrainer with a specified start and max iteration', 'run pseudo-label generation on unlabeled data using the teacher model with configurable thresholding', 'update the teacher model weights via exponential moving average from the student model']
```

Usage

```
{'build_BaselineTrainer': 'build a BaselineTrainer instance from a Detectron2 config for supervised object detection training', 'build_ATeacherTrainer': 'build an ATeacherTrainer instance from a config for semi-supervised teacher-student object detection training', 'run_train_loop': 'run the training loop on a BaselineTrainer or ATeacherTrainer with a specified start and max iteration', 'run_pseudo_labeling': 'run pseudo-label generation on unlabeled data using the teacher model with configurable thresholding', 'update_teacher_model': 'update the teacher model weights via exponential moving average from the student model'}
```

