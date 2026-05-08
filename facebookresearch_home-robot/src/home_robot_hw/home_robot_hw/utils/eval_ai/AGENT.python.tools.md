# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/utils/eval_ai/evaluation_pb2_grpc.py

Prompts

```
['create a gRPC client using EnvironmentStub to initialize the evaluation environment', 'use EnvironmentStub to query the number of episodes available in the environment', 'call the reset RPC via EnvironmentStub to reset the environment to its initial state', 'use EnvironmentStub to apply an action and receive the resulting observation', 'subclass EnvironmentServicer and implement methods like init_env and apply_action for a gRPC server']
```

Usage

```
{'init_environment_grpc': 'create a gRPC client using EnvironmentStub to initialize the evaluation environment', 'get_number_of_episodes': 'use EnvironmentStub to query the number of episodes available in the environment', 'reset_environment': 'call the reset RPC via EnvironmentStub to reset the environment to its initial state', 'apply_action_to_environment': 'use EnvironmentStub to apply an action and receive the resulting observation', 'implement_environment_servicer': 'subclass EnvironmentServicer and implement methods like init_env and apply_action for a gRPC server'}
```

