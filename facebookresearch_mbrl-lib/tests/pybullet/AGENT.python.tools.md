# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/tests/pybullet/test_diagnostics.py

Prompts

```
['test the DatasetEvaluator to generate prediction plots for each observation dimension', 'test the FineTuner to fine-tune a dynamics model and verify updated outputs', 'test the Visualizer to generate a rollout video of the agent policy', 'create a one-dimensional transition reward model from config and observation action shapes', 'create a replay buffer from config and populate it with agent rollout trajectories', 'rollout agent trajectories in a PyBullet environment and store transitions into a replay buffer', 'test that freezing a pybullet gym environment produces deterministic observations and rewards across steps', 'test that getting and setting environment state works correctly for pybullet gym environments', 'test that environment state can be transferred between two separate pybullet gym instances', 'test the recursive equality comparison function for numpy arrays, dicts, and scalars', 'test that two environment states are equal by comparing all elements except the unique file name']
```

Usage

```
{'test_eval_on_dataset': 'test the DatasetEvaluator to generate prediction plots for each observation dimension', 'test_finetuner': 'test the FineTuner to fine-tune a dynamics model and verify updated outputs', 'test_visualizer': 'test the Visualizer to generate a rollout video of the agent policy', 'create_one_dim_tr_model': 'create a one-dimensional transition reward model from config and observation action shapes', 'create_replay_buffer': 'create a replay buffer from config and populate it with agent rollout trajectories'}
```

## File: facebookresearch_mbrl-lib/tests/pybullet/test_diagnostics_from_cfg.py

Prompts

```
['test the DatasetEvaluator to generate prediction plots for each observation dimension', 'test the FineTuner to fine-tune a dynamics model and verify updated outputs', 'test the Visualizer to generate a rollout video of the agent policy', 'create a one-dimensional transition reward model from config and observation action shapes', 'create a replay buffer from config and populate it with agent rollout trajectories', 'rollout agent trajectories in a PyBullet environment and store transitions into a replay buffer', 'test that freezing a pybullet gym environment produces deterministic observations and rewards across steps', 'test that getting and setting environment state works correctly for pybullet gym environments', 'test that environment state can be transferred between two separate pybullet gym instances', 'test the recursive equality comparison function for numpy arrays, dicts, and scalars', 'test that two environment states are equal by comparing all elements except the unique file name']
```

Usage

```
{'test_eval_on_dataset': 'test the DatasetEvaluator to evaluate model predictions on a saved dataset and generate per-dimension plots', 'test_finetuner': 'test the FineTuner to fine-tune a dynamics model and verify updated model outputs and replay buffer growth', 'test_visualizer': 'test the Visualizer to generate rollout video files for a TrajectoryOptimizerAgent policy', 'create_one_dim_tr_model': 'create a one-dimensional transition dynamics model from an OmegaConf config with given observation and action shapes', 'rollout_agent_trajectories': 'rollout agent trajectories in a PyBullet environment and store transitions into a replay buffer'}
```

## File: facebookresearch_mbrl-lib/tests/pybullet/test_util.py

Prompts

```
['test the DatasetEvaluator to generate prediction plots for each observation dimension', 'test the FineTuner to fine-tune a dynamics model and verify updated outputs', 'test the Visualizer to generate a rollout video of the agent policy', 'create a one-dimensional transition reward model from config and observation action shapes', 'create a replay buffer from config and populate it with agent rollout trajectories', 'rollout agent trajectories in a PyBullet environment and store transitions into a replay buffer', 'test that freezing a pybullet gym environment produces deterministic observations and rewards across steps', 'test that getting and setting environment state works correctly for pybullet gym environments', 'test that environment state can be transferred between two separate pybullet gym instances', 'test the recursive equality comparison function for numpy arrays, dicts, and scalars', 'test that two environment states are equal by comparing all elements except the unique file name']
```

Usage

```
{'test_freeze_pybullet_env': 'test that freezing a pybullet gym environment produces deterministic observations and rewards across steps', 'test_get_and_set_state': 'test that getting and setting environment state works correctly for pybullet gym environments', 'test_transfer_state_between_envs': 'test that environment state can be transferred between two separate pybullet gym instances', 'test_is_eq_comparison': 'test the recursive equality comparison function for numpy arrays, dicts, and scalars', 'test_state_eq_comparison': 'test that two environment states are equal by comparing all elements except the unique file name'}
```

