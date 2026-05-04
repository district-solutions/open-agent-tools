# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_batch_stats.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'build a forward pass through BatchNormBatchStat that computes batch-level mean and variance at inference time', 'test BatchNormBatchStat in training mode to verify it delegates to the parent BatchNorm2d forward method', 'refactor BatchNormBatchStat inference to use F.batch_norm with training=True for on-the-fly batch statistics', 'review the config override that patches box_head and mask_head conv_norm to use BatchNormBatchStat', 'build a distributed batch shuffle that gathers tensors from all GPUs and randomly permutes them', 'build a distributed batch unshuffle that restores tensors to their original GPU assignment after shuffling', 'build a differentiable all-gather that collects tensors from all GPUs with padding for uneven batch sizes', 'build a wrapper that adds batch shuffle and unshuffle around a module method during training', 'review the Detectron2 config that wraps FastRCNNConvFCHead and MaskRCNNConvUpsampleHead with cross-GPU batch shuffling for BatchNorm', 'apply a sequence of modules to multiple tensor inputs with shared BatchNorm normalization', 'create a RetinaNet head that applies shared BatchNorm normalization across all feature pyramid levels', 'run the forward pass of RetinaNetHead_SharedTrainingBN on a list of feature tensors to get logits and bbox predictions', 'refactor apply_sequential to support additional normalization layer types beyond BatchNorm2d and SyncBatchNorm', 'review the RetinaNetHead_SharedTrainingBN class and how it overrides the forward method to use apply_sequential']
```

Usage

```
{'create_BatchNormBatchStat_layer': 'create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'build_BatchNormBatchStat_forward': 'build a forward pass through BatchNormBatchStat that computes batch-level mean and variance at inference time', 'test_BatchNormBatchStat_training_mode': 'test BatchNormBatchStat in training mode to verify it delegates to the parent BatchNorm2d forward method', 'refactor_BatchNormBatchStat_inference': 'refactor BatchNormBatchStat inference to use F.batch_norm with training=True for on-the-fly batch statistics', 'review_BatchNormBatchStat_config_override': 'review the config override that patches box_head and mask_head conv_norm to use BatchNormBatchStat'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_shuffle.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'build a forward pass through BatchNormBatchStat that computes batch-level mean and variance at inference time', 'test BatchNormBatchStat in training mode to verify it delegates to the parent BatchNorm2d forward method', 'refactor BatchNormBatchStat inference to use F.batch_norm with training=True for on-the-fly batch statistics', 'review the config override that patches box_head and mask_head conv_norm to use BatchNormBatchStat', 'build a distributed batch shuffle that gathers tensors from all GPUs and randomly permutes them', 'build a distributed batch unshuffle that restores tensors to their original GPU assignment after shuffling', 'build a differentiable all-gather that collects tensors from all GPUs with padding for uneven batch sizes', 'build a wrapper that adds batch shuffle and unshuffle around a module method during training', 'review the Detectron2 config that wraps FastRCNNConvFCHead and MaskRCNNConvUpsampleHead with cross-GPU batch shuffling for BatchNorm', 'apply a sequence of modules to multiple tensor inputs with shared BatchNorm normalization', 'create a RetinaNet head that applies shared BatchNorm normalization across all feature pyramid levels', 'run the forward pass of RetinaNetHead_SharedTrainingBN on a list of feature tensors to get logits and bbox predictions', 'refactor apply_sequential to support additional normalization layer types beyond BatchNorm2d and SyncBatchNorm', 'review the RetinaNetHead_SharedTrainingBN class and how it overrides the forward method to use apply_sequential']
```

Usage

```
{'build_batch_shuffle': 'build a distributed batch shuffle that gathers tensors from all GPUs and randomly permutes them', 'build_batch_unshuffle': 'build a distributed batch unshuffle that restores tensors to their original GPU assignment after shuffling', 'build_concat_all_gather': 'build a differentiable all-gather that collects tensors from all GPUs with padding for uneven batch sizes', 'build_wrap_shuffle': 'build a wrapper that adds batch shuffle and unshuffle around a module method during training', 'review_mask_rcnn_BNhead_shuffle_config': 'review the Detectron2 config that wraps FastRCNNConvFCHead and MaskRCNNConvUpsampleHead with cross-GPU batch shuffling for BatchNorm'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Rethinking-BatchNorm/configs/retinanet_SyncBNhead_SharedTraining.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'build a forward pass through BatchNormBatchStat that computes batch-level mean and variance at inference time', 'test BatchNormBatchStat in training mode to verify it delegates to the parent BatchNorm2d forward method', 'refactor BatchNormBatchStat inference to use F.batch_norm with training=True for on-the-fly batch statistics', 'review the config override that patches box_head and mask_head conv_norm to use BatchNormBatchStat', 'build a distributed batch shuffle that gathers tensors from all GPUs and randomly permutes them', 'build a distributed batch unshuffle that restores tensors to their original GPU assignment after shuffling', 'build a differentiable all-gather that collects tensors from all GPUs with padding for uneven batch sizes', 'build a wrapper that adds batch shuffle and unshuffle around a module method during training', 'review the Detectron2 config that wraps FastRCNNConvFCHead and MaskRCNNConvUpsampleHead with cross-GPU batch shuffling for BatchNorm', 'apply a sequence of modules to multiple tensor inputs with shared BatchNorm normalization', 'create a RetinaNet head that applies shared BatchNorm normalization across all feature pyramid levels', 'run the forward pass of RetinaNetHead_SharedTrainingBN on a list of feature tensors to get logits and bbox predictions', 'refactor apply_sequential to support additional normalization layer types beyond BatchNorm2d and SyncBatchNorm', 'review the RetinaNetHead_SharedTrainingBN class and how it overrides the forward method to use apply_sequential']
```

Usage

```
{'apply_sequential_with_batchnorm': 'apply a sequence of modules to multiple tensor inputs with shared BatchNorm normalization', 'create_RetinaNetHead_SharedTrainingBN': 'create a RetinaNet head that applies shared BatchNorm normalization across all feature pyramid levels', 'forward_RetinaNetHead_SharedTrainingBN': 'run the forward pass of RetinaNetHead_SharedTrainingBN on a list of feature tensors to get logits and bbox predictions', 'refactor_apply_sequential': 'refactor apply_sequential to support additional normalization layer types beyond BatchNorm2d and SyncBatchNorm', 'review_RetinaNetHead_SharedTrainingBN': 'review the RetinaNetHead_SharedTrainingBN class and how it overrides the forward method to use apply_sequential'}
```

