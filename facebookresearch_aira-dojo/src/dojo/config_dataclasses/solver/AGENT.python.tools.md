# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/solver/base.py

Prompts

```
['configure the SolverConfig dataclass to set a custom step limit for the search process', 'configure the SolverConfig dataclass to specify available packages like numpy and pandas for the solver', 'configure the SolverConfig dataclass to define operator configurations for the solver', 'configure the SolverConfig dataclass to set memory and debug memory settings for the solver', 'validate the SolverConfig dataclass instance by calling its validate method to check configuration', 'create an EvolutionarySolverConfig dataclass instance with island and generation hyperparameters', 'configure the number of islands and max island size for the evolutionary solver', 'set the crossover probability and migration probability for island evolution', 'set the initial and final temperature values for exploration to exploitation shift', 'validate an EvolutionarySolverConfig instance by calling its validate method', 'create a GreedySolverConfig instance with default improvement steps, debug settings, and draft count', 'configure the GreedySolverConfig to set the number of improvement iterations for the search process', 'configure the GreedySolverConfig to enable or disable data preview before agent execution', 'configure the GreedySolverConfig max debug depth and debug probability for debugging analysis', 'validate a GreedySolverConfig instance to ensure all configuration fields are correct', 'configure an MCTS solver with num_children, uct_c, max_debug_depth, max_debug_time, and data_preview settings', 'review the MCTSSolverConfig dataclass to understand MCTS search and agent configuration options', 'validate an MCTSSolverConfig instance by calling its validate method to check required fields', 'set the UCT exploration constant uct_c on an MCTSSolverConfig to balance exploration and exploitation']
```

Usage

```
{'configure_solver_step_limit': 'configure the SolverConfig dataclass to set a custom step limit for the search process', 'configure_solver_available_packages': 'configure the SolverConfig dataclass to specify available packages like numpy and pandas for the solver', 'configure_solver_operators': 'configure the SolverConfig dataclass to define operator configurations for the solver', 'configure_solver_memory': 'configure the SolverConfig dataclass to set memory and debug memory settings for the solver', 'validate_solver_config': 'validate the SolverConfig dataclass instance by calling its validate method to check configuration'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/solver/evo.py

Prompts

```
['configure the SolverConfig dataclass to set a custom step limit for the search process', 'configure the SolverConfig dataclass to specify available packages like numpy and pandas for the solver', 'configure the SolverConfig dataclass to define operator configurations for the solver', 'configure the SolverConfig dataclass to set memory and debug memory settings for the solver', 'validate the SolverConfig dataclass instance by calling its validate method to check configuration', 'create an EvolutionarySolverConfig dataclass instance with island and generation hyperparameters', 'configure the number of islands and max island size for the evolutionary solver', 'set the crossover probability and migration probability for island evolution', 'set the initial and final temperature values for exploration to exploitation shift', 'validate an EvolutionarySolverConfig instance by calling its validate method', 'create a GreedySolverConfig instance with default improvement steps, debug settings, and draft count', 'configure the GreedySolverConfig to set the number of improvement iterations for the search process', 'configure the GreedySolverConfig to enable or disable data preview before agent execution', 'configure the GreedySolverConfig max debug depth and debug probability for debugging analysis', 'validate a GreedySolverConfig instance to ensure all configuration fields are correct', 'configure an MCTS solver with num_children, uct_c, max_debug_depth, max_debug_time, and data_preview settings', 'review the MCTSSolverConfig dataclass to understand MCTS search and agent configuration options', 'validate an MCTSSolverConfig instance by calling its validate method to check required fields', 'set the UCT exploration constant uct_c on an MCTSSolverConfig to balance exploration and exploitation']
```

Usage

```
{'create_EvolutionarySolverConfig': 'create an EvolutionarySolverConfig dataclass instance with island and generation hyperparameters', 'configure_island_evolution': 'configure the number of islands and max island size for the evolutionary solver', 'set_crossover_migration_probs': 'set the crossover probability and migration probability for island evolution', 'configure_temperature_schedule': 'set the initial and final temperature values for exploration to exploitation shift', 'validate_EvolutionarySolverConfig': 'validate an EvolutionarySolverConfig instance by calling its validate method'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/solver/greedy.py

Prompts

```
['configure the SolverConfig dataclass to set a custom step limit for the search process', 'configure the SolverConfig dataclass to specify available packages like numpy and pandas for the solver', 'configure the SolverConfig dataclass to define operator configurations for the solver', 'configure the SolverConfig dataclass to set memory and debug memory settings for the solver', 'validate the SolverConfig dataclass instance by calling its validate method to check configuration', 'create an EvolutionarySolverConfig dataclass instance with island and generation hyperparameters', 'configure the number of islands and max island size for the evolutionary solver', 'set the crossover probability and migration probability for island evolution', 'set the initial and final temperature values for exploration to exploitation shift', 'validate an EvolutionarySolverConfig instance by calling its validate method', 'create a GreedySolverConfig instance with default improvement steps, debug settings, and draft count', 'configure the GreedySolverConfig to set the number of improvement iterations for the search process', 'configure the GreedySolverConfig to enable or disable data preview before agent execution', 'configure the GreedySolverConfig max debug depth and debug probability for debugging analysis', 'validate a GreedySolverConfig instance to ensure all configuration fields are correct', 'configure an MCTS solver with num_children, uct_c, max_debug_depth, max_debug_time, and data_preview settings', 'review the MCTSSolverConfig dataclass to understand MCTS search and agent configuration options', 'validate an MCTSSolverConfig instance by calling its validate method to check required fields', 'set the UCT exploration constant uct_c on an MCTSSolverConfig to balance exploration and exploitation']
```

Usage

```
{'create_GreedySolverConfig': 'create a GreedySolverConfig instance with default improvement steps, debug settings, and draft count', 'configure_improvement_steps': 'configure the GreedySolverConfig to set the number of improvement iterations for the search process', 'configure_data_preview': 'configure the GreedySolverConfig to enable or disable data preview before agent execution', 'configure_debug_settings': 'configure the GreedySolverConfig max debug depth and debug probability for debugging analysis', 'validate_GreedySolverConfig': 'validate a GreedySolverConfig instance to ensure all configuration fields are correct'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/solver/mcts.py

Prompts

```
['configure the SolverConfig dataclass to set a custom step limit for the search process', 'configure the SolverConfig dataclass to specify available packages like numpy and pandas for the solver', 'configure the SolverConfig dataclass to define operator configurations for the solver', 'configure the SolverConfig dataclass to set memory and debug memory settings for the solver', 'validate the SolverConfig dataclass instance by calling its validate method to check configuration', 'create an EvolutionarySolverConfig dataclass instance with island and generation hyperparameters', 'configure the number of islands and max island size for the evolutionary solver', 'set the crossover probability and migration probability for island evolution', 'set the initial and final temperature values for exploration to exploitation shift', 'validate an EvolutionarySolverConfig instance by calling its validate method', 'create a GreedySolverConfig instance with default improvement steps, debug settings, and draft count', 'configure the GreedySolverConfig to set the number of improvement iterations for the search process', 'configure the GreedySolverConfig to enable or disable data preview before agent execution', 'configure the GreedySolverConfig max debug depth and debug probability for debugging analysis', 'validate a GreedySolverConfig instance to ensure all configuration fields are correct', 'configure an MCTS solver with num_children, uct_c, max_debug_depth, max_debug_time, and data_preview settings', 'review the MCTSSolverConfig dataclass to understand MCTS search and agent configuration options', 'validate an MCTSSolverConfig instance by calling its validate method to check required fields', 'set the UCT exploration constant uct_c on an MCTSSolverConfig to balance exploration and exploitation']
```

Usage

```
{'configure_MCTSSolverConfig': 'configure an MCTS solver with num_children, uct_c, max_debug_depth, max_debug_time, and data_preview settings', 'review_MCTSSolverConfig': 'review the MCTSSolverConfig dataclass to understand MCTS search and agent configuration options', 'validate_MCTSSolverConfig': 'validate an MCTSSolverConfig instance by calling its validate method to check required fields', 'set_uct_exploration': 'set the UCT exploration constant uct_c on an MCTSSolverConfig to balance exploration and exploitation', 'configure_data_preview': 'configure the data_preview flag on MCTSSolverConfig to provide agents with data before execution'}
```

