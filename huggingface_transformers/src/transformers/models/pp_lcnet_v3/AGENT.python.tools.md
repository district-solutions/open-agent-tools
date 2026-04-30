# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_lcnet_v3/configuration_pp_lcnet_v3.py

Prompts

```
['create a PPLCNetV3Config instance with custom scale, stem_channels, and block_configs parameters', 'build a PP-LCNetV3 model by instantiating PPLCNetV3Config and passing it to the model loader', 'validate a PPLCNetV3Config architecture by calling validate_architecture to ensure block_configs has 5 stages', 'customize PP-LCNetV3 block_configs with custom kernel sizes, channel dimensions, strides, and squeeze-excitation flags', 'configure PPLCNetV3Config output features and output indices for multi-scale feature extraction', 'create a PPLCNetV3Backbone model with PPLCNetV3Config for image feature extraction', 'run the PPLCNetV3Backbone forward pass on pixel values to extract feature maps', 'build a PPLCNetV3Encoder with stem convolution and stage blocks for feature encoding', 'build a PPLCNetV3Block containing depthwise separable convolution layers for a stage', 'review the PPLCNetV3LearnableRepLayer that fuses multiple convolution branches with structural reparameterization', 'create a PPLCNetV3Config with custom scale, block_configs, stem_channels, and conv_symmetric_num parameters', 'build a PPLCNetV3Encoder with a PPLCNetV3Config to initialize the stem convolution layer', 'create a PPLCNetV3LearnableRepLayer with multi-branch convolution and structural reparameterization', 'create a PPLCNetV3DepthwiseSeparableConvLayer with depthwise and pointwise learnable rep layers', 'initialize PPLCNetV3PreTrainedModel weights with ones for scale and zeros for bias on learnable affine blocks']
```

Usage

```
{'create_pp_lcnet_v3_config': 'create a PPLCNetV3Config instance with custom scale, stem_channels, and block_configs parameters', 'build_pp_lcnet_v3_model': 'build a PP-LCNetV3 model by instantiating PPLCNetV3Config and passing it to the model loader', 'validate_pp_lcnet_v3_architecture': 'validate a PPLCNetV3Config architecture by calling validate_architecture to ensure block_configs has 5 stages', 'customize_pp_lcnet_v3_blocks': 'customize PP-LCNetV3 block_configs with custom kernel sizes, channel dimensions, strides, and squeeze-excitation flags', 'configure_pp_lcnet_v3_output_features': 'configure PPLCNetV3Config output features and output indices for multi-scale feature extraction'}
```

## File: huggingface_transformers/src/transformers/models/pp_lcnet_v3/modeling_pp_lcnet_v3.py

Prompts

```
['create a PPLCNetV3Config instance with custom scale, stem_channels, and block_configs parameters', 'build a PP-LCNetV3 model by instantiating PPLCNetV3Config and passing it to the model loader', 'validate a PPLCNetV3Config architecture by calling validate_architecture to ensure block_configs has 5 stages', 'customize PP-LCNetV3 block_configs with custom kernel sizes, channel dimensions, strides, and squeeze-excitation flags', 'configure PPLCNetV3Config output features and output indices for multi-scale feature extraction', 'create a PPLCNetV3Backbone model with PPLCNetV3Config for image feature extraction', 'run the PPLCNetV3Backbone forward pass on pixel values to extract feature maps', 'build a PPLCNetV3Encoder with stem convolution and stage blocks for feature encoding', 'build a PPLCNetV3Block containing depthwise separable convolution layers for a stage', 'review the PPLCNetV3LearnableRepLayer that fuses multiple convolution branches with structural reparameterization', 'create a PPLCNetV3Config with custom scale, block_configs, stem_channels, and conv_symmetric_num parameters', 'build a PPLCNetV3Encoder with a PPLCNetV3Config to initialize the stem convolution layer', 'create a PPLCNetV3LearnableRepLayer with multi-branch convolution and structural reparameterization', 'create a PPLCNetV3DepthwiseSeparableConvLayer with depthwise and pointwise learnable rep layers', 'initialize PPLCNetV3PreTrainedModel weights with ones for scale and zeros for bias on learnable affine blocks']
```

Usage

```
{'create_pp_lcnet_v3_backbone': 'create a PPLCNetV3Backbone model with PPLCNetV3Config for image feature extraction', 'run_pp_lcnet_v3_forward': 'run the PPLCNetV3Backbone forward pass on pixel values to extract feature maps', 'build_pp_lcnet_v3_encoder': 'build a PPLCNetV3Encoder with stem convolution and stage blocks for feature encoding', 'build_pp_lcnet_v3_block': 'build a PPLCNetV3Block containing depthwise separable convolution layers for a stage', 'review_pp_lcnet_v3_conv_layer': 'review the PPLCNetV3LearnableRepLayer that fuses multiple convolution branches with structural reparameterization'}
```

## File: huggingface_transformers/src/transformers/models/pp_lcnet_v3/modular_pp_lcnet_v3.py

Prompts

```
['create a PPLCNetV3Config instance with custom scale, stem_channels, and block_configs parameters', 'build a PP-LCNetV3 model by instantiating PPLCNetV3Config and passing it to the model loader', 'validate a PPLCNetV3Config architecture by calling validate_architecture to ensure block_configs has 5 stages', 'customize PP-LCNetV3 block_configs with custom kernel sizes, channel dimensions, strides, and squeeze-excitation flags', 'configure PPLCNetV3Config output features and output indices for multi-scale feature extraction', 'create a PPLCNetV3Backbone model with PPLCNetV3Config for image feature extraction', 'run the PPLCNetV3Backbone forward pass on pixel values to extract feature maps', 'build a PPLCNetV3Encoder with stem convolution and stage blocks for feature encoding', 'build a PPLCNetV3Block containing depthwise separable convolution layers for a stage', 'review the PPLCNetV3LearnableRepLayer that fuses multiple convolution branches with structural reparameterization', 'create a PPLCNetV3Config with custom scale, block_configs, stem_channels, and conv_symmetric_num parameters', 'build a PPLCNetV3Encoder with a PPLCNetV3Config to initialize the stem convolution layer', 'create a PPLCNetV3LearnableRepLayer with multi-branch convolution and structural reparameterization', 'create a PPLCNetV3DepthwiseSeparableConvLayer with depthwise and pointwise learnable rep layers', 'initialize PPLCNetV3PreTrainedModel weights with ones for scale and zeros for bias on learnable affine blocks']
```

Usage

```
{'create_PPLCNetV3Config': 'create a PPLCNetV3Config with custom scale, block_configs, stem_channels, and conv_symmetric_num parameters', 'build_PPLCNetV3Encoder': 'build a PPLCNetV3Encoder with a PPLCNetV3Config to initialize the stem convolution layer', 'create_PPLCNetV3LearnableRepLayer': 'create a PPLCNetV3LearnableRepLayer with multi-branch convolution and structural reparameterization', 'create_PPLCNetV3DepthwiseSeparableConvLayer': 'create a PPLCNetV3DepthwiseSeparableConvLayer with depthwise and pointwise learnable rep layers', 'initialize_PPLCNetV3PreTrainedModel': 'initialize PPLCNetV3PreTrainedModel weights with ones for scale and zeros for bias on learnable affine blocks'}
```

