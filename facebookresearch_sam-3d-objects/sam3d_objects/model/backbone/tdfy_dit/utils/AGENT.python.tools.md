# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/utils/postprocessing_utils.py

Prompts

```
['postprocess a mesh by simplifying with quadric edge collapse and removing invisible faces using multiview rasterization', 'fill holes in a mesh by rasterizing from multiple views and solving a mincut problem on the dual graph', 'parametrize a mesh to UV texture space using xatlas for subsequent texture baking', 'bake a texture onto a parametrized mesh from multiple observations using fast splatting or gradient-based optimization', 'convert a Strivec or Gaussian appearance representation with an extracted mesh into a textured trimesh GLB object', 'compute the radical inverse of an integer n in a given base for low-discrepancy sampling', 'generate a Halton sequence point for a given dimension and index using prime bases', 'generate a Hammersley sequence point combining uniform sampling with Halton sequence values', 'sample uniformly distributed points on a sphere using the Hammersley sequence with optional offset and remapping', 'review the random_utils module and its low-discrepancy sequence functions for quasi-random sampling', 'render a 360 degree orbiting video of a 3D sample with configurable resolution and frame count', 'render color and depth frames from a 3D sample given camera extrinsics and intrinsics', 'convert yaw, pitch, radius, and fov values into camera extrinsics and intrinsics matrices', 'render a multi-view set of images from a 3D sample using Hammersley sphere sampling', 'render four orthogonal snapshot views of a 3D sample with configurable offset and resolution']
```

Usage

```
{'postprocess_mesh': 'postprocess a mesh by simplifying with quadric edge collapse and removing invisible faces using multiview rasterization', 'fill_holes': 'fill holes in a mesh by rasterizing from multiple views and solving a mincut problem on the dual graph', 'parametrize_mesh': 'parametrize a mesh to UV texture space using xatlas for subsequent texture baking', 'bake_texture': 'bake a texture onto a parametrized mesh from multiple observations using fast splatting or gradient-based optimization', 'to_glb': 'convert a Strivec or Gaussian appearance representation with an extracted mesh into a textured trimesh GLB object'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/utils/random_utils.py

Prompts

```
['postprocess a mesh by simplifying with quadric edge collapse and removing invisible faces using multiview rasterization', 'fill holes in a mesh by rasterizing from multiple views and solving a mincut problem on the dual graph', 'parametrize a mesh to UV texture space using xatlas for subsequent texture baking', 'bake a texture onto a parametrized mesh from multiple observations using fast splatting or gradient-based optimization', 'convert a Strivec or Gaussian appearance representation with an extracted mesh into a textured trimesh GLB object', 'compute the radical inverse of an integer n in a given base for low-discrepancy sampling', 'generate a Halton sequence point for a given dimension and index using prime bases', 'generate a Hammersley sequence point combining uniform sampling with Halton sequence values', 'sample uniformly distributed points on a sphere using the Hammersley sequence with optional offset and remapping', 'review the random_utils module and its low-discrepancy sequence functions for quasi-random sampling', 'render a 360 degree orbiting video of a 3D sample with configurable resolution and frame count', 'render color and depth frames from a 3D sample given camera extrinsics and intrinsics', 'convert yaw, pitch, radius, and fov values into camera extrinsics and intrinsics matrices', 'render a multi-view set of images from a 3D sample using Hammersley sphere sampling', 'render four orthogonal snapshot views of a 3D sample with configurable offset and resolution']
```

Usage

```
{'compute_radical_inverse': 'compute the radical inverse of an integer n in a given base for low-discrepancy sampling', 'generate_halton_sequence': 'generate a Halton sequence point for a given dimension and index using prime bases', 'generate_hammersley_sequence': 'generate a Hammersley sequence point combining uniform sampling with Halton sequence values', 'sample_sphere_hammersley': 'sample uniformly distributed points on a sphere using the Hammersley sequence with optional offset and remapping', 'review_random_utils': 'review the random_utils module and its low-discrepancy sequence functions for quasi-random sampling'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/utils/render_utils.py

Prompts

```
['postprocess a mesh by simplifying with quadric edge collapse and removing invisible faces using multiview rasterization', 'fill holes in a mesh by rasterizing from multiple views and solving a mincut problem on the dual graph', 'parametrize a mesh to UV texture space using xatlas for subsequent texture baking', 'bake a texture onto a parametrized mesh from multiple observations using fast splatting or gradient-based optimization', 'convert a Strivec or Gaussian appearance representation with an extracted mesh into a textured trimesh GLB object', 'compute the radical inverse of an integer n in a given base for low-discrepancy sampling', 'generate a Halton sequence point for a given dimension and index using prime bases', 'generate a Hammersley sequence point combining uniform sampling with Halton sequence values', 'sample uniformly distributed points on a sphere using the Hammersley sequence with optional offset and remapping', 'review the random_utils module and its low-discrepancy sequence functions for quasi-random sampling', 'render a 360 degree orbiting video of a 3D sample with configurable resolution and frame count', 'render color and depth frames from a 3D sample given camera extrinsics and intrinsics', 'convert yaw, pitch, radius, and fov values into camera extrinsics and intrinsics matrices', 'render a multi-view set of images from a 3D sample using Hammersley sphere sampling', 'render four orthogonal snapshot views of a 3D sample with configurable offset and resolution']
```

Usage

```
{'render_video_360': 'render a 360 degree orbiting video of a 3D sample with configurable resolution and frame count', 'render_frames_multi_view': 'render color and depth frames from a 3D sample given camera extrinsics and intrinsics', 'convert_camera_params': 'convert yaw, pitch, radius, and fov values into camera extrinsics and intrinsics matrices', 'render_multiview_hammersley': 'render a multi-view set of images from a 3D sample using Hammersley sphere sampling', 'render_snapshot_four_views': 'render four orthogonal snapshot views of a 3D sample with configurable offset and resolution'}
```

