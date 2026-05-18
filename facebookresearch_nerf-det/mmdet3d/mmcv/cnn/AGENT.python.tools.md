# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/alexnet.py

Prompts

```
['build an AlexNet backbone model with configurable num_classes for feature extraction or classification', 'create an AlexNet model with a classifier head by setting num_classes to a positive integer', 'run a forward pass through the AlexNet features module on a torch tensor input', 'initialize AlexNet model weights from a pretrained checkpoint file path or use default initialization', 'review the AlexNet convolutional feature layers and optional classifier sequential layers', 'build a PyTorch model from a single config dict using the MODELS registry', 'build a Sequential module from a list of config dicts using build_model_from_cfg', 'build a model from config dict with default arguments using build_model_from_cfg', 'review the MODELS Registry instance and its build_func configuration for model building', 'test build_model_from_cfg with both dict and list config inputs', 'build a ResNet backbone with depth 50 using Bottleneck blocks and pytorch style', 'create a BasicBlock layer with 64 input planes and 128 output planes for feature extraction', 'create a Bottleneck layer with gradient checkpointing enabled to save memory during training', 'make a residual layer with 3 Bottleneck blocks and stride 2 for downsampling', 'freeze the first 2 stages of a ResNet backbone to prevent gradient updates during fine-tuning', 'build a VGG backbone network with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolutional layer with configurable input output planes and dilation rate', 'create a VGG layer block with convolutions relu and max pooling for a given stage', 'initialize VGG backbone weights using pretrained checkpoint or kaiming normal initialization', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_alexnet_backbone': 'build an AlexNet backbone model with configurable num_classes for feature extraction or classification', 'create_alexnet_classifier': 'create an AlexNet model with a classifier head by setting num_classes to a positive integer', 'run_alexnet_forward': 'run a forward pass through the AlexNet features module on a torch tensor input', 'init_alexnet_weights': 'initialize AlexNet model weights from a pretrained checkpoint file path or use default initialization', 'review_alexnet_architecture': 'review the AlexNet convolutional feature layers and optional classifier sequential layers'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/builder.py

Prompts

```
['build an AlexNet backbone model with configurable num_classes for feature extraction or classification', 'create an AlexNet model with a classifier head by setting num_classes to a positive integer', 'run a forward pass through the AlexNet features module on a torch tensor input', 'initialize AlexNet model weights from a pretrained checkpoint file path or use default initialization', 'review the AlexNet convolutional feature layers and optional classifier sequential layers', 'build a PyTorch model from a single config dict using the MODELS registry', 'build a Sequential module from a list of config dicts using build_model_from_cfg', 'build a model from config dict with default arguments using build_model_from_cfg', 'review the MODELS Registry instance and its build_func configuration for model building', 'test build_model_from_cfg with both dict and list config inputs', 'build a ResNet backbone with depth 50 using Bottleneck blocks and pytorch style', 'create a BasicBlock layer with 64 input planes and 128 output planes for feature extraction', 'create a Bottleneck layer with gradient checkpointing enabled to save memory during training', 'make a residual layer with 3 Bottleneck blocks and stride 2 for downsampling', 'freeze the first 2 stages of a ResNet backbone to prevent gradient updates during fine-tuning', 'build a VGG backbone network with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolutional layer with configurable input output planes and dilation rate', 'create a VGG layer block with convolutions relu and max pooling for a given stage', 'initialize VGG backbone weights using pretrained checkpoint or kaiming normal initialization', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_model_from_cfg_single': 'build a PyTorch model from a single config dict using the MODELS registry', 'build_model_from_cfg_sequential': 'build a Sequential module from a list of config dicts using build_model_from_cfg', 'build_model_from_cfg_with_defaults': 'build a model from config dict with default arguments using build_model_from_cfg', 'review_MODELS_registry': 'review the MODELS Registry instance and its build_func configuration for model building', 'test_build_model_from_cfg': 'test build_model_from_cfg with both dict and list config inputs'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/resnet.py

Prompts

```
['build an AlexNet backbone model with configurable num_classes for feature extraction or classification', 'create an AlexNet model with a classifier head by setting num_classes to a positive integer', 'run a forward pass through the AlexNet features module on a torch tensor input', 'initialize AlexNet model weights from a pretrained checkpoint file path or use default initialization', 'review the AlexNet convolutional feature layers and optional classifier sequential layers', 'build a PyTorch model from a single config dict using the MODELS registry', 'build a Sequential module from a list of config dicts using build_model_from_cfg', 'build a model from config dict with default arguments using build_model_from_cfg', 'review the MODELS Registry instance and its build_func configuration for model building', 'test build_model_from_cfg with both dict and list config inputs', 'build a ResNet backbone with depth 50 using Bottleneck blocks and pytorch style', 'create a BasicBlock layer with 64 input planes and 128 output planes for feature extraction', 'create a Bottleneck layer with gradient checkpointing enabled to save memory during training', 'make a residual layer with 3 Bottleneck blocks and stride 2 for downsampling', 'freeze the first 2 stages of a ResNet backbone to prevent gradient updates during fine-tuning', 'build a VGG backbone network with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolutional layer with configurable input output planes and dilation rate', 'create a VGG layer block with convolutions relu and max pooling for a given stage', 'initialize VGG backbone weights using pretrained checkpoint or kaiming normal initialization', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_resnet_backbone': 'build a ResNet backbone with depth 50 using Bottleneck blocks and pytorch style', 'create_basicblock_layer': 'create a BasicBlock layer with 64 input planes and 128 output planes for feature extraction', 'create_bottleneck_layer': 'create a Bottleneck layer with gradient checkpointing enabled to save memory during training', 'make_res_layer': 'make a residual layer with 3 Bottleneck blocks and stride 2 for downsampling', 'freeze_resnet_stages': 'freeze the first 2 stages of a ResNet backbone to prevent gradient updates during fine-tuning'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/vgg.py

Prompts

```
['build an AlexNet backbone model with configurable num_classes for feature extraction or classification', 'create an AlexNet model with a classifier head by setting num_classes to a positive integer', 'run a forward pass through the AlexNet features module on a torch tensor input', 'initialize AlexNet model weights from a pretrained checkpoint file path or use default initialization', 'review the AlexNet convolutional feature layers and optional classifier sequential layers', 'build a PyTorch model from a single config dict using the MODELS registry', 'build a Sequential module from a list of config dicts using build_model_from_cfg', 'build a model from config dict with default arguments using build_model_from_cfg', 'review the MODELS Registry instance and its build_func configuration for model building', 'test build_model_from_cfg with both dict and list config inputs', 'build a ResNet backbone with depth 50 using Bottleneck blocks and pytorch style', 'create a BasicBlock layer with 64 input planes and 128 output planes for feature extraction', 'create a Bottleneck layer with gradient checkpointing enabled to save memory during training', 'make a residual layer with 3 Bottleneck blocks and stride 2 for downsampling', 'freeze the first 2 stages of a ResNet backbone to prevent gradient updates during fine-tuning', 'build a VGG backbone network with depth 16 and batch normalization for feature extraction', 'create a 3x3 convolutional layer with configurable input output planes and dilation rate', 'create a VGG layer block with convolutions relu and max pooling for a given stage', 'initialize VGG backbone weights using pretrained checkpoint or kaiming normal initialization', 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor']
```

Usage

```
{'build_VGG_backbone': 'build a VGG backbone network with depth 16 and batch normalization for feature extraction', 'create_conv3x3_layer': 'create a 3x3 convolutional layer with configurable input output planes and dilation rate', 'create_make_vgg_layer': 'create a VGG layer block with convolutions relu and max pooling for a given stage', 'init_weights_VGG': 'initialize VGG backbone weights using pretrained checkpoint or kaiming normal initialization', 'forward_VGG': 'run forward pass through VGG backbone to extract multi-stage feature maps from input tensor'}
```

