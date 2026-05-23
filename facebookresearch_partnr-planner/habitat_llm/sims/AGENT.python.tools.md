# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/sims/collaboration_sim.py

Prompts

```
['create an ObjectStateMachine from a Habitat simulator and MetadataInterface with power, clean, and filled states', 'build a CollaborationSim instance from a DictConfig to manage object states in a Habitat simulation', 'review the CollaborationSim object_state_machine property to access the initialized ObjectStateMachine', 'run initialize_object_state_machine on CollaborationSim with a CollaborationEpisode to set initial object states', 'refactor the CollaborationSim by calling reconfigure with a new DictConfig and CollaborationEpisode to update metadata and states', 'build a MetadataInterface instance that loads HSSD object and receptacle metadata from CSV and JSON files', 'create a metadata dict by merging default paths with overrides from an omegaconf config node', 'test the MetadataInterface refresh_scene_caches method to populate receptacle and region semantic name mappings from a simulator', 'review the get_scene_objs_of_class method to find all ManagedObject instances of a given semantic class in the scene', 'summarize the get_template_handles_of_class method to query a MetadataMediator for all object template handles of a semantic class']
```

Usage

```
{'initialize_object_state_machine': 'create an ObjectStateMachine from a Habitat simulator and MetadataInterface with power, clean, and filled states', 'CollaborationSim_init': 'build a CollaborationSim instance from a DictConfig to manage object states in a Habitat simulation', 'CollaborationSim_object_state_machine': 'review the CollaborationSim object_state_machine property to access the initialized ObjectStateMachine', 'CollaborationSim_initialize_object_state_machine': 'run initialize_object_state_machine on CollaborationSim with a CollaborationEpisode to set initial object states', 'CollaborationSim_reconfigure': 'refactor the CollaborationSim by calling reconfigure with a new DictConfig and CollaborationEpisode to update metadata and states'}
```

## File: facebookresearch_partnr-planner/habitat_llm/sims/metadata_interface.py

Prompts

```
['create an ObjectStateMachine from a Habitat simulator and MetadataInterface with power, clean, and filled states', 'build a CollaborationSim instance from a DictConfig to manage object states in a Habitat simulation', 'review the CollaborationSim object_state_machine property to access the initialized ObjectStateMachine', 'run initialize_object_state_machine on CollaborationSim with a CollaborationEpisode to set initial object states', 'refactor the CollaborationSim by calling reconfigure with a new DictConfig and CollaborationEpisode to update metadata and states', 'build a MetadataInterface instance that loads HSSD object and receptacle metadata from CSV and JSON files', 'create a metadata dict by merging default paths with overrides from an omegaconf config node', 'test the MetadataInterface refresh_scene_caches method to populate receptacle and region semantic name mappings from a simulator', 'review the get_scene_objs_of_class method to find all ManagedObject instances of a given semantic class in the scene', 'summarize the get_template_handles_of_class method to query a MetadataMediator for all object template handles of a semantic class']
```

Usage

```
{'build_MetadataInterface': 'build a MetadataInterface instance that loads HSSD object and receptacle metadata from CSV and JSON files', 'create_get_metadata_dict_from_config': 'create a metadata dict by merging default paths with overrides from an omegaconf config node', 'test_refresh_scene_caches': 'test the MetadataInterface refresh_scene_caches method to populate receptacle and region semantic name mappings from a simulator', 'review_get_scene_objs_of_class': 'review the get_scene_objs_of_class method to find all ManagedObject instances of a given semantic class in the scene', 'summarize_get_template_handles_of_class': 'summarize the get_template_handles_of_class method to query a MetadataMediator for all object template handles of a semantic class'}
```

