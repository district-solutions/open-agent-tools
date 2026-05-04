# Agent Python Tools

- repo: facebookresearch/assemblyhands-toolkit
- repo_uri: https://github.com/facebookresearch/assemblyhands-toolkit

## File: facebookresearch_assemblyhands-toolkit/src/common/nets/layer.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional final ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dims', 'build a PyTorch sequential module of 2D transposed convolution layers with batch norm and ReLU', 'build a PyTorch ResBlock module with configurable input and output feature dimensions and shortcut connections', 'build a PyTorch sequential module of bilinear interpolation upsampling followed by 2D conv layers', 'build a JointHeatmapLoss module that computes squared error loss on joint heatmap predictions with validity masking', 'create a HandTypeLoss module that computes binary cross entropy loss for hand type classification with validity masking', 'build a RelRootDepthLoss module that computes L1 loss on relative root depth predictions with validity masking', 'review the JointHeatmapLoss, HandTypeLoss, and RelRootDepthLoss classes for custom loss computation in hand pose estimation', 'refactor the JointHeatmapLoss forward method to support additional reduction options beyond per-element squared error', 'build a ResNet-based backbone network module to extract image features from input images', 'build a pose estimation network with deconvolution layers to predict 3D joint heatmaps and hand type', 'review the PoseNet soft argmax method that computes weighted coordinates from a 1D heatmap using softmax', 'test the PoseNet forward pass to verify it returns joint heatmaps, root depth, and hand type predictions', 'refactor the BackboneNet init_weights method to support custom weight initialization strategies for the ResNet backbone', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from the pretrained model zoo by calling init_weights', 'build a ResNet layer using _make_layer with a specified block type, planes, and stride', 'review the ResNetBackbone class and its supported variants including ResNet18, 34, 50, 101, and 152']
```

Usage

```
{'build_linear_layers': 'build a PyTorch sequential module of linear layers with optional final ReLU from feature dimension list', 'build_conv2d_layers': 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dims', 'build_deconv2d_layers': 'build a PyTorch sequential module of 2D transposed convolution layers with batch norm and ReLU', 'build_resblock': 'build a PyTorch ResBlock module with configurable input and output feature dimensions and shortcut connections', 'build_upsample_layers': 'build a PyTorch sequential module of bilinear interpolation upsampling followed by 2D conv layers'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/nets/loss.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional final ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dims', 'build a PyTorch sequential module of 2D transposed convolution layers with batch norm and ReLU', 'build a PyTorch ResBlock module with configurable input and output feature dimensions and shortcut connections', 'build a PyTorch sequential module of bilinear interpolation upsampling followed by 2D conv layers', 'build a JointHeatmapLoss module that computes squared error loss on joint heatmap predictions with validity masking', 'create a HandTypeLoss module that computes binary cross entropy loss for hand type classification with validity masking', 'build a RelRootDepthLoss module that computes L1 loss on relative root depth predictions with validity masking', 'review the JointHeatmapLoss, HandTypeLoss, and RelRootDepthLoss classes for custom loss computation in hand pose estimation', 'refactor the JointHeatmapLoss forward method to support additional reduction options beyond per-element squared error', 'build a ResNet-based backbone network module to extract image features from input images', 'build a pose estimation network with deconvolution layers to predict 3D joint heatmaps and hand type', 'review the PoseNet soft argmax method that computes weighted coordinates from a 1D heatmap using softmax', 'test the PoseNet forward pass to verify it returns joint heatmaps, root depth, and hand type predictions', 'refactor the BackboneNet init_weights method to support custom weight initialization strategies for the ResNet backbone', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from the pretrained model zoo by calling init_weights', 'build a ResNet layer using _make_layer with a specified block type, planes, and stride', 'review the ResNetBackbone class and its supported variants including ResNet18, 34, 50, 101, and 152']
```

Usage

```
{'build_JointHeatmapLoss': 'build a JointHeatmapLoss module that computes squared error loss on joint heatmap predictions with validity masking', 'create_HandTypeLoss': 'create a HandTypeLoss module that computes binary cross entropy loss for hand type classification with validity masking', 'build_RelRootDepthLoss': 'build a RelRootDepthLoss module that computes L1 loss on relative root depth predictions with validity masking', 'review_loss_classes': 'review the JointHeatmapLoss, HandTypeLoss, and RelRootDepthLoss classes for custom loss computation in hand pose estimation', 'refactor_JointHeatmapLoss': 'refactor the JointHeatmapLoss forward method to support additional reduction options beyond per-element squared error'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/nets/module.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional final ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dims', 'build a PyTorch sequential module of 2D transposed convolution layers with batch norm and ReLU', 'build a PyTorch ResBlock module with configurable input and output feature dimensions and shortcut connections', 'build a PyTorch sequential module of bilinear interpolation upsampling followed by 2D conv layers', 'build a JointHeatmapLoss module that computes squared error loss on joint heatmap predictions with validity masking', 'create a HandTypeLoss module that computes binary cross entropy loss for hand type classification with validity masking', 'build a RelRootDepthLoss module that computes L1 loss on relative root depth predictions with validity masking', 'review the JointHeatmapLoss, HandTypeLoss, and RelRootDepthLoss classes for custom loss computation in hand pose estimation', 'refactor the JointHeatmapLoss forward method to support additional reduction options beyond per-element squared error', 'build a ResNet-based backbone network module to extract image features from input images', 'build a pose estimation network with deconvolution layers to predict 3D joint heatmaps and hand type', 'review the PoseNet soft argmax method that computes weighted coordinates from a 1D heatmap using softmax', 'test the PoseNet forward pass to verify it returns joint heatmaps, root depth, and hand type predictions', 'refactor the BackboneNet init_weights method to support custom weight initialization strategies for the ResNet backbone', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from the pretrained model zoo by calling init_weights', 'build a ResNet layer using _make_layer with a specified block type, planes, and stride', 'review the ResNetBackbone class and its supported variants including ResNet18, 34, 50, 101, and 152']
```

Usage

```
{'build_BackboneNet': 'build a ResNet-based backbone network module to extract image features from input images', 'build_PoseNet': 'build a pose estimation network with deconvolution layers to predict 3D joint heatmaps and hand type', 'review_PoseNet_soft_argmax_1d': 'review the PoseNet soft argmax method that computes weighted coordinates from a 1D heatmap using softmax', 'test_PoseNet_forward': 'test the PoseNet forward pass to verify it returns joint heatmaps, root depth, and hand type predictions', 'refactor_BackboneNet_init_weights': 'refactor the BackboneNet init_weights method to support custom weight initialization strategies for the ResNet backbone'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/nets/resnet.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional final ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dims', 'build a PyTorch sequential module of 2D transposed convolution layers with batch norm and ReLU', 'build a PyTorch ResBlock module with configurable input and output feature dimensions and shortcut connections', 'build a PyTorch sequential module of bilinear interpolation upsampling followed by 2D conv layers', 'build a JointHeatmapLoss module that computes squared error loss on joint heatmap predictions with validity masking', 'create a HandTypeLoss module that computes binary cross entropy loss for hand type classification with validity masking', 'build a RelRootDepthLoss module that computes L1 loss on relative root depth predictions with validity masking', 'review the JointHeatmapLoss, HandTypeLoss, and RelRootDepthLoss classes for custom loss computation in hand pose estimation', 'refactor the JointHeatmapLoss forward method to support additional reduction options beyond per-element squared error', 'build a ResNet-based backbone network module to extract image features from input images', 'build a pose estimation network with deconvolution layers to predict 3D joint heatmaps and hand type', 'review the PoseNet soft argmax method that computes weighted coordinates from a 1D heatmap using softmax', 'test the PoseNet forward pass to verify it returns joint heatmaps, root depth, and hand type predictions', 'refactor the BackboneNet init_weights method to support custom weight initialization strategies for the ResNet backbone', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'initialize the ResNetBackbone weights from the pretrained model zoo by calling init_weights', 'build a ResNet layer using _make_layer with a specified block type, planes, and stride', 'review the ResNetBackbone class and its supported variants including ResNet18, 34, 50, 101, and 152']
```

Usage

```
{'build_resnet_backbone': 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'create_resnet_forward_pass': 'create a forward pass through the ResNetBackbone to extract feature maps from input images', 'init_resnet_weights': 'initialize the ResNetBackbone weights from the pretrained model zoo by calling init_weights', 'make_resnet_layer': 'build a ResNet layer using _make_layer with a specified block type, planes, and stride', 'review_resnet_architecture': 'review the ResNetBackbone class and its supported variants including ResNet18, 34, 50, 101, and 152'}
```

