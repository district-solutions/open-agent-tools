# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/cotracker/evaluation/core/eval_utils.py

Prompts

```
['compute TAP-Vid metrics including Jaccard, points within threshold, and occlusion accuracy for video tracking predictions', 'run compute_tapvid_metrics with query points, ground truth occlusions, and predicted tracks to evaluate tracking performance', 'test compute_tapvid_metrics by passing numpy arrays for query points, ground truth, and predictions in first or strided mode', 'review compute_tapvid_metrics to understand how Jaccard and occlusion accuracy are computed across pixel thresholds', 'refactor compute_tapvid_metrics to support additional query modes beyond first and strided sampling strategies', 'run the Evaluator evaluate_sequence method to evaluate a CoTracker model on a test dataloader and return metrics', 'run the Evaluator compute_metrics method to compute tracking accuracy metrics for tapvid or dynamic_replica datasets', 'create an Evaluator instance with an experiment directory path for CoTracker model evaluation and visualization', 'test the Evaluator evaluate_sequence method with a tapvid dataset to compute query-based tracking metrics', 'test the Evaluator evaluate_sequence method with a CoTrackerThreeOnline model for online tracking evaluation']
```

Usage

```
{'compute_tapvid_metrics': 'compute TAP-Vid metrics including Jaccard, points within threshold, and occlusion accuracy for video tracking predictions', 'run_compute_tapvid_metrics': 'run compute_tapvid_metrics with query points, ground truth occlusions, and predicted tracks to evaluate tracking performance', 'test_compute_tapvid_metrics': 'test compute_tapvid_metrics by passing numpy arrays for query points, ground truth, and predictions in first or strided mode', 'review_compute_tapvid_metrics': 'review compute_tapvid_metrics to understand how Jaccard and occlusion accuracy are computed across pixel thresholds', 'refactor_compute_tapvid_metrics': 'refactor compute_tapvid_metrics to support additional query modes beyond first and strided sampling strategies'}
```

## File: facebookresearch_co-tracker/cotracker/evaluation/core/evaluator.py

Prompts

```
['compute TAP-Vid metrics including Jaccard, points within threshold, and occlusion accuracy for video tracking predictions', 'run compute_tapvid_metrics with query points, ground truth occlusions, and predicted tracks to evaluate tracking performance', 'test compute_tapvid_metrics by passing numpy arrays for query points, ground truth, and predictions in first or strided mode', 'review compute_tapvid_metrics to understand how Jaccard and occlusion accuracy are computed across pixel thresholds', 'refactor compute_tapvid_metrics to support additional query modes beyond first and strided sampling strategies', 'run the Evaluator evaluate_sequence method to evaluate a CoTracker model on a test dataloader and return metrics', 'run the Evaluator compute_metrics method to compute tracking accuracy metrics for tapvid or dynamic_replica datasets', 'create an Evaluator instance with an experiment directory path for CoTracker model evaluation and visualization', 'test the Evaluator evaluate_sequence method with a tapvid dataset to compute query-based tracking metrics', 'test the Evaluator evaluate_sequence method with a CoTrackerThreeOnline model for online tracking evaluation']
```

Usage

```
{'run_Evaluator_evaluate_sequence': 'run the Evaluator evaluate_sequence method to evaluate a CoTracker model on a test dataloader and return metrics', 'run_Evaluator_compute_metrics': 'run the Evaluator compute_metrics method to compute tracking accuracy metrics for tapvid or dynamic_replica datasets', 'create_Evaluator_instance': 'create an Evaluator instance with an experiment directory path for CoTracker model evaluation and visualization', 'test_Evaluator_tapvid_evaluation': 'test the Evaluator evaluate_sequence method with a tapvid dataset to compute query-based tracking metrics', 'test_Evaluator_online_model': 'test the Evaluator evaluate_sequence method with a CoTrackerThreeOnline model for online tracking evaluation'}
```

