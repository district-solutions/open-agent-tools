# Agent Python Tools

- repo: facebookresearch/fairselfsupervisionbenchmark
- repo_uri: https://github.com/facebookresearch/fair_self_supervision_benchmark

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/metrics/metrics_ap.py

Prompts

```
['create an APMetricsCalculator instance to track mAP metrics for a model split', 'finalize accumulated metrics and compute the final mAP for the current split', 'compute mean average precision from prediction and ground truth numpy arrays', 'compute mAP across multiple GPU devices by fetching blobs from Caffe2 workspace', 'get computed mAP metrics as a JSON dictionary for the current split', 'sum blob values across all devices using Caffe2 workspace FetchBlob', 'print a JSON-formatted dictionary of training and evaluation statistics to stdout', 'build a JSON stats dictionary from train and test metrics calculators with model info', 'review the get_json_stats_dict function to understand how training metrics are aggregated into JSON', 'refactor sum_multi_device_blob to support a custom device range instead of cfg.NUM_DEVICES', 'build a TopkMetricsCalculator instance to track top1 and top5 error metrics across training iterations', 'run compute_topk_accuracy to calculate top-k accuracy from softmax predictions and ground truth labels', 'run compute_multi_device_topk_accuracy to aggregate top-k accuracy across all GPU devices in a multi-GPU setup', 'test the TopkMetricsCalculator get_split_err method to compute per-blob error rates from Caffe2 workspace blobs', 'refactor the TopkMetricsCalculator finalize_metrics method to normalize accumulated loss and error metrics by total sample count']
```

Usage

```
{'create_APMetricsCalculator': 'create an APMetricsCalculator instance to track mAP metrics for a model split', 'finalize_metrics_APMetricsCalculator': 'finalize accumulated metrics and compute the final mAP for the current split', 'compute_mAP': 'compute mean average precision from prediction and ground truth numpy arrays', 'compute_multi_device_mAP': 'compute mAP across multiple GPU devices by fetching blobs from Caffe2 workspace', 'get_computed_metrics_APMetricsCalculator': 'get computed mAP metrics as a JSON dictionary for the current split'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/metrics/metrics_helper.py

Prompts

```
['create an APMetricsCalculator instance to track mAP metrics for a model split', 'finalize accumulated metrics and compute the final mAP for the current split', 'compute mean average precision from prediction and ground truth numpy arrays', 'compute mAP across multiple GPU devices by fetching blobs from Caffe2 workspace', 'get computed mAP metrics as a JSON dictionary for the current split', 'sum blob values across all devices using Caffe2 workspace FetchBlob', 'print a JSON-formatted dictionary of training and evaluation statistics to stdout', 'build a JSON stats dictionary from train and test metrics calculators with model info', 'review the get_json_stats_dict function to understand how training metrics are aggregated into JSON', 'refactor sum_multi_device_blob to support a custom device range instead of cfg.NUM_DEVICES', 'build a TopkMetricsCalculator instance to track top1 and top5 error metrics across training iterations', 'run compute_topk_accuracy to calculate top-k accuracy from softmax predictions and ground truth labels', 'run compute_multi_device_topk_accuracy to aggregate top-k accuracy across all GPU devices in a multi-GPU setup', 'test the TopkMetricsCalculator get_split_err method to compute per-blob error rates from Caffe2 workspace blobs', 'refactor the TopkMetricsCalculator finalize_metrics method to normalize accumulated loss and error metrics by total sample count']
```

Usage

```
{'sum_multi_device_blob': 'sum blob values across all devices using Caffe2 workspace FetchBlob', 'print_json_stats': 'print a JSON-formatted dictionary of training and evaluation statistics to stdout', 'get_json_stats_dict': 'build a JSON stats dictionary from train and test metrics calculators with model info', 'review_get_json_stats_dict': 'review the get_json_stats_dict function to understand how training metrics are aggregated into JSON', 'refactor_sum_multi_device_blob': 'refactor sum_multi_device_blob to support a custom device range instead of cfg.NUM_DEVICES'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/metrics/metrics_topk.py

Prompts

```
['create an APMetricsCalculator instance to track mAP metrics for a model split', 'finalize accumulated metrics and compute the final mAP for the current split', 'compute mean average precision from prediction and ground truth numpy arrays', 'compute mAP across multiple GPU devices by fetching blobs from Caffe2 workspace', 'get computed mAP metrics as a JSON dictionary for the current split', 'sum blob values across all devices using Caffe2 workspace FetchBlob', 'print a JSON-formatted dictionary of training and evaluation statistics to stdout', 'build a JSON stats dictionary from train and test metrics calculators with model info', 'review the get_json_stats_dict function to understand how training metrics are aggregated into JSON', 'refactor sum_multi_device_blob to support a custom device range instead of cfg.NUM_DEVICES', 'build a TopkMetricsCalculator instance to track top1 and top5 error metrics across training iterations', 'run compute_topk_accuracy to calculate top-k accuracy from softmax predictions and ground truth labels', 'run compute_multi_device_topk_accuracy to aggregate top-k accuracy across all GPU devices in a multi-GPU setup', 'test the TopkMetricsCalculator get_split_err method to compute per-blob error rates from Caffe2 workspace blobs', 'refactor the TopkMetricsCalculator finalize_metrics method to normalize accumulated loss and error metrics by total sample count']
```

Usage

```
{'build_TopkMetricsCalculator': 'build a TopkMetricsCalculator instance to track top1 and top5 error metrics across training iterations', 'run_compute_topk_accuracy': 'run compute_topk_accuracy to calculate top-k accuracy from softmax predictions and ground truth labels', 'run_compute_multi_device_topk_accuracy': 'run compute_multi_device_topk_accuracy to aggregate top-k accuracy across all GPU devices in a multi-GPU setup', 'test_TopkMetricsCalculator_get_split_err': 'test the TopkMetricsCalculator get_split_err method to compute per-blob error rates from Caffe2 workspace blobs', 'refactor_TopkMetricsCalculator_finalize_metrics': 'refactor the TopkMetricsCalculator finalize_metrics method to normalize accumulated loss and error metrics by total sample count'}
```

