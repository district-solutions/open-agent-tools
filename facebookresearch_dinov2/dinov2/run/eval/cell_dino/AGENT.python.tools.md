# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/run/eval/cell_dino/knn.py

Prompts

```
['run k-NN evaluation for Cell-DINO and Channel-Adaptive DINO models using submitit job launcher', 'submit Evaluator jobs to the cluster for k-NN Cell-DINO evaluation via submit_jobs', 'setup Evaluator arguments with submitit JobEnvironment job ID and process group rank', 'checkpoint and requeue an Evaluator instance using submitit DelayedSubmission for fault tolerance', 'parse command-line arguments for k-NN Cell-DINO evaluation using the combined args parser', 'run the DINOv2 linear Cell-DINO evaluation using submitit job launcher with a config file', 'create an Evaluator instance with args to run linear evaluation on Cell-DINO data']
```

Usage

```
{'run_knn_evaluation': 'run k-NN evaluation for Cell-DINO and Channel-Adaptive DINO models using submitit job launcher', 'submit_evaluator_jobs': 'submit Evaluator jobs to the cluster for k-NN Cell-DINO evaluation via submit_jobs', 'setup_evaluator_args': 'setup Evaluator arguments with submitit JobEnvironment job ID and process group rank', 'checkpoint_evaluator': 'checkpoint and requeue an Evaluator instance using submitit DelayedSubmission for fault tolerance', 'parse_knn_args': 'parse command-line arguments for k-NN Cell-DINO evaluation using the combined args parser'}
```

## File: facebookresearch_dinov2/dinov2/run/eval/cell_dino/linear.py

Prompts

```
['run k-NN evaluation for Cell-DINO and Channel-Adaptive DINO models using submitit job launcher', 'submit Evaluator jobs to the cluster for k-NN Cell-DINO evaluation via submit_jobs', 'setup Evaluator arguments with submitit JobEnvironment job ID and process group rank', 'checkpoint and requeue an Evaluator instance using submitit DelayedSubmission for fault tolerance', 'parse command-line arguments for k-NN Cell-DINO evaluation using the combined args parser', 'run the DINOv2 linear Cell-DINO evaluation using submitit job launcher with a config file', 'create an Evaluator instance with args to run linear evaluation on Cell-DINO data']
```

Usage

```
{'run_linear_evaluation': 'run the DINOv2 linear Cell-DINO evaluation using submitit job launcher with a config file', 'submit_evaluator_jobs': 'submit Evaluator jobs to the cluster using submit_jobs for linear Cell-DINO evaluation', 'create_evaluator_instance': 'create an Evaluator instance with args to run linear evaluation on Cell-DINO data', 'setup_evaluator_args': 'setup evaluator arguments by replacing job ID placeholders and logging process group info', 'checkpoint_evaluator': 'checkpoint an Evaluator by requeuing it as a DelayedSubmission for fault tolerance'}
```

