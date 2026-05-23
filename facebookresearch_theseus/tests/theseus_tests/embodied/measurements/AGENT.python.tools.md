# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/embodied/measurements/test_between.py

Prompts

```
['test the Between cost function jacobian computation for SO2, SO3, SE2, and SE3 groups', 'test copying a Between cost function with SE2 variables and verify all attributes are deep copied', 'test the Between error computation for Point2 variables by comparing against expected p2 minus p1 minus measurement', 'test the Between error computation for SO2 variables against precomputed expected error values from numpy file', 'test the Between jacobian for SE3 variables by comparing against torch autograd functional jacobian results', 'test the MovingFrameBetween copy method to verify all SE2 frames and poses are deep copied', 'test the MovingFrameBetween jacobian computation against numeric jacobian for multiple batch sizes', 'test the MovingFrameBetween error calculation with predefined SE2 inputs and expected outputs', 'build a MovingFrameBetween cost function with SE2 frames, poses, measurement, and ScaleCostWeight', 'review the MovingFrameBetween jacobians method to verify error and jacobian tensor correctness', 'test the Reprojection cost term by computing residuals between projected world points and image feature points', 'test the Reprojection jacobians by comparing numerical finite-difference derivatives against analytical jacobians', 'create a Theseus SE3 camera pose from translation and quaternion rotation tensors', 'create Theseus Vector variables for camera calibration parameters like focal length and distortion coefficients', 'test the SE3 retract method by perturbing camera pose and verifying error changes match numerical gradients']
```

Usage

```
{'test_Between_jacobian_SO2_SO3_SE2_SE3': 'test the Between cost function jacobian computation for SO2, SO3, SE2, and SE3 groups', 'test_Between_copy_SE2': 'test copying a Between cost function with SE2 variables and verify all attributes are deep copied', 'test_Between_error_Point2': 'test the Between error computation for Point2 variables by comparing against expected p2 minus p1 minus measurement', 'test_Between_error_SO2': 'test the Between error computation for SO2 variables against precomputed expected error values from numpy file', 'test_Between_jacobian_SE3': 'test the Between jacobian for SE3 variables by comparing against torch autograd functional jacobian results'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/measurements/test_moving_frame_between.py

Prompts

```
['test the Between cost function jacobian computation for SO2, SO3, SE2, and SE3 groups', 'test copying a Between cost function with SE2 variables and verify all attributes are deep copied', 'test the Between error computation for Point2 variables by comparing against expected p2 minus p1 minus measurement', 'test the Between error computation for SO2 variables against precomputed expected error values from numpy file', 'test the Between jacobian for SE3 variables by comparing against torch autograd functional jacobian results', 'test the MovingFrameBetween copy method to verify all SE2 frames and poses are deep copied', 'test the MovingFrameBetween jacobian computation against numeric jacobian for multiple batch sizes', 'test the MovingFrameBetween error calculation with predefined SE2 inputs and expected outputs', 'build a MovingFrameBetween cost function with SE2 frames, poses, measurement, and ScaleCostWeight', 'review the MovingFrameBetween jacobians method to verify error and jacobian tensor correctness', 'test the Reprojection cost term by computing residuals between projected world points and image feature points', 'test the Reprojection jacobians by comparing numerical finite-difference derivatives against analytical jacobians', 'create a Theseus SE3 camera pose from translation and quaternion rotation tensors', 'create Theseus Vector variables for camera calibration parameters like focal length and distortion coefficients', 'test the SE3 retract method by perturbing camera pose and verifying error changes match numerical gradients']
```

Usage

```
{'test_copy_moving_frame_between': 'test the MovingFrameBetween copy method to verify all SE2 frames and poses are deep copied', 'test_jacobian_moving_frame_between': 'test the MovingFrameBetween jacobian computation against numeric jacobian for multiple batch sizes', 'test_error_moving_frame_between_se2': 'test the MovingFrameBetween error calculation with predefined SE2 inputs and expected outputs', 'build_MovingFrameBetween_cost_function': 'build a MovingFrameBetween cost function with SE2 frames, poses, measurement, and ScaleCostWeight', 'review_MovingFrameBetween_jacobians': 'review the MovingFrameBetween jacobians method to verify error and jacobian tensor correctness'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/measurements/test_reprojection.py

Prompts

```
['test the Between cost function jacobian computation for SO2, SO3, SE2, and SE3 groups', 'test copying a Between cost function with SE2 variables and verify all attributes are deep copied', 'test the Between error computation for Point2 variables by comparing against expected p2 minus p1 minus measurement', 'test the Between error computation for SO2 variables against precomputed expected error values from numpy file', 'test the Between jacobian for SE3 variables by comparing against torch autograd functional jacobian results', 'test the MovingFrameBetween copy method to verify all SE2 frames and poses are deep copied', 'test the MovingFrameBetween jacobian computation against numeric jacobian for multiple batch sizes', 'test the MovingFrameBetween error calculation with predefined SE2 inputs and expected outputs', 'build a MovingFrameBetween cost function with SE2 frames, poses, measurement, and ScaleCostWeight', 'review the MovingFrameBetween jacobians method to verify error and jacobian tensor correctness', 'test the Reprojection cost term by computing residuals between projected world points and image feature points', 'test the Reprojection jacobians by comparing numerical finite-difference derivatives against analytical jacobians', 'create a Theseus SE3 camera pose from translation and quaternion rotation tensors', 'create Theseus Vector variables for camera calibration parameters like focal length and distortion coefficients', 'test the SE3 retract method by perturbing camera pose and verifying error changes match numerical gradients']
```

Usage

```
{'test_Reprojection_residual': 'test the Reprojection cost term by computing residuals between projected world points and image feature points', 'test_Reprojection_jacobians': 'test the Reprojection jacobians by comparing numerical finite-difference derivatives against analytical jacobians', 'create_theseus_SE3_pose': 'create a Theseus SE3 camera pose from translation and quaternion rotation tensors', 'create_theseus_Vector_calibration': 'create Theseus Vector variables for camera calibration parameters like focal length and distortion coefficients', 'test_RE3_retract': 'test the SE3 retract method by perturbing camera pose and verifying error changes match numerical gradients'}
```

