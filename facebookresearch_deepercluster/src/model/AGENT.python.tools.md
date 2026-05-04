# Agent Python Tools

- repo: facebookresearch/deepercluster
- repo_uri: https://github.com/facebookresearch/deepercluster

## File: facebookresearch_deepercluster/src/model/model_factory.py

Prompts

```
['create a frozen Sobel edge detection layer using two Conv2d layers for grayscale and gradient filtering', 'build a VGG16-based neural network with optional Sobel preprocessing, batch normalization, and classification head', 'build a GPU prediction layer with an SGD optimizer for a given number of super classes', 'wrap a PyTorch module with DistributedDataParallel for multi-GPU training on a specified GPU', 'convert a Sobel-based network into an RGB input network by fusing Sobel weights into the first convolution layer', 'load pretrained model weights from a checkpoint file into a model body using args.pretrained path', 'rename checkpoint state dict keys by removing the module prefix added by DataParallel or DistributedDataParallel', 'remove sobel layer weight and bias keys from the checkpoint state dict before loading', 'remove prediction layer weight and bias keys from the checkpoint state dict before loading', 'load pretrained weights with CUDA device mapping when using multi-GPU distributed training with world_size greater than 1', 'build a VGG16 model with configurable input dimensions, dropout rate, and batch normalization', 'run a forward pass through the VGG16 model on an input tensor to get features', 'create a sequential feature layer stack from a config list with optional batch normalization', 'refactor the VGG16 classifier to add or remove the final ReLU activation layer', 'review the VGG16 weight initialization using Kaiming normal for Conv2d layers']
```

Usage

```
{'create_sobel_layer': 'create a frozen Sobel edge detection layer using two Conv2d layers for grayscale and gradient filtering', 'build_model_factory': 'build a VGG16-based neural network with optional Sobel preprocessing, batch normalization, and classification head', 'build_prediction_layer': 'build a GPU prediction layer with an SGD optimizer for a given number of super classes', 'wrap_net_to_cuda': 'wrap a PyTorch module with DistributedDataParallel for multi-GPU training on a specified GPU', 'convert_sobel_to_rgb': 'convert a Sobel-based network into an RGB input network by fusing Sobel weights into the first convolution layer'}
```

## File: facebookresearch_deepercluster/src/model/pretrain.py

Prompts

```
['create a frozen Sobel edge detection layer using two Conv2d layers for grayscale and gradient filtering', 'build a VGG16-based neural network with optional Sobel preprocessing, batch normalization, and classification head', 'build a GPU prediction layer with an SGD optimizer for a given number of super classes', 'wrap a PyTorch module with DistributedDataParallel for multi-GPU training on a specified GPU', 'convert a Sobel-based network into an RGB input network by fusing Sobel weights into the first convolution layer', 'load pretrained model weights from a checkpoint file into a model body using args.pretrained path', 'rename checkpoint state dict keys by removing the module prefix added by DataParallel or DistributedDataParallel', 'remove sobel layer weight and bias keys from the checkpoint state dict before loading', 'remove prediction layer weight and bias keys from the checkpoint state dict before loading', 'load pretrained weights with CUDA device mapping when using multi-GPU distributed training with world_size greater than 1', 'build a VGG16 model with configurable input dimensions, dropout rate, and batch normalization', 'run a forward pass through the VGG16 model on an input tensor to get features', 'create a sequential feature layer stack from a config list with optional batch normalization', 'refactor the VGG16 classifier to add or remove the final ReLU activation layer', 'review the VGG16 weight initialization using Kaiming normal for Conv2d layers']
```

Usage

```
{'load_pretrained_weights': 'load pretrained model weights from a checkpoint file into a model body using args.pretrained path', 'rename_checkpoint_keys': 'rename checkpoint state dict keys by removing the module prefix added by DataParallel or DistributedDataParallel', 'remove_sobel_keys': 'remove sobel layer weight and bias keys from the checkpoint state dict before loading', 'remove_pred_layer_keys': 'remove prediction layer weight and bias keys from the checkpoint state dict before loading', 'load_weights_with_gpu_mapping': 'load pretrained weights with CUDA device mapping when using multi-GPU distributed training with world_size greater than 1'}
```

## File: facebookresearch_deepercluster/src/model/vgg16.py

Prompts

```
['create a frozen Sobel edge detection layer using two Conv2d layers for grayscale and gradient filtering', 'build a VGG16-based neural network with optional Sobel preprocessing, batch normalization, and classification head', 'build a GPU prediction layer with an SGD optimizer for a given number of super classes', 'wrap a PyTorch module with DistributedDataParallel for multi-GPU training on a specified GPU', 'convert a Sobel-based network into an RGB input network by fusing Sobel weights into the first convolution layer', 'load pretrained model weights from a checkpoint file into a model body using args.pretrained path', 'rename checkpoint state dict keys by removing the module prefix added by DataParallel or DistributedDataParallel', 'remove sobel layer weight and bias keys from the checkpoint state dict before loading', 'remove prediction layer weight and bias keys from the checkpoint state dict before loading', 'load pretrained weights with CUDA device mapping when using multi-GPU distributed training with world_size greater than 1', 'build a VGG16 model with configurable input dimensions, dropout rate, and batch normalization', 'run a forward pass through the VGG16 model on an input tensor to get features', 'create a sequential feature layer stack from a config list with optional batch normalization', 'refactor the VGG16 classifier to add or remove the final ReLU activation layer', 'review the VGG16 weight initialization using Kaiming normal for Conv2d layers']
```

Usage

```
{'build_vgg16_model': 'build a VGG16 model with configurable input dimensions, dropout rate, and batch normalization', 'run_vgg16_forward': 'run a forward pass through the VGG16 model on an input tensor to get features', 'create_make_layers': 'create a sequential feature layer stack from a config list with optional batch normalization', 'refactor_vgg16_classifier': 'refactor the VGG16 classifier to add or remove the final ReLU activation layer', 'review_vgg16_weight_init': 'review the VGG16 weight initialization using Kaiming normal for Conv2d layers'}
```

