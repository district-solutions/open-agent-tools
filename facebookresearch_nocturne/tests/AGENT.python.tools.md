# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/tests/test_config.py

Prompts

```
['test that the default Hydra config contains no None values in the scenario dictionary', 'test that custom scenario config values like max_visible_objects are propagated to the Nocturne simulation', 'run all config validation tests by calling the main entry point function', 'review the test_custom_config function to verify scenario config propagation assertions', 'summarize the test_config_values function that validates default Hydra config for None values', 'test that expert actions are computed correctly from inverse dynamics in the Nocturne simulation', 'create a Nocturne simulation from a scenario file with objects set to expert control mode', 'run a single simulation step with a given time delta using the Nocturne Simulation step method', 'get the expert action for a specific object at a given time step from the scenario', 'compare speed and heading between test and ground truth simulation objects using numpy isclose', 'test the RL environment step and rendering functions with vehicle actions over 90 timesteps', 'run the test_rl_env function to verify vehicle movement and cone image rendering in Nocturne', 'create a Nocturne RL environment using Hydra compose and initialize with a config file', 'test that vehicles move when stepping the environment with acceleration and steering actions', 'test rendering a cone image for a vehicle with specified distance, FOV, and heading', 'test vehicle collision detection by placing two vehicles at overlapping positions and asserting getCollided returns true', 'test road line collision by positioning a vehicle so a collidable road segment intersects its geometry', 'test the visible_state function returns padded arrays matching max_visible_objects and max_visible_road_points config values', 'test cone image generation with different start times and pedestrian settings to verify scene construction changes']
```

Usage

```
{'test_config_values': 'test that the default Hydra config contains no None values in the scenario dictionary', 'test_custom_config': 'test that custom scenario config values like max_visible_objects are propagated to the Nocturne simulation', 'run_test_main': 'run all config validation tests by calling the main entry point function', 'review_test_custom_config': 'review the test_custom_config function to verify scenario config propagation assertions', 'summarize_test_config_values': 'summarize the test_config_values function that validates default Hydra config for None values'}
```

## File: facebookresearch_nocturne/tests/test_dynamics.py

Prompts

```
['test that the default Hydra config contains no None values in the scenario dictionary', 'test that custom scenario config values like max_visible_objects are propagated to the Nocturne simulation', 'run all config validation tests by calling the main entry point function', 'review the test_custom_config function to verify scenario config propagation assertions', 'summarize the test_config_values function that validates default Hydra config for None values', 'test that expert actions are computed correctly from inverse dynamics in the Nocturne simulation', 'create a Nocturne simulation from a scenario file with objects set to expert control mode', 'run a single simulation step with a given time delta using the Nocturne Simulation step method', 'get the expert action for a specific object at a given time step from the scenario', 'compare speed and heading between test and ground truth simulation objects using numpy isclose', 'test the RL environment step and rendering functions with vehicle actions over 90 timesteps', 'run the test_rl_env function to verify vehicle movement and cone image rendering in Nocturne', 'create a Nocturne RL environment using Hydra compose and initialize with a config file', 'test that vehicles move when stepping the environment with acceleration and steering actions', 'test rendering a cone image for a vehicle with specified distance, FOV, and heading', 'test vehicle collision detection by placing two vehicles at overlapping positions and asserting getCollided returns true', 'test road line collision by positioning a vehicle so a collidable road segment intersects its geometry', 'test the visible_state function returns padded arrays matching max_visible_objects and max_visible_road_points config values', 'test cone image generation with different start times and pedestrian settings to verify scene construction changes']
```

Usage

```
{'test_inverse_dynamics': 'test that expert actions are computed correctly from inverse dynamics in the Nocturne simulation', 'create_sim_with_expert_control': 'create a Nocturne simulation from a scenario file with objects set to expert control mode', 'run_simulation_step': 'run a single simulation step with a given time delta using the Nocturne Simulation step method', 'get_expert_action': 'get the expert action for a specific object at a given time step from the scenario', 'compare_object_states': 'compare speed and heading between test and ground truth simulation objects using numpy isclose'}
```

## File: facebookresearch_nocturne/tests/test_rl_env.py

Prompts

```
['test that the default Hydra config contains no None values in the scenario dictionary', 'test that custom scenario config values like max_visible_objects are propagated to the Nocturne simulation', 'run all config validation tests by calling the main entry point function', 'review the test_custom_config function to verify scenario config propagation assertions', 'summarize the test_config_values function that validates default Hydra config for None values', 'test that expert actions are computed correctly from inverse dynamics in the Nocturne simulation', 'create a Nocturne simulation from a scenario file with objects set to expert control mode', 'run a single simulation step with a given time delta using the Nocturne Simulation step method', 'get the expert action for a specific object at a given time step from the scenario', 'compare speed and heading between test and ground truth simulation objects using numpy isclose', 'test the RL environment step and rendering functions with vehicle actions over 90 timesteps', 'run the test_rl_env function to verify vehicle movement and cone image rendering in Nocturne', 'create a Nocturne RL environment using Hydra compose and initialize with a config file', 'test that vehicles move when stepping the environment with acceleration and steering actions', 'test rendering a cone image for a vehicle with specified distance, FOV, and heading', 'test vehicle collision detection by placing two vehicles at overlapping positions and asserting getCollided returns true', 'test road line collision by positioning a vehicle so a collidable road segment intersects its geometry', 'test the visible_state function returns padded arrays matching max_visible_objects and max_visible_road_points config values', 'test cone image generation with different start times and pedestrian settings to verify scene construction changes']
```

Usage

```
{'test_rl_env_step_and_rendering': 'test the RL environment step and rendering functions with vehicle actions over 90 timesteps', 'run_rl_env_test': 'run the test_rl_env function to verify vehicle movement and cone image rendering in Nocturne', 'create_env_with_hydra_config': 'create a Nocturne RL environment using Hydra compose and initialize with a config file', 'test_vehicle_movement_with_actions': 'test that vehicles move when stepping the environment with acceleration and steering actions', 'test_cone_image_rendering': 'test rendering a cone image for a vehicle with specified distance, FOV, and heading'}
```

## File: facebookresearch_nocturne/tests/test_simulation_functions.py

Prompts

```
['test that the default Hydra config contains no None values in the scenario dictionary', 'test that custom scenario config values like max_visible_objects are propagated to the Nocturne simulation', 'run all config validation tests by calling the main entry point function', 'review the test_custom_config function to verify scenario config propagation assertions', 'summarize the test_config_values function that validates default Hydra config for None values', 'test that expert actions are computed correctly from inverse dynamics in the Nocturne simulation', 'create a Nocturne simulation from a scenario file with objects set to expert control mode', 'run a single simulation step with a given time delta using the Nocturne Simulation step method', 'get the expert action for a specific object at a given time step from the scenario', 'compare speed and heading between test and ground truth simulation objects using numpy isclose', 'test the RL environment step and rendering functions with vehicle actions over 90 timesteps', 'run the test_rl_env function to verify vehicle movement and cone image rendering in Nocturne', 'create a Nocturne RL environment using Hydra compose and initialize with a config file', 'test that vehicles move when stepping the environment with acceleration and steering actions', 'test rendering a cone image for a vehicle with specified distance, FOV, and heading', 'test vehicle collision detection by placing two vehicles at overlapping positions and asserting getCollided returns true', 'test road line collision by positioning a vehicle so a collidable road segment intersects its geometry', 'test the visible_state function returns padded arrays matching max_visible_objects and max_visible_road_points config values', 'test cone image generation with different start times and pedestrian settings to verify scene construction changes']
```

Usage

```
{'test_simulation_collisions': 'test vehicle collision detection by placing two vehicles at overlapping positions and asserting getCollided returns true', 'test_road_collision': 'test road line collision by positioning a vehicle so a collidable road segment intersects its geometry', 'run_simulation_step': 'run a nocturne simulation step with a small time delta to update collision state after repositioning vehicles', 'test_visible_state_padding': 'test the visible_state function returns padded arrays matching max_visible_objects and max_visible_road_points config values', 'test_cone_image_generation': 'test cone image generation with different start times and pedestrian settings to verify scene construction changes'}
```

