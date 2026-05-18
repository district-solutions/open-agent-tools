# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/examples/imitation_learning/filters.py

Prompts

```
['create a MeanStdFilter instance with a given input shape to whiten tensor inputs', 'whiten a batch of tensors by subtracting the running mean and dividing by the running std', 'push a single sample into the MeanStdFilter to update the running mean and variance statistics', 'toggle the MeanStdFilter between training mode to update stats and eval mode to freeze stats', 'inspect the running mean, variance, std, sample count, and shape of a MeanStdFilter', 'build an ImitationAgent with continuous actions using a config dict specifying n_inputs, hidden_layers, mean_scalings, and std_devs', 'build an ImitationAgent with discrete actions using a config dict specifying actions_discretizations and actions_bounds', 'run the ImitationAgent forward pass on a batch of state tensors to sample actions from the learned distribution', 'run the ImitationAgent log_prob method to compute the log probability of expert ground truth actions given input states', 'run the ImitationAgent dist method to construct a probability distribution from a batch of state tensor inputs', 'run the replay video script to generate MP4 rollouts of a trained Nocturne imitation learning controller', 'review the local policy function that converts numpy state arrays to torch tensors and calls model forward', 'summarize the simulation loop that steps through scenarios collecting ego state and visible state for each vehicle', 'refactor the hardcoded MODEL_PATH and CONFIG_PATH to accept command line arguments for flexible model selection', 'review the ffmpeg subprocess call that stacks policy and expert rollout videos side by side with hstack', 'run the imitation learning training script with hydra config to train a behavioral cloning model', 'review the set_seed_everywhere function that sets random seeds for torch, cuda, numpy, and random modules', 'refactor the main training loop to support custom loss functions or additional metrics logging', 'test the ImitationAgent model configuration with discrete and continuous action space settings', 'summarize how the WaymoDataset and DataLoader are configured for imitation learning training']
```

Usage

```
{'create_mean_std_filter': 'create a MeanStdFilter instance with a given input shape to whiten tensor inputs', 'whiten_tensor_with_forward': 'whiten a batch of tensors by subtracting the running mean and dividing by the running std', 'push_sample_to_filter': 'push a single sample into the MeanStdFilter to update the running mean and variance statistics', 'toggle_tracking_mode': 'toggle the MeanStdFilter between training mode to update stats and eval mode to freeze stats', 'inspect_filter_statistics': 'inspect the running mean, variance, std, sample count, and shape of a MeanStdFilter'}
```

## File: facebookresearch_nocturne/examples/imitation_learning/model.py

Prompts

```
['create a MeanStdFilter instance with a given input shape to whiten tensor inputs', 'whiten a batch of tensors by subtracting the running mean and dividing by the running std', 'push a single sample into the MeanStdFilter to update the running mean and variance statistics', 'toggle the MeanStdFilter between training mode to update stats and eval mode to freeze stats', 'inspect the running mean, variance, std, sample count, and shape of a MeanStdFilter', 'build an ImitationAgent with continuous actions using a config dict specifying n_inputs, hidden_layers, mean_scalings, and std_devs', 'build an ImitationAgent with discrete actions using a config dict specifying actions_discretizations and actions_bounds', 'run the ImitationAgent forward pass on a batch of state tensors to sample actions from the learned distribution', 'run the ImitationAgent log_prob method to compute the log probability of expert ground truth actions given input states', 'run the ImitationAgent dist method to construct a probability distribution from a batch of state tensor inputs', 'run the replay video script to generate MP4 rollouts of a trained Nocturne imitation learning controller', 'review the local policy function that converts numpy state arrays to torch tensors and calls model forward', 'summarize the simulation loop that steps through scenarios collecting ego state and visible state for each vehicle', 'refactor the hardcoded MODEL_PATH and CONFIG_PATH to accept command line arguments for flexible model selection', 'review the ffmpeg subprocess call that stacks policy and expert rollout videos side by side with hstack', 'run the imitation learning training script with hydra config to train a behavioral cloning model', 'review the set_seed_everywhere function that sets random seeds for torch, cuda, numpy, and random modules', 'refactor the main training loop to support custom loss functions or additional metrics logging', 'test the ImitationAgent model configuration with discrete and continuous action space settings', 'summarize how the WaymoDataset and DataLoader are configured for imitation learning training']
```

Usage

```
{'build_ImitationAgent_continuous': 'build an ImitationAgent with continuous actions using a config dict specifying n_inputs, hidden_layers, mean_scalings, and std_devs', 'build_ImitationAgent_discrete': 'build an ImitationAgent with discrete actions using a config dict specifying actions_discretizations and actions_bounds', 'run_ImitationAgent_forward': 'run the ImitationAgent forward pass on a batch of state tensors to sample actions from the learned distribution', 'run_ImitationAgent_log_prob': 'run the ImitationAgent log_prob method to compute the log probability of expert ground truth actions given input states', 'run_ImitationAgent_dist': 'run the ImitationAgent dist method to construct a probability distribution from a batch of state tensor inputs'}
```

## File: facebookresearch_nocturne/examples/imitation_learning/replay_video.py

Prompts

```
['create a MeanStdFilter instance with a given input shape to whiten tensor inputs', 'whiten a batch of tensors by subtracting the running mean and dividing by the running std', 'push a single sample into the MeanStdFilter to update the running mean and variance statistics', 'toggle the MeanStdFilter between training mode to update stats and eval mode to freeze stats', 'inspect the running mean, variance, std, sample count, and shape of a MeanStdFilter', 'build an ImitationAgent with continuous actions using a config dict specifying n_inputs, hidden_layers, mean_scalings, and std_devs', 'build an ImitationAgent with discrete actions using a config dict specifying actions_discretizations and actions_bounds', 'run the ImitationAgent forward pass on a batch of state tensors to sample actions from the learned distribution', 'run the ImitationAgent log_prob method to compute the log probability of expert ground truth actions given input states', 'run the ImitationAgent dist method to construct a probability distribution from a batch of state tensor inputs', 'run the replay video script to generate MP4 rollouts of a trained Nocturne imitation learning controller', 'review the local policy function that converts numpy state arrays to torch tensors and calls model forward', 'summarize the simulation loop that steps through scenarios collecting ego state and visible state for each vehicle', 'refactor the hardcoded MODEL_PATH and CONFIG_PATH to accept command line arguments for flexible model selection', 'review the ffmpeg subprocess call that stacks policy and expert rollout videos side by side with hstack', 'run the imitation learning training script with hydra config to train a behavioral cloning model', 'review the set_seed_everywhere function that sets random seeds for torch, cuda, numpy, and random modules', 'refactor the main training loop to support custom loss functions or additional metrics logging', 'test the ImitationAgent model configuration with discrete and continuous action space settings', 'summarize how the WaymoDataset and DataLoader are configured for imitation learning training']
```

Usage

```
{'run_replay_video': 'run the replay video script to generate MP4 rollouts of a trained Nocturne imitation learning controller', 'review_policy_function': 'review the local policy function that converts numpy state arrays to torch tensors and calls model forward', 'summarize_simulation_loop': 'summarize the simulation loop that steps through scenarios collecting ego state and visible state for each vehicle', 'refactor_model_path': 'refactor the hardcoded MODEL_PATH and CONFIG_PATH to accept command line arguments for flexible model selection', 'review_ffmpeg_stacking': 'review the ffmpeg subprocess call that stacks policy and expert rollout videos side by side with hstack'}
```

## File: facebookresearch_nocturne/examples/imitation_learning/train.py

Prompts

```
['create a MeanStdFilter instance with a given input shape to whiten tensor inputs', 'whiten a batch of tensors by subtracting the running mean and dividing by the running std', 'push a single sample into the MeanStdFilter to update the running mean and variance statistics', 'toggle the MeanStdFilter between training mode to update stats and eval mode to freeze stats', 'inspect the running mean, variance, std, sample count, and shape of a MeanStdFilter', 'build an ImitationAgent with continuous actions using a config dict specifying n_inputs, hidden_layers, mean_scalings, and std_devs', 'build an ImitationAgent with discrete actions using a config dict specifying actions_discretizations and actions_bounds', 'run the ImitationAgent forward pass on a batch of state tensors to sample actions from the learned distribution', 'run the ImitationAgent log_prob method to compute the log probability of expert ground truth actions given input states', 'run the ImitationAgent dist method to construct a probability distribution from a batch of state tensor inputs', 'run the replay video script to generate MP4 rollouts of a trained Nocturne imitation learning controller', 'review the local policy function that converts numpy state arrays to torch tensors and calls model forward', 'summarize the simulation loop that steps through scenarios collecting ego state and visible state for each vehicle', 'refactor the hardcoded MODEL_PATH and CONFIG_PATH to accept command line arguments for flexible model selection', 'review the ffmpeg subprocess call that stacks policy and expert rollout videos side by side with hstack', 'run the imitation learning training script with hydra config to train a behavioral cloning model', 'review the set_seed_everywhere function that sets random seeds for torch, cuda, numpy, and random modules', 'refactor the main training loop to support custom loss functions or additional metrics logging', 'test the ImitationAgent model configuration with discrete and continuous action space settings', 'summarize how the WaymoDataset and DataLoader are configured for imitation learning training']
```

Usage

```
{'run_imitation_learning_training': 'run the imitation learning training script with hydra config to train a behavioral cloning model', 'review_set_seed_everywhere': 'review the set_seed_everywhere function that sets random seeds for torch, cuda, numpy, and random modules', 'refactor_main_training_loop': 'refactor the main training loop to support custom loss functions or additional metrics logging', 'test_imitation_agent_model': 'test the ImitationAgent model configuration with discrete and continuous action space settings', 'summarize_waymo_dataset_loading': 'summarize how the WaymoDataset and DataLoader are configured for imitation learning training'}
```

