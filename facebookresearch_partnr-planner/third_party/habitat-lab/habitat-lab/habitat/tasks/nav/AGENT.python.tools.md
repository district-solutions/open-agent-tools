# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/tasks/nav/instance_image_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoalSensor that renders image goals from camera parameters in a HabitatSim dataset', 'create an InstanceImageGoalHFOVSensor that returns the horizontal field of view for the current episode goal', 'register the InstanceImageNav-v1 task for navigating to a specific object instance using a goal image', 'create an InstanceImageGoal with a list of InstanceImageParameters for camera-based image goal generation', 'create a NavigationEpisode with start position, rotation quaternion, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation agents', 'implement the SPL measure to calculate success weighted by path length for navigation evaluation', 'register a NavigationTask with the Habitat registry to define embodied navigation episodes and goals', 'create a VelocityAction to control agent linear and angular velocity with configurable speed ranges', 'create an ObjectGoalNavEpisode with object_category to define navigation goals for a specific scene', 'create an ObjectViewLocation with agent_state and iou to describe navigable viewpoints around an object goal', 'create an ObjectGoal with object_id, object_name, and view_points to specify a navigation target object', 'use ObjectGoalSensor get_observation to return the task category ID or object ID for an episode', 'register the ObjectNavigationTask with the Habitat registry to define an ObjectNav-v1 navigation task', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using ShortestPathFollower', 'create a one-hot encoding array for a HabitatSim action using action_to_one_hot', 'review the ShortestPathFollower class and its get_next_action method for navigation logic', 'test the action_to_one_hot function returns a correct one-hot numpy array for a given action']
```

Usage

```
{'create_InstanceImageGoalNavEpisode': 'create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create_InstanceImageGoalSensor': 'create an InstanceImageGoalSensor that renders image goals from camera parameters in a HabitatSim dataset', 'create_InstanceImageGoalHFOVSensor': 'create an InstanceImageGoalHFOVSensor that returns the horizontal field of view for the current episode goal', 'register_InstanceImageNavigationTask': 'register the InstanceImageNav-v1 task for navigating to a specific object instance using a goal image', 'create_InstanceImageGoal': 'create an InstanceImageGoal with a list of InstanceImageParameters for camera-based image goal generation'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/tasks/nav/nav.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoalSensor that renders image goals from camera parameters in a HabitatSim dataset', 'create an InstanceImageGoalHFOVSensor that returns the horizontal field of view for the current episode goal', 'register the InstanceImageNav-v1 task for navigating to a specific object instance using a goal image', 'create an InstanceImageGoal with a list of InstanceImageParameters for camera-based image goal generation', 'create a NavigationEpisode with start position, rotation quaternion, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation agents', 'implement the SPL measure to calculate success weighted by path length for navigation evaluation', 'register a NavigationTask with the Habitat registry to define embodied navigation episodes and goals', 'create a VelocityAction to control agent linear and angular velocity with configurable speed ranges', 'create an ObjectGoalNavEpisode with object_category to define navigation goals for a specific scene', 'create an ObjectViewLocation with agent_state and iou to describe navigable viewpoints around an object goal', 'create an ObjectGoal with object_id, object_name, and view_points to specify a navigation target object', 'use ObjectGoalSensor get_observation to return the task category ID or object ID for an episode', 'register the ObjectNavigationTask with the Habitat registry to define an ObjectNav-v1 navigation task', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using ShortestPathFollower', 'create a one-hot encoding array for a HabitatSim action using action_to_one_hot', 'review the ShortestPathFollower class and its get_next_action method for navigation logic', 'test the action_to_one_hot function returns a correct one-hot numpy array for a given action']
```

Usage

```
{'create_navigation_episode': 'create a NavigationEpisode with start position, rotation quaternion, and list of NavigationGoal targets', 'build_pointgoal_sensor': 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation agents', 'implement_spl_measure': 'implement the SPL measure to calculate success weighted by path length for navigation evaluation', 'register_navigation_task': 'register a NavigationTask with the Habitat registry to define embodied navigation episodes and goals', 'create_velocity_action': 'create a VelocityAction to control agent linear and angular velocity with configurable speed ranges'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/tasks/nav/object_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoalSensor that renders image goals from camera parameters in a HabitatSim dataset', 'create an InstanceImageGoalHFOVSensor that returns the horizontal field of view for the current episode goal', 'register the InstanceImageNav-v1 task for navigating to a specific object instance using a goal image', 'create an InstanceImageGoal with a list of InstanceImageParameters for camera-based image goal generation', 'create a NavigationEpisode with start position, rotation quaternion, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation agents', 'implement the SPL measure to calculate success weighted by path length for navigation evaluation', 'register a NavigationTask with the Habitat registry to define embodied navigation episodes and goals', 'create a VelocityAction to control agent linear and angular velocity with configurable speed ranges', 'create an ObjectGoalNavEpisode with object_category to define navigation goals for a specific scene', 'create an ObjectViewLocation with agent_state and iou to describe navigable viewpoints around an object goal', 'create an ObjectGoal with object_id, object_name, and view_points to specify a navigation target object', 'use ObjectGoalSensor get_observation to return the task category ID or object ID for an episode', 'register the ObjectNavigationTask with the Habitat registry to define an ObjectNav-v1 navigation task', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using ShortestPathFollower', 'create a one-hot encoding array for a HabitatSim action using action_to_one_hot', 'review the ShortestPathFollower class and its get_next_action method for navigation logic', 'test the action_to_one_hot function returns a correct one-hot numpy array for a given action']
```

Usage

```
{'create_ObjectGoalNavEpisode': 'create an ObjectGoalNavEpisode with object_category to define navigation goals for a specific scene', 'create_ObjectViewLocation': 'create an ObjectViewLocation with agent_state and iou to describe navigable viewpoints around an object goal', 'create_ObjectGoal': 'create an ObjectGoal with object_id, object_name, and view_points to specify a navigation target object', 'use_ObjectGoalSensor_get_observation': 'use ObjectGoalSensor get_observation to return the task category ID or object ID for an episode', 'register_ObjectNavigationTask': 'register the ObjectNavigationTask with the Habitat registry to define an ObjectNav-v1 navigation task'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/tasks/nav/shortest_path_follower.py

Prompts

```
['create an InstanceImageGoalNavEpisode with a goal object ID and goal image ID for navigation', 'create an InstanceImageGoalSensor that renders image goals from camera parameters in a HabitatSim dataset', 'create an InstanceImageGoalHFOVSensor that returns the horizontal field of view for the current episode goal', 'register the InstanceImageNav-v1 task for navigating to a specific object instance using a goal image', 'create an InstanceImageGoal with a list of InstanceImageParameters for camera-based image goal generation', 'create a NavigationEpisode with start position, rotation quaternion, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation agents', 'implement the SPL measure to calculate success weighted by path length for navigation evaluation', 'register a NavigationTask with the Habitat registry to define embodied navigation episodes and goals', 'create a VelocityAction to control agent linear and angular velocity with configurable speed ranges', 'create an ObjectGoalNavEpisode with object_category to define navigation goals for a specific scene', 'create an ObjectViewLocation with agent_state and iou to describe navigable viewpoints around an object goal', 'create an ObjectGoal with object_id, object_name, and view_points to specify a navigation target object', 'use ObjectGoalSensor get_observation to return the task category ID or object ID for an episode', 'register the ObjectNavigationTask with the Habitat registry to define an ObjectNav-v1 navigation task', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using ShortestPathFollower', 'create a one-hot encoding array for a HabitatSim action using action_to_one_hot', 'review the ShortestPathFollower class and its get_next_action method for navigation logic', 'test the action_to_one_hot function returns a correct one-hot numpy array for a given action']
```

Usage

```
{'build_shortest_path_follower': 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get_next_action': 'get the next action along the shortest path to a goal position using ShortestPathFollower', 'create_one_hot_action': 'create a one-hot encoding array for a HabitatSim action using action_to_one_hot', 'review_shortest_path_follower_class': 'review the ShortestPathFollower class and its get_next_action method for navigation logic', 'test_action_to_one_hot': 'test the action_to_one_hot function returns a correct one-hot numpy array for a given action'}
```

