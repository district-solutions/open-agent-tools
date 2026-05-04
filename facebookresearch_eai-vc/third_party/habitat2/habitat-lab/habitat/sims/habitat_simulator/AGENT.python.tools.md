# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/sims/habitat_simulator/actions.py

Prompts

```
['extend the HabitatSimActions singleton to register a new custom action name and get its integer ID', 'check if a given action name is already registered in the HabitatSimActions singleton', 'get the integer value of a registered action by name using attribute or item access on HabitatSimActions', 'review the HabitatSimV0ActionSpaceConfiguration class that defines stop, move_forward, turn_left, and turn_right actions', 'review the HabitatSimV1ActionSpaceConfiguration class that extends v0 with look_up and look_down tilt actions', 'create a DebugVisualizer instance with a habitat_sim.Simulator and output path for visual debugging', 'point the debug camera at a target 3D position using look_at with optional look_from vector', 'render and save a debug observation as a timestamped PNG image file to disk', 'compute camera placement and save an observation image of a rigid object from a given angle', 'produce a video from cached debug observations with configurable FPS and output path', 'create a HabitatSim simulator instance from a DictConfig to run embodied AI simulation', 'run the HabitatSim reset and step methods to navigate an agent through a scene', 'build a sensor suite with RGB, depth, and semantic sensors for the HabitatSim simulator', 'test the geodesic_distance method to compute shortest path distance between two positions in a scene', 'refactor the overwrite_config function to merge Habitat Lab config into Habitat-Sim config with custom transformations', 'add a wireframe box object to the habitat simulator at a given center position with optional orientation', 'add a visualization-only wireframe sphere to the habitat simulator at a given global position and radius', 'snap a rigid object down along gravity onto the nearest support surface and validate placement', 'get the eight bounding box corner coordinates of a rigid object in its local space', 'get a dictionary mapping all active object IDs to their descriptive handle names in the simulator']
```

Usage

```
{'extend_action_space': 'extend the HabitatSimActions singleton to register a new custom action name and get its integer ID', 'has_action': 'check if a given action name is already registered in the HabitatSimActions singleton', 'get_action_value': 'get the integer value of a registered action by name using attribute or item access on HabitatSimActions', 'review_v0_action_space': 'review the HabitatSimV0ActionSpaceConfiguration class that defines stop, move_forward, turn_left, and turn_right actions', 'review_v1_action_space': 'review the HabitatSimV1ActionSpaceConfiguration class that extends v0 with look_up and look_down tilt actions'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/sims/habitat_simulator/debug_visualizer.py

Prompts

```
['extend the HabitatSimActions singleton to register a new custom action name and get its integer ID', 'check if a given action name is already registered in the HabitatSimActions singleton', 'get the integer value of a registered action by name using attribute or item access on HabitatSimActions', 'review the HabitatSimV0ActionSpaceConfiguration class that defines stop, move_forward, turn_left, and turn_right actions', 'review the HabitatSimV1ActionSpaceConfiguration class that extends v0 with look_up and look_down tilt actions', 'create a DebugVisualizer instance with a habitat_sim.Simulator and output path for visual debugging', 'point the debug camera at a target 3D position using look_at with optional look_from vector', 'render and save a debug observation as a timestamped PNG image file to disk', 'compute camera placement and save an observation image of a rigid object from a given angle', 'produce a video from cached debug observations with configurable FPS and output path', 'create a HabitatSim simulator instance from a DictConfig to run embodied AI simulation', 'run the HabitatSim reset and step methods to navigate an agent through a scene', 'build a sensor suite with RGB, depth, and semantic sensors for the HabitatSim simulator', 'test the geodesic_distance method to compute shortest path distance between two positions in a scene', 'refactor the overwrite_config function to merge Habitat Lab config into Habitat-Sim config with custom transformations', 'add a wireframe box object to the habitat simulator at a given center position with optional orientation', 'add a visualization-only wireframe sphere to the habitat simulator at a given global position and radius', 'snap a rigid object down along gravity onto the nearest support surface and validate placement', 'get the eight bounding box corner coordinates of a rigid object in its local space', 'get a dictionary mapping all active object IDs to their descriptive handle names in the simulator']
```

Usage

```
{'create_debug_visualizer': 'create a DebugVisualizer instance with a habitat_sim.Simulator and output path for visual debugging', 'look_at_camera_target': 'point the debug camera at a target 3D position using look_at with optional look_from vector', 'save_observation_image': 'render and save a debug observation as a timestamped PNG image file to disk', 'peek_rigid_object_view': 'compute camera placement and save an observation image of a rigid object from a given angle', 'make_debug_video': 'produce a video from cached debug observations with configurable FPS and output path'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/sims/habitat_simulator/habitat_simulator.py

Prompts

```
['extend the HabitatSimActions singleton to register a new custom action name and get its integer ID', 'check if a given action name is already registered in the HabitatSimActions singleton', 'get the integer value of a registered action by name using attribute or item access on HabitatSimActions', 'review the HabitatSimV0ActionSpaceConfiguration class that defines stop, move_forward, turn_left, and turn_right actions', 'review the HabitatSimV1ActionSpaceConfiguration class that extends v0 with look_up and look_down tilt actions', 'create a DebugVisualizer instance with a habitat_sim.Simulator and output path for visual debugging', 'point the debug camera at a target 3D position using look_at with optional look_from vector', 'render and save a debug observation as a timestamped PNG image file to disk', 'compute camera placement and save an observation image of a rigid object from a given angle', 'produce a video from cached debug observations with configurable FPS and output path', 'create a HabitatSim simulator instance from a DictConfig to run embodied AI simulation', 'run the HabitatSim reset and step methods to navigate an agent through a scene', 'build a sensor suite with RGB, depth, and semantic sensors for the HabitatSim simulator', 'test the geodesic_distance method to compute shortest path distance between two positions in a scene', 'refactor the overwrite_config function to merge Habitat Lab config into Habitat-Sim config with custom transformations', 'add a wireframe box object to the habitat simulator at a given center position with optional orientation', 'add a visualization-only wireframe sphere to the habitat simulator at a given global position and radius', 'snap a rigid object down along gravity onto the nearest support surface and validate placement', 'get the eight bounding box corner coordinates of a rigid object in its local space', 'get a dictionary mapping all active object IDs to their descriptive handle names in the simulator']
```

Usage

```
{'create_HabitatSim_simulator': 'create a HabitatSim simulator instance from a DictConfig to run embodied AI simulation', 'run_HabitatSim_reset_and_step': 'run the HabitatSim reset and step methods to navigate an agent through a scene', 'build_HabitatSim_sensor_suite': 'build a sensor suite with RGB, depth, and semantic sensors for the HabitatSim simulator', 'test_geodesic_distance': 'test the geodesic_distance method to compute shortest path distance between two positions in a scene', 'refactor_overwrite_config': 'refactor the overwrite_config function to merge Habitat Lab config into Habitat-Sim config with custom transformations'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/sims/habitat_simulator/sim_utilities.py

Prompts

```
['extend the HabitatSimActions singleton to register a new custom action name and get its integer ID', 'check if a given action name is already registered in the HabitatSimActions singleton', 'get the integer value of a registered action by name using attribute or item access on HabitatSimActions', 'review the HabitatSimV0ActionSpaceConfiguration class that defines stop, move_forward, turn_left, and turn_right actions', 'review the HabitatSimV1ActionSpaceConfiguration class that extends v0 with look_up and look_down tilt actions', 'create a DebugVisualizer instance with a habitat_sim.Simulator and output path for visual debugging', 'point the debug camera at a target 3D position using look_at with optional look_from vector', 'render and save a debug observation as a timestamped PNG image file to disk', 'compute camera placement and save an observation image of a rigid object from a given angle', 'produce a video from cached debug observations with configurable FPS and output path', 'create a HabitatSim simulator instance from a DictConfig to run embodied AI simulation', 'run the HabitatSim reset and step methods to navigate an agent through a scene', 'build a sensor suite with RGB, depth, and semantic sensors for the HabitatSim simulator', 'test the geodesic_distance method to compute shortest path distance between two positions in a scene', 'refactor the overwrite_config function to merge Habitat Lab config into Habitat-Sim config with custom transformations', 'add a wireframe box object to the habitat simulator at a given center position with optional orientation', 'add a visualization-only wireframe sphere to the habitat simulator at a given global position and radius', 'snap a rigid object down along gravity onto the nearest support surface and validate placement', 'get the eight bounding box corner coordinates of a rigid object in its local space', 'get a dictionary mapping all active object IDs to their descriptive handle names in the simulator']
```

Usage

```
{'add_wire_box': 'add a wireframe box object to the habitat simulator at a given center position with optional orientation', 'add_viz_sphere': 'add a visualization-only wireframe sphere to the habitat simulator at a given global position and radius', 'snap_down': 'snap a rigid object down along gravity onto the nearest support surface and validate placement', 'get_bb_corners': 'get the eight bounding box corner coordinates of a rigid object in its local space', 'get_all_object_ids': 'get a dictionary mapping all active object IDs to their descriptive handle names in the simulator'}
```

