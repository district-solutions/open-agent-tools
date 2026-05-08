# Agent Python Tools

- repo: facebookresearch/interhand2.6m
- repo_uri: https://github.com/facebookresearch/interhand2.6m

## File: facebookresearch_interhand2.6m/common/nets/layer.py

Prompts

```
['build a sequential linear layer stack from a list of feature dimensions with optional final ReLU', 'build a sequential 2D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a sequential 2D transposed convolution (deconv) upsampling layer stack with batch norm and ReLU', 'build a ResBlock module with residual connections and optional 1x1 shortcut conv for dimension mismatch', 'build a sequential 3D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a JointHeatmapLoss module that computes masked MSE loss between predicted and ground truth joint heatmaps', 'create a HandTypeLoss module that computes masked binary cross-entropy loss for hand type classification', 'create a RelRootDepthLoss module that computes masked L1 loss between predicted and ground truth root depth values', 'review the JointHeatmapLoss forward method to understand its masked squared error computation on joint heatmaps', 'refactor the JointHeatmapLoss class to fix the __ini__ typo in its constructor to __init__', 'build a BackboneNet module that extracts image features using a ResNet backbone network', 'build a PoseNet module that predicts 3D joint heatmaps, root depth, and hand type from image features', 'test the PoseNet soft_argmax_1d method to compute softmax-weighted coordinates from a 1D heatmap', 'review the PoseNet forward pass that produces joint heatmaps, root depth, and hand classification', 'refactor the BackboneNet init_weights method to initialize ResNet backbone weights for training', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from a pretrained model zoo checkpoint', 'review the ResNetBackbone _make_layer method that constructs residual blocks with optional downsampling', 'summarize the ResNetBackbone resnet_spec dictionary that maps variant types to block, layers, and channel configs']
```

Usage

```
{'build_linear_layers': 'build a sequential linear layer stack from a list of feature dimensions with optional final ReLU', 'build_conv2d_layers': 'build a sequential 2D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build_deconv_layers': 'build a sequential 2D transposed convolution (deconv) upsampling layer stack with batch norm and ReLU', 'build_resblock': 'build a ResBlock module with residual connections and optional 1x1 shortcut conv for dimension mismatch', 'build_conv3d_layers': 'build a sequential 3D convolutional layer stack with batch norm and ReLU from feature dimensions'}
```

## File: facebookresearch_interhand2.6m/common/nets/loss.py

Prompts

```
['build a sequential linear layer stack from a list of feature dimensions with optional final ReLU', 'build a sequential 2D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a sequential 2D transposed convolution (deconv) upsampling layer stack with batch norm and ReLU', 'build a ResBlock module with residual connections and optional 1x1 shortcut conv for dimension mismatch', 'build a sequential 3D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a JointHeatmapLoss module that computes masked MSE loss between predicted and ground truth joint heatmaps', 'create a HandTypeLoss module that computes masked binary cross-entropy loss for hand type classification', 'create a RelRootDepthLoss module that computes masked L1 loss between predicted and ground truth root depth values', 'review the JointHeatmapLoss forward method to understand its masked squared error computation on joint heatmaps', 'refactor the JointHeatmapLoss class to fix the __ini__ typo in its constructor to __init__', 'build a BackboneNet module that extracts image features using a ResNet backbone network', 'build a PoseNet module that predicts 3D joint heatmaps, root depth, and hand type from image features', 'test the PoseNet soft_argmax_1d method to compute softmax-weighted coordinates from a 1D heatmap', 'review the PoseNet forward pass that produces joint heatmaps, root depth, and hand classification', 'refactor the BackboneNet init_weights method to initialize ResNet backbone weights for training', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from a pretrained model zoo checkpoint', 'review the ResNetBackbone _make_layer method that constructs residual blocks with optional downsampling', 'summarize the ResNetBackbone resnet_spec dictionary that maps variant types to block, layers, and channel configs']
```

Usage

```
{'build_joint_heatmap_loss': 'build a JointHeatmapLoss module that computes masked MSE loss between predicted and ground truth joint heatmaps', 'create_hand_type_loss': 'create a HandTypeLoss module that computes masked binary cross-entropy loss for hand type classification', 'create_rel_root_depth_loss': 'create a RelRootDepthLoss module that computes masked L1 loss between predicted and ground truth root depth values', 'review_JointHeatmapLoss_forward': 'review the JointHeatmapLoss forward method to understand its masked squared error computation on joint heatmaps', 'refactor_JointHeatmapLoss_init': 'refactor the JointHeatmapLoss class to fix the __ini__ typo in its constructor to __init__'}
```

## File: facebookresearch_interhand2.6m/common/nets/module.py

Prompts

```
['build a sequential linear layer stack from a list of feature dimensions with optional final ReLU', 'build a sequential 2D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a sequential 2D transposed convolution (deconv) upsampling layer stack with batch norm and ReLU', 'build a ResBlock module with residual connections and optional 1x1 shortcut conv for dimension mismatch', 'build a sequential 3D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a JointHeatmapLoss module that computes masked MSE loss between predicted and ground truth joint heatmaps', 'create a HandTypeLoss module that computes masked binary cross-entropy loss for hand type classification', 'create a RelRootDepthLoss module that computes masked L1 loss between predicted and ground truth root depth values', 'review the JointHeatmapLoss forward method to understand its masked squared error computation on joint heatmaps', 'refactor the JointHeatmapLoss class to fix the __ini__ typo in its constructor to __init__', 'build a BackboneNet module that extracts image features using a ResNet backbone network', 'build a PoseNet module that predicts 3D joint heatmaps, root depth, and hand type from image features', 'test the PoseNet soft_argmax_1d method to compute softmax-weighted coordinates from a 1D heatmap', 'review the PoseNet forward pass that produces joint heatmaps, root depth, and hand classification', 'refactor the BackboneNet init_weights method to initialize ResNet backbone weights for training', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from a pretrained model zoo checkpoint', 'review the ResNetBackbone _make_layer method that constructs residual blocks with optional downsampling', 'summarize the ResNetBackbone resnet_spec dictionary that maps variant types to block, layers, and channel configs']
```

Usage

```
{'build_BackboneNet': 'build a BackboneNet module that extracts image features using a ResNet backbone network', 'build_PoseNet': 'build a PoseNet module that predicts 3D joint heatmaps, root depth, and hand type from image features', 'test_PoseNet_soft_argmax_1d': 'test the PoseNet soft_argmax_1d method to compute softmax-weighted coordinates from a 1D heatmap', 'review_PoseNet_forward': 'review the PoseNet forward pass that produces joint heatmaps, root depth, and hand classification', 'refactor_BackboneNet_init_weights': 'refactor the BackboneNet init_weights method to initialize ResNet backbone weights for training'}
```

## File: facebookresearch_interhand2.6m/common/nets/resnet.py

Prompts

```
['build a sequential linear layer stack from a list of feature dimensions with optional final ReLU', 'build a sequential 2D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a sequential 2D transposed convolution (deconv) upsampling layer stack with batch norm and ReLU', 'build a ResBlock module with residual connections and optional 1x1 shortcut conv for dimension mismatch', 'build a sequential 3D convolutional layer stack with batch norm and ReLU from feature dimensions', 'build a JointHeatmapLoss module that computes masked MSE loss between predicted and ground truth joint heatmaps', 'create a HandTypeLoss module that computes masked binary cross-entropy loss for hand type classification', 'create a RelRootDepthLoss module that computes masked L1 loss between predicted and ground truth root depth values', 'review the JointHeatmapLoss forward method to understand its masked squared error computation on joint heatmaps', 'refactor the JointHeatmapLoss class to fix the __ini__ typo in its constructor to __init__', 'build a BackboneNet module that extracts image features using a ResNet backbone network', 'build a PoseNet module that predicts 3D joint heatmaps, root depth, and hand type from image features', 'test the PoseNet soft_argmax_1d method to compute softmax-weighted coordinates from a 1D heatmap', 'review the PoseNet forward pass that produces joint heatmaps, root depth, and hand classification', 'refactor the BackboneNet init_weights method to initialize ResNet backbone weights for training', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from a pretrained model zoo checkpoint', 'review the ResNetBackbone _make_layer method that constructs residual blocks with optional downsampling', 'summarize the ResNetBackbone resnet_spec dictionary that maps variant types to block, layers, and channel configs']
```

Usage

```
{'build_resnet_backbone': 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create_resnet_forward_pass': 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'init_resnet_weights': 'initialize the ResNetBackbone weights from a pretrained model zoo checkpoint', 'review_resnet_make_layer': 'review the ResNetBackbone _make_layer method that constructs residual blocks with optional downsampling', 'summarize_resnet_spec': 'summarize the ResNetBackbone resnet_spec dictionary that maps variant types to block, layers, and channel configs'}
```

