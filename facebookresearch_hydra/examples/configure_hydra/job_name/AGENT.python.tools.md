# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/configure_hydra/job_name/no_config_file_override.py

Prompts

```
['run the python module to print the Hydra job name using HydraConfig', 'run the experiment function decorated with hydra.main to access HydraConfig job name', 'create a Hydra app that prints the job name without a config file', 'review the experiment function that uses HydraConfig.get() to access the job name', 'refactor the experiment function to customize how the Hydra job name is printed', 'run the Hydra experiment that prints the job name overridden by the config file', 'run the Hydra main decorated function to print the job name from config.yaml', 'review the experiment function that uses HydraConfig.get().job.name to print the overridden job name', 'summarize how the config file overrides the Hydra job name via hydra.job.name in config.yaml', 'refactor the experiment function to print additional HydraConfig fields beyond just the job name']
```

Usage

```
{'run_experiment_print_job_name': 'run the python module to print the Hydra job name using HydraConfig', 'run_experiment_with_hydra_main': 'run the experiment function decorated with hydra.main to access HydraConfig job name', 'create_hydra_app_no_config': 'create a Hydra app that prints the job name without a config file', 'review_experiment_hydraconfig': 'review the experiment function that uses HydraConfig.get() to access the job name', 'refactor_experiment_job_name': 'refactor the experiment function to customize how the Hydra job name is printed'}
```

## File: facebookresearch_hydra/examples/configure_hydra/job_name/with_config_file_override.py

Prompts

```
['run the python module to print the Hydra job name using HydraConfig', 'run the experiment function decorated with hydra.main to access HydraConfig job name', 'create a Hydra app that prints the job name without a config file', 'review the experiment function that uses HydraConfig.get() to access the job name', 'refactor the experiment function to customize how the Hydra job name is printed', 'run the Hydra experiment that prints the job name overridden by the config file', 'run the Hydra main decorated function to print the job name from config.yaml', 'review the experiment function that uses HydraConfig.get().job.name to print the overridden job name', 'summarize how the config file overrides the Hydra job name via hydra.job.name in config.yaml', 'refactor the experiment function to print additional HydraConfig fields beyond just the job name']
```

Usage

```
{'run_experiment_with_config_override': 'run the Hydra experiment that prints the job name overridden by the config file', 'run_hydra_job_name_override': 'run the Hydra main decorated function to print the job name from config.yaml', 'review_experiment_function': 'review the experiment function that uses HydraConfig.get().job.name to print the overridden job name', 'summarize_hydra_config_override': 'summarize how the config file overrides the Hydra job name via hydra.job.name in config.yaml', 'refactor_experiment_for_custom_output': 'refactor the experiment function to print additional HydraConfig fields beyond just the job name'}
```

