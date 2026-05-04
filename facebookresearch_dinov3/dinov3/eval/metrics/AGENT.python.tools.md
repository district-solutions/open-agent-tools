# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/metrics/classification.py

Prompts

```
['build a classification metric collection from a ClassificationMetricType enum and number of classes', 'build a top-k multiclass accuracy metric collection with configurable averaging method and k values', 'build a top-k multiclass recall metric collection with configurable averaging method and k values', 'create an AnyMatchAccuracy metric that checks if any top-k prediction matches a list of targets', 'compute top-k accuracy percentages for model output predictions against target labels', 'create an ImageNet_C_Metric instance to track model accuracy across ImageNet-C corruption types and severity levels', 'call update on ImageNet_C_Metric with model predictions and target tensors to accumulate per-corruption accuracy', 'call compute on ImageNet_C_Metric to get the Mean Corruption Error score as a top-1 tensor', 'compute the relative average corruption error score by comparing model scores against AlexNet inverse reference scores', 'use CORRUPTION_LEVEL_TO_ID to map a corruption type and severity level pair to its integer bucket index']
```

Usage

```
{'build_classification_metric': 'build a classification metric collection from a ClassificationMetricType enum and number of classes', 'build_topk_accuracy_metric': 'build a top-k multiclass accuracy metric collection with configurable averaging method and k values', 'build_topk_recall_metric': 'build a top-k multiclass recall metric collection with configurable averaging method and k values', 'AnyMatchAccuracy': 'create an AnyMatchAccuracy metric that checks if any top-k prediction matches a list of targets', 'accuracy': 'compute top-k accuracy percentages for model output predictions against target labels'}
```

## File: facebookresearch_dinov3/dinov3/eval/metrics/imagenet_c.py

Prompts

```
['build a classification metric collection from a ClassificationMetricType enum and number of classes', 'build a top-k multiclass accuracy metric collection with configurable averaging method and k values', 'build a top-k multiclass recall metric collection with configurable averaging method and k values', 'create an AnyMatchAccuracy metric that checks if any top-k prediction matches a list of targets', 'compute top-k accuracy percentages for model output predictions against target labels', 'create an ImageNet_C_Metric instance to track model accuracy across ImageNet-C corruption types and severity levels', 'call update on ImageNet_C_Metric with model predictions and target tensors to accumulate per-corruption accuracy', 'call compute on ImageNet_C_Metric to get the Mean Corruption Error score as a top-1 tensor', 'compute the relative average corruption error score by comparing model scores against AlexNet inverse reference scores', 'use CORRUPTION_LEVEL_TO_ID to map a corruption type and severity level pair to its integer bucket index']
```

Usage

```
{'use_ImageNet_C_Metric': 'create an ImageNet_C_Metric instance to track model accuracy across ImageNet-C corruption types and severity levels', 'update_ImageNet_C_Metric': 'call update on ImageNet_C_Metric with model predictions and target tensors to accumulate per-corruption accuracy', 'compute_ImageNet_C_Metric': 'call compute on ImageNet_C_Metric to get the Mean Corruption Error score as a top-1 tensor', 'compute_relative_average_scores': 'compute the relative average corruption error score by comparing model scores against AlexNet inverse reference scores', 'lookup_CORRUPTION_LEVEL_TO_ID': 'use CORRUPTION_LEVEL_TO_ID to map a corruption type and severity level pair to its integer bucket index'}
```

