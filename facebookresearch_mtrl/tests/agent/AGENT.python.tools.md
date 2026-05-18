# Agent Python Tools

- repo: facebookresearch/mtrl
- repo_uri: https://github.com/facebookresearch/mtrl

## File: facebookresearch_mtrl/tests/agent/hipbmdp_test.py

Prompts

```
['test the agent instantiation and action selection across multiple encoder and agent type combinations', 'get a Hydra config composed with environment and agent overrides then prepared with metadata', 'get parameterized override tuples for each agent name, mode, and encoder combination', 'get pixel encoder test overrides with encoding dimension for all agent types', 'get a HIP training environment and its metadata as a pytest session-scoped fixture', 'test the parametrized test_agent function that validates action shapes for Meta-World MT10 agents', 'build config override combinations for SAC and DeepMDP agents with MoE encoder and task routing modes', 'create a pytest session fixture that yields the Meta-World MT10 training environment and its metadata', 'build a Meta-World vector environment with state SAC agent and return environment metadata', 'build a HIP BMDP environment with SAC agent and return environment metadata', 'test the get_metaworld_env_and_metadata function with a specific env name and mode', 'test the get_hip_env_and_metadata function with a specific env name and mode', 'refactor get_metaworld_env_and_metadata to support custom episode steps and task lists']
```

Usage

```
{'test_agent_with_encoders': 'test the agent instantiation and action selection across multiple encoder and agent type combinations', 'get_config_with_overrides': 'get a Hydra config composed with environment and agent overrides then prepared with metadata', 'get_overrides_using_encoders': 'get parameterized override tuples for each agent name, mode, and encoder combination', 'get_overrides_for_testing_agent': 'get pixel encoder test overrides with encoding dimension for all agent types', 'get_hip_train_env_and_metadata': 'get a HIP training environment and its metadata as a pytest session-scoped fixture'}
```

## File: facebookresearch_mtrl/tests/agent/metaworld_test.py

Prompts

```
['test the agent instantiation and action selection across multiple encoder and agent type combinations', 'get a Hydra config composed with environment and agent overrides then prepared with metadata', 'get parameterized override tuples for each agent name, mode, and encoder combination', 'get pixel encoder test overrides with encoding dimension for all agent types', 'get a HIP training environment and its metadata as a pytest session-scoped fixture', 'test the parametrized test_agent function that validates action shapes for Meta-World MT10 agents', 'build config override combinations for SAC and DeepMDP agents with MoE encoder and task routing modes', 'create a pytest session fixture that yields the Meta-World MT10 training environment and its metadata', 'build a Meta-World vector environment with state SAC agent and return environment metadata', 'build a HIP BMDP environment with SAC agent and return environment metadata', 'test the get_metaworld_env_and_metadata function with a specific env name and mode', 'test the get_hip_env_and_metadata function with a specific env name and mode', 'refactor get_metaworld_env_and_metadata to support custom episode steps and task lists']
```

Usage

```
{'test_agent_with_overrides': 'test the parametrized test_agent function that validates action shapes for Meta-World MT10 agents', 'get_config_with_overrides': 'create a Hydra config composed with agent and encoder overrides then prepared with environment metadata', 'get_overrides_using_encoders_and_meta_encoders': 'build config override combinations for SAC and DeepMDP agents with MoE encoder and task routing modes', 'get_overrides_for_testing_agent': 'generate test parameter tuples combining feedforward encoders with MoE meta-encoders and encoding dimensions', 'get_mt10_train_env_and_metadata': 'create a pytest session fixture that yields the Meta-World MT10 training environment and its metadata'}
```

## File: facebookresearch_mtrl/tests/agent/utils.py

Prompts

```
['test the agent instantiation and action selection across multiple encoder and agent type combinations', 'get a Hydra config composed with environment and agent overrides then prepared with metadata', 'get parameterized override tuples for each agent name, mode, and encoder combination', 'get pixel encoder test overrides with encoding dimension for all agent types', 'get a HIP training environment and its metadata as a pytest session-scoped fixture', 'test the parametrized test_agent function that validates action shapes for Meta-World MT10 agents', 'build config override combinations for SAC and DeepMDP agents with MoE encoder and task routing modes', 'create a pytest session fixture that yields the Meta-World MT10 training environment and its metadata', 'build a Meta-World vector environment with state SAC agent and return environment metadata', 'build a HIP BMDP environment with SAC agent and return environment metadata', 'test the get_metaworld_env_and_metadata function with a specific env name and mode', 'test the get_hip_env_and_metadata function with a specific env name and mode', 'refactor get_metaworld_env_and_metadata to support custom episode steps and task lists']
```

Usage

```
{'build_metaworld_env': 'build a Meta-World vector environment with state SAC agent and return environment metadata', 'build_hip_env': 'build a HIP BMDP environment with SAC agent and return environment metadata', 'test_get_metaworld_env_and_metadata': 'test the get_metaworld_env_and_metadata function with a specific env name and mode', 'test_get_hip_env_and_metadata': 'test the get_hip_env_and_metadata function with a specific env name and mode', 'refactor_get_metaworld_env_and_metadata': 'refactor get_metaworld_env_and_metadata to support custom episode steps and task lists'}
```

