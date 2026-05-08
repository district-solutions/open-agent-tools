# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/common/nets/layer.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of transposed convolution layers with batch norm and ReLU from feature dimension list', 'review the make_linear_layers function to understand how it constructs linear layers with configurable batch norm and final ReLU', 'refactor the make_conv_layers function to support additional kernel sizes or stride configurations', 'build a PyTorch module to compute coordinate loss between predicted and ground truth 2D/3D coordinates with validity masking', 'build a PyTorch module to compute pose loss by converting axis-angle rotations to matrices and measuring absolute difference', 'test the CoordLoss forward pass with sample coordinate tensors, validity masks, and 3D flags', 'test the PoseLoss forward pass with axis-angle pose tensors and validity masks', 'refactor the PoseLoss to uncomment and use the axis-angle normalization approach instead of matrix conversion', 'build a PositionNet module to predict 3D hand joint coordinates from hand features using soft argmax', 'build a RotationNet module to predict MANO root pose, hand pose, shape parameters, and root translation', 'build a TransNet module to compute relative hand translation using Gaussian heatmaps and a backbone network', 'build a BoxNet module to predict left and right hand bounding box centers, sizes, and confidence scores', 'build a HandRoI module to crop, resize, and extract features from hand regions of interest using affine transforms', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'run a forward pass through the ResNetBackbone with an optional stage parameter for early or late features', 'initialize the ResNetBackbone weights from ImageNet pretrained model zoo for resnet18 or resnet50', 'review the _make_layer method that constructs ResNet blocks with optional downsampling for stride changes', 'refactor the forward method to support early stage extraction after conv1 and maxpool layers']
```

Usage

```
{'build_linear_layers': 'build a PyTorch sequential module of linear layers with optional batch norm and ReLU from feature dimension list', 'build_conv_layers': 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dimension list', 'build_deconv_layers': 'build a PyTorch sequential module of transposed convolution layers with batch norm and ReLU from feature dimension list', 'review_make_linear_layers': 'review the make_linear_layers function to understand how it constructs linear layers with configurable batch norm and final ReLU', 'refactor_make_conv_layers': 'refactor the make_conv_layers function to support additional kernel sizes or stride configurations'}
```

## File: facebookresearch_interwild/common/nets/loss.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of transposed convolution layers with batch norm and ReLU from feature dimension list', 'review the make_linear_layers function to understand how it constructs linear layers with configurable batch norm and final ReLU', 'refactor the make_conv_layers function to support additional kernel sizes or stride configurations', 'build a PyTorch module to compute coordinate loss between predicted and ground truth 2D/3D coordinates with validity masking', 'build a PyTorch module to compute pose loss by converting axis-angle rotations to matrices and measuring absolute difference', 'test the CoordLoss forward pass with sample coordinate tensors, validity masks, and 3D flags', 'test the PoseLoss forward pass with axis-angle pose tensors and validity masks', 'refactor the PoseLoss to uncomment and use the axis-angle normalization approach instead of matrix conversion', 'build a PositionNet module to predict 3D hand joint coordinates from hand features using soft argmax', 'build a RotationNet module to predict MANO root pose, hand pose, shape parameters, and root translation', 'build a TransNet module to compute relative hand translation using Gaussian heatmaps and a backbone network', 'build a BoxNet module to predict left and right hand bounding box centers, sizes, and confidence scores', 'build a HandRoI module to crop, resize, and extract features from hand regions of interest using affine transforms', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'run a forward pass through the ResNetBackbone with an optional stage parameter for early or late features', 'initialize the ResNetBackbone weights from ImageNet pretrained model zoo for resnet18 or resnet50', 'review the _make_layer method that constructs ResNet blocks with optional downsampling for stride changes', 'refactor the forward method to support early stage extraction after conv1 and maxpool layers']
```

Usage

```
{'build_CoordLoss': 'build a PyTorch module to compute coordinate loss between predicted and ground truth 2D/3D coordinates with validity masking', 'build_PoseLoss': 'build a PyTorch module to compute pose loss by converting axis-angle rotations to matrices and measuring absolute difference', 'test_CoordLoss_forward': 'test the CoordLoss forward pass with sample coordinate tensors, validity masks, and 3D flags', 'test_PoseLoss_forward': 'test the PoseLoss forward pass with axis-angle pose tensors and validity masks', 'refactor_PoseLoss': 'refactor the PoseLoss to uncomment and use the axis-angle normalization approach instead of matrix conversion'}
```

## File: facebookresearch_interwild/common/nets/module.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of transposed convolution layers with batch norm and ReLU from feature dimension list', 'review the make_linear_layers function to understand how it constructs linear layers with configurable batch norm and final ReLU', 'refactor the make_conv_layers function to support additional kernel sizes or stride configurations', 'build a PyTorch module to compute coordinate loss between predicted and ground truth 2D/3D coordinates with validity masking', 'build a PyTorch module to compute pose loss by converting axis-angle rotations to matrices and measuring absolute difference', 'test the CoordLoss forward pass with sample coordinate tensors, validity masks, and 3D flags', 'test the PoseLoss forward pass with axis-angle pose tensors and validity masks', 'refactor the PoseLoss to uncomment and use the axis-angle normalization approach instead of matrix conversion', 'build a PositionNet module to predict 3D hand joint coordinates from hand features using soft argmax', 'build a RotationNet module to predict MANO root pose, hand pose, shape parameters, and root translation', 'build a TransNet module to compute relative hand translation using Gaussian heatmaps and a backbone network', 'build a BoxNet module to predict left and right hand bounding box centers, sizes, and confidence scores', 'build a HandRoI module to crop, resize, and extract features from hand regions of interest using affine transforms', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'run a forward pass through the ResNetBackbone with an optional stage parameter for early or late features', 'initialize the ResNetBackbone weights from ImageNet pretrained model zoo for resnet18 or resnet50', 'review the _make_layer method that constructs ResNet blocks with optional downsampling for stride changes', 'refactor the forward method to support early stage extraction after conv1 and maxpool layers']
```

Usage

```
{'build_PositionNet': 'build a PositionNet module to predict 3D hand joint coordinates from hand features using soft argmax', 'build_RotationNet': 'build a RotationNet module to predict MANO root pose, hand pose, shape parameters, and root translation', 'build_TransNet': 'build a TransNet module to compute relative hand translation using Gaussian heatmaps and a backbone network', 'build_BoxNet': 'build a BoxNet module to predict left and right hand bounding box centers, sizes, and confidence scores', 'build_HandRoI': 'build a HandRoI module to crop, resize, and extract features from hand regions of interest using affine transforms'}
```

## File: facebookresearch_interwild/common/nets/resnet.py

Prompts

```
['build a PyTorch sequential module of linear layers with optional batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of 2D convolution layers with batch norm and ReLU from feature dimension list', 'build a PyTorch sequential module of transposed convolution layers with batch norm and ReLU from feature dimension list', 'review the make_linear_layers function to understand how it constructs linear layers with configurable batch norm and final ReLU', 'refactor the make_conv_layers function to support additional kernel sizes or stride configurations', 'build a PyTorch module to compute coordinate loss between predicted and ground truth 2D/3D coordinates with validity masking', 'build a PyTorch module to compute pose loss by converting axis-angle rotations to matrices and measuring absolute difference', 'test the CoordLoss forward pass with sample coordinate tensors, validity masks, and 3D flags', 'test the PoseLoss forward pass with axis-angle pose tensors and validity masks', 'refactor the PoseLoss to uncomment and use the axis-angle normalization approach instead of matrix conversion', 'build a PositionNet module to predict 3D hand joint coordinates from hand features using soft argmax', 'build a RotationNet module to predict MANO root pose, hand pose, shape parameters, and root translation', 'build a TransNet module to compute relative hand translation using Gaussian heatmaps and a backbone network', 'build a BoxNet module to predict left and right hand bounding box centers, sizes, and confidence scores', 'build a HandRoI module to crop, resize, and extract features from hand regions of interest using affine transforms', 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'run a forward pass through the ResNetBackbone with an optional stage parameter for early or late features', 'initialize the ResNetBackbone weights from ImageNet pretrained model zoo for resnet18 or resnet50', 'review the _make_layer method that constructs ResNet blocks with optional downsampling for stride changes', 'refactor the forward method to support early stage extraction after conv1 and maxpool layers']
```

Usage

```
{'build_resnet_backbone': 'build a ResNetBackbone model with a specified ResNet variant like 18, 50, or 101', 'run_forward_pass': 'run a forward pass through the ResNetBackbone with an optional stage parameter for early or late features', 'init_weights_imagenet': 'initialize the ResNetBackbone weights from ImageNet pretrained model zoo for resnet18 or resnet50', 'review_make_layer': 'review the _make_layer method that constructs ResNet blocks with optional downsampling for stride changes', 'refactor_forward_stage': 'refactor the forward method to support early stage extraction after conv1 and maxpool layers'}
```

