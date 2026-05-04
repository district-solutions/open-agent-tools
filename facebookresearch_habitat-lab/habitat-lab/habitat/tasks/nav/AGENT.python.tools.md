# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/tasks/nav/instance_image_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoal with a list of InstanceImageParameters camera parameters for image goal generation', 'review the InstanceImageGoalSensor get_observation method that renders and caches instance image goals from episodes', 'review the InstanceImageGoalSensor method that creates a temporary sensor to render an image goal then removes it', 'review the InstanceImageGoalHFOVSensor class that returns the horizontal field of view of the current episode goal', 'build a python module that creates a NavigationTask with a HabitatSim simulator and config', 'create a PointGoalSensor to observe goal direction in cartesian or polar coordinates', 'create an ImageGoalSensor to observe an RGB image taken from the goal position', 'create a TopDownMap measure to render and update a top-down map of the agent path', 'create a VelocityAction to move the agent with linear and angular velocity control', 'create an ObjectGoalNavEpisode with an object category and scene id for navigation goals', 'build an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable viewpoints around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id observations', 'build an ObjectNavigationTask registered as ObjectNav-v1 for object goal navigation in Habitat simulator', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'create a one-hot encoding numpy array from an integer action using action_to_one_hot', 'get the next action along the shortest path to a goal position using get_next_action', 'review the ShortestPathFollower class and its get_next_action method for navigation tasks', 'test the action_to_one_hot function to verify it returns a correct one-hot numpy array']
```

Usage

```
{'create_InstanceImageGoalNavEpisode': 'create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create_InstanceImageGoal': 'create an InstanceImageGoal with a list of InstanceImageParameters camera parameters for image goal generation', 'review_InstanceImageGoalSensor_get_observation': 'review the InstanceImageGoalSensor get_observation method that renders and caches instance image goals from episodes', 'review_InstanceImageGoalSensor_get_instance_image_goal': 'review the InstanceImageGoalSensor method that creates a temporary sensor to render an image goal then removes it', 'review_InstanceImageGoalHFOVSensor': 'review the InstanceImageGoalHFOVSensor class that returns the horizontal field of view of the current episode goal'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/tasks/nav/nav.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoal with a list of InstanceImageParameters camera parameters for image goal generation', 'review the InstanceImageGoalSensor get_observation method that renders and caches instance image goals from episodes', 'review the InstanceImageGoalSensor method that creates a temporary sensor to render an image goal then removes it', 'review the InstanceImageGoalHFOVSensor class that returns the horizontal field of view of the current episode goal', 'build a python module that creates a NavigationTask with a HabitatSim simulator and config', 'create a PointGoalSensor to observe goal direction in cartesian or polar coordinates', 'create an ImageGoalSensor to observe an RGB image taken from the goal position', 'create a TopDownMap measure to render and update a top-down map of the agent path', 'create a VelocityAction to move the agent with linear and angular velocity control', 'create an ObjectGoalNavEpisode with an object category and scene id for navigation goals', 'build an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable viewpoints around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id observations', 'build an ObjectNavigationTask registered as ObjectNav-v1 for object goal navigation in Habitat simulator', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'create a one-hot encoding numpy array from an integer action using action_to_one_hot', 'get the next action along the shortest path to a goal position using get_next_action', 'review the ShortestPathFollower class and its get_next_action method for navigation tasks', 'test the action_to_one_hot function to verify it returns a correct one-hot numpy array']
```

Usage

```
{'build_navigation_task': 'build a python module that creates a NavigationTask with a HabitatSim simulator and config', 'create_pointgoal_sensor': 'create a PointGoalSensor to observe goal direction in cartesian or polar coordinates', 'create_imagegoal_sensor': 'create an ImageGoalSensor to observe an RGB image taken from the goal position', 'create_topdown_map_measure': 'create a TopDownMap measure to render and update a top-down map of the agent path', 'create_velocity_action': 'create a VelocityAction to move the agent with linear and angular velocity control'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/tasks/nav/object_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoal with a list of InstanceImageParameters camera parameters for image goal generation', 'review the InstanceImageGoalSensor get_observation method that renders and caches instance image goals from episodes', 'review the InstanceImageGoalSensor method that creates a temporary sensor to render an image goal then removes it', 'review the InstanceImageGoalHFOVSensor class that returns the horizontal field of view of the current episode goal', 'build a python module that creates a NavigationTask with a HabitatSim simulator and config', 'create a PointGoalSensor to observe goal direction in cartesian or polar coordinates', 'create an ImageGoalSensor to observe an RGB image taken from the goal position', 'create a TopDownMap measure to render and update a top-down map of the agent path', 'create a VelocityAction to move the agent with linear and angular velocity control', 'create an ObjectGoalNavEpisode with an object category and scene id for navigation goals', 'build an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable viewpoints around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id observations', 'build an ObjectNavigationTask registered as ObjectNav-v1 for object goal navigation in Habitat simulator', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'create a one-hot encoding numpy array from an integer action using action_to_one_hot', 'get the next action along the shortest path to a goal position using get_next_action', 'review the ShortestPathFollower class and its get_next_action method for navigation tasks', 'test the action_to_one_hot function to verify it returns a correct one-hot numpy array']
```

Usage

```
{'create_ObjectGoalNavEpisode': 'create an ObjectGoalNavEpisode with an object category and scene id for navigation goals', 'build_ObjectGoal': 'build an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create_ObjectViewLocation': 'create an ObjectViewLocation with agent_state and iou to define navigable viewpoints around an object', 'review_ObjectGoalSensor_get_observation': 'review the ObjectGoalSensor get_observation method to return task category id or object id observations', 'build_ObjectNavigationTask': 'build an ObjectNavigationTask registered as ObjectNav-v1 for object goal navigation in Habitat simulator'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/tasks/nav/shortest_path_follower.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoal with a list of InstanceImageParameters camera parameters for image goal generation', 'review the InstanceImageGoalSensor get_observation method that renders and caches instance image goals from episodes', 'review the InstanceImageGoalSensor method that creates a temporary sensor to render an image goal then removes it', 'review the InstanceImageGoalHFOVSensor class that returns the horizontal field of view of the current episode goal', 'build a python module that creates a NavigationTask with a HabitatSim simulator and config', 'create a PointGoalSensor to observe goal direction in cartesian or polar coordinates', 'create an ImageGoalSensor to observe an RGB image taken from the goal position', 'create a TopDownMap measure to render and update a top-down map of the agent path', 'create a VelocityAction to move the agent with linear and angular velocity control', 'create an ObjectGoalNavEpisode with an object category and scene id for navigation goals', 'build an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable viewpoints around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id observations', 'build an ObjectNavigationTask registered as ObjectNav-v1 for object goal navigation in Habitat simulator', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'create a one-hot encoding numpy array from an integer action using action_to_one_hot', 'get the next action along the shortest path to a goal position using get_next_action', 'review the ShortestPathFollower class and its get_next_action method for navigation tasks', 'test the action_to_one_hot function to verify it returns a correct one-hot numpy array']
```

Usage

```
{'build_shortest_path_follower': 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'create_action_one_hot': 'create a one-hot encoding numpy array from an integer action using action_to_one_hot', 'get_next_action_shortest_path': 'get the next action along the shortest path to a goal position using get_next_action', 'review_shortest_path_follower_class': 'review the ShortestPathFollower class and its get_next_action method for navigation tasks', 'test_action_to_one_hot': 'test the action_to_one_hot function to verify it returns a correct one-hot numpy array'}
```

