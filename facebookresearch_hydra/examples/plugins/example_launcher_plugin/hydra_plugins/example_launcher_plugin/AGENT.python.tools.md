# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/plugins/example_launcher_plugin/hydra_plugins/example_launcher_plugin/example_launcher.py

Prompts

```
['create a LauncherConfig dataclass with foo and bar fields for Hydra launcher plugin settings', 'register a LauncherConfig with ConfigStore under the hydra/launcher group for plugin discovery', 'build an ExampleLauncher class extending Hydra Launcher to execute jobs locally with custom configuration', 'setup the ExampleLauncher with a HydraContext, TaskFunction, and DictConfig before launching jobs', 'launch a sequence of Hydra jobs with overrides using ExampleLauncher and return JobReturn results']
```

Usage

```
{'create_launcher_config': 'create a LauncherConfig dataclass with foo and bar fields for Hydra launcher plugin settings', 'register_launcher_config': 'register a LauncherConfig with ConfigStore under the hydra/launcher group for plugin discovery', 'build_example_launcher': 'build an ExampleLauncher class extending Hydra Launcher to execute jobs locally with custom configuration', 'setup_example_launcher': 'setup the ExampleLauncher with a HydraContext, TaskFunction, and DictConfig before launching jobs', 'launch_jobs': 'launch a sequence of Hydra jobs with overrides using ExampleLauncher and return JobReturn results'}
```

