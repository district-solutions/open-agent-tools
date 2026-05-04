# Agent Python Tools

- repo: google-deepmind/distributionshiftframework
- repo_uri: https://github.com/google-deepmind/distribution_shift_framework

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/metrics/metrics.py

Prompts

```
['compute the Pearson correlation coefficient between predictions and labels using scipy.stats.pearsonr', 'compute the F1 score for classification predictions using sklearn with macro or weighted averaging', 'compute the recall score for classification predictions using sklearn with macro or weighted averaging', 'compute top-k accuracy from network logits and labels using JAX vmap and lax.top_k', 'compute a batch of metrics like pearson, f1, and recall from predictions and labels in one call']
```

Usage

```
{'compute_pearson_correlation': 'compute the Pearson correlation coefficient between predictions and labels using scipy.stats.pearsonr', 'compute_f1_score': 'compute the F1 score for classification predictions using sklearn with macro or weighted averaging', 'compute_recall_score': 'compute the recall score for classification predictions using sklearn with macro or weighted averaging', 'compute_top_k_accuracy': 'compute top-k accuracy from network logits and labels using JAX vmap and lax.top_k', 'compute_all_metrics': 'compute a batch of metrics like pearson, f1, and recall from predictions and labels in one call'}
```

