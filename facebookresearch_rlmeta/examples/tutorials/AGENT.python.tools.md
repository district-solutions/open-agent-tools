# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/examples/tutorials/loop_example.py

Prompts

```
['run a ParallelLoop with mock environment and agent factories for evaluation rollouts', 'create a MockEnv subclass of Env with reset, step, close, and seed methods', 'create a MockAgent subclass of Agent with async_act, async_observe, and async_update methods', 'build an env_factory function that returns MockEnv instances by index', 'review the main function that sets up Server, Controller, and ParallelLoop for RL training', 'create a Remotable subclass with remote_method decorated functions for RPC calls', 'build a Server instance and register a Remotable service with add_service', 'create a remote client using make_remote to connect to a running server', 'run async batch remote method calls with tensor or scalar arguments', 'test the Adder class by calling add and batch_add methods remotely']
```

Usage

```
{'run_parallel_loop': 'run a ParallelLoop with mock environment and agent factories for evaluation rollouts', 'create_mock_env': 'create a MockEnv subclass of Env with reset, step, close, and seed methods', 'create_mock_agent': 'create a MockAgent subclass of Agent with async_act, async_observe, and async_update methods', 'build_env_factory': 'build an env_factory function that returns MockEnv instances by index', 'review_main_setup': 'review the main function that sets up Server, Controller, and ParallelLoop for RL training'}
```

## File: facebookresearch_rlmeta/examples/tutorials/remote_example.py

Prompts

```
['run a ParallelLoop with mock environment and agent factories for evaluation rollouts', 'create a MockEnv subclass of Env with reset, step, close, and seed methods', 'create a MockAgent subclass of Agent with async_act, async_observe, and async_update methods', 'build an env_factory function that returns MockEnv instances by index', 'review the main function that sets up Server, Controller, and ParallelLoop for RL training', 'create a Remotable subclass with remote_method decorated functions for RPC calls', 'build a Server instance and register a Remotable service with add_service', 'create a remote client using make_remote to connect to a running server', 'run async batch remote method calls with tensor or scalar arguments', 'test the Adder class by calling add and batch_add methods remotely']
```

Usage

```
{'create_remotable_class': 'create a Remotable subclass with remote_method decorated functions for RPC calls', 'build_remote_server': 'build a Server instance and register a Remotable service with add_service', 'create_remote_client': 'create a remote client using make_remote to connect to a running server', 'run_batch_remote_calls': 'run async batch remote method calls with tensor or scalar arguments', 'test_remote_adder': 'test the Adder class by calling add and batch_add methods remotely'}
```

