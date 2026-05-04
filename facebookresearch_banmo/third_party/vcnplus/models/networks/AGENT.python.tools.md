# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/dlav0.py

Prompts

```
['build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion', 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test the exkp module forward pass by passing an image tensor through the network', 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor the residual class to add dropout or change the skip connection strategy', 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers', 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion', 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo']
```

Usage

```
{'build_pose_net': 'build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create_DLA_backbone': 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create_DLAUp_feature_pyramid': 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create_IDAUp_upsample': 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review_BottleneckX_block': 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/large_hourglass.py

Prompts

```
['build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion', 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test the exkp module forward pass by passing an image tensor through the network', 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor the residual class to add dropout or change the skip connection strategy', 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers', 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion', 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo']
```

Usage

```
{'build_large_hourglass_net': 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create_hourglassnet_model': 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test_exkp_forward': 'test the exkp module forward pass by passing an image tensor through the network', 'review_kp_module': 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor_residual_block': 'refactor the residual class to add dropout or change the skip connection strategy'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/msra_resnet.py

Prompts

```
['build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion', 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test the exkp module forward pass by passing an image tensor through the network', 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor the residual class to add dropout or change the skip connection strategy', 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers', 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion', 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo']
```

Usage

```
{'build_pose_resnet_model': 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create_basicblock_layer': 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create_bottleneck_layer': 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get_pose_net': 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init_pose_resnet_weights': 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/pose_dla_dcn.py

Prompts

```
['build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion', 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test the exkp module forward pass by passing an image tensor through the network', 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor the residual class to add dropout or change the skip connection strategy', 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers', 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion', 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo']
```

Usage

```
{'build_pose_net': 'build a DLA pose estimation network with get_pose_net specifying num_layers, heads, and down_ratio', 'create_DLA_backbone': 'create a DLA backbone model using dla34 with pretrained ImageNet weights and custom input channels', 'create_BasicBlock': 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create_Bottleneck': 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create_IDAUp': 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/resnet_dcn.py

Prompts

```
['build a DLA pose estimation network with get_pose_net using num_layers, heads dict, and down_ratio', 'create a DLA backbone model using dla34, dla60, or dla102 with pretrained ImageNet weights', 'create a DLAUp feature pyramid module that fuses multi-scale features from DLA levels', 'create an IDAUp module that projects and upsamples multi-level feature maps to a common resolution', 'review the BottleneckX class which implements grouped convolutions with configurable cardinality and expansion', 'build a large hourglass network model using get_large_hourglass_net with heads config and head_conv', 'create an HourglassNet model with a heads dictionary and optional num_stacks parameter', 'test the exkp module forward pass by passing an image tensor through the network', 'review the kp_module recursive keypoint hourglass module with up, low, and merge layers', 'refactor the residual class to add dropout or change the skip connection strategy', 'build a PoseResNet model with specified heads and head_conv for human pose estimation', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions and batch normalization', 'get a pretrained pose estimation ResNet model by layer count, heads, and head_conv config', 'init PoseResNet weights from ImageNet pretrained model and initialize deconv and head layers', 'create a BasicBlock residual block with configurable inplanes, planes, stride, and dilation parameters', 'create a Bottleneck residual block with 1x3x1 conv pattern and configurable expansion factor', 'create an IDAUp module with deformable convolutions for feature pyramid upsampling and fusion', 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo']
```

Usage

```
{'build_pose_resnet_model': 'build a PoseResNet model with deformable conv deconv layers for multi-head pose estimation', 'create_pose_net_from_resnet': 'create a pose estimation network from a pretrained ResNet backbone using get_pose_net', 'test_BasicBlock_forward': 'test the BasicBlock forward pass with residual connections and batch normalization', 'refactor_Bottleneck_expansion': 'refactor the Bottleneck class to change the expansion factor for feature channels', 'review_PoseResNet_init_weights': 'review the PoseResNet init_weights method that loads pretrained ResNet weights from model_zoo'}
```

