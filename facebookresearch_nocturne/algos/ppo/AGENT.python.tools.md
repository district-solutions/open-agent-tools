# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/algos/ppo/base_runner.py

Prompts

```
['initialize a Runner instance with a config dict containing algo parameters, envs, device, and num_agents', 'compute returns for collected rollout data using the critic network and value normalizer', 'train the MAPPO policy using data stored in the shared replay buffer', 'save the policy actor and critic network state dicts to the models directory', 'restore the policy actor and critic networks from previously saved model files', 'create a SubprocVecEnv from env factory functions to run gym environments in parallel subprocesses', 'create a ShareSubprocVecEnv to run multi-agent environments with shared observations in parallel subprocesses', 'create a DummyVecEnv to run multiple gym environments synchronously in the same process', 'create a ShareDummyVecEnv to run multi-agent environments with shared observations synchronously in the same process', 'review the ShareVecEnv abstract base class and its reset, step_async, step_wait, and render methods']
```

Usage

```
{'init_Runner': 'initialize a Runner instance with a config dict containing algo parameters, envs, device, and num_agents', 'compute_Runner_compute': 'compute returns for collected rollout data using the critic network and value normalizer', 'train_Runner_train': 'train the MAPPO policy using data stored in the shared replay buffer', 'save_Runner_save': 'save the policy actor and critic network state dicts to the models directory', 'restore_Runner_restore': 'restore the policy actor and critic networks from previously saved model files'}
```

## File: facebookresearch_nocturne/algos/ppo/env_wrappers.py

Prompts

```
['initialize a Runner instance with a config dict containing algo parameters, envs, device, and num_agents', 'compute returns for collected rollout data using the critic network and value normalizer', 'train the MAPPO policy using data stored in the shared replay buffer', 'save the policy actor and critic network state dicts to the models directory', 'restore the policy actor and critic networks from previously saved model files', 'create a SubprocVecEnv from env factory functions to run gym environments in parallel subprocesses', 'create a ShareSubprocVecEnv to run multi-agent environments with shared observations in parallel subprocesses', 'create a DummyVecEnv to run multiple gym environments synchronously in the same process', 'create a ShareDummyVecEnv to run multi-agent environments with shared observations synchronously in the same process', 'review the ShareVecEnv abstract base class and its reset, step_async, step_wait, and render methods']
```

Usage

```
{'create_subproc_vec_env': 'create a SubprocVecEnv from env factory functions to run gym environments in parallel subprocesses', 'create_share_subproc_vec_env': 'create a ShareSubprocVecEnv to run multi-agent environments with shared observations in parallel subprocesses', 'create_dummy_vec_env': 'create a DummyVecEnv to run multiple gym environments synchronously in the same process', 'create_share_dummy_vec_env': 'create a ShareDummyVecEnv to run multi-agent environments with shared observations synchronously in the same process', 'review_share_vec_env': 'review the ShareVecEnv abstract base class and its reset, step_async, step_wait, and render methods'}
```

