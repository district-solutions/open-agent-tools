# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/engine.py

Prompts

```
['train a DETA detection model for one epoch with gradient clipping and EMA updates', 'evaluate a DETA detection model on a dataset with COCO and panoptic metrics', 'refactor train_one_epoch to support a custom loss weighting scheme or scheduler', 'refactor evaluate to add test-time augmentation with horizontal flip and soft NMS', 'review the evaluate function for COCO bbox and segmentation evaluation logic', 'run test-time augmented evaluation on a detection model with multi-scale inputs and soft NMS', 'run box filtering to keep detections within a specified min and max scale range', 'test the TTA evaluation function with a detection model, dataloader, and COCO evaluator', 'test the filter_boxes function with a tensor of boxes and scale thresholds', 'refactor evaluate_tta to support configurable scale ranges instead of hardcoded SCALE_RANGES_DICT', 'train a Deformable DETR object detection model on COCO dataset with configurable backbone and transformer hyperparameters', 'evaluate a trained Deformable DETR model checkpoint on the validation set with optional test-time augmentation', 'finetune a Deformable DETR model from a pretrained checkpoint with optional class embedding reset', 'resume Deformable DETR training from a saved checkpoint restoring optimizer, scheduler, and EMA state', 'configure per-parameter learning rate groups for backbone, linear projection, and transformer parameters with ViT decay']
```

Usage

```
{'train_one_epoch': 'train a DETA detection model for one epoch with gradient clipping and EMA updates', 'evaluate': 'evaluate a DETA detection model on a dataset with COCO and panoptic metrics', 'refactor_train_one_epoch': 'refactor train_one_epoch to support a custom loss weighting scheme or scheduler', 'refactor_evaluate': 'refactor evaluate to add test-time augmentation with horizontal flip and soft NMS', 'review_evaluate': 'review the evaluate function for COCO bbox and segmentation evaluation logic'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/engine_tta.py

Prompts

```
['train a DETA detection model for one epoch with gradient clipping and EMA updates', 'evaluate a DETA detection model on a dataset with COCO and panoptic metrics', 'refactor train_one_epoch to support a custom loss weighting scheme or scheduler', 'refactor evaluate to add test-time augmentation with horizontal flip and soft NMS', 'review the evaluate function for COCO bbox and segmentation evaluation logic', 'run test-time augmented evaluation on a detection model with multi-scale inputs and soft NMS', 'run box filtering to keep detections within a specified min and max scale range', 'test the TTA evaluation function with a detection model, dataloader, and COCO evaluator', 'test the filter_boxes function with a tensor of boxes and scale thresholds', 'refactor evaluate_tta to support configurable scale ranges instead of hardcoded SCALE_RANGES_DICT', 'train a Deformable DETR object detection model on COCO dataset with configurable backbone and transformer hyperparameters', 'evaluate a trained Deformable DETR model checkpoint on the validation set with optional test-time augmentation', 'finetune a Deformable DETR model from a pretrained checkpoint with optional class embedding reset', 'resume Deformable DETR training from a saved checkpoint restoring optimizer, scheduler, and EMA state', 'configure per-parameter learning rate groups for backbone, linear projection, and transformer parameters with ViT decay']
```

Usage

```
{'run_evaluate_tta': 'run test-time augmented evaluation on a detection model with multi-scale inputs and soft NMS', 'run_filter_boxes': 'run box filtering to keep detections within a specified min and max scale range', 'test_evaluate_tta': 'test the TTA evaluation function with a detection model, dataloader, and COCO evaluator', 'test_filter_boxes': 'test the filter_boxes function with a tensor of boxes and scale thresholds', 'refactor_evaluate_tta': 'refactor evaluate_tta to support configurable scale ranges instead of hardcoded SCALE_RANGES_DICT'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/main.py

Prompts

```
['train a DETA detection model for one epoch with gradient clipping and EMA updates', 'evaluate a DETA detection model on a dataset with COCO and panoptic metrics', 'refactor train_one_epoch to support a custom loss weighting scheme or scheduler', 'refactor evaluate to add test-time augmentation with horizontal flip and soft NMS', 'review the evaluate function for COCO bbox and segmentation evaluation logic', 'run test-time augmented evaluation on a detection model with multi-scale inputs and soft NMS', 'run box filtering to keep detections within a specified min and max scale range', 'test the TTA evaluation function with a detection model, dataloader, and COCO evaluator', 'test the filter_boxes function with a tensor of boxes and scale thresholds', 'refactor evaluate_tta to support configurable scale ranges instead of hardcoded SCALE_RANGES_DICT', 'train a Deformable DETR object detection model on COCO dataset with configurable backbone and transformer hyperparameters', 'evaluate a trained Deformable DETR model checkpoint on the validation set with optional test-time augmentation', 'finetune a Deformable DETR model from a pretrained checkpoint with optional class embedding reset', 'resume Deformable DETR training from a saved checkpoint restoring optimizer, scheduler, and EMA state', 'configure per-parameter learning rate groups for backbone, linear projection, and transformer parameters with ViT decay']
```

Usage

```
{'train_deformable_detr_model': 'train a Deformable DETR object detection model on COCO dataset with configurable backbone and transformer hyperparameters', 'evaluate_detr_checkpoint': 'evaluate a trained Deformable DETR model checkpoint on the validation set with optional test-time augmentation', 'finetune_detr_from_checkpoint': 'finetune a Deformable DETR model from a pretrained checkpoint with optional class embedding reset', 'resume_detr_training': 'resume Deformable DETR training from a saved checkpoint restoring optimizer, scheduler, and EMA state', 'configure_custom_lr_schedule': 'configure per-parameter learning rate groups for backbone, linear projection, and transformer parameters with ViT decay'}
```

