# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/banding_removal/fastmri/model/public_unet.py

Prompts

```
['build a U-Net model with configurable channels, pool layers, and dropout for MRI image segmentation', 'build a U-Net model variant with push-pop skip connections and average pooling for image reconstruction', 'create a convolutional block with dense or residual variants for feature extraction in neural networks', 'run the unet factory function to create a UnetModel from argparse arguments with num_chans and num_pools', 'review the ConvBlock forward pass to understand dense concatenation and residual skip connection logic', 'build a variational network model by calling var_net with an args namespace containing method_str and sens_method_str', 'build a variational network with explicit sensitivity maps by calling var_net_explicit_sens with an args namespace', "create a SequentialPlus module chain using parse_model with a string like 'DC(),FT(),Abs()' to build reconstruction steps", 'create a SoftDC module with a neural net, space option img-space or k-space, and mode parallel or sequential', 'review the complex_mul function which performs element-wise complex multiplication on tensors with shape ending in 2']
```

Usage

```
{'build_unet_model': 'build a U-Net model with configurable channels, pool layers, and dropout for MRI image segmentation', 'build_unet_model2': 'build a U-Net model variant with push-pop skip connections and average pooling for image reconstruction', 'create_convblock': 'create a convolutional block with dense or residual variants for feature extraction in neural networks', 'run_unet_factory': 'run the unet factory function to create a UnetModel from argparse arguments with num_chans and num_pools', 'review_convblock_forward': 'review the ConvBlock forward pass to understand dense concatenation and residual skip connection logic'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/model/var_net.py

Prompts

```
['build a U-Net model with configurable channels, pool layers, and dropout for MRI image segmentation', 'build a U-Net model variant with push-pop skip connections and average pooling for image reconstruction', 'create a convolutional block with dense or residual variants for feature extraction in neural networks', 'run the unet factory function to create a UnetModel from argparse arguments with num_chans and num_pools', 'review the ConvBlock forward pass to understand dense concatenation and residual skip connection logic', 'build a variational network model by calling var_net with an args namespace containing method_str and sens_method_str', 'build a variational network with explicit sensitivity maps by calling var_net_explicit_sens with an args namespace', "create a SequentialPlus module chain using parse_model with a string like 'DC(),FT(),Abs()' to build reconstruction steps", 'create a SoftDC module with a neural net, space option img-space or k-space, and mode parallel or sequential', 'review the complex_mul function which performs element-wise complex multiplication on tensors with shape ending in 2']
```

Usage

```
{'build_var_net_model': 'build a variational network model by calling var_net with an args namespace containing method_str and sens_method_str', 'build_var_net_explicit_sens': 'build a variational network with explicit sensitivity maps by calling var_net_explicit_sens with an args namespace', 'create_sequentialplus_module': "create a SequentialPlus module chain using parse_model with a string like 'DC(),FT(),Abs()' to build reconstruction steps", 'create_softdc_module': 'create a SoftDC module with a neural net, space option img-space or k-space, and mode parallel or sequential', 'review_complex_mul': 'review the complex_mul function which performs element-wise complex multiplication on tensors with shape ending in 2'}
```

