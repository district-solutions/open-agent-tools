# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/launchers/launch_cumulative_speedup.py

Prompts

```
['run a cascaded scientist experiment to measure cumulative training time reduction across records', 'gather training time and validation loss metrics from workspace version directories into a DataFrame', 'generate a command to launch a scientist run for a specific record with model and template settings', 'compute the best training time reduction from workspace results while filtering out invalid solutions', 'launch parallel cascaded scientist jobs via submitit executor across multiple model and template combinations', 'generate a command list to launch a scientist job with a specific record number, model, and knowledge source paths', 'get the current SLURM job ID from environment variables for workspace path augmentation', 'run a subprocess command with an augmented workspace path that includes the SLURM job ID', 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'submit batch scientist jobs via submitit across record numbers, search variants, and frontier models', 'run LLM agent baseline experiments across multiple records, models, and knowledge levels via SLURM', 'generate a launch_scientist command with record number, model, knowledge level, and science runner config', 'run a subprocess command with an augmented workspace path using the current SLURM job ID', 'run a scientist job on a SLURM cluster using submitit with configurable hyperparameters', 'submit a batch of scientist jobs across a grid of hypothesis and debug parameters', 'configure SLURM job parameters like timeout, CPUs, nodes, and array parallelism', 'run a scientist experiment with a specific task name, model, and iteration count', 'launch scientist jobs via CLI with argparse options for job name, timeout, and search parameters']
```

Usage

```
{'run_cascaded_speedup_experiment': 'run a cascaded scientist experiment to measure cumulative training time reduction across records', 'gather_metrics_from_workspace': 'gather training time and validation loss metrics from workspace version directories into a DataFrame', 'generate_scientist_command': 'generate a command to launch a scientist run for a specific record with model and template settings', 'compute_training_time_reduction': 'compute the best training time reduction from workspace results while filtering out invalid solutions', 'launch_cascaded_jobs_with_submitit': 'launch parallel cascaded scientist jobs via submitit executor across multiple model and template combinations'}
```

## File: facebookresearch_llm-speedrunner/launchers/launch_llm_speedrun_agent_additional_knowledge.py

Prompts

```
['run a cascaded scientist experiment to measure cumulative training time reduction across records', 'gather training time and validation loss metrics from workspace version directories into a DataFrame', 'generate a command to launch a scientist run for a specific record with model and template settings', 'compute the best training time reduction from workspace results while filtering out invalid solutions', 'launch parallel cascaded scientist jobs via submitit executor across multiple model and template combinations', 'generate a command list to launch a scientist job with a specific record number, model, and knowledge source paths', 'get the current SLURM job ID from environment variables for workspace path augmentation', 'run a subprocess command with an augmented workspace path that includes the SLURM job ID', 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'submit batch scientist jobs via submitit across record numbers, search variants, and frontier models', 'run LLM agent baseline experiments across multiple records, models, and knowledge levels via SLURM', 'generate a launch_scientist command with record number, model, knowledge level, and science runner config', 'run a subprocess command with an augmented workspace path using the current SLURM job ID', 'run a scientist job on a SLURM cluster using submitit with configurable hyperparameters', 'submit a batch of scientist jobs across a grid of hypothesis and debug parameters', 'configure SLURM job parameters like timeout, CPUs, nodes, and array parallelism', 'run a scientist experiment with a specific task name, model, and iteration count', 'launch scientist jobs via CLI with argparse options for job name, timeout, and search parameters']
```

Usage

```
{'generate_cmd': 'generate a command list to launch a scientist job with a specific record number, model, and knowledge source paths', 'get_slurm_id': 'get the current SLURM job ID from environment variables for workspace path augmentation', 'worker': 'run a subprocess command with an augmented workspace path that includes the SLURM job ID', 'set_agent_search_parameters': 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'main': 'submit batch scientist jobs via submitit across record numbers, search variants, and frontier models'}
```

## File: facebookresearch_llm-speedrunner/launchers/launch_llm_speedrun_agent_baselines.py

Prompts

```
['run a cascaded scientist experiment to measure cumulative training time reduction across records', 'gather training time and validation loss metrics from workspace version directories into a DataFrame', 'generate a command to launch a scientist run for a specific record with model and template settings', 'compute the best training time reduction from workspace results while filtering out invalid solutions', 'launch parallel cascaded scientist jobs via submitit executor across multiple model and template combinations', 'generate a command list to launch a scientist job with a specific record number, model, and knowledge source paths', 'get the current SLURM job ID from environment variables for workspace path augmentation', 'run a subprocess command with an augmented workspace path that includes the SLURM job ID', 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'submit batch scientist jobs via submitit across record numbers, search variants, and frontier models', 'run LLM agent baseline experiments across multiple records, models, and knowledge levels via SLURM', 'generate a launch_scientist command with record number, model, knowledge level, and science runner config', 'run a subprocess command with an augmented workspace path using the current SLURM job ID', 'run a scientist job on a SLURM cluster using submitit with configurable hyperparameters', 'submit a batch of scientist jobs across a grid of hypothesis and debug parameters', 'configure SLURM job parameters like timeout, CPUs, nodes, and array parallelism', 'run a scientist experiment with a specific task name, model, and iteration count', 'launch scientist jobs via CLI with argparse options for job name, timeout, and search parameters']
```

Usage

```
{'run_llm_speedrun_agent_baselines': 'run LLM agent baseline experiments across multiple records, models, and knowledge levels via SLURM', 'generate_cmd_scientist_launch': 'generate a launch_scientist command with record number, model, knowledge level, and science runner config', 'set_agent_search_parameters': 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'run_worker_with_slurm_id': 'run a subprocess command with an augmented workspace path using the current SLURM job ID', 'get_slurm_id': 'get the current SLURM job ID from environment variables SLURM_JOB_ID, SLURM_ARRAY_JOB_ID, and SLURM_ARRAY_TASK_ID'}
```

## File: facebookresearch_llm-speedrunner/launchers/launch_slurm.py

Prompts

```
['run a cascaded scientist experiment to measure cumulative training time reduction across records', 'gather training time and validation loss metrics from workspace version directories into a DataFrame', 'generate a command to launch a scientist run for a specific record with model and template settings', 'compute the best training time reduction from workspace results while filtering out invalid solutions', 'launch parallel cascaded scientist jobs via submitit executor across multiple model and template combinations', 'generate a command list to launch a scientist job with a specific record number, model, and knowledge source paths', 'get the current SLURM job ID from environment variables for workspace path augmentation', 'run a subprocess command with an augmented workspace path that includes the SLURM job ID', 'set agent search parameters for flat, tree, forest, aide, or multi-aide search strategies', 'submit batch scientist jobs via submitit across record numbers, search variants, and frontier models', 'run LLM agent baseline experiments across multiple records, models, and knowledge levels via SLURM', 'generate a launch_scientist command with record number, model, knowledge level, and science runner config', 'run a subprocess command with an augmented workspace path using the current SLURM job ID', 'run a scientist job on a SLURM cluster using submitit with configurable hyperparameters', 'submit a batch of scientist jobs across a grid of hypothesis and debug parameters', 'configure SLURM job parameters like timeout, CPUs, nodes, and array parallelism', 'run a scientist experiment with a specific task name, model, and iteration count', 'launch scientist jobs via CLI with argparse options for job name, timeout, and search parameters']
```

Usage

```
{'run_scientist_job': 'run a scientist job on a SLURM cluster using submitit with configurable hyperparameters', 'submit_batch_jobs': 'submit a batch of scientist jobs across a grid of hypothesis and debug parameters', 'configure_job_parameters': 'configure SLURM job parameters like timeout, CPUs, nodes, and array parallelism', 'run_scientist_with_task': 'run a scientist experiment with a specific task name, model, and iteration count', 'launch_scientist_cli': 'launch scientist jobs via CLI with argparse options for job name, timeout, and search parameters'}
```

