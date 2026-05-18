# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/gym/multigym.py

Prompts

```
['create a GymMulti instance with CartPole-v0 and a neural controller for black-box optimization benchmarking', 'run GymMulti.get_env_names to list all available gym environments that pass validation checks', 'test the gym_multi_function method by passing a parameter array and limited_fidelity flag to simulate', 'review the GymMulti neural method that applies a neural net parametrized by x to observation o', 'build a conformant planning policy by optimizing a direct sequence of actions with gym_conformant', 'test that all ng_gym env names are available and guaranteed envs exist', 'test GymMulti with LunarLander-v2 environment using parametrized pytest test', 'test GymMulti with TupleActionSpace-v0 using neural control and random inputs', 'register a custom TupleActionSpace-v0 Gym environment with 168 max episode steps', 'get the list of available Gym environment names via GymMulti.get_env_names', 'create a TupleActionSpace gym environment with tuple of discrete action spaces', 'reset the TupleActionSpace environment and return the initial observation', 'step the TupleActionSpace environment with a tuple action and get observation and reward', 'review the TupleActionSpace reward calculation which sums action[1] minus action[0]', 'test the TupleActionSpace step method with a valid tuple action of two arrays']
```

Usage

```
{'create_GymMulti_benchmark': 'create a GymMulti instance with CartPole-v0 and a neural controller for black-box optimization benchmarking', 'run_GymMulti_get_env_names': 'run GymMulti.get_env_names to list all available gym environments that pass validation checks', 'test_gym_multi_function': 'test the gym_multi_function method by passing a parameter array and limited_fidelity flag to simulate', 'review_GymMulti_neural': 'review the GymMulti neural method that applies a neural net parametrized by x to observation o', 'build_GymMulti_conformant': 'build a conformant planning policy by optimizing a direct sequence of actions with gym_conformant'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/gym/test_multigym.py

Prompts

```
['create a GymMulti instance with CartPole-v0 and a neural controller for black-box optimization benchmarking', 'run GymMulti.get_env_names to list all available gym environments that pass validation checks', 'test the gym_multi_function method by passing a parameter array and limited_fidelity flag to simulate', 'review the GymMulti neural method that applies a neural net parametrized by x to observation o', 'build a conformant planning policy by optimizing a direct sequence of actions with gym_conformant', 'test that all ng_gym env names are available and guaranteed envs exist', 'test GymMulti with LunarLander-v2 environment using parametrized pytest test', 'test GymMulti with TupleActionSpace-v0 using neural control and random inputs', 'register a custom TupleActionSpace-v0 Gym environment with 168 max episode steps', 'get the list of available Gym environment names via GymMulti.get_env_names', 'create a TupleActionSpace gym environment with tuple of discrete action spaces', 'reset the TupleActionSpace environment and return the initial observation', 'step the TupleActionSpace environment with a tuple action and get observation and reward', 'review the TupleActionSpace reward calculation which sums action[1] minus action[0]', 'test the TupleActionSpace step method with a valid tuple action of two arrays']
```

Usage

```
{'test_multigym_env_names': 'test that all ng_gym env names are available and guaranteed envs exist', 'test_run_multigym_lunarlander': 'test GymMulti with LunarLander-v2 environment using parametrized pytest test', 'test_tuple_action_space_neural': 'test GymMulti with TupleActionSpace-v0 using neural control and random inputs', 'register_tuple_action_space_gym': 'register a custom TupleActionSpace-v0 Gym environment with 168 max episode steps', 'get_gym_env_names': 'get the list of available Gym environment names via GymMulti.get_env_names'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/gym/tuple_gym_env.py

Prompts

```
['create a GymMulti instance with CartPole-v0 and a neural controller for black-box optimization benchmarking', 'run GymMulti.get_env_names to list all available gym environments that pass validation checks', 'test the gym_multi_function method by passing a parameter array and limited_fidelity flag to simulate', 'review the GymMulti neural method that applies a neural net parametrized by x to observation o', 'build a conformant planning policy by optimizing a direct sequence of actions with gym_conformant', 'test that all ng_gym env names are available and guaranteed envs exist', 'test GymMulti with LunarLander-v2 environment using parametrized pytest test', 'test GymMulti with TupleActionSpace-v0 using neural control and random inputs', 'register a custom TupleActionSpace-v0 Gym environment with 168 max episode steps', 'get the list of available Gym environment names via GymMulti.get_env_names', 'create a TupleActionSpace gym environment with tuple of discrete action spaces', 'reset the TupleActionSpace environment and return the initial observation', 'step the TupleActionSpace environment with a tuple action and get observation and reward', 'review the TupleActionSpace reward calculation which sums action[1] minus action[0]', 'test the TupleActionSpace step method with a valid tuple action of two arrays']
```

Usage

```
{'create_TupleActionSpace_env': 'create a TupleActionSpace gym environment with tuple of discrete action spaces', 'reset_TupleActionSpace': 'reset the TupleActionSpace environment and return the initial observation', 'step_TupleActionSpace': 'step the TupleActionSpace environment with a tuple action and get observation and reward', 'review_TupleActionSpace_reward': 'review the TupleActionSpace reward calculation which sums action[1] minus action[0]', 'test_TupleActionSpace_step': 'test the TupleActionSpace step method with a valid tuple action of two arrays'}
```

