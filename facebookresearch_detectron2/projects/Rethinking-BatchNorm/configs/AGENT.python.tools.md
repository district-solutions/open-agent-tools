# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_batch_stats.py

Prompts

```
['create a BatchNormBatchStat class that uses batch statistics during inference instead of running statistics', 'review the BatchNormBatchStat forward method to understand how it overrides standard BatchNorm2d behavior at inference time', 'refactor the BatchNormBatchStat forward method to customize the momentum or epsilon parameters for batch norm inference', 'test the BatchNormBatchStat class to verify it computes batch statistics during inference rather than using running statistics', 'summarize the mask_rcnn_BNhead_batch_stats config that patches box and mask head conv_norm with BatchNormBatchStat', 'gather tensors from all GPUs with padding support for uneven batch sizes across distributed processes', 'shuffle a tensor across all GPUs in a distributed training setup using random permutation and broadcast', 'restore the original tensor order after a cross-GPU batch shuffle using the saved unshuffle indices', 'create a wrapper class that applies batch shuffle and unshuffle around a module method during training', 'configure a Mask R-CNN model with cross-GPU batch shuffling applied to box and mask ROI heads', 'apply a sequence of modules to tensor inputs with special BatchNorm handling that normalizes all inputs together', 'create a RetinaNet head that applies shared BatchNorm training across multiple feature levels using apply_sequential', 'run the forward pass of RetinaNetHead_SharedTrainingBN to compute classification logits and bounding box regression outputs', 'configure the detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training', 'import the retinanet_SyncBNhead configuration including model, dataloader, lr_multiplier, optimizer, and train settings']
```

Usage

```
{'create_BatchNormBatchStat_class': 'create a BatchNormBatchStat class that uses batch statistics during inference instead of running statistics', 'review_BatchNormBatchStat_forward': 'review the BatchNormBatchStat forward method to understand how it overrides standard BatchNorm2d behavior at inference time', 'refactor_BatchNormBatchStat_forward': 'refactor the BatchNormBatchStat forward method to customize the momentum or epsilon parameters for batch norm inference', 'test_BatchNormBatchStat_inference': 'test the BatchNormBatchStat class to verify it computes batch statistics during inference rather than using running statistics', 'summarize_mask_rcnn_BNhead_batch_stats_config': 'summarize the mask_rcnn_BNhead_batch_stats config that patches box and mask head conv_norm with BatchNormBatchStat'}
```

## File: facebookresearch_detectron2/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_shuffle.py

Prompts

```
['create a BatchNormBatchStat class that uses batch statistics during inference instead of running statistics', 'review the BatchNormBatchStat forward method to understand how it overrides standard BatchNorm2d behavior at inference time', 'refactor the BatchNormBatchStat forward method to customize the momentum or epsilon parameters for batch norm inference', 'test the BatchNormBatchStat class to verify it computes batch statistics during inference rather than using running statistics', 'summarize the mask_rcnn_BNhead_batch_stats config that patches box and mask head conv_norm with BatchNormBatchStat', 'gather tensors from all GPUs with padding support for uneven batch sizes across distributed processes', 'shuffle a tensor across all GPUs in a distributed training setup using random permutation and broadcast', 'restore the original tensor order after a cross-GPU batch shuffle using the saved unshuffle indices', 'create a wrapper class that applies batch shuffle and unshuffle around a module method during training', 'configure a Mask R-CNN model with cross-GPU batch shuffling applied to box and mask ROI heads', 'apply a sequence of modules to tensor inputs with special BatchNorm handling that normalizes all inputs together', 'create a RetinaNet head that applies shared BatchNorm training across multiple feature levels using apply_sequential', 'run the forward pass of RetinaNetHead_SharedTrainingBN to compute classification logits and bounding box regression outputs', 'configure the detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training', 'import the retinanet_SyncBNhead configuration including model, dataloader, lr_multiplier, optimizer, and train settings']
```

Usage

```
{'concat_all_gather': 'gather tensors from all GPUs with padding support for uneven batch sizes across distributed processes', 'batch_shuffle': 'shuffle a tensor across all GPUs in a distributed training setup using random permutation and broadcast', 'batch_unshuffle': 'restore the original tensor order after a cross-GPU batch shuffle using the saved unshuffle indices', 'wrap_shuffle': 'create a wrapper class that applies batch shuffle and unshuffle around a module method during training', 'mask_rcnn_bnhead_shuffle_config': 'configure a Mask R-CNN model with cross-GPU batch shuffling applied to box and mask ROI heads'}
```

## File: facebookresearch_detectron2/projects/Rethinking-BatchNorm/configs/retinanet_SyncBNhead_SharedTraining.py

Prompts

```
['create a BatchNormBatchStat class that uses batch statistics during inference instead of running statistics', 'review the BatchNormBatchStat forward method to understand how it overrides standard BatchNorm2d behavior at inference time', 'refactor the BatchNormBatchStat forward method to customize the momentum or epsilon parameters for batch norm inference', 'test the BatchNormBatchStat class to verify it computes batch statistics during inference rather than using running statistics', 'summarize the mask_rcnn_BNhead_batch_stats config that patches box and mask head conv_norm with BatchNormBatchStat', 'gather tensors from all GPUs with padding support for uneven batch sizes across distributed processes', 'shuffle a tensor across all GPUs in a distributed training setup using random permutation and broadcast', 'restore the original tensor order after a cross-GPU batch shuffle using the saved unshuffle indices', 'create a wrapper class that applies batch shuffle and unshuffle around a module method during training', 'configure a Mask R-CNN model with cross-GPU batch shuffling applied to box and mask ROI heads', 'apply a sequence of modules to tensor inputs with special BatchNorm handling that normalizes all inputs together', 'create a RetinaNet head that applies shared BatchNorm training across multiple feature levels using apply_sequential', 'run the forward pass of RetinaNetHead_SharedTrainingBN to compute classification logits and bounding box regression outputs', 'configure the detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training', 'import the retinanet_SyncBNhead configuration including model, dataloader, lr_multiplier, optimizer, and train settings']
```

Usage

```
{'apply_sequential_with_batchnorm': 'apply a sequence of modules to tensor inputs with special BatchNorm handling that normalizes all inputs together', 'create_RetinaNetHead_SharedTrainingBN': 'create a RetinaNet head that applies shared BatchNorm training across multiple feature levels using apply_sequential', 'forward_RetinaNetHead_SharedTrainingBN': 'run the forward pass of RetinaNetHead_SharedTrainingBN to compute classification logits and bounding box regression outputs', 'configure_model_head_target': 'configure the detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training', 'import_retinanet_SyncBNhead_config': 'import the retinanet_SyncBNhead configuration including model, dataloader, lr_multiplier, optimizer, and train settings'}
```

