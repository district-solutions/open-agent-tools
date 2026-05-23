# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/utils/core.py

Prompts

```
['load a Hydra DictConfig from a YAML config file with optional overrides', 'setup random seed, habitat plugins, and wandb logger from a DictConfig', 'recursively resolve Hydra config interpolations to prevent multi-process resolution issues', 'save a list of rollout result dicts to a CSV file at a given path', 'print LLM planner responses to console with color-coded agent prefixes', 'unproject a batch of posed RGBD depth images to 3D XYZ coordinates using PyTorch tensors', 'unproject image coordinates with metric depth to 3D world space coordinates using numpy and magnum matrices', 'project a batch of 3D world coordinates to 2D image pixel coordinates using camera and projection matrices', 'convert an OpenGL camera pose matrix to OpenCV format by flipping the Y and Z axes', 'review the geometric utility functions for camera coordinate transformations between image space and 3D world space', 'init a list of Agent instances from a dict of agent configs and an EnvironmentInterface', 'find all receptacles in the current Habitat simulator scene with optional filter applied', 'check if a Furniture or Receptacle entity has an open default link allowing access', 'compute the distance from an agent end effector to a target object checking occlusion', 'load all faucet marker set points in global space from the simulator objects', 'print all rooms, furniture, objects, and receptacles from a WorldGraph to the console', 'print a map of furniture entity names to their simulation handles for debugging', 'print a map of object entity names to their simulation handles for debugging', 'get a list of semantic names for all navigable entities in a WorldGraph', 'review the world_graph utility module and its functions for WorldGraph entity inspection']
```

Usage

```
{'get_config': 'load a Hydra DictConfig from a YAML config file with optional overrides', 'setup_config': 'setup random seed, habitat plugins, and wandb logger from a DictConfig', 'fix_config': 'recursively resolve Hydra config interpolations to prevent multi-process resolution issues', 'save_data': 'save a list of rollout result dicts to a CSV file at a given path', 'rollout_print': 'print LLM planner responses to console with color-coded agent prefixes'}
```

## File: facebookresearch_partnr-planner/habitat_llm/utils/geometric.py

Prompts

```
['load a Hydra DictConfig from a YAML config file with optional overrides', 'setup random seed, habitat plugins, and wandb logger from a DictConfig', 'recursively resolve Hydra config interpolations to prevent multi-process resolution issues', 'save a list of rollout result dicts to a CSV file at a given path', 'print LLM planner responses to console with color-coded agent prefixes', 'unproject a batch of posed RGBD depth images to 3D XYZ coordinates using PyTorch tensors', 'unproject image coordinates with metric depth to 3D world space coordinates using numpy and magnum matrices', 'project a batch of 3D world coordinates to 2D image pixel coordinates using camera and projection matrices', 'convert an OpenGL camera pose matrix to OpenCV format by flipping the Y and Z axes', 'review the geometric utility functions for camera coordinate transformations between image space and 3D world space', 'init a list of Agent instances from a dict of agent configs and an EnvironmentInterface', 'find all receptacles in the current Habitat simulator scene with optional filter applied', 'check if a Furniture or Receptacle entity has an open default link allowing access', 'compute the distance from an agent end effector to a target object checking occlusion', 'load all faucet marker set points in global space from the simulator objects', 'print all rooms, furniture, objects, and receptacles from a WorldGraph to the console', 'print a map of furniture entity names to their simulation handles for debugging', 'print a map of object entity names to their simulation handles for debugging', 'get a list of semantic names for all navigable entities in a WorldGraph', 'review the world_graph utility module and its functions for WorldGraph entity inspection']
```

Usage

```
{'unproject_masked_depth_to_xyz': 'unproject a batch of posed RGBD depth images to 3D XYZ coordinates using PyTorch tensors', 'unproject_coordinates': 'unproject image coordinates with metric depth to 3D world space coordinates using numpy and magnum matrices', 'project_to_im_coordinates': 'project a batch of 3D world coordinates to 2D image pixel coordinates using camera and projection matrices', 'opengl_to_opencv': 'convert an OpenGL camera pose matrix to OpenCV format by flipping the Y and Z axes', 'review_geometric_utils': 'review the geometric utility functions for camera coordinate transformations between image space and 3D world space'}
```

## File: facebookresearch_partnr-planner/habitat_llm/utils/sim.py

Prompts

```
['load a Hydra DictConfig from a YAML config file with optional overrides', 'setup random seed, habitat plugins, and wandb logger from a DictConfig', 'recursively resolve Hydra config interpolations to prevent multi-process resolution issues', 'save a list of rollout result dicts to a CSV file at a given path', 'print LLM planner responses to console with color-coded agent prefixes', 'unproject a batch of posed RGBD depth images to 3D XYZ coordinates using PyTorch tensors', 'unproject image coordinates with metric depth to 3D world space coordinates using numpy and magnum matrices', 'project a batch of 3D world coordinates to 2D image pixel coordinates using camera and projection matrices', 'convert an OpenGL camera pose matrix to OpenCV format by flipping the Y and Z axes', 'review the geometric utility functions for camera coordinate transformations between image space and 3D world space', 'init a list of Agent instances from a dict of agent configs and an EnvironmentInterface', 'find all receptacles in the current Habitat simulator scene with optional filter applied', 'check if a Furniture or Receptacle entity has an open default link allowing access', 'compute the distance from an agent end effector to a target object checking occlusion', 'load all faucet marker set points in global space from the simulator objects', 'print all rooms, furniture, objects, and receptacles from a WorldGraph to the console', 'print a map of furniture entity names to their simulation handles for debugging', 'print a map of object entity names to their simulation handles for debugging', 'get a list of semantic names for all navigable entities in a WorldGraph', 'review the world_graph utility module and its functions for WorldGraph entity inspection']
```

Usage

```
{'init_agents': 'init a list of Agent instances from a dict of agent configs and an EnvironmentInterface', 'find_receptacles': 'find all receptacles in the current Habitat simulator scene with optional filter applied', 'is_open': 'check if a Furniture or Receptacle entity has an open default link allowing access', 'ee_distance_to_object': 'compute the distance from an agent end effector to a target object checking occlusion', 'get_faucet_points': 'load all faucet marker set points in global space from the simulator objects'}
```

## File: facebookresearch_partnr-planner/habitat_llm/utils/world_graph.py

Prompts

```
['load a Hydra DictConfig from a YAML config file with optional overrides', 'setup random seed, habitat plugins, and wandb logger from a DictConfig', 'recursively resolve Hydra config interpolations to prevent multi-process resolution issues', 'save a list of rollout result dicts to a CSV file at a given path', 'print LLM planner responses to console with color-coded agent prefixes', 'unproject a batch of posed RGBD depth images to 3D XYZ coordinates using PyTorch tensors', 'unproject image coordinates with metric depth to 3D world space coordinates using numpy and magnum matrices', 'project a batch of 3D world coordinates to 2D image pixel coordinates using camera and projection matrices', 'convert an OpenGL camera pose matrix to OpenCV format by flipping the Y and Z axes', 'review the geometric utility functions for camera coordinate transformations between image space and 3D world space', 'init a list of Agent instances from a dict of agent configs and an EnvironmentInterface', 'find all receptacles in the current Habitat simulator scene with optional filter applied', 'check if a Furniture or Receptacle entity has an open default link allowing access', 'compute the distance from an agent end effector to a target object checking occlusion', 'load all faucet marker set points in global space from the simulator objects', 'print all rooms, furniture, objects, and receptacles from a WorldGraph to the console', 'print a map of furniture entity names to their simulation handles for debugging', 'print a map of object entity names to their simulation handles for debugging', 'get a list of semantic names for all navigable entities in a WorldGraph', 'review the world_graph utility module and its functions for WorldGraph entity inspection']
```

Usage

```
{'print_all_entities': 'print all rooms, furniture, objects, and receptacles from a WorldGraph to the console', 'print_furniture_entity_handles': 'print a map of furniture entity names to their simulation handles for debugging', 'print_object_entity_handles': 'print a map of object entity names to their simulation handles for debugging', 'get_all_entity_names': 'get a list of semantic names for all navigable entities in a WorldGraph', 'review_world_graph_utils': 'review the world_graph utility module and its functions for WorldGraph entity inspection'}
```

