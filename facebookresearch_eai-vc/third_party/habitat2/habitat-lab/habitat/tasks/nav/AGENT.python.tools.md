# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/tasks/nav/instance_image_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with goal_object_id and goal_image_id for navigation', 'create an InstanceImageGoalSensor to render instance image goals from camera parameters', 'create an InstanceImageGoalHFOVSensor to return the horizontal field of view of image goals', 'review the InstanceImageGoal class that holds image_goals list and object_surface_area', 'review the InstanceImageParameters class with position, rotation, hfov, and image_dimensions fields', 'create a PointGoalSensor to compute cartesian or polar goal observations for point goal navigation', 'create an ImageGoalSensor to return RGB images taken from the goal position with random rotation', 'create an EpisodicGPSSensor to observe the agent position relative to the episode start coordinate frame', 'create a VelocityAction to move the agent with configurable linear and angular velocity controls', 'create a NavigationTask to configure and run navigation episodes with start positions and goal specifications', 'create an ObjectGoalNavEpisode with a target object category and scene ID for navigation', 'create an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define a navigable viewpoint around an object', 'build an ObjectGoalSensor to observe object goal specifications by category ID or object ID', "register the ObjectNav-v1 task with Habitat's registry for object goal navigation episodes", 'build a ShortestPathFollower instance with a HabitatSim and goal radius for navigation', 'get the next action along the shortest path to a goal position', 'create a one-hot encoding numpy array from a HabitatSim action integer', 'review the ShortestPathFollower class and its get_next_action method for navigation', 'refactor the ShortestPathFollower to change stop_on_error behavior on GreedyFollowerError']
```

Usage

```
{'create_InstanceImageGoalNavEpisode': 'create an InstanceImageGoalNavEpisode with goal_object_id and goal_image_id for navigation', 'create_InstanceImageGoalSensor': 'create an InstanceImageGoalSensor to render instance image goals from camera parameters', 'create_InstanceImageGoalHFOVSensor': 'create an InstanceImageGoalHFOVSensor to return the horizontal field of view of image goals', 'review_InstanceImageGoal': 'review the InstanceImageGoal class that holds image_goals list and object_surface_area', 'review_InstanceImageParameters': 'review the InstanceImageParameters class with position, rotation, hfov, and image_dimensions fields'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/tasks/nav/nav.py

Prompts

```
['create an InstanceImageGoalNavEpisode with goal_object_id and goal_image_id for navigation', 'create an InstanceImageGoalSensor to render instance image goals from camera parameters', 'create an InstanceImageGoalHFOVSensor to return the horizontal field of view of image goals', 'review the InstanceImageGoal class that holds image_goals list and object_surface_area', 'review the InstanceImageParameters class with position, rotation, hfov, and image_dimensions fields', 'create a PointGoalSensor to compute cartesian or polar goal observations for point goal navigation', 'create an ImageGoalSensor to return RGB images taken from the goal position with random rotation', 'create an EpisodicGPSSensor to observe the agent position relative to the episode start coordinate frame', 'create a VelocityAction to move the agent with configurable linear and angular velocity controls', 'create a NavigationTask to configure and run navigation episodes with start positions and goal specifications', 'create an ObjectGoalNavEpisode with a target object category and scene ID for navigation', 'create an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define a navigable viewpoint around an object', 'build an ObjectGoalSensor to observe object goal specifications by category ID or object ID', "register the ObjectNav-v1 task with Habitat's registry for object goal navigation episodes", 'build a ShortestPathFollower instance with a HabitatSim and goal radius for navigation', 'get the next action along the shortest path to a goal position', 'create a one-hot encoding numpy array from a HabitatSim action integer', 'review the ShortestPathFollower class and its get_next_action method for navigation', 'refactor the ShortestPathFollower to change stop_on_error behavior on GreedyFollowerError']
```

Usage

```
{'create_PointGoalSensor': 'create a PointGoalSensor to compute cartesian or polar goal observations for point goal navigation', 'create_ImageGoalSensor': 'create an ImageGoalSensor to return RGB images taken from the goal position with random rotation', 'create_EpisodicGPSSensor': 'create an EpisodicGPSSensor to observe the agent position relative to the episode start coordinate frame', 'create_VelocityAction': 'create a VelocityAction to move the agent with configurable linear and angular velocity controls', 'create_NavigationTask': 'create a NavigationTask to configure and run navigation episodes with start positions and goal specifications'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/tasks/nav/object_nav_task.py

Prompts

```
['create an InstanceImageGoalNavEpisode with goal_object_id and goal_image_id for navigation', 'create an InstanceImageGoalSensor to render instance image goals from camera parameters', 'create an InstanceImageGoalHFOVSensor to return the horizontal field of view of image goals', 'review the InstanceImageGoal class that holds image_goals list and object_surface_area', 'review the InstanceImageParameters class with position, rotation, hfov, and image_dimensions fields', 'create a PointGoalSensor to compute cartesian or polar goal observations for point goal navigation', 'create an ImageGoalSensor to return RGB images taken from the goal position with random rotation', 'create an EpisodicGPSSensor to observe the agent position relative to the episode start coordinate frame', 'create a VelocityAction to move the agent with configurable linear and angular velocity controls', 'create a NavigationTask to configure and run navigation episodes with start positions and goal specifications', 'create an ObjectGoalNavEpisode with a target object category and scene ID for navigation', 'create an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define a navigable viewpoint around an object', 'build an ObjectGoalSensor to observe object goal specifications by category ID or object ID', "register the ObjectNav-v1 task with Habitat's registry for object goal navigation episodes", 'build a ShortestPathFollower instance with a HabitatSim and goal radius for navigation', 'get the next action along the shortest path to a goal position', 'create a one-hot encoding numpy array from a HabitatSim action integer', 'review the ShortestPathFollower class and its get_next_action method for navigation', 'refactor the ShortestPathFollower to change stop_on_error behavior on GreedyFollowerError']
```

Usage

```
{'create_ObjectGoalNavEpisode': 'create an ObjectGoalNavEpisode with a target object category and scene ID for navigation', 'create_ObjectGoal': 'create an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create_ObjectViewLocation': 'create an ObjectViewLocation with agent_state and iou to define a navigable viewpoint around an object', 'build_ObjectGoalSensor': 'build an ObjectGoalSensor to observe object goal specifications by category ID or object ID', 'register_ObjectNavigationTask': "register the ObjectNav-v1 task with Habitat's registry for object goal navigation episodes"}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/tasks/nav/shortest_path_follower.py

Prompts

```
['create an InstanceImageGoalNavEpisode with goal_object_id and goal_image_id for navigation', 'create an InstanceImageGoalSensor to render instance image goals from camera parameters', 'create an InstanceImageGoalHFOVSensor to return the horizontal field of view of image goals', 'review the InstanceImageGoal class that holds image_goals list and object_surface_area', 'review the InstanceImageParameters class with position, rotation, hfov, and image_dimensions fields', 'create a PointGoalSensor to compute cartesian or polar goal observations for point goal navigation', 'create an ImageGoalSensor to return RGB images taken from the goal position with random rotation', 'create an EpisodicGPSSensor to observe the agent position relative to the episode start coordinate frame', 'create a VelocityAction to move the agent with configurable linear and angular velocity controls', 'create a NavigationTask to configure and run navigation episodes with start positions and goal specifications', 'create an ObjectGoalNavEpisode with a target object category and scene ID for navigation', 'create an ObjectGoal with object_id, view_points, and room info for object navigation targets', 'create an ObjectViewLocation with agent_state and iou to define a navigable viewpoint around an object', 'build an ObjectGoalSensor to observe object goal specifications by category ID or object ID', "register the ObjectNav-v1 task with Habitat's registry for object goal navigation episodes", 'build a ShortestPathFollower instance with a HabitatSim and goal radius for navigation', 'get the next action along the shortest path to a goal position', 'create a one-hot encoding numpy array from a HabitatSim action integer', 'review the ShortestPathFollower class and its get_next_action method for navigation', 'refactor the ShortestPathFollower to change stop_on_error behavior on GreedyFollowerError']
```

Usage

```
{'build_shortest_path_follower': 'build a ShortestPathFollower instance with a HabitatSim and goal radius for navigation', 'get_next_action_shortest_path': 'get the next action along the shortest path to a goal position', 'create_action_one_hot': 'create a one-hot encoding numpy array from a HabitatSim action integer', 'review_shortest_path_follower_class': 'review the ShortestPathFollower class and its get_next_action method for navigation', 'refactor_stop_on_error': 'refactor the ShortestPathFollower to change stop_on_error behavior on GreedyFollowerError'}
```

