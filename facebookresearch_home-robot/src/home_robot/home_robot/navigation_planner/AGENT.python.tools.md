# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/navigation_planner/discrete_planner.py

Prompts

```
['create a DiscretePlanner instance with turn angle, collision threshold, step size, and map resolution parameters', 'plan a low-level discrete navigation action from obstacle map, goal map, and sensor pose using FMM planner', 'get a short-term goal waypoint from the obstacle map and goal map using fast marching method pathfinding', 'check whether the agent had a collision and update the collision map with new obstacle cells', 'find the closest goal location in the goal map avoiding obstacles using Euclidean distance', 'create an FMMPlanner instance with a traversible binary map and optional scale and step size parameters', 'set a single goal point on the FMM planner and compute the fast marching distance map', 'set multiple long-term goals from a binary goal map and compute the FMM distance field', 'find the nearest traversible point to a multi-goal map within a specified distance threshold']
```

Usage

```
{'create_discrete_planner': 'create a DiscretePlanner instance with turn angle, collision threshold, step size, and map resolution parameters', 'plan_navigation_action': 'plan a low-level discrete navigation action from obstacle map, goal map, and sensor pose using FMM planner', 'get_short_term_goal': 'get a short-term goal waypoint from the obstacle map and goal map using fast marching method pathfinding', 'check_collision': 'check whether the agent had a collision and update the collision map with new obstacle cells', 'get_closest_goal': 'find the closest goal location in the goal map avoiding obstacles using Euclidean distance'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/navigation_planner/fmm_planner.py

Prompts

```
['create a DiscretePlanner instance with turn angle, collision threshold, step size, and map resolution parameters', 'plan a low-level discrete navigation action from obstacle map, goal map, and sensor pose using FMM planner', 'get a short-term goal waypoint from the obstacle map and goal map using fast marching method pathfinding', 'check whether the agent had a collision and update the collision map with new obstacle cells', 'find the closest goal location in the goal map avoiding obstacles using Euclidean distance', 'create an FMMPlanner instance with a traversible binary map and optional scale and step size parameters', 'set a single goal point on the FMM planner and compute the fast marching distance map', 'set multiple long-term goals from a binary goal map and compute the FMM distance field', 'find the nearest traversible point to a multi-goal map within a specified distance threshold']
```

Usage

```
{'create_fmm_planner': 'create an FMMPlanner instance with a traversible binary map and optional scale and step size parameters', 'set_goal': 'set a single goal point on the FMM planner and compute the fast marching distance map', 'set_multi_goal': 'set multiple long-term goals from a binary goal map and compute the FMM distance field', 'get_short_term_goal': 'compute the nearest short-term goal within step size of the current robot state', 'find_within_distance_to_multi_goal': 'find the nearest traversible point to a multi-goal map within a specified distance threshold'}
```

