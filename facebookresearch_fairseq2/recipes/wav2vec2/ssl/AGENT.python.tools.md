# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/criterion.py

Prompts

```
['create a Wav2Vec2SslCriterion instance with a model and loss weight parameters for training', 'configure a Wav2Vec2SslLossSection dataclass with custom diversity and feature penalty weights', 'run the Wav2Vec2SslCriterion on a SequenceBatch to compute loss and update metrics', 'prepare a MetricBag with SSL metrics by calling prepare_metric_bag on the criterion', 'review the Wav2Vec2SslCriterion call method that returns aggregated loss and target count', 'add SSL metrics like loss, accuracy, and perplexity to a fairseq2 MetricBag for wav2vec2 training', 'update wav2vec2 loss metrics including contrastive loss, diversity loss, and feature penalty in a MetricBag', 'update wav2vec2 accuracy metrics by comparing predicted logits against zero-index targets in a MetricBag', 'update wav2vec2 vector quantizer metrics including code perplexity, probability perplexity, and temperature', 'update batch-level metrics tracking total number of examples and elements from a SequenceBatch', 'create a wav2vec2 SSL trainer with criterion, data readers, and validation units from a recipe context', 'register the wav2vec2 SSL dataset family with its config and opener in the dependency container', 'process a sequence batch through the wav2vec2 SSL criterion and return loss tensor and batch size', 'evaluate a sequence batch through the wav2vec2 SSL criterion for validation during training', 'prepare the metric bag by registering wav2vec2 SSL criterion metrics for tracking training progress']
```

Usage

```
{'create_ssl_criterion': 'create a Wav2Vec2SslCriterion instance with a model and loss weight parameters for training', 'configure_loss_section': 'configure a Wav2Vec2SslLossSection dataclass with custom diversity and feature penalty weights', 'run_criterion_forward': 'run the Wav2Vec2SslCriterion on a SequenceBatch to compute loss and update metrics', 'prepare_metric_bag': 'prepare a MetricBag with SSL metrics by calling prepare_metric_bag on the criterion', 'review_criterion_call': 'review the Wav2Vec2SslCriterion call method that returns aggregated loss and target count'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/metrics.py

Prompts

```
['create a Wav2Vec2SslCriterion instance with a model and loss weight parameters for training', 'configure a Wav2Vec2SslLossSection dataclass with custom diversity and feature penalty weights', 'run the Wav2Vec2SslCriterion on a SequenceBatch to compute loss and update metrics', 'prepare a MetricBag with SSL metrics by calling prepare_metric_bag on the criterion', 'review the Wav2Vec2SslCriterion call method that returns aggregated loss and target count', 'add SSL metrics like loss, accuracy, and perplexity to a fairseq2 MetricBag for wav2vec2 training', 'update wav2vec2 loss metrics including contrastive loss, diversity loss, and feature penalty in a MetricBag', 'update wav2vec2 accuracy metrics by comparing predicted logits against zero-index targets in a MetricBag', 'update wav2vec2 vector quantizer metrics including code perplexity, probability perplexity, and temperature', 'update batch-level metrics tracking total number of examples and elements from a SequenceBatch', 'create a wav2vec2 SSL trainer with criterion, data readers, and validation units from a recipe context', 'register the wav2vec2 SSL dataset family with its config and opener in the dependency container', 'process a sequence batch through the wav2vec2 SSL criterion and return loss tensor and batch size', 'evaluate a sequence batch through the wav2vec2 SSL criterion for validation during training', 'prepare the metric bag by registering wav2vec2 SSL criterion metrics for tracking training progress']
```

Usage

```
{'add_ssl_metrics': 'add SSL metrics like loss, accuracy, and perplexity to a fairseq2 MetricBag for wav2vec2 training', 'update_wav2vec2_loss': 'update wav2vec2 loss metrics including contrastive loss, diversity loss, and feature penalty in a MetricBag', 'update_wav2vec2_accuracy': 'update wav2vec2 accuracy metrics by comparing predicted logits against zero-index targets in a MetricBag', 'update_wav2vec2_quantizer_metrics': 'update wav2vec2 vector quantizer metrics including code perplexity, probability perplexity, and temperature', 'update_wav2vec2_batch_metrics': 'update batch-level metrics tracking total number of examples and elements from a SequenceBatch'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/ssl/recipe.py

Prompts

```
['create a Wav2Vec2SslCriterion instance with a model and loss weight parameters for training', 'configure a Wav2Vec2SslLossSection dataclass with custom diversity and feature penalty weights', 'run the Wav2Vec2SslCriterion on a SequenceBatch to compute loss and update metrics', 'prepare a MetricBag with SSL metrics by calling prepare_metric_bag on the criterion', 'review the Wav2Vec2SslCriterion call method that returns aggregated loss and target count', 'add SSL metrics like loss, accuracy, and perplexity to a fairseq2 MetricBag for wav2vec2 training', 'update wav2vec2 loss metrics including contrastive loss, diversity loss, and feature penalty in a MetricBag', 'update wav2vec2 accuracy metrics by comparing predicted logits against zero-index targets in a MetricBag', 'update wav2vec2 vector quantizer metrics including code perplexity, probability perplexity, and temperature', 'update batch-level metrics tracking total number of examples and elements from a SequenceBatch', 'create a wav2vec2 SSL trainer with criterion, data readers, and validation units from a recipe context', 'register the wav2vec2 SSL dataset family with its config and opener in the dependency container', 'process a sequence batch through the wav2vec2 SSL criterion and return loss tensor and batch size', 'evaluate a sequence batch through the wav2vec2 SSL criterion for validation during training', 'prepare the metric bag by registering wav2vec2 SSL criterion metrics for tracking training progress']
```

Usage

```
{'create_trainer_for_wav2vec2_ssl': 'create a wav2vec2 SSL trainer with criterion, data readers, and validation units from a recipe context', 'register_wav2vec2_ssl_dataset_family': 'register the wav2vec2 SSL dataset family with its config and opener in the dependency container', 'process_batch_in_train_unit': 'process a sequence batch through the wav2vec2 SSL criterion and return loss tensor and batch size', 'evaluate_batch_in_eval_unit': 'evaluate a sequence batch through the wav2vec2 SSL criterion for validation during training', 'prepare_metric_bag_for_criterion': 'prepare the metric bag by registering wav2vec2 SSL criterion metrics for tracking training progress'}
```

