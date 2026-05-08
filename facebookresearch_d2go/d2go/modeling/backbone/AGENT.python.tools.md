# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/modeling/backbone/fbnet_cfg.py

Prompts

```
['add FBNet backbone default config options including arch, scale factor, and head settings to a CfgNode', 'add FBNet V2 backbone and VT_FPN default config options including normalization and token settings to a CfgNode', 'add BiFPN backbone default config options including depth multiplier, scale factor, and width divisor to a CfgNode', 'review the add_fbnet_default_configs function to understand FBNet detection, keypoint, and mask head config defaults', 'summarize the add_fbnet_v2_default_configs function covering FBNet V2 normalization args and VT_FPN feature pyramid settings', 'build an FBNetV2 backbone module from a detectron2 config for object detection', 'build FBNet stages for a named subpart like trunk, rpn, bbox, kpts, or mask', 'register an FBNetV2 C4 backbone in the detectron2 BACKBONE_REGISTRY for detection tasks', 'register an FBNetV2 FPN backbone with LastLevelMaxPool top block in the BACKBONE_REGISTRY', 'create an FBNetV2 RetinaNet backbone with LastLevelP6P7 top block for multi-scale detection', 'build an RPN head module that predicts classification logits and bbox regression for a list of feature tensors', 'create a Mask R-CNN 1x1 convolution predictor that outputs mask logits from input feature maps', 'create a Keypoint R-CNN predictor with transposed convolution and bilinear upsampling for keypoint heatmaps', 'create a Keypoint R-CNN predictor with transposed convolution but no additional upsampling step', 'create a Keypoint R-CNN predictor using an IRFBlock for transposed upsampling without extra interpolation']
```

Usage

```
{'add_fbnet_default_configs': 'add FBNet backbone default config options including arch, scale factor, and head settings to a CfgNode', 'add_fbnet_v2_default_configs': 'add FBNet V2 backbone and VT_FPN default config options including normalization and token settings to a CfgNode', 'add_bifpn_default_configs': 'add BiFPN backbone default config options including depth multiplier, scale factor, and width divisor to a CfgNode', 'review_add_fbnet_default_configs': 'review the add_fbnet_default_configs function to understand FBNet detection, keypoint, and mask head config defaults', 'summarize_add_fbnet_v2_default_configs': 'summarize the add_fbnet_v2_default_configs function covering FBNet V2 normalization args and VT_FPN feature pyramid settings'}
```

## File: facebookresearch_d2go/d2go/modeling/backbone/fbnet_v2.py

Prompts

```
['add FBNet backbone default config options including arch, scale factor, and head settings to a CfgNode', 'add FBNet V2 backbone and VT_FPN default config options including normalization and token settings to a CfgNode', 'add BiFPN backbone default config options including depth multiplier, scale factor, and width divisor to a CfgNode', 'review the add_fbnet_default_configs function to understand FBNet detection, keypoint, and mask head config defaults', 'summarize the add_fbnet_v2_default_configs function covering FBNet V2 normalization args and VT_FPN feature pyramid settings', 'build an FBNetV2 backbone module from a detectron2 config for object detection', 'build FBNet stages for a named subpart like trunk, rpn, bbox, kpts, or mask', 'register an FBNetV2 C4 backbone in the detectron2 BACKBONE_REGISTRY for detection tasks', 'register an FBNetV2 FPN backbone with LastLevelMaxPool top block in the BACKBONE_REGISTRY', 'create an FBNetV2 RetinaNet backbone with LastLevelP6P7 top block for multi-scale detection', 'build an RPN head module that predicts classification logits and bbox regression for a list of feature tensors', 'create a Mask R-CNN 1x1 convolution predictor that outputs mask logits from input feature maps', 'create a Keypoint R-CNN predictor with transposed convolution and bilinear upsampling for keypoint heatmaps', 'create a Keypoint R-CNN predictor with transposed convolution but no additional upsampling step', 'create a Keypoint R-CNN predictor using an IRFBlock for transposed upsampling without extra interpolation']
```

Usage

```
{'build_fbnet_backbone': 'build an FBNetV2 backbone module from a detectron2 config for object detection', 'build_fbnet_stages': 'build FBNet stages for a named subpart like trunk, rpn, bbox, kpts, or mask', 'register_fbnetv2_c4_backbone': 'register an FBNetV2 C4 backbone in the detectron2 BACKBONE_REGISTRY for detection tasks', 'register_fbnetv2_fpn_backbone': 'register an FBNetV2 FPN backbone with LastLevelMaxPool top block in the BACKBONE_REGISTRY', 'create_fbnetv2_retinanet_backbone': 'create an FBNetV2 RetinaNet backbone with LastLevelP6P7 top block for multi-scale detection'}
```

## File: facebookresearch_d2go/d2go/modeling/backbone/modules.py

Prompts

```
['add FBNet backbone default config options including arch, scale factor, and head settings to a CfgNode', 'add FBNet V2 backbone and VT_FPN default config options including normalization and token settings to a CfgNode', 'add BiFPN backbone default config options including depth multiplier, scale factor, and width divisor to a CfgNode', 'review the add_fbnet_default_configs function to understand FBNet detection, keypoint, and mask head config defaults', 'summarize the add_fbnet_v2_default_configs function covering FBNet V2 normalization args and VT_FPN feature pyramid settings', 'build an FBNetV2 backbone module from a detectron2 config for object detection', 'build FBNet stages for a named subpart like trunk, rpn, bbox, kpts, or mask', 'register an FBNetV2 C4 backbone in the detectron2 BACKBONE_REGISTRY for detection tasks', 'register an FBNetV2 FPN backbone with LastLevelMaxPool top block in the BACKBONE_REGISTRY', 'create an FBNetV2 RetinaNet backbone with LastLevelP6P7 top block for multi-scale detection', 'build an RPN head module that predicts classification logits and bbox regression for a list of feature tensors', 'create a Mask R-CNN 1x1 convolution predictor that outputs mask logits from input feature maps', 'create a Keypoint R-CNN predictor with transposed convolution and bilinear upsampling for keypoint heatmaps', 'create a Keypoint R-CNN predictor with transposed convolution but no additional upsampling step', 'create a Keypoint R-CNN predictor using an IRFBlock for transposed upsampling without extra interpolation']
```

Usage

```
{'build_RPNHeadConvRegressor': 'build an RPN head module that predicts classification logits and bbox regression for a list of feature tensors', 'create_MaskRCNNConv1x1Predictor': 'create a Mask R-CNN 1x1 convolution predictor that outputs mask logits from input feature maps', 'create_KeypointRCNNPredictor': 'create a Keypoint R-CNN predictor with transposed convolution and bilinear upsampling for keypoint heatmaps', 'create_KeypointRCNNPredictorNoUpscale': 'create a Keypoint R-CNN predictor with transposed convolution but no additional upsampling step', 'create_KeypointRCNNIRFPredictorNoUpscale': 'create a Keypoint R-CNN predictor using an IRFBlock for transposed upsampling without extra interpolation'}
```

