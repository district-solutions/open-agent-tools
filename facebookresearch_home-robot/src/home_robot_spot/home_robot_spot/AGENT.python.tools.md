# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_spot/home_robot_spot/grasp_env.py

Prompts

```
['create a GraspController instance with a Spot robot, config, and target object labels for vision-based grasping', "run the gaze_and_grasp method to sweep, detect, and grasp an object using Spot's arm and gripper", 'test the find_obj method to detect an object in an image and return its center pixel coordinates', 'refactor the sweep method to adjust sweep angles or change how object matches are evaluated during scanning', 'review the grasp method to understand how Spot attempts to grasp an object at given pixel coordinates with retries', 'create a SpotClient instance with config to control a Boston Dynamics Spot robot', 'start the Spot robot by powering on, acquiring lease, and launching observation publishers', 'get RGB-D observations from the Spot hand camera with camera pose and 3D point cloud', 'navigate the Spot robot base to a target xyt position with optional blocking mode', 'execute a full motion plan trajectory on the Spot robot with position and rotation error thresholds', 'create a SpotDemoAgent instance with parameters dict, spot config, optional dock id and output path', 'run a VLM-driven pick and place task on the Spot robot using a language command prompt', 'run autonomous frontier-based exploration on the Spot robot for a configurable number of steps', 'navigate the Spot robot to a detected object instance using RRT motion planning', 'plan a path from the current robot position to the nearest unexplored frontier point']
```

Usage

```
{'create_grasp_controller': 'create a GraspController instance with a Spot robot, config, and target object labels for vision-based grasping', 'run_gaze_and_grasp': "run the gaze_and_grasp method to sweep, detect, and grasp an object using Spot's arm and gripper", 'test_find_obj': 'test the find_obj method to detect an object in an image and return its center pixel coordinates', 'refactor_sweep': 'refactor the sweep method to adjust sweep angles or change how object matches are evaluated during scanning', 'review_grasp': 'review the grasp method to understand how Spot attempts to grasp an object at given pixel coordinates with retries'}
```

## File: facebookresearch_home-robot/src/home_robot_spot/home_robot_spot/spot_client.py

Prompts

```
['create a GraspController instance with a Spot robot, config, and target object labels for vision-based grasping', "run the gaze_and_grasp method to sweep, detect, and grasp an object using Spot's arm and gripper", 'test the find_obj method to detect an object in an image and return its center pixel coordinates', 'refactor the sweep method to adjust sweep angles or change how object matches are evaluated during scanning', 'review the grasp method to understand how Spot attempts to grasp an object at given pixel coordinates with retries', 'create a SpotClient instance with config to control a Boston Dynamics Spot robot', 'start the Spot robot by powering on, acquiring lease, and launching observation publishers', 'get RGB-D observations from the Spot hand camera with camera pose and 3D point cloud', 'navigate the Spot robot base to a target xyt position with optional blocking mode', 'execute a full motion plan trajectory on the Spot robot with position and rotation error thresholds', 'create a SpotDemoAgent instance with parameters dict, spot config, optional dock id and output path', 'run a VLM-driven pick and place task on the Spot robot using a language command prompt', 'run autonomous frontier-based exploration on the Spot robot for a configurable number of steps', 'navigate the Spot robot to a detected object instance using RRT motion planning', 'plan a path from the current robot position to the nearest unexplored frontier point']
```

Usage

```
{'create_spot_client': 'create a SpotClient instance with config to control a Boston Dynamics Spot robot', 'start_spot_robot': 'start the Spot robot by powering on, acquiring lease, and launching observation publishers', 'get_rgbd_observations': 'get RGB-D observations from the Spot hand camera with camera pose and 3D point cloud', 'navigate_spot_to_position': 'navigate the Spot robot base to a target xyt position with optional blocking mode', 'execute_motion_plan': 'execute a full motion plan trajectory on the Spot robot with position and rotation error thresholds'}
```

## File: facebookresearch_home-robot/src/home_robot_spot/home_robot_spot/spot_demo_agent.py

Prompts

```
['create a GraspController instance with a Spot robot, config, and target object labels for vision-based grasping', "run the gaze_and_grasp method to sweep, detect, and grasp an object using Spot's arm and gripper", 'test the find_obj method to detect an object in an image and return its center pixel coordinates', 'refactor the sweep method to adjust sweep angles or change how object matches are evaluated during scanning', 'review the grasp method to understand how Spot attempts to grasp an object at given pixel coordinates with retries', 'create a SpotClient instance with config to control a Boston Dynamics Spot robot', 'start the Spot robot by powering on, acquiring lease, and launching observation publishers', 'get RGB-D observations from the Spot hand camera with camera pose and 3D point cloud', 'navigate the Spot robot base to a target xyt position with optional blocking mode', 'execute a full motion plan trajectory on the Spot robot with position and rotation error thresholds', 'create a SpotDemoAgent instance with parameters dict, spot config, optional dock id and output path', 'run a VLM-driven pick and place task on the Spot robot using a language command prompt', 'run autonomous frontier-based exploration on the Spot robot for a configurable number of steps', 'navigate the Spot robot to a detected object instance using RRT motion planning', 'plan a path from the current robot position to the nearest unexplored frontier point']
```

Usage

```
{'create_SpotDemoAgent': 'create a SpotDemoAgent instance with parameters dict, spot config, optional dock id and output path', 'run_SpotDemoAgent_run_task': 'run a VLM-driven pick and place task on the Spot robot using a language command prompt', 'run_SpotDemoAgent_run_explore': 'run autonomous frontier-based exploration on the Spot robot for a configurable number of steps', 'run_SpotDemoAgent_navigate_to_an_instance': 'navigate the Spot robot to a detected object instance using RRT motion planning', 'run_SpotDemoAgent_plan_to_frontier': 'plan a path from the current robot position to the nearest unexplored frontier point'}
```

