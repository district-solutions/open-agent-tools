# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_base_controller.py

Prompts

```
['create a Pose object from joint quaternions and a root transform Matrix4', 'create a Motion from joint quaternion arrays, transform arrays, displacement, and fps', 'create a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the controller joints, offset, and base transform as a flattened list of floats', 'create a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame so the humanoid moves toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a hand', 'calculate a walking motion frame where the humanoid moves toward a target while facing a separate direction', 'compute interpolated humanoid joint states and root transform for a given 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance by loading motion poses from a numpy file path', 'reset the humanoid controller to its rest state with a given base transformation matrix', 'apply a base transformation matrix to offset all subsequent poses relative to it', 'advance to the next pose in the motion sequence with optional cycling behavior', 'calculate and set joint transforms for the current motion frame with optional auto-advance']
```

Usage

```
{'create_Pose': 'create a Pose object from joint quaternions and a root transform Matrix4', 'create_Motion': 'create a Motion from joint quaternion arrays, transform arrays, displacement, and fps', 'create_HumanoidBaseController': 'create a HumanoidBaseController with a custom motion fps and base offset vector', 'reset_HumanoidBaseController': 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get_pose_HumanoidBaseController': 'get the controller joints, offset, and base transform as a flattened list of floats'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_rearrange_controller.py

Prompts

```
['create a Pose object from joint quaternions and a root transform Matrix4', 'create a Motion from joint quaternion arrays, transform arrays, displacement, and fps', 'create a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the controller joints, offset, and base transform as a flattened list of floats', 'create a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame so the humanoid moves toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a hand', 'calculate a walking motion frame where the humanoid moves toward a target while facing a separate direction', 'compute interpolated humanoid joint states and root transform for a given 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance by loading motion poses from a numpy file path', 'reset the humanoid controller to its rest state with a given base transformation matrix', 'apply a base transformation matrix to offset all subsequent poses relative to it', 'advance to the next pose in the motion sequence with optional cycling behavior', 'calculate and set joint transforms for the current motion frame with optional auto-advance']
```

Usage

```
{'create_HumanoidRearrangeController': 'create a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate_walk_pose': 'calculate the next walking motion frame so the humanoid moves toward a target position', 'calculate_reach_pose': 'calculate the humanoid joint pose and root transform to reach a 3D position with a hand', 'calculate_walk_pose_directional': 'calculate a walking motion frame where the humanoid moves toward a target while facing a separate direction', 'trilinear_interpolate_pose': 'compute interpolated humanoid joint states and root transform for a given 3D reach position using trilinear interpolation'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_seq_pose_controller.py

Prompts

```
['create a Pose object from joint quaternions and a root transform Matrix4', 'create a Motion from joint quaternion arrays, transform arrays, displacement, and fps', 'create a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the controller joints, offset, and base transform as a flattened list of floats', 'create a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame so the humanoid moves toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a hand', 'calculate a walking motion frame where the humanoid moves toward a target while facing a separate direction', 'compute interpolated humanoid joint states and root transform for a given 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance by loading motion poses from a numpy file path', 'reset the humanoid controller to its rest state with a given base transformation matrix', 'apply a base transformation matrix to offset all subsequent poses relative to it', 'advance to the next pose in the motion sequence with optional cycling behavior', 'calculate and set joint transforms for the current motion frame with optional auto-advance']
```

Usage

```
{'init_HumanoidSeqPoseController': 'create a HumanoidSeqPoseController instance by loading motion poses from a numpy file path', 'reset_HumanoidSeqPoseController': 'reset the humanoid controller to its rest state with a given base transformation matrix', 'apply_base_transformation_HumanoidSeqPoseController': 'apply a base transformation matrix to offset all subsequent poses relative to it', 'next_pose_HumanoidSeqPoseController': 'advance to the next pose in the motion sequence with optional cycling behavior', 'calculate_pose_HumanoidSeqPoseController': 'calculate and set joint transforms for the current motion frame with optional auto-advance'}
```

