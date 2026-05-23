# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/layers/Fusion.py

Prompts

```
['build a Fusion module that fuses feature maps with residual convolutions and bilinear upsampling', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU for residual feature transformation', 'test the Fusion forward pass with input tensor and optional previous stage feature map', 'test the ResidualConvUnit forward pass to verify residual connection adds input to output', 'review the Fusion module bilinear interpolation with scale factor 2 for upsampling output features', 'build a PyTorch module to predict normal and shear force fields from input feature tensors', 'create a convolution block with 3x3 padding followed by ELU activation for feature extraction', 'create a padded 3x3 convolution layer using reflection or zero padding before convolving input', 'create an interpolation module to resize tensors by a given scale factor using bilinear or nearest mode', 'test the upsample function to double the spatial dimensions of a tensor using nearest neighbor interpolation', 'build a Reassemble module to read, rearrange, and resample patch embeddings for a given image size', 'create a Resample layer that projects and upsamples or downsamples 2D feature maps by stride s', 'use Read_ignore to skip the first N tokens and return the remaining sequence from index start_index', 'use Read_add to add the CLS token readout to all subsequent tokens before returning them', 'use Read_projection to concatenate the CLS token with each patch token and project through a Linear+GELU layer']
```

Usage

```
{'build_Fusion_module': 'build a Fusion module that fuses feature maps with residual convolutions and bilinear upsampling', 'create_ResidualConvUnit': 'create a ResidualConvUnit with two 3x3 conv layers and ReLU for residual feature transformation', 'test_Fusion_forward': 'test the Fusion forward pass with input tensor and optional previous stage feature map', 'test_ResidualConvUnit_forward': 'test the ResidualConvUnit forward pass to verify residual connection adds input to output', 'review_Fusion_interpolate': 'review the Fusion module bilinear interpolation with scale factor 2 for upsampling output features'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/layers/Head.py

Prompts

```
['build a Fusion module that fuses feature maps with residual convolutions and bilinear upsampling', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU for residual feature transformation', 'test the Fusion forward pass with input tensor and optional previous stage feature map', 'test the ResidualConvUnit forward pass to verify residual connection adds input to output', 'review the Fusion module bilinear interpolation with scale factor 2 for upsampling output features', 'build a PyTorch module to predict normal and shear force fields from input feature tensors', 'create a convolution block with 3x3 padding followed by ELU activation for feature extraction', 'create a padded 3x3 convolution layer using reflection or zero padding before convolving input', 'create an interpolation module to resize tensors by a given scale factor using bilinear or nearest mode', 'test the upsample function to double the spatial dimensions of a tensor using nearest neighbor interpolation', 'build a Reassemble module to read, rearrange, and resample patch embeddings for a given image size', 'create a Resample layer that projects and upsamples or downsamples 2D feature maps by stride s', 'use Read_ignore to skip the first N tokens and return the remaining sequence from index start_index', 'use Read_add to add the CLS token readout to all subsequent tokens before returning them', 'use Read_projection to concatenate the CLS token with each patch token and project through a Linear+GELU layer']
```

Usage

```
{'build_NormalShearHead': 'build a PyTorch module to predict normal and shear force fields from input feature tensors', 'create_ConvBlock': 'create a convolution block with 3x3 padding followed by ELU activation for feature extraction', 'create_Conv3x3': 'create a padded 3x3 convolution layer using reflection or zero padding before convolving input', 'create_Interpolate': 'create an interpolation module to resize tensors by a given scale factor using bilinear or nearest mode', 'test_upsample': 'test the upsample function to double the spatial dimensions of a tensor using nearest neighbor interpolation'}
```

## File: facebookresearch_sparsh/tactile_ssl/downstream_task/utils_forcefield/layers/Reassemble.py

Prompts

```
['build a Fusion module that fuses feature maps with residual convolutions and bilinear upsampling', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU for residual feature transformation', 'test the Fusion forward pass with input tensor and optional previous stage feature map', 'test the ResidualConvUnit forward pass to verify residual connection adds input to output', 'review the Fusion module bilinear interpolation with scale factor 2 for upsampling output features', 'build a PyTorch module to predict normal and shear force fields from input feature tensors', 'create a convolution block with 3x3 padding followed by ELU activation for feature extraction', 'create a padded 3x3 convolution layer using reflection or zero padding before convolving input', 'create an interpolation module to resize tensors by a given scale factor using bilinear or nearest mode', 'test the upsample function to double the spatial dimensions of a tensor using nearest neighbor interpolation', 'build a Reassemble module to read, rearrange, and resample patch embeddings for a given image size', 'create a Resample layer that projects and upsamples or downsamples 2D feature maps by stride s', 'use Read_ignore to skip the first N tokens and return the remaining sequence from index start_index', 'use Read_add to add the CLS token readout to all subsequent tokens before returning them', 'use Read_projection to concatenate the CLS token with each patch token and project through a Linear+GELU layer']
```

Usage

```
{'build_Reassemble_module': 'build a Reassemble module to read, rearrange, and resample patch embeddings for a given image size', 'create_Resample_layer': 'create a Resample layer that projects and upsamples or downsamples 2D feature maps by stride s', 'use_Read_ignore_class': 'use Read_ignore to skip the first N tokens and return the remaining sequence from index start_index', 'use_Read_add_class': 'use Read_add to add the CLS token readout to all subsequent tokens before returning them', 'use_Read_projection_class': 'use Read_projection to concatenate the CLS token with each patch token and project through a Linear+GELU layer'}
```

