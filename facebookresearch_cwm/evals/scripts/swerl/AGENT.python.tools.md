# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/evals/scripts/swerl/eval_cli.py

Prompts

```
['run SWE-bench evaluation on gold patches using the eval_cli with a data file and eval directory', 'run SWE-bench evaluation on model predictions by providing a pred_file with instance_id and model_patch', 'run SWE-bench evaluation with noop patches to verify the eval harness has no false negatives', 'aggregate existing evaluation results from eval_dir eval.jsonl without running new evaluations by setting run to False', 'run SWE-bench evaluation on a random subset of instances by setting num_instances_to_eval to a positive integer', 'run the format_swerl script to convert SWE-bench dataset to SWE-RL JSONL format for evaluation', 'run python -m evals.scripts.swerl.format_swerl with save_path, dataset, split, and namespace arguments', 'use map_fn to transform a SWE-bench instance dict by adding repo_root_path, eval_script, and docker_url fields', 'use make_test_spec on a SWE-bench instance dict to generate an eval script for the instance', 'use main to load a HuggingFace dataset, map it with map_fn, shuffle, and save as JSONL']
```

Usage

```
{'run_swebench_eval_gold': 'run SWE-bench evaluation on gold patches using the eval_cli with a data file and eval directory', 'run_swebench_eval_predictions': 'run SWE-bench evaluation on model predictions by providing a pred_file with instance_id and model_patch', 'run_swebench_eval_noop': 'run SWE-bench evaluation with noop patches to verify the eval harness has no false negatives', 'aggregate_swebench_results': 'aggregate existing evaluation results from eval_dir eval.jsonl without running new evaluations by setting run to False', 'run_swebench_eval_subset': 'run SWE-bench evaluation on a random subset of instances by setting num_instances_to_eval to a positive integer'}
```

## File: facebookresearch_cwm/evals/scripts/swerl/format_swerl.py

Prompts

```
['run SWE-bench evaluation on gold patches using the eval_cli with a data file and eval directory', 'run SWE-bench evaluation on model predictions by providing a pred_file with instance_id and model_patch', 'run SWE-bench evaluation with noop patches to verify the eval harness has no false negatives', 'aggregate existing evaluation results from eval_dir eval.jsonl without running new evaluations by setting run to False', 'run SWE-bench evaluation on a random subset of instances by setting num_instances_to_eval to a positive integer', 'run the format_swerl script to convert SWE-bench dataset to SWE-RL JSONL format for evaluation', 'run python -m evals.scripts.swerl.format_swerl with save_path, dataset, split, and namespace arguments', 'use map_fn to transform a SWE-bench instance dict by adding repo_root_path, eval_script, and docker_url fields', 'use make_test_spec on a SWE-bench instance dict to generate an eval script for the instance', 'use main to load a HuggingFace dataset, map it with map_fn, shuffle, and save as JSONL']
```

Usage

```
{'convert_swebench_to_swerl_format': 'run the format_swerl script to convert SWE-bench dataset to SWE-RL JSONL format for evaluation', 'run_format_swerl_cli': 'run python -m evals.scripts.swerl.format_swerl with save_path, dataset, split, and namespace arguments', 'map_swebench_instance': 'use map_fn to transform a SWE-bench instance dict by adding repo_root_path, eval_script, and docker_url fields', 'create_test_spec_from_instance': 'use make_test_spec on a SWE-bench instance dict to generate an eval script for the instance', 'load_and_save_swerl_dataset': 'use main to load a HuggingFace dataset, map it with map_fn, shuffle, and save as JSONL'}
```

