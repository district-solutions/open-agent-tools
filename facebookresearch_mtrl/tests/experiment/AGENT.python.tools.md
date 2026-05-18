# Agent Python Tools

- repo: facebookresearch/mtrl
- repo_uri: https://github.com/facebookresearch/mtrl

## File: facebookresearch_mtrl/tests/experiment/hipbmdp_test.py

Prompts

```
['run the parametrized pytest test for DMControl multi-task experiments across 9 RL agents', 'generate test configurations for DMControl multi-task experiments with various agent and hyperparameter combinations', 'test the hipbmdp agent on the dmcontrol-finger-spin-distribution-v0 environment with 10 parallel envs', 'run parametrized tests for sac, sac_ae, and deepmdp agents with disentangled alpha toggled', 'check the output from a DMControl experiment command with specified agent, env, and training parameters', 'run the pytest parametrized test_metaworld_single_agent to validate MetaWorld single-agent RL configurations', 'call get_config_for_metaworld_single_agent to generate all test config combinations for MetaWorld experiments', 'test the MetaWorld MT10 environment using the state_sac agent with Mixture of Experts encoder', 'test the MetaWorld MT10 environment using the state_deepmdp agent with feedforward encoder', 'review the get_config_for_metaworld_single_agent function to understand agent and encoder parameter combinations', 'build a command list to run a multitask RL experiment with configurable agent and environment parameters', 'test the experiment command output by running subprocess and validating expected model save and delete log messages', 'create all parameter combination configs from a dict of parameter lists using itertools product', 'map a parameter combination list to a config dict by zipping values with their corresponding keys', 'generate a unique test ID string from an experiment name and config dict using SHA-224 hashing']
```

Usage

```
{'run_test_dmcontrol_multi_task': 'run the parametrized pytest test for DMControl multi-task experiments across 9 RL agents', 'generate_config_get_config_for_dmcontrol_multi_task': 'generate test configurations for DMControl multi-task experiments with various agent and hyperparameter combinations', 'test_hipbmdp_agent': 'test the hipbmdp agent on the dmcontrol-finger-spin-distribution-v0 environment with 10 parallel envs', 'run_parametrized_test_sac_agents': 'run parametrized tests for sac, sac_ae, and deepmdp agents with disentangled alpha toggled', 'check_output_check_output_from_cmd': 'check the output from a DMControl experiment command with specified agent, env, and training parameters'}
```

## File: facebookresearch_mtrl/tests/experiment/metaworld_test.py

Prompts

```
['run the parametrized pytest test for DMControl multi-task experiments across 9 RL agents', 'generate test configurations for DMControl multi-task experiments with various agent and hyperparameter combinations', 'test the hipbmdp agent on the dmcontrol-finger-spin-distribution-v0 environment with 10 parallel envs', 'run parametrized tests for sac, sac_ae, and deepmdp agents with disentangled alpha toggled', 'check the output from a DMControl experiment command with specified agent, env, and training parameters', 'run the pytest parametrized test_metaworld_single_agent to validate MetaWorld single-agent RL configurations', 'call get_config_for_metaworld_single_agent to generate all test config combinations for MetaWorld experiments', 'test the MetaWorld MT10 environment using the state_sac agent with Mixture of Experts encoder', 'test the MetaWorld MT10 environment using the state_deepmdp agent with feedforward encoder', 'review the get_config_for_metaworld_single_agent function to understand agent and encoder parameter combinations', 'build a command list to run a multitask RL experiment with configurable agent and environment parameters', 'test the experiment command output by running subprocess and validating expected model save and delete log messages', 'create all parameter combination configs from a dict of parameter lists using itertools product', 'map a parameter combination list to a config dict by zipping values with their corresponding keys', 'generate a unique test ID string from an experiment name and config dict using SHA-224 hashing']
```

Usage

```
{'run_metaworld_single_agent_tests': 'run the pytest parametrized test_metaworld_single_agent to validate MetaWorld single-agent RL configurations', 'get_metaworld_single_agent_configs': 'call get_config_for_metaworld_single_agent to generate all test config combinations for MetaWorld experiments', 'test_metaworld_with_sac_agent': 'test the MetaWorld MT10 environment using the state_sac agent with Mixture of Experts encoder', 'test_metaworld_with_deepmdp_agent': 'test the MetaWorld MT10 environment using the state_deepmdp agent with feedforward encoder', 'review_metaworld_test_config': 'review the get_config_for_metaworld_single_agent function to understand agent and encoder parameter combinations'}
```

## File: facebookresearch_mtrl/tests/experiment/utils.py

Prompts

```
['run the parametrized pytest test for DMControl multi-task experiments across 9 RL agents', 'generate test configurations for DMControl multi-task experiments with various agent and hyperparameter combinations', 'test the hipbmdp agent on the dmcontrol-finger-spin-distribution-v0 environment with 10 parallel envs', 'run parametrized tests for sac, sac_ae, and deepmdp agents with disentangled alpha toggled', 'check the output from a DMControl experiment command with specified agent, env, and training parameters', 'run the pytest parametrized test_metaworld_single_agent to validate MetaWorld single-agent RL configurations', 'call get_config_for_metaworld_single_agent to generate all test config combinations for MetaWorld experiments', 'test the MetaWorld MT10 environment using the state_sac agent with Mixture of Experts encoder', 'test the MetaWorld MT10 environment using the state_deepmdp agent with feedforward encoder', 'review the get_config_for_metaworld_single_agent function to understand agent and encoder parameter combinations', 'build a command list to run a multitask RL experiment with configurable agent and environment parameters', 'test the experiment command output by running subprocess and validating expected model save and delete log messages', 'create all parameter combination configs from a dict of parameter lists using itertools product', 'map a parameter combination list to a config dict by zipping values with their corresponding keys', 'generate a unique test ID string from an experiment name and config dict using SHA-224 hashing']
```

Usage

```
{'build_experiment_command': 'build a command list to run a multitask RL experiment with configurable agent and environment parameters', 'test_experiment_output': 'test the experiment command output by running subprocess and validating expected model save and delete log messages', 'create_test_configs': 'create all parameter combination configs from a dict of parameter lists using itertools product', 'map_params_to_config': 'map a parameter combination list to a config dict by zipping values with their corresponding keys', 'generate_test_id': 'generate a unique test ID string from an experiment name and config dict using SHA-224 hashing'}
```

