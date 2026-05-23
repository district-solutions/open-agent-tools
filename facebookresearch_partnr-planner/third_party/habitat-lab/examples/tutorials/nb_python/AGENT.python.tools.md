# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/examples/tutorials/nb_python/Habitat2_Quickstart.py

Prompts

```
['create a Habitat environment with high resolution rendering using insert_render_options to configure third RGB sensor at 512x512', 'build a custom RearrangeTask subclass NavPickTaskV1 that resets the agent to a random navigable point and selects a random target object', 'create a DistanceToTargetObject measure class that computes Euclidean distance from the robot end-effector to the target object scene position', 'build a NavPickReward measurement class that returns negative distance-to-object scaled by a configurable factor with collision penalties', 'create a NavPickSuccess measure class that checks if the robot is currently grasping the correct target object by comparing scene object IDs', 'display RGB, semantic, and depth sensor observations from a Habitat Lab environment using matplotlib', 'create a custom NavigationTask subclass that overrides episode active checking with collision and stop logic', "create a custom Habitat sensor that returns the agent's 3D position as an observation", 'create a ForwardOnlyAgent that moves forward until a goal distance threshold is reached', 'run a PPO reinforcement learning training loop for PointNav navigation using Habitat Baselines', 'run example_pointnav_draw_target_birdseye_view to draw a birdseye view of an agent and navigation goal', 'run example_pointnav_draw_target_birdseye_view_agent_on_border to draw birdseye views with the agent on map borders', 'run example_get_topdown_map to generate and display a topdown map from a Habitat simulation', 'run example_top_down_map_measure to navigate an agent with shortest path following and record a video with topdown map metrics', 'review the ShortestPathFollowerAgent class that uses ShortestPathFollower to extract the next action on the shortest path to a goal']
```

Usage

```
{'create_habitat_env_with_render_options': 'create a Habitat environment with high resolution rendering using insert_render_options to configure third RGB sensor at 512x512', 'build_navpick_task_class': 'build a custom RearrangeTask subclass NavPickTaskV1 that resets the agent to a random navigable point and selects a random target object', 'create_distance_to_target_measure': 'create a DistanceToTargetObject measure class that computes Euclidean distance from the robot end-effector to the target object scene position', 'build_navpick_reward_measure': 'build a NavPickReward measurement class that returns negative distance-to-object scaled by a configurable factor with collision penalties', 'create_navpick_success_measure': 'create a NavPickSuccess measure class that checks if the robot is currently grasping the correct target object by comparing scene object IDs'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/examples/tutorials/nb_python/Habitat_Lab.py

Prompts

```
['create a Habitat environment with high resolution rendering using insert_render_options to configure third RGB sensor at 512x512', 'build a custom RearrangeTask subclass NavPickTaskV1 that resets the agent to a random navigable point and selects a random target object', 'create a DistanceToTargetObject measure class that computes Euclidean distance from the robot end-effector to the target object scene position', 'build a NavPickReward measurement class that returns negative distance-to-object scaled by a configurable factor with collision penalties', 'create a NavPickSuccess measure class that checks if the robot is currently grasping the correct target object by comparing scene object IDs', 'display RGB, semantic, and depth sensor observations from a Habitat Lab environment using matplotlib', 'create a custom NavigationTask subclass that overrides episode active checking with collision and stop logic', "create a custom Habitat sensor that returns the agent's 3D position as an observation", 'create a ForwardOnlyAgent that moves forward until a goal distance threshold is reached', 'run a PPO reinforcement learning training loop for PointNav navigation using Habitat Baselines', 'run example_pointnav_draw_target_birdseye_view to draw a birdseye view of an agent and navigation goal', 'run example_pointnav_draw_target_birdseye_view_agent_on_border to draw birdseye views with the agent on map borders', 'run example_get_topdown_map to generate and display a topdown map from a Habitat simulation', 'run example_top_down_map_measure to navigate an agent with shortest path following and record a video with topdown map metrics', 'review the ShortestPathFollowerAgent class that uses ShortestPathFollower to extract the next action on the shortest path to a goal']
```

Usage

```
{'display_sample': 'display RGB, semantic, and depth sensor observations from a Habitat Lab environment using matplotlib', 'create_navigation_task': 'create a custom NavigationTask subclass that overrides episode active checking with collision and stop logic', 'create_sensor': "create a custom Habitat sensor that returns the agent's 3D position as an observation", 'create_agent': 'create a ForwardOnlyAgent that moves forward until a goal distance threshold is reached', 'run_rl_training': 'run a PPO reinforcement learning training loop for PointNav navigation using Habitat Baselines'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/examples/tutorials/nb_python/Habitat_Lab_TopdownMap_Visualization.py

Prompts

```
['create a Habitat environment with high resolution rendering using insert_render_options to configure third RGB sensor at 512x512', 'build a custom RearrangeTask subclass NavPickTaskV1 that resets the agent to a random navigable point and selects a random target object', 'create a DistanceToTargetObject measure class that computes Euclidean distance from the robot end-effector to the target object scene position', 'build a NavPickReward measurement class that returns negative distance-to-object scaled by a configurable factor with collision penalties', 'create a NavPickSuccess measure class that checks if the robot is currently grasping the correct target object by comparing scene object IDs', 'display RGB, semantic, and depth sensor observations from a Habitat Lab environment using matplotlib', 'create a custom NavigationTask subclass that overrides episode active checking with collision and stop logic', "create a custom Habitat sensor that returns the agent's 3D position as an observation", 'create a ForwardOnlyAgent that moves forward until a goal distance threshold is reached', 'run a PPO reinforcement learning training loop for PointNav navigation using Habitat Baselines', 'run example_pointnav_draw_target_birdseye_view to draw a birdseye view of an agent and navigation goal', 'run example_pointnav_draw_target_birdseye_view_agent_on_border to draw birdseye views with the agent on map borders', 'run example_get_topdown_map to generate and display a topdown map from a Habitat simulation', 'run example_top_down_map_measure to navigate an agent with shortest path following and record a video with topdown map metrics', 'review the ShortestPathFollowerAgent class that uses ShortestPathFollower to extract the next action on the shortest path to a goal']
```

Usage

```
{'run_pointnav_birdseye_view': 'run example_pointnav_draw_target_birdseye_view to draw a birdseye view of an agent and navigation goal', 'run_birdseye_view_agent_on_border': 'run example_pointnav_draw_target_birdseye_view_agent_on_border to draw birdseye views with the agent on map borders', 'run_get_topdown_map': 'run example_get_topdown_map to generate and display a topdown map from a Habitat simulation', 'run_top_down_map_measure': 'run example_top_down_map_measure to navigate an agent with shortest path following and record a video with topdown map metrics', 'review_ShortestPathFollowerAgent': 'review the ShortestPathFollowerAgent class that uses ShortestPathFollower to extract the next action on the shortest path to a goal'}
```

