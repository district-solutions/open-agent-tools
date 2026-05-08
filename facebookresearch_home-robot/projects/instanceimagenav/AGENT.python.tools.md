# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/instanceimagenav/config_utils.py

Prompts

```
['get a Habitat simulator config from a YAML path with optional command line overrides', 'get a config that includes top-down map and collision measurements when generate_videos is enabled', 'get a config with Stretch agent embodiment settings including height radius and camera parameters', 'review the get_config function to understand how it patches Habitat simulator agent and sensor settings', 'refactor get_config to parameterize the hardcoded agent height radius and camera dimensions', 'create a Habitat top-down map measure that populates the metric with an initial map at step zero', 'get the original top-down map from the Habitat simulator with optional fog of war mask initialization', 'draw axis-aligned bounding boxes for goal objects on the top-down map using semantic scene annotations', 'draw the straight shortest path from the agent position to the goal on the top-down map', 'update the fog of war mask to reveal areas around the agent based on field of view and visibility distance']
```

Usage

```
{'get_config_from_yaml': 'get a Habitat simulator config from a YAML path with optional command line overrides', 'get_config_with_video_measurements': 'get a config that includes top-down map and collision measurements when generate_videos is enabled', 'get_config_stretch_agent': 'get a config with Stretch agent embodiment settings including height radius and camera parameters', 'review_get_config': 'review the get_config function to understand how it patches Habitat simulator agent and sensor settings', 'refactor_get_config': 'refactor get_config to parameterize the hardcoded agent height radius and camera dimensions'}
```

## File: facebookresearch_home-robot/projects/instanceimagenav/habitat_extensions.py

Prompts

```
['get a Habitat simulator config from a YAML path with optional command line overrides', 'get a config that includes top-down map and collision measurements when generate_videos is enabled', 'get a config with Stretch agent embodiment settings including height radius and camera parameters', 'review the get_config function to understand how it patches Habitat simulator agent and sensor settings', 'refactor get_config to parameterize the hardcoded agent height radius and camera dimensions', 'create a Habitat top-down map measure that populates the metric with an initial map at step zero', 'get the original top-down map from the Habitat simulator with optional fog of war mask initialization', 'draw axis-aligned bounding boxes for goal objects on the top-down map using semantic scene annotations', 'draw the straight shortest path from the agent position to the goal on the top-down map', 'update the fog of war mask to reveal areas around the agent based on field of view and visibility distance']
```

Usage

```
{'create_MyTopDownMap_measure': 'create a Habitat top-down map measure that populates the metric with an initial map at step zero', 'get_original_map': 'get the original top-down map from the Habitat simulator with optional fog of war mask initialization', 'draw_goals_aabb': 'draw axis-aligned bounding boxes for goal objects on the top-down map using semantic scene annotations', 'draw_shortest_path': 'draw the straight shortest path from the agent position to the goal on the top-down map', 'update_fog_of_war_mask': 'update the fog of war mask to reveal areas around the agent based on field of view and visibility distance'}
```

