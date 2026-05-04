# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/bop_toolkit/bop_toolkit_lib/tests/test_misc.py

Prompts

```
['test misc.transform_pts_Rt to transform a point cloud using a single rotation matrix and translation vector', 'test misct.transform_pts_Rt to batch-transform point clouds across multiple rotation and translation tensors', 'test misc.project_pts to project 3D points onto a 2D image plane using a pinhole camera model', 'test misct.project_pts to batch-project 3D points onto 2D image planes using camera intrinsics and poses', 'test pose_error_htt.project_pts_htt to project 3D points using a Hand Tracking Toolkit PinholePlaneCameraModel', 'test the MSSD pose error metric comparing CPU and batched GPU implementations', 'test the MSPD pose error metric comparing CPU, GPU, and HTT camera implementations', 'generate random pose estimations with rotation and translation for batch testing', 'review the TestPoseErrors unittest class that validates BOP toolkit pose error calculations', 'run the unittest suite to verify MSSD and MSPD pose error metric correctness']
```

Usage

```
{'test_transform_pts_Rt_numpy': 'test misc.transform_pts_Rt to transform a point cloud using a single rotation matrix and translation vector', 'test_transform_pts_Rt_torch': 'test misct.transform_pts_Rt to batch-transform point clouds across multiple rotation and translation tensors', 'test_project_pts_numpy': 'test misc.project_pts to project 3D points onto a 2D image plane using a pinhole camera model', 'test_project_pts_torch': 'test misct.project_pts to batch-project 3D points onto 2D image planes using camera intrinsics and poses', 'test_project_pts_htt': 'test pose_error_htt.project_pts_htt to project 3D points using a Hand Tracking Toolkit PinholePlaneCameraModel'}
```

## File: facebookresearch_foundpose/external/bop_toolkit/bop_toolkit_lib/tests/test_pose_errors.py

Prompts

```
['test misc.transform_pts_Rt to transform a point cloud using a single rotation matrix and translation vector', 'test misct.transform_pts_Rt to batch-transform point clouds across multiple rotation and translation tensors', 'test misc.project_pts to project 3D points onto a 2D image plane using a pinhole camera model', 'test misct.project_pts to batch-project 3D points onto 2D image planes using camera intrinsics and poses', 'test pose_error_htt.project_pts_htt to project 3D points using a Hand Tracking Toolkit PinholePlaneCameraModel', 'test the MSSD pose error metric comparing CPU and batched GPU implementations', 'test the MSPD pose error metric comparing CPU, GPU, and HTT camera implementations', 'generate random pose estimations with rotation and translation for batch testing', 'review the TestPoseErrors unittest class that validates BOP toolkit pose error calculations', 'run the unittest suite to verify MSSD and MSPD pose error metric correctness']
```

Usage

```
{'test_mssd_pose_errors': 'test the MSSD pose error metric comparing CPU and batched GPU implementations', 'test_mspd_pose_errors': 'test the MSPD pose error metric comparing CPU, GPU, and HTT camera implementations', 'generate_random_pose_estimations': 'generate random pose estimations with rotation and translation for batch testing', 'review_TestPoseErrors_class': 'review the TestPoseErrors unittest class that validates BOP toolkit pose error calculations', 'run_pose_error_tests': 'run the unittest suite to verify MSSD and MSPD pose error metric correctness'}
```

