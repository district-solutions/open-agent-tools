# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_navigation/orb_slam2_ros/scripts/orb_slam2_ros/pcdlib.py

Prompts

```
['run the script to reconstruct a 3D point cloud from ORB-SLAM2 RGB and depth images', 'create a DepthImgProcessor to transform depth and RGB images into a camera-frame point cloud', 'get the point cloud in the camera coordinate frame from a depth image using DepthImgProcessor.get_pcd_ic', 'get the point cloud in the world coordinate frame by transforming camera points with an extrinsic matrix', 'create a PointCloudProcessor that subscribes to ORB-SLAM2 pose topics and stitches keyframe point clouds into a world map', 'run the VisualSLAM ROS node to fetch camera pose and reconstruct 3D world using ORB-SLAM2', 'get the camera pose in the world frame as translation, rotation, and homogeneous matrix', 'get the full camera trajectory in the world frame as an array of homogeneous poses', 'get the robot base pose in the world frame derived from camera pose and TF transforms', 'fetch the 3D point cloud with colors that the robot has seen so far in the world frame']
```

Usage

```
{'run_pcd_reconstruction': 'run the script to reconstruct a 3D point cloud from ORB-SLAM2 RGB and depth images', 'create_depth_img_processor': 'create a DepthImgProcessor to transform depth and RGB images into a camera-frame point cloud', 'get_pcd_in_camera_frame': 'get the point cloud in the camera coordinate frame from a depth image using DepthImgProcessor.get_pcd_ic', 'get_pcd_in_world_frame': 'get the point cloud in the world coordinate frame by transforming camera points with an extrinsic matrix', 'create_point_cloud_processor': 'create a PointCloudProcessor that subscribes to ORB-SLAM2 pose topics and stitches keyframe point clouds into a world map'}
```

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_navigation/orb_slam2_ros/scripts/orb_slam2_ros/vslam.py

Prompts

```
['run the script to reconstruct a 3D point cloud from ORB-SLAM2 RGB and depth images', 'create a DepthImgProcessor to transform depth and RGB images into a camera-frame point cloud', 'get the point cloud in the camera coordinate frame from a depth image using DepthImgProcessor.get_pcd_ic', 'get the point cloud in the world coordinate frame by transforming camera points with an extrinsic matrix', 'create a PointCloudProcessor that subscribes to ORB-SLAM2 pose topics and stitches keyframe point clouds into a world map', 'run the VisualSLAM ROS node to fetch camera pose and reconstruct 3D world using ORB-SLAM2', 'get the camera pose in the world frame as translation, rotation, and homogeneous matrix', 'get the full camera trajectory in the world frame as an array of homogeneous poses', 'get the robot base pose in the world frame derived from camera pose and TF transforms', 'fetch the 3D point cloud with colors that the robot has seen so far in the world frame']
```

Usage

```
{'run_vslam_node': 'run the VisualSLAM ROS node to fetch camera pose and reconstruct 3D world using ORB-SLAM2', 'get_camera_pose': 'get the camera pose in the world frame as translation, rotation, and homogeneous matrix', 'get_camera_trajectory': 'get the full camera trajectory in the world frame as an array of homogeneous poses', 'get_base_pose': 'get the robot base pose in the world frame derived from camera pose and TF transforms', 'get_3d_map': 'fetch the 3D point cloud with colors that the robot has seen so far in the world frame'}
```

