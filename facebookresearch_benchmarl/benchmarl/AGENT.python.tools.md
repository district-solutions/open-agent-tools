# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/benchmarl/eval_results.py

Prompts

```
['get the marl-eval input dictionary by merging all json files from a hydra multirun folder', 'load and merge multiple json files into a single dictionary with optional output file', 'process and normalize metrics in raw benchmark data using the data processing pipeline', 'create environment comparison and sample efficiency matrices from processed benchmark data', 'plot performance profiles comparing algorithms across environments using the comparison matrix', 'create an Experiment from a Hydra DictConfig with algorithm, task, model, and critic model configs', 'reload a BenchMARL Experiment from a checkpoint file using the .hydra metadata folder', 'load a TaskClass from a Hydra DictConfig given the task name string', 'load a ModelConfig from a Hydra DictConfig supporting single or SequenceModelConfig with layers', 'load an AlgorithmConfig from a Hydra DictConfig for the reinforcement learning algorithm', 'run a benchmarl experiment with a specified algorithm and task using hydra config', 'run a benchmarl experiment with algorithm mappo and task vmas/balance', 'review the hydra_experiment function that loads and runs a benchmarl experiment', 'summarize the hydra_experiment function that prints config and runs an experiment', 'set the random seed for PyTorch, NumPy, and Python using seed_everything with an integer seed value', 'use the local_seed context manager to temporarily isolate random state changes in a code block', 'read a YAML config file into a dictionary and remove the defaults key using _read_yaml_config', 'dynamically import a class from a dotted module path string using _class_from_name', 'add RNN-specific transforms like InitTracker and TensorDictPrimer to a TorchRL environment using _add_rnn_transforms']
```

Usage

```
{'get_raw_dict_from_multirun_folder': 'get the marl-eval input dictionary by merging all json files from a hydra multirun folder', 'load_and_merge_json_dicts': 'load and merge multiple json files into a single dictionary with optional output file', 'Plotting_process_data': 'process and normalize metrics in raw benchmark data using the data processing pipeline', 'Plotting_create_matrices': 'create environment comparison and sample efficiency matrices from processed benchmark data', 'Plotting_performance_profile_figure': 'plot performance profiles comparing algorithms across environments using the comparison matrix'}
```

## File: facebookresearch_benchmarl/benchmarl/hydra_config.py

Prompts

```
['get the marl-eval input dictionary by merging all json files from a hydra multirun folder', 'load and merge multiple json files into a single dictionary with optional output file', 'process and normalize metrics in raw benchmark data using the data processing pipeline', 'create environment comparison and sample efficiency matrices from processed benchmark data', 'plot performance profiles comparing algorithms across environments using the comparison matrix', 'create an Experiment from a Hydra DictConfig with algorithm, task, model, and critic model configs', 'reload a BenchMARL Experiment from a checkpoint file using the .hydra metadata folder', 'load a TaskClass from a Hydra DictConfig given the task name string', 'load a ModelConfig from a Hydra DictConfig supporting single or SequenceModelConfig with layers', 'load an AlgorithmConfig from a Hydra DictConfig for the reinforcement learning algorithm', 'run a benchmarl experiment with a specified algorithm and task using hydra config', 'run a benchmarl experiment with algorithm mappo and task vmas/balance', 'review the hydra_experiment function that loads and runs a benchmarl experiment', 'summarize the hydra_experiment function that prints config and runs an experiment', 'set the random seed for PyTorch, NumPy, and Python using seed_everything with an integer seed value', 'use the local_seed context manager to temporarily isolate random state changes in a code block', 'read a YAML config file into a dictionary and remove the defaults key using _read_yaml_config', 'dynamically import a class from a dotted module path string using _class_from_name', 'add RNN-specific transforms like InitTracker and TensorDictPrimer to a TorchRL environment using _add_rnn_transforms']
```

Usage

```
{'load_experiment_from_hydra': 'create an Experiment from a Hydra DictConfig with algorithm, task, model, and critic model configs', 'reload_experiment_from_file': 'reload a BenchMARL Experiment from a checkpoint file using the .hydra metadata folder', 'load_task_config_from_hydra': 'load a TaskClass from a Hydra DictConfig given the task name string', 'load_model_config_from_hydra': 'load a ModelConfig from a Hydra DictConfig supporting single or SequenceModelConfig with layers', 'load_algorithm_config_from_hydra': 'load an AlgorithmConfig from a Hydra DictConfig for the reinforcement learning algorithm'}
```

## File: facebookresearch_benchmarl/benchmarl/run.py

Prompts

```
['get the marl-eval input dictionary by merging all json files from a hydra multirun folder', 'load and merge multiple json files into a single dictionary with optional output file', 'process and normalize metrics in raw benchmark data using the data processing pipeline', 'create environment comparison and sample efficiency matrices from processed benchmark data', 'plot performance profiles comparing algorithms across environments using the comparison matrix', 'create an Experiment from a Hydra DictConfig with algorithm, task, model, and critic model configs', 'reload a BenchMARL Experiment from a checkpoint file using the .hydra metadata folder', 'load a TaskClass from a Hydra DictConfig given the task name string', 'load a ModelConfig from a Hydra DictConfig supporting single or SequenceModelConfig with layers', 'load an AlgorithmConfig from a Hydra DictConfig for the reinforcement learning algorithm', 'run a benchmarl experiment with a specified algorithm and task using hydra config', 'run a benchmarl experiment with algorithm mappo and task vmas/balance', 'review the hydra_experiment function that loads and runs a benchmarl experiment', 'summarize the hydra_experiment function that prints config and runs an experiment', 'set the random seed for PyTorch, NumPy, and Python using seed_everything with an integer seed value', 'use the local_seed context manager to temporarily isolate random state changes in a code block', 'read a YAML config file into a dictionary and remove the defaults key using _read_yaml_config', 'dynamically import a class from a dotted module path string using _class_from_name', 'add RNN-specific transforms like InitTracker and TensorDictPrimer to a TorchRL environment using _add_rnn_transforms']
```

Usage

```
{'run_experiment': 'run a benchmarl experiment with a specified algorithm and task using hydra config', 'run_mappo_balance': 'run a benchmarl experiment with algorithm mappo and task vmas/balance', 'load_experiment_from_hydra': 'load an experiment from hydra config with a specified task name', 'review_hydra_experiment': 'review the hydra_experiment function that loads and runs a benchmarl experiment', 'summarize_hydra_experiment': 'summarize the hydra_experiment function that prints config and runs an experiment'}
```

## File: facebookresearch_benchmarl/benchmarl/utils.py

Prompts

```
['get the marl-eval input dictionary by merging all json files from a hydra multirun folder', 'load and merge multiple json files into a single dictionary with optional output file', 'process and normalize metrics in raw benchmark data using the data processing pipeline', 'create environment comparison and sample efficiency matrices from processed benchmark data', 'plot performance profiles comparing algorithms across environments using the comparison matrix', 'create an Experiment from a Hydra DictConfig with algorithm, task, model, and critic model configs', 'reload a BenchMARL Experiment from a checkpoint file using the .hydra metadata folder', 'load a TaskClass from a Hydra DictConfig given the task name string', 'load a ModelConfig from a Hydra DictConfig supporting single or SequenceModelConfig with layers', 'load an AlgorithmConfig from a Hydra DictConfig for the reinforcement learning algorithm', 'run a benchmarl experiment with a specified algorithm and task using hydra config', 'run a benchmarl experiment with algorithm mappo and task vmas/balance', 'review the hydra_experiment function that loads and runs a benchmarl experiment', 'summarize the hydra_experiment function that prints config and runs an experiment', 'set the random seed for PyTorch, NumPy, and Python using seed_everything with an integer seed value', 'use the local_seed context manager to temporarily isolate random state changes in a code block', 'read a YAML config file into a dictionary and remove the defaults key using _read_yaml_config', 'dynamically import a class from a dotted module path string using _class_from_name', 'add RNN-specific transforms like InitTracker and TensorDictPrimer to a TorchRL environment using _add_rnn_transforms']
```

Usage

```
{'seed_everything': 'set the random seed for PyTorch, NumPy, and Python using seed_everything with an integer seed value', 'local_seed_context': 'use the local_seed context manager to temporarily isolate random state changes in a code block', 'read_yaml_config': 'read a YAML config file into a dictionary and remove the defaults key using _read_yaml_config', 'class_from_name': 'dynamically import a class from a dotted module path string using _class_from_name', 'add_rnn_transforms': 'add RNN-specific transforms like InitTracker and TensorDictPrimer to a TorchRL environment using _add_rnn_transforms'}
```

