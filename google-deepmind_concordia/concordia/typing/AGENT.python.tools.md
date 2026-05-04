# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/typing/entity.py

Prompts

```
['create an ActionSpec dataclass instance with a call_to_action string and output type', 'validate an action string against an ActionSpec using the validate method', 'convert an ActionSpec instance to a JSON-serializable dictionary using to_dict', 'reconstruct an ActionSpec from a dictionary using action_spec_from_dict', 'implement a concrete Entity subclass with name, act, and observe methods', 'build a python module that subclasses ContextComponent and overrides pre_act and post_act methods', 'build a python module that subclasses ActingComponent and implements get_action_attempt to decide entity actions', 'review the Phase enum successors property to understand valid lifecycle transitions between READY PRE_ACT and UPDATE', 'build a python module that subclasses BaseComponent and implements get_state and set_state for serialization', 'review the EntityWithComponents abstract class to understand get_component and phase management for entity composition', 'build a prefab entity by subclassing Prefab and implementing the abstract build method', 'create an InstanceConfig dataclass with a prefab name, Role enum value, and params mapping', 'create a Config dataclass with prefabs mapping, instances sequence, default premise, and max steps', 'define a Role StrEnum value as ENTITY, GAME_MASTER, or INITIALIZER for prefab instances', 'review a Prefab subclass to ensure it defines the required description class attribute', 'run a Concordia simulation with a premise string and max steps limit', 'add a game master entity to the simulation for world state management', 'add an entity to the simulation as a passive agent', 'get the list of game master entities from the simulation', 'get the list of all entities in the simulation']
```

Usage

```
{'create_action_spec': 'create an ActionSpec dataclass instance with a call_to_action string and output type', 'validate_action': 'validate an action string against an ActionSpec using the validate method', 'convert_action_spec_to_dict': 'convert an ActionSpec instance to a JSON-serializable dictionary using to_dict', 'deserialize_action_spec_from_dict': 'reconstruct an ActionSpec from a dictionary using action_spec_from_dict', 'implement_entity_subclass': 'implement a concrete Entity subclass with name, act, and observe methods'}
```

## File: google-deepmind_concordia/concordia/typing/entity_component.py

Prompts

```
['create an ActionSpec dataclass instance with a call_to_action string and output type', 'validate an action string against an ActionSpec using the validate method', 'convert an ActionSpec instance to a JSON-serializable dictionary using to_dict', 'reconstruct an ActionSpec from a dictionary using action_spec_from_dict', 'implement a concrete Entity subclass with name, act, and observe methods', 'build a python module that subclasses ContextComponent and overrides pre_act and post_act methods', 'build a python module that subclasses ActingComponent and implements get_action_attempt to decide entity actions', 'review the Phase enum successors property to understand valid lifecycle transitions between READY PRE_ACT and UPDATE', 'build a python module that subclasses BaseComponent and implements get_state and set_state for serialization', 'review the EntityWithComponents abstract class to understand get_component and phase management for entity composition', 'build a prefab entity by subclassing Prefab and implementing the abstract build method', 'create an InstanceConfig dataclass with a prefab name, Role enum value, and params mapping', 'create a Config dataclass with prefabs mapping, instances sequence, default premise, and max steps', 'define a Role StrEnum value as ENTITY, GAME_MASTER, or INITIALIZER for prefab instances', 'review a Prefab subclass to ensure it defines the required description class attribute', 'run a Concordia simulation with a premise string and max steps limit', 'add a game master entity to the simulation for world state management', 'add an entity to the simulation as a passive agent', 'get the list of game master entities from the simulation', 'get the list of all entities in the simulation']
```

Usage

```
{'build_context_component_subclass': 'build a python module that subclasses ContextComponent and overrides pre_act and post_act methods', 'build_acting_component_subclass': 'build a python module that subclasses ActingComponent and implements get_action_attempt to decide entity actions', 'review_phase_enum_successors': 'review the Phase enum successors property to understand valid lifecycle transitions between READY PRE_ACT and UPDATE', 'build_base_component_with_state': 'build a python module that subclasses BaseComponent and implements get_state and set_state for serialization', 'review_entitywithcomponents_abstraction': 'review the EntityWithComponents abstract class to understand get_component and phase management for entity composition'}
```

## File: google-deepmind_concordia/concordia/typing/prefab.py

Prompts

```
['create an ActionSpec dataclass instance with a call_to_action string and output type', 'validate an action string against an ActionSpec using the validate method', 'convert an ActionSpec instance to a JSON-serializable dictionary using to_dict', 'reconstruct an ActionSpec from a dictionary using action_spec_from_dict', 'implement a concrete Entity subclass with name, act, and observe methods', 'build a python module that subclasses ContextComponent and overrides pre_act and post_act methods', 'build a python module that subclasses ActingComponent and implements get_action_attempt to decide entity actions', 'review the Phase enum successors property to understand valid lifecycle transitions between READY PRE_ACT and UPDATE', 'build a python module that subclasses BaseComponent and implements get_state and set_state for serialization', 'review the EntityWithComponents abstract class to understand get_component and phase management for entity composition', 'build a prefab entity by subclassing Prefab and implementing the abstract build method', 'create an InstanceConfig dataclass with a prefab name, Role enum value, and params mapping', 'create a Config dataclass with prefabs mapping, instances sequence, default premise, and max steps', 'define a Role StrEnum value as ENTITY, GAME_MASTER, or INITIALIZER for prefab instances', 'review a Prefab subclass to ensure it defines the required description class attribute', 'run a Concordia simulation with a premise string and max steps limit', 'add a game master entity to the simulation for world state management', 'add an entity to the simulation as a passive agent', 'get the list of game master entities from the simulation', 'get the list of all entities in the simulation']
```

Usage

```
{'build_prefab_entity': 'build a prefab entity by subclassing Prefab and implementing the abstract build method', 'create_instance_config': 'create an InstanceConfig dataclass with a prefab name, Role enum value, and params mapping', 'create_config': 'create a Config dataclass with prefabs mapping, instances sequence, default premise, and max steps', 'define_role_enum': 'define a Role StrEnum value as ENTITY, GAME_MASTER, or INITIALIZER for prefab instances', 'review_prefab_subclass': 'review a Prefab subclass to ensure it defines the required description class attribute'}
```

## File: google-deepmind_concordia/concordia/typing/simulation.py

Prompts

```
['create an ActionSpec dataclass instance with a call_to_action string and output type', 'validate an action string against an ActionSpec using the validate method', 'convert an ActionSpec instance to a JSON-serializable dictionary using to_dict', 'reconstruct an ActionSpec from a dictionary using action_spec_from_dict', 'implement a concrete Entity subclass with name, act, and observe methods', 'build a python module that subclasses ContextComponent and overrides pre_act and post_act methods', 'build a python module that subclasses ActingComponent and implements get_action_attempt to decide entity actions', 'review the Phase enum successors property to understand valid lifecycle transitions between READY PRE_ACT and UPDATE', 'build a python module that subclasses BaseComponent and implements get_state and set_state for serialization', 'review the EntityWithComponents abstract class to understand get_component and phase management for entity composition', 'build a prefab entity by subclassing Prefab and implementing the abstract build method', 'create an InstanceConfig dataclass with a prefab name, Role enum value, and params mapping', 'create a Config dataclass with prefabs mapping, instances sequence, default premise, and max steps', 'define a Role StrEnum value as ENTITY, GAME_MASTER, or INITIALIZER for prefab instances', 'review a Prefab subclass to ensure it defines the required description class attribute', 'run a Concordia simulation with a premise string and max steps limit', 'add a game master entity to the simulation for world state management', 'add an entity to the simulation as a passive agent', 'get the list of game master entities from the simulation', 'get the list of all entities in the simulation']
```

Usage

```
{'run_simulation': 'run a Concordia simulation with a premise string and max steps limit', 'add_game_master': 'add a game master entity to the simulation for world state management', 'add_entity': 'add an entity to the simulation as a passive agent', 'get_game_masters': 'get the list of game master entities from the simulation', 'get_entities': 'get the list of all entities in the simulation'}
```

