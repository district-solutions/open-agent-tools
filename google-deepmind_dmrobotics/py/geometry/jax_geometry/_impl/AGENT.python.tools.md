# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/geometry/jax_geometry/_impl/map_coordinates.py

Prompts

```
['map an image to new coordinates using bilinear interpolation with JAX', 'map an image to new coordinates using nearest neighbor interpolation with JAX', 'bilinearly interpolate a single channel image at a specified y x coordinate', 'perform nearest neighbor interpolation on a single channel image at a coordinate', 'slice a JAX array with out-of-bounds indices masked by a padding value', 'test dynamic_slice_with_padding to slice an image array with out-of-bounds coordinate padding', 'test map_coordinates with identity coordinates to verify image sampling returns the original image', 'test map_coordinates with edge coordinates using nearest and bilinear interpolation methods', 'run padded_slice to extract a region from an array with constant value padding for overflow', 'create a random uniform source image with a given shape using JAX PRNG']
```

Usage

```
{'map_coordinates_bilinear': 'map an image to new coordinates using bilinear interpolation with JAX', 'map_coordinates_nearest': 'map an image to new coordinates using nearest neighbor interpolation with JAX', 'bilinear_interpolate': 'bilinearly interpolate a single channel image at a specified y x coordinate', 'nearest_interpolate': 'perform nearest neighbor interpolation on a single channel image at a coordinate', 'dynamic_slice_with_padding': 'slice a JAX array with out-of-bounds indices masked by a padding value'}
```

## File: google-deepmind_dmrobotics/py/geometry/jax_geometry/_impl/map_coordinates_test.py

Prompts

```
['map an image to new coordinates using bilinear interpolation with JAX', 'map an image to new coordinates using nearest neighbor interpolation with JAX', 'bilinearly interpolate a single channel image at a specified y x coordinate', 'perform nearest neighbor interpolation on a single channel image at a coordinate', 'slice a JAX array with out-of-bounds indices masked by a padding value', 'test dynamic_slice_with_padding to slice an image array with out-of-bounds coordinate padding', 'test map_coordinates with identity coordinates to verify image sampling returns the original image', 'test map_coordinates with edge coordinates using nearest and bilinear interpolation methods', 'run padded_slice to extract a region from an array with constant value padding for overflow', 'create a random uniform source image with a given shape using JAX PRNG']
```

Usage

```
{'test_dynamic_slice_with_padding': 'test dynamic_slice_with_padding to slice an image array with out-of-bounds coordinate padding', 'test_map_coordinates_identity': 'test map_coordinates with identity coordinates to verify image sampling returns the original image', 'test_map_coordinates_edges': 'test map_coordinates with edge coordinates using nearest and bilinear interpolation methods', 'run_padded_slice': 'run padded_slice to extract a region from an array with constant value padding for overflow', 'create_source_image': 'create a random uniform source image with a given shape using JAX PRNG'}
```

