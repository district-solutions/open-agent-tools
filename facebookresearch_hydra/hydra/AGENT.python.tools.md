# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/hydra/compose.py

Prompts

```
['compose a Hydra config from a YAML file name with a list of override strings', 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose a Hydra config using default settings with no config name or overrides', 'review the compose function to understand how it initializes GlobalHydra and calls compose_config', 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility', 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor a Hydra decorated task function to use a different config_path or version_base', 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str', 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get the current Hydra version_base from the VersionBase singleton instance', 'check if the current version_base is at least a specified minimum version string', 'parse a version string and extract only the major and minor components', 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning']
```

Usage

```
{'compose_config_with_overrides': 'compose a Hydra config from a YAML file name with a list of override strings', 'compose_config_without_hydra_node': 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose_config_with_hydra_node': 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose_config_default': 'compose a Hydra config using default settings with no config name or overrides', 'review_compose_function': 'review the compose function to understand how it initializes GlobalHydra and calls compose_config'}
```

## File: facebookresearch_hydra/hydra/initialize.py

Prompts

```
['compose a Hydra config from a YAML file name with a list of override strings', 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose a Hydra config using default settings with no config name or overrides', 'review the compose function to understand how it initializes GlobalHydra and calls compose_config', 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility', 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor a Hydra decorated task function to use a different config_path or version_base', 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str', 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get the current Hydra version_base from the VersionBase singleton instance', 'check if the current version_base is at least a specified minimum version string', 'parse a version string and extract only the major and minor components', 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning']
```

Usage

```
{'initialize_hydra_with_config_path': 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize_hydra_config_module': 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize_hydra_config_dir': 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup_and_restore_global_hydra': 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review_initialize_version_base': 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility'}
```

## File: facebookresearch_hydra/hydra/main.py

Prompts

```
['compose a Hydra config from a YAML file name with a list of override strings', 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose a Hydra config using default settings with no config name or overrides', 'review the compose function to understand how it initializes GlobalHydra and calls compose_config', 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility', 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor a Hydra decorated task function to use a different config_path or version_base', 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str', 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get the current Hydra version_base from the VersionBase singleton instance', 'check if the current version_base is at least a specified minimum version string', 'parse a version string and extract only the major and minor components', 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning']
```

Usage

```
{'run_hydra_task': 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create_hydra_main_decorator': 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun_hydra_config': 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review_main_decorator': 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor_hydra_task_function': 'refactor a Hydra decorated task function to use a different config_path or version_base'}
```

## File: facebookresearch_hydra/hydra/utils.py

Prompts

```
['compose a Hydra config from a YAML file name with a list of override strings', 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose a Hydra config using default settings with no config name or overrides', 'review the compose function to understand how it initializes GlobalHydra and calls compose_config', 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility', 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor a Hydra decorated task function to use a different config_path or version_base', 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str', 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get the current Hydra version_base from the VersionBase singleton instance', 'check if the current version_base is at least a specified minimum version string', 'parse a version string and extract only the major and minor components', 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning']
```

Usage

```
{'get_class_by_dotpath': 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get_method_by_dotpath': 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get_object_by_dotpath': 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert_path_to_absolute': 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert_object_to_hydra_override_string': 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str'}
```

## File: facebookresearch_hydra/hydra/version.py

Prompts

```
['compose a Hydra config from a YAML file name with a list of override strings', 'compose a Hydra config that excludes the hydra node from the returned DictConfig', 'compose a Hydra config that includes the hydra node in the returned DictConfig', 'compose a Hydra config using default settings with no config name or overrides', 'review the compose function to understand how it initializes GlobalHydra and calls compose_config', 'initialize Hydra with a relative config_path using the initialize context manager', 'initialize Hydra with an importable config module name using initialize_config_module', 'initialize Hydra with an absolute config directory path using initialize_config_dir', 'backup and restore the GlobalHydra singleton instance using get_gh_backup and restore_gh_from_backup', 'review the initialize class version_base parameter handling for Hydra 1.2 compatibility', 'run a python function decorated with @hydra.main to execute a Hydra-managed task with config', 'create a Hydra task function using @hydra.main with a config_path and config_name', 'rerun a previous Hydra job by loading a pickled config file via _get_rerun_conf', 'review the hydra.main decorator function and its config_path and version_base parameters', 'refactor a Hydra decorated task function to use a different config_path or version_base', 'get a Python class by its fully qualified dotpath string using hydra.utils.get_class', 'get a callable method or function by its fully qualified dotpath string using hydra.utils.get_method', 'get any Python object by its fully qualified dotpath string using hydra.utils.get_object', 'convert a relative or absolute path string to an absolute path using hydra.utils.to_absolute_path', 'convert a Python dict or list to a Hydra override value string using hydra.utils.to_hydra_override_value_str', 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get the current Hydra version_base from the VersionBase singleton instance', 'check if the current version_base is at least a specified minimum version string', 'parse a version string and extract only the major and minor components', 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning']
```

Usage

```
{'set_version_base': 'set the Hydra version_base compatibility level to a specific version string like 1.1', 'get_version_base': 'get the current Hydra version_base from the VersionBase singleton instance', 'check_base_at_least': 'check if the current version_base is at least a specified minimum version string', 'parse_version_major_minor': 'parse a version string and extract only the major and minor components', 'configure_version_singleton': 'configure the VersionBase singleton instance to manage Hydra backward compatibility versioning'}
```

