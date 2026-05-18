# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/examples/create_env.py

Prompts

```
['create a Nocturne RL environment using Hydra config and run 80 simulation steps with vehicle actions', 'run the create_env example to test step and rendering functions in the Nocturne driving simulator', 'test rendering by calling getConeImage on the first vehicle with configurable view distance and angle', 'test env.step by sending Action objects with acceleration, steering, and head_angle to moving vehicles', 'review the create_rl_env function that sets up a Nocturne environment, resets it, and steps through 80 timesteps', 'run a Nocturne simulation from an example scenario JSON file with configurable parameters', 'save a rendered scenario image to a PNG file using matplotlib', 'get a flattened vector of visible objects, road points, stop signs, and traffic lights for a vehicle', 'apply an Action with acceleration, steering, and head angle to a vehicle in the simulation', 'query vehicles, cyclists, pedestrians, and all objects that moved in the current scenario', 'make a movie of the whole Nocturne scenario using scenario.getImage with target positions drawn', 'make a movie centered around a vehicle with the view rotating to follow the source vehicle', 'make a movie using getConeImage to render a cone-shaped view around a moving vehicle', 'make a single image of the whole Nocturne scenario and save it as a PNG file', 'make a single image of the visible state features using getFeaturesImage around a vehicle']
```

Usage

```
{'create_rl_env': 'create a Nocturne RL environment using Hydra config and run 80 simulation steps with vehicle actions', 'run_create_env': 'run the create_env example to test step and rendering functions in the Nocturne driving simulator', 'test_getConeImage': 'test rendering by calling getConeImage on the first vehicle with configurable view distance and angle', 'test_env_step': 'test env.step by sending Action objects with acceleration, steering, and head_angle to moving vehicles', 'review_create_rl_env': 'review the create_rl_env function that sets up a Nocturne environment, resets it, and steps through 80 timesteps'}
```

## File: facebookresearch_nocturne/examples/nocturne_functions.py

Prompts

```
['create a Nocturne RL environment using Hydra config and run 80 simulation steps with vehicle actions', 'run the create_env example to test step and rendering functions in the Nocturne driving simulator', 'test rendering by calling getConeImage on the first vehicle with configurable view distance and angle', 'test env.step by sending Action objects with acceleration, steering, and head_angle to moving vehicles', 'review the create_rl_env function that sets up a Nocturne environment, resets it, and steps through 80 timesteps', 'run a Nocturne simulation from an example scenario JSON file with configurable parameters', 'save a rendered scenario image to a PNG file using matplotlib', 'get a flattened vector of visible objects, road points, stop signs, and traffic lights for a vehicle', 'apply an Action with acceleration, steering, and head angle to a vehicle in the simulation', 'query vehicles, cyclists, pedestrians, and all objects that moved in the current scenario', 'make a movie of the whole Nocturne scenario using scenario.getImage with target positions drawn', 'make a movie centered around a vehicle with the view rotating to follow the source vehicle', 'make a movie using getConeImage to render a cone-shaped view around a moving vehicle', 'make a single image of the whole Nocturne scenario and save it as a PNG file', 'make a single image of the visible state features using getFeaturesImage around a vehicle']
```

Usage

```
{'run_simulation_scenario': 'run a Nocturne simulation from an example scenario JSON file with configurable parameters', 'save_image_rendering': 'save a rendered scenario image to a PNG file using matplotlib', 'get_flattened_visible_state': 'get a flattened vector of visible objects, road points, stop signs, and traffic lights for a vehicle', 'apply_action_to_vehicle': 'apply an Action with acceleration, steering, and head angle to a vehicle in the simulation', 'query_scenario_objects': 'query vehicles, cyclists, pedestrians, and all objects that moved in the current scenario'}
```

## File: facebookresearch_nocturne/examples/rendering.py

Prompts

```
['create a Nocturne RL environment using Hydra config and run 80 simulation steps with vehicle actions', 'run the create_env example to test step and rendering functions in the Nocturne driving simulator', 'test rendering by calling getConeImage on the first vehicle with configurable view distance and angle', 'test env.step by sending Action objects with acceleration, steering, and head_angle to moving vehicles', 'review the create_rl_env function that sets up a Nocturne environment, resets it, and steps through 80 timesteps', 'run a Nocturne simulation from an example scenario JSON file with configurable parameters', 'save a rendered scenario image to a PNG file using matplotlib', 'get a flattened vector of visible objects, road points, stop signs, and traffic lights for a vehicle', 'apply an Action with acceleration, steering, and head angle to a vehicle in the simulation', 'query vehicles, cyclists, pedestrians, and all objects that moved in the current scenario', 'make a movie of the whole Nocturne scenario using scenario.getImage with target positions drawn', 'make a movie centered around a vehicle with the view rotating to follow the source vehicle', 'make a movie using getConeImage to render a cone-shaped view around a moving vehicle', 'make a single image of the whole Nocturne scenario and save it as a PNG file', 'make a single image of the visible state features using getFeaturesImage around a vehicle']
```

Usage

```
{'make_movie_whole_scenario': 'make a movie of the whole Nocturne scenario using scenario.getImage with target positions drawn', 'make_movie_around_vehicle': 'make a movie centered around a vehicle with the view rotating to follow the source vehicle', 'make_movie_cone_view': 'make a movie using getConeImage to render a cone-shaped view around a moving vehicle', 'make_image_scenario': 'make a single image of the whole Nocturne scenario and save it as a PNG file', 'make_image_features': 'make a single image of the visible state features using getFeaturesImage around a vehicle'}
```

