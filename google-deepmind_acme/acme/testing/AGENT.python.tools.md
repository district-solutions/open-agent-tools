# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/testing/fakes.py

Prompts

```
['create a fake Acme environment with a given EnvironmentSpec for testing reinforcement learning components', 'build a discrete state and action fake environment with configurable number of actions and observations', 'build a continuous state and action fake environment with configurable action and observation dimensions', 'create a fake Reverb N-step transition dataset from an environment spec for testing replay buffers', 'create a fake RLDS dataset with configurable episode count and length from an environment spec', 'build a multiagent environment spec with dummy observation action and reward specs for given agent indices', 'create a dummy multiagent sub-spec mapping agent IDs to bounded array specs for testing', 'test the make_multiagent_environment_spec function with a list of agent indices to verify spec structure', 'review the multiagent_fakes module to understand how dummy environment specs are constructed for multiagent testing', 'refactor the _make_multiagent_spec function to support custom bounded array shape and value ranges', 'create a TestCase class extending parameterized.TestCase for pytest compatibility with absl flags', 'test the get_tempdir method to create a temporary directory and return its full path', 'review the TestCase class and how it handles unparsed FLAG access for pytest', 'refactor the get_tempdir method to support custom flag initialization logic', 'summarize the TestCase class providing pytest-compatible testing with absl flag parsing']
```

Usage

```
{'create_fake_environment': 'create a fake Acme environment with a given EnvironmentSpec for testing reinforcement learning components', 'build_discrete_environment': 'build a discrete state and action fake environment with configurable number of actions and observations', 'build_continuous_environment': 'build a continuous state and action fake environment with configurable action and observation dimensions', 'create_transition_dataset': 'create a fake Reverb N-step transition dataset from an environment spec for testing replay buffers', 'create_rlds_dataset': 'create a fake RLDS dataset with configurable episode count and length from an environment spec'}
```

## File: google-deepmind_acme/acme/testing/multiagent_fakes.py

Prompts

```
['create a fake Acme environment with a given EnvironmentSpec for testing reinforcement learning components', 'build a discrete state and action fake environment with configurable number of actions and observations', 'build a continuous state and action fake environment with configurable action and observation dimensions', 'create a fake Reverb N-step transition dataset from an environment spec for testing replay buffers', 'create a fake RLDS dataset with configurable episode count and length from an environment spec', 'build a multiagent environment spec with dummy observation action and reward specs for given agent indices', 'create a dummy multiagent sub-spec mapping agent IDs to bounded array specs for testing', 'test the make_multiagent_environment_spec function with a list of agent indices to verify spec structure', 'review the multiagent_fakes module to understand how dummy environment specs are constructed for multiagent testing', 'refactor the _make_multiagent_spec function to support custom bounded array shape and value ranges', 'create a TestCase class extending parameterized.TestCase for pytest compatibility with absl flags', 'test the get_tempdir method to create a temporary directory and return its full path', 'review the TestCase class and how it handles unparsed FLAG access for pytest', 'refactor the get_tempdir method to support custom flag initialization logic', 'summarize the TestCase class providing pytest-compatible testing with absl flag parsing']
```

Usage

```
{'build_multiagent_env_spec': 'build a multiagent environment spec with dummy observation action and reward specs for given agent indices', 'create_multiagent_sub_spec': 'create a dummy multiagent sub-spec mapping agent IDs to bounded array specs for testing', 'test_make_multiagent_environment_spec': 'test the make_multiagent_environment_spec function with a list of agent indices to verify spec structure', 'review_multiagent_fakes': 'review the multiagent_fakes module to understand how dummy environment specs are constructed for multiagent testing', 'refactor_multiagent_spec': 'refactor the _make_multiagent_spec function to support custom bounded array shape and value ranges'}
```

## File: google-deepmind_acme/acme/testing/test_utils.py

Prompts

```
['create a fake Acme environment with a given EnvironmentSpec for testing reinforcement learning components', 'build a discrete state and action fake environment with configurable number of actions and observations', 'build a continuous state and action fake environment with configurable action and observation dimensions', 'create a fake Reverb N-step transition dataset from an environment spec for testing replay buffers', 'create a fake RLDS dataset with configurable episode count and length from an environment spec', 'build a multiagent environment spec with dummy observation action and reward specs for given agent indices', 'create a dummy multiagent sub-spec mapping agent IDs to bounded array specs for testing', 'test the make_multiagent_environment_spec function with a list of agent indices to verify spec structure', 'review the multiagent_fakes module to understand how dummy environment specs are constructed for multiagent testing', 'refactor the _make_multiagent_spec function to support custom bounded array shape and value ranges', 'create a TestCase class extending parameterized.TestCase for pytest compatibility with absl flags', 'test the get_tempdir method to create a temporary directory and return its full path', 'review the TestCase class and how it handles unparsed FLAG access for pytest', 'refactor the get_tempdir method to support custom flag initialization logic', 'summarize the TestCase class providing pytest-compatible testing with absl flag parsing']
```

Usage

```
{'create_testcase_class': 'create a TestCase class extending parameterized.TestCase for pytest compatibility with absl flags', 'test_get_tempdir': 'test the get_tempdir method to create a temporary directory and return its full path', 'review_testcase_flags': 'review the TestCase class and how it handles unparsed FLAG access for pytest', 'refactor_get_tempdir': 'refactor the get_tempdir method to support custom flag initialization logic', 'summarize_testcase': 'summarize the TestCase class providing pytest-compatible testing with absl flag parsing'}
```

