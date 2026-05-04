# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/option_keyboard/gpe_gpi_experiments/eval_keyboard_fig5.py

Prompts

```
['run the eval_keyboard_fig5 script to evaluate trained keyboard models across multiple weight configurations', 'evaluate a keyboard model by running episodes with different weight vectors and collecting returns', 'generate raw data for polar plots visualizing how well a keyboard covers the weight space', 'run an episode using the regressed agent with a keyboard-wrapped scavenger environment', 'export evaluation returns to a CSV file with angle, return value, and keyboard index columns', 'create a DQN Agent instance with batch size, optimizer name, optimizer kwargs, and initial cumulant weight', 'call step on the Agent to select random actions during training or return regressed weights during evaluation', 'call update on the Agent with environment transitions to accumulate replay and trigger gradient descent when batch is full', 'call get_logs on the Agent to retrieve the current regressed cumulant weight values as a dictionary', 'review the Agent class that regresses cumulant weights via TensorFlow gradient descent to predict rewards', 'run the phi model training script with absl flags for num_phis, learning_rate, and export_path', 'create a function that collects random action experience from a scavenger environment and returns observations, actions, and rewards', 'build a Sonnet MLP-based PhiModel that maps arena observations and actions to phi values with configurable dimensionality', 'train a linear mapping from learned phis to auxiliary task rewards using Adam optimizer with weight normalization', 'export the trained PhiModel to a specified path using SmartModuleExport after completing training steps']
```

Usage

```
{'run_keyboard_evaluation': 'run the eval_keyboard_fig5 script to evaluate trained keyboard models across multiple weight configurations', 'evaluate_keyboard_function': 'evaluate a keyboard model by running episodes with different weight vectors and collecting returns', 'generate_polar_plot_data': 'generate raw data for polar plots visualizing how well a keyboard covers the weight space', 'run_episode_with_agent': 'run an episode using the regressed agent with a keyboard-wrapped scavenger environment', 'export_returns_to_csv': 'export evaluation returns to a CSV file with angle, return value, and keyboard index columns'}
```

## File: google-deepmind_deepmind-research/option_keyboard/gpe_gpi_experiments/regressed_agent.py

Prompts

```
['run the eval_keyboard_fig5 script to evaluate trained keyboard models across multiple weight configurations', 'evaluate a keyboard model by running episodes with different weight vectors and collecting returns', 'generate raw data for polar plots visualizing how well a keyboard covers the weight space', 'run an episode using the regressed agent with a keyboard-wrapped scavenger environment', 'export evaluation returns to a CSV file with angle, return value, and keyboard index columns', 'create a DQN Agent instance with batch size, optimizer name, optimizer kwargs, and initial cumulant weight', 'call step on the Agent to select random actions during training or return regressed weights during evaluation', 'call update on the Agent with environment transitions to accumulate replay and trigger gradient descent when batch is full', 'call get_logs on the Agent to retrieve the current regressed cumulant weight values as a dictionary', 'review the Agent class that regresses cumulant weights via TensorFlow gradient descent to predict rewards', 'run the phi model training script with absl flags for num_phis, learning_rate, and export_path', 'create a function that collects random action experience from a scavenger environment and returns observations, actions, and rewards', 'build a Sonnet MLP-based PhiModel that maps arena observations and actions to phi values with configurable dimensionality', 'train a linear mapping from learned phis to auxiliary task rewards using Adam optimizer with weight normalization', 'export the trained PhiModel to a specified path using SmartModuleExport after completing training steps']
```

Usage

```
{'create_agent': 'create a DQN Agent instance with batch size, optimizer name, optimizer kwargs, and initial cumulant weight', 'step_agent': 'call step on the Agent to select random actions during training or return regressed weights during evaluation', 'update_agent': 'call update on the Agent with environment transitions to accumulate replay and trigger gradient descent when batch is full', 'get_logs_agent': 'call get_logs on the Agent to retrieve the current regressed cumulant weight values as a dictionary', 'review_agent_class': 'review the Agent class that regresses cumulant weights via TensorFlow gradient descent to predict rewards'}
```

## File: google-deepmind_deepmind-research/option_keyboard/gpe_gpi_experiments/train_phi_model.py

Prompts

```
['run the eval_keyboard_fig5 script to evaluate trained keyboard models across multiple weight configurations', 'evaluate a keyboard model by running episodes with different weight vectors and collecting returns', 'generate raw data for polar plots visualizing how well a keyboard covers the weight space', 'run an episode using the regressed agent with a keyboard-wrapped scavenger environment', 'export evaluation returns to a CSV file with angle, return value, and keyboard index columns', 'create a DQN Agent instance with batch size, optimizer name, optimizer kwargs, and initial cumulant weight', 'call step on the Agent to select random actions during training or return regressed weights during evaluation', 'call update on the Agent with environment transitions to accumulate replay and trigger gradient descent when batch is full', 'call get_logs on the Agent to retrieve the current regressed cumulant weight values as a dictionary', 'review the Agent class that regresses cumulant weights via TensorFlow gradient descent to predict rewards', 'run the phi model training script with absl flags for num_phis, learning_rate, and export_path', 'create a function that collects random action experience from a scavenger environment and returns observations, actions, and rewards', 'build a Sonnet MLP-based PhiModel that maps arena observations and actions to phi values with configurable dimensionality', 'train a linear mapping from learned phis to auxiliary task rewards using Adam optimizer with weight normalization', 'export the trained PhiModel to a specified path using SmartModuleExport after completing training steps']
```

Usage

```
{'run_train_phi_model': 'run the phi model training script with absl flags for num_phis, learning_rate, and export_path', 'collect_experience_scavenger_env': 'create a function that collects random action experience from a scavenger environment and returns observations, actions, and rewards', 'build_phimodel_network': 'build a Sonnet MLP-based PhiModel that maps arena observations and actions to phi values with configurable dimensionality', 'train_phis_to_rewards': 'train a linear mapping from learned phis to auxiliary task rewards using Adam optimizer with weight normalization', 'export_trained_phi_model': 'export the trained PhiModel to a specified path using SmartModuleExport after completing training steps'}
```

