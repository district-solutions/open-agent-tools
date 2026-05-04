# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/grade_code.py

Prompts

```
['run execute_code to grade a Python file against an MLEBench task and get a grading summary', 'run the CLI to grade a code submission for an MLEBench task and save results to JSON', 'review execute_code to understand how it uses JupyterInterpreterConfig and MLEBenchTaskConfig to evaluate code', 'refactor execute_code to support a different interpreter or benchmark beyond MLEBench', 'summarize the main CLI entry point that validates inputs and saves grading results to a JSON file', 'submit a batch of RunConfig jobs to a Slurm executor via submitit with an rsync snapshot', 'recursively set a nested dot-separated key on a dataclass config object to a new value', 'recursively retrieve the value of a nested dot-separated key from a dataclass config object', 'run the Hydra-based entry point that expands variable sweeps into RunnerConfig jobs and launches them on Slurm', 'asynchronously expand RunnerConfig objects into RunConfigs, resolve OmegaConf interpolations, and submit jobs or print a dry-run summary']
```

Usage

```
{'run_execute_code': 'run execute_code to grade a Python file against an MLEBench task and get a grading summary', 'run_main_cli': 'run the CLI to grade a code submission for an MLEBench task and save results to JSON', 'review_execute_code': 'review execute_code to understand how it uses JupyterInterpreterConfig and MLEBenchTaskConfig to evaluate code', 'refactor_execute_code': 'refactor execute_code to support a different interpreter or benchmark beyond MLEBench', 'summarize_main': 'summarize the main CLI entry point that validates inputs and saves grading results to a JSON file'}
```

## File: facebookresearch_aira-dojo/src/dojo/main_runner_job_array.py

Prompts

```
['run execute_code to grade a Python file against an MLEBench task and get a grading summary', 'run the CLI to grade a code submission for an MLEBench task and save results to JSON', 'review execute_code to understand how it uses JupyterInterpreterConfig and MLEBenchTaskConfig to evaluate code', 'refactor execute_code to support a different interpreter or benchmark beyond MLEBench', 'summarize the main CLI entry point that validates inputs and saves grading results to a JSON file', 'submit a batch of RunConfig jobs to a Slurm executor via submitit with an rsync snapshot', 'recursively set a nested dot-separated key on a dataclass config object to a new value', 'recursively retrieve the value of a nested dot-separated key from a dataclass config object', 'run the Hydra-based entry point that expands variable sweeps into RunnerConfig jobs and launches them on Slurm', 'asynchronously expand RunnerConfig objects into RunConfigs, resolve OmegaConf interpolations, and submit jobs or print a dry-run summary']
```

Usage

```
{'launch_jobs': 'submit a batch of RunConfig jobs to a Slurm executor via submitit with an rsync snapshot', 'override_config': 'recursively set a nested dot-separated key on a dataclass config object to a new value', 'fetch_config': 'recursively retrieve the value of a nested dot-separated key from a dataclass config object', 'main_runner_entry': 'run the Hydra-based entry point that expands variable sweeps into RunnerConfig jobs and launches them on Slurm', 'main_async': 'asynchronously expand RunnerConfig objects into RunConfigs, resolve OmegaConf interpolations, and submit jobs or print a dry-run summary'}
```

