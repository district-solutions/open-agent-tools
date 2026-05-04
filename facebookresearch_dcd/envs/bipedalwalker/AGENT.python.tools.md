# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/envs/bipedalwalker/adversarial.py

Prompts

```
['create a BipedalWalkerAdversarialEnv instance with full mode and a random seed for adversarial level generation', 'run step_adversary on a BipedalWalkerAdversarialEnv to mutate terrain parameters one step at a time', 'reset the adversarial environment to a specific level encoding with custom terrain parameters and seed', 'mutate the current level parameters by a specified number of edits using PARAM_MUTATIONS ranges', 'register BipedalWalker-Adversarial-v0 and related Gym environments with custom entry points and max episode steps', 'register a new MultiGrid environment with gym using a custom entry point and reward threshold', 'register a MultiGrid environment with gym specifying a custom max episode steps limit', 'register a MultiGrid environment with gym using the default reward threshold of 0.95', 'review the register function to understand how MultiGrid environments are added to the gym registry', 'summarize the env_list module variable that tracks registered MultiGrid environment IDs', 'create a BipedalWalkerCustom gym environment with an EnvConfig and optional seed for reproducibility', 'run a single step on the BipedalWalkerCustom environment by passing a 4-element action array', 'reset the BipedalWalkerCustom environment to its initial state and return the first observation', 'render the BipedalWalkerCustom environment in human or rgb_array mode using the render method', 'reinitialize the BipedalWalkerCustom environment with a new EnvConfig and seed without creating a new instance', 'create a BipedalWalkerDefault gym environment with default terrain configuration', 'create a BipedalWalkerInsane gym environment with all terrain obstacles maxed out', 'create a procedurally generated BipedalWalkerXChal environment with random obstacle parameters', 'create a BipedalWalkerPOETRose gym environment using a specific rose ID like 1a or 2b', 'create an EnvConfig with custom stump height, pit gap, stair, and roughness parameters']
```

Usage

```
{'create_adversarial_env': 'create a BipedalWalkerAdversarialEnv instance with full mode and a random seed for adversarial level generation', 'run_step_adversary': 'run step_adversary on a BipedalWalkerAdversarialEnv to mutate terrain parameters one step at a time', 'reset_to_level': 'reset the adversarial environment to a specific level encoding with custom terrain parameters and seed', 'mutate_level': 'mutate the current level parameters by a specified number of edits using PARAM_MUTATIONS ranges', 'register_gym_envs': 'register BipedalWalker-Adversarial-v0 and related Gym environments with custom entry points and max episode steps'}
```

## File: facebookresearch_dcd/envs/bipedalwalker/register.py

Prompts

```
['create a BipedalWalkerAdversarialEnv instance with full mode and a random seed for adversarial level generation', 'run step_adversary on a BipedalWalkerAdversarialEnv to mutate terrain parameters one step at a time', 'reset the adversarial environment to a specific level encoding with custom terrain parameters and seed', 'mutate the current level parameters by a specified number of edits using PARAM_MUTATIONS ranges', 'register BipedalWalker-Adversarial-v0 and related Gym environments with custom entry points and max episode steps', 'register a new MultiGrid environment with gym using a custom entry point and reward threshold', 'register a MultiGrid environment with gym specifying a custom max episode steps limit', 'register a MultiGrid environment with gym using the default reward threshold of 0.95', 'review the register function to understand how MultiGrid environments are added to the gym registry', 'summarize the env_list module variable that tracks registered MultiGrid environment IDs', 'create a BipedalWalkerCustom gym environment with an EnvConfig and optional seed for reproducibility', 'run a single step on the BipedalWalkerCustom environment by passing a 4-element action array', 'reset the BipedalWalkerCustom environment to its initial state and return the first observation', 'render the BipedalWalkerCustom environment in human or rgb_array mode using the render method', 'reinitialize the BipedalWalkerCustom environment with a new EnvConfig and seed without creating a new instance', 'create a BipedalWalkerDefault gym environment with default terrain configuration', 'create a BipedalWalkerInsane gym environment with all terrain obstacles maxed out', 'create a procedurally generated BipedalWalkerXChal environment with random obstacle parameters', 'create a BipedalWalkerPOETRose gym environment using a specific rose ID like 1a or 2b', 'create an EnvConfig with custom stump height, pit gap, stair, and roughness parameters']
```

Usage

```
{'register_multigrid_env': 'register a new MultiGrid environment with gym using a custom entry point and reward threshold', 'register_env_with_max_steps': 'register a MultiGrid environment with gym specifying a custom max episode steps limit', 'register_env_default_threshold': 'register a MultiGrid environment with gym using the default reward threshold of 0.95', 'review_register_function': 'review the register function to understand how MultiGrid environments are added to the gym registry', 'summarize_env_list': 'summarize the env_list module variable that tracks registered MultiGrid environment IDs'}
```

## File: facebookresearch_dcd/envs/bipedalwalker/walker_env.py

Prompts

```
['create a BipedalWalkerAdversarialEnv instance with full mode and a random seed for adversarial level generation', 'run step_adversary on a BipedalWalkerAdversarialEnv to mutate terrain parameters one step at a time', 'reset the adversarial environment to a specific level encoding with custom terrain parameters and seed', 'mutate the current level parameters by a specified number of edits using PARAM_MUTATIONS ranges', 'register BipedalWalker-Adversarial-v0 and related Gym environments with custom entry points and max episode steps', 'register a new MultiGrid environment with gym using a custom entry point and reward threshold', 'register a MultiGrid environment with gym specifying a custom max episode steps limit', 'register a MultiGrid environment with gym using the default reward threshold of 0.95', 'review the register function to understand how MultiGrid environments are added to the gym registry', 'summarize the env_list module variable that tracks registered MultiGrid environment IDs', 'create a BipedalWalkerCustom gym environment with an EnvConfig and optional seed for reproducibility', 'run a single step on the BipedalWalkerCustom environment by passing a 4-element action array', 'reset the BipedalWalkerCustom environment to its initial state and return the first observation', 'render the BipedalWalkerCustom environment in human or rgb_array mode using the render method', 'reinitialize the BipedalWalkerCustom environment with a new EnvConfig and seed without creating a new instance', 'create a BipedalWalkerDefault gym environment with default terrain configuration', 'create a BipedalWalkerInsane gym environment with all terrain obstacles maxed out', 'create a procedurally generated BipedalWalkerXChal environment with random obstacle parameters', 'create a BipedalWalkerPOETRose gym environment using a specific rose ID like 1a or 2b', 'create an EnvConfig with custom stump height, pit gap, stair, and roughness parameters']
```

Usage

```
{'create_BipedalWalkerCustom_env': 'create a BipedalWalkerCustom gym environment with an EnvConfig and optional seed for reproducibility', 'run_step_BipedalWalkerCustom': 'run a single step on the BipedalWalkerCustom environment by passing a 4-element action array', 'reset_BipedalWalkerCustom': 'reset the BipedalWalkerCustom environment to its initial state and return the first observation', 'render_BipedalWalkerCustom': 'render the BipedalWalkerCustom environment in human or rgb_array mode using the render method', 're_init_BipedalWalkerCustom': 'reinitialize the BipedalWalkerCustom environment with a new EnvConfig and seed without creating a new instance'}
```

## File: facebookresearch_dcd/envs/bipedalwalker/walker_test_envs.py

Prompts

```
['create a BipedalWalkerAdversarialEnv instance with full mode and a random seed for adversarial level generation', 'run step_adversary on a BipedalWalkerAdversarialEnv to mutate terrain parameters one step at a time', 'reset the adversarial environment to a specific level encoding with custom terrain parameters and seed', 'mutate the current level parameters by a specified number of edits using PARAM_MUTATIONS ranges', 'register BipedalWalker-Adversarial-v0 and related Gym environments with custom entry points and max episode steps', 'register a new MultiGrid environment with gym using a custom entry point and reward threshold', 'register a MultiGrid environment with gym specifying a custom max episode steps limit', 'register a MultiGrid environment with gym using the default reward threshold of 0.95', 'review the register function to understand how MultiGrid environments are added to the gym registry', 'summarize the env_list module variable that tracks registered MultiGrid environment IDs', 'create a BipedalWalkerCustom gym environment with an EnvConfig and optional seed for reproducibility', 'run a single step on the BipedalWalkerCustom environment by passing a 4-element action array', 'reset the BipedalWalkerCustom environment to its initial state and return the first observation', 'render the BipedalWalkerCustom environment in human or rgb_array mode using the render method', 'reinitialize the BipedalWalkerCustom environment with a new EnvConfig and seed without creating a new instance', 'create a BipedalWalkerDefault gym environment with default terrain configuration', 'create a BipedalWalkerInsane gym environment with all terrain obstacles maxed out', 'create a procedurally generated BipedalWalkerXChal environment with random obstacle parameters', 'create a BipedalWalkerPOETRose gym environment using a specific rose ID like 1a or 2b', 'create an EnvConfig with custom stump height, pit gap, stair, and roughness parameters']
```

Usage

```
{'create_bipedalwalker_default_env': 'create a BipedalWalkerDefault gym environment with default terrain configuration', 'create_bipedalwalker_insane_env': 'create a BipedalWalkerInsane gym environment with all terrain obstacles maxed out', 'create_bipedalwalker_xchal_env': 'create a procedurally generated BipedalWalkerXChal environment with random obstacle parameters', 'create_bipedalwalker_poet_rose_env': 'create a BipedalWalkerPOETRose gym environment using a specific rose ID like 1a or 2b', 'create_bipedalwalker_config': 'create an EnvConfig with custom stump height, pit gap, stair, and roughness parameters'}
```

