# Agent Python Tools

- repo: facebookresearch/neuralfeels
- repo_uri: https://github.com/facebookresearch/neuralfeels

## File: facebookresearch_neuralfeels/neuralfeels/geometry/align_utils.py

Prompts

```
['register two Open3D point clouds using ICP and return the 6DoF transformation matrix', 'run point-to-point ICP registration on two point clouds with a custom max correspondence distance', 'visualize source, target, and transformed point clouds in an Open3D 3D viewer window', 'register two point clouds with ICP and optionally display a debug visualization of the alignment', 'run ICP registration and extract fitness, inlier RMSE, and correspondence set metrics', 'build a python module that computes the four normalized frustum plane normals from camera intrinsics and rotation matrix', 'create a function that checks which 3D points lie inside a camera frustum using dot product against frustum normals', 'test the is_visible function to determine which 3D points are visible in a camera frame given depth and intrinsics', 'refactor the is_visible function to support a configurable truncation distance behind the surface for visibility checks', 'run the test_inside_frustum function to visualize camera frustum, point cloud visibility, and ray sampling in a trimesh scene', 'create a 4x4 pose matrix from Euler angles and translation using euler2matrix', 'build a GPU point cloud from a depth image using depth_image_to_point_cloud_GPU', 'test the transform_points function to apply a 4x4 transformation matrix to 3D points', 'review the look_at function that builds a camera-to-world transformation from eye, target, and up vectors', 'summarize the ray_box_intersection function that computes near and far z values where rays intersect a 3D box']
```

Usage

```
{'register_two_point_clouds': 'register two Open3D point clouds using ICP and return the 6DoF transformation matrix', 'run_icp_registration': 'run point-to-point ICP registration on two point clouds with a custom max correspondence distance', 'visualize_registration_result': 'visualize source, target, and transformed point clouds in an Open3D 3D viewer window', 'register_with_debug_vis': 'register two point clouds with ICP and optionally display a debug visualization of the alignment', 'get_icp_metrics': 'run ICP registration and extract fitness, inlier RMSE, and correspondence set metrics'}
```

## File: facebookresearch_neuralfeels/neuralfeels/geometry/frustum.py

Prompts

```
['register two Open3D point clouds using ICP and return the 6DoF transformation matrix', 'run point-to-point ICP registration on two point clouds with a custom max correspondence distance', 'visualize source, target, and transformed point clouds in an Open3D 3D viewer window', 'register two point clouds with ICP and optionally display a debug visualization of the alignment', 'run ICP registration and extract fitness, inlier RMSE, and correspondence set metrics', 'build a python module that computes the four normalized frustum plane normals from camera intrinsics and rotation matrix', 'create a function that checks which 3D points lie inside a camera frustum using dot product against frustum normals', 'test the is_visible function to determine which 3D points are visible in a camera frame given depth and intrinsics', 'refactor the is_visible function to support a configurable truncation distance behind the surface for visibility checks', 'run the test_inside_frustum function to visualize camera frustum, point cloud visibility, and ray sampling in a trimesh scene', 'create a 4x4 pose matrix from Euler angles and translation using euler2matrix', 'build a GPU point cloud from a depth image using depth_image_to_point_cloud_GPU', 'test the transform_points function to apply a 4x4 transformation matrix to 3D points', 'review the look_at function that builds a camera-to-world transformation from eye, target, and up vectors', 'summarize the ray_box_intersection function that computes near and far z values where rays intersect a 3D box']
```

Usage

```
{'build_get_frustum_normals': 'build a python module that computes the four normalized frustum plane normals from camera intrinsics and rotation matrix', 'create_check_inside_frustum': 'create a function that checks which 3D points lie inside a camera frustum using dot product against frustum normals', 'test_is_visible': 'test the is_visible function to determine which 3D points are visible in a camera frame given depth and intrinsics', 'refactor_is_visible_truncation': 'refactor the is_visible function to support a configurable truncation distance behind the surface for visibility checks', 'run_test_inside_frustum': 'run the test_inside_frustum function to visualize camera frustum, point cloud visibility, and ray sampling in a trimesh scene'}
```

## File: facebookresearch_neuralfeels/neuralfeels/geometry/transform.py

Prompts

```
['register two Open3D point clouds using ICP and return the 6DoF transformation matrix', 'run point-to-point ICP registration on two point clouds with a custom max correspondence distance', 'visualize source, target, and transformed point clouds in an Open3D 3D viewer window', 'register two point clouds with ICP and optionally display a debug visualization of the alignment', 'run ICP registration and extract fitness, inlier RMSE, and correspondence set metrics', 'build a python module that computes the four normalized frustum plane normals from camera intrinsics and rotation matrix', 'create a function that checks which 3D points lie inside a camera frustum using dot product against frustum normals', 'test the is_visible function to determine which 3D points are visible in a camera frame given depth and intrinsics', 'refactor the is_visible function to support a configurable truncation distance behind the surface for visibility checks', 'run the test_inside_frustum function to visualize camera frustum, point cloud visibility, and ray sampling in a trimesh scene', 'create a 4x4 pose matrix from Euler angles and translation using euler2matrix', 'build a GPU point cloud from a depth image using depth_image_to_point_cloud_GPU', 'test the transform_points function to apply a 4x4 transformation matrix to 3D points', 'review the look_at function that builds a camera-to-world transformation from eye, target, and up vectors', 'summarize the ray_box_intersection function that computes near and far z values where rays intersect a 3D box']
```

Usage

```
{'create_euler_to_matrix': 'create a 4x4 pose matrix from Euler angles and translation using euler2matrix', 'build_depth_to_pointcloud': 'build a GPU point cloud from a depth image using depth_image_to_point_cloud_GPU', 'test_transform_points': 'test the transform_points function to apply a 4x4 transformation matrix to 3D points', 'review_look_at': 'review the look_at function that builds a camera-to-world transformation from eye, target, and up vectors', 'summarize_ray_box_intersection': 'summarize the ray_box_intersection function that computes near and far z values where rays intersect a 3D box'}
```

