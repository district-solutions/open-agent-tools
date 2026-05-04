# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_batch_stats.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'use the BatchNormBatchStat forward method to apply batch norm with batch stats in inference mode', 'patch a Mask R-CNN model to use BatchNormBatchStat for box and mask head normalization', 'review the BatchNormBatchStat class that overrides forward to use F.batch_norm with training=True at inference', 'summarize the Detectron2 config that patches Mask R-CNN heads to use batch statistics during inference', 'build a multi-GPU batch shuffle that gathers tensors across GPUs and randomly permutes them for BatchNorm training', 'create a function that gathers tensors from all GPUs with padding support for uneven batch sizes', 'test the batch_unshuffle function to restore tensor order after a distributed batch shuffle operation', 'review the wrap_shuffle function that wraps a module method with batch shuffle and unshuffle during training', 'refactor the FastRCNNConvFCHead and MaskRCNNConvUpsampleHead to use batch shuffle for improved BatchNorm statistics', 'apply a sequence of modules to multiple tensors with shared BatchNorm normalization across all inputs', 'apply a sequence of non-BatchNorm modules to each input tensor independently and return results', 'create a RetinaNet head that applies shared BatchNorm normalization across classification and bounding box prediction subnets', 'forward a list of feature tensors through the shared training BN head to get logits and bbox regression outputs', 'patch the Detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training']
```

Usage

```
{'create_BatchNormBatchStat_class': 'create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'use_BatchNormBatchStat_forward': 'use the BatchNormBatchStat forward method to apply batch norm with batch stats in inference mode', 'patch_mask_rcnn_conv_norm': 'patch a Mask R-CNN model to use BatchNormBatchStat for box and mask head normalization', 'review_BatchNormBatchStat_class': 'review the BatchNormBatchStat class that overrides forward to use F.batch_norm with training=True at inference', 'summarize_mask_rcnn_BNhead_batch_stats_config': 'summarize the Detectron2 config that patches Mask R-CNN heads to use batch statistics during inference'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/Rethinking-BatchNorm/configs/mask_rcnn_BNhead_shuffle.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'use the BatchNormBatchStat forward method to apply batch norm with batch stats in inference mode', 'patch a Mask R-CNN model to use BatchNormBatchStat for box and mask head normalization', 'review the BatchNormBatchStat class that overrides forward to use F.batch_norm with training=True at inference', 'summarize the Detectron2 config that patches Mask R-CNN heads to use batch statistics during inference', 'build a multi-GPU batch shuffle that gathers tensors across GPUs and randomly permutes them for BatchNorm training', 'create a function that gathers tensors from all GPUs with padding support for uneven batch sizes', 'test the batch_unshuffle function to restore tensor order after a distributed batch shuffle operation', 'review the wrap_shuffle function that wraps a module method with batch shuffle and unshuffle during training', 'refactor the FastRCNNConvFCHead and MaskRCNNConvUpsampleHead to use batch shuffle for improved BatchNorm statistics', 'apply a sequence of modules to multiple tensors with shared BatchNorm normalization across all inputs', 'apply a sequence of non-BatchNorm modules to each input tensor independently and return results', 'create a RetinaNet head that applies shared BatchNorm normalization across classification and bounding box prediction subnets', 'forward a list of feature tensors through the shared training BN head to get logits and bbox regression outputs', 'patch the Detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training']
```

Usage

```
{'build_batch_shuffle_for_bn': 'build a multi-GPU batch shuffle that gathers tensors across GPUs and randomly permutes them for BatchNorm training', 'create_concat_all_gather': 'create a function that gathers tensors from all GPUs with padding support for uneven batch sizes', 'test_batch_unshuffle': 'test the batch_unshuffle function to restore tensor order after a distributed batch shuffle operation', 'review_wrap_shuffle': 'review the wrap_shuffle function that wraps a module method with batch shuffle and unshuffle during training', 'refactor_roi_heads_with_shuffle': 'refactor the FastRCNNConvFCHead and MaskRCNNConvUpsampleHead to use batch shuffle for improved BatchNorm statistics'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/Rethinking-BatchNorm/configs/retinanet_SyncBNhead_SharedTraining.py

Prompts

```
['create a BatchNormBatchStat layer that uses batch statistics during inference instead of running statistics', 'use the BatchNormBatchStat forward method to apply batch norm with batch stats in inference mode', 'patch a Mask R-CNN model to use BatchNormBatchStat for box and mask head normalization', 'review the BatchNormBatchStat class that overrides forward to use F.batch_norm with training=True at inference', 'summarize the Detectron2 config that patches Mask R-CNN heads to use batch statistics during inference', 'build a multi-GPU batch shuffle that gathers tensors across GPUs and randomly permutes them for BatchNorm training', 'create a function that gathers tensors from all GPUs with padding support for uneven batch sizes', 'test the batch_unshuffle function to restore tensor order after a distributed batch shuffle operation', 'review the wrap_shuffle function that wraps a module method with batch shuffle and unshuffle during training', 'refactor the FastRCNNConvFCHead and MaskRCNNConvUpsampleHead to use batch shuffle for improved BatchNorm statistics', 'apply a sequence of modules to multiple tensors with shared BatchNorm normalization across all inputs', 'apply a sequence of non-BatchNorm modules to each input tensor independently and return results', 'create a RetinaNet head that applies shared BatchNorm normalization across classification and bounding box prediction subnets', 'forward a list of feature tensors through the shared training BN head to get logits and bbox regression outputs', 'patch the Detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training']
```

Usage

```
{'apply_sequential_with_batchnorm': 'apply a sequence of modules to multiple tensors with shared BatchNorm normalization across all inputs', 'apply_sequential_non_batchnorm': 'apply a sequence of non-BatchNorm modules to each input tensor independently and return results', 'create_RetinaNetHead_SharedTrainingBN': 'create a RetinaNet head that applies shared BatchNorm normalization across classification and bounding box prediction subnets', 'forward_RetinaNetHead_SharedTrainingBN': 'forward a list of feature tensors through the shared training BN head to get logits and bbox regression outputs', 'patch_model_head_target': 'patch the Detectron2 model head target to use RetinaNetHead_SharedTrainingBN for shared BatchNorm training'}
```

