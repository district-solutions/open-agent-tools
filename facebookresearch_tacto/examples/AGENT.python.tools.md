# Agent Python Tools

- repo: facebookresearch/tacto
- repo_uri: https://github.com/facebookresearch/tacto

## File: facebookresearch_tacto/examples/camera.py

Prompts

```
['create a Camera instance with custom width and height for a PyBullet simulation', 'get the RGB color image and depth image from the PyBullet Camera', 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute the projection matrix with field of view for the Camera', 'review the Camera class and its PyBullet view and projection matrix setup', 'generate a depthmap simulating a ball contact at a given xyz position', 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render color and depth images from a depthmap using the TACTO renderer', 'get the file path to the TACTO digit sensor configuration', 'run the demo to render and plot a ball contact imprint using TACTO', 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold', 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get the current end effector position, orientation, and gripper width states', 'set robot actions by overwriting current states with desired end effector and gripper targets', 'move the Sawyer gripper to a target position with optional orientation and grip force', 'recursively overwrite values in one dictionary with non-None values from another dictionary', 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert an observation dict, list, or numpy array into a Gym observation space', 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point']
```

Usage

```
{'create_camera_instance': 'create a Camera instance with custom width and height for a PyBullet simulation', 'get_camera_image': 'get the RGB color image and depth image from the PyBullet Camera', 'compute_view_matrix': 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute_projection_matrix': 'compute the projection matrix with field of view for the Camera', 'review_camera_class': 'review the Camera class and its PyBullet view and projection matrix setup'}
```

## File: facebookresearch_tacto/examples/demo_render.py

Prompts

```
['create a Camera instance with custom width and height for a PyBullet simulation', 'get the RGB color image and depth image from the PyBullet Camera', 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute the projection matrix with field of view for the Camera', 'review the Camera class and its PyBullet view and projection matrix setup', 'generate a depthmap simulating a ball contact at a given xyz position', 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render color and depth images from a depthmap using the TACTO renderer', 'get the file path to the TACTO digit sensor configuration', 'run the demo to render and plot a ball contact imprint using TACTO', 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold', 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get the current end effector position, orientation, and gripper width states', 'set robot actions by overwriting current states with desired end effector and gripper targets', 'move the Sawyer gripper to a target position with optional orientation and grip force', 'recursively overwrite values in one dictionary with non-None values from another dictionary', 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert an observation dict, list, or numpy array into a Gym observation space', 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point']
```

Usage

```
{'generate_ball_depthmap': 'generate a depthmap simulating a ball contact at a given xyz position', 'create_tacto_renderer': 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render_from_depth': 'render color and depth images from a depthmap using the TACTO renderer', 'get_digit_config_path': 'get the file path to the TACTO digit sensor configuration', 'run_demo_render': 'run the demo to render and plot a ball contact imprint using TACTO'}
```

## File: facebookresearch_tacto/examples/demo_sawyer_gripper_env.py

Prompts

```
['create a Camera instance with custom width and height for a PyBullet simulation', 'get the RGB color image and depth image from the PyBullet Camera', 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute the projection matrix with field of view for the Camera', 'review the Camera class and its PyBullet view and projection matrix setup', 'generate a depthmap simulating a ball contact at a given xyz position', 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render color and depth images from a depthmap using the TACTO renderer', 'get the file path to the TACTO digit sensor configuration', 'run the demo to render and plot a ball contact imprint using TACTO', 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold', 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get the current end effector position, orientation, and gripper width states', 'set robot actions by overwriting current states with desired end effector and gripper targets', 'move the Sawyer gripper to a target position with optional orientation and grip force', 'recursively overwrite values in one dictionary with non-None values from another dictionary', 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert an observation dict, list, or numpy array into a Gym observation space', 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point']
```

Usage

```
{'run_grasping_policy_demo': 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create_grasping_policy': 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build_grasp_action_sequence': 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test_grasping_policy_forward': 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review_grasping_policy_phases': 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold'}
```

## File: facebookresearch_tacto/examples/sawyer_gripper.py

Prompts

```
['create a Camera instance with custom width and height for a PyBullet simulation', 'get the RGB color image and depth image from the PyBullet Camera', 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute the projection matrix with field of view for the Camera', 'review the Camera class and its PyBullet view and projection matrix setup', 'generate a depthmap simulating a ball contact at a given xyz position', 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render color and depth images from a depthmap using the TACTO renderer', 'get the file path to the TACTO digit sensor configuration', 'run the demo to render and plot a ball contact imprint using TACTO', 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold', 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get the current end effector position, orientation, and gripper width states', 'set robot actions by overwriting current states with desired end effector and gripper targets', 'move the Sawyer gripper to a target position with optional orientation and grip force', 'recursively overwrite values in one dictionary with non-None values from another dictionary', 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert an observation dict, list, or numpy array into a Gym observation space', 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point']
```

Usage

```
{'init_SawyerGripper': 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get_states_SawyerGripper': 'get the current end effector position, orientation, and gripper width states', 'set_actions_SawyerGripper': 'set robot actions by overwriting current states with desired end effector and gripper targets', 'go_SawyerGripper': 'move the Sawyer gripper to a target position with optional orientation and grip force', 'overwrite_dict': 'recursively overwrite values in one dictionary with non-None values from another dictionary'}
```

## File: facebookresearch_tacto/examples/sawyer_gripper_env.py

Prompts

```
['create a Camera instance with custom width and height for a PyBullet simulation', 'get the RGB color image and depth image from the PyBullet Camera', 'compute the view matrix from yaw, pitch, and roll for the Camera', 'compute the projection matrix with field of view for the Camera', 'review the Camera class and its PyBullet view and projection matrix setup', 'generate a depthmap simulating a ball contact at a given xyz position', 'create a TACTO Renderer with specified width, height, and digit sensor config path', 'render color and depth images from a depthmap using the TACTO renderer', 'get the file path to the TACTO digit sensor configuration', 'run the demo to render and plot a ball contact imprint using TACTO', 'run the demo to execute a hard-coded grasping policy on the sawyer gripper gym environment', 'create a GraspingPolicy instance that inherits from torch.nn.Module and takes a gym environment', 'build a time-based action sequence that positions, closes, lifts, and holds a gripper', 'test the GraspingPolicy forward method to return gripper actions based on environment states', 'review the GraspingPolicy forward method phases for approach, descend, close, lift, and hold', 'initialize a SawyerGripper robot instance with robot_params and init_state configuration', 'get the current end effector position, orientation, and gripper width states', 'set robot actions by overwriting current states with desired end effector and gripper targets', 'move the Sawyer gripper to a target position with optional orientation and grip force', 'recursively overwrite values in one dictionary with non-None values from another dictionary', 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert an observation dict, list, or numpy array into a Gym observation space', 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point']
```

Usage

```
{'create_sawyer_gripper_env': 'create a SawyerGripperEnv instance with a custom config path for the PyBullet simulation', 'run_step_sawyer_gripper_env': 'run one timestep of the SawyerGripperEnv dynamics by calling step with an action dict', 'reset_sawyer_gripper_env': 'reset the SawyerGripperEnv to a random object position and return the initial observation', 'convert_obs_to_obs_space': 'convert an observation dict, list, or numpy array into a Gym observation space', 'register_sawyer_gripper_v0': 'register the sawyer-gripper-v0 environment with Gym using make_sawyer_gripper_env as the entry point'}
```

