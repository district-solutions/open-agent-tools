# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/modeling/meta_arch/custom_rcnn.py

Prompts

```
['build a CustomRCNN model from a Detectron2 config with image labels and caption support', 'run inference on batched inputs using CustomRCNN to detect instances with postprocessing', 'run the CustomRCNN forward pass with batched inputs to compute detection losses', 'review the CustomRCNN from_config class method to extract config parameters for initialization', 'review the CustomRCNN _sync_caption_features method that gathers caption features across GPU ranks', 'build a DeformableDetr meta architecture model using a Detectron2 config with transformer parameters', 'create a CustomSetCriterion loss class with optional frequency extreme decomposition loss support', 'create a MaskedBackbone wrapper around a Detectron2 backbone that provides padding masking for NestedTensors', 'review the DeformableDetr forward pass that handles training loss computation and inference post processing', 'refactor the _max_size_loss method to compute binary cross entropy on the largest predicted box per label']
```

Usage

```
{'build_CustomRCNN': 'build a CustomRCNN model from a Detectron2 config with image labels and caption support', 'run_CustomRCNN_inference': 'run inference on batched inputs using CustomRCNN to detect instances with postprocessing', 'run_CustomRCNN_forward': 'run the CustomRCNN forward pass with batched inputs to compute detection losses', 'review_CustomRCNN_from_config': 'review the CustomRCNN from_config class method to extract config parameters for initialization', 'review_CustomRCNN_sync_caption_features': 'review the CustomRCNN _sync_caption_features method that gathers caption features across GPU ranks'}
```

## File: facebookresearch_detic/detic/modeling/meta_arch/d2_deformable_detr.py

Prompts

```
['build a CustomRCNN model from a Detectron2 config with image labels and caption support', 'run inference on batched inputs using CustomRCNN to detect instances with postprocessing', 'run the CustomRCNN forward pass with batched inputs to compute detection losses', 'review the CustomRCNN from_config class method to extract config parameters for initialization', 'review the CustomRCNN _sync_caption_features method that gathers caption features across GPU ranks', 'build a DeformableDetr meta architecture model using a Detectron2 config with transformer parameters', 'create a CustomSetCriterion loss class with optional frequency extreme decomposition loss support', 'create a MaskedBackbone wrapper around a Detectron2 backbone that provides padding masking for NestedTensors', 'review the DeformableDetr forward pass that handles training loss computation and inference post processing', 'refactor the _max_size_loss method to compute binary cross entropy on the largest predicted box per label']
```

Usage

```
{'build_deformable_detr_meta_arch': 'build a DeformableDetr meta architecture model using a Detectron2 config with transformer parameters', 'create_custom_set_criterion': 'create a CustomSetCriterion loss class with optional frequency extreme decomposition loss support', 'create_masked_backbone': 'create a MaskedBackbone wrapper around a Detectron2 backbone that provides padding masking for NestedTensors', 'review_deformable_detr_forward': 'review the DeformableDetr forward pass that handles training loss computation and inference post processing', 'refactor_max_size_loss': 'refactor the _max_size_loss method to compute binary cross entropy on the largest predicted box per label'}
```

