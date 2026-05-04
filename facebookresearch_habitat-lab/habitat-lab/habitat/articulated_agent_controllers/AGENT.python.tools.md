# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_base_controller.py

Prompts

```
['create a Pose object with joint quaternions and a root transform Matrix4', 'create a Motion object from joint quaternion arrays and transform arrays with fps', 'initialize a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the HumanoidBaseController joints and transforms as a flattened list of floats', 'build a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame joint positions and root transform toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a specified hand', 'calculate a walking motion frame toward a target position while facing a separate target direction', 'compute interpolated humanoid joint states and root transform for a 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance that loads motion poses from a numpy file path', 'reset the HumanoidSeqPoseController to its initial pose using a base transformation matrix', 'advance the HumanoidSeqPoseController to the next pose in the motion sequence with optional cycling', 'move the HumanoidSeqPoseController to the previous pose in the motion sequence with optional cycling', 'calculate and set joint transforms for the current frame in the HumanoidSeqPoseController']
```

Usage

```
{'create_pose': 'create a Pose object with joint quaternions and a root transform Matrix4', 'create_motion': 'create a Motion object from joint quaternion arrays and transform arrays with fps', 'init_humanoid_base_controller': 'initialize a HumanoidBaseController with a custom motion fps and base offset vector', 'reset_humanoid_base_controller': 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get_pose_vectorized': 'get the HumanoidBaseController joints and transforms as a flattened list of floats'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_rearrange_controller.py

Prompts

```
['create a Pose object with joint quaternions and a root transform Matrix4', 'create a Motion object from joint quaternion arrays and transform arrays with fps', 'initialize a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the HumanoidBaseController joints and transforms as a flattened list of floats', 'build a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame joint positions and root transform toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a specified hand', 'calculate a walking motion frame toward a target position while facing a separate target direction', 'compute interpolated humanoid joint states and root transform for a 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance that loads motion poses from a numpy file path', 'reset the HumanoidSeqPoseController to its initial pose using a base transformation matrix', 'advance the HumanoidSeqPoseController to the next pose in the motion sequence with optional cycling', 'move the HumanoidSeqPoseController to the previous pose in the motion sequence with optional cycling', 'calculate and set joint transforms for the current frame in the HumanoidSeqPoseController']
```

Usage

```
{'build_HumanoidRearrangeController': 'build a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate_walk_pose': 'calculate the next walking motion frame joint positions and root transform toward a target position', 'calculate_reach_pose': 'calculate the humanoid joint pose and root transform to reach a 3D position with a specified hand', 'calculate_walk_pose_directional': 'calculate a walking motion frame toward a target position while facing a separate target direction', 'trilinear_interpolate_pose': 'compute interpolated humanoid joint states and root transform for a 3D reach position using trilinear interpolation'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agent_controllers/humanoid_seq_pose_controller.py

Prompts

```
['create a Pose object with joint quaternions and a root transform Matrix4', 'create a Motion object from joint quaternion arrays and transform arrays with fps', 'initialize a HumanoidBaseController with a custom motion fps and base offset vector', 'reset the HumanoidBaseController joints to rest state with a base transformation matrix', 'get the HumanoidBaseController joints and transforms as a flattened list of floats', 'build a HumanoidRearrangeController instance by loading walk pose data from a pickle file path', 'calculate the next walking motion frame joint positions and root transform toward a target position', 'calculate the humanoid joint pose and root transform to reach a 3D position with a specified hand', 'calculate a walking motion frame toward a target position while facing a separate target direction', 'compute interpolated humanoid joint states and root transform for a 3D reach position using trilinear interpolation', 'create a HumanoidSeqPoseController instance that loads motion poses from a numpy file path', 'reset the HumanoidSeqPoseController to its initial pose using a base transformation matrix', 'advance the HumanoidSeqPoseController to the next pose in the motion sequence with optional cycling', 'move the HumanoidSeqPoseController to the previous pose in the motion sequence with optional cycling', 'calculate and set joint transforms for the current frame in the HumanoidSeqPoseController']
```

Usage

```
{'create_HumanoidSeqPoseController': 'create a HumanoidSeqPoseController instance that loads motion poses from a numpy file path', 'reset_HumanoidSeqPoseController': 'reset the HumanoidSeqPoseController to its initial pose using a base transformation matrix', 'next_pose_HumanoidSeqPoseController': 'advance the HumanoidSeqPoseController to the next pose in the motion sequence with optional cycling', 'prev_pose_HumanoidSeqPoseController': 'move the HumanoidSeqPoseController to the previous pose in the motion sequence with optional cycling', 'calculate_pose_HumanoidSeqPoseController': 'calculate and set joint transforms for the current frame in the HumanoidSeqPoseController'}
```

