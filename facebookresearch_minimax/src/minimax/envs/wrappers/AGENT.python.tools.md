# Agent Python Tools

- repo: facebookresearch/minimax
- repo_uri: https://github.com/facebookresearch/minimax

## File: facebookresearch_minimax/src/minimax/envs/wrappers/env_wrapper.py

Prompts

```
['create a subclass of EnvWrapper that overrides reset_extra to inject custom metadata into environment tuples', 'step the wrapped environment forward by calling step with a PRNG key, state, and action', 'reset the wrapped environment to its initial state using reset with a PRNG key', 'set the environment state directly by calling set_state with an EnvState instance', 'access the unwrapped base environment through the base_env property of an EnvWrapper instance', 'build a python module to wrap an environment with MonitorEpisodicMetricsWrapper to track episodic metrics', 'test the MonitorEpisodicMetricsWrapper is_compatible method to check if an environment supports get_episodic_metrics', 'review the MonitorEpisodicMetricsWrapper step method that prefixes episodic metric keys with ep/ in info dict', 'create a function call to get_monitored_metrics that returns episodic metric names prefixed with ep/', 'refactor the MonitorEpisodicMetricsWrapper init to initialize metrics by calling get_episodic_metrics on the base environment', 'build a python module that wraps an environment with MonitorReturnWrapper to track episodic returns', 'create a function that initializes episodic return tracking by resetting ep_return to zero', 'test the MonitorReturnWrapper step method to verify it correctly accumulates rewards and resets on episode end', 'review the MonitorReturnWrapper get_monitored_metrics method to confirm it adds return to tracked metrics', 'refactor the MonitorReturnWrapper step method to handle variable-length step returns and track cumulative rewards', 'create a UEDEnvWrapper instance that wraps an existing environment and tracks nesting depth', 'reset the teacher environment using a JAX PRNG key and append extra state data', 'step the teacher environment with an action and optional extra dictionary data', 'check if an environment is compatible with the UEDEnvWrapper using the is_compatible class method']
```

Usage

```
{'create_env_wrapper_subclass': 'create a subclass of EnvWrapper that overrides reset_extra to inject custom metadata into environment tuples', 'step_env_wrapper': 'step the wrapped environment forward by calling step with a PRNG key, state, and action', 'reset_env_wrapper': 'reset the wrapped environment to its initial state using reset with a PRNG key', 'set_state_env_wrapper': 'set the environment state directly by calling set_state with an EnvState instance', 'get_base_env': 'access the unwrapped base environment through the base_env property of an EnvWrapper instance'}
```

## File: facebookresearch_minimax/src/minimax/envs/wrappers/monitor_ep_metrics.py

Prompts

```
['create a subclass of EnvWrapper that overrides reset_extra to inject custom metadata into environment tuples', 'step the wrapped environment forward by calling step with a PRNG key, state, and action', 'reset the wrapped environment to its initial state using reset with a PRNG key', 'set the environment state directly by calling set_state with an EnvState instance', 'access the unwrapped base environment through the base_env property of an EnvWrapper instance', 'build a python module to wrap an environment with MonitorEpisodicMetricsWrapper to track episodic metrics', 'test the MonitorEpisodicMetricsWrapper is_compatible method to check if an environment supports get_episodic_metrics', 'review the MonitorEpisodicMetricsWrapper step method that prefixes episodic metric keys with ep/ in info dict', 'create a function call to get_monitored_metrics that returns episodic metric names prefixed with ep/', 'refactor the MonitorEpisodicMetricsWrapper init to initialize metrics by calling get_episodic_metrics on the base environment', 'build a python module that wraps an environment with MonitorReturnWrapper to track episodic returns', 'create a function that initializes episodic return tracking by resetting ep_return to zero', 'test the MonitorReturnWrapper step method to verify it correctly accumulates rewards and resets on episode end', 'review the MonitorReturnWrapper get_monitored_metrics method to confirm it adds return to tracked metrics', 'refactor the MonitorReturnWrapper step method to handle variable-length step returns and track cumulative rewards', 'create a UEDEnvWrapper instance that wraps an existing environment and tracks nesting depth', 'reset the teacher environment using a JAX PRNG key and append extra state data', 'step the teacher environment with an action and optional extra dictionary data', 'check if an environment is compatible with the UEDEnvWrapper using the is_compatible class method']
```

Usage

```
{'build_episodic_metrics_wrapper': 'build a python module to wrap an environment with MonitorEpisodicMetricsWrapper to track episodic metrics', 'test_is_compatible': 'test the MonitorEpisodicMetricsWrapper is_compatible method to check if an environment supports get_episodic_metrics', 'review_step_method': 'review the MonitorEpisodicMetricsWrapper step method that prefixes episodic metric keys with ep/ in info dict', 'create_monitored_metrics': 'create a function call to get_monitored_metrics that returns episodic metric names prefixed with ep/', 'refactor_metrics_initialization': 'refactor the MonitorEpisodicMetricsWrapper init to initialize metrics by calling get_episodic_metrics on the base environment'}
```

## File: facebookresearch_minimax/src/minimax/envs/wrappers/monitor_return.py

Prompts

```
['create a subclass of EnvWrapper that overrides reset_extra to inject custom metadata into environment tuples', 'step the wrapped environment forward by calling step with a PRNG key, state, and action', 'reset the wrapped environment to its initial state using reset with a PRNG key', 'set the environment state directly by calling set_state with an EnvState instance', 'access the unwrapped base environment through the base_env property of an EnvWrapper instance', 'build a python module to wrap an environment with MonitorEpisodicMetricsWrapper to track episodic metrics', 'test the MonitorEpisodicMetricsWrapper is_compatible method to check if an environment supports get_episodic_metrics', 'review the MonitorEpisodicMetricsWrapper step method that prefixes episodic metric keys with ep/ in info dict', 'create a function call to get_monitored_metrics that returns episodic metric names prefixed with ep/', 'refactor the MonitorEpisodicMetricsWrapper init to initialize metrics by calling get_episodic_metrics on the base environment', 'build a python module that wraps an environment with MonitorReturnWrapper to track episodic returns', 'create a function that initializes episodic return tracking by resetting ep_return to zero', 'test the MonitorReturnWrapper step method to verify it correctly accumulates rewards and resets on episode end', 'review the MonitorReturnWrapper get_monitored_metrics method to confirm it adds return to tracked metrics', 'refactor the MonitorReturnWrapper step method to handle variable-length step returns and track cumulative rewards', 'create a UEDEnvWrapper instance that wraps an existing environment and tracks nesting depth', 'reset the teacher environment using a JAX PRNG key and append extra state data', 'step the teacher environment with an action and optional extra dictionary data', 'check if an environment is compatible with the UEDEnvWrapper using the is_compatible class method']
```

Usage

```
{'build_MonitorReturnWrapper': 'build a python module that wraps an environment with MonitorReturnWrapper to track episodic returns', 'create_reset_extra': 'create a function that initializes episodic return tracking by resetting ep_return to zero', 'test_step_tracking': 'test the MonitorReturnWrapper step method to verify it correctly accumulates rewards and resets on episode end', 'review_get_monitored_metrics': 'review the MonitorReturnWrapper get_monitored_metrics method to confirm it adds return to tracked metrics', 'refactor_step_return_logic': 'refactor the MonitorReturnWrapper step method to handle variable-length step returns and track cumulative rewards'}
```

## File: facebookresearch_minimax/src/minimax/envs/wrappers/ued_env_wrapper.py

Prompts

```
['create a subclass of EnvWrapper that overrides reset_extra to inject custom metadata into environment tuples', 'step the wrapped environment forward by calling step with a PRNG key, state, and action', 'reset the wrapped environment to its initial state using reset with a PRNG key', 'set the environment state directly by calling set_state with an EnvState instance', 'access the unwrapped base environment through the base_env property of an EnvWrapper instance', 'build a python module to wrap an environment with MonitorEpisodicMetricsWrapper to track episodic metrics', 'test the MonitorEpisodicMetricsWrapper is_compatible method to check if an environment supports get_episodic_metrics', 'review the MonitorEpisodicMetricsWrapper step method that prefixes episodic metric keys with ep/ in info dict', 'create a function call to get_monitored_metrics that returns episodic metric names prefixed with ep/', 'refactor the MonitorEpisodicMetricsWrapper init to initialize metrics by calling get_episodic_metrics on the base environment', 'build a python module that wraps an environment with MonitorReturnWrapper to track episodic returns', 'create a function that initializes episodic return tracking by resetting ep_return to zero', 'test the MonitorReturnWrapper step method to verify it correctly accumulates rewards and resets on episode end', 'review the MonitorReturnWrapper get_monitored_metrics method to confirm it adds return to tracked metrics', 'refactor the MonitorReturnWrapper step method to handle variable-length step returns and track cumulative rewards', 'create a UEDEnvWrapper instance that wraps an existing environment and tracks nesting depth', 'reset the teacher environment using a JAX PRNG key and append extra state data', 'step the teacher environment with an action and optional extra dictionary data', 'check if an environment is compatible with the UEDEnvWrapper using the is_compatible class method']
```

Usage

```
{'create_ued_env_wrapper': 'create a UEDEnvWrapper instance that wraps an existing environment and tracks nesting depth', 'reset_teacher_env': 'reset the teacher environment using a JAX PRNG key and append extra state data', 'step_teacher_env': 'step the teacher environment with an action and optional extra dictionary data', 'get_base_env': 'get the unwrapped base environment by traversing all wrapper nesting levels', 'check_env_compatibility': 'check if an environment is compatible with the UEDEnvWrapper using the is_compatible class method'}
```

