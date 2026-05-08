# Agent Python Tools

- repo: facebookresearch/humenv
- repo_uri: https://github.com/facebookresearch/humenv

## File: facebookresearch_humenv/humenv/env.py

Prompts

```
['create a HumEnv humanoid simulation environment with a reward task, XML model, and state init mode', 'reset the HumEnv environment to a t-pose, fall, or MoCap-based initial state', 'step the HumEnv environment forward with an action and return observation, reward, and termination', 'render the HumEnv simulation as an RGB array from the configured camera angle', 'compute a proprioceptive observation dictionary with heading-invariant local body positions, rotations, and velocities', 'reset a MuJoCo human model to a standing T-pose with zero velocity', 'reset a MuJoCo human model to a randomized falling state with random orientation and actions', 'reset a MuJoCo human model to either T-pose or a falling state based on a probability', "convert Euler angles to a quaternion using MuJoCo's mju_euler2Quat utility function", 'simulate random control actions on a MuJoCo model for a specified number of integration steps', 'create a LocomotionReward instance to compute humanoid locomotion rewards with configurable speed and angle', 'create a JumpReward instance to compute rewards for humanoid jumping to a target height', 'create a HeadstandReward instance to compute rewards for maintaining a headstand pose', 'create a RotationReward instance to compute rewards for rotating around a specified axis at target velocity', 'create an ArmsReward instance to compute rewards for raising arms to specified left and right poses', 'convert a numpy quaternion array from wxyz format to xyzw format using wxyz_to_xyzw', 'rotate a 3D vector by a quaternion using quat_rotate to apply the rotation', 'compute the heading angle in radians from a quaternion using calc_heading', 'multiply two quaternion arrays together using quat_mul to compose rotations', 'convert a normalized quaternion to an exponential map representation using quat_to_exp_map']
```

Usage

```
{'create_HumEnv': 'create a HumEnv humanoid simulation environment with a reward task, XML model, and state init mode', 'reset_HumEnv': 'reset the HumEnv environment to a t-pose, fall, or MoCap-based initial state', 'step_HumEnv': 'step the HumEnv environment forward with an action and return observation, reward, and termination', 'render_HumEnv': 'render the HumEnv simulation as an RGB array from the configured camera angle', 'compute_humanoid_self_obs_v2': 'compute a proprioceptive observation dictionary with heading-invariant local body positions, rotations, and velocities'}
```

## File: facebookresearch_humenv/humenv/reset.py

Prompts

```
['create a HumEnv humanoid simulation environment with a reward task, XML model, and state init mode', 'reset the HumEnv environment to a t-pose, fall, or MoCap-based initial state', 'step the HumEnv environment forward with an action and return observation, reward, and termination', 'render the HumEnv simulation as an RGB array from the configured camera angle', 'compute a proprioceptive observation dictionary with heading-invariant local body positions, rotations, and velocities', 'reset a MuJoCo human model to a standing T-pose with zero velocity', 'reset a MuJoCo human model to a randomized falling state with random orientation and actions', 'reset a MuJoCo human model to either T-pose or a falling state based on a probability', "convert Euler angles to a quaternion using MuJoCo's mju_euler2Quat utility function", 'simulate random control actions on a MuJoCo model for a specified number of integration steps', 'create a LocomotionReward instance to compute humanoid locomotion rewards with configurable speed and angle', 'create a JumpReward instance to compute rewards for humanoid jumping to a target height', 'create a HeadstandReward instance to compute rewards for maintaining a headstand pose', 'create a RotationReward instance to compute rewards for rotating around a specified axis at target velocity', 'create an ArmsReward instance to compute rewards for raising arms to specified left and right poses', 'convert a numpy quaternion array from wxyz format to xyzw format using wxyz_to_xyzw', 'rotate a 3D vector by a quaternion using quat_rotate to apply the rotation', 'compute the heading angle in radians from a quaternion using calc_heading', 'multiply two quaternion arrays together using quat_mul to compose rotations', 'convert a normalized quaternion to an exponential map representation using quat_to_exp_map']
```

Usage

```
{'reset_human_to_tpose': 'reset a MuJoCo human model to a standing T-pose with zero velocity', 'reset_human_to_fall': 'reset a MuJoCo human model to a randomized falling state with random orientation and actions', 'reset_human_default_or_fall': 'reset a MuJoCo human model to either T-pose or a falling state based on a probability', 'convert_euler_to_quaternion': "convert Euler angles to a quaternion using MuJoCo's mju_euler2Quat utility function", 'simulate_random_actions': 'simulate random control actions on a MuJoCo model for a specified number of integration steps'}
```

## File: facebookresearch_humenv/humenv/rewards.py

Prompts

```
['create a HumEnv humanoid simulation environment with a reward task, XML model, and state init mode', 'reset the HumEnv environment to a t-pose, fall, or MoCap-based initial state', 'step the HumEnv environment forward with an action and return observation, reward, and termination', 'render the HumEnv simulation as an RGB array from the configured camera angle', 'compute a proprioceptive observation dictionary with heading-invariant local body positions, rotations, and velocities', 'reset a MuJoCo human model to a standing T-pose with zero velocity', 'reset a MuJoCo human model to a randomized falling state with random orientation and actions', 'reset a MuJoCo human model to either T-pose or a falling state based on a probability', "convert Euler angles to a quaternion using MuJoCo's mju_euler2Quat utility function", 'simulate random control actions on a MuJoCo model for a specified number of integration steps', 'create a LocomotionReward instance to compute humanoid locomotion rewards with configurable speed and angle', 'create a JumpReward instance to compute rewards for humanoid jumping to a target height', 'create a HeadstandReward instance to compute rewards for maintaining a headstand pose', 'create a RotationReward instance to compute rewards for rotating around a specified axis at target velocity', 'create an ArmsReward instance to compute rewards for raising arms to specified left and right poses', 'convert a numpy quaternion array from wxyz format to xyzw format using wxyz_to_xyzw', 'rotate a 3D vector by a quaternion using quat_rotate to apply the rotation', 'compute the heading angle in radians from a quaternion using calc_heading', 'multiply two quaternion arrays together using quat_mul to compose rotations', 'convert a normalized quaternion to an exponential map representation using quat_to_exp_map']
```

Usage

```
{'create_LocomotionReward': 'create a LocomotionReward instance to compute humanoid locomotion rewards with configurable speed and angle', 'create_JumpReward': 'create a JumpReward instance to compute rewards for humanoid jumping to a target height', 'create_HeadstandReward': 'create a HeadstandReward instance to compute rewards for maintaining a headstand pose', 'create_RotationReward': 'create a RotationReward instance to compute rewards for rotating around a specified axis at target velocity', 'create_ArmsReward': 'create an ArmsReward instance to compute rewards for raising arms to specified left and right poses'}
```

## File: facebookresearch_humenv/humenv/utils.py

Prompts

```
['create a HumEnv humanoid simulation environment with a reward task, XML model, and state init mode', 'reset the HumEnv environment to a t-pose, fall, or MoCap-based initial state', 'step the HumEnv environment forward with an action and return observation, reward, and termination', 'render the HumEnv simulation as an RGB array from the configured camera angle', 'compute a proprioceptive observation dictionary with heading-invariant local body positions, rotations, and velocities', 'reset a MuJoCo human model to a standing T-pose with zero velocity', 'reset a MuJoCo human model to a randomized falling state with random orientation and actions', 'reset a MuJoCo human model to either T-pose or a falling state based on a probability', "convert Euler angles to a quaternion using MuJoCo's mju_euler2Quat utility function", 'simulate random control actions on a MuJoCo model for a specified number of integration steps', 'create a LocomotionReward instance to compute humanoid locomotion rewards with configurable speed and angle', 'create a JumpReward instance to compute rewards for humanoid jumping to a target height', 'create a HeadstandReward instance to compute rewards for maintaining a headstand pose', 'create a RotationReward instance to compute rewards for rotating around a specified axis at target velocity', 'create an ArmsReward instance to compute rewards for raising arms to specified left and right poses', 'convert a numpy quaternion array from wxyz format to xyzw format using wxyz_to_xyzw', 'rotate a 3D vector by a quaternion using quat_rotate to apply the rotation', 'compute the heading angle in radians from a quaternion using calc_heading', 'multiply two quaternion arrays together using quat_mul to compose rotations', 'convert a normalized quaternion to an exponential map representation using quat_to_exp_map']
```

Usage

```
{'convert_quaternion_wxyz_to_xyzw': 'convert a numpy quaternion array from wxyz format to xyzw format using wxyz_to_xyzw', 'rotate_vector_by_quaternion': 'rotate a 3D vector by a quaternion using quat_rotate to apply the rotation', 'compute_heading_from_quaternion': 'compute the heading angle in radians from a quaternion using calc_heading', 'multiply_two_quaternions': 'multiply two quaternion arrays together using quat_mul to compose rotations', 'convert_quaternion_to_exponential_map': 'convert a normalized quaternion to an exponential map representation using quat_to_exp_map'}
```

