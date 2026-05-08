# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/experiment.py

Prompts

```
['run an Implicitron training experiment with a Hydra config YAML file and CLI overrides', 'run the Experiment class to initialize model, optimizer, dataloaders, and start the training loop', 'create an Experiment instance with a data source, model factory, optimizer factory, and training loop', 'dump the experiment config to a YAML file in the experiment directory using OmegaConf', 'setup environment variables for running on a FAIR cluster with submitit and SLURM', 'run the visualize_reconstruction function to generate fly-around videos from a trained Implicitron model checkpoint', 'run the main CLI entry point to visualize a reconstruction with command-line arguments for exp_dir and render_size', 'run the _get_config_from_experiment_directory function to load and merge an expconfig.yaml with Experiment defaults', 'review the visualize_reconstruction function which loads a model, sets up datasets, and renders fly-around videos per sequence', 'refactor the visualize_reconstruction function to support custom render_flyaround_kwargs or additional visdom configuration options']
```

Usage

```
{'run_experiment': 'run an Implicitron training experiment with a Hydra config YAML file and CLI overrides', 'run_Experiment_run': 'run the Experiment class to initialize model, optimizer, dataloaders, and start the training loop', 'create_Experiment': 'create an Experiment instance with a data source, model factory, optimizer factory, and training loop', 'dump_cfg': 'dump the experiment config to a YAML file in the experiment directory using OmegaConf', 'setup_envvars_for_cluster': 'setup environment variables for running on a FAIR cluster with submitit and SLURM'}
```

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/visualize_reconstruction.py

Prompts

```
['run an Implicitron training experiment with a Hydra config YAML file and CLI overrides', 'run the Experiment class to initialize model, optimizer, dataloaders, and start the training loop', 'create an Experiment instance with a data source, model factory, optimizer factory, and training loop', 'dump the experiment config to a YAML file in the experiment directory using OmegaConf', 'setup environment variables for running on a FAIR cluster with submitit and SLURM', 'run the visualize_reconstruction function to generate fly-around videos from a trained Implicitron model checkpoint', 'run the main CLI entry point to visualize a reconstruction with command-line arguments for exp_dir and render_size', 'run the _get_config_from_experiment_directory function to load and merge an expconfig.yaml with Experiment defaults', 'review the visualize_reconstruction function which loads a model, sets up datasets, and renders fly-around videos per sequence', 'refactor the visualize_reconstruction function to support custom render_flyaround_kwargs or additional visdom configuration options']
```

Usage

```
{'run_visualize_reconstruction': 'run the visualize_reconstruction function to generate fly-around videos from a trained Implicitron model checkpoint', 'run_main_cli': 'run the main CLI entry point to visualize a reconstruction with command-line arguments for exp_dir and render_size', 'run_get_config': 'run the _get_config_from_experiment_directory function to load and merge an expconfig.yaml with Experiment defaults', 'review_visualize_reconstruction': 'review the visualize_reconstruction function which loads a model, sets up datasets, and renders fly-around videos per sequence', 'refactor_visualize_reconstruction': 'refactor the visualize_reconstruction function to support custom render_flyaround_kwargs or additional visdom configuration options'}
```

