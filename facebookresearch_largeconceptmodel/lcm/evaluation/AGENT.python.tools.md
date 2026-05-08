# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/evaluation/__main__.py

Prompts

```
['run the LCM evaluation CLI to execute model evaluation tasks locally or via SLURM', 'run a dry run of the LCM evaluation CLI to print the config and exit', 'run the LCM evaluation CLI with SLURM launcher options for distributed evaluation', 'run the LCM evaluation CLI with the local launcher for single-machine evaluation', 'run cfg_from_cli to parse CLI arguments into a CliConfig and LauncherOptions tuple', 'create a Message dataclass with a Role enum and content string for chat messages', 'create a Prediction dataclass to store model prediction text, embeddings, tokens, and logprobs', 'run the Scorer score_texts method to compute model-based metrics on a sequence of text inputs', 'update an AverageMetric with new values and compute confidence intervals using compute_ci', 'parse task config kwargs into a dictionary matching the fields of a TaskConfig dataclass', 'build an EvalRunModule from a base config dict and task dict for async SLURM evaluation', 'schedule an EvalRunModule on a SLURM launcher and aggregate evaluation metrics with confidence intervals', 'create a RunModuleConfig dataclass to configure SLURM node requirements, shards, and environment variables for eval runs', 'run an EvalRunModule task on a distributed gang device with optional shard iteration values', 'get a cacheable config dict from an EvalRunModule with non-hashed keys overwritten for deduplication', 'run an LCM evaluation task with a RunConfig and predictor to compute metrics', 'create a RunConfig dataclass to configure a single LCM evaluation task run', 'build a RunConfig from a dictionary or DictConfig using from_dict class method', 'update dataset parameters in RunConfig based on task registry defaults', 'compute confidence interval bounds for average metrics using compute_ci method']
```

Usage

```
{'run_evaluation_cli': 'run the LCM evaluation CLI to execute model evaluation tasks locally or via SLURM', 'run_evaluation_dry_run': 'run a dry run of the LCM evaluation CLI to print the config and exit', 'run_evaluation_slurm': 'run the LCM evaluation CLI with SLURM launcher options for distributed evaluation', 'run_evaluation_local': 'run the LCM evaluation CLI with the local launcher for single-machine evaluation', 'run_cfg_from_cli': 'run cfg_from_cli to parse CLI arguments into a CliConfig and LauncherOptions tuple'}
```

## File: facebookresearch_largeconceptmodel/lcm/evaluation/api.py

Prompts

```
['run the LCM evaluation CLI to execute model evaluation tasks locally or via SLURM', 'run a dry run of the LCM evaluation CLI to print the config and exit', 'run the LCM evaluation CLI with SLURM launcher options for distributed evaluation', 'run the LCM evaluation CLI with the local launcher for single-machine evaluation', 'run cfg_from_cli to parse CLI arguments into a CliConfig and LauncherOptions tuple', 'create a Message dataclass with a Role enum and content string for chat messages', 'create a Prediction dataclass to store model prediction text, embeddings, tokens, and logprobs', 'run the Scorer score_texts method to compute model-based metrics on a sequence of text inputs', 'update an AverageMetric with new values and compute confidence intervals using compute_ci', 'parse task config kwargs into a dictionary matching the fields of a TaskConfig dataclass', 'build an EvalRunModule from a base config dict and task dict for async SLURM evaluation', 'schedule an EvalRunModule on a SLURM launcher and aggregate evaluation metrics with confidence intervals', 'create a RunModuleConfig dataclass to configure SLURM node requirements, shards, and environment variables for eval runs', 'run an EvalRunModule task on a distributed gang device with optional shard iteration values', 'get a cacheable config dict from an EvalRunModule with non-hashed keys overwritten for deduplication', 'run an LCM evaluation task with a RunConfig and predictor to compute metrics', 'create a RunConfig dataclass to configure a single LCM evaluation task run', 'build a RunConfig from a dictionary or DictConfig using from_dict class method', 'update dataset parameters in RunConfig based on task registry defaults', 'compute confidence interval bounds for average metrics using compute_ci method']
```

Usage

```
{'create_Message': 'create a Message dataclass with a Role enum and content string for chat messages', 'create_Prediction': 'create a Prediction dataclass to store model prediction text, embeddings, tokens, and logprobs', 'run_Scorer_score_texts': 'run the Scorer score_texts method to compute model-based metrics on a sequence of text inputs', 'update_AverageMetric': 'update an AverageMetric with new values and compute confidence intervals using compute_ci', 'parse_task_configs': 'parse task config kwargs into a dictionary matching the fields of a TaskConfig dataclass'}
```

## File: facebookresearch_largeconceptmodel/lcm/evaluation/arun.py

Prompts

```
['run the LCM evaluation CLI to execute model evaluation tasks locally or via SLURM', 'run a dry run of the LCM evaluation CLI to print the config and exit', 'run the LCM evaluation CLI with SLURM launcher options for distributed evaluation', 'run the LCM evaluation CLI with the local launcher for single-machine evaluation', 'run cfg_from_cli to parse CLI arguments into a CliConfig and LauncherOptions tuple', 'create a Message dataclass with a Role enum and content string for chat messages', 'create a Prediction dataclass to store model prediction text, embeddings, tokens, and logprobs', 'run the Scorer score_texts method to compute model-based metrics on a sequence of text inputs', 'update an AverageMetric with new values and compute confidence intervals using compute_ci', 'parse task config kwargs into a dictionary matching the fields of a TaskConfig dataclass', 'build an EvalRunModule from a base config dict and task dict for async SLURM evaluation', 'schedule an EvalRunModule on a SLURM launcher and aggregate evaluation metrics with confidence intervals', 'create a RunModuleConfig dataclass to configure SLURM node requirements, shards, and environment variables for eval runs', 'run an EvalRunModule task on a distributed gang device with optional shard iteration values', 'get a cacheable config dict from an EvalRunModule with non-hashed keys overwritten for deduplication', 'run an LCM evaluation task with a RunConfig and predictor to compute metrics', 'create a RunConfig dataclass to configure a single LCM evaluation task run', 'build a RunConfig from a dictionary or DictConfig using from_dict class method', 'update dataset parameters in RunConfig based on task registry defaults', 'compute confidence interval bounds for average metrics using compute_ci method']
```

Usage

```
{'build_async_task': 'build an EvalRunModule from a base config dict and task dict for async SLURM evaluation', 'schedule_task': 'schedule an EvalRunModule on a SLURM launcher and aggregate evaluation metrics with confidence intervals', 'run_module_config': 'create a RunModuleConfig dataclass to configure SLURM node requirements, shards, and environment variables for eval runs', 'evalrunmodule_run': 'run an EvalRunModule task on a distributed gang device with optional shard iteration values', 'evalrunmodule_get_config_for_cache': 'get a cacheable config dict from an EvalRunModule with non-hashed keys overwritten for deduplication'}
```

## File: facebookresearch_largeconceptmodel/lcm/evaluation/run.py

Prompts

```
['run the LCM evaluation CLI to execute model evaluation tasks locally or via SLURM', 'run a dry run of the LCM evaluation CLI to print the config and exit', 'run the LCM evaluation CLI with SLURM launcher options for distributed evaluation', 'run the LCM evaluation CLI with the local launcher for single-machine evaluation', 'run cfg_from_cli to parse CLI arguments into a CliConfig and LauncherOptions tuple', 'create a Message dataclass with a Role enum and content string for chat messages', 'create a Prediction dataclass to store model prediction text, embeddings, tokens, and logprobs', 'run the Scorer score_texts method to compute model-based metrics on a sequence of text inputs', 'update an AverageMetric with new values and compute confidence intervals using compute_ci', 'parse task config kwargs into a dictionary matching the fields of a TaskConfig dataclass', 'build an EvalRunModule from a base config dict and task dict for async SLURM evaluation', 'schedule an EvalRunModule on a SLURM launcher and aggregate evaluation metrics with confidence intervals', 'create a RunModuleConfig dataclass to configure SLURM node requirements, shards, and environment variables for eval runs', 'run an EvalRunModule task on a distributed gang device with optional shard iteration values', 'get a cacheable config dict from an EvalRunModule with non-hashed keys overwritten for deduplication', 'run an LCM evaluation task with a RunConfig and predictor to compute metrics', 'create a RunConfig dataclass to configure a single LCM evaluation task run', 'build a RunConfig from a dictionary or DictConfig using from_dict class method', 'update dataset parameters in RunConfig based on task registry defaults', 'compute confidence interval bounds for average metrics using compute_ci method']
```

Usage

```
{'run_evaluation_task': 'run an LCM evaluation task with a RunConfig and predictor to compute metrics', 'create_run_config': 'create a RunConfig dataclass to configure a single LCM evaluation task run', 'build_run_config_from_dict': 'build a RunConfig from a dictionary or DictConfig using from_dict class method', 'update_dataset_params': 'update dataset parameters in RunConfig based on task registry defaults', 'compute_confidence_intervals': 'compute confidence interval bounds for average metrics using compute_ci method'}
```

