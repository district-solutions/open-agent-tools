# Agent Python Tools

- repo: facebookresearch/mask-predict
- repo_uri: https://github.com/facebookresearch/mask-predict

## File: facebookresearch_mask-predict/fairseq/criterions/cross_entropy.py

Prompts

```
['run the CrossEntropyCriterion forward method to compute loss for a given sample and model', 'compute the cross entropy loss using nll_loss on log-probabilities and target tokens', 'aggregate logging outputs from data parallel training by summing loss, tokens, and sentences', 'review the CrossEntropyCriterion class and its forward, compute_loss, and aggregate_logging_outputs methods', 'refactor the compute_loss method to support a different reduction strategy or loss function', 'build a custom FairseqCriterion subclass that computes loss for a given model and sample', 'create a subclass of FairseqCriterion that adds criterion-specific arguments to an argparse parser', 'test the FairseqCriterion forward method to compute loss, sample size, and logging outputs', 'review the FairseqCriterion aggregate_logging_outputs method for aggregating data parallel training outputs', 'summarize the FairseqCriterion grad_denom method that computes the gradient denominator from sample sizes', 'compute label smoothed negative log likelihood loss given log probs, target, and epsilon', 'create a LabelSmoothedCrossEntropyCriterion instance with a label smoothing epsilon value', 'review the forward method that computes loss, sample size, and logging output for a model sample', 'refactor the compute_loss method to extract log probs and targets before calling label_smoothed_nll_loss', 'summarize how aggregate_logging_outputs combines per-batch loss and nll_loss across data parallel processes', 'build a FairseqCriterion subclass that combines label smoothing cross entropy with sequence length prediction loss', 'create a compute_loss method that calculates NLL loss, smooth loss, and length loss from model outputs', 'test the LabelSmoothedLengthCrossEntropyCriterion forward method to compute loss, sample size, and logging outputs for a sample', 'refactor the add_args static method to add label smoothing epsilon argument to the Fairseq argument parser']
```

Usage

```
{'run_cross_entropy_forward': 'run the CrossEntropyCriterion forward method to compute loss for a given sample and model', 'compute_cross_entropy_loss': 'compute the cross entropy loss using nll_loss on log-probabilities and target tokens', 'aggregate_logging_outputs': 'aggregate logging outputs from data parallel training by summing loss, tokens, and sentences', 'review_cross_entropy_criterion': 'review the CrossEntropyCriterion class and its forward, compute_loss, and aggregate_logging_outputs methods', 'refactor_compute_loss': 'refactor the compute_loss method to support a different reduction strategy or loss function'}
```

## File: facebookresearch_mask-predict/fairseq/criterions/fairseq_criterion.py

Prompts

```
['run the CrossEntropyCriterion forward method to compute loss for a given sample and model', 'compute the cross entropy loss using nll_loss on log-probabilities and target tokens', 'aggregate logging outputs from data parallel training by summing loss, tokens, and sentences', 'review the CrossEntropyCriterion class and its forward, compute_loss, and aggregate_logging_outputs methods', 'refactor the compute_loss method to support a different reduction strategy or loss function', 'build a custom FairseqCriterion subclass that computes loss for a given model and sample', 'create a subclass of FairseqCriterion that adds criterion-specific arguments to an argparse parser', 'test the FairseqCriterion forward method to compute loss, sample size, and logging outputs', 'review the FairseqCriterion aggregate_logging_outputs method for aggregating data parallel training outputs', 'summarize the FairseqCriterion grad_denom method that computes the gradient denominator from sample sizes', 'compute label smoothed negative log likelihood loss given log probs, target, and epsilon', 'create a LabelSmoothedCrossEntropyCriterion instance with a label smoothing epsilon value', 'review the forward method that computes loss, sample size, and logging output for a model sample', 'refactor the compute_loss method to extract log probs and targets before calling label_smoothed_nll_loss', 'summarize how aggregate_logging_outputs combines per-batch loss and nll_loss across data parallel processes', 'build a FairseqCriterion subclass that combines label smoothing cross entropy with sequence length prediction loss', 'create a compute_loss method that calculates NLL loss, smooth loss, and length loss from model outputs', 'test the LabelSmoothedLengthCrossEntropyCriterion forward method to compute loss, sample size, and logging outputs for a sample', 'refactor the add_args static method to add label smoothing epsilon argument to the Fairseq argument parser']
```

Usage

```
{'build_criterion': 'build a custom FairseqCriterion subclass that computes loss for a given model and sample', 'create_add_args': 'create a subclass of FairseqCriterion that adds criterion-specific arguments to an argparse parser', 'test_forward': 'test the FairseqCriterion forward method to compute loss, sample size, and logging outputs', 'review_aggregate_logging_outputs': 'review the FairseqCriterion aggregate_logging_outputs method for aggregating data parallel training outputs', 'summarize_grad_denom': 'summarize the FairseqCriterion grad_denom method that computes the gradient denominator from sample sizes'}
```

## File: facebookresearch_mask-predict/fairseq/criterions/label_smoothed_cross_entropy.py

Prompts

```
['run the CrossEntropyCriterion forward method to compute loss for a given sample and model', 'compute the cross entropy loss using nll_loss on log-probabilities and target tokens', 'aggregate logging outputs from data parallel training by summing loss, tokens, and sentences', 'review the CrossEntropyCriterion class and its forward, compute_loss, and aggregate_logging_outputs methods', 'refactor the compute_loss method to support a different reduction strategy or loss function', 'build a custom FairseqCriterion subclass that computes loss for a given model and sample', 'create a subclass of FairseqCriterion that adds criterion-specific arguments to an argparse parser', 'test the FairseqCriterion forward method to compute loss, sample size, and logging outputs', 'review the FairseqCriterion aggregate_logging_outputs method for aggregating data parallel training outputs', 'summarize the FairseqCriterion grad_denom method that computes the gradient denominator from sample sizes', 'compute label smoothed negative log likelihood loss given log probs, target, and epsilon', 'create a LabelSmoothedCrossEntropyCriterion instance with a label smoothing epsilon value', 'review the forward method that computes loss, sample size, and logging output for a model sample', 'refactor the compute_loss method to extract log probs and targets before calling label_smoothed_nll_loss', 'summarize how aggregate_logging_outputs combines per-batch loss and nll_loss across data parallel processes', 'build a FairseqCriterion subclass that combines label smoothing cross entropy with sequence length prediction loss', 'create a compute_loss method that calculates NLL loss, smooth loss, and length loss from model outputs', 'test the LabelSmoothedLengthCrossEntropyCriterion forward method to compute loss, sample size, and logging outputs for a sample', 'refactor the add_args static method to add label smoothing epsilon argument to the Fairseq argument parser']
```

Usage

```
{'compute_label_smoothed_nll_loss': 'compute label smoothed negative log likelihood loss given log probs, target, and epsilon', 'create_label_smoothed_criterion': 'create a LabelSmoothedCrossEntropyCriterion instance with a label smoothing epsilon value', 'review_forward_loss_computation': 'review the forward method that computes loss, sample size, and logging output for a model sample', 'refactor_compute_loss_method': 'refactor the compute_loss method to extract log probs and targets before calling label_smoothed_nll_loss', 'summarize_aggregate_logging_outputs': 'summarize how aggregate_logging_outputs combines per-batch loss and nll_loss across data parallel processes'}
```

## File: facebookresearch_mask-predict/fairseq/criterions/label_smoothed_length_cross_entropy.py

Prompts

```
['run the CrossEntropyCriterion forward method to compute loss for a given sample and model', 'compute the cross entropy loss using nll_loss on log-probabilities and target tokens', 'aggregate logging outputs from data parallel training by summing loss, tokens, and sentences', 'review the CrossEntropyCriterion class and its forward, compute_loss, and aggregate_logging_outputs methods', 'refactor the compute_loss method to support a different reduction strategy or loss function', 'build a custom FairseqCriterion subclass that computes loss for a given model and sample', 'create a subclass of FairseqCriterion that adds criterion-specific arguments to an argparse parser', 'test the FairseqCriterion forward method to compute loss, sample size, and logging outputs', 'review the FairseqCriterion aggregate_logging_outputs method for aggregating data parallel training outputs', 'summarize the FairseqCriterion grad_denom method that computes the gradient denominator from sample sizes', 'compute label smoothed negative log likelihood loss given log probs, target, and epsilon', 'create a LabelSmoothedCrossEntropyCriterion instance with a label smoothing epsilon value', 'review the forward method that computes loss, sample size, and logging output for a model sample', 'refactor the compute_loss method to extract log probs and targets before calling label_smoothed_nll_loss', 'summarize how aggregate_logging_outputs combines per-batch loss and nll_loss across data parallel processes', 'build a FairseqCriterion subclass that combines label smoothing cross entropy with sequence length prediction loss', 'create a compute_loss method that calculates NLL loss, smooth loss, and length loss from model outputs', 'test the LabelSmoothedLengthCrossEntropyCriterion forward method to compute loss, sample size, and logging outputs for a sample', 'refactor the add_args static method to add label smoothing epsilon argument to the Fairseq argument parser']
```

Usage

```
{'build_label_smoothed_length_criterion': 'build a FairseqCriterion subclass that combines label smoothing cross entropy with sequence length prediction loss', 'create_compute_loss_method': 'create a compute_loss method that calculates NLL loss, smooth loss, and length loss from model outputs', 'test_forward_method': 'test the LabelSmoothedLengthCrossEntropyCriterion forward method to compute loss, sample size, and logging outputs for a sample', 'review_aggregate_logging_outputs': 'review the aggregate_logging_outputs static method that aggregates logging outputs from data parallel training across processes', 'refactor_add_args_parser': 'refactor the add_args static method to add label smoothing epsilon argument to the Fairseq argument parser'}
```

