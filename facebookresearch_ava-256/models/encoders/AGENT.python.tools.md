# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/models/encoders/expression.py

Prompts

```
['build an ExpressionEncoder with UV triangle indices and barycentric coordinates for face expression encoding', 'run the ExpressionEncoder forward pass with vertices and texture tensors to get a 64x4x4 expression code', 'create a texture preprocessor Sequential module with weight-normalized convolutions and LeakyReLU activations', 'create a geometry preprocessor Sequential module that processes geometry maps through weight-normalized convolutions', 'review the ExpressionEncoder init method to understand UV buffer registration and channel multiplier configuration', 'build a person identity encoder using IdentityEncoder with UV triangle indices and barycentric coordinates', 'run the UnetEncoder forward pass on an input tensor to get latent codes and bias maps', 'create a geometry map encoding from neutral vertices using the IdentityEncoder forward method', 'combine geometry and texture bias maps using GeoTexCombiner to mix cross-modal information', 'review the UnetEncoder architecture with 8 downsampling layers using weight-normalized convolutions', 'generate a geometry image from vertices and their topology using PyTorch tensors', 'generate a geometry map using barycentric coordinates and triangle indices for mesh rasterization', 'test the generate_geomap function with sample vertex and topology tensors', 'review the generate_geomap function for backpropagation performance with repeated indices', 'refactor the generate_geomap function to re-enable shape assertions for debugging']
```

Usage

```
{'build_expression_encoder': 'build an ExpressionEncoder with UV triangle indices and barycentric coordinates for face expression encoding', 'run_expression_encoder_forward': 'run the ExpressionEncoder forward pass with vertices and texture tensors to get a 64x4x4 expression code', 'create_texture_preprocessor': 'create a texture preprocessor Sequential module with weight-normalized convolutions and LeakyReLU activations', 'create_geometry_preprocessor': 'create a geometry preprocessor Sequential module that processes geometry maps through weight-normalized convolutions', 'review_expression_encoder_init': 'review the ExpressionEncoder init method to understand UV buffer registration and channel multiplier configuration'}
```

## File: facebookresearch_ava-256/models/encoders/identity.py

Prompts

```
['build an ExpressionEncoder with UV triangle indices and barycentric coordinates for face expression encoding', 'run the ExpressionEncoder forward pass with vertices and texture tensors to get a 64x4x4 expression code', 'create a texture preprocessor Sequential module with weight-normalized convolutions and LeakyReLU activations', 'create a geometry preprocessor Sequential module that processes geometry maps through weight-normalized convolutions', 'review the ExpressionEncoder init method to understand UV buffer registration and channel multiplier configuration', 'build a person identity encoder using IdentityEncoder with UV triangle indices and barycentric coordinates', 'run the UnetEncoder forward pass on an input tensor to get latent codes and bias maps', 'create a geometry map encoding from neutral vertices using the IdentityEncoder forward method', 'combine geometry and texture bias maps using GeoTexCombiner to mix cross-modal information', 'review the UnetEncoder architecture with 8 downsampling layers using weight-normalized convolutions', 'generate a geometry image from vertices and their topology using PyTorch tensors', 'generate a geometry map using barycentric coordinates and triangle indices for mesh rasterization', 'test the generate_geomap function with sample vertex and topology tensors', 'review the generate_geomap function for backpropagation performance with repeated indices', 'refactor the generate_geomap function to re-enable shape assertions for debugging']
```

Usage

```
{'build_identity_encoder': 'build a person identity encoder using IdentityEncoder with UV triangle indices and barycentric coordinates', 'run_unet_encoder_forward': 'run the UnetEncoder forward pass on an input tensor to get latent codes and bias maps', 'create_geomap_encoding': 'create a geometry map encoding from neutral vertices using the IdentityEncoder forward method', 'combine_geo_tex_bias_maps': 'combine geometry and texture bias maps using GeoTexCombiner to mix cross-modal information', 'review_unet_encoder_architecture': 'review the UnetEncoder architecture with 8 downsampling layers using weight-normalized convolutions'}
```

## File: facebookresearch_ava-256/models/encoders/utils.py

Prompts

```
['build an ExpressionEncoder with UV triangle indices and barycentric coordinates for face expression encoding', 'run the ExpressionEncoder forward pass with vertices and texture tensors to get a 64x4x4 expression code', 'create a texture preprocessor Sequential module with weight-normalized convolutions and LeakyReLU activations', 'create a geometry preprocessor Sequential module that processes geometry maps through weight-normalized convolutions', 'review the ExpressionEncoder init method to understand UV buffer registration and channel multiplier configuration', 'build a person identity encoder using IdentityEncoder with UV triangle indices and barycentric coordinates', 'run the UnetEncoder forward pass on an input tensor to get latent codes and bias maps', 'create a geometry map encoding from neutral vertices using the IdentityEncoder forward method', 'combine geometry and texture bias maps using GeoTexCombiner to mix cross-modal information', 'review the UnetEncoder architecture with 8 downsampling layers using weight-normalized convolutions', 'generate a geometry image from vertices and their topology using PyTorch tensors', 'generate a geometry map using barycentric coordinates and triangle indices for mesh rasterization', 'test the generate_geomap function with sample vertex and topology tensors', 'review the generate_geomap function for backpropagation performance with repeated indices', 'refactor the generate_geomap function to re-enable shape assertions for debugging']
```

Usage

```
{'generate_geomap_from_vertices': 'generate a geometry image from vertices and their topology using PyTorch tensors', 'generate_geomap_barycentric_interpolation': 'generate a geometry map using barycentric coordinates and triangle indices for mesh rasterization', 'test_generate_geomap': 'test the generate_geomap function with sample vertex and topology tensors', 'review_generate_geomap_performance': 'review the generate_geomap function for backpropagation performance with repeated indices', 'refactor_generate_geomap_assertions': 'refactor the generate_geomap function to re-enable shape assertions for debugging'}
```

