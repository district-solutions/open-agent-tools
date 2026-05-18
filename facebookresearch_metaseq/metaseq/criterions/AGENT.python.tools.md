# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/criterions/base_criterion.py

Prompts

```
['build a criterion from a MetaseqDataclass config and task using build_criterion', 'add criterion-specific arguments to an argparse parser using the add_args class method', 'compute the loss for a model sample by overriding the forward method', 'aggregate logging outputs from data parallel training using reduce_metrics', 'review the BaseCriterion class and its padding index initialization logic', 'compute negative log-likelihood loss for large tensors using the nll_loss function with ignore_index support', 'create a CrossEntropyCriterion instance registered as cross_entropy for MetaSeq model training tasks', 'compute cross-entropy loss from model normalized log-probabilities and target tokens using compute_loss', 'aggregate logging outputs across data parallel workers and log loss and perplexity metrics', 'review the CrossEntropyCriterion forward method to understand loss computation and inner state instrumentation', 'build a MetaSeq criterion class that computes vocab-parallel cross entropy loss for model training', 'test the reduce_metrics static method that aggregates logging outputs from data parallel training', 'refactor VocabParallelCrossEntropyCriterion to support custom sample size calculation or additional logging metrics', 'summarize the logging_outputs_can_be_summed method that enables faster distributed training by allowing output aggregation']
```

Usage

```
{'build_criterion_from_cfg': 'build a criterion from a MetaseqDataclass config and task using build_criterion', 'add_args_to_parser': 'add criterion-specific arguments to an argparse parser using the add_args class method', 'forward_compute_loss': 'compute the loss for a model sample by overriding the forward method', 'reduce_metrics_aggregate': 'aggregate logging outputs from data parallel training using reduce_metrics', 'review_basecriterion_class': 'review the BaseCriterion class and its padding index initialization logic'}
```

## File: facebookresearch_metaseq/metaseq/criterions/cross_entropy.py

Prompts

```
['build a criterion from a MetaseqDataclass config and task using build_criterion', 'add criterion-specific arguments to an argparse parser using the add_args class method', 'compute the loss for a model sample by overriding the forward method', 'aggregate logging outputs from data parallel training using reduce_metrics', 'review the BaseCriterion class and its padding index initialization logic', 'compute negative log-likelihood loss for large tensors using the nll_loss function with ignore_index support', 'create a CrossEntropyCriterion instance registered as cross_entropy for MetaSeq model training tasks', 'compute cross-entropy loss from model normalized log-probabilities and target tokens using compute_loss', 'aggregate logging outputs across data parallel workers and log loss and perplexity metrics', 'review the CrossEntropyCriterion forward method to understand loss computation and inner state instrumentation', 'build a MetaSeq criterion class that computes vocab-parallel cross entropy loss for model training', 'test the reduce_metrics static method that aggregates logging outputs from data parallel training', 'refactor VocabParallelCrossEntropyCriterion to support custom sample size calculation or additional logging metrics', 'summarize the logging_outputs_can_be_summed method that enables faster distributed training by allowing output aggregation']
```

Usage

```
{'compute_nll_loss': 'compute negative log-likelihood loss for large tensors using the nll_loss function with ignore_index support', 'create_cross_entropy_criterion': 'create a CrossEntropyCriterion instance registered as cross_entropy for MetaSeq model training tasks', 'compute_loss_from_model_output': 'compute cross-entropy loss from model normalized log-probabilities and target tokens using compute_loss', 'reduce_metrics_for_distributed_training': 'aggregate logging outputs across data parallel workers and log loss and perplexity metrics', 'review_forward_method': 'review the CrossEntropyCriterion forward method to understand loss computation and inner state instrumentation'}
```

## File: facebookresearch_metaseq/metaseq/criterions/vocab_parallel_cross_entropy.py

Prompts

```
['build a criterion from a MetaseqDataclass config and task using build_criterion', 'add criterion-specific arguments to an argparse parser using the add_args class method', 'compute the loss for a model sample by overriding the forward method', 'aggregate logging outputs from data parallel training using reduce_metrics', 'review the BaseCriterion class and its padding index initialization logic', 'compute negative log-likelihood loss for large tensors using the nll_loss function with ignore_index support', 'create a CrossEntropyCriterion instance registered as cross_entropy for MetaSeq model training tasks', 'compute cross-entropy loss from model normalized log-probabilities and target tokens using compute_loss', 'aggregate logging outputs across data parallel workers and log loss and perplexity metrics', 'review the CrossEntropyCriterion forward method to understand loss computation and inner state instrumentation', 'build a MetaSeq criterion class that computes vocab-parallel cross entropy loss for model training', 'test the reduce_metrics static method that aggregates logging outputs from data parallel training', 'refactor VocabParallelCrossEntropyCriterion to support custom sample size calculation or additional logging metrics', 'summarize the logging_outputs_can_be_summed method that enables faster distributed training by allowing output aggregation']
```

Usage

```
{'build_VocabParallelCrossEntropyCriterion': 'build a MetaSeq criterion class that computes vocab-parallel cross entropy loss for model training', 'review_forward_method': 'review the forward method to understand how loss is computed and logging outputs are generated', 'test_reduce_metrics': 'test the reduce_metrics static method that aggregates logging outputs from data parallel training', 'refactor_VocabParallelCrossEntropyCriterion': 'refactor VocabParallelCrossEntropyCriterion to support custom sample size calculation or additional logging metrics', 'summarize_logging_outputs_can_be_summed': 'summarize the logging_outputs_can_be_summed method that enables faster distributed training by allowing output aggregation'}
```

