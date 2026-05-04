# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/prefabs/simulation/checkpoint_test.py

Prompts

```
['test that simulation checkpoint data contains entities, game_masters, and raw_log keys', 'test checkpoint save and restore roundtrip preserves entity and game master names', 'test that non-serializable measurements are excluded from checkpoint JSON data', 'test checkpoint roundtrip restores both standard and reactive measurements on entities and game masters', 'test reactive measurements capture and publish_datum work correctly after checkpoint restore', 'run a Concordia simulation with entities and game masters using the Simulation class play method', 'add an entity with a prefab config and optional memory state to the simulation', 'add a game master with a prefab config to the simulation with shared memory bank', 'save simulation state to a JSON checkpoint file and load it back to resume', 'update a dynamic state variable on an entity component by entity name and key', 'run a QuestionnaireSimulation with a config, language model, and embedder to execute questionnaire-based agent simulations', 'save the current state of all entities and game masters to a JSON checkpoint file at a given step', 'load entity and game master states from a checkpoint dictionary to restore or update the simulation']
```

Usage

```
{'test_checkpoint_structure': 'test that simulation checkpoint data contains entities, game_masters, and raw_log keys', 'test_roundtrip_without_measurements': 'test checkpoint save and restore roundtrip preserves entity and game master names', 'test_measurements_dropped_by_json': 'test that non-serializable measurements are excluded from checkpoint JSON data', 'test_roundtrip_restores_measurements': 'test checkpoint roundtrip restores both standard and reactive measurements on entities and game masters', 'test_reactive_capture_after_restore': 'test reactive measurements capture and publish_datum work correctly after checkpoint restore'}
```

## File: google-deepmind_concordia/concordia/prefabs/simulation/generic.py

Prompts

```
['test that simulation checkpoint data contains entities, game_masters, and raw_log keys', 'test checkpoint save and restore roundtrip preserves entity and game master names', 'test that non-serializable measurements are excluded from checkpoint JSON data', 'test checkpoint roundtrip restores both standard and reactive measurements on entities and game masters', 'test reactive measurements capture and publish_datum work correctly after checkpoint restore', 'run a Concordia simulation with entities and game masters using the Simulation class play method', 'add an entity with a prefab config and optional memory state to the simulation', 'add a game master with a prefab config to the simulation with shared memory bank', 'save simulation state to a JSON checkpoint file and load it back to resume', 'update a dynamic state variable on an entity component by entity name and key', 'run a QuestionnaireSimulation with a config, language model, and embedder to execute questionnaire-based agent simulations', 'save the current state of all entities and game masters to a JSON checkpoint file at a given step', 'load entity and game master states from a checkpoint dictionary to restore or update the simulation']
```

Usage

```
{'run_simulation': 'run a Concordia simulation with entities and game masters using the Simulation class play method', 'add_entity_to_simulation': 'add an entity with a prefab config and optional memory state to the simulation', 'add_game_master_to_simulation': 'add a game master with a prefab config to the simulation with shared memory bank', 'save_and_load_checkpoints': 'save simulation state to a JSON checkpoint file and load it back to resume', 'set_component_dynamic_state': 'update a dynamic state variable on an entity component by entity name and key'}
```

## File: google-deepmind_concordia/concordia/prefabs/simulation/questionnaire_simulation.py

Prompts

```
['test that simulation checkpoint data contains entities, game_masters, and raw_log keys', 'test checkpoint save and restore roundtrip preserves entity and game master names', 'test that non-serializable measurements are excluded from checkpoint JSON data', 'test checkpoint roundtrip restores both standard and reactive measurements on entities and game masters', 'test reactive measurements capture and publish_datum work correctly after checkpoint restore', 'run a Concordia simulation with entities and game masters using the Simulation class play method', 'add an entity with a prefab config and optional memory state to the simulation', 'add a game master with a prefab config to the simulation with shared memory bank', 'save simulation state to a JSON checkpoint file and load it back to resume', 'update a dynamic state variable on an entity component by entity name and key', 'run a QuestionnaireSimulation with a config, language model, and embedder to execute questionnaire-based agent simulations', 'save the current state of all entities and game masters to a JSON checkpoint file at a given step', 'load entity and game master states from a checkpoint dictionary to restore or update the simulation']
```

Usage

```
{'run_questionnaire_simulation': 'run a QuestionnaireSimulation with a config, language model, and embedder to execute questionnaire-based agent simulations', 'add_game_master_to_simulation': 'add a game master entity to the simulation using an instance config with GAME_MASTER or INITIALIZER role', 'add_entity_to_simulation': 'add an entity to the simulation using an instance config with ENTITY role and optional pre-loaded memory state', 'save_simulation_checkpoint': 'save the current state of all entities and game masters to a JSON checkpoint file at a given step', 'load_simulation_from_checkpoint': 'load entity and game master states from a checkpoint dictionary to restore or update the simulation'}
```

