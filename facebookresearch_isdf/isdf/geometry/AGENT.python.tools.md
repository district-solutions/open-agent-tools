# Agent Python Tools

- repo: facebookresearch/isdf
- repo_uri: https://github.com/facebookresearch/isdf

## File: facebookresearch_isdf/isdf/geometry/frustum.py

Prompts

```
['compute the four normalized frustum plane normals from camera rotation matrix and intrinsics', 'check which 3D points lie inside a camera frustum using dot product against frustum normals', 'determine which 3D points are visible in a camera frame using forward projection and depth comparison', 'determine which 3D points are visible in a batched camera frame using PyTorch tensor operations', 'visualize camera frustum normals, visible points, and ray samples in a trimesh 3D scene', 'create camera ray directions from intrinsics using ray_dirs_C with batch size, height, width, fx, fy, cx, cy', 'transform camera rays to world coordinates using origin_dirs_W with a camera-to-world transform matrix', 'build a camera rotation and translation from eye, target, and up vectors using the look_at function', 'generate a 3D point cloud from a depth image using pointcloud_from_depth with camera intrinsics', 'estimate surface normals from a 3D point cloud tensor using estimate_pointcloud_normals']
```

Usage

```
{'compute_frustum_normals': 'compute the four normalized frustum plane normals from camera rotation matrix and intrinsics', 'check_points_inside_frustum': 'check which 3D points lie inside a camera frustum using dot product against frustum normals', 'determine_point_visibility_numpy': 'determine which 3D points are visible in a camera frame using forward projection and depth comparison', 'determine_point_visibility_torch': 'determine which 3D points are visible in a batched camera frame using PyTorch tensor operations', 'visualize_frustum_and_rays': 'visualize camera frustum normals, visible points, and ray samples in a trimesh 3D scene'}
```

## File: facebookresearch_isdf/isdf/geometry/transform.py

Prompts

```
['compute the four normalized frustum plane normals from camera rotation matrix and intrinsics', 'check which 3D points lie inside a camera frustum using dot product against frustum normals', 'determine which 3D points are visible in a camera frame using forward projection and depth comparison', 'determine which 3D points are visible in a batched camera frame using PyTorch tensor operations', 'visualize camera frustum normals, visible points, and ray samples in a trimesh 3D scene', 'create camera ray directions from intrinsics using ray_dirs_C with batch size, height, width, fx, fy, cx, cy', 'transform camera rays to world coordinates using origin_dirs_W with a camera-to-world transform matrix', 'build a camera rotation and translation from eye, target, and up vectors using the look_at function', 'generate a 3D point cloud from a depth image using pointcloud_from_depth with camera intrinsics', 'estimate surface normals from a 3D point cloud tensor using estimate_pointcloud_normals']
```

Usage

```
{'create_camera_rays': 'create camera ray directions from intrinsics using ray_dirs_C with batch size, height, width, fx, fy, cx, cy', 'transform_rays_to_world': 'transform camera rays to world coordinates using origin_dirs_W with a camera-to-world transform matrix', 'build_look_at_transform': 'build a camera rotation and translation from eye, target, and up vectors using the look_at function', 'generate_pointcloud_from_depth': 'generate a 3D point cloud from a depth image using pointcloud_from_depth with camera intrinsics', 'estimate_normals_from_pointcloud': 'estimate surface normals from a 3D point cloud tensor using estimate_pointcloud_normals'}
```

