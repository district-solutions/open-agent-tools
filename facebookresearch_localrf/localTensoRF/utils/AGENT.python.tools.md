# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/localTensoRF/utils/ray_utils.py

Prompts

```
['contract 3D points so those outside the unit sphere are mapped inside using NeRF-W contraction', 'compute ray directions in camera coordinates from pixel coordinates, focal length, and principal point', 'convert spherical coordinates (radius, theta, phi) to 3D Cartesian xyz coordinates using PyTorch', 'compute 360-degree equirectangular ray directions from pixel indices and image width and height', 'transform camera-space ray directions to world coordinates using a camera-to-world transformation matrix', 'smooth camera poses using spline interpolation with optional median prefiltering', 'convert a 3D SDF tensor to a PLY mesh file using marching cubes', 'visualize a depth map as a colorized tensor using a colormap', 'compute the SSIM image quality metric between two RGB images', 'draw colored 3D camera pose wireframes and return the rendered image']
```

Usage

```
{'contract_points_inside_unit_sphere': 'contract 3D points so those outside the unit sphere are mapped inside using NeRF-W contraction', 'get_ray_directions_lean_camera_rays': 'compute ray directions in camera coordinates from pixel coordinates, focal length, and principal point', 'sphere2xyz_spherical_to_cartesian': 'convert spherical coordinates (radius, theta, phi) to 3D Cartesian xyz coordinates using PyTorch', 'get_ray_directions_360_equirectangular': 'compute 360-degree equirectangular ray directions from pixel indices and image width and height', 'get_rays_lean_world_rays': 'transform camera-space ray directions to world coordinates using a camera-to-world transformation matrix'}
```

## File: facebookresearch_localrf/localTensoRF/utils/utils.py

Prompts

```
['contract 3D points so those outside the unit sphere are mapped inside using NeRF-W contraction', 'compute ray directions in camera coordinates from pixel coordinates, focal length, and principal point', 'convert spherical coordinates (radius, theta, phi) to 3D Cartesian xyz coordinates using PyTorch', 'compute 360-degree equirectangular ray directions from pixel indices and image width and height', 'transform camera-space ray directions to world coordinates using a camera-to-world transformation matrix', 'smooth camera poses using spline interpolation with optional median prefiltering', 'convert a 3D SDF tensor to a PLY mesh file using marching cubes', 'visualize a depth map as a colorized tensor using a colormap', 'compute the SSIM image quality metric between two RGB images', 'draw colored 3D camera pose wireframes and return the rendered image']
```

Usage

```
{'smooth_poses_spline': 'smooth camera poses using spline interpolation with optional median prefiltering', 'convert_sdf_samples_to_ply': 'convert a 3D SDF tensor to a PLY mesh file using marching cubes', 'visualize_depth': 'visualize a depth map as a colorized tensor using a colormap', 'rgb_ssim': 'compute the SSIM image quality metric between two RGB images', 'draw_poses': 'draw colored 3D camera pose wireframes and return the rendered image'}
```

