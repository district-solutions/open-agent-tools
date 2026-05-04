# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/backbones.py

Prompts

```
['build a DINOv2 ViT-L/14 vision transformer model pretrained on LVD-142M dataset', 'build a DINOv2 ViT-g/14 model with swiglufused FFN layer pretrained on LVD-142M', 'build a DINOv2 ViT-L/14 model with 4 register tokens and antialias interpolation', 'build a custom DINOv2 model with configurable arch, patch size, and image size via _make_dinov2_model', 'build a DINOv2 ViT-B/14 model without pretrained weights by setting pretrained to False', 'build a DINOv2 ViT-L/14 linear classifier with pretrained ImageNet-1K weights for image classification', 'build a DINOv2 ViT-g/14 linear classifier with register tokens and pretrained weights', 'create a linear classification head with configurable layers and pretrained weights from a DINOv2 model', 'create a LinearClassifierWrapper that combines a DINOv2 backbone with a linear head for classification', 'build a DINOv2 ViT-S/14 linear classifier with 1 or 4 layers for lightweight image classification', 'build a DINOv2 linear depth estimation model with pretrained weights for monocular depth prediction', 'build a DINOv2 DPT depth estimation model with pretrained weights for monocular depth prediction', 'create a ViT-Large linear depth model using dinov2_vitl14_ld with NYU or KITTI pretrained weights', 'create a ViT-Giant2 DPT depth model using dinov2_vitg14_dd for high-accuracy monocular depth estimation', 'get the min and max depth range tuple for NYU or KITTI pretrained weight configurations', 'build a DINOv2 model name string from an architecture name, patch size, and optional register token count', 'create a PyTorch CenterPadding module that pads tensor dimensions to a specified multiple', 'test the CenterPadding forward pass by padding a tensor to the nearest multiple of a given value', 'refactor the CenterPadding _get_pad method to compute left and right padding sizes for a given dimension', 'summarize the DINOv2 base URL constant used for downloading pretrained model weights']
```

Usage

```
{'build_dinov2_vitl14_model': 'build a DINOv2 ViT-L/14 vision transformer model pretrained on LVD-142M dataset', 'build_dinov2_vitg14_model': 'build a DINOv2 ViT-g/14 model with swiglufused FFN layer pretrained on LVD-142M', 'build_dinov2_vitl14_reg_model': 'build a DINOv2 ViT-L/14 model with 4 register tokens and antialias interpolation', 'build_custom_dinov2_model': 'build a custom DINOv2 model with configurable arch, patch size, and image size via _make_dinov2_model', 'build_unpretrained_dinov2_model': 'build a DINOv2 ViT-B/14 model without pretrained weights by setting pretrained to False'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/classifiers.py

Prompts

```
['build a DINOv2 ViT-L/14 vision transformer model pretrained on LVD-142M dataset', 'build a DINOv2 ViT-g/14 model with swiglufused FFN layer pretrained on LVD-142M', 'build a DINOv2 ViT-L/14 model with 4 register tokens and antialias interpolation', 'build a custom DINOv2 model with configurable arch, patch size, and image size via _make_dinov2_model', 'build a DINOv2 ViT-B/14 model without pretrained weights by setting pretrained to False', 'build a DINOv2 ViT-L/14 linear classifier with pretrained ImageNet-1K weights for image classification', 'build a DINOv2 ViT-g/14 linear classifier with register tokens and pretrained weights', 'create a linear classification head with configurable layers and pretrained weights from a DINOv2 model', 'create a LinearClassifierWrapper that combines a DINOv2 backbone with a linear head for classification', 'build a DINOv2 ViT-S/14 linear classifier with 1 or 4 layers for lightweight image classification', 'build a DINOv2 linear depth estimation model with pretrained weights for monocular depth prediction', 'build a DINOv2 DPT depth estimation model with pretrained weights for monocular depth prediction', 'create a ViT-Large linear depth model using dinov2_vitl14_ld with NYU or KITTI pretrained weights', 'create a ViT-Giant2 DPT depth model using dinov2_vitg14_dd for high-accuracy monocular depth estimation', 'get the min and max depth range tuple for NYU or KITTI pretrained weight configurations', 'build a DINOv2 model name string from an architecture name, patch size, and optional register token count', 'create a PyTorch CenterPadding module that pads tensor dimensions to a specified multiple', 'test the CenterPadding forward pass by padding a tensor to the nearest multiple of a given value', 'refactor the CenterPadding _get_pad method to compute left and right padding sizes for a given dimension', 'summarize the DINOv2 base URL constant used for downloading pretrained model weights']
```

Usage

```
{'build_dinov2_vitl14_linear_classifier': 'build a DINOv2 ViT-L/14 linear classifier with pretrained ImageNet-1K weights for image classification', 'build_dinov2_vitg14_reg_classifier': 'build a DINOv2 ViT-g/14 linear classifier with register tokens and pretrained weights', 'create_linear_classification_head': 'create a linear classification head with configurable layers and pretrained weights from a DINOv2 model', 'create_linear_classifier_wrapper': 'create a LinearClassifierWrapper that combines a DINOv2 backbone with a linear head for classification', 'build_dinov2_vits14_classifier': 'build a DINOv2 ViT-S/14 linear classifier with 1 or 4 layers for lightweight image classification'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/depthers.py

Prompts

```
['build a DINOv2 ViT-L/14 vision transformer model pretrained on LVD-142M dataset', 'build a DINOv2 ViT-g/14 model with swiglufused FFN layer pretrained on LVD-142M', 'build a DINOv2 ViT-L/14 model with 4 register tokens and antialias interpolation', 'build a custom DINOv2 model with configurable arch, patch size, and image size via _make_dinov2_model', 'build a DINOv2 ViT-B/14 model without pretrained weights by setting pretrained to False', 'build a DINOv2 ViT-L/14 linear classifier with pretrained ImageNet-1K weights for image classification', 'build a DINOv2 ViT-g/14 linear classifier with register tokens and pretrained weights', 'create a linear classification head with configurable layers and pretrained weights from a DINOv2 model', 'create a LinearClassifierWrapper that combines a DINOv2 backbone with a linear head for classification', 'build a DINOv2 ViT-S/14 linear classifier with 1 or 4 layers for lightweight image classification', 'build a DINOv2 linear depth estimation model with pretrained weights for monocular depth prediction', 'build a DINOv2 DPT depth estimation model with pretrained weights for monocular depth prediction', 'create a ViT-Large linear depth model using dinov2_vitl14_ld with NYU or KITTI pretrained weights', 'create a ViT-Giant2 DPT depth model using dinov2_vitg14_dd for high-accuracy monocular depth estimation', 'get the min and max depth range tuple for NYU or KITTI pretrained weight configurations', 'build a DINOv2 model name string from an architecture name, patch size, and optional register token count', 'create a PyTorch CenterPadding module that pads tensor dimensions to a specified multiple', 'test the CenterPadding forward pass by padding a tensor to the nearest multiple of a given value', 'refactor the CenterPadding _get_pad method to compute left and right padding sizes for a given dimension', 'summarize the DINOv2 base URL constant used for downloading pretrained model weights']
```

Usage

```
{'build_dinov2_linear_depther': 'build a DINOv2 linear depth estimation model with pretrained weights for monocular depth prediction', 'build_dinov2_dpt_depther': 'build a DINOv2 DPT depth estimation model with pretrained weights for monocular depth prediction', 'create_vit_large_linear_depther': 'create a ViT-Large linear depth model using dinov2_vitl14_ld with NYU or KITTI pretrained weights', 'create_vit_giant_dpt_depther': 'create a ViT-Giant2 DPT depth model using dinov2_vitg14_dd for high-accuracy monocular depth estimation', 'get_depth_range_for_weights': 'get the min and max depth range tuple for NYU or KITTI pretrained weight configurations'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/hub/utils.py

Prompts

```
['build a DINOv2 ViT-L/14 vision transformer model pretrained on LVD-142M dataset', 'build a DINOv2 ViT-g/14 model with swiglufused FFN layer pretrained on LVD-142M', 'build a DINOv2 ViT-L/14 model with 4 register tokens and antialias interpolation', 'build a custom DINOv2 model with configurable arch, patch size, and image size via _make_dinov2_model', 'build a DINOv2 ViT-B/14 model without pretrained weights by setting pretrained to False', 'build a DINOv2 ViT-L/14 linear classifier with pretrained ImageNet-1K weights for image classification', 'build a DINOv2 ViT-g/14 linear classifier with register tokens and pretrained weights', 'create a linear classification head with configurable layers and pretrained weights from a DINOv2 model', 'create a LinearClassifierWrapper that combines a DINOv2 backbone with a linear head for classification', 'build a DINOv2 ViT-S/14 linear classifier with 1 or 4 layers for lightweight image classification', 'build a DINOv2 linear depth estimation model with pretrained weights for monocular depth prediction', 'build a DINOv2 DPT depth estimation model with pretrained weights for monocular depth prediction', 'create a ViT-Large linear depth model using dinov2_vitl14_ld with NYU or KITTI pretrained weights', 'create a ViT-Giant2 DPT depth model using dinov2_vitg14_dd for high-accuracy monocular depth estimation', 'get the min and max depth range tuple for NYU or KITTI pretrained weight configurations', 'build a DINOv2 model name string from an architecture name, patch size, and optional register token count', 'create a PyTorch CenterPadding module that pads tensor dimensions to a specified multiple', 'test the CenterPadding forward pass by padding a tensor to the nearest multiple of a given value', 'refactor the CenterPadding _get_pad method to compute left and right padding sizes for a given dimension', 'summarize the DINOv2 base URL constant used for downloading pretrained model weights']
```

Usage

```
{'build_dinov2_model_name': 'build a DINOv2 model name string from an architecture name, patch size, and optional register token count', 'create_center_padding_module': 'create a PyTorch CenterPadding module that pads tensor dimensions to a specified multiple', 'test_center_padding_forward': 'test the CenterPadding forward pass by padding a tensor to the nearest multiple of a given value', 'refactor_center_padding_get_pad': 'refactor the CenterPadding _get_pad method to compute left and right padding sizes for a given dimension', 'summarize_dinov2_base_url': 'summarize the DINOv2 base URL constant used for downloading pretrained model weights'}
```

