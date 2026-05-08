# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/pointnet2backbone.py

Prompts

```
['build a PointNet2Backbone network for point cloud feature learning with set abstraction and feature upsampling layers', 'run a forward pass on a point cloud tensor through the PointNet2Backbone network to extract features', 'create four set abstraction layers with decreasing point counts from 2048 to 256 using PointnetSAModuleVotes', 'create four feature upsampling layers using PointnetFPModule to interpolate and refine features back to original point count', 'break up a point cloud tensor into xyz coordinates and optional feature descriptors for processing', 'build a Res16UNetBase sparse 3D U-Net model with configurable in/out channels and dimensionality', 'create a Res16UNet34 model variant with 2-3-4-6 encoder layers using BasicBlock', 'create a Res16UNet18 model variant with uniform 2-layer blocks using BasicBlock', 'review the Res16UNetBase forward pass encoder-decoder path with skip connections and feature normalization', 'summarize the Res16UNetBase network_initialization method that builds 8 encoder-decoder blocks with transposed convolutions', 'build a ResNet subclass by setting BLOCK and LAYERS class attributes on ResNetBase', 'create a ResNetBase network by calling network_initialization with in_channels, out_channels, config, and D', 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, four layers, and final conv', 'refactor the ResNetBase _make_layer method to change block construction or downsampling logic', 'summarize the ResNetBase weight_initialization method that sets MinkowskiBatchNorm weights to 1 and bias to 0']
```

Usage

```
{'build_pointnet2_backbone': 'build a PointNet2Backbone network for point cloud feature learning with set abstraction and feature upsampling layers', 'run_forward_pass': 'run a forward pass on a point cloud tensor through the PointNet2Backbone network to extract features', 'create_set_abstraction_layers': 'create four set abstraction layers with decreasing point counts from 2048 to 256 using PointnetSAModuleVotes', 'create_feature_upsampling_layers': 'create four feature upsampling layers using PointnetFPModule to interpolate and refine features back to original point count', 'break_up_pointcloud': 'break up a point cloud tensor into xyz coordinates and optional feature descriptors for processing'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/res16unet.py

Prompts

```
['build a PointNet2Backbone network for point cloud feature learning with set abstraction and feature upsampling layers', 'run a forward pass on a point cloud tensor through the PointNet2Backbone network to extract features', 'create four set abstraction layers with decreasing point counts from 2048 to 256 using PointnetSAModuleVotes', 'create four feature upsampling layers using PointnetFPModule to interpolate and refine features back to original point count', 'break up a point cloud tensor into xyz coordinates and optional feature descriptors for processing', 'build a Res16UNetBase sparse 3D U-Net model with configurable in/out channels and dimensionality', 'create a Res16UNet34 model variant with 2-3-4-6 encoder layers using BasicBlock', 'create a Res16UNet18 model variant with uniform 2-layer blocks using BasicBlock', 'review the Res16UNetBase forward pass encoder-decoder path with skip connections and feature normalization', 'summarize the Res16UNetBase network_initialization method that builds 8 encoder-decoder blocks with transposed convolutions', 'build a ResNet subclass by setting BLOCK and LAYERS class attributes on ResNetBase', 'create a ResNetBase network by calling network_initialization with in_channels, out_channels, config, and D', 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, four layers, and final conv', 'refactor the ResNetBase _make_layer method to change block construction or downsampling logic', 'summarize the ResNetBase weight_initialization method that sets MinkowskiBatchNorm weights to 1 and bias to 0']
```

Usage

```
{'build_Res16UNetBase_model': 'build a Res16UNetBase sparse 3D U-Net model with configurable in/out channels and dimensionality', 'create_Res16UNet34_variant': 'create a Res16UNet34 model variant with 2-3-4-6 encoder layers using BasicBlock', 'create_Res16UNet18_variant': 'create a Res16UNet18 model variant with uniform 2-layer blocks using BasicBlock', 'review_Res16UNetBase_forward': 'review the Res16UNetBase forward pass encoder-decoder path with skip connections and feature normalization', 'summarize_Res16UNetBase_network_initialization': 'summarize the Res16UNetBase network_initialization method that builds 8 encoder-decoder blocks with transposed convolutions'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/resnet.py

Prompts

```
['build a PointNet2Backbone network for point cloud feature learning with set abstraction and feature upsampling layers', 'run a forward pass on a point cloud tensor through the PointNet2Backbone network to extract features', 'create four set abstraction layers with decreasing point counts from 2048 to 256 using PointnetSAModuleVotes', 'create four feature upsampling layers using PointnetFPModule to interpolate and refine features back to original point count', 'break up a point cloud tensor into xyz coordinates and optional feature descriptors for processing', 'build a Res16UNetBase sparse 3D U-Net model with configurable in/out channels and dimensionality', 'create a Res16UNet34 model variant with 2-3-4-6 encoder layers using BasicBlock', 'create a Res16UNet18 model variant with uniform 2-layer blocks using BasicBlock', 'review the Res16UNetBase forward pass encoder-decoder path with skip connections and feature normalization', 'summarize the Res16UNetBase network_initialization method that builds 8 encoder-decoder blocks with transposed convolutions', 'build a ResNet subclass by setting BLOCK and LAYERS class attributes on ResNetBase', 'create a ResNetBase network by calling network_initialization with in_channels, out_channels, config, and D', 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, four layers, and final conv', 'refactor the ResNetBase _make_layer method to change block construction or downsampling logic', 'summarize the ResNetBase weight_initialization method that sets MinkowskiBatchNorm weights to 1 and bias to 0']
```

Usage

```
{'build_ResNetBase_subclass': 'build a ResNet subclass by setting BLOCK and LAYERS class attributes on ResNetBase', 'create_ResNetBase_network': 'create a ResNetBase network by calling network_initialization with in_channels, out_channels, config, and D', 'review_ResNetBase_forward': 'review the ResNetBase forward pass that chains conv1, bn1, relu, pool, four layers, and final conv', 'refactor_ResNetBase_make_layer': 'refactor the ResNetBase _make_layer method to change block construction or downsampling logic', 'summarize_ResNetBase_weight_initialization': 'summarize the ResNetBase weight_initialization method that sets MinkowskiBatchNorm weights to 1 and bias to 0'}
```

