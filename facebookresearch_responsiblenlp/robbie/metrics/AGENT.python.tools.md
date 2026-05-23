# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/robbie/metrics/_base.py

Prompts

```
['build a Metric instance from argparse args using the Metric.build class method', 'add metric and metric batch size arguments to an argparse ArgumentParser using Metric.add_args', 'create a MetricConfig dataclass with a custom batch size for metric evaluation', 'score an iterator of Prediction objects and return a MetricResult with scores and stats', 'create a Score dataclass with a float score, label, prompt, prediction, and metadata dict', 'create an HFClassifierMetric instance with a HuggingFace model ID, labels, and batch config', 'build an HFClassifierMetric from CLI args using the from_args class method', 'run the score method on an iterator of Prediction objects to get a MetricResult', 'review the lazy-loaded HuggingFace sequence classification model and tokenizer properties', 'refactor the summarize callback to aggregate Score objects into custom statistics', 'build a python module that uses the Perspective API to score text toxicity for model predictions', 'create a function that returns a Score with score -1 for failed predictions', 'test the PerspeciveMetric class score method by passing an iterator of Prediction objects', 'refactor the _get_toxicity_score method to support additional toxicity attributes beyond TOXICITY', 'review the retryable function that checks for HTTP 429, 500, and 503 status codes', 'truncate model generation to first sentence and mask demographic descriptors with XYZ placeholder', 'calculate overall and per-group negativity rates from a list of Regard classifier scores', 'register the regard metric using the sasha/regardv3 HuggingFace classifier model with custom preprocessing', 'map integer indices to sentiment labels neg, neutral, pos, and other for the Regard classifier']
```

Usage

```
{'build_metric_from_args': 'build a Metric instance from argparse args using the Metric.build class method', 'add_metric_args': 'add metric and metric batch size arguments to an argparse ArgumentParser using Metric.add_args', 'create_metric_config': 'create a MetricConfig dataclass with a custom batch size for metric evaluation', 'score_predictions': 'score an iterator of Prediction objects and return a MetricResult with scores and stats', 'create_score': 'create a Score dataclass with a float score, label, prompt, prediction, and metadata dict'}
```

## File: facebookresearch_responsiblenlp/robbie/metrics/hf.py

Prompts

```
['build a Metric instance from argparse args using the Metric.build class method', 'add metric and metric batch size arguments to an argparse ArgumentParser using Metric.add_args', 'create a MetricConfig dataclass with a custom batch size for metric evaluation', 'score an iterator of Prediction objects and return a MetricResult with scores and stats', 'create a Score dataclass with a float score, label, prompt, prediction, and metadata dict', 'create an HFClassifierMetric instance with a HuggingFace model ID, labels, and batch config', 'build an HFClassifierMetric from CLI args using the from_args class method', 'run the score method on an iterator of Prediction objects to get a MetricResult', 'review the lazy-loaded HuggingFace sequence classification model and tokenizer properties', 'refactor the summarize callback to aggregate Score objects into custom statistics', 'build a python module that uses the Perspective API to score text toxicity for model predictions', 'create a function that returns a Score with score -1 for failed predictions', 'test the PerspeciveMetric class score method by passing an iterator of Prediction objects', 'refactor the _get_toxicity_score method to support additional toxicity attributes beyond TOXICITY', 'review the retryable function that checks for HTTP 429, 500, and 503 status codes', 'truncate model generation to first sentence and mask demographic descriptors with XYZ placeholder', 'calculate overall and per-group negativity rates from a list of Regard classifier scores', 'register the regard metric using the sasha/regardv3 HuggingFace classifier model with custom preprocessing', 'map integer indices to sentiment labels neg, neutral, pos, and other for the Regard classifier']
```

Usage

```
{'create_HFClassifierMetric': 'create an HFClassifierMetric instance with a HuggingFace model ID, labels, and batch config', 'build_HFClassifierMetric_from_args': 'build an HFClassifierMetric from CLI args using the from_args class method', 'run_HFClassifierMetric_score': 'run the score method on an iterator of Prediction objects to get a MetricResult', 'review_HFClassifierMetric_model': 'review the lazy-loaded HuggingFace sequence classification model and tokenizer properties', 'refactor_HFClassifierMetric_summarize': 'refactor the summarize callback to aggregate Score objects into custom statistics'}
```

## File: facebookresearch_responsiblenlp/robbie/metrics/perspective.py

Prompts

```
['build a Metric instance from argparse args using the Metric.build class method', 'add metric and metric batch size arguments to an argparse ArgumentParser using Metric.add_args', 'create a MetricConfig dataclass with a custom batch size for metric evaluation', 'score an iterator of Prediction objects and return a MetricResult with scores and stats', 'create a Score dataclass with a float score, label, prompt, prediction, and metadata dict', 'create an HFClassifierMetric instance with a HuggingFace model ID, labels, and batch config', 'build an HFClassifierMetric from CLI args using the from_args class method', 'run the score method on an iterator of Prediction objects to get a MetricResult', 'review the lazy-loaded HuggingFace sequence classification model and tokenizer properties', 'refactor the summarize callback to aggregate Score objects into custom statistics', 'build a python module that uses the Perspective API to score text toxicity for model predictions', 'create a function that returns a Score with score -1 for failed predictions', 'test the PerspeciveMetric class score method by passing an iterator of Prediction objects', 'refactor the _get_toxicity_score method to support additional toxicity attributes beyond TOXICITY', 'review the retryable function that checks for HTTP 429, 500, and 503 status codes', 'truncate model generation to first sentence and mask demographic descriptors with XYZ placeholder', 'calculate overall and per-group negativity rates from a list of Regard classifier scores', 'register the regard metric using the sasha/regardv3 HuggingFace classifier model with custom preprocessing', 'map integer indices to sentiment labels neg, neutral, pos, and other for the Regard classifier']
```

Usage

```
{'build_perspective_toxicity_scoring': 'build a python module that uses the Perspective API to score text toxicity for model predictions', 'create_failed_score_function': 'create a function that returns a Score with score -1 for failed predictions', 'test_PerspeciveMetric_score': 'test the PerspeciveMetric class score method by passing an iterator of Prediction objects', 'refactor_get_toxicity_score': 'refactor the _get_toxicity_score method to support additional toxicity attributes beyond TOXICITY', 'review_retryable_function': 'review the retryable function that checks for HTTP 429, 500, and 503 status codes'}
```

## File: facebookresearch_responsiblenlp/robbie/metrics/regard.py

Prompts

```
['build a Metric instance from argparse args using the Metric.build class method', 'add metric and metric batch size arguments to an argparse ArgumentParser using Metric.add_args', 'create a MetricConfig dataclass with a custom batch size for metric evaluation', 'score an iterator of Prediction objects and return a MetricResult with scores and stats', 'create a Score dataclass with a float score, label, prompt, prediction, and metadata dict', 'create an HFClassifierMetric instance with a HuggingFace model ID, labels, and batch config', 'build an HFClassifierMetric from CLI args using the from_args class method', 'run the score method on an iterator of Prediction objects to get a MetricResult', 'review the lazy-loaded HuggingFace sequence classification model and tokenizer properties', 'refactor the summarize callback to aggregate Score objects into custom statistics', 'build a python module that uses the Perspective API to score text toxicity for model predictions', 'create a function that returns a Score with score -1 for failed predictions', 'test the PerspeciveMetric class score method by passing an iterator of Prediction objects', 'refactor the _get_toxicity_score method to support additional toxicity attributes beyond TOXICITY', 'review the retryable function that checks for HTTP 429, 500, and 503 status codes', 'truncate model generation to first sentence and mask demographic descriptors with XYZ placeholder', 'calculate overall and per-group negativity rates from a list of Regard classifier scores', 'register the regard metric using the sasha/regardv3 HuggingFace classifier model with custom preprocessing', 'map integer indices to sentiment labels neg, neutral, pos, and other for the Regard classifier']
```

Usage

```
{'preprocess_Prediction': 'truncate model generation to first sentence and mask demographic descriptors with XYZ placeholder', 'summarize_Scores': 'calculate overall and per-group negativity rates from a list of Regard classifier scores', 'register_Metric_regard': 'register the regard metric using the sasha/regardv3 HuggingFace classifier model with custom preprocessing', 'use_LABELS': 'map integer indices to sentiment labels neg, neutral, pos, and other for the Regard classifier', 'create_HFClassifierMetric': 'build an HFClassifierMetric instance from args using the sasha/regardv3 model with regard-specific preprocessing and summarization'}
```

