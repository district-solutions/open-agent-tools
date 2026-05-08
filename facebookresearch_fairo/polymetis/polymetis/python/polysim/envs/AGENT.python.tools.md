# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/abstract_env.py

Prompts

```
['implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review the AbstractControlledEnv reset method signature for environment initialization', 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints', 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities', 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute the end-effector position and orientation quaternion from given joint positions', 'compute joint positions that satisfy a target end-effector position and orientation', 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place an agent at a specified position and orientation in the Habitat simulator scene', 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'get the current joint positions and velocities from the MuJoCo simulation', 'get commanded, applied, measured, and external joint torque arrays from the simulation']
```

Usage

```
{'implement_AbstractControlledEnv': 'implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review_reset_method': 'review the AbstractControlledEnv reset method signature for environment initialization', 'review_get_num_dofs': 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review_get_current_joint_pos_vel': 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review_apply_joint_torques': 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/bullet_locomotor.py

Prompts

```
['implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review the AbstractControlledEnv reset method signature for environment initialization', 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints', 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities', 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute the end-effector position and orientation quaternion from given joint positions', 'compute joint positions that satisfy a target end-effector position and orientation', 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place an agent at a specified position and orientation in the Habitat simulator scene', 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'get the current joint positions and velocities from the MuJoCo simulation', 'get commanded, applied, measured, and external joint torque arrays from the simulation']
```

Usage

```
{'create_DaisyLocomotorEnv': 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get_states_DaisyLocomotorEnv': 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset_then_step_DaisyLocomotorEnv': 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set_friction_parameters_DaisyLocomotorEnv': 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get_current_full_state_DaisyLocomotorEnv': 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/bullet_manipulator.py

Prompts

```
['implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review the AbstractControlledEnv reset method signature for environment initialization', 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints', 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities', 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute the end-effector position and orientation quaternion from given joint positions', 'compute joint positions that satisfy a target end-effector position and orientation', 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place an agent at a specified position and orientation in the Habitat simulator scene', 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'get the current joint positions and velocities from the MuJoCo simulation', 'get commanded, applied, measured, and external joint torque arrays from the simulation']
```

Usage

```
{'create_bullet_manipulator_env': 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load_robot_from_urdf': 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply_joint_torques': 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute_forward_kinematics': 'compute the end-effector position and orientation quaternion from given joint positions', 'compute_inverse_kinematics': 'compute joint positions that satisfy a target end-effector position and orientation'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/habitat_manipulator.py

Prompts

```
['implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review the AbstractControlledEnv reset method signature for environment initialization', 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints', 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities', 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute the end-effector position and orientation quaternion from given joint positions', 'compute joint positions that satisfy a target end-effector position and orientation', 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place an agent at a specified position and orientation in the Habitat simulator scene', 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'get the current joint positions and velocities from the MuJoCo simulation', 'get commanded, applied, measured, and external joint torque arrays from the simulation']
```

Usage

```
{'create_habitat_simulator_config': 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place_agent_in_scene': 'place an agent at a specified position and orientation in the Habitat simulator scene', 'place_robot_from_agent': 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create_habitat_manipulator_env': 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'apply_joint_torques': 'apply joint torques to the robot and step the physics simulation forward by one timestep'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/envs/mujoco_manipulator.py

Prompts

```
['implement a subclass of AbstractControlledEnv that provides concrete simulation environment methods', 'review the AbstractControlledEnv reset method signature for environment initialization', 'review the AbstractControlledEnv get_num_dofs method for returning control input dimensions', 'review the AbstractControlledEnv get_current_joint_pos_vel method for returning joint positions and velocities', 'review the AbstractControlledEnv apply_joint_torques method for applying desired torques to joints', 'create a DaisyLocomotorEnv instance with custom hz, gui, n_dofs, and control_mode parameters', 'get the full robot state dictionary with joint positions, velocities, and base orientation', 'reset the robot to a desired joint state and apply torque control for one simulation step', 'set restitution, lateral friction, and damping parameters on all robot joints via PyBullet', 'get the concatenated full state vector including joint pos, base pos, orientation, and velocities', 'create a BulletManipulatorEnv instance with a robot model config and PyBullet GUI or DIRECT mode', 'load a robot URDF file into the PyBullet simulation using load_robot_description_from_urdf', 'apply a numpy array of torques to robot joints with optional gravity compensation', 'compute the end-effector position and orientation quaternion from given joint positions', 'compute joint positions that satisfy a target end-effector position and orientation', 'create a Habitat simulator configuration with RGB and depth camera sensors from a GLB scene path', 'place an agent at a specified position and orientation in the Habitat simulator scene', 'position a robot articulated object relative to the agent using local base position and orientation vector', 'create a HabitatManipulatorEnv that loads a URDF robot into a Habitat scene with gravity compensation and joint damping', 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'get the current joint positions and velocities from the MuJoCo simulation', 'get commanded, applied, measured, and external joint torque arrays from the simulation']
```

Usage

```
{'create_mujoco_manipulator_env': 'create a MujocoManipulatorEnv instance with a robot model config and optional GUI mode', 'reset_simulation': 'reset the MujocoManipulatorEnv simulation to a specified joint position and velocity', 'apply_joint_torques': 'apply torque commands to robot joints and step the MuJoCo simulation forward', 'get_joint_pos_vel': 'get the current joint positions and velocities from the MuJoCo simulation', 'get_joint_torques': 'get commanded, applied, measured, and external joint torque arrays from the simulation'}
```

