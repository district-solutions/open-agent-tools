# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/tests/home_robot/motion/test_ik.py

Prompts

```
['test inverse kinematics solvers across pybullet and pinocchio backends with FK consistency checks', 'test pinocchio IK solver results match pybullet IK solver results for the same robot pose', 'test pinocchio IK with CEM optimization achieves lower position error than direct IK solve', 'test pybullet IK with CEM optimization achieves lower position error than direct IK solve', 'test ROS joint pose conversion to pinocchio format produces expected joint values', 'test the RRT planner with a SimpleEnv and start/goal points', 'test the RRTConnect planner with a SimpleEnv and start/goal points', 'test the Shortcut wrapper around RRT to verify shorter trajectories', 'test the Shortcut wrapper around RRTConnect to verify shorter trajectories', 'run a motion planner in a SimpleEnv with obstacles and visualize results']
```

Usage

```
{'test_ik_solvers': 'test inverse kinematics solvers across pybullet and pinocchio backends with FK consistency checks', 'test_pinocchio_against_pybullet': 'test pinocchio IK solver results match pybullet IK solver results for the same robot pose', 'test_pinocchio_ik_optimization': 'test pinocchio IK with CEM optimization achieves lower position error than direct IK solve', 'test_pybullet_ik_optimization': 'test pybullet IK with CEM optimization achieves lower position error than direct IK solve', 'test_ros_to_pin': 'test ROS joint pose conversion to pinocchio format produces expected joint values'}
```

## File: facebookresearch_home-robot/tests/home_robot/motion/test_rrt.py

Prompts

```
['test inverse kinematics solvers across pybullet and pinocchio backends with FK consistency checks', 'test pinocchio IK solver results match pybullet IK solver results for the same robot pose', 'test pinocchio IK with CEM optimization achieves lower position error than direct IK solve', 'test pybullet IK with CEM optimization achieves lower position error than direct IK solve', 'test ROS joint pose conversion to pinocchio format produces expected joint values', 'test the RRT planner with a SimpleEnv and start/goal points', 'test the RRTConnect planner with a SimpleEnv and start/goal points', 'test the Shortcut wrapper around RRT to verify shorter trajectories', 'test the Shortcut wrapper around RRTConnect to verify shorter trajectories', 'run a motion planner in a SimpleEnv with obstacles and visualize results']
```

Usage

```
{'test_RRT_planner': 'test the RRT planner with a SimpleEnv and start/goal points', 'test_RRTConnect_planner': 'test the RRTConnect planner with a SimpleEnv and start/goal points', 'test_Shortcut_with_RRT': 'test the Shortcut wrapper around RRT to verify shorter trajectories', 'test_Shortcut_with_RRTConnect': 'test the Shortcut wrapper around RRTConnect to verify shorter trajectories', 'run_planner_in_simple_env': 'run a motion planner in a SimpleEnv with obstacles and visualize results'}
```

