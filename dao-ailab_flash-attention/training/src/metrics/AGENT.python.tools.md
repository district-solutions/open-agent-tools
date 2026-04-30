# Agent Python Tools

- repo: dao-ailab/flash-attention
- repo_uri: https://github.com/dao-ailab/flash-attention

## File: dao-ailab_flash-attention/training/src/metrics/accuracy.py

Prompts

```
['create an AccuracyMine instance that wraps torchmetrics.Accuracy for mixup-compatible targets', 'test the AccuracyMine.update method with floating-point target tensors using argmax', 'test the AccuracyMine.update method with integer target tensors without argmax conversion', 'review the AccuracyMine class that extends torchmetrics.Accuracy to handle mixup targets', 'summarize the AccuracyMine.update method that applies argmax to floating-point targets', 'create a torchmetrics Metric subclass that tracks the total number of tokens seen across batches', 'test the NumTokens.update method accumulates target tensor element count into a running total', 'test the NumTokens.compute method returns the accumulated token count as a tensor', 'refactor the NumTokens.reset method to preserve the accumulated count across epoch boundaries', 'review the NumTokens._forward_reduce_state_update method for correct single-call update-and-compute behavior', 'create a Perplexity metric instance for measuring language model prediction quality', 'update the Perplexity metric with model predictions and target tokens', 'compute the final Perplexity score from accumulated log probabilities and token count', 'use the Perplexity metric with an ignore_index to skip masked tokens', 'test that Perplexity computes exp(average(nll)) instead of average(exp(nll))']
```

Usage

```
{'create_AccuracyMine': 'create an AccuracyMine instance that wraps torchmetrics.Accuracy for mixup-compatible targets', 'test_AccuracyMine_update': 'test the AccuracyMine.update method with floating-point target tensors using argmax', 'test_AccuracyMine_update_int': 'test the AccuracyMine.update method with integer target tensors without argmax conversion', 'review_AccuracyMine': 'review the AccuracyMine class that extends torchmetrics.Accuracy to handle mixup targets', 'summarize_AccuracyMine_update': 'summarize the AccuracyMine.update method that applies argmax to floating-point targets'}
```

## File: dao-ailab_flash-attention/training/src/metrics/num_tokens.py

Prompts

```
['create an AccuracyMine instance that wraps torchmetrics.Accuracy for mixup-compatible targets', 'test the AccuracyMine.update method with floating-point target tensors using argmax', 'test the AccuracyMine.update method with integer target tensors without argmax conversion', 'review the AccuracyMine class that extends torchmetrics.Accuracy to handle mixup targets', 'summarize the AccuracyMine.update method that applies argmax to floating-point targets', 'create a torchmetrics Metric subclass that tracks the total number of tokens seen across batches', 'test the NumTokens.update method accumulates target tensor element count into a running total', 'test the NumTokens.compute method returns the accumulated token count as a tensor', 'refactor the NumTokens.reset method to preserve the accumulated count across epoch boundaries', 'review the NumTokens._forward_reduce_state_update method for correct single-call update-and-compute behavior', 'create a Perplexity metric instance for measuring language model prediction quality', 'update the Perplexity metric with model predictions and target tokens', 'compute the final Perplexity score from accumulated log probabilities and token count', 'use the Perplexity metric with an ignore_index to skip masked tokens', 'test that Perplexity computes exp(average(nll)) instead of average(exp(nll))']
```

Usage

```
{'create_class_num_tokens': 'create a torchmetrics Metric subclass that tracks the total number of tokens seen across batches', 'test_num_tokens_update': 'test the NumTokens.update method accumulates target tensor element count into a running total', 'test_num_tokens_compute': 'test the NumTokens.compute method returns the accumulated token count as a tensor', 'refactor_num_tokens_reset': 'refactor the NumTokens.reset method to preserve the accumulated count across epoch boundaries', 'review_num_tokens_forward': 'review the NumTokens._forward_reduce_state_update method for correct single-call update-and-compute behavior'}
```

## File: dao-ailab_flash-attention/training/src/metrics/perplexity.py

Prompts

```
['create an AccuracyMine instance that wraps torchmetrics.Accuracy for mixup-compatible targets', 'test the AccuracyMine.update method with floating-point target tensors using argmax', 'test the AccuracyMine.update method with integer target tensors without argmax conversion', 'review the AccuracyMine class that extends torchmetrics.Accuracy to handle mixup targets', 'summarize the AccuracyMine.update method that applies argmax to floating-point targets', 'create a torchmetrics Metric subclass that tracks the total number of tokens seen across batches', 'test the NumTokens.update method accumulates target tensor element count into a running total', 'test the NumTokens.compute method returns the accumulated token count as a tensor', 'refactor the NumTokens.reset method to preserve the accumulated count across epoch boundaries', 'review the NumTokens._forward_reduce_state_update method for correct single-call update-and-compute behavior', 'create a Perplexity metric instance for measuring language model prediction quality', 'update the Perplexity metric with model predictions and target tokens', 'compute the final Perplexity score from accumulated log probabilities and token count', 'use the Perplexity metric with an ignore_index to skip masked tokens', 'test that Perplexity computes exp(average(nll)) instead of average(exp(nll))']
```

Usage

```
{'create_perplexity_metric': 'create a Perplexity metric instance for measuring language model prediction quality', 'update_perplexity_with_predictions': 'update the Perplexity metric with model predictions and target tokens', 'compute_perplexity_score': 'compute the final Perplexity score from accumulated log probabilities and token count', 'use_perplexity_with_ignore_index': 'use the Perplexity metric with an ignore_index to skip masked tokens', 'test_perplexity_correctness': 'test that Perplexity computes exp(average(nll)) instead of average(exp(nll))'}
```

