# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/private_computation_cli/private_computation_cli.py

Prompts

```
['run a private lift study by study ID with input paths and optional objective IDs', 'create a private computation instance with a config file, role, game type, and input path', 'run an attribution job with a dataset ID, input path, attribution rule, and aggregation type', 'validate a private computation instance by comparing aggregated results against expected results', 'scrub secrets from an input file and write the cleaned output to a specified path', 'create a private computation instance with a given role, game type, input path, and container counts', 'run the next stage of a private computation instance by its instance ID', 'validate the metrics of a private computation instance against an expected result path', 'get the updated status of a private computation instance by its instance ID', 'build a PrivateComputationService from config dicts for private computation, MPC, PID, and post-processing handlers']
```

Usage

```
{'run_private_lift_study': 'run a private lift study by study ID with input paths and optional objective IDs', 'create_private_computation_instance': 'create a private computation instance with a config file, role, game type, and input path', 'run_attribution_job': 'run an attribution job with a dataset ID, input path, attribution rule, and aggregation type', 'validate_private_computation_instance': 'validate a private computation instance by comparing aggregated results against expected results', 'scrub_secrets_from_file': 'scrub secrets from an input file and write the cleaned output to a specified path'}
```

## File: facebookresearch_fbpcs/fbpcs/private_computation_cli/private_computation_service_wrapper.py

Prompts

```
['run a private lift study by study ID with input paths and optional objective IDs', 'create a private computation instance with a config file, role, game type, and input path', 'run an attribution job with a dataset ID, input path, attribution rule, and aggregation type', 'validate a private computation instance by comparing aggregated results against expected results', 'scrub secrets from an input file and write the cleaned output to a specified path', 'create a private computation instance with a given role, game type, input path, and container counts', 'run the next stage of a private computation instance by its instance ID', 'validate the metrics of a private computation instance against an expected result path', 'get the updated status of a private computation instance by its instance ID', 'build a PrivateComputationService from config dicts for private computation, MPC, PID, and post-processing handlers']
```

Usage

```
{'create_instance': 'create a private computation instance with a given role, game type, input path, and container counts', 'run_next': 'run the next stage of a private computation instance by its instance ID', 'validate': 'validate the metrics of a private computation instance against an expected result path', 'get_instance': 'get the updated status of a private computation instance by its instance ID', 'build_private_computation_service': 'build a PrivateComputationService from config dicts for private computation, MPC, PID, and post-processing handlers'}
```

