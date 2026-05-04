# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/benchmarl/experiment/callback.py

Prompts

```
['create a custom Callback subclass that overrides on_batch_collected to log collected data batches', 'implement the on_train_step method in a Callback subclass to return loss values as a TensorDict', 'use CallbackNotifier to register multiple Callback instances and broadcast experiment lifecycle events to all of them', 'override the on_setup method in a Callback subclass to initialize resources when the experiment is set up', 'implement on_state_dict and on_load_state_dict in a Callback subclass to save and restore custom state', 'run a BenchMARL Experiment with a task, algorithm config, model config, seed, and experiment config', 'reload a BenchMARL Experiment from a saved checkpoint file using Experiment.reload_from_file', 'create an ExperimentConfig by loading parameters from a YAML file using ExperimentConfig.get_from_yaml', 'run a single evaluation loop on a BenchMARL Experiment to log results without training', 'save the BenchMARL Experiment state dict including losses, buffers, and collector to a checkpoint file', 'create a Logger instance to log multi-agent RL experiment metrics to TensorBoard or W&B', 'log hyperparameters to all configured loggers with automatic flattening for TensorBoard', 'log collection step rewards and episode metrics from a TensorDict batch to all loggers', 'log evaluation rollouts with episode rewards, video frames, and JSON metrics for marl-eval reporting', 'create a JsonWriter to write marl-eval compliant JSON metric files for experiment reporting']
```

Usage

```
{'create_custom_callback': 'create a custom Callback subclass that overrides on_batch_collected to log collected data batches', 'implement_on_train_step': 'implement the on_train_step method in a Callback subclass to return loss values as a TensorDict', 'use_callback_notifier': 'use CallbackNotifier to register multiple Callback instances and broadcast experiment lifecycle events to all of them', 'override_on_setup': 'override the on_setup method in a Callback subclass to initialize resources when the experiment is set up', 'handle_state_dict_callbacks': 'implement on_state_dict and on_load_state_dict in a Callback subclass to save and restore custom state'}
```

## File: facebookresearch_benchmarl/benchmarl/experiment/experiment.py

Prompts

```
['create a custom Callback subclass that overrides on_batch_collected to log collected data batches', 'implement the on_train_step method in a Callback subclass to return loss values as a TensorDict', 'use CallbackNotifier to register multiple Callback instances and broadcast experiment lifecycle events to all of them', 'override the on_setup method in a Callback subclass to initialize resources when the experiment is set up', 'implement on_state_dict and on_load_state_dict in a Callback subclass to save and restore custom state', 'run a BenchMARL Experiment with a task, algorithm config, model config, seed, and experiment config', 'reload a BenchMARL Experiment from a saved checkpoint file using Experiment.reload_from_file', 'create an ExperimentConfig by loading parameters from a YAML file using ExperimentConfig.get_from_yaml', 'run a single evaluation loop on a BenchMARL Experiment to log results without training', 'save the BenchMARL Experiment state dict including losses, buffers, and collector to a checkpoint file', 'create a Logger instance to log multi-agent RL experiment metrics to TensorBoard or W&B', 'log hyperparameters to all configured loggers with automatic flattening for TensorBoard', 'log collection step rewards and episode metrics from a TensorDict batch to all loggers', 'log evaluation rollouts with episode rewards, video frames, and JSON metrics for marl-eval reporting', 'create a JsonWriter to write marl-eval compliant JSON metric files for experiment reporting']
```

Usage

```
{'run_experiment': 'run a BenchMARL Experiment with a task, algorithm config, model config, seed, and experiment config', 'reload_experiment_from_checkpoint': 'reload a BenchMARL Experiment from a saved checkpoint file using Experiment.reload_from_file', 'create_experiment_config_from_yaml': 'create an ExperimentConfig by loading parameters from a YAML file using ExperimentConfig.get_from_yaml', 'evaluate_experiment': 'run a single evaluation loop on a BenchMARL Experiment to log results without training', 'save_experiment_state': 'save the BenchMARL Experiment state dict including losses, buffers, and collector to a checkpoint file'}
```

## File: facebookresearch_benchmarl/benchmarl/experiment/logger.py

Prompts

```
['create a custom Callback subclass that overrides on_batch_collected to log collected data batches', 'implement the on_train_step method in a Callback subclass to return loss values as a TensorDict', 'use CallbackNotifier to register multiple Callback instances and broadcast experiment lifecycle events to all of them', 'override the on_setup method in a Callback subclass to initialize resources when the experiment is set up', 'implement on_state_dict and on_load_state_dict in a Callback subclass to save and restore custom state', 'run a BenchMARL Experiment with a task, algorithm config, model config, seed, and experiment config', 'reload a BenchMARL Experiment from a saved checkpoint file using Experiment.reload_from_file', 'create an ExperimentConfig by loading parameters from a YAML file using ExperimentConfig.get_from_yaml', 'run a single evaluation loop on a BenchMARL Experiment to log results without training', 'save the BenchMARL Experiment state dict including losses, buffers, and collector to a checkpoint file', 'create a Logger instance to log multi-agent RL experiment metrics to TensorBoard or W&B', 'log hyperparameters to all configured loggers with automatic flattening for TensorBoard', 'log collection step rewards and episode metrics from a TensorDict batch to all loggers', 'log evaluation rollouts with episode rewards, video frames, and JSON metrics for marl-eval reporting', 'create a JsonWriter to write marl-eval compliant JSON metric files for experiment reporting']
```

Usage

```
{'create_Logger': 'create a Logger instance to log multi-agent RL experiment metrics to TensorBoard or W&B', 'log_hparams': 'log hyperparameters to all configured loggers with automatic flattening for TensorBoard', 'log_collection': 'log collection step rewards and episode metrics from a TensorDict batch to all loggers', 'log_evaluation': 'log evaluation rollouts with episode rewards, video frames, and JSON metrics for marl-eval reporting', 'create_JsonWriter': 'create a JsonWriter to write marl-eval compliant JSON metric files for experiment reporting'}
```

