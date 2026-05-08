# Agent Python Tools

- repo: facebookresearch/holodiffusion
- repo_uri: https://github.com/facebookresearch/holo_diffusion

## File: facebookresearch_holodiffusion/holo_diffusion/utils/render_utils/flyaround.py

Prompts

```
['render a flyaround video of a 3D scene using a model with circular, figure-eight, or trefoil knot camera trajectories', 'generate a simple 360 degree camera trajectory with configurable elevation, radius, and focal length for rendering', 'extract and process rendered images, masks, and depth maps from model prediction dictionaries into visualization-ready tensors', 'stack multiple images into a grid layout for side-by-side visualization with optional resizing', 'generate MP4 videos from a list of rendered prediction frames with optional visdom visualization', 'render a textured PyTorch3D mesh using soft rasterization to produce an image, render mask, and depth map', 'create a FeatureShader module to render vertex feature maps from mesh fragments without shading', 'compute a depth map from rasterization fragments using softmax blending with configurable znear and zfar', 'blend per-face colors and alpha using softmax weights based on 2D distance and depth from rasterization fragments', 'clamp a tensor to a minimum absolute value while preserving the original sign of each element', 'convert depth maps to shaded images using mesh rendering with pytorch3d cameras and materials', 'convert depth maps to shaded images using point cloud normals with ambient lighting control', 'render a point cloud grid as a shaded mesh image with configurable material and background color', 'compute shaded values from a point cloud grid using estimated surface normals and neighborhood size', 'build a triangle mesh from a vertex grid and binary mask for 3D rendering']
```

Usage

```
{'render_flyaround_video': 'render a flyaround video of a 3D scene using a model with circular, figure-eight, or trefoil knot camera trajectories', 'generate_simple_360_trajectory': 'generate a simple 360 degree camera trajectory with configurable elevation, radius, and focal length for rendering', 'extract_images_from_predictions': 'extract and process rendered images, masks, and depth maps from model prediction dictionaries into visualization-ready tensors', 'stack_images_grid': 'stack multiple images into a grid layout for side-by-side visualization with optional resizing', 'generate_prediction_videos': 'generate MP4 videos from a list of rendered prediction frames with optional visdom visualization'}
```

## File: facebookresearch_holodiffusion/holo_diffusion/utils/render_utils/mesh_render.py

Prompts

```
['render a flyaround video of a 3D scene using a model with circular, figure-eight, or trefoil knot camera trajectories', 'generate a simple 360 degree camera trajectory with configurable elevation, radius, and focal length for rendering', 'extract and process rendered images, masks, and depth maps from model prediction dictionaries into visualization-ready tensors', 'stack multiple images into a grid layout for side-by-side visualization with optional resizing', 'generate MP4 videos from a list of rendered prediction frames with optional visdom visualization', 'render a textured PyTorch3D mesh using soft rasterization to produce an image, render mask, and depth map', 'create a FeatureShader module to render vertex feature maps from mesh fragments without shading', 'compute a depth map from rasterization fragments using softmax blending with configurable znear and zfar', 'blend per-face colors and alpha using softmax weights based on 2D distance and depth from rasterization fragments', 'clamp a tensor to a minimum absolute value while preserving the original sign of each element', 'convert depth maps to shaded images using mesh rendering with pytorch3d cameras and materials', 'convert depth maps to shaded images using point cloud normals with ambient lighting control', 'render a point cloud grid as a shaded mesh image with configurable material and background color', 'compute shaded values from a point cloud grid using estimated surface normals and neighborhood size', 'build a triangle mesh from a vertex grid and binary mask for 3D rendering']
```

Usage

```
{'render_mesh_with_soft_rasterization': 'render a textured PyTorch3D mesh using soft rasterization to produce an image, render mask, and depth map', 'create_feature_shader_for_vertex_features': 'create a FeatureShader module to render vertex feature maps from mesh fragments without shading', 'compute_softmax_depth_from_fragments': 'compute a depth map from rasterization fragments using softmax blending with configurable znear and zfar', 'blend_features_with_softmax_weights': 'blend per-face colors and alpha using softmax weights based on 2D distance and depth from rasterization fragments', 'clamp_tensor_preserving_sign': 'clamp a tensor to a minimum absolute value while preserving the original sign of each element'}
```

## File: facebookresearch_holodiffusion/holo_diffusion/utils/render_utils/shaded_depth_render.py

Prompts

```
['render a flyaround video of a 3D scene using a model with circular, figure-eight, or trefoil knot camera trajectories', 'generate a simple 360 degree camera trajectory with configurable elevation, radius, and focal length for rendering', 'extract and process rendered images, masks, and depth maps from model prediction dictionaries into visualization-ready tensors', 'stack multiple images into a grid layout for side-by-side visualization with optional resizing', 'generate MP4 videos from a list of rendered prediction frames with optional visdom visualization', 'render a textured PyTorch3D mesh using soft rasterization to produce an image, render mask, and depth map', 'create a FeatureShader module to render vertex feature maps from mesh fragments without shading', 'compute a depth map from rasterization fragments using softmax blending with configurable znear and zfar', 'blend per-face colors and alpha using softmax weights based on 2D distance and depth from rasterization fragments', 'clamp a tensor to a minimum absolute value while preserving the original sign of each element', 'convert depth maps to shaded images using mesh rendering with pytorch3d cameras and materials', 'convert depth maps to shaded images using point cloud normals with ambient lighting control', 'render a point cloud grid as a shaded mesh image with configurable material and background color', 'compute shaded values from a point cloud grid using estimated surface normals and neighborhood size', 'build a triangle mesh from a vertex grid and binary mask for 3D rendering']
```

Usage

```
{'depth_to_shaded_mesh': 'convert depth maps to shaded images using mesh rendering with pytorch3d cameras and materials', 'depth_to_shaded_pointcloud': 'convert depth maps to shaded images using point cloud normals with ambient lighting control', 'grid_pcl_to_shaded_mesh': 'render a point cloud grid as a shaded mesh image with configurable material and background color', 'grid_pcl_to_shaded': 'compute shaded values from a point cloud grid using estimated surface normals and neighborhood size', 'get_grid_mesh': 'build a triangle mesh from a vertex grid and binary mask for 3D rendering'}
```

