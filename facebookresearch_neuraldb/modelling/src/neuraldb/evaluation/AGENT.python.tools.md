# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/modelling/src/neuraldb/evaluation/postprocess_baselines.py

Prompts

```
['get a compute_metrics function for evaluating baseline model predictions using a tokenizer and generator', 'postprocess predicted and label text by stripping special tokens and splitting on answer delimiters', 'compute exact match and F1 scores on decoded predictions with per-type and per-relation breakdowns', 'compute the average of a scoring function across all prediction-label pairs in the dataset', 'compute a scoring function broken down by metadata field like question type or relation', 'build a metrics computation function using get_spj_evaluation with a tokenizer and generator config', 'postprocess model predictions and labels by stripping special tokens and splitting by answer delimiter', 'compute exact match and case insensitive exact match scores between decoded predictions and labels', 'write prediction label and metadata pairs to a JSON lines file for later inspection', 'compute exact match breakdown scores grouped by question type and relation using breakdown_score', 'compute precision score by comparing actual and predicted label sets', 'compute recall score by comparing actual and predicted label sets', 'compute the F1 score from precision and recall values', 'calculate the average score across all instances using a scoring function', 'calculate per-group scores by metadata key using a scoring function']
```

Usage

```
{'get_baseline_evaluation': 'get a compute_metrics function for evaluating baseline model predictions using a tokenizer and generator', 'postprocess_text': 'postprocess predicted and label text by stripping special tokens and splitting on answer delimiters', 'compute_metrics': 'compute exact match and F1 scores on decoded predictions with per-type and per-relation breakdowns', 'average_score': 'compute the average of a scoring function across all prediction-label pairs in the dataset', 'breakdown_score': 'compute a scoring function broken down by metadata field like question type or relation'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/evaluation/postprocess_spj.py

Prompts

```
['get a compute_metrics function for evaluating baseline model predictions using a tokenizer and generator', 'postprocess predicted and label text by stripping special tokens and splitting on answer delimiters', 'compute exact match and F1 scores on decoded predictions with per-type and per-relation breakdowns', 'compute the average of a scoring function across all prediction-label pairs in the dataset', 'compute a scoring function broken down by metadata field like question type or relation', 'build a metrics computation function using get_spj_evaluation with a tokenizer and generator config', 'postprocess model predictions and labels by stripping special tokens and splitting by answer delimiter', 'compute exact match and case insensitive exact match scores between decoded predictions and labels', 'write prediction label and metadata pairs to a JSON lines file for later inspection', 'compute exact match breakdown scores grouped by question type and relation using breakdown_score', 'compute precision score by comparing actual and predicted label sets', 'compute recall score by comparing actual and predicted label sets', 'compute the F1 score from precision and recall values', 'calculate the average score across all instances using a scoring function', 'calculate per-group scores by metadata key using a scoring function']
```

Usage

```
{'build_evaluation_metrics': 'build a metrics computation function using get_spj_evaluation with a tokenizer and generator config', 'postprocess_predictions': 'postprocess model predictions and labels by stripping special tokens and splitting by answer delimiter', 'compute_exact_match': 'compute exact match and case insensitive exact match scores between decoded predictions and labels', 'write_predictions_file': 'write prediction label and metadata pairs to a JSON lines file for later inspection', 'breakdown_score_by_type': 'compute exact match breakdown scores grouped by question type and relation using breakdown_score'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/evaluation/scoring_functions.py

Prompts

```
['get a compute_metrics function for evaluating baseline model predictions using a tokenizer and generator', 'postprocess predicted and label text by stripping special tokens and splitting on answer delimiters', 'compute exact match and F1 scores on decoded predictions with per-type and per-relation breakdowns', 'compute the average of a scoring function across all prediction-label pairs in the dataset', 'compute a scoring function broken down by metadata field like question type or relation', 'build a metrics computation function using get_spj_evaluation with a tokenizer and generator config', 'postprocess model predictions and labels by stripping special tokens and splitting by answer delimiter', 'compute exact match and case insensitive exact match scores between decoded predictions and labels', 'write prediction label and metadata pairs to a JSON lines file for later inspection', 'compute exact match breakdown scores grouped by question type and relation using breakdown_score', 'compute precision score by comparing actual and predicted label sets', 'compute recall score by comparing actual and predicted label sets', 'compute the F1 score from precision and recall values', 'calculate the average score across all instances using a scoring function', 'calculate per-group scores by metadata key using a scoring function']
```

Usage

```
{'compute_precision': 'compute precision score by comparing actual and predicted label sets', 'compute_recall': 'compute recall score by comparing actual and predicted label sets', 'compute_f1': 'compute the F1 score from precision and recall values', 'calculate_average_score': 'calculate the average score across all instances using a scoring function', 'calculate_breakdown_score': 'calculate per-group scores by metadata key using a scoring function'}
```

