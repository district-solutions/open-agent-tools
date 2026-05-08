# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/hydra/experimental/callback.py

Prompts

```
['create a subclass of Hydra Callback to add custom lifecycle hook logic', 'implement the on_run_start method in a Callback subclass to run setup before job starts', 'implement the on_run_end method in a Callback subclass to run cleanup after job ends', 'implement the on_job_start method to log or track when each Hydra job begins', 'implement the on_job_end method to process JobReturn data after each Hydra job completes', 'implement the on_compose_config method to inspect or modify the composed config before it is returned', 'create a LogJobReturnCallback to log job return values or errors on job end', 'create a PickleJobInfoCallback to pickle job config and return value to output directory', 'create a LogComposeCallback to log composed config, overrides, and defaults list', 'review the PickleJobInfoCallback _save_pickle method that serializes objects to pickle files', 'review the LogComposeCallback on_compose_config method that logs config composition details', 'compose a Hydra config from a config_name with override list and return as DictConfig', 'compose a Hydra config in strict mode to validate overrides against schema', 'compose a Hydra config and include the hydra config section in the returned DictConfig', 'review the deprecated hydra.experimental.compose function and migrate calls to hydra.compose', 'summarize the compose function signature, parameters, and return type for Hydra config composition', 'create a python module that uses hydra.experimental.initialize with a config_path to set up Hydra configuration', 'create a python module that uses hydra.experimental.initialize_config_module to initialize Hydra with an importable config module', 'create a python module that uses hydra.experimental.initialize_config_dir to initialize Hydra with an absolute config directory path', 'create a python module that calls get_gh_backup to create a deep copy of the current GlobalHydra singleton instance', 'create a python module that calls restore_gh_from_backup to restore a previously backed up GlobalHydra singleton instance']
```

Usage

```
{'create_callback_subclass': 'create a subclass of Hydra Callback to add custom lifecycle hook logic', 'implement_on_run_start': 'implement the on_run_start method in a Callback subclass to run setup before job starts', 'implement_on_run_end': 'implement the on_run_end method in a Callback subclass to run cleanup after job ends', 'implement_on_job_start': 'implement the on_job_start method to log or track when each Hydra job begins', 'implement_on_job_end': 'implement the on_job_end method to process JobReturn data after each Hydra job completes', 'implement_on_compose_config': 'implement the on_compose_config method to inspect or modify the composed config before it is returned'}
```

## File: facebookresearch_hydra/hydra/experimental/callbacks.py

Prompts

```
['create a subclass of Hydra Callback to add custom lifecycle hook logic', 'implement the on_run_start method in a Callback subclass to run setup before job starts', 'implement the on_run_end method in a Callback subclass to run cleanup after job ends', 'implement the on_job_start method to log or track when each Hydra job begins', 'implement the on_job_end method to process JobReturn data after each Hydra job completes', 'implement the on_compose_config method to inspect or modify the composed config before it is returned', 'create a LogJobReturnCallback to log job return values or errors on job end', 'create a PickleJobInfoCallback to pickle job config and return value to output directory', 'create a LogComposeCallback to log composed config, overrides, and defaults list', 'review the PickleJobInfoCallback _save_pickle method that serializes objects to pickle files', 'review the LogComposeCallback on_compose_config method that logs config composition details', 'compose a Hydra config from a config_name with override list and return as DictConfig', 'compose a Hydra config in strict mode to validate overrides against schema', 'compose a Hydra config and include the hydra config section in the returned DictConfig', 'review the deprecated hydra.experimental.compose function and migrate calls to hydra.compose', 'summarize the compose function signature, parameters, and return type for Hydra config composition', 'create a python module that uses hydra.experimental.initialize with a config_path to set up Hydra configuration', 'create a python module that uses hydra.experimental.initialize_config_module to initialize Hydra with an importable config module', 'create a python module that uses hydra.experimental.initialize_config_dir to initialize Hydra with an absolute config directory path', 'create a python module that calls get_gh_backup to create a deep copy of the current GlobalHydra singleton instance', 'create a python module that calls restore_gh_from_backup to restore a previously backed up GlobalHydra singleton instance']
```

Usage

```
{'create_log_job_return_callback': 'create a LogJobReturnCallback to log job return values or errors on job end', 'create_pickle_job_info_callback': 'create a PickleJobInfoCallback to pickle job config and return value to output directory', 'create_log_compose_callback': 'create a LogComposeCallback to log composed config, overrides, and defaults list', 'review_pickle_job_info_callback_save_pickle': 'review the PickleJobInfoCallback _save_pickle method that serializes objects to pickle files', 'review_log_compose_callback_on_compose_config': 'review the LogComposeCallback on_compose_config method that logs config composition details'}
```

## File: facebookresearch_hydra/hydra/experimental/compose.py

Prompts

```
['create a subclass of Hydra Callback to add custom lifecycle hook logic', 'implement the on_run_start method in a Callback subclass to run setup before job starts', 'implement the on_run_end method in a Callback subclass to run cleanup after job ends', 'implement the on_job_start method to log or track when each Hydra job begins', 'implement the on_job_end method to process JobReturn data after each Hydra job completes', 'implement the on_compose_config method to inspect or modify the composed config before it is returned', 'create a LogJobReturnCallback to log job return values or errors on job end', 'create a PickleJobInfoCallback to pickle job config and return value to output directory', 'create a LogComposeCallback to log composed config, overrides, and defaults list', 'review the PickleJobInfoCallback _save_pickle method that serializes objects to pickle files', 'review the LogComposeCallback on_compose_config method that logs config composition details', 'compose a Hydra config from a config_name with override list and return as DictConfig', 'compose a Hydra config in strict mode to validate overrides against schema', 'compose a Hydra config and include the hydra config section in the returned DictConfig', 'review the deprecated hydra.experimental.compose function and migrate calls to hydra.compose', 'summarize the compose function signature, parameters, and return type for Hydra config composition', 'create a python module that uses hydra.experimental.initialize with a config_path to set up Hydra configuration', 'create a python module that uses hydra.experimental.initialize_config_module to initialize Hydra with an importable config module', 'create a python module that uses hydra.experimental.initialize_config_dir to initialize Hydra with an absolute config directory path', 'create a python module that calls get_gh_backup to create a deep copy of the current GlobalHydra singleton instance', 'create a python module that calls restore_gh_from_backup to restore a previously backed up GlobalHydra singleton instance']
```

Usage

```
{'compose_config_with_overrides': 'compose a Hydra config from a config_name with override list and return as DictConfig', 'compose_config_strict_mode': 'compose a Hydra config in strict mode to validate overrides against schema', 'compose_config_with_hydra_config': 'compose a Hydra config and include the hydra config section in the returned DictConfig', 'review_compose_deprecation': 'review the deprecated hydra.experimental.compose function and migrate calls to hydra.compose', 'summarize_compose_function': 'summarize the compose function signature, parameters, and return type for Hydra config composition'}
```

## File: facebookresearch_hydra/hydra/experimental/initialize.py

Prompts

```
['create a subclass of Hydra Callback to add custom lifecycle hook logic', 'implement the on_run_start method in a Callback subclass to run setup before job starts', 'implement the on_run_end method in a Callback subclass to run cleanup after job ends', 'implement the on_job_start method to log or track when each Hydra job begins', 'implement the on_job_end method to process JobReturn data after each Hydra job completes', 'implement the on_compose_config method to inspect or modify the composed config before it is returned', 'create a LogJobReturnCallback to log job return values or errors on job end', 'create a PickleJobInfoCallback to pickle job config and return value to output directory', 'create a LogComposeCallback to log composed config, overrides, and defaults list', 'review the PickleJobInfoCallback _save_pickle method that serializes objects to pickle files', 'review the LogComposeCallback on_compose_config method that logs config composition details', 'compose a Hydra config from a config_name with override list and return as DictConfig', 'compose a Hydra config in strict mode to validate overrides against schema', 'compose a Hydra config and include the hydra config section in the returned DictConfig', 'review the deprecated hydra.experimental.compose function and migrate calls to hydra.compose', 'summarize the compose function signature, parameters, and return type for Hydra config composition', 'create a python module that uses hydra.experimental.initialize with a config_path to set up Hydra configuration', 'create a python module that uses hydra.experimental.initialize_config_module to initialize Hydra with an importable config module', 'create a python module that uses hydra.experimental.initialize_config_dir to initialize Hydra with an absolute config directory path', 'create a python module that calls get_gh_backup to create a deep copy of the current GlobalHydra singleton instance', 'create a python module that calls restore_gh_from_backup to restore a previously backed up GlobalHydra singleton instance']
```

Usage

```
{'initialize_hydra_with_config_path': 'create a python module that uses hydra.experimental.initialize with a config_path to set up Hydra configuration', 'initialize_hydra_config_module': 'create a python module that uses hydra.experimental.initialize_config_module to initialize Hydra with an importable config module', 'initialize_hydra_config_dir': 'create a python module that uses hydra.experimental.initialize_config_dir to initialize Hydra with an absolute config directory path', 'backup_global_hydra': 'create a python module that calls get_gh_backup to create a deep copy of the current GlobalHydra singleton instance', 'restore_global_hydra': 'create a python module that calls restore_gh_from_backup to restore a previously backed up GlobalHydra singleton instance'}
```

