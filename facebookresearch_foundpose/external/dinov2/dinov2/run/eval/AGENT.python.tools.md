# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/run/eval/knn.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit job launcher with a config file', 'run the Evaluator class to execute k-NN evaluation on a dataset with provided args', 'run the Evaluator checkpoint method to requeue a failed submitit job for retry', 'run the Evaluator _setup_args method to configure job environment and output directory', 'run the main function to parse args and submit DINOv2 k-NN evaluation jobs via submitit', 'run a DINOv2 linear evaluation job using submitit with a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation arguments and execution', 'submit DINOv2 linear evaluation jobs to a cluster using submitit with the Evaluator class', 'setup evaluation arguments by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator by returning a DelayedSubmission for requeuing on failure', 'run the DINOv2 logistic regression evaluation using submitit job launcher with a config file', 'submit DINOv2 logistic regression evaluation jobs to a cluster using the submit_jobs function', 'setup checkpointing for the Evaluator class to requeue failed log regression jobs via submitit', 'review the Evaluator _setup_args method that configures output directory with submitit job ID']
```

Usage

```
{'run_knn_evaluation': 'run the DINOv2 k-NN evaluation using submitit job launcher with a config file', 'run_Evaluator_call': 'run the Evaluator class to execute k-NN evaluation on a dataset with provided args', 'run_Evaluator_checkpoint': 'run the Evaluator checkpoint method to requeue a failed submitit job for retry', 'run_Evaluator_setup_args': 'run the Evaluator _setup_args method to configure job environment and output directory', 'run_main': 'run the main function to parse args and submit DINOv2 k-NN evaluation jobs via submitit'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/run/eval/linear.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit job launcher with a config file', 'run the Evaluator class to execute k-NN evaluation on a dataset with provided args', 'run the Evaluator checkpoint method to requeue a failed submitit job for retry', 'run the Evaluator _setup_args method to configure job environment and output directory', 'run the main function to parse args and submit DINOv2 k-NN evaluation jobs via submitit', 'run a DINOv2 linear evaluation job using submitit with a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation arguments and execution', 'submit DINOv2 linear evaluation jobs to a cluster using submitit with the Evaluator class', 'setup evaluation arguments by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator by returning a DelayedSubmission for requeuing on failure', 'run the DINOv2 logistic regression evaluation using submitit job launcher with a config file', 'submit DINOv2 logistic regression evaluation jobs to a cluster using the submit_jobs function', 'setup checkpointing for the Evaluator class to requeue failed log regression jobs via submitit', 'review the Evaluator _setup_args method that configures output directory with submitit job ID']
```

Usage

```
{'run_linear_evaluation': 'run a DINOv2 linear evaluation job using submitit with a config file', 'create_Evaluator_class': 'create an Evaluator instance that wraps DINOv2 linear evaluation arguments and execution', 'submit_jobs_linear': 'submit DINOv2 linear evaluation jobs to a cluster using submitit with the Evaluator class', 'setup_eval_args': 'setup evaluation arguments by replacing job ID placeholders and logging process group info', 'checkpoint_Evaluator': 'checkpoint an Evaluator by returning a DelayedSubmission for requeuing on failure'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/run/eval/log_regression.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit job launcher with a config file', 'run the Evaluator class to execute k-NN evaluation on a dataset with provided args', 'run the Evaluator checkpoint method to requeue a failed submitit job for retry', 'run the Evaluator _setup_args method to configure job environment and output directory', 'run the main function to parse args and submit DINOv2 k-NN evaluation jobs via submitit', 'run a DINOv2 linear evaluation job using submitit with a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation arguments and execution', 'submit DINOv2 linear evaluation jobs to a cluster using submitit with the Evaluator class', 'setup evaluation arguments by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator by returning a DelayedSubmission for requeuing on failure', 'run the DINOv2 logistic regression evaluation using submitit job launcher with a config file', 'submit DINOv2 logistic regression evaluation jobs to a cluster using the submit_jobs function', 'setup checkpointing for the Evaluator class to requeue failed log regression jobs via submitit', 'review the Evaluator _setup_args method that configures output directory with submitit job ID']
```

Usage

```
{'run_log_regression_evaluation': 'run the DINOv2 logistic regression evaluation using submitit job launcher with a config file', 'create_Evaluator_class': 'create an Evaluator instance that wraps DINOv2 log regression main with submitit job environment setup', 'submit_log_regression_jobs': 'submit DINOv2 logistic regression evaluation jobs to a cluster using the submit_jobs function', 'setup_Evaluator_checkpoint': 'setup checkpointing for the Evaluator class to requeue failed log regression jobs via submitit', 'review_Evaluator_setup_args': 'review the Evaluator _setup_args method that configures output directory with submitit job ID'}
```

