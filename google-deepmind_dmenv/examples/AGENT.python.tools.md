# Agent Python Tools

- repo: google-deepmind/dmenv
- repo_uri: https://github.com/google-deepmind/dm_env

## File: google-deepmind_dmenv/examples/catch.py

Prompts

```
['create a Catch RL environment with custom rows, columns, and seed parameters', 'reset the Catch environment to start a new episode with a random ball position', 'step the Catch environment with a discrete action to move the paddle left, right, or stay', 'get the BoundedArray observation spec describing the board shape, dtype, and value bounds', 'get the DiscreteArray action spec with three available actions for paddle movement', 'run the CatchTest class to test the dm_env catch environment using absltest', 'test the catch.Catch environment by running CatchTest with EnvironmentTestMixin', 'review the CatchTest class and its make_object_under_test method for test coverage', 'summarize the CatchTest class which tests the dm_env catch example environment', 'refactor the CatchTest class to add custom test methods beyond EnvironmentTestMixin']
```

Usage

```
{'create_catch_environment': 'create a Catch RL environment with custom rows, columns, and seed parameters', 'reset_catch_episode': 'reset the Catch environment to start a new episode with a random ball position', 'step_catch_action': 'step the Catch environment with a discrete action to move the paddle left, right, or stay', 'get_observation_spec': 'get the BoundedArray observation spec describing the board shape, dtype, and value bounds', 'get_action_spec': 'get the DiscreteArray action spec with three available actions for paddle movement'}
```

## File: google-deepmind_dmenv/examples/catch_test.py

Prompts

```
['create a Catch RL environment with custom rows, columns, and seed parameters', 'reset the Catch environment to start a new episode with a random ball position', 'step the Catch environment with a discrete action to move the paddle left, right, or stay', 'get the BoundedArray observation spec describing the board shape, dtype, and value bounds', 'get the DiscreteArray action spec with three available actions for paddle movement', 'run the CatchTest class to test the dm_env catch environment using absltest', 'test the catch.Catch environment by running CatchTest with EnvironmentTestMixin', 'review the CatchTest class and its make_object_under_test method for test coverage', 'summarize the CatchTest class which tests the dm_env catch example environment', 'refactor the CatchTest class to add custom test methods beyond EnvironmentTestMixin']
```

Usage

```
{'run_catch_test': 'run the CatchTest class to test the dm_env catch environment using absltest', 'test_catch_environment': 'test the catch.Catch environment by running CatchTest with EnvironmentTestMixin', 'review_catch_test': 'review the CatchTest class and its make_object_under_test method for test coverage', 'summarize_catch_test': 'summarize the CatchTest class which tests the dm_env catch example environment', 'refactor_catch_test': 'refactor the CatchTest class to add custom test methods beyond EnvironmentTestMixin'}
```

