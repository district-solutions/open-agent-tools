# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/tasks/mlebench/evaluate.py

Prompts

```
['run evaluate_submission to grade a CSV submission file against an MLEBench competition and save a grading report', 'run is_lower_better to check if lower scores are better for a given MLEBench competition', 'test evaluate_submission by passing a submission CSV path, data directory, competition ID, and output directory', 'review evaluate_submission to understand how it grades submissions, ranks scores, and generates medal thresholds', 'refactor evaluate_submission to support additional submission file formats beyond CSV', 'create an MLEBenchTask instance with an MLEBenchTaskConfig to set up a machine learning benchmark task', 'prepare an MLEBenchTask by initializing the submission file path and task description for the solver interpreter', 'execute a single step of an MLEBenchTask by running solution code and evaluating the generated submission CSV', 'evaluate the fitness of a final solution by running it and scoring the submission against competition metrics', 'parse an evaluation report dictionary converting numeric values to floats for consistent scoring output']
```

Usage

```
{'run_evaluate_submission': 'run evaluate_submission to grade a CSV submission file against an MLEBench competition and save a grading report', 'run_is_lower_better': 'run is_lower_better to check if lower scores are better for a given MLEBench competition', 'test_evaluate_submission': 'test evaluate_submission by passing a submission CSV path, data directory, competition ID, and output directory', 'review_evaluate_submission': 'review evaluate_submission to understand how it grades submissions, ranks scores, and generates medal thresholds', 'refactor_evaluate_submission': 'refactor evaluate_submission to support additional submission file formats beyond CSV'}
```

## File: facebookresearch_aira-dojo/src/dojo/tasks/mlebench/task.py

Prompts

```
['run evaluate_submission to grade a CSV submission file against an MLEBench competition and save a grading report', 'run is_lower_better to check if lower scores are better for a given MLEBench competition', 'test evaluate_submission by passing a submission CSV path, data directory, competition ID, and output directory', 'review evaluate_submission to understand how it grades submissions, ranks scores, and generates medal thresholds', 'refactor evaluate_submission to support additional submission file formats beyond CSV', 'create an MLEBenchTask instance with an MLEBenchTaskConfig to set up a machine learning benchmark task', 'prepare an MLEBenchTask by initializing the submission file path and task description for the solver interpreter', 'execute a single step of an MLEBenchTask by running solution code and evaluating the generated submission CSV', 'evaluate the fitness of a final solution by running it and scoring the submission against competition metrics', 'parse an evaluation report dictionary converting numeric values to floats for consistent scoring output']
```

Usage

```
{'create_MLEBenchTask': 'create an MLEBenchTask instance with an MLEBenchTaskConfig to set up a machine learning benchmark task', 'prepare_MLEBenchTask': 'prepare an MLEBenchTask by initializing the submission file path and task description for the solver interpreter', 'step_task_MLEBenchTask': 'execute a single step of an MLEBenchTask by running solution code and evaluating the generated submission CSV', 'evaluate_fitness_MLEBenchTask': 'evaluate the fitness of a final solution by running it and scoring the submission against competition metrics', 'parse_report_MLEBenchTask': 'parse an evaluation report dictionary converting numeric values to floats for consistent scoring output'}
```

