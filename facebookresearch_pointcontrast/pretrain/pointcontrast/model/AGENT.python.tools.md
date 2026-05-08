# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/pretrain/pointcontrast/model/res16unet.py

Prompts

```
['build a Res16UNet34 sparse 3D U-Net model with BasicBlock layers for point cloud processing', 'build a Res16UNet34C sparse 3D U-Net model with custom decoder channel planes for segmentation', 'run the Res16UNetBase forward pass on a MinkowskiEngine SparseTensor input for feature extraction', 'review the Res16UNetBase network_initialization method to understand encoder-decoder layer construction with skip connections', 'refactor the Res16UNetBase forward method to change L2 feature normalization behavior on output', 'build a ResNetBase subclass by setting BLOCK and LAYERS class attributes for sparse 3D point cloud feature extraction', 'create a ResNet network with conv1, batch norm, relu, pooling, and four residual layers using network_initialization', 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, layer1-4, and final conv', 'refactor the _make_layer method to customize stride, dilation, or norm_type for residual block construction', 'summarize the weight_initialization method that sets MinkowskiBatchNorm weights to 1 and biases to 0']
```

Usage

```
{'build_Res16UNet34_model': 'build a Res16UNet34 sparse 3D U-Net model with BasicBlock layers for point cloud processing', 'build_Res16UNet34C_model': 'build a Res16UNet34C sparse 3D U-Net model with custom decoder channel planes for segmentation', 'run_Res16UNetBase_forward': 'run the Res16UNetBase forward pass on a MinkowskiEngine SparseTensor input for feature extraction', 'review_Res16UNetBase_network_initialization': 'review the Res16UNetBase network_initialization method to understand encoder-decoder layer construction with skip connections', 'refactor_Res16UNetBase_normalize_feature': 'refactor the Res16UNetBase forward method to change L2 feature normalization behavior on output'}
```

## File: facebookresearch_pointcontrast/pretrain/pointcontrast/model/resnet.py

Prompts

```
['build a Res16UNet34 sparse 3D U-Net model with BasicBlock layers for point cloud processing', 'build a Res16UNet34C sparse 3D U-Net model with custom decoder channel planes for segmentation', 'run the Res16UNetBase forward pass on a MinkowskiEngine SparseTensor input for feature extraction', 'review the Res16UNetBase network_initialization method to understand encoder-decoder layer construction with skip connections', 'refactor the Res16UNetBase forward method to change L2 feature normalization behavior on output', 'build a ResNetBase subclass by setting BLOCK and LAYERS class attributes for sparse 3D point cloud feature extraction', 'create a ResNet network with conv1, batch norm, relu, pooling, and four residual layers using network_initialization', 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, layer1-4, and final conv', 'refactor the _make_layer method to customize stride, dilation, or norm_type for residual block construction', 'summarize the weight_initialization method that sets MinkowskiBatchNorm weights to 1 and biases to 0']
```

Usage

```
{'build_ResNetBase_subclass': 'build a ResNetBase subclass by setting BLOCK and LAYERS class attributes for sparse 3D point cloud feature extraction', 'create_network_initialization': 'create a ResNet network with conv1, batch norm, relu, pooling, and four residual layers using network_initialization', 'review_ResNetBase_forward': 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, layer1-4, and final conv', 'refactor_make_layer': 'refactor the _make_layer method to customize stride, dilation, or norm_type for residual block construction', 'summarize_weight_initialization': 'summarize the weight_initialization method that sets MinkowskiBatchNorm weights to 1 and biases to 0'}
```

