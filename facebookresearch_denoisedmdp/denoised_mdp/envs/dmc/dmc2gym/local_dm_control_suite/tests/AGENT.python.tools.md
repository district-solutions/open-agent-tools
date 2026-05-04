# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/tests/domains_test.py

Prompts

```
['create a uniform random policy that samples actions within the bounds of a given action spec', 'step through a DM Control environment episodes using a provided policy and yield each time step', 'make a trajectory generator for a given domain and task using a seeded uniform random policy', 'test that all physics model components in a DM Control domain task have non-empty names', 'test that two trajectories with identical seeds produce identical observations rewards and discounts', 'run the LoaderTest suite to verify dm_control.suite.load works without kwargs', 'run the LoaderTest suite to verify dm_control.suite.load works with task_kwargs', 'run the LoaderConstantsTest suite to verify suite.BENCHMARKING EASY HARD EXTRA are non-empty', 'test that suite.load cartpole swingup returns a control.Environment instance', 'test that suite.load cartpole swingup with task_kwargs returns a control.Environment instance', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using the lqr_solver', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert an LQR policy is optimal by comparing measured total loss against the analytical expected cost', 'run the LqrTest parameterized test suite for lqr_2_1 and lqr_6_2 environments via absltest', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'create_uniform_random_policy': 'create a uniform random policy that samples actions within the bounds of a given action spec', 'step_environment': 'step through a DM Control environment episodes using a provided policy and yield each time step', 'make_trajectory': 'make a trajectory generator for a given domain and task using a seeded uniform random policy', 'test_domain_components_have_names': 'test that all physics model components in a DM Control domain task have non-empty names', 'test_environment_is_deterministic': 'test that two trajectories with identical seeds produce identical observations rewards and discounts'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/tests/loader_test.py

Prompts

```
['create a uniform random policy that samples actions within the bounds of a given action spec', 'step through a DM Control environment episodes using a provided policy and yield each time step', 'make a trajectory generator for a given domain and task using a seeded uniform random policy', 'test that all physics model components in a DM Control domain task have non-empty names', 'test that two trajectories with identical seeds produce identical observations rewards and discounts', 'run the LoaderTest suite to verify dm_control.suite.load works without kwargs', 'run the LoaderTest suite to verify dm_control.suite.load works with task_kwargs', 'run the LoaderConstantsTest suite to verify suite.BENCHMARKING EASY HARD EXTRA are non-empty', 'test that suite.load cartpole swingup returns a control.Environment instance', 'test that suite.load cartpole swingup with task_kwargs returns a control.Environment instance', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using the lqr_solver', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert an LQR policy is optimal by comparing measured total loss against the analytical expected cost', 'run the LqrTest parameterized test suite for lqr_2_1 and lqr_6_2 environments via absltest', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'run_loader_tests': 'run the LoaderTest suite to verify dm_control.suite.load works without kwargs', 'run_loader_kwargs_tests': 'run the LoaderTest suite to verify dm_control.suite.load works with task_kwargs', 'run_constants_tests': 'run the LoaderConstantsTest suite to verify suite.BENCHMARKING EASY HARD EXTRA are non-empty', 'test_load_without_kwargs': 'test that suite.load cartpole swingup returns a control.Environment instance', 'test_load_with_kwargs': 'test that suite.load cartpole swingup with task_kwargs returns a control.Environment instance'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/tests/lqr_test.py

Prompts

```
['create a uniform random policy that samples actions within the bounds of a given action spec', 'step through a DM Control environment episodes using a provided policy and yield each time step', 'make a trajectory generator for a given domain and task using a seeded uniform random policy', 'test that all physics model components in a DM Control domain task have non-empty names', 'test that two trajectories with identical seeds produce identical observations rewards and discounts', 'run the LoaderTest suite to verify dm_control.suite.load works without kwargs', 'run the LoaderTest suite to verify dm_control.suite.load works with task_kwargs', 'run the LoaderConstantsTest suite to verify suite.BENCHMARKING EASY HARD EXTRA are non-empty', 'test that suite.load cartpole swingup returns a control.Environment instance', 'test that suite.load cartpole swingup with task_kwargs returns a control.Environment instance', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using the lqr_solver', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert an LQR policy is optimal by comparing measured total loss against the analytical expected cost', 'run the LqrTest parameterized test suite for lqr_2_1 and lqr_6_2 environments via absltest', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'test_lqr_optimal_policy': 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using the lqr_solver', 'test_lqr_optimal_policy_no_scipy': 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assertPolicyisOptimal': 'assert an LQR policy is optimal by comparing measured total loss against the analytical expected cost', 'run_lqr_test_suite': 'run the LqrTest parameterized test suite for lqr_2_1 and lqr_6_2 environments via absltest', 'review_LqrTest_class': 'review the LqrTest class and its parameterized test methods for LQR domain validation'}
```

