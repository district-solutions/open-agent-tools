# Agent Python Tools

- repo: facebookresearch/deepbisim4control
- repo_uri: https://github.com/facebookresearch/deep_bisim4control

## File: facebookresearch_deepbisim4control/local_dm_control_suite/tests/domains_test.py

Prompts

```
['test all dm_control suite domains to verify tasks conform to observation and action specifications', 'test that identical seeds and actions produce identical trajectories across dm_control environments', 'test that reward visualization correctly blends material colors based on reward values in dm_control tasks', 'test that consecutive observation arrays in dm_control environments do not share memory', 'test that consecutive resets produce different initial states in dm_control suite environments', 'test the LoaderTest to load a cartpole swingup environment without any task kwargs', 'test the LoaderTest to load a cartpole swingup environment with custom time_limit and random kwargs', 'test the LoaderConstantsTest to verify suite BENCHMARKING, EASY, HARD, and EXTRA constants are non-empty', 'run the absltest main to execute all dm_control suite loader test cases', 'review the LoaderTest and LoaderConstantsTest classes to understand dm_control suite loading patterns', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using lqr_solver.solve', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert the LQR policy is optimal by comparing measured total loss against analytical expected cost', 'run the LQR domain test suite using absltest.main for all parameterized test cases', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'test_dm_control_suite_domains': 'test all dm_control suite domains to verify tasks conform to observation and action specifications', 'test_environment_determinism': 'test that identical seeds and actions produce identical trajectories across dm_control environments', 'test_visualize_reward': 'test that reward visualization correctly blends material colors based on reward values in dm_control tasks', 'test_observation_memory_isolation': 'test that consecutive observation arrays in dm_control environments do not share memory', 'test_initial_state_randomization': 'test that consecutive resets produce different initial states in dm_control suite environments'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/tests/loader_test.py

Prompts

```
['test all dm_control suite domains to verify tasks conform to observation and action specifications', 'test that identical seeds and actions produce identical trajectories across dm_control environments', 'test that reward visualization correctly blends material colors based on reward values in dm_control tasks', 'test that consecutive observation arrays in dm_control environments do not share memory', 'test that consecutive resets produce different initial states in dm_control suite environments', 'test the LoaderTest to load a cartpole swingup environment without any task kwargs', 'test the LoaderTest to load a cartpole swingup environment with custom time_limit and random kwargs', 'test the LoaderConstantsTest to verify suite BENCHMARKING, EASY, HARD, and EXTRA constants are non-empty', 'run the absltest main to execute all dm_control suite loader test cases', 'review the LoaderTest and LoaderConstantsTest classes to understand dm_control suite loading patterns', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using lqr_solver.solve', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert the LQR policy is optimal by comparing measured total loss against analytical expected cost', 'run the LQR domain test suite using absltest.main for all parameterized test cases', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'test_load_without_kwargs': 'test the LoaderTest to load a cartpole swingup environment without any task kwargs', 'test_load_with_kwargs': 'test the LoaderTest to load a cartpole swingup environment with custom time_limit and random kwargs', 'test_suite_constants': 'test the LoaderConstantsTest to verify suite BENCHMARKING, EASY, HARD, and EXTRA constants are non-empty', 'run_loader_tests': 'run the absltest main to execute all dm_control suite loader test cases', 'review_loader_test_classes': 'review the LoaderTest and LoaderConstantsTest classes to understand dm_control suite loading patterns'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/tests/lqr_test.py

Prompts

```
['test all dm_control suite domains to verify tasks conform to observation and action specifications', 'test that identical seeds and actions produce identical trajectories across dm_control environments', 'test that reward visualization correctly blends material colors based on reward values in dm_control tasks', 'test that consecutive observation arrays in dm_control environments do not share memory', 'test that consecutive resets produce different initial states in dm_control suite environments', 'test the LoaderTest to load a cartpole swingup environment without any task kwargs', 'test the LoaderTest to load a cartpole swingup environment with custom time_limit and random kwargs', 'test the LoaderConstantsTest to verify suite BENCHMARKING, EASY, HARD, and EXTRA constants are non-empty', 'run the absltest main to execute all dm_control suite loader test cases', 'review the LoaderTest and LoaderConstantsTest classes to understand dm_control suite loading patterns', 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using lqr_solver.solve', 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assert the LQR policy is optimal by comparing measured total loss against analytical expected cost', 'run the LQR domain test suite using absltest.main for all parameterized test cases', 'review the LqrTest class and its parameterized test methods for LQR domain validation']
```

Usage

```
{'test_lqr_optimal_policy': 'test the LQR optimal policy for lqr_2_1 and lqr_6_2 environments using lqr_solver.solve', 'test_lqr_optimal_policy_no_scipy': 'test the LQR optimal policy using the non-scipy DARE solver code path', 'assertPolicyisOptimal': 'assert the LQR policy is optimal by comparing measured total loss against analytical expected cost', 'run_lqr_test_suite': 'run the LQR domain test suite using absltest.main for all parameterized test cases', 'review_LqrTest_class': 'review the LqrTest class and its parameterized test methods for LQR domain validation'}
```

