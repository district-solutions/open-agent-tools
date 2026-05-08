# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/envs/pomdp/pocman.py

Prompts

```
['create a PocManEnv instance to run the micro maze POMDP environment with gym API', 'run a single step in the PocManEnv by calling step with an action integer 0-3', 'reset the PocManEnv to initial state and get the first observation vector', 'create a Ghost instance with position, direction, and ghost_range for maze navigation', 'compute the Euclidean distance between two Position objects using manhattan_distance function', 'create a StateEmbedEnvironment wrapping a gym env with a MemoryNetwork for POMDP state embedding', 'run embed_state on the current raw state to produce a hidden-layer concatenated embedding vector', 'test the StateEmbedEnvironment reset method to clear history and return an embedded initial state', 'test the StateEmbedEnvironment step method to take an action and return an embedded next state with reward', 'review the StateEmbedEnvironment class for POMDP state embedding using a MemoryNetwork world model', 'create a StringGameEnv instance to run a POMDP string game with A and B characters', 'run a step on the StringGameEnv by passing an action and receiving observation and reward', 'reset the StringGameEnv to clear recent actions and states for a new episode', 'get the reward based on the last 3 actions using the get_reward method', 'print the internal state showing recent states and actions as character strings', 'create a StringGameEnvV1 gym environment with stochastic termination and string-based rewards', 'run a step on the StringGameEnvV1 environment by passing an action and getting observation and reward', 'test the StringGameEnvV1 reset method to verify it clears actions and returns initial observation', 'review the StringGameEnvV1 get_reward method that maps action history strings to reward values', 'summarize the StringGameEnvV1 sample_terminal method that probabilistically decides episode termination per action']
```

Usage

```
{'create_pocman_env': 'create a PocManEnv instance to run the micro maze POMDP environment with gym API', 'run_pocman_step': 'run a single step in the PocManEnv by calling step with an action integer 0-3', 'reset_pocman_env': 'reset the PocManEnv to initial state and get the first observation vector', 'create_ghost_agent': 'create a Ghost instance with position, direction, and ghost_range for maze navigation', 'compute_manhattan_distance': 'compute the Euclidean distance between two Position objects using manhattan_distance function'}
```

## File: facebookresearch_reagent/reagent/gym/envs/pomdp/state_embed_env.py

Prompts

```
['create a PocManEnv instance to run the micro maze POMDP environment with gym API', 'run a single step in the PocManEnv by calling step with an action integer 0-3', 'reset the PocManEnv to initial state and get the first observation vector', 'create a Ghost instance with position, direction, and ghost_range for maze navigation', 'compute the Euclidean distance between two Position objects using manhattan_distance function', 'create a StateEmbedEnvironment wrapping a gym env with a MemoryNetwork for POMDP state embedding', 'run embed_state on the current raw state to produce a hidden-layer concatenated embedding vector', 'test the StateEmbedEnvironment reset method to clear history and return an embedded initial state', 'test the StateEmbedEnvironment step method to take an action and return an embedded next state with reward', 'review the StateEmbedEnvironment class for POMDP state embedding using a MemoryNetwork world model', 'create a StringGameEnv instance to run a POMDP string game with A and B characters', 'run a step on the StringGameEnv by passing an action and receiving observation and reward', 'reset the StringGameEnv to clear recent actions and states for a new episode', 'get the reward based on the last 3 actions using the get_reward method', 'print the internal state showing recent states and actions as character strings', 'create a StringGameEnvV1 gym environment with stochastic termination and string-based rewards', 'run a step on the StringGameEnvV1 environment by passing an action and getting observation and reward', 'test the StringGameEnvV1 reset method to verify it clears actions and returns initial observation', 'review the StringGameEnvV1 get_reward method that maps action history strings to reward values', 'summarize the StringGameEnvV1 sample_terminal method that probabilistically decides episode termination per action']
```

Usage

```
{'create_StateEmbedEnvironment': 'create a StateEmbedEnvironment wrapping a gym env with a MemoryNetwork for POMDP state embedding', 'run_embed_state': 'run embed_state on the current raw state to produce a hidden-layer concatenated embedding vector', 'test_reset': 'test the StateEmbedEnvironment reset method to clear history and return an embedded initial state', 'test_step': 'test the StateEmbedEnvironment step method to take an action and return an embedded next state with reward', 'review_StateEmbedEnvironment': 'review the StateEmbedEnvironment class for POMDP state embedding using a MemoryNetwork world model'}
```

## File: facebookresearch_reagent/reagent/gym/envs/pomdp/string_game.py

Prompts

```
['create a PocManEnv instance to run the micro maze POMDP environment with gym API', 'run a single step in the PocManEnv by calling step with an action integer 0-3', 'reset the PocManEnv to initial state and get the first observation vector', 'create a Ghost instance with position, direction, and ghost_range for maze navigation', 'compute the Euclidean distance between two Position objects using manhattan_distance function', 'create a StateEmbedEnvironment wrapping a gym env with a MemoryNetwork for POMDP state embedding', 'run embed_state on the current raw state to produce a hidden-layer concatenated embedding vector', 'test the StateEmbedEnvironment reset method to clear history and return an embedded initial state', 'test the StateEmbedEnvironment step method to take an action and return an embedded next state with reward', 'review the StateEmbedEnvironment class for POMDP state embedding using a MemoryNetwork world model', 'create a StringGameEnv instance to run a POMDP string game with A and B characters', 'run a step on the StringGameEnv by passing an action and receiving observation and reward', 'reset the StringGameEnv to clear recent actions and states for a new episode', 'get the reward based on the last 3 actions using the get_reward method', 'print the internal state showing recent states and actions as character strings', 'create a StringGameEnvV1 gym environment with stochastic termination and string-based rewards', 'run a step on the StringGameEnvV1 environment by passing an action and getting observation and reward', 'test the StringGameEnvV1 reset method to verify it clears actions and returns initial observation', 'review the StringGameEnvV1 get_reward method that maps action history strings to reward values', 'summarize the StringGameEnvV1 sample_terminal method that probabilistically decides episode termination per action']
```

Usage

```
{'create_string_game_env': 'create a StringGameEnv instance to run a POMDP string game with A and B characters', 'run_step_with_action': 'run a step on the StringGameEnv by passing an action and receiving observation and reward', 'reset_string_game_env': 'reset the StringGameEnv to clear recent actions and states for a new episode', 'get_reward_from_history': 'get the reward based on the last 3 actions using the get_reward method', 'print_internal_state': 'print the internal state showing recent states and actions as character strings'}
```

## File: facebookresearch_reagent/reagent/gym/envs/pomdp/string_game_v1.py

Prompts

```
['create a PocManEnv instance to run the micro maze POMDP environment with gym API', 'run a single step in the PocManEnv by calling step with an action integer 0-3', 'reset the PocManEnv to initial state and get the first observation vector', 'create a Ghost instance with position, direction, and ghost_range for maze navigation', 'compute the Euclidean distance between two Position objects using manhattan_distance function', 'create a StateEmbedEnvironment wrapping a gym env with a MemoryNetwork for POMDP state embedding', 'run embed_state on the current raw state to produce a hidden-layer concatenated embedding vector', 'test the StateEmbedEnvironment reset method to clear history and return an embedded initial state', 'test the StateEmbedEnvironment step method to take an action and return an embedded next state with reward', 'review the StateEmbedEnvironment class for POMDP state embedding using a MemoryNetwork world model', 'create a StringGameEnv instance to run a POMDP string game with A and B characters', 'run a step on the StringGameEnv by passing an action and receiving observation and reward', 'reset the StringGameEnv to clear recent actions and states for a new episode', 'get the reward based on the last 3 actions using the get_reward method', 'print the internal state showing recent states and actions as character strings', 'create a StringGameEnvV1 gym environment with stochastic termination and string-based rewards', 'run a step on the StringGameEnvV1 environment by passing an action and getting observation and reward', 'test the StringGameEnvV1 reset method to verify it clears actions and returns initial observation', 'review the StringGameEnvV1 get_reward method that maps action history strings to reward values', 'summarize the StringGameEnvV1 sample_terminal method that probabilistically decides episode termination per action']
```

Usage

```
{'create_StringGameEnvV1': 'create a StringGameEnvV1 gym environment with stochastic termination and string-based rewards', 'run_step_StringGameEnvV1': 'run a step on the StringGameEnvV1 environment by passing an action and getting observation and reward', 'test_reset_StringGameEnvV1': 'test the StringGameEnvV1 reset method to verify it clears actions and returns initial observation', 'review_get_reward_StringGameEnvV1': 'review the StringGameEnvV1 get_reward method that maps action history strings to reward values', 'summarize_sample_terminal_StringGameEnvV1': 'summarize the StringGameEnvV1 sample_terminal method that probabilistically decides episode termination per action'}
```

