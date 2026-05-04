# Agent Python Tools

- repo: facebookresearch/deepcluster
- repo_uri: https://github.com/facebookresearch/deepcluster

## File: facebookresearch_deepcluster/models/alexnet.py

Prompts

```
['build a PyTorch AlexNet model with optional Sobel filter and batch normalization for image classification', 'create convolutional feature layers from a config tuple list with optional batch norm and ReLU', 'run the AlexNet forward pass on input tensor through features, classifier, and top layer', 'review the AlexNet weight initialization logic for Conv2d, BatchNorm2d, and Linear layers', 'summarize the AlexNet 2012 architecture config with filter counts, kernel sizes, strides, and padding', 'build a VGG16 model with optional Sobel edge detection and batch normalization for image classification', 'create a VGG16 model with Sobel edge detection filters enabled for edge-aware feature extraction', 'create a sequential feature extraction layer stack with configurable batch normalization from a channel config', 'review the VGG forward pass that applies Sobel, features, classifier, and top layer sequentially', 'review the VGG weight initialization using Kaiming normal for Conv2d and normal for Linear layers']
```

Usage

```
{'build_alexnet_model': 'build a PyTorch AlexNet model with optional Sobel filter and batch normalization for image classification', 'create_feature_layers': 'create convolutional feature layers from a config tuple list with optional batch norm and ReLU', 'run_alexnet_forward': 'run the AlexNet forward pass on input tensor through features, classifier, and top layer', 'review_initialize_weights': 'review the AlexNet weight initialization logic for Conv2d, BatchNorm2d, and Linear layers', 'summarize_alexnet_config': 'summarize the AlexNet 2012 architecture config with filter counts, kernel sizes, strides, and padding'}
```

## File: facebookresearch_deepcluster/models/vgg16.py

Prompts

```
['build a PyTorch AlexNet model with optional Sobel filter and batch normalization for image classification', 'create convolutional feature layers from a config tuple list with optional batch norm and ReLU', 'run the AlexNet forward pass on input tensor through features, classifier, and top layer', 'review the AlexNet weight initialization logic for Conv2d, BatchNorm2d, and Linear layers', 'summarize the AlexNet 2012 architecture config with filter counts, kernel sizes, strides, and padding', 'build a VGG16 model with optional Sobel edge detection and batch normalization for image classification', 'create a VGG16 model with Sobel edge detection filters enabled for edge-aware feature extraction', 'create a sequential feature extraction layer stack with configurable batch normalization from a channel config', 'review the VGG forward pass that applies Sobel, features, classifier, and top layer sequentially', 'review the VGG weight initialization using Kaiming normal for Conv2d and normal for Linear layers']
```

Usage

```
{'build_vgg16_model': 'build a VGG16 model with optional Sobel edge detection and batch normalization for image classification', 'create_vgg16_with_sobel': 'create a VGG16 model with Sobel edge detection filters enabled for edge-aware feature extraction', 'create_make_layers': 'create a sequential feature extraction layer stack with configurable batch normalization from a channel config', 'review_VGG_forward': 'review the VGG forward pass that applies Sobel, features, classifier, and top layer sequentially', 'review_VGG_initialize_weights': 'review the VGG weight initialization using Kaiming normal for Conv2d and normal for Linear layers'}
```

