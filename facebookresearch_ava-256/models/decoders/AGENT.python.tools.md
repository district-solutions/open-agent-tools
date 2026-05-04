# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/models/decoders/assembler.py

Prompts

```
['build a DecoderAssembler with mesh topology arrays, vertex statistics, and primitive configuration for 3D face rendering', 'run the DecoderAssembler forward pass with identity conditions, expression encoding, and camera view position to predict geometry and primitives', 'create a GeometryDecoder instance inside DecoderAssembler to decode expression-driven facial geometry from identity latent codes', 'create an RGBDecoder instance inside DecoderAssembler to decode view-conditioned primitive RGB colors from identity and expression codes', 'review the DecoderAssembler forward method residuals_weight parameter to control blending between predicted and default primitive position, rotation, and scale', 'build a GeometryDecoder instance with mesh UV, triangle, and UV triangle arrays plus hyperparameters', 'review the GeometryDecoder constructor to understand how deconv layers and early exits for motion and geometry are built', 'summarize the forward method outputs: opacity, geometry, position residual, rotation residual, and scale residual', 'test the GeometryDecoder registered coords buffer used for grid sampling geometry predictions onto mesh vertices', 'run the RGBDecoder forward pass with expression code, identity code, identity biases, and view direction tensors', 'build the transposed convolution layers in RGBDecoder for upsampling from 4x4 feature maps to full resolution', 'review the RGBDecoder view conditioning module that processes 3D view direction vectors into 8-channel feature maps', 'refactor the RGBDecoder tensor reshaping logic that converts flat texture maps into volumetric box grids']
```

Usage

```
{'build_decoder_assembler': 'build a DecoderAssembler with mesh topology arrays, vertex statistics, and primitive configuration for 3D face rendering', 'run_forward_pass': 'run the DecoderAssembler forward pass with identity conditions, expression encoding, and camera view position to predict geometry and primitives', 'create_geometry_decoder': 'create a GeometryDecoder instance inside DecoderAssembler to decode expression-driven facial geometry from identity latent codes', 'create_rgb_decoder': 'create an RGBDecoder instance inside DecoderAssembler to decode view-conditioned primitive RGB colors from identity and expression codes', 'review_forward_residuals': 'review the DecoderAssembler forward method residuals_weight parameter to control blending between predicted and default primitive position, rotation, and scale'}
```

## File: facebookresearch_ava-256/models/decoders/geometry.py

Prompts

```
['build a DecoderAssembler with mesh topology arrays, vertex statistics, and primitive configuration for 3D face rendering', 'run the DecoderAssembler forward pass with identity conditions, expression encoding, and camera view position to predict geometry and primitives', 'create a GeometryDecoder instance inside DecoderAssembler to decode expression-driven facial geometry from identity latent codes', 'create an RGBDecoder instance inside DecoderAssembler to decode view-conditioned primitive RGB colors from identity and expression codes', 'review the DecoderAssembler forward method residuals_weight parameter to control blending between predicted and default primitive position, rotation, and scale', 'build a GeometryDecoder instance with mesh UV, triangle, and UV triangle arrays plus hyperparameters', 'review the GeometryDecoder constructor to understand how deconv layers and early exits for motion and geometry are built', 'summarize the forward method outputs: opacity, geometry, position residual, rotation residual, and scale residual', 'test the GeometryDecoder registered coords buffer used for grid sampling geometry predictions onto mesh vertices', 'run the RGBDecoder forward pass with expression code, identity code, identity biases, and view direction tensors', 'build the transposed convolution layers in RGBDecoder for upsampling from 4x4 feature maps to full resolution', 'review the RGBDecoder view conditioning module that processes 3D view direction vectors into 8-channel feature maps', 'refactor the RGBDecoder tensor reshaping logic that converts flat texture maps into volumetric box grids']
```

Usage

```
{'build_geometry_decoder': 'build a GeometryDecoder instance with mesh UV, triangle, and UV triangle arrays plus hyperparameters', 'run_forward_pass': 'run a forward pass on the GeometryDecoder with expression code, identity code, and identity biases', 'review_geometry_decoder_init': 'review the GeometryDecoder constructor to understand how deconv layers and early exits for motion and geometry are built', 'summarize_forward_outputs': 'summarize the forward method outputs: opacity, geometry, position residual, rotation residual, and scale residual', 'test_geometry_decoder_coords': 'test the GeometryDecoder registered coords buffer used for grid sampling geometry predictions onto mesh vertices'}
```

## File: facebookresearch_ava-256/models/decoders/rgb.py

Prompts

```
['build a DecoderAssembler with mesh topology arrays, vertex statistics, and primitive configuration for 3D face rendering', 'run the DecoderAssembler forward pass with identity conditions, expression encoding, and camera view position to predict geometry and primitives', 'create a GeometryDecoder instance inside DecoderAssembler to decode expression-driven facial geometry from identity latent codes', 'create an RGBDecoder instance inside DecoderAssembler to decode view-conditioned primitive RGB colors from identity and expression codes', 'review the DecoderAssembler forward method residuals_weight parameter to control blending between predicted and default primitive position, rotation, and scale', 'build a GeometryDecoder instance with mesh UV, triangle, and UV triangle arrays plus hyperparameters', 'review the GeometryDecoder constructor to understand how deconv layers and early exits for motion and geometry are built', 'summarize the forward method outputs: opacity, geometry, position residual, rotation residual, and scale residual', 'test the GeometryDecoder registered coords buffer used for grid sampling geometry predictions onto mesh vertices', 'run the RGBDecoder forward pass with expression code, identity code, identity biases, and view direction tensors', 'build the transposed convolution layers in RGBDecoder for upsampling from 4x4 feature maps to full resolution', 'review the RGBDecoder view conditioning module that processes 3D view direction vectors into 8-channel feature maps', 'refactor the RGBDecoder tensor reshaping logic that converts flat texture maps into volumetric box grids']
```

Usage

```
{'create_rgb_decoder': 'create an RGBDecoder instance with imsize, nboxes, boxsize, outch, and viewcond parameters for volumetric primitive decoding', 'run_rgb_decoder_forward': 'run the RGBDecoder forward pass with expression code, identity code, identity biases, and view direction tensors', 'build_rgb_decoder_layers': 'build the transposed convolution layers in RGBDecoder for upsampling from 4x4 feature maps to full resolution', 'review_rgb_decoder_view_conditioning': 'review the RGBDecoder view conditioning module that processes 3D view direction vectors into 8-channel feature maps', 'refactor_rgb_decoder_tensor_reshaping': 'refactor the RGBDecoder tensor reshaping logic that converts flat texture maps into volumetric box grids'}
```

