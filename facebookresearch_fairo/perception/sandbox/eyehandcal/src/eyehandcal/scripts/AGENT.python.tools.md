# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/perception/sandbox/eyehandcal/src/eyehandcal/scripts/collect_data_and_cal.py

Prompts

```
['run the eye-hand calibration script to collect robot poses and calibrate camera intrinsics using ArUco markers', 'run the realsense_images generator to capture stable RGB images from Intel RealSense cameras with motion detection', 'run the robot_poses generator to move a robot to sampled poses and yield end-effector positions', 'run sample_poses_from_data to generate robot poses by sampling points from a convex hull of XYZ coordinates', 'run extract_obs_data_std to extract standardized observation data and build projection matrices for a given camera index', 'run the script to record robot end-effector calibration points using camera and ARTag markers', 'run the script to collect robot xyz position poses via interactive camera view prompts', 'run the script to collect robot quaternion orientation poses via interactive camera view prompts', 'run the script to detect ARTag markers in Realsense camera images using FairoTag', 'run the script to save collected xyz and quaternion poses to calibration_points.json']
```

Usage

```
{'run_eye_hand_calibration': 'run the eye-hand calibration script to collect robot poses and calibrate camera intrinsics using ArUco markers', 'run_realsense_images': 'run the realsense_images generator to capture stable RGB images from Intel RealSense cameras with motion detection', 'run_robot_poses': 'run the robot_poses generator to move a robot to sampled poses and yield end-effector positions', 'run_sample_poses_from_data': 'run sample_poses_from_data to generate robot poses by sampling points from a convex hull of XYZ coordinates', 'run_extract_obs_data_std': 'run extract_obs_data_std to extract standardized observation data and build projection matrices for a given camera index'}
```

## File: facebookresearch_fairo/perception/sandbox/eyehandcal/src/eyehandcal/scripts/record_calibration_points.py

Prompts

```
['run the eye-hand calibration script to collect robot poses and calibrate camera intrinsics using ArUco markers', 'run the realsense_images generator to capture stable RGB images from Intel RealSense cameras with motion detection', 'run the robot_poses generator to move a robot to sampled poses and yield end-effector positions', 'run sample_poses_from_data to generate robot poses by sampling points from a convex hull of XYZ coordinates', 'run extract_obs_data_std to extract standardized observation data and build projection matrices for a given camera index', 'run the script to record robot end-effector calibration points using camera and ARTag markers', 'run the script to collect robot xyz position poses via interactive camera view prompts', 'run the script to collect robot quaternion orientation poses via interactive camera view prompts', 'run the script to detect ARTag markers in Realsense camera images using FairoTag', 'run the script to save collected xyz and quaternion poses to calibration_points.json']
```

Usage

```
{'run_record_calibration_points': 'run the script to record robot end-effector calibration points using camera and ARTag markers', 'run_record_xyz_poses': 'run the script to collect robot xyz position poses via interactive camera view prompts', 'run_record_quat_poses': 'run the script to collect robot quaternion orientation poses via interactive camera view prompts', 'run_detect_markers': 'run the script to detect ARTag markers in Realsense camera images using FairoTag', 'run_save_calibration_json': 'run the script to save collected xyz and quaternion poses to calibration_points.json'}
```

