# Agent Python Tools

- repo: facebookresearch/online-3dgs-monocular
- repo_uri: https://github.com/facebookresearch/online-3dgs-monocular

## File: facebookresearch_online-3dgs-monocular/DepthCov-Modified/depth_cov/nn/UNet.py

Prompts

```
['build a UNet model with configurable num_levels, in_channels, and base_feature_channels for feature extraction', 'create a UNet encoder with DownConv layers that progressively downsample features across num_levels', 'create a UNet decoder with UpConv layers that progressively upsample features and skip-connect encoder outputs', 'run the UNet forward pass on input tensor x to extract multi-scale feature maps', 'review the UNet ImageNet normalization layer with mean [0.485, 0.456, 0.406] and std [0.229, 0.224, 0.225]', 'create a BaseConv module with two stacked Conv2d layers and LeakyReLU activations', 'create a ResidualConv module with skip connections, GroupNorm, and LeakyReLU activations', 'create a DownConv module that applies MaxPool2d followed by a ResidualConv block', 'create an UpConv module that upsamples, concatenates skip connections, and applies ResidualConv', 'review the nn layers module containing BaseConv, ResidualConv, DownConv, and UpConv classes']
```

Usage

```
{'build_unet_model': 'build a UNet model with configurable num_levels, in_channels, and base_feature_channels for feature extraction', 'create_unet_encoder': 'create a UNet encoder with DownConv layers that progressively downsample features across num_levels', 'create_unet_decoder': 'create a UNet decoder with UpConv layers that progressively upsample features and skip-connect encoder outputs', 'run_unet_forward': 'run the UNet forward pass on input tensor x to extract multi-scale feature maps', 'review_unet_normalization': 'review the UNet ImageNet normalization layer with mean [0.485, 0.456, 0.406] and std [0.229, 0.224, 0.225]'}
```

## File: facebookresearch_online-3dgs-monocular/DepthCov-Modified/depth_cov/nn/layers.py

Prompts

```
['build a UNet model with configurable num_levels, in_channels, and base_feature_channels for feature extraction', 'create a UNet encoder with DownConv layers that progressively downsample features across num_levels', 'create a UNet decoder with UpConv layers that progressively upsample features and skip-connect encoder outputs', 'run the UNet forward pass on input tensor x to extract multi-scale feature maps', 'review the UNet ImageNet normalization layer with mean [0.485, 0.456, 0.406] and std [0.229, 0.224, 0.225]', 'create a BaseConv module with two stacked Conv2d layers and LeakyReLU activations', 'create a ResidualConv module with skip connections, GroupNorm, and LeakyReLU activations', 'create a DownConv module that applies MaxPool2d followed by a ResidualConv block', 'create an UpConv module that upsamples, concatenates skip connections, and applies ResidualConv', 'review the nn layers module containing BaseConv, ResidualConv, DownConv, and UpConv classes']
```

Usage

```
{'create_baseconv_layer': 'create a BaseConv module with two stacked Conv2d layers and LeakyReLU activations', 'create_residualconv_layer': 'create a ResidualConv module with skip connections, GroupNorm, and LeakyReLU activations', 'create_downconv_layer': 'create a DownConv module that applies MaxPool2d followed by a ResidualConv block', 'create_upconv_layer': 'create an UpConv module that upsamples, concatenates skip connections, and applies ResidualConv', 'review_layers_module': 'review the nn layers module containing BaseConv, ResidualConv, DownConv, and UpConv classes'}
```

