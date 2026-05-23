# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/cnn/alexnet.py

Prompts

```
['build an AlexNet backbone model with configurable number of classes for image feature extraction', 'create an AlexNet model with a classifier head for N-class image classification tasks', 'run a forward pass through the AlexNet model on a batch of input images', 'initialize AlexNet model weights from a pretrained checkpoint file path', 'review the AlexNet convolutional feature layers and classifier sequential architecture', 'build a ResNet backbone with a specified depth like 50, 101, or 152 for feature extraction', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization for ResNet-18 or ResNet-34', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions for ResNet-50 and deeper variants', 'build a residual layer with a configurable number of blocks using make_res_layer for a ResNet stage', 'initialize ResNet weights from a pretrained checkpoint or apply Kaiming initialization to convolution layers', 'build a VGG backbone model with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolution layer with configurable input output planes and dilation rate', 'create a VGG layer with convolutions batch norm relu and max pooling blocks', 'initialize VGG model weights from a pretrained checkpoint or with kaiming normal init', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_alexnet_backbone': 'build an AlexNet backbone model with configurable number of classes for image feature extraction', 'create_alexnet_classifier': 'create an AlexNet model with a classifier head for N-class image classification tasks', 'run_alexnet_forward': 'run a forward pass through the AlexNet model on a batch of input images', 'init_alexnet_weights': 'initialize AlexNet model weights from a pretrained checkpoint file path', 'review_alexnet_architecture': 'review the AlexNet convolutional feature layers and classifier sequential architecture'}
```

## File: facebookresearch_sapiens/cv/mmcv/cnn/resnet.py

Prompts

```
['build an AlexNet backbone model with configurable number of classes for image feature extraction', 'create an AlexNet model with a classifier head for N-class image classification tasks', 'run a forward pass through the AlexNet model on a batch of input images', 'initialize AlexNet model weights from a pretrained checkpoint file path', 'review the AlexNet convolutional feature layers and classifier sequential architecture', 'build a ResNet backbone with a specified depth like 50, 101, or 152 for feature extraction', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization for ResNet-18 or ResNet-34', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions for ResNet-50 and deeper variants', 'build a residual layer with a configurable number of blocks using make_res_layer for a ResNet stage', 'initialize ResNet weights from a pretrained checkpoint or apply Kaiming initialization to convolution layers', 'build a VGG backbone model with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolution layer with configurable input output planes and dilation rate', 'create a VGG layer with convolutions batch norm relu and max pooling blocks', 'initialize VGG model weights from a pretrained checkpoint or with kaiming normal init', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_resnet_backbone': 'build a ResNet backbone with a specified depth like 50, 101, or 152 for feature extraction', 'create_basicblock_layer': 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization for ResNet-18 or ResNet-34', 'create_bottleneck_layer': 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions for ResNet-50 and deeper variants', 'build_res_layer': 'build a residual layer with a configurable number of blocks using make_res_layer for a ResNet stage', 'init_resnet_weights': 'initialize ResNet weights from a pretrained checkpoint or apply Kaiming initialization to convolution layers'}
```

## File: facebookresearch_sapiens/cv/mmcv/cnn/vgg.py

Prompts

```
['build an AlexNet backbone model with configurable number of classes for image feature extraction', 'create an AlexNet model with a classifier head for N-class image classification tasks', 'run a forward pass through the AlexNet model on a batch of input images', 'initialize AlexNet model weights from a pretrained checkpoint file path', 'review the AlexNet convolutional feature layers and classifier sequential architecture', 'build a ResNet backbone with a specified depth like 50, 101, or 152 for feature extraction', 'create a BasicBlock residual layer with two 3x3 convolutions and batch normalization for ResNet-18 or ResNet-34', 'create a Bottleneck residual layer with 1x1, 3x3, 1x1 convolutions for ResNet-50 and deeper variants', 'build a residual layer with a configurable number of blocks using make_res_layer for a ResNet stage', 'initialize ResNet weights from a pretrained checkpoint or apply Kaiming initialization to convolution layers', 'build a VGG backbone model with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolution layer with configurable input output planes and dilation rate', 'create a VGG layer with convolutions batch norm relu and max pooling blocks', 'initialize VGG model weights from a pretrained checkpoint or with kaiming normal init', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_vgg_backbone': 'build a VGG backbone model with depth 16 and batch normalization for feature extraction', 'create_conv3x3_layer': 'create a 3x3 convolution layer with configurable input output planes and dilation rate', 'create_vgg_layer': 'create a VGG layer with convolutions batch norm relu and max pooling blocks', 'init_vgg_weights': 'initialize VGG model weights from a pretrained checkpoint or with kaiming normal init', 'run_vgg_forward': 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor'}
```

