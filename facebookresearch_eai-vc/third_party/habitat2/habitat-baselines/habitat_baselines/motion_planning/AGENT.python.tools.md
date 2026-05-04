# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/motion_planning/grasp_generator.py

Prompts

```
['generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision checks', 'generate a RobotTarget for a specified object index by sampling grasp points on its bounding sphere', 'compute feasible joint positions to reach a desired end-effector target using randomized inverse kinematics search', 'sample candidate grasp points on an object bounding sphere and find valid collision-free joint configurations', 'return the default reference joint state array for the robot arm as a numpy array', 'build a MotionPlanner instance with a RearrangeSim and DictConfig to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a joint trajectory', 'test the _is_state_valid method to check if a given joint state is collision free', 'review the _render_verify_motion_plan method that renders a motion plan as a video and verifies collision freedom', 'refactor the _get_path method to customize OMPL planner configuration and state space bounds', 'review the MpSim abstract base class defining the motion planner simulator interface with abstract methods', 'review the HabMpSim class implementing the Habitat motion planner simulator with collision and state management', 'build a python module to use HabMpSim get_collisions to detect collisions between objects in the simulator', 'build a python module to use HabMpSim start_mp to freeze all objects to STATIC before motion planning', 'build a python module to use HabMpSim capture_state to snapshot the current simulator environment state', 'create a JsMpSpace instance with a RearrangeSim and IkHelper to plan robot arm joint-space motion', 'set up an OMPL planning problem with start and goal joint states using JsMpSpace.set_problem', 'convert an OMPL solution path to a numpy array of joint states using JsMpSpace.convert_sol', 'render start and target robot arm configurations to JPEG images using JsMpSpace.render_start_targ', 'get restrictive or non-restrictive joint state limits for the planning problem using JsMpSpace.get_state_lims']
```

Usage

```
{'gen_target_from_ee_pos': 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision checks', 'gen_target_from_obj_idx': 'generate a RobotTarget for a specified object index by sampling grasp points on its bounding sphere', '_gen_goal_state': 'compute feasible joint positions to reach a desired end-effector target using randomized inverse kinematics search', '_bounding_sphere_sample': 'sample candidate grasp points on an object bounding sphere and find valid collision-free joint configurations', 'get_def_js': 'return the default reference joint state array for the robot arm as a numpy array'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/motion_planning/motion_plan.py

Prompts

```
['generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision checks', 'generate a RobotTarget for a specified object index by sampling grasp points on its bounding sphere', 'compute feasible joint positions to reach a desired end-effector target using randomized inverse kinematics search', 'sample candidate grasp points on an object bounding sphere and find valid collision-free joint configurations', 'return the default reference joint state array for the robot arm as a numpy array', 'build a MotionPlanner instance with a RearrangeSim and DictConfig to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a joint trajectory', 'test the _is_state_valid method to check if a given joint state is collision free', 'review the _render_verify_motion_plan method that renders a motion plan as a video and verifies collision freedom', 'refactor the _get_path method to customize OMPL planner configuration and state space bounds', 'review the MpSim abstract base class defining the motion planner simulator interface with abstract methods', 'review the HabMpSim class implementing the Habitat motion planner simulator with collision and state management', 'build a python module to use HabMpSim get_collisions to detect collisions between objects in the simulator', 'build a python module to use HabMpSim start_mp to freeze all objects to STATIC before motion planning', 'build a python module to use HabMpSim capture_state to snapshot the current simulator environment state', 'create a JsMpSpace instance with a RearrangeSim and IkHelper to plan robot arm joint-space motion', 'set up an OMPL planning problem with start and goal joint states using JsMpSpace.set_problem', 'convert an OMPL solution path to a numpy array of joint states using JsMpSpace.convert_sol', 'render start and target robot arm configurations to JPEG images using JsMpSpace.render_start_targ', 'get restrictive or non-restrictive joint state limits for the planning problem using JsMpSpace.get_state_lims']
```

Usage

```
{'build_motion_planner': 'build a MotionPlanner instance with a RearrangeSim and DictConfig to plan robot arm motion', 'run_motion_plan': 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a joint trajectory', 'test_is_state_valid': 'test the _is_state_valid method to check if a given joint state is collision free', 'review_motion_plan_render': 'review the _render_verify_motion_plan method that renders a motion plan as a video and verifies collision freedom', 'refactor_get_path': 'refactor the _get_path method to customize OMPL planner configuration and state space bounds'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/motion_planning/mp_sim.py

Prompts

```
['generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision checks', 'generate a RobotTarget for a specified object index by sampling grasp points on its bounding sphere', 'compute feasible joint positions to reach a desired end-effector target using randomized inverse kinematics search', 'sample candidate grasp points on an object bounding sphere and find valid collision-free joint configurations', 'return the default reference joint state array for the robot arm as a numpy array', 'build a MotionPlanner instance with a RearrangeSim and DictConfig to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a joint trajectory', 'test the _is_state_valid method to check if a given joint state is collision free', 'review the _render_verify_motion_plan method that renders a motion plan as a video and verifies collision freedom', 'refactor the _get_path method to customize OMPL planner configuration and state space bounds', 'review the MpSim abstract base class defining the motion planner simulator interface with abstract methods', 'review the HabMpSim class implementing the Habitat motion planner simulator with collision and state management', 'build a python module to use HabMpSim get_collisions to detect collisions between objects in the simulator', 'build a python module to use HabMpSim start_mp to freeze all objects to STATIC before motion planning', 'build a python module to use HabMpSim capture_state to snapshot the current simulator environment state', 'create a JsMpSpace instance with a RearrangeSim and IkHelper to plan robot arm joint-space motion', 'set up an OMPL planning problem with start and goal joint states using JsMpSpace.set_problem', 'convert an OMPL solution path to a numpy array of joint states using JsMpSpace.convert_sol', 'render start and target robot arm configurations to JPEG images using JsMpSpace.render_start_targ', 'get restrictive or non-restrictive joint state limits for the planning problem using JsMpSpace.get_state_lims']
```

Usage

```
{'review_MpSim_abstract_class': 'review the MpSim abstract base class defining the motion planner simulator interface with abstract methods', 'review_HabMpSim_class': 'review the HabMpSim class implementing the Habitat motion planner simulator with collision and state management', 'build_HabMpSim_get_collisions': 'build a python module to use HabMpSim get_collisions to detect collisions between objects in the simulator', 'build_HabMpSim_start_mp': 'build a python module to use HabMpSim start_mp to freeze all objects to STATIC before motion planning', 'build_HabMpSim_capture_state': 'build a python module to use HabMpSim capture_state to snapshot the current simulator environment state'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/motion_planning/mp_spaces.py

Prompts

```
['generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision checks', 'generate a RobotTarget for a specified object index by sampling grasp points on its bounding sphere', 'compute feasible joint positions to reach a desired end-effector target using randomized inverse kinematics search', 'sample candidate grasp points on an object bounding sphere and find valid collision-free joint configurations', 'return the default reference joint state array for the robot arm as a numpy array', 'build a MotionPlanner instance with a RearrangeSim and DictConfig to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a joint trajectory', 'test the _is_state_valid method to check if a given joint state is collision free', 'review the _render_verify_motion_plan method that renders a motion plan as a video and verifies collision freedom', 'refactor the _get_path method to customize OMPL planner configuration and state space bounds', 'review the MpSim abstract base class defining the motion planner simulator interface with abstract methods', 'review the HabMpSim class implementing the Habitat motion planner simulator with collision and state management', 'build a python module to use HabMpSim get_collisions to detect collisions between objects in the simulator', 'build a python module to use HabMpSim start_mp to freeze all objects to STATIC before motion planning', 'build a python module to use HabMpSim capture_state to snapshot the current simulator environment state', 'create a JsMpSpace instance with a RearrangeSim and IkHelper to plan robot arm joint-space motion', 'set up an OMPL planning problem with start and goal joint states using JsMpSpace.set_problem', 'convert an OMPL solution path to a numpy array of joint states using JsMpSpace.convert_sol', 'render start and target robot arm configurations to JPEG images using JsMpSpace.render_start_targ', 'get restrictive or non-restrictive joint state limits for the planning problem using JsMpSpace.get_state_lims']
```

Usage

```
{'create_JsMpSpace_planner': 'create a JsMpSpace instance with a RearrangeSim and IkHelper to plan robot arm joint-space motion', 'set_problem_OMPL': 'set up an OMPL planning problem with start and goal joint states using JsMpSpace.set_problem', 'convert_sol_path': 'convert an OMPL solution path to a numpy array of joint states using JsMpSpace.convert_sol', 'render_start_targ': 'render start and target robot arm configurations to JPEG images using JsMpSpace.render_start_targ', 'get_state_lims': 'get restrictive or non-restrictive joint state limits for the planning problem using JsMpSpace.get_state_lims'}
```

