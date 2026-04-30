# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/metrics/_base_metric.py

Prompts

```
['build a python class that extends _BaseMetric to implement a tracking evaluation metric', 'run the eval_sequence method to evaluate tracking data for a single sequence', 'combine sequence results via sum or weighted average using combine_sequences', 'print a formatted results table for all sequences and a combined summary row', 'summarize final tracker results by extracting summary fields from combined sequence results', 'create a Count metric instance to tally tracker and ground truth detections and IDs', 'combine sequences using Count metric to sum detections and IDs across all sequences', 'combine classes class-averaged using Count metric to average detection counts across classes', 'combine classes detection-averaged using Count metric to sum detection counts across classes', 'eval the HOTA metrics for a single tracking sequence given gt and tracker detection data', 'combine HOTA metrics across multiple sequences into aggregated results', 'combine HOTA metrics across all classes by averaging over detection values', 'compute derived sub-metric fields like DetRe, DetPr, DetA, HOTA, and OWTA from raw counts', 'plot HOTA metric results as curves over alpha thresholds for a tracker and class']
```

Usage

```
{'build_metric_class': 'build a python class that extends _BaseMetric to implement a tracking evaluation metric', 'run_eval_sequence': 'run the eval_sequence method to evaluate tracking data for a single sequence', 'combine_sequences': 'combine sequence results via sum or weighted average using combine_sequences', 'print_table': 'print a formatted results table for all sequences and a combined summary row', 'summarize_results': 'summarize final tracker results by extracting summary fields from combined sequence results'}
```

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/metrics/count.py

Prompts

```
['build a python class that extends _BaseMetric to implement a tracking evaluation metric', 'run the eval_sequence method to evaluate tracking data for a single sequence', 'combine sequence results via sum or weighted average using combine_sequences', 'print a formatted results table for all sequences and a combined summary row', 'summarize final tracker results by extracting summary fields from combined sequence results', 'create a Count metric instance to tally tracker and ground truth detections and IDs', 'combine sequences using Count metric to sum detections and IDs across all sequences', 'combine classes class-averaged using Count metric to average detection counts across classes', 'combine classes detection-averaged using Count metric to sum detection counts across classes', 'eval the HOTA metrics for a single tracking sequence given gt and tracker detection data', 'combine HOTA metrics across multiple sequences into aggregated results', 'combine HOTA metrics across all classes by averaging over detection values', 'compute derived sub-metric fields like DetRe, DetPr, DetA, HOTA, and OWTA from raw counts', 'plot HOTA metric results as curves over alpha thresholds for a tracker and class']
```

Usage

```
{'create_Count_metric': 'create a Count metric instance to tally tracker and ground truth detections and IDs', 'run_eval_sequence': 'run eval_sequence on a Count metric to get detection, ID, and frame counts for one sequence', 'combine_sequences_Count': 'combine sequences using Count metric to sum detections and IDs across all sequences', 'combine_classes_class_averaged_Count': 'combine classes class-averaged using Count metric to average detection counts across classes', 'combine_classes_det_averaged_Count': 'combine classes detection-averaged using Count metric to sum detection counts across classes'}
```

## File: facebookresearch_sam3/sam3/eval/hota_eval_toolkit/trackeval/metrics/hota.py

Prompts

```
['build a python class that extends _BaseMetric to implement a tracking evaluation metric', 'run the eval_sequence method to evaluate tracking data for a single sequence', 'combine sequence results via sum or weighted average using combine_sequences', 'print a formatted results table for all sequences and a combined summary row', 'summarize final tracker results by extracting summary fields from combined sequence results', 'create a Count metric instance to tally tracker and ground truth detections and IDs', 'combine sequences using Count metric to sum detections and IDs across all sequences', 'combine classes class-averaged using Count metric to average detection counts across classes', 'combine classes detection-averaged using Count metric to sum detection counts across classes', 'eval the HOTA metrics for a single tracking sequence given gt and tracker detection data', 'combine HOTA metrics across multiple sequences into aggregated results', 'combine HOTA metrics across all classes by averaging over detection values', 'compute derived sub-metric fields like DetRe, DetPr, DetA, HOTA, and OWTA from raw counts', 'plot HOTA metric results as curves over alpha thresholds for a tracker and class']
```

Usage

```
{'eval_sequence_hota_metrics': 'eval the HOTA metrics for a single tracking sequence given gt and tracker detection data', 'combine_sequences_hota_metrics': 'combine HOTA metrics across multiple sequences into aggregated results', 'combine_classes_det_averaged': 'combine HOTA metrics across all classes by averaging over detection values', 'compute_final_fields_hota': 'compute derived sub-metric fields like DetRe, DetPr, DetA, HOTA, and OWTA from raw counts', 'plot_single_tracker_results_hota': 'plot HOTA metric results as curves over alpha thresholds for a tracker and class'}
```

