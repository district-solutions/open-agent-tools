# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/base.py

Prompts

```
['create a python subclass of Agent that implements select_action and update methods', 'implement the select_action method to return a discrete action given a dm_env timestep', 'implement the update method to process a transition with timestep, action, and new_timestep', 'review the Agent abstract base class and its required abstract methods for compliance', 'refactor an existing Agent subclass to correctly handle dm_env.TimeStep inputs and int actions', 'run an agent on a dm_env environment for a specified number of episodes', 'run an agent on an environment with terminal logging enabled for every step', 'run a single episode of an agent interacting with a dm_env environment', 'review the run function that implements the agent-environment training loop with reset step and update', 'summarize the experiment module that provides a simple agent-environment training loop']
```

Usage

```
{'create_agent_subclass': 'create a python subclass of Agent that implements select_action and update methods', 'implement_select_action': 'implement the select_action method to return a discrete action given a dm_env timestep', 'implement_update': 'implement the update method to process a transition with timestep, action, and new_timestep', 'review_agent_interface': 'review the Agent abstract base class and its required abstract methods for compliance', 'refactor_agent_subclass': 'refactor an existing Agent subclass to correctly handle dm_env.TimeStep inputs and int actions'}
```

## File: google-deepmind_bsuite/bsuite/baselines/experiment.py

Prompts

```
['create a python subclass of Agent that implements select_action and update methods', 'implement the select_action method to return a discrete action given a dm_env timestep', 'implement the update method to process a transition with timestep, action, and new_timestep', 'review the Agent abstract base class and its required abstract methods for compliance', 'refactor an existing Agent subclass to correctly handle dm_env.TimeStep inputs and int actions', 'run an agent on a dm_env environment for a specified number of episodes', 'run an agent on an environment with terminal logging enabled for every step', 'run a single episode of an agent interacting with a dm_env environment', 'review the run function that implements the agent-environment training loop with reset step and update', 'summarize the experiment module that provides a simple agent-environment training loop']
```

Usage

```
{'run_agent_training_loop': 'run an agent on a dm_env environment for a specified number of episodes', 'run_agent_with_verbose_logging': 'run an agent on an environment with terminal logging enabled for every step', 'run_single_episode': 'run a single episode of an agent interacting with a dm_env environment', 'review_run_function': 'review the run function that implements the agent-environment training loop with reset step and update', 'summarize_experiment_module': 'summarize the experiment module that provides a simple agent-environment training loop'}
```

