# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/metrics/_base_metric.py

Prompts

```
['eval a tracking sequence and compute metric results from raw data', 'combine per-sequence metric results into aggregated results across all sequences', 'print a formatted results table for a tracker across all sequences and classes', 'return a simple summary dictionary of final results for a tracker from combined sequence data', 'return detailed per-sequence results with array labels and AUC fields for a tracker', 'create a TETA metric instance for evaluating track accuracy with configurable exhaustive mode', 'run TETA metric evaluation on a single tracking sequence across all IoU thresholds', 'compute global alignment score between ground truth and predicted track IDs', 'combine TETA metric results across multiple evaluation sequences into aggregated scores', 'compute optimal ground-truth to track matches using Hungarian algorithm at each IoU threshold']
```

Usage

```
{'eval_sequence_metric': 'eval a tracking sequence and compute metric results from raw data', 'combine_sequences_metrics': 'combine per-sequence metric results into aggregated results across all sequences', 'print_table_results': 'print a formatted results table for a tracker across all sequences and classes', 'summary_results_tracker': 'return a simple summary dictionary of final results for a tracker from combined sequence data', 'detailed_results_tracker': 'return detailed per-sequence results with array labels and AUC fields for a tracker'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/metrics/teta.py

Prompts

```
['eval a tracking sequence and compute metric results from raw data', 'combine per-sequence metric results into aggregated results across all sequences', 'print a formatted results table for a tracker across all sequences and classes', 'return a simple summary dictionary of final results for a tracker from combined sequence data', 'return detailed per-sequence results with array labels and AUC fields for a tracker', 'create a TETA metric instance for evaluating track accuracy with configurable exhaustive mode', 'run TETA metric evaluation on a single tracking sequence across all IoU thresholds', 'compute global alignment score between ground truth and predicted track IDs', 'combine TETA metric results across multiple evaluation sequences into aggregated scores', 'compute optimal ground-truth to track matches using Hungarian algorithm at each IoU threshold']
```

Usage

```
{'create_TETA_metric': 'create a TETA metric instance for evaluating track accuracy with configurable exhaustive mode', 'run_eval_sequence': 'run TETA metric evaluation on a single tracking sequence across all IoU thresholds', 'compute_global_alignment_score': 'compute global alignment score between ground truth and predicted track IDs', 'combine_sequences': 'combine TETA metric results across multiple evaluation sequences into aggregated scores', 'compute_matches': 'compute optimal ground-truth to track matches using Hungarian algorithm at each IoU threshold'}
```

