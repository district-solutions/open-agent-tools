# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/world_model/entities/floor.py

Prompts

```
['create a Floor entity from a name and properties dictionary for use in the Habitat simulator', 'sample valid placement locations on a Floor entity given a spatial constraint and reference object', 'get all object IDs between a navmesh point and the stage floor using a downward raycast', 'sample candidate placement poses on the floor with next_to or on spatial propositions', 'create a deep copy of a Floor entity preserving its name and properties', 'sample valid placement poses on a furniture entity using rejection sampling and spatial constraints', 'sort a list of sampled poses by their L2 distance to the agent base position', 'compute the minimum L2 distance from a new sample point to existing sampled poses', 'check whether a Furniture entity is articulated by inspecting its properties dictionary', 'compute valid placement locations on a Furniture instance given a spatial relation and agent']
```

Usage

```
{'create_Floor_entity': 'create a Floor entity from a name and properties dictionary for use in the Habitat simulator', 'sample_Floor_place_location': 'sample valid placement locations on a Floor entity given a spatial constraint and reference object', 'get_floor_object_ids': 'get all object IDs between a navmesh point and the stage floor using a downward raycast', 'sample_position_on_floor': 'sample candidate placement poses on the floor with next_to or on spatial propositions', 'deepcopy_Floor_entity': 'create a deep copy of a Floor entity preserving its name and properties'}
```

## File: facebookresearch_partnr-planner/habitat_llm/world_model/entities/furniture.py

Prompts

```
['create a Floor entity from a name and properties dictionary for use in the Habitat simulator', 'sample valid placement locations on a Floor entity given a spatial constraint and reference object', 'get all object IDs between a navmesh point and the stage floor using a downward raycast', 'sample candidate placement poses on the floor with next_to or on spatial propositions', 'create a deep copy of a Floor entity preserving its name and properties', 'sample valid placement poses on a furniture entity using rejection sampling and spatial constraints', 'sort a list of sampled poses by their L2 distance to the agent base position', 'compute the minimum L2 distance from a new sample point to existing sampled poses', 'check whether a Furniture entity is articulated by inspecting its properties dictionary', 'compute valid placement locations on a Furniture instance given a spatial relation and agent']
```

Usage

```
{'sample_position_on_furniture': 'sample valid placement poses on a furniture entity using rejection sampling and spatial constraints', 'sort_proposed_samples_based_on_distance_to_agent': 'sort a list of sampled poses by their L2 distance to the agent base position', 'distance_to_other_samples': 'compute the minimum L2 distance from a new sample point to existing sampled poses', 'Furniture_is_articulated': 'check whether a Furniture entity is articulated by inspecting its properties dictionary', 'Furniture_sample_place_location': 'compute valid placement locations on a Furniture instance given a spatial relation and agent'}
```

