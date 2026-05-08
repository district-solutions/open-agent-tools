# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/pulsar/renderer.py

Prompts

```
['create a Pulsar Renderer module with specified width, height, and maximum number of balls for differentiable rendering', 'render 3D spheres to an image using the Renderer forward pass with vertex positions, colors, radii, and camera parameters', 'transform camera parameter vectors into internal position, pixel vectors, focal length, and principal point offset tensors', 'extract sphere IDs from a result info tensor using the sphere_ids_from_result_info_nograd static method', 'extract a depth map from a result info tensor using the depth_map_from_result_info_nograd static method', 'create a PulsarPointsRenderer with a PointsRasterizer to render differentiable point clouds using the pulsar backend', 'render a batch of point clouds with gamma and camera parameters using the PulsarPointsRenderer forward method', 'extract camera intrinsics like focal length, sensor width, and principal point from PyTorch3D cameras to pulsar format', 'extract camera extrinsics including position and rotation from PyTorch3D R and T matrices via OpenCV conversion', 'convert a scalar or tensor value into a float32 PyTorch tensor reshaped to a single element on a given device']
```

Usage

```
{'create_pulsar_renderer': 'create a Pulsar Renderer module with specified width, height, and maximum number of balls for differentiable rendering', 'render_spheres_with_renderer': 'render 3D spheres to an image using the Renderer forward pass with vertex positions, colors, radii, and camera parameters', 'transform_camera_params': 'transform camera parameter vectors into internal position, pixel vectors, focal length, and principal point offset tensors', 'extract_sphere_ids_from_info': 'extract sphere IDs from a result info tensor using the sphere_ids_from_result_info_nograd static method', 'extract_depth_map_from_info': 'extract a depth map from a result info tensor using the depth_map_from_result_info_nograd static method'}
```

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/pulsar/unified.py

Prompts

```
['create a Pulsar Renderer module with specified width, height, and maximum number of balls for differentiable rendering', 'render 3D spheres to an image using the Renderer forward pass with vertex positions, colors, radii, and camera parameters', 'transform camera parameter vectors into internal position, pixel vectors, focal length, and principal point offset tensors', 'extract sphere IDs from a result info tensor using the sphere_ids_from_result_info_nograd static method', 'extract a depth map from a result info tensor using the depth_map_from_result_info_nograd static method', 'create a PulsarPointsRenderer with a PointsRasterizer to render differentiable point clouds using the pulsar backend', 'render a batch of point clouds with gamma and camera parameters using the PulsarPointsRenderer forward method', 'extract camera intrinsics like focal length, sensor width, and principal point from PyTorch3D cameras to pulsar format', 'extract camera extrinsics including position and rotation from PyTorch3D R and T matrices via OpenCV conversion', 'convert a scalar or tensor value into a float32 PyTorch tensor reshaped to a single element on a given device']
```

Usage

```
{'create_PulsarPointsRenderer': 'create a PulsarPointsRenderer with a PointsRasterizer to render differentiable point clouds using the pulsar backend', 'render_point_clouds_forward': 'render a batch of point clouds with gamma and camera parameters using the PulsarPointsRenderer forward method', 'extract_camera_intrinsics': 'extract camera intrinsics like focal length, sensor width, and principal point from PyTorch3D cameras to pulsar format', 'extract_camera_extrinsics': 'extract camera extrinsics including position and rotation from PyTorch3D R and T matrices via OpenCV conversion', 'ensure_float_tensor': 'convert a scalar or tensor value into a float32 PyTorch tensor reshaped to a single element on a given device'}
```

