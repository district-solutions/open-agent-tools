# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/tasks/nav/nav.py

Prompts

```
['create a NavigationEpisode with start position, rotation, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation tasks', 'implement the SPL success weighted by path length measure for evaluating navigation agents', 'create a VelocityAction with configurable linear and angular velocity ranges for continuous control', 'build a NavigationTask registered as Nav-v0 with episode config merging and stop action support', 'create an ObjectGoalNavEpisode with a scene_id and object_category for object navigation', 'build an ObjectGoal with object_id, object_name, room_id, and view_points for navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable positions around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id', 'register the ObjectNavigationTask class as ObjectNav-v1 for object goal navigation tasks in Habitat', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using the follower', 'create a one-hot encoding array from a HabitatSim action integer value', 'build a greedy geodesic follower for navigating toward a goal in the Habitat simulator', 'review the ShortestPathFollower class and its get_next_action method for navigation logic']
```

Usage

```
{'create_navigation_episode': 'create a NavigationEpisode with start position, rotation, and list of NavigationGoal targets', 'build_pointgoal_sensor': 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation tasks', 'implement_spl_measure': 'implement the SPL success weighted by path length measure for evaluating navigation agents', 'create_velocity_action': 'create a VelocityAction with configurable linear and angular velocity ranges for continuous control', 'build_navigation_task': 'build a NavigationTask registered as Nav-v0 with episode config merging and stop action support'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/tasks/nav/object_nav_task.py

Prompts

```
['create a NavigationEpisode with start position, rotation, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation tasks', 'implement the SPL success weighted by path length measure for evaluating navigation agents', 'create a VelocityAction with configurable linear and angular velocity ranges for continuous control', 'build a NavigationTask registered as Nav-v0 with episode config merging and stop action support', 'create an ObjectGoalNavEpisode with a scene_id and object_category for object navigation', 'build an ObjectGoal with object_id, object_name, room_id, and view_points for navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable positions around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id', 'register the ObjectNavigationTask class as ObjectNav-v1 for object goal navigation tasks in Habitat', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using the follower', 'create a one-hot encoding array from a HabitatSim action integer value', 'build a greedy geodesic follower for navigating toward a goal in the Habitat simulator', 'review the ShortestPathFollower class and its get_next_action method for navigation logic']
```

Usage

```
{'create_ObjectGoalNavEpisode': 'create an ObjectGoalNavEpisode with a scene_id and object_category for object navigation', 'build_ObjectGoal': 'build an ObjectGoal with object_id, object_name, room_id, and view_points for navigation targets', 'create_ObjectViewLocation': 'create an ObjectViewLocation with agent_state and iou to define navigable positions around an object', 'review_ObjectGoalSensor_get_observation': 'review the ObjectGoalSensor get_observation method to return task category id or object id', 'register_ObjectNavigationTask': 'register the ObjectNavigationTask class as ObjectNav-v1 for object goal navigation tasks in Habitat'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/tasks/nav/shortest_path_follower.py

Prompts

```
['create a NavigationEpisode with start position, rotation, and list of NavigationGoal targets', 'build a PointGoalSensor to compute cartesian or polar goal observations for navigation tasks', 'implement the SPL success weighted by path length measure for evaluating navigation agents', 'create a VelocityAction with configurable linear and angular velocity ranges for continuous control', 'build a NavigationTask registered as Nav-v0 with episode config merging and stop action support', 'create an ObjectGoalNavEpisode with a scene_id and object_category for object navigation', 'build an ObjectGoal with object_id, object_name, room_id, and view_points for navigation targets', 'create an ObjectViewLocation with agent_state and iou to define navigable positions around an object', 'review the ObjectGoalSensor get_observation method to return task category id or object id', 'register the ObjectNavigationTask class as ObjectNav-v1 for object goal navigation tasks in Habitat', 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get the next action along the shortest path to a goal position using the follower', 'create a one-hot encoding array from a HabitatSim action integer value', 'build a greedy geodesic follower for navigating toward a goal in the Habitat simulator', 'review the ShortestPathFollower class and its get_next_action method for navigation logic']
```

Usage

```
{'build_shortest_path_follower': 'build a ShortestPathFollower instance with a HabitatSim simulator and goal radius for navigation', 'get_next_action': 'get the next action along the shortest path to a goal position using the follower', 'create_one_hot_action': 'create a one-hot encoding array from a HabitatSim action integer value', 'build_greedy_follower': 'build a greedy geodesic follower for navigating toward a goal in the Habitat simulator', 'review_shortest_path_follower_class': 'review the ShortestPathFollower class and its get_next_action method for navigation logic'}
```

