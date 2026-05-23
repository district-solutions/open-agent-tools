# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/models/layers/blocks.py

Prompts

```
['build a spectral normalized Conv2d layer using spectral_conv_function with specified channels and kernel size', 'build a standard Conv2d layer using conv_function with specified input output channels and kernel size', 'get the appropriate convolution layer function based on whether spectral normalization is enabled in opt', 'create a ResNet_Block with optional downsampling or upsampling using the ResNet_Block class', 'create an Identity passthrough nn.Module that returns its input unchanged using the Identity class', 'create a bn module with standing stats accumulation for batch normalization', 'create a BatchNorm_StandingStats layer with learnable gain and bias parameters', 'build a LinearNoiseLayer that adds BigGAN-style noise to batch normalization', 'get a discriminator normalization layer factory supporting spectral, batch, or instance norm', 'run the fused_bn function to apply scaled and shifted batch normalization on tensors', 'build a RasterizePointsXYsBlending module to rasterize 3D points with configurable feature size and radius', 'create a RasterizePointsXYsBlending module using alphacomposite accumulation to blend 3D point features', 'test the RasterizePointsXYsBlending forward pass with 3D points and source features', 'review the RasterizePointsXYsBlending class and its alphacomposite, wsum, and wsumnorm accumulation modes', 'refactor the RasterizePointsXYsBlending module to support custom z-buffer accumulation functions']
```

Usage

```
{'build_spectral_conv': 'build a spectral normalized Conv2d layer using spectral_conv_function with specified channels and kernel size', 'build_plain_conv': 'build a standard Conv2d layer using conv_function with specified input output channels and kernel size', 'get_conv_layer_from_opt': 'get the appropriate convolution layer function based on whether spectral normalization is enabled in opt', 'create_resnet_block': 'create a ResNet_Block with optional downsampling or upsampling using the ResNet_Block class', 'create_identity_module': 'create an Identity passthrough nn.Module that returns its input unchanged using the Identity class'}
```

## File: facebookresearch_synsin/models/layers/normalization.py

Prompts

```
['build a spectral normalized Conv2d layer using spectral_conv_function with specified channels and kernel size', 'build a standard Conv2d layer using conv_function with specified input output channels and kernel size', 'get the appropriate convolution layer function based on whether spectral normalization is enabled in opt', 'create a ResNet_Block with optional downsampling or upsampling using the ResNet_Block class', 'create an Identity passthrough nn.Module that returns its input unchanged using the Identity class', 'create a bn module with standing stats accumulation for batch normalization', 'create a BatchNorm_StandingStats layer with learnable gain and bias parameters', 'build a LinearNoiseLayer that adds BigGAN-style noise to batch normalization', 'get a discriminator normalization layer factory supporting spectral, batch, or instance norm', 'run the fused_bn function to apply scaled and shifted batch normalization on tensors', 'build a RasterizePointsXYsBlending module to rasterize 3D points with configurable feature size and radius', 'create a RasterizePointsXYsBlending module using alphacomposite accumulation to blend 3D point features', 'test the RasterizePointsXYsBlending forward pass with 3D points and source features', 'review the RasterizePointsXYsBlending class and its alphacomposite, wsum, and wsumnorm accumulation modes', 'refactor the RasterizePointsXYsBlending module to support custom z-buffer accumulation functions']
```

Usage

```
{'create_bn_layer': 'create a bn module with standing stats accumulation for batch normalization', 'create_batchnorm_standing_stats': 'create a BatchNorm_StandingStats layer with learnable gain and bias parameters', 'build_linear_noise_layer': 'build a LinearNoiseLayer that adds BigGAN-style noise to batch normalization', 'get_D_norm_layer': 'get a discriminator normalization layer factory supporting spectral, batch, or instance norm', 'run_fused_bn': 'run the fused_bn function to apply scaled and shifted batch normalization on tensors'}
```

## File: facebookresearch_synsin/models/layers/z_buffer_layers.py

Prompts

```
['build a spectral normalized Conv2d layer using spectral_conv_function with specified channels and kernel size', 'build a standard Conv2d layer using conv_function with specified input output channels and kernel size', 'get the appropriate convolution layer function based on whether spectral normalization is enabled in opt', 'create a ResNet_Block with optional downsampling or upsampling using the ResNet_Block class', 'create an Identity passthrough nn.Module that returns its input unchanged using the Identity class', 'create a bn module with standing stats accumulation for batch normalization', 'create a BatchNorm_StandingStats layer with learnable gain and bias parameters', 'build a LinearNoiseLayer that adds BigGAN-style noise to batch normalization', 'get a discriminator normalization layer factory supporting spectral, batch, or instance norm', 'run the fused_bn function to apply scaled and shifted batch normalization on tensors', 'build a RasterizePointsXYsBlending module to rasterize 3D points with configurable feature size and radius', 'create a RasterizePointsXYsBlending module using alphacomposite accumulation to blend 3D point features', 'test the RasterizePointsXYsBlending forward pass with 3D points and source features', 'review the RasterizePointsXYsBlending class and its alphacomposite, wsum, and wsumnorm accumulation modes', 'refactor the RasterizePointsXYsBlending module to support custom z-buffer accumulation functions']
```

Usage

```
{'build_rasterize_points_xy_blending': 'build a RasterizePointsXYsBlending module to rasterize 3D points with configurable feature size and radius', 'create_rasterize_with_alpha_composite': 'create a RasterizePointsXYsBlending module using alphacomposite accumulation to blend 3D point features', 'test_rasterize_forward_pass': 'test the RasterizePointsXYsBlending forward pass with 3D points and source features', 'review_rasterize_accumulation_modes': 'review the RasterizePointsXYsBlending class and its alphacomposite, wsum, and wsumnorm accumulation modes', 'refactor_rasterize_z_buffer': 'refactor the RasterizePointsXYsBlending module to support custom z-buffer accumulation functions'}
```

