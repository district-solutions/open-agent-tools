# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/aira_core/config/base.py

Prompts

```
['create a dataclass that inherits from BaseConfig to define a new configuration schema', 'validate a BaseConfig instance and all nested config fields by calling the validate method', 'configure a BaseConfig instance and all nested config fields for debug mode recursively', 'generate a SHA-224 hash of a BaseConfig instance excluding fields marked with exclude_from_hash metadata', 'define fields to exclude from hashing by setting exclude_from_hash in the dataclass field metadata']
```

Usage

```
{'create_config_subclass': 'create a dataclass that inherits from BaseConfig to define a new configuration schema', 'validate_config': 'validate a BaseConfig instance and all nested config fields by calling the validate method', 'configure_for_debug': 'configure a BaseConfig instance and all nested config fields for debug mode recursively', 'hash_config': 'generate a SHA-224 hash of a BaseConfig instance excluding fields marked with exclude_from_hash metadata', 'exclude_fields_from_hash': 'define fields to exclude from hashing by setting exclude_from_hash in the dataclass field metadata'}
```

