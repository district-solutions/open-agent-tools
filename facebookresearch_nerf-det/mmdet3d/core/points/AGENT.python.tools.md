# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/points/base_points.py

Prompts

```
['create a BasePoints object from a torch tensor or numpy array with N x 3 coordinates', 'rotate the points in a BasePoints object by a given angle around the X, Y, or Z axis', 'translate the points in a BasePoints object by a given 3D translation vector', 'filter points in a BasePoints object to keep only those within a specified 3D bounding box range', 'concatenate a list of BasePoints objects into a single BasePoints object using the cat class method', 'create a CameraPoints instance from a tensor with N x 3 point coordinates in CAM space', 'flip CameraPoints horizontally or vertically along the BEV direction using the flip method', 'check which CameraPoints fall within a given BEV point range using in_range_bev', 'convert CameraPoints from CAM coordinates to another coordinate system using convert_to', 'review the CameraPoints class and its rotation_axis attribute set to 1 for Y-axis rotation', 'create a DepthPoints instance from a tensor with N x 3 coordinates in DEPTH mode', 'flip DepthPoints horizontally or vertically along the BEV direction', 'check which DepthPoints fall within a given x_min, y_min, x_max, y_max range', 'convert DepthPoints from DEPTH coordinates to another Coord3DMode using a rotation-translation matrix', 'review the DepthPoints class that extends BasePoints for DEPTH coordinate point cloud operations', 'create a LiDARPoints instance from a tensor with N x 3 point coordinates', 'flip LiDAR points horizontally or vertically along the BEV direction', 'check which LiDAR points fall within a given x and y bounding range', 'convert LiDAR points to a different coordinate mode using a transformation matrix', 'review the LiDARPoints class and its flip, in_range_bev, and convert_to methods']
```

Usage

```
{'create_BasePoints_from_tensor': 'create a BasePoints object from a torch tensor or numpy array with N x 3 coordinates', 'rotate_BasePoints': 'rotate the points in a BasePoints object by a given angle around the X, Y, or Z axis', 'translate_BasePoints': 'translate the points in a BasePoints object by a given 3D translation vector', 'filter_BasePoints_in_range_3d': 'filter points in a BasePoints object to keep only those within a specified 3D bounding box range', 'concatenate_BasePoints': 'concatenate a list of BasePoints objects into a single BasePoints object using the cat class method'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/points/cam_points.py

Prompts

```
['create a BasePoints object from a torch tensor or numpy array with N x 3 coordinates', 'rotate the points in a BasePoints object by a given angle around the X, Y, or Z axis', 'translate the points in a BasePoints object by a given 3D translation vector', 'filter points in a BasePoints object to keep only those within a specified 3D bounding box range', 'concatenate a list of BasePoints objects into a single BasePoints object using the cat class method', 'create a CameraPoints instance from a tensor with N x 3 point coordinates in CAM space', 'flip CameraPoints horizontally or vertically along the BEV direction using the flip method', 'check which CameraPoints fall within a given BEV point range using in_range_bev', 'convert CameraPoints from CAM coordinates to another coordinate system using convert_to', 'review the CameraPoints class and its rotation_axis attribute set to 1 for Y-axis rotation', 'create a DepthPoints instance from a tensor with N x 3 coordinates in DEPTH mode', 'flip DepthPoints horizontally or vertically along the BEV direction', 'check which DepthPoints fall within a given x_min, y_min, x_max, y_max range', 'convert DepthPoints from DEPTH coordinates to another Coord3DMode using a rotation-translation matrix', 'review the DepthPoints class that extends BasePoints for DEPTH coordinate point cloud operations', 'create a LiDARPoints instance from a tensor with N x 3 point coordinates', 'flip LiDAR points horizontally or vertically along the BEV direction', 'check which LiDAR points fall within a given x and y bounding range', 'convert LiDAR points to a different coordinate mode using a transformation matrix', 'review the LiDARPoints class and its flip, in_range_bev, and convert_to methods']
```

Usage

```
{'create_CameraPoints': 'create a CameraPoints instance from a tensor with N x 3 point coordinates in CAM space', 'flip_CameraPoints': 'flip CameraPoints horizontally or vertically along the BEV direction using the flip method', 'in_range_bev_CameraPoints': 'check which CameraPoints fall within a given BEV point range using in_range_bev', 'convert_to_CameraPoints': 'convert CameraPoints from CAM coordinates to another coordinate system using convert_to', 'review_CameraPoints_rotation_axis': 'review the CameraPoints class and its rotation_axis attribute set to 1 for Y-axis rotation'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/points/depth_points.py

Prompts

```
['create a BasePoints object from a torch tensor or numpy array with N x 3 coordinates', 'rotate the points in a BasePoints object by a given angle around the X, Y, or Z axis', 'translate the points in a BasePoints object by a given 3D translation vector', 'filter points in a BasePoints object to keep only those within a specified 3D bounding box range', 'concatenate a list of BasePoints objects into a single BasePoints object using the cat class method', 'create a CameraPoints instance from a tensor with N x 3 point coordinates in CAM space', 'flip CameraPoints horizontally or vertically along the BEV direction using the flip method', 'check which CameraPoints fall within a given BEV point range using in_range_bev', 'convert CameraPoints from CAM coordinates to another coordinate system using convert_to', 'review the CameraPoints class and its rotation_axis attribute set to 1 for Y-axis rotation', 'create a DepthPoints instance from a tensor with N x 3 coordinates in DEPTH mode', 'flip DepthPoints horizontally or vertically along the BEV direction', 'check which DepthPoints fall within a given x_min, y_min, x_max, y_max range', 'convert DepthPoints from DEPTH coordinates to another Coord3DMode using a rotation-translation matrix', 'review the DepthPoints class that extends BasePoints for DEPTH coordinate point cloud operations', 'create a LiDARPoints instance from a tensor with N x 3 point coordinates', 'flip LiDAR points horizontally or vertically along the BEV direction', 'check which LiDAR points fall within a given x and y bounding range', 'convert LiDAR points to a different coordinate mode using a transformation matrix', 'review the LiDARPoints class and its flip, in_range_bev, and convert_to methods']
```

Usage

```
{'create_DepthPoints': 'create a DepthPoints instance from a tensor with N x 3 coordinates in DEPTH mode', 'flip_DepthPoints': 'flip DepthPoints horizontally or vertically along the BEV direction', 'in_range_bev_DepthPoints': 'check which DepthPoints fall within a given x_min, y_min, x_max, y_max range', 'convert_to_DepthPoints': 'convert DepthPoints from DEPTH coordinates to another Coord3DMode using a rotation-translation matrix', 'review_DepthPoints_class': 'review the DepthPoints class that extends BasePoints for DEPTH coordinate point cloud operations'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/points/lidar_points.py

Prompts

```
['create a BasePoints object from a torch tensor or numpy array with N x 3 coordinates', 'rotate the points in a BasePoints object by a given angle around the X, Y, or Z axis', 'translate the points in a BasePoints object by a given 3D translation vector', 'filter points in a BasePoints object to keep only those within a specified 3D bounding box range', 'concatenate a list of BasePoints objects into a single BasePoints object using the cat class method', 'create a CameraPoints instance from a tensor with N x 3 point coordinates in CAM space', 'flip CameraPoints horizontally or vertically along the BEV direction using the flip method', 'check which CameraPoints fall within a given BEV point range using in_range_bev', 'convert CameraPoints from CAM coordinates to another coordinate system using convert_to', 'review the CameraPoints class and its rotation_axis attribute set to 1 for Y-axis rotation', 'create a DepthPoints instance from a tensor with N x 3 coordinates in DEPTH mode', 'flip DepthPoints horizontally or vertically along the BEV direction', 'check which DepthPoints fall within a given x_min, y_min, x_max, y_max range', 'convert DepthPoints from DEPTH coordinates to another Coord3DMode using a rotation-translation matrix', 'review the DepthPoints class that extends BasePoints for DEPTH coordinate point cloud operations', 'create a LiDARPoints instance from a tensor with N x 3 point coordinates', 'flip LiDAR points horizontally or vertically along the BEV direction', 'check which LiDAR points fall within a given x and y bounding range', 'convert LiDAR points to a different coordinate mode using a transformation matrix', 'review the LiDARPoints class and its flip, in_range_bev, and convert_to methods']
```

Usage

```
{'create_LiDARPoints': 'create a LiDARPoints instance from a tensor with N x 3 point coordinates', 'flip_LiDARPoints': 'flip LiDAR points horizontally or vertically along the BEV direction', 'in_range_bev_LiDARPoints': 'check which LiDAR points fall within a given x and y bounding range', 'convert_to_LiDARPoints': 'convert LiDAR points to a different coordinate mode using a transformation matrix', 'review_LiDARPoints': 'review the LiDARPoints class and its flip, in_range_bev, and convert_to methods'}
```

