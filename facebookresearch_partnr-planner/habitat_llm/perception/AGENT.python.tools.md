# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/perception/perception.py

Prompts

```
['review the abstract Perception class and its detectors initialization pattern', 'refactor the Perception abstract class to add concrete initialization logic', 'build a concrete subclass of Perception that implements the abstract initialize method', 'test a concrete Perception subclass to verify detectors are stored correctly', 'summarize the Perception abstract base class and its role in the agent perception stack', 'preprocess simulator observations for each agent extracting camera intrinsics, depth, and panoptic masks', 'detect objects in the agent field of view using panoptic sensor output and depth images', 'map object sim handles from the panoptic image to their semantic category names', 'build a 3x3 camera intrinsics matrix from focal length and image center parameters', 'get object detections with masks, locations, and camera info for non-privileged graph updates', 'build a PerceptionSim instance from a RearrangeSim to construct a complete ground truth world graph with rooms, furniture, and objects', "get a partial world graph subgraph containing only objects visible in the agent's current field of view", 'get the most recent complete ground truth world graph with updated object receptacle and agent room associations', 'initialize the world graph in partial observability mode returning only receptacles without objects for the agent', 'update the ground truth graph to reflect which receptacle each object currently rests on after being moved']
```

Usage

```
{'review_Perception_class': 'review the abstract Perception class and its detectors initialization pattern', 'refactor_Perception_initialize': 'refactor the Perception abstract class to add concrete initialization logic', 'build_Perception_subclass': 'build a concrete subclass of Perception that implements the abstract initialize method', 'test_Perception_subclass': 'test a concrete Perception subclass to verify detectors are stored correctly', 'summarize_Perception_class': 'summarize the Perception abstract base class and its role in the agent perception stack'}
```

## File: facebookresearch_partnr-planner/habitat_llm/perception/perception_obs.py

Prompts

```
['review the abstract Perception class and its detectors initialization pattern', 'refactor the Perception abstract class to add concrete initialization logic', 'build a concrete subclass of Perception that implements the abstract initialize method', 'test a concrete Perception subclass to verify detectors are stored correctly', 'summarize the Perception abstract base class and its role in the agent perception stack', 'preprocess simulator observations for each agent extracting camera intrinsics, depth, and panoptic masks', 'detect objects in the agent field of view using panoptic sensor output and depth images', 'map object sim handles from the panoptic image to their semantic category names', 'build a 3x3 camera intrinsics matrix from focal length and image center parameters', 'get object detections with masks, locations, and camera info for non-privileged graph updates', 'build a PerceptionSim instance from a RearrangeSim to construct a complete ground truth world graph with rooms, furniture, and objects', "get a partial world graph subgraph containing only objects visible in the agent's current field of view", 'get the most recent complete ground truth world graph with updated object receptacle and agent room associations', 'initialize the world graph in partial observability mode returning only receptacles without objects for the agent', 'update the ground truth graph to reflect which receptacle each object currently rests on after being moved']
```

Usage

```
{'preprocess_agent_observations': 'preprocess simulator observations for each agent extracting camera intrinsics, depth, and panoptic masks', 'detect_objects_from_panoptic': 'detect objects in the agent field of view using panoptic sensor output and depth images', 'map_panoptic_handles_to_categories': 'map object sim handles from the panoptic image to their semantic category names', 'build_intrinsics_matrix': 'build a 3x3 camera intrinsics matrix from focal length and image center parameters', 'get_object_detections_non_privileged': 'get object detections with masks, locations, and camera info for non-privileged graph updates'}
```

## File: facebookresearch_partnr-planner/habitat_llm/perception/perception_sim.py

Prompts

```
['review the abstract Perception class and its detectors initialization pattern', 'refactor the Perception abstract class to add concrete initialization logic', 'build a concrete subclass of Perception that implements the abstract initialize method', 'test a concrete Perception subclass to verify detectors are stored correctly', 'summarize the Perception abstract base class and its role in the agent perception stack', 'preprocess simulator observations for each agent extracting camera intrinsics, depth, and panoptic masks', 'detect objects in the agent field of view using panoptic sensor output and depth images', 'map object sim handles from the panoptic image to their semantic category names', 'build a 3x3 camera intrinsics matrix from focal length and image center parameters', 'get object detections with masks, locations, and camera info for non-privileged graph updates', 'build a PerceptionSim instance from a RearrangeSim to construct a complete ground truth world graph with rooms, furniture, and objects', "get a partial world graph subgraph containing only objects visible in the agent's current field of view", 'get the most recent complete ground truth world graph with updated object receptacle and agent room associations', 'initialize the world graph in partial observability mode returning only receptacles without objects for the agent', 'update the ground truth graph to reflect which receptacle each object currently rests on after being moved']
```

Usage

```
{'build_world_graph_from_sim': 'build a PerceptionSim instance from a RearrangeSim to construct a complete ground truth world graph with rooms, furniture, and objects', 'get_recent_subgraph': "get a partial world graph subgraph containing only objects visible in the agent's current field of view", 'get_recent_graph': 'get the most recent complete ground truth world graph with updated object receptacle and agent room associations', 'initialize_partial_obs': 'initialize the world graph in partial observability mode returning only receptacles without objects for the agent', 'update_object_receptacle_associations': 'update the ground truth graph to reflect which receptacle each object currently rests on after being moved'}
```

