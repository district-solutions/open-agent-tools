# Agent Python Tools

- repo: facebookresearch/house3d
- repo_uri: https://github.com/facebookresearch/house3d

## File: facebookresearch_house3d/House3D/common.py

Prompts

```
['load a House3D config from a JSON file and validate required keys and file paths', 'create a default House3D config dict with coarse colormap for a given data prefix directory', 'create a default House3D config dict with fine colormap for a given data prefix directory', 'detect available NVIDIA GPU device IDs accessible from the current Linux environment', 'run the detect_nvidia_devices function to print available GPU device IDs to stdout', 'create a House object from a house ID and config using create_house function', 'render the current environment view as an RGB image using the Environment render method', 'move the agent forward or rotate in the simulated house environment using move_forward and rotate', 'generate a 2D top-down localization map of the agent position using gen_2dmap method', 'switch between houses in a MultiHouseEnv using reset_house with a house ID', 'create a House object from SUNCG dataset JSON, OBJ, and metadata CSV files to load house navigation data', 'set the target room type for a House instance and compute shortest-path connectivity map to that room', 'get a random valid navigable location within a specified room type using the House getRandomLocation method', 'parse wall bounding boxes from an OBJ file and return a list of wall objects with min and max coordinates', 'check whether a robot at a given continuous coordinate would collide with any obstacles in the House', 'create a RoomNavTask Gym environment wrapping a House3D Environment for room navigation', 'run a step on the RoomNavTask with a discrete or continuous action and get reward', 'reset the RoomNavTask episode and optionally set a specific target room type', 'refactor the RoomNavTask step method to support a new reward shaping type', 'review the reset_see_criteria function that adjusts pixel thresholds for object visibility']
```

Usage

```
{'load_config_from_json': 'load a House3D config from a JSON file and validate required keys and file paths', 'create_default_config_coarse': 'create a default House3D config dict with coarse colormap for a given data prefix directory', 'create_default_config_fine': 'create a default House3D config dict with fine colormap for a given data prefix directory', 'detect_nvidia_devices': 'detect available NVIDIA GPU device IDs accessible from the current Linux environment', 'run_detect_nvidia_devices': 'run the detect_nvidia_devices function to print available GPU device IDs to stdout'}
```

## File: facebookresearch_house3d/House3D/core.py

Prompts

```
['load a House3D config from a JSON file and validate required keys and file paths', 'create a default House3D config dict with coarse colormap for a given data prefix directory', 'create a default House3D config dict with fine colormap for a given data prefix directory', 'detect available NVIDIA GPU device IDs accessible from the current Linux environment', 'run the detect_nvidia_devices function to print available GPU device IDs to stdout', 'create a House object from a house ID and config using create_house function', 'render the current environment view as an RGB image using the Environment render method', 'move the agent forward or rotate in the simulated house environment using move_forward and rotate', 'generate a 2D top-down localization map of the agent position using gen_2dmap method', 'switch between houses in a MultiHouseEnv using reset_house with a house ID', 'create a House object from SUNCG dataset JSON, OBJ, and metadata CSV files to load house navigation data', 'set the target room type for a House instance and compute shortest-path connectivity map to that room', 'get a random valid navigable location within a specified room type using the House getRandomLocation method', 'parse wall bounding boxes from an OBJ file and return a list of wall objects with min and max coordinates', 'check whether a robot at a given continuous coordinate would collide with any obstacles in the House', 'create a RoomNavTask Gym environment wrapping a House3D Environment for room navigation', 'run a step on the RoomNavTask with a discrete or continuous action and get reward', 'reset the RoomNavTask episode and optionally set a specific target room type', 'refactor the RoomNavTask step method to support a new reward shaping type', 'review the reset_see_criteria function that adjusts pixel thresholds for object visibility']
```

Usage

```
{'create_house_from_id': 'create a House object from a house ID and config using create_house function', 'render_environment_view': 'render the current environment view as an RGB image using the Environment render method', 'move_agent_in_house': 'move the agent forward or rotate in the simulated house environment using move_forward and rotate', 'generate_2d_map': 'generate a 2D top-down localization map of the agent position using gen_2dmap method', 'switch_house_in_multi_env': 'switch between houses in a MultiHouseEnv using reset_house with a house ID'}
```

## File: facebookresearch_house3d/House3D/house.py

Prompts

```
['load a House3D config from a JSON file and validate required keys and file paths', 'create a default House3D config dict with coarse colormap for a given data prefix directory', 'create a default House3D config dict with fine colormap for a given data prefix directory', 'detect available NVIDIA GPU device IDs accessible from the current Linux environment', 'run the detect_nvidia_devices function to print available GPU device IDs to stdout', 'create a House object from a house ID and config using create_house function', 'render the current environment view as an RGB image using the Environment render method', 'move the agent forward or rotate in the simulated house environment using move_forward and rotate', 'generate a 2D top-down localization map of the agent position using gen_2dmap method', 'switch between houses in a MultiHouseEnv using reset_house with a house ID', 'create a House object from SUNCG dataset JSON, OBJ, and metadata CSV files to load house navigation data', 'set the target room type for a House instance and compute shortest-path connectivity map to that room', 'get a random valid navigable location within a specified room type using the House getRandomLocation method', 'parse wall bounding boxes from an OBJ file and return a list of wall objects with min and max coordinates', 'check whether a robot at a given continuous coordinate would collide with any obstacles in the House', 'create a RoomNavTask Gym environment wrapping a House3D Environment for room navigation', 'run a step on the RoomNavTask with a discrete or continuous action and get reward', 'reset the RoomNavTask episode and optionally set a specific target room type', 'refactor the RoomNavTask step method to support a new reward shaping type', 'review the reset_see_criteria function that adjusts pixel thresholds for object visibility']
```

Usage

```
{'create_House_instance': 'create a House object from SUNCG dataset JSON, OBJ, and metadata CSV files to load house navigation data', 'setTargetRoom_House': 'set the target room type for a House instance and compute shortest-path connectivity map to that room', 'getRandomLocation_House': 'get a random valid navigable location within a specified room type using the House getRandomLocation method', 'parse_walls': 'parse wall bounding boxes from an OBJ file and return a list of wall objects with min and max coordinates', 'check_occupy_House': 'check whether a robot at a given continuous coordinate would collide with any obstacles in the House'}
```

## File: facebookresearch_house3d/House3D/roomnav.py

Prompts

```
['load a House3D config from a JSON file and validate required keys and file paths', 'create a default House3D config dict with coarse colormap for a given data prefix directory', 'create a default House3D config dict with fine colormap for a given data prefix directory', 'detect available NVIDIA GPU device IDs accessible from the current Linux environment', 'run the detect_nvidia_devices function to print available GPU device IDs to stdout', 'create a House object from a house ID and config using create_house function', 'render the current environment view as an RGB image using the Environment render method', 'move the agent forward or rotate in the simulated house environment using move_forward and rotate', 'generate a 2D top-down localization map of the agent position using gen_2dmap method', 'switch between houses in a MultiHouseEnv using reset_house with a house ID', 'create a House object from SUNCG dataset JSON, OBJ, and metadata CSV files to load house navigation data', 'set the target room type for a House instance and compute shortest-path connectivity map to that room', 'get a random valid navigable location within a specified room type using the House getRandomLocation method', 'parse wall bounding boxes from an OBJ file and return a list of wall objects with min and max coordinates', 'check whether a robot at a given continuous coordinate would collide with any obstacles in the House', 'create a RoomNavTask Gym environment wrapping a House3D Environment for room navigation', 'run a step on the RoomNavTask with a discrete or continuous action and get reward', 'reset the RoomNavTask episode and optionally set a specific target room type', 'refactor the RoomNavTask step method to support a new reward shaping type', 'review the reset_see_criteria function that adjusts pixel thresholds for object visibility']
```

Usage

```
{'create_roomnavtask_gym_env': 'create a RoomNavTask Gym environment wrapping a House3D Environment for room navigation', 'run_roomnavtask_step': 'run a step on the RoomNavTask with a discrete or continuous action and get reward', 'reset_roomnavtask_target': 'reset the RoomNavTask episode and optionally set a specific target room type', 'refactor_roomnavtask_reward': 'refactor the RoomNavTask step method to support a new reward shaping type', 'review_reset_see_criteria': 'review the reset_see_criteria function that adjusts pixel thresholds for object visibility'}
```

