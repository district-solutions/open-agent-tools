# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/renderers/gaussian_render.py

Prompts

```
['convert OpenCV camera intrinsics to an OpenGL perspective projection matrix given near and far clip planes', 'render a 3D Gaussian scene using the Inria diff_gaussian_rasterization backend with configurable kernel size and SH conversion', 'render a 3D Gaussian scene using the gsplat backend and return color, alpha, and RGBA outputs', 'create a GaussianRenderer instance with configurable resolution, SSAA, background color, and rendering backend options', 'render a Gaussian point cloud from camera extrinsics and intrinsics using the GaussianRenderer class with optional color override', 'render a DfsOctree scene with camera extrinsics and intrinsics using OctreeRenderer', 'render a voxel-based octree using OctreeVoxelRasterizer with density and SH features', 'render a gaussian-based octree using OctreeGaussianRasterizer with opacity and SH features', 'render a trivec-based octree using OctreeTrivecRasterizer with density and trivec features', 'evaluate spherical harmonics coefficients at unit directions for a given degree using hardcoded SH polynomials', 'evaluate spherical harmonics on batched direction tensors with configurable degree from 0 to 4', 'convert RGB color values to spherical harmonics coefficients by normalizing with the C0 constant', 'convert spherical harmonics coefficients back to RGB color values using the C0 constant', 'review the spherical harmonics normalization constants C0 through C4 used in SH polynomial evaluation']
```

Usage

```
{'convert_intrinsics_to_projection': 'convert OpenCV camera intrinsics to an OpenGL perspective projection matrix given near and far clip planes', 'render_gaussian_scene_inria': 'render a 3D Gaussian scene using the Inria diff_gaussian_rasterization backend with configurable kernel size and SH conversion', 'render_gaussian_scene_gsplat': 'render a 3D Gaussian scene using the gsplat backend and return color, alpha, and RGBA outputs', 'create_gaussian_renderer': 'create a GaussianRenderer instance with configurable resolution, SSAA, background color, and rendering backend options', 'render_with_gaussian_renderer_class': 'render a Gaussian point cloud from camera extrinsics and intrinsics using the GaussianRenderer class with optional color override'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/renderers/octree_renderer.py

Prompts

```
['convert OpenCV camera intrinsics to an OpenGL perspective projection matrix given near and far clip planes', 'render a 3D Gaussian scene using the Inria diff_gaussian_rasterization backend with configurable kernel size and SH conversion', 'render a 3D Gaussian scene using the gsplat backend and return color, alpha, and RGBA outputs', 'create a GaussianRenderer instance with configurable resolution, SSAA, background color, and rendering backend options', 'render a Gaussian point cloud from camera extrinsics and intrinsics using the GaussianRenderer class with optional color override', 'render a DfsOctree scene with camera extrinsics and intrinsics using OctreeRenderer', 'render a voxel-based octree using OctreeVoxelRasterizer with density and SH features', 'render a gaussian-based octree using OctreeGaussianRasterizer with opacity and SH features', 'render a trivec-based octree using OctreeTrivecRasterizer with density and trivec features', 'evaluate spherical harmonics coefficients at unit directions for a given degree using hardcoded SH polynomials', 'evaluate spherical harmonics on batched direction tensors with configurable degree from 0 to 4', 'convert RGB color values to spherical harmonics coefficients by normalizing with the C0 constant', 'convert spherical harmonics coefficients back to RGB color values using the C0 constant', 'review the spherical harmonics normalization constants C0 through C4 used in SH polynomial evaluation']
```

Usage

```
{'render_octree_scene': 'render a DfsOctree scene with camera extrinsics and intrinsics using OctreeRenderer', 'convert_intrinsics_to_projection': 'convert OpenCV camera intrinsics to an OpenGL perspective projection matrix', 'render_voxel_octree': 'render a voxel-based octree using OctreeVoxelRasterizer with density and SH features', 'render_gaussian_octree': 'render a gaussian-based octree using OctreeGaussianRasterizer with opacity and SH features', 'render_trivec_octree': 'render a trivec-based octree using OctreeTrivecRasterizer with density and trivec features'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/renderers/sh_utils.py

Prompts

```
['convert OpenCV camera intrinsics to an OpenGL perspective projection matrix given near and far clip planes', 'render a 3D Gaussian scene using the Inria diff_gaussian_rasterization backend with configurable kernel size and SH conversion', 'render a 3D Gaussian scene using the gsplat backend and return color, alpha, and RGBA outputs', 'create a GaussianRenderer instance with configurable resolution, SSAA, background color, and rendering backend options', 'render a Gaussian point cloud from camera extrinsics and intrinsics using the GaussianRenderer class with optional color override', 'render a DfsOctree scene with camera extrinsics and intrinsics using OctreeRenderer', 'render a voxel-based octree using OctreeVoxelRasterizer with density and SH features', 'render a gaussian-based octree using OctreeGaussianRasterizer with opacity and SH features', 'render a trivec-based octree using OctreeTrivecRasterizer with density and trivec features', 'evaluate spherical harmonics coefficients at unit directions for a given degree using hardcoded SH polynomials', 'evaluate spherical harmonics on batched direction tensors with configurable degree from 0 to 4', 'convert RGB color values to spherical harmonics coefficients by normalizing with the C0 constant', 'convert spherical harmonics coefficients back to RGB color values using the C0 constant', 'review the spherical harmonics normalization constants C0 through C4 used in SH polynomial evaluation']
```

Usage

```
{'eval_sh_spherical_harmonics': 'evaluate spherical harmonics coefficients at unit directions for a given degree using hardcoded SH polynomials', 'eval_sh_batched_directions': 'evaluate spherical harmonics on batched direction tensors with configurable degree from 0 to 4', 'RGB2SH_convert_rgb_to_sh': 'convert RGB color values to spherical harmonics coefficients by normalizing with the C0 constant', 'SH2RGB_convert_sh_to_rgb': 'convert spherical harmonics coefficients back to RGB color values using the C0 constant', 'review_sh_utils_constants': 'review the spherical harmonics normalization constants C0 through C4 used in SH polynomial evaluation'}
```

