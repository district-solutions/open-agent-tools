# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/run/eval/knn.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit to launch distributed jobs via the main entry point', 'run the Evaluator class call method to execute k-NN evaluation with configured arguments and job setup', 'run the Evaluator checkpoint method to requeue a submitit job with DelayedSubmission for fault tolerance', 'run the Evaluator _setup_args method to configure output directory with job ID and log process group info', 'run the main function to parse k-NN arguments, setup logging, validate config, and submit evaluation jobs', 'run a submitit job to perform linear evaluation on DINOv2 features using a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation with submitit checkpoint support', 'setup the Evaluator args by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator to requeue it as a DelayedSubmission for fault-tolerant execution', 'call the Evaluator to invoke DINOv2 linear evaluation main with the configured args', 'run the DINOv2 logistic regression evaluation using submitit to launch distributed jobs via a config file', 'create an Evaluator instance that wraps args and calls log_regression_main when invoked as a callable', 'submit DINOv2 logistic regression evaluation jobs to a cluster using submitit with a config file and Evaluator class', 'checkpoint an Evaluator by requeuing it as a DelayedSubmission for submitit job resubmission on failure']
```

Usage

```
{'run_knn_evaluation': 'run the DINOv2 k-NN evaluation using submitit to launch distributed jobs via the main entry point', 'run_evaluator_call': 'run the Evaluator class call method to execute k-NN evaluation with configured arguments and job setup', 'run_evaluator_checkpoint': 'run the Evaluator checkpoint method to requeue a submitit job with DelayedSubmission for fault tolerance', 'run_evaluator_setup_args': 'run the Evaluator _setup_args method to configure output directory with job ID and log process group info', 'run_main_entry': 'run the main function to parse k-NN arguments, setup logging, validate config, and submit evaluation jobs'}
```

## File: facebookresearch_dinov2/dinov2/run/eval/linear.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit to launch distributed jobs via the main entry point', 'run the Evaluator class call method to execute k-NN evaluation with configured arguments and job setup', 'run the Evaluator checkpoint method to requeue a submitit job with DelayedSubmission for fault tolerance', 'run the Evaluator _setup_args method to configure output directory with job ID and log process group info', 'run the main function to parse k-NN arguments, setup logging, validate config, and submit evaluation jobs', 'run a submitit job to perform linear evaluation on DINOv2 features using a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation with submitit checkpoint support', 'setup the Evaluator args by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator to requeue it as a DelayedSubmission for fault-tolerant execution', 'call the Evaluator to invoke DINOv2 linear evaluation main with the configured args', 'run the DINOv2 logistic regression evaluation using submitit to launch distributed jobs via a config file', 'create an Evaluator instance that wraps args and calls log_regression_main when invoked as a callable', 'submit DINOv2 logistic regression evaluation jobs to a cluster using submitit with a config file and Evaluator class', 'checkpoint an Evaluator by requeuing it as a DelayedSubmission for submitit job resubmission on failure']
```

Usage

```
{'run_linear_evaluation': 'run a submitit job to perform linear evaluation on DINOv2 features using a config file', 'create_evaluator_class': 'create an Evaluator instance that wraps DINOv2 linear evaluation with submitit checkpoint support', 'setup_evaluator_args': 'setup the Evaluator args by replacing job ID placeholders and logging process group info', 'checkpoint_evaluator': 'checkpoint an Evaluator to requeue it as a DelayedSubmission for fault-tolerant execution', 'call_evaluator': 'call the Evaluator to invoke DINOv2 linear evaluation main with the configured args'}
```

## File: facebookresearch_dinov2/dinov2/run/eval/log_regression.py

Prompts

```
['run the DINOv2 k-NN evaluation using submitit to launch distributed jobs via the main entry point', 'run the Evaluator class call method to execute k-NN evaluation with configured arguments and job setup', 'run the Evaluator checkpoint method to requeue a submitit job with DelayedSubmission for fault tolerance', 'run the Evaluator _setup_args method to configure output directory with job ID and log process group info', 'run the main function to parse k-NN arguments, setup logging, validate config, and submit evaluation jobs', 'run a submitit job to perform linear evaluation on DINOv2 features using a config file', 'create an Evaluator instance that wraps DINOv2 linear evaluation with submitit checkpoint support', 'setup the Evaluator args by replacing job ID placeholders and logging process group info', 'checkpoint an Evaluator to requeue it as a DelayedSubmission for fault-tolerant execution', 'call the Evaluator to invoke DINOv2 linear evaluation main with the configured args', 'run the DINOv2 logistic regression evaluation using submitit to launch distributed jobs via a config file', 'create an Evaluator instance that wraps args and calls log_regression_main when invoked as a callable', 'submit DINOv2 logistic regression evaluation jobs to a cluster using submitit with a config file and Evaluator class', 'checkpoint an Evaluator by requeuing it as a DelayedSubmission for submitit job resubmission on failure']
```

Usage

```
{'run_log_regression_evaluation': 'run the DINOv2 logistic regression evaluation using submitit to launch distributed jobs via a config file', 'create_Evaluator_class': 'create an Evaluator instance that wraps args and calls log_regression_main when invoked as a callable', 'submit_log_regression_jobs': 'submit DINOv2 logistic regression evaluation jobs to a cluster using submitit with a config file and Evaluator class', 'setup_evaluator_args': 'setup the Evaluator args by replacing job ID placeholders and logging process group task information', 'checkpoint_Evaluator': 'checkpoint an Evaluator by requeuing it as a DelayedSubmission for submitit job resubmission on failure'}
```

