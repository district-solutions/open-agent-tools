# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/metaworld/tests/metaworld/envs/mujoco/sawyer_xyz/test_obs_space_hand.py

Prompts

```
['test the SawyerXYZ robot hand observation space by running 100 spherical reach targets and asserting hand position bounds', 'run the SawyerRandomReachPolicy get_action method to compute delta position and grab effort for a given observation', 'create a SawyerRandomReachPolicy instance with a target XYZ coordinate to drive the robot hand toward that target', 'sample random points from the surface of a sphere with a given radius for use as reach targets', 'review the SawyerXYZEnv _HAND_SPACE observation space bounds to verify hand position containment after reaching', 'test that metaworld MT50 benchmark environments return the same object position and goal on each reset', 'run the metaworld MT50 benchmark to iterate over all training environment classes and tasks', 'create a metaworld environment instance from a training class and set a specific task on it', 'review the test_reset_returns_same_obj_and_goal function to understand how it validates deterministic reset behavior', 'summarize the metaworld reset test that checks initial object poses and goal positions are consistent across resets', 'run the pytest test_scripted_policy to verify Sawyer robot policies succeed in Meta-World environments', 'run the parametrized test_scripted_policy with noisy action cases marked as basic', 'review the test_cases_latest_nonoise list of 89 Meta-World environment and policy configurations', 'review the test_cases_latest_noisy list of 89 noisy action test configurations', 'review the env pytest fixture that instantiates Meta-World environments with partial observability disabled', 'test a policy against a Meta-World environment and return success flag, rewards, and returns', 'run a policy in a Meta-World environment yielding reward, done, and info per step', 'test a policy in a Meta-World environment with GUI rendering enabled', 'refactor the trajectory generator to support custom noise distributions or action clipping', 'summarize the observation space error text function for debugging out-of-bounds observations']
```

Usage

```
{'test_reaching_limit': 'test the SawyerXYZ robot hand observation space by running 100 spherical reach targets and asserting hand position bounds', 'run_SawyerRandomReachPolicy_get_action': 'run the SawyerRandomReachPolicy get_action method to compute delta position and grab effort for a given observation', 'create_SawyerRandomReachPolicy': 'create a SawyerRandomReachPolicy instance with a target XYZ coordinate to drive the robot hand toward that target', 'sample_spherical': 'sample random points from the surface of a sphere with a given radius for use as reach targets', 'review_SawyerXYZEnv_HAND_SPACE': 'review the SawyerXYZEnv _HAND_SPACE observation space bounds to verify hand position containment after reaching'}
```

## File: facebookresearch_eai-vc/third_party/metaworld/tests/metaworld/envs/mujoco/sawyer_xyz/test_sawyer_xyz_env.py

Prompts

```
['test the SawyerXYZ robot hand observation space by running 100 spherical reach targets and asserting hand position bounds', 'run the SawyerRandomReachPolicy get_action method to compute delta position and grab effort for a given observation', 'create a SawyerRandomReachPolicy instance with a target XYZ coordinate to drive the robot hand toward that target', 'sample random points from the surface of a sphere with a given radius for use as reach targets', 'review the SawyerXYZEnv _HAND_SPACE observation space bounds to verify hand position containment after reaching', 'test that metaworld MT50 benchmark environments return the same object position and goal on each reset', 'run the metaworld MT50 benchmark to iterate over all training environment classes and tasks', 'create a metaworld environment instance from a training class and set a specific task on it', 'review the test_reset_returns_same_obj_and_goal function to understand how it validates deterministic reset behavior', 'summarize the metaworld reset test that checks initial object poses and goal positions are consistent across resets', 'run the pytest test_scripted_policy to verify Sawyer robot policies succeed in Meta-World environments', 'run the parametrized test_scripted_policy with noisy action cases marked as basic', 'review the test_cases_latest_nonoise list of 89 Meta-World environment and policy configurations', 'review the test_cases_latest_noisy list of 89 noisy action test configurations', 'review the env pytest fixture that instantiates Meta-World environments with partial observability disabled', 'test a policy against a Meta-World environment and return success flag, rewards, and returns', 'run a policy in a Meta-World environment yielding reward, done, and info per step', 'test a policy in a Meta-World environment with GUI rendering enabled', 'refactor the trajectory generator to support custom noise distributions or action clipping', 'summarize the observation space error text function for debugging out-of-bounds observations']
```

Usage

```
{'test_reset_returns_same_obj_and_goal': 'test that metaworld MT50 benchmark environments return the same object position and goal on each reset', 'run_metaworld_mt50_benchmark': 'run the metaworld MT50 benchmark to iterate over all training environment classes and tasks', 'create_metaworld_environment': 'create a metaworld environment instance from a training class and set a specific task on it', 'review_test_reset_returns_same_obj_and_goal': 'review the test_reset_returns_same_obj_and_goal function to understand how it validates deterministic reset behavior', 'summarize_metaworld_reset_test': 'summarize the metaworld reset test that checks initial object poses and goal positions are consistent across resets'}
```

## File: facebookresearch_eai-vc/third_party/metaworld/tests/metaworld/envs/mujoco/sawyer_xyz/test_scripted_policies.py

Prompts

```
['test the SawyerXYZ robot hand observation space by running 100 spherical reach targets and asserting hand position bounds', 'run the SawyerRandomReachPolicy get_action method to compute delta position and grab effort for a given observation', 'create a SawyerRandomReachPolicy instance with a target XYZ coordinate to drive the robot hand toward that target', 'sample random points from the surface of a sphere with a given radius for use as reach targets', 'review the SawyerXYZEnv _HAND_SPACE observation space bounds to verify hand position containment after reaching', 'test that metaworld MT50 benchmark environments return the same object position and goal on each reset', 'run the metaworld MT50 benchmark to iterate over all training environment classes and tasks', 'create a metaworld environment instance from a training class and set a specific task on it', 'review the test_reset_returns_same_obj_and_goal function to understand how it validates deterministic reset behavior', 'summarize the metaworld reset test that checks initial object poses and goal positions are consistent across resets', 'run the pytest test_scripted_policy to verify Sawyer robot policies succeed in Meta-World environments', 'run the parametrized test_scripted_policy with noisy action cases marked as basic', 'review the test_cases_latest_nonoise list of 89 Meta-World environment and policy configurations', 'review the test_cases_latest_noisy list of 89 noisy action test configurations', 'review the env pytest fixture that instantiates Meta-World environments with partial observability disabled', 'test a policy against a Meta-World environment and return success flag, rewards, and returns', 'run a policy in a Meta-World environment yielding reward, done, and info per step', 'test a policy in a Meta-World environment with GUI rendering enabled', 'refactor the trajectory generator to support custom noise distributions or action clipping', 'summarize the observation space error text function for debugging out-of-bounds observations']
```

Usage

```
{'run_test_scripted_policy': 'run the pytest test_scripted_policy to verify Sawyer robot policies succeed in Meta-World environments', 'run_test_scripted_policy_noisy': 'run the parametrized test_scripted_policy with noisy action cases marked as basic', 'review_test_cases_latest_nonoise': 'review the test_cases_latest_nonoise list of 89 Meta-World environment and policy configurations', 'review_test_cases_latest_noisy': 'review the test_cases_latest_noisy list of 89 noisy action test configurations', 'review_env_fixture': 'review the env pytest fixture that instantiates Meta-World environments with partial observability disabled'}
```

## File: facebookresearch_eai-vc/third_party/metaworld/tests/metaworld/envs/mujoco/sawyer_xyz/utils.py

Prompts

```
['test the SawyerXYZ robot hand observation space by running 100 spherical reach targets and asserting hand position bounds', 'run the SawyerRandomReachPolicy get_action method to compute delta position and grab effort for a given observation', 'create a SawyerRandomReachPolicy instance with a target XYZ coordinate to drive the robot hand toward that target', 'sample random points from the surface of a sphere with a given radius for use as reach targets', 'review the SawyerXYZEnv _HAND_SPACE observation space bounds to verify hand position containment after reaching', 'test that metaworld MT50 benchmark environments return the same object position and goal on each reset', 'run the metaworld MT50 benchmark to iterate over all training environment classes and tasks', 'create a metaworld environment instance from a training class and set a specific task on it', 'review the test_reset_returns_same_obj_and_goal function to understand how it validates deterministic reset behavior', 'summarize the metaworld reset test that checks initial object poses and goal positions are consistent across resets', 'run the pytest test_scripted_policy to verify Sawyer robot policies succeed in Meta-World environments', 'run the parametrized test_scripted_policy with noisy action cases marked as basic', 'review the test_cases_latest_nonoise list of 89 Meta-World environment and policy configurations', 'review the test_cases_latest_noisy list of 89 noisy action test configurations', 'review the env pytest fixture that instantiates Meta-World environments with partial observability disabled', 'test a policy against a Meta-World environment and return success flag, rewards, and returns', 'run a policy in a Meta-World environment yielding reward, done, and info per step', 'test a policy in a Meta-World environment with GUI rendering enabled', 'refactor the trajectory generator to support custom noise distributions or action clipping', 'summarize the observation space error text function for debugging out-of-bounds observations']
```

Usage

```
{'test_trajectory_summary': 'test a policy against a Meta-World environment and return success flag, rewards, and returns', 'run_trajectory_generator': 'run a policy in a Meta-World environment yielding reward, done, and info per step', 'test_trajectory_summary_with_render': 'test a policy in a Meta-World environment with GUI rendering enabled', 'refactor_trajectory_generator': 'refactor the trajectory generator to support custom noise distributions or action clipping', 'summarize_obs_space_error_text': 'summarize the observation space error text function for debugging out-of-bounds observations'}
```

