# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/motion_planning/grasp_generator.py

Prompts

```
['build a GraspGenerator instance with MpSim, MpSpace, IkHelper, and motion planning parameters for robot grasp planning', 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision validation', "generate a RobotTarget by sampling grasp points around an object's bounding sphere in the simulation", 'generate feasible joint states for a desired end-effector target position using random search and IK solving', 'compute the actual end-effector position in world space from a given set of robot joint angles', 'build a MotionPlanner instance with a RearrangeSim and CfgNode config to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a collision-free joint trajectory', 'create a state validity check using _is_state_valid to verify if a joint configuration is collision free', 'configure motion planning parameters via set_config to set EE margin, grasp threshold, and collision counting options', 'render a debug video of a motion plan using _render_verify_motion_plan to visualize and validate joint states', 'build a python module using HabMpSim to plan robot arm motion in a Habitat simulation environment', 'create a function that calls get_collisions to detect and return pairs of colliding objects in the simulator', 'test the HabMpSim capture_state and set_state methods to save and restore simulator environment state', 'refactor the HabMpSim start_mp and end_mp methods to manage object motion types during motion planning', 'review the MpSim abstract class and its required methods for implementing custom motion planner simulator interfaces', 'create a JsMpSpace instance with a RearrangeSim, IkHelper, call counter, and render flag for joint-space motion planning', 'set up an OMPL planning problem with start/goal joint states and an admissible end-effector distance heuristic', 'convert an OMPL solution path into a numpy array of joint states for execution', 'render start and goal robot states to JPEG images in a specified output directory for visualization', 'get restrictive or permissive joint angle limits for the 7-DOF robot arm planning space']
```

Usage

```
{'build_grasp_generator': 'build a GraspGenerator instance with MpSim, MpSpace, IkHelper, and motion planning parameters for robot grasp planning', 'gen_target_from_ee_pos': 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision validation', 'gen_target_from_obj_idx': "generate a RobotTarget by sampling grasp points around an object's bounding sphere in the simulation", 'gen_goal_state': 'generate feasible joint states for a desired end-effector target position using random search and IK solving', 'get_real_ee_pos': 'compute the actual end-effector position in world space from a given set of robot joint angles'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/motion_planning/motion_plan.py

Prompts

```
['build a GraspGenerator instance with MpSim, MpSpace, IkHelper, and motion planning parameters for robot grasp planning', 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision validation', "generate a RobotTarget by sampling grasp points around an object's bounding sphere in the simulation", 'generate feasible joint states for a desired end-effector target position using random search and IK solving', 'compute the actual end-effector position in world space from a given set of robot joint angles', 'build a MotionPlanner instance with a RearrangeSim and CfgNode config to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a collision-free joint trajectory', 'create a state validity check using _is_state_valid to verify if a joint configuration is collision free', 'configure motion planning parameters via set_config to set EE margin, grasp threshold, and collision counting options', 'render a debug video of a motion plan using _render_verify_motion_plan to visualize and validate joint states', 'build a python module using HabMpSim to plan robot arm motion in a Habitat simulation environment', 'create a function that calls get_collisions to detect and return pairs of colliding objects in the simulator', 'test the HabMpSim capture_state and set_state methods to save and restore simulator environment state', 'refactor the HabMpSim start_mp and end_mp methods to manage object motion types during motion planning', 'review the MpSim abstract class and its required methods for implementing custom motion planner simulator interfaces', 'create a JsMpSpace instance with a RearrangeSim, IkHelper, call counter, and render flag for joint-space motion planning', 'set up an OMPL planning problem with start/goal joint states and an admissible end-effector distance heuristic', 'convert an OMPL solution path into a numpy array of joint states for execution', 'render start and goal robot states to JPEG images in a specified output directory for visualization', 'get restrictive or permissive joint angle limits for the 7-DOF robot arm planning space']
```

Usage

```
{'build_motion_planner': 'build a MotionPlanner instance with a RearrangeSim and CfgNode config to plan robot arm motion', 'run_motion_plan': 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a collision-free joint trajectory', 'create_state_validity_check': 'create a state validity check using _is_state_valid to verify if a joint configuration is collision free', 'configure_motion_planning_params': 'configure motion planning parameters via set_config to set EE margin, grasp threshold, and collision counting options', 'render_debug_motion_plan': 'render a debug video of a motion plan using _render_verify_motion_plan to visualize and validate joint states'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/motion_planning/mp_sim.py

Prompts

```
['build a GraspGenerator instance with MpSim, MpSpace, IkHelper, and motion planning parameters for robot grasp planning', 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision validation', "generate a RobotTarget by sampling grasp points around an object's bounding sphere in the simulation", 'generate feasible joint states for a desired end-effector target position using random search and IK solving', 'compute the actual end-effector position in world space from a given set of robot joint angles', 'build a MotionPlanner instance with a RearrangeSim and CfgNode config to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a collision-free joint trajectory', 'create a state validity check using _is_state_valid to verify if a joint configuration is collision free', 'configure motion planning parameters via set_config to set EE margin, grasp threshold, and collision counting options', 'render a debug video of a motion plan using _render_verify_motion_plan to visualize and validate joint states', 'build a python module using HabMpSim to plan robot arm motion in a Habitat simulation environment', 'create a function that calls get_collisions to detect and return pairs of colliding objects in the simulator', 'test the HabMpSim capture_state and set_state methods to save and restore simulator environment state', 'refactor the HabMpSim start_mp and end_mp methods to manage object motion types during motion planning', 'review the MpSim abstract class and its required methods for implementing custom motion planner simulator interfaces', 'create a JsMpSpace instance with a RearrangeSim, IkHelper, call counter, and render flag for joint-space motion planning', 'set up an OMPL planning problem with start/goal joint states and an admissible end-effector distance heuristic', 'convert an OMPL solution path into a numpy array of joint states for execution', 'render start and goal robot states to JPEG images in a specified output directory for visualization', 'get restrictive or permissive joint angle limits for the 7-DOF robot arm planning space']
```

Usage

```
{'build_HabMpSim_motion_planner': 'build a python module using HabMpSim to plan robot arm motion in a Habitat simulation environment', 'create_get_collisions': 'create a function that calls get_collisions to detect and return pairs of colliding objects in the simulator', 'test_capture_and_set_state': 'test the HabMpSim capture_state and set_state methods to save and restore simulator environment state', 'refactor_start_mp_end_mp': 'refactor the HabMpSim start_mp and end_mp methods to manage object motion types during motion planning', 'review_MpSim_abstract_interface': 'review the MpSim abstract class and its required methods for implementing custom motion planner simulator interfaces'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/motion_planning/mp_spaces.py

Prompts

```
['build a GraspGenerator instance with MpSim, MpSpace, IkHelper, and motion planning parameters for robot grasp planning', 'generate a RobotTarget from a given end-effector 3D position using inverse kinematics and collision validation', "generate a RobotTarget by sampling grasp points around an object's bounding sphere in the simulation", 'generate feasible joint states for a desired end-effector target position using random search and IK solving', 'compute the actual end-effector position in world space from a given set of robot joint angles', 'build a MotionPlanner instance with a RearrangeSim and CfgNode config to plan robot arm motion', 'run motion_plan on a MotionPlanner with start joint states and a RobotTarget to get a collision-free joint trajectory', 'create a state validity check using _is_state_valid to verify if a joint configuration is collision free', 'configure motion planning parameters via set_config to set EE margin, grasp threshold, and collision counting options', 'render a debug video of a motion plan using _render_verify_motion_plan to visualize and validate joint states', 'build a python module using HabMpSim to plan robot arm motion in a Habitat simulation environment', 'create a function that calls get_collisions to detect and return pairs of colliding objects in the simulator', 'test the HabMpSim capture_state and set_state methods to save and restore simulator environment state', 'refactor the HabMpSim start_mp and end_mp methods to manage object motion types during motion planning', 'review the MpSim abstract class and its required methods for implementing custom motion planner simulator interfaces', 'create a JsMpSpace instance with a RearrangeSim, IkHelper, call counter, and render flag for joint-space motion planning', 'set up an OMPL planning problem with start/goal joint states and an admissible end-effector distance heuristic', 'convert an OMPL solution path into a numpy array of joint states for execution', 'render start and goal robot states to JPEG images in a specified output directory for visualization', 'get restrictive or permissive joint angle limits for the 7-DOF robot arm planning space']
```

Usage

```
{'create_JsMpSpace': 'create a JsMpSpace instance with a RearrangeSim, IkHelper, call counter, and render flag for joint-space motion planning', 'set_problem_JsMpSpace': 'set up an OMPL planning problem with start/goal joint states and an admissible end-effector distance heuristic', 'convert_sol_JsMpSpace': 'convert an OMPL solution path into a numpy array of joint states for execution', 'render_start_targ_JsMpSpace': 'render start and goal robot states to JPEG images in a specified output directory for visualization', 'get_state_lims_JsMpSpace': 'get restrictive or permissive joint angle limits for the 7-DOF robot arm planning space'}
```

