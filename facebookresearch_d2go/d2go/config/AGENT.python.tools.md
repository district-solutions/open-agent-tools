# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/config/config.py

Prompts

```
['load a full D2Go config from a YAML file with base inheritance and defaults merged', 'auto scale a D2Go solver config to a new world size using registered scaling methods', 'merge command-line style config overrides into a CfgNode from a dot-keyed string list', 'recursively convert a D2Go CfgNode config object into a plain Python dictionary', 'cast a detectron2 CfgNode instance into a D2Go CfgNode preserving all internal fields', 'flatten a nested configuration dictionary into a single-layer dict with dot-separated keys', 'read a value from a nested config dict using a dot-separated flattened key path', 'convert a configuration dictionary into a flat list of alternating key and value strings', 'generate a side-by-side comparison table showing differences between two configuration dicts', 'compute the diff between two CfgNode configs and return only the changed keys and values']
```

Usage

```
{'load_full_config_from_file': 'load a full D2Go config from a YAML file with base inheritance and defaults merged', 'auto_scale_world_size': 'auto scale a D2Go solver config to a new world size using registered scaling methods', 'CfgNode_merge_from_list': 'merge command-line style config overrides into a CfgNode from a dot-keyed string list', 'convert_cfg_to_dict': 'recursively convert a D2Go CfgNode config object into a plain Python dictionary', 'CfgNode_cast_from_other_class': 'cast a detectron2 CfgNode instance into a D2Go CfgNode preserving all internal fields'}
```

## File: facebookresearch_d2go/d2go/config/utils.py

Prompts

```
['load a full D2Go config from a YAML file with base inheritance and defaults merged', 'auto scale a D2Go solver config to a new world size using registered scaling methods', 'merge command-line style config overrides into a CfgNode from a dot-keyed string list', 'recursively convert a D2Go CfgNode config object into a plain Python dictionary', 'cast a detectron2 CfgNode instance into a D2Go CfgNode preserving all internal fields', 'flatten a nested configuration dictionary into a single-layer dict with dot-separated keys', 'read a value from a nested config dict using a dot-separated flattened key path', 'convert a configuration dictionary into a flat list of alternating key and value strings', 'generate a side-by-side comparison table showing differences between two configuration dicts', 'compute the diff between two CfgNode configs and return only the changed keys and values']
```

Usage

```
{'flatten_config_dict': 'flatten a nested configuration dictionary into a single-layer dict with dot-separated keys', 'get_from_flattened_config_dict': 'read a value from a nested config dict using a dot-separated flattened key path', 'config_dict_to_list_str': 'convert a configuration dictionary into a flat list of alternating key and value strings', 'get_cfg_diff_table': 'generate a side-by-side comparison table showing differences between two configuration dicts', 'get_diff_cfg': 'compute the diff between two CfgNode configs and return only the changed keys and values'}
```

