# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/prefabs/game_master/dial_dyad_initializer.py

Prompts

```
['build a game master prefab that generates formative childhood memories for all entities in a Concordia simulation', 'build an EntityAgentWithLogging game master using a language model and associative memory bank with player characters', 'configure a DayInTheLifeInitializer component with player names, specific memories, and a scenario type for formative memory generation', 'create a game master prefab with player characters, shared memories, and player-specific context parameters', 'assemble game master components including instructions, observations, memory, and action spec into a single entity agent', 'build the components dictionary for a PersonaInitializer game master with a given generator and player names', 'build a game master entity from components using a SwitchAct component and player names', 'build a PersonaInitializer prefab game master entity from a model and memory bank after setting a generator', 'review the GameMaster prefab class that wires a PersonaGenerator with standard Concordia game master infrastructure', 'refactor the build_components function to add additional context components for a PersonaInitializer game master', 'build a game master entity with simultaneous event resolution using GameMasterSimultaneous prefab', 'build a FixedIncrementClock component that advances simulation time by fixed minute increments', 'build a SimultaneousNarrativeEventResolution component to resolve all player actions simultaneously', 'build an NPC event generator component that creates random events with configurable probability', 'build a location-based partial observability filter to restrict entity observations by location', 'build a GameMaster prefab entity for a spaceship simulation game using a language model and memory bank', 'configure oxygen and power generator spaceship systems with failure probabilities and warning messages', 'set the acting order for players to game master choice, fixed, or random', 'add extra components to the game master with custom insertion indices in the component order', 'customize event resolution steps by providing comma-separated thought chain step names']
```

Usage

```
{'build_game_master_prefab': 'build a game master prefab that generates formative childhood memories for all entities in a Concordia simulation', 'build_game_master_entity': 'build an EntityAgentWithLogging game master using a language model and associative memory bank with player characters', 'configure_day_in_life_initializer': 'configure a DayInTheLifeInitializer component with player names, specific memories, and a scenario type for formative memory generation', 'create_game_master_with_player_characters': 'create a game master prefab with player characters, shared memories, and player-specific context parameters', 'assemble_game_master_components': 'assemble game master components including instructions, observations, memory, and action spec into a single entity agent'}
```

## File: google-deepmind_concordia/concordia/contrib/prefabs/game_master/persona_initializer.py

Prompts

```
['build a game master prefab that generates formative childhood memories for all entities in a Concordia simulation', 'build an EntityAgentWithLogging game master using a language model and associative memory bank with player characters', 'configure a DayInTheLifeInitializer component with player names, specific memories, and a scenario type for formative memory generation', 'create a game master prefab with player characters, shared memories, and player-specific context parameters', 'assemble game master components including instructions, observations, memory, and action spec into a single entity agent', 'build the components dictionary for a PersonaInitializer game master with a given generator and player names', 'build a game master entity from components using a SwitchAct component and player names', 'build a PersonaInitializer prefab game master entity from a model and memory bank after setting a generator', 'review the GameMaster prefab class that wires a PersonaGenerator with standard Concordia game master infrastructure', 'refactor the build_components function to add additional context components for a PersonaInitializer game master', 'build a game master entity with simultaneous event resolution using GameMasterSimultaneous prefab', 'build a FixedIncrementClock component that advances simulation time by fixed minute increments', 'build a SimultaneousNarrativeEventResolution component to resolve all player actions simultaneously', 'build an NPC event generator component that creates random events with configurable probability', 'build a location-based partial observability filter to restrict entity observations by location', 'build a GameMaster prefab entity for a spaceship simulation game using a language model and memory bank', 'configure oxygen and power generator spaceship systems with failure probabilities and warning messages', 'set the acting order for players to game master choice, fixed, or random', 'add extra components to the game master with custom insertion indices in the component order', 'customize event resolution steps by providing comma-separated thought chain step names']
```

Usage

```
{'build_persona_initializer_components': 'build the components dictionary for a PersonaInitializer game master with a given generator and player names', 'build_persona_game_master_entity': 'build a game master entity from components using a SwitchAct component and player names', 'build_persona_prefab': 'build a PersonaInitializer prefab game master entity from a model and memory bank after setting a generator', 'review_persona_initializer_prefab': 'review the GameMaster prefab class that wires a PersonaGenerator with standard Concordia game master infrastructure', 'refactor_persona_components': 'refactor the build_components function to add additional context components for a PersonaInitializer game master'}
```

## File: google-deepmind_concordia/concordia/contrib/prefabs/game_master/simultaneous_resolution_gm.py

Prompts

```
['build a game master prefab that generates formative childhood memories for all entities in a Concordia simulation', 'build an EntityAgentWithLogging game master using a language model and associative memory bank with player characters', 'configure a DayInTheLifeInitializer component with player names, specific memories, and a scenario type for formative memory generation', 'create a game master prefab with player characters, shared memories, and player-specific context parameters', 'assemble game master components including instructions, observations, memory, and action spec into a single entity agent', 'build the components dictionary for a PersonaInitializer game master with a given generator and player names', 'build a game master entity from components using a SwitchAct component and player names', 'build a PersonaInitializer prefab game master entity from a model and memory bank after setting a generator', 'review the GameMaster prefab class that wires a PersonaGenerator with standard Concordia game master infrastructure', 'refactor the build_components function to add additional context components for a PersonaInitializer game master', 'build a game master entity with simultaneous event resolution using GameMasterSimultaneous prefab', 'build a FixedIncrementClock component that advances simulation time by fixed minute increments', 'build a SimultaneousNarrativeEventResolution component to resolve all player actions simultaneously', 'build an NPC event generator component that creates random events with configurable probability', 'build a location-based partial observability filter to restrict entity observations by location', 'build a GameMaster prefab entity for a spaceship simulation game using a language model and memory bank', 'configure oxygen and power generator spaceship systems with failure probabilities and warning messages', 'set the acting order for players to game master choice, fixed, or random', 'add extra components to the game master with custom insertion indices in the component order', 'customize event resolution steps by providing comma-separated thought chain step names']
```

Usage

```
{'build_game_master_simultaneous': 'build a game master entity with simultaneous event resolution using GameMasterSimultaneous prefab', 'build_fixed_increment_clock': 'build a FixedIncrementClock component that advances simulation time by fixed minute increments', 'build_simultaneous_narrative_resolution': 'build a SimultaneousNarrativeEventResolution component to resolve all player actions simultaneously', 'build_npc_event_generator': 'build an NPC event generator component that creates random events with configurable probability', 'build_location_based_filter': 'build a location-based partial observability filter to restrict entity observations by location'}
```

## File: google-deepmind_concordia/concordia/contrib/prefabs/game_master/space_ship.py

Prompts

```
['build a game master prefab that generates formative childhood memories for all entities in a Concordia simulation', 'build an EntityAgentWithLogging game master using a language model and associative memory bank with player characters', 'configure a DayInTheLifeInitializer component with player names, specific memories, and a scenario type for formative memory generation', 'create a game master prefab with player characters, shared memories, and player-specific context parameters', 'assemble game master components including instructions, observations, memory, and action spec into a single entity agent', 'build the components dictionary for a PersonaInitializer game master with a given generator and player names', 'build a game master entity from components using a SwitchAct component and player names', 'build a PersonaInitializer prefab game master entity from a model and memory bank after setting a generator', 'review the GameMaster prefab class that wires a PersonaGenerator with standard Concordia game master infrastructure', 'refactor the build_components function to add additional context components for a PersonaInitializer game master', 'build a game master entity with simultaneous event resolution using GameMasterSimultaneous prefab', 'build a FixedIncrementClock component that advances simulation time by fixed minute increments', 'build a SimultaneousNarrativeEventResolution component to resolve all player actions simultaneously', 'build an NPC event generator component that creates random events with configurable probability', 'build a location-based partial observability filter to restrict entity observations by location', 'build a GameMaster prefab entity for a spaceship simulation game using a language model and memory bank', 'configure oxygen and power generator spaceship systems with failure probabilities and warning messages', 'set the acting order for players to game master choice, fixed, or random', 'add extra components to the game master with custom insertion indices in the component order', 'customize event resolution steps by providing comma-separated thought chain step names']
```

Usage

```
{'build_game_master': 'build a GameMaster prefab entity for a spaceship simulation game using a language model and memory bank', 'configure_spaceship_systems': 'configure oxygen and power generator spaceship systems with failure probabilities and warning messages', 'set_acting_order': 'set the acting order for players to game master choice, fixed, or random', 'add_extra_components': 'add extra components to the game master with custom insertion indices in the component order', 'customize_event_resolution': 'customize event resolution steps by providing comma-separated thought chain step names'}
```

