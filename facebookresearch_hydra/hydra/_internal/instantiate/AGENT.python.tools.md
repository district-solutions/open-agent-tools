# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/hydra/_internal/instantiate/_instantiate2.py

Prompts

```
['instantiate a Python object from an OmegaConf config with a _target_ key and parameters', 'recursively instantiate nested OmegaConf nodes into Python objects using instantiate_node with recursive mode', "resolve a target string like 'torch.nn.Linear' into a callable using _resolve_target", 'call a target callable with extracted positional args and kwargs using _call_target', 'convert an OmegaConf node to a plain dict or list using _convert_node with ConvertMode']
```

Usage

```
{'instantiate_from_config': 'instantiate a Python object from an OmegaConf config with a _target_ key and parameters', 'instantiate_node_recursively': 'recursively instantiate nested OmegaConf nodes into Python objects using instantiate_node with recursive mode', 'resolve_target_callable': "resolve a target string like 'torch.nn.Linear' into a callable using _resolve_target", 'call_target_with_kwargs': 'call a target callable with extracted positional args and kwargs using _call_target', 'convert_node_to_container': 'convert an OmegaConf node to a plain dict or list using _convert_node with ConvertMode'}
```

