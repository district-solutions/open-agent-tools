# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/data_pipeline/classification/multi_label_classification.py

Prompts

```
['run multi-label text classification on a JSONL dataset using a HuggingFace model via Ray', 'create a TextClassificationConfig dataclass with model_dir, text_key, threshold_fname, and top_k settings', 'review the TextClassification class __call__ method that cleans text and applies threshold-based label filtering', 'refactor the run_remotely Ray remote function to adjust batch_size or max_concurrency for GPU inference', 'summarize the TextClassification setup method that loads a HuggingFace pipeline and configures classification thresholds']
```

Usage

```
{'run_multi_label_classification': 'run multi-label text classification on a JSONL dataset using a HuggingFace model via Ray', 'create_TextClassificationConfig': 'create a TextClassificationConfig dataclass with model_dir, text_key, threshold_fname, and top_k settings', 'review_TextClassification_call': 'review the TextClassification class __call__ method that cleans text and applies threshold-based label filtering', 'refactor_run_remotely': 'refactor the run_remotely Ray remote function to adjust batch_size or max_concurrency for GPU inference', 'summarize_TextClassification_setup': 'summarize the TextClassification setup method that loads a HuggingFace pipeline and configures classification thresholds'}
```

