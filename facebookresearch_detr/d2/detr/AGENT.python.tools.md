# Agent Python Tools

- repo: facebookresearch/detr
- repo_uri: https://github.com/facebookresearch/detr.git

## File: facebookresearch_detr/d2/detr/config.py

Prompts

```
['add DETR config fields to a Detectron2 CfgNode including loss weights and transformer hyperparameters', 'review the add_detr_config function to understand which DETR model parameters it registers on the config node', 'summarize the add_detr_config function and list all DETR config fields it sets with default values', 'refactor add_detr_config to make GIOU_WEIGHT and L1_WEIGHT configurable via command-line arguments', 'refactor add_detr_config to expose NHEADS ENC_LAYERS and DEC_LAYERS as tunable parameters', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with a config to map Detectron2 dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and prepare an image and annotations', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation strategy during training', 'build a DETR object detection model with a Detectron2 config and transformer backbone', 'run DETR inference on batched inputs to get predicted boxes, scores, and class labels', 'create a MaskedBackbone wrapper that builds a Detectron2 backbone with padding mask support', 'review the Detr forward method to understand training loss computation and inference output processing', 'refactor the Detr prepare_targets method to normalize ground truth boxes and convert polygon masks']
```

Usage

```
{'add_detr_config_to_cfg': 'add DETR config fields to a Detectron2 CfgNode including loss weights and transformer hyperparameters', 'review_add_detr_config': 'review the add_detr_config function to understand which DETR model parameters it registers on the config node', 'summarize_add_detr_config': 'summarize the add_detr_config function and list all DETR config fields it sets with default values', 'refactor_add_detr_config_loss_weights': 'refactor add_detr_config to make GIOU_WEIGHT and L1_WEIGHT configurable via command-line arguments', 'refactor_add_detr_config_transformer': 'refactor add_detr_config to expose NHEADS ENC_LAYERS and DEC_LAYERS as tunable parameters'}
```

## File: facebookresearch_detr/d2/detr/dataset_mapper.py

Prompts

```
['add DETR config fields to a Detectron2 CfgNode including loss weights and transformer hyperparameters', 'review the add_detr_config function to understand which DETR model parameters it registers on the config node', 'summarize the add_detr_config function and list all DETR config fields it sets with default values', 'refactor add_detr_config to make GIOU_WEIGHT and L1_WEIGHT configurable via command-line arguments', 'refactor add_detr_config to expose NHEADS ENC_LAYERS and DEC_LAYERS as tunable parameters', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with a config to map Detectron2 dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and prepare an image and annotations', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation strategy during training', 'build a DETR object detection model with a Detectron2 config and transformer backbone', 'run DETR inference on batched inputs to get predicted boxes, scores, and class labels', 'create a MaskedBackbone wrapper that builds a Detectron2 backbone with padding mask support', 'review the Detr forward method to understand training loss computation and inference output processing', 'refactor the Detr prepare_targets method to normalize ground truth boxes and convert polygon masks']
```

Usage

```
{'build_transform_gen': 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create_DetrDatasetMapper': 'create a DetrDatasetMapper instance with a config to map Detectron2 dataset dicts for DETR', 'call_DetrDatasetMapper': 'call the DetrDatasetMapper on a dataset dict to read, transform, and prepare an image and annotations', 'review_DetrDatasetMapper_call': 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor_DetrDatasetMapper_crop': 'refactor the DetrDatasetMapper to customize the random crop generation strategy during training'}
```

## File: facebookresearch_detr/d2/detr/detr.py

Prompts

```
['add DETR config fields to a Detectron2 CfgNode including loss weights and transformer hyperparameters', 'review the add_detr_config function to understand which DETR model parameters it registers on the config node', 'summarize the add_detr_config function and list all DETR config fields it sets with default values', 'refactor add_detr_config to make GIOU_WEIGHT and L1_WEIGHT configurable via command-line arguments', 'refactor add_detr_config to expose NHEADS ENC_LAYERS and DEC_LAYERS as tunable parameters', 'build a list of TransformGen objects from a Detectron2 config for training or inference', 'create a DetrDatasetMapper instance with a config to map Detectron2 dataset dicts for DETR', 'call the DetrDatasetMapper on a dataset dict to read, transform, and prepare an image and annotations', 'review the DetrDatasetMapper __call__ method to understand image reading, cropping, and annotation transformation logic', 'refactor the DetrDatasetMapper to customize the random crop generation strategy during training', 'build a DETR object detection model with a Detectron2 config and transformer backbone', 'run DETR inference on batched inputs to get predicted boxes, scores, and class labels', 'create a MaskedBackbone wrapper that builds a Detectron2 backbone with padding mask support', 'review the Detr forward method to understand training loss computation and inference output processing', 'refactor the Detr prepare_targets method to normalize ground truth boxes and convert polygon masks']
```

Usage

```
{'build_DETR_model': 'build a DETR object detection model with a Detectron2 config and transformer backbone', 'run_DETR_inference': 'run DETR inference on batched inputs to get predicted boxes, scores, and class labels', 'create_MaskedBackbone': 'create a MaskedBackbone wrapper that builds a Detectron2 backbone with padding mask support', 'review_Detr_forward': 'review the Detr forward method to understand training loss computation and inference output processing', 'refactor_Detr_prepare_targets': 'refactor the Detr prepare_targets method to normalize ground truth boxes and convert polygon masks'}
```

