# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/dataset_generation/tests/test_episode_generator.py

Prompts

```
['initialize an episode generator with a gen_config and metadata_dict for the Partnr planner benchmark', 'generate a rearrangement episode from an initialized generator and an initial state configuration dictionary', 'get semantic debug information from the episode generator state for troubleshooting unstable episodes', 'test the LLM rearrange episode generator with multiple initial state configurations including clutter and furniture states', 'serialize and deserialize a CollaborationDatasetV0 containing generated episodes to and from JSON format', 'test the spatial temporal correction heuristic with parametrized evaluation proposition groups', 'run pytest on the evaluation generator test file to validate spatial temporal correction logic', 'test TemporalParser.constraint_from_groups to convert proposition index groups into a temporal constraint', 'test TemporalParser.groups_from_constraint to convert a corrected temporal constraint back into proposition index groups', 'test the spatial temporal correction heuristic using propositions_a dataset with is_on_top and is_next_to relations']
```

Usage

```
{'initialize_generator': 'initialize an episode generator with a gen_config and metadata_dict for the Partnr planner benchmark', 'generate_episode': 'generate a rearrangement episode from an initialized generator and an initial state configuration dictionary', 'get_generator_state_semantic_debug_info': 'get semantic debug information from the episode generator state for troubleshooting unstable episodes', 'test_llm_rearrange_episode_generator': 'test the LLM rearrange episode generator with multiple initial state configurations including clutter and furniture states', 'CollaborationDatasetV0_serialization': 'serialize and deserialize a CollaborationDatasetV0 containing generated episodes to and from JSON format'}
```

## File: facebookresearch_partnr-planner/dataset_generation/tests/test_evaluation_generator.py

Prompts

```
['initialize an episode generator with a gen_config and metadata_dict for the Partnr planner benchmark', 'generate a rearrangement episode from an initialized generator and an initial state configuration dictionary', 'get semantic debug information from the episode generator state for troubleshooting unstable episodes', 'test the LLM rearrange episode generator with multiple initial state configurations including clutter and furniture states', 'serialize and deserialize a CollaborationDatasetV0 containing generated episodes to and from JSON format', 'test the spatial temporal correction heuristic with parametrized evaluation proposition groups', 'run pytest on the evaluation generator test file to validate spatial temporal correction logic', 'test TemporalParser.constraint_from_groups to convert proposition index groups into a temporal constraint', 'test TemporalParser.groups_from_constraint to convert a corrected temporal constraint back into proposition index groups', 'test the spatial temporal correction heuristic using propositions_a dataset with is_on_top and is_next_to relations']
```

Usage

```
{'test_spatial_temporal_heuristic': 'test the spatial temporal correction heuristic with parametrized evaluation proposition groups', 'run_test_evaluation_generator': 'run pytest on the evaluation generator test file to validate spatial temporal correction logic', 'test_temporal_parser_constraint_from_groups': 'test TemporalParser.constraint_from_groups to convert proposition index groups into a temporal constraint', 'test_temporal_parser_groups_from_constraint': 'test TemporalParser.groups_from_constraint to convert a corrected temporal constraint back into proposition index groups', 'test_spatial_temporal_correction_with_propositions_a': 'test the spatial temporal correction heuristic using propositions_a dataset with is_on_top and is_next_to relations'}
```

