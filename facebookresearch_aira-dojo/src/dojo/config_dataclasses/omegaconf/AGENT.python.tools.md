# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/omegaconf/resolvers.py

Prompts

```
['register custom OmegaConf resolvers for experiment ID generation, time, torch version, and git commit ID', 'generate a unique experiment ID from a RunConfig using the generate_id OmegaConf resolver', 'get the current timestamp as a formatted string via the get_current_time OmegaConf resolver', 'get the installed PyTorch version string via the get_torch_version OmegaConf resolver', 'get the current git HEAD commit hash via the get_git_commit_id OmegaConf resolver']
```

Usage

```
{'register_omegaconf_resolvers': 'register custom OmegaConf resolvers for experiment ID generation, time, torch version, and git commit ID', 'generate_experiment_id': 'generate a unique experiment ID from a RunConfig using the generate_id OmegaConf resolver', 'get_current_time_resolver': 'get the current timestamp as a formatted string via the get_current_time OmegaConf resolver', 'get_torch_version_resolver': 'get the installed PyTorch version string via the get_torch_version OmegaConf resolver', 'get_git_commit_id_resolver': 'get the current git HEAD commit hash via the get_git_commit_id OmegaConf resolver'}
```

