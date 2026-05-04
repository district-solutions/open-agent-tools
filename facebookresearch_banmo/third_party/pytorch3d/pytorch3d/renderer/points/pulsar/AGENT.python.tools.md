# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/renderer/points/pulsar/renderer.py

Prompts

```
['create a Pulsar Renderer module with width, height, and max_num_balls parameters for differentiable sphere rendering', 'render a batch of 3D spheres into an image tensor using the Renderer forward pass with camera params', 'transform camera parameter vectors into internal camera representation vectors using _transform_cam_params', 'extract sphere IDs from a result info tensor using sphere_ids_from_result_info_nograd', 'extract a depth map from a result info tensor using depth_map_from_result_info_nograd', 'build a PulsarPointsRenderer with a PointsRasterizer to render point clouds using the pulsar backend', 'run the PulsarPointsRenderer forward pass on a Pointclouds object with gamma and camera kwargs', 'review the PulsarPointsRenderer _conf_check method to verify gamma and camera configuration consistency', 'summarize the PulsarPointsRenderer _extract_intrinsics method which converts PyTorch3D camera intrinsics to pulsar format', 'refactor the PulsarPointsRenderer _extract_extrinsics method to chain PyTorch3D to OpenCV to Pulsar camera conversion']
```

Usage

```
{'create_renderer_module': 'create a Pulsar Renderer module with width, height, and max_num_balls parameters for differentiable sphere rendering', 'render_spheres_with_forward': 'render a batch of 3D spheres into an image tensor using the Renderer forward pass with camera params', 'transform_camera_parameters': 'transform camera parameter vectors into internal camera representation vectors using _transform_cam_params', 'extract_sphere_ids': 'extract sphere IDs from a result info tensor using sphere_ids_from_result_info_nograd', 'extract_depth_map': 'extract a depth map from a result info tensor using depth_map_from_result_info_nograd'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/renderer/points/pulsar/unified.py

Prompts

```
['create a Pulsar Renderer module with width, height, and max_num_balls parameters for differentiable sphere rendering', 'render a batch of 3D spheres into an image tensor using the Renderer forward pass with camera params', 'transform camera parameter vectors into internal camera representation vectors using _transform_cam_params', 'extract sphere IDs from a result info tensor using sphere_ids_from_result_info_nograd', 'extract a depth map from a result info tensor using depth_map_from_result_info_nograd', 'build a PulsarPointsRenderer with a PointsRasterizer to render point clouds using the pulsar backend', 'run the PulsarPointsRenderer forward pass on a Pointclouds object with gamma and camera kwargs', 'review the PulsarPointsRenderer _conf_check method to verify gamma and camera configuration consistency', 'summarize the PulsarPointsRenderer _extract_intrinsics method which converts PyTorch3D camera intrinsics to pulsar format', 'refactor the PulsarPointsRenderer _extract_extrinsics method to chain PyTorch3D to OpenCV to Pulsar camera conversion']
```

Usage

```
{'build_PulsarPointsRenderer': 'build a PulsarPointsRenderer with a PointsRasterizer to render point clouds using the pulsar backend', 'run_PulsarPointsRenderer_forward': 'run the PulsarPointsRenderer forward pass on a Pointclouds object with gamma and camera kwargs', 'review_PulsarPointsRenderer_conf_check': 'review the PulsarPointsRenderer _conf_check method to verify gamma and camera configuration consistency', 'summarize_PulsarPointsRenderer_extract_intrinsics': 'summarize the PulsarPointsRenderer _extract_intrinsics method which converts PyTorch3D camera intrinsics to pulsar format', 'refactor_PulsarPointsRenderer_extract_extrinsics': 'refactor the PulsarPointsRenderer _extract_extrinsics method to chain PyTorch3D to OpenCV to Pulsar camera conversion'}
```

