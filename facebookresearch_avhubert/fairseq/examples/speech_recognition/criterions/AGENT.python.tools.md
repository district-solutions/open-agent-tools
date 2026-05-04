# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/criterions/ASG_loss.py

Prompts

```
['build an ASGCriterion instance with a task, silence token, and transition matrix initialization value', 'add ASG loss CLI arguments like transitions init, max replabel, and linseg updates to a parser', 'compute the ASG loss for a speech recognition sample by passing a model and sample batch', 'aggregate logging outputs from data parallel ASG loss training across multiple processes', 'review the ASGCriterion linseg_step method that controls LinSeg initialization progress during training', 'build a fairseq criterion that computes cross entropy loss with accuracy metrics for speech recognition', 'compute negative log likelihood loss from model log probabilities and target tokens with padding ignored', 'get logging output with correct predictions, total tokens, and sample size for training metrics', 'run the forward pass to compute cross entropy loss, sample size, and accuracy logging for a batch', 'aggregate logging outputs from data parallel training to compute average loss and accuracy across GPUs']
```

Usage

```
{'build_asg_criterion': 'build an ASGCriterion instance with a task, silence token, and transition matrix initialization value', 'add_asg_loss_args': 'add ASG loss CLI arguments like transitions init, max replabel, and linseg updates to a parser', 'compute_asg_loss_forward': 'compute the ASG loss for a speech recognition sample by passing a model and sample batch', 'aggregate_asg_logging_outputs': 'aggregate logging outputs from data parallel ASG loss training across multiple processes', 'review_asg_linseg_step': 'review the ASGCriterion linseg_step method that controls LinSeg initialization progress during training'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/criterions/cross_entropy_acc.py

Prompts

```
['build an ASGCriterion instance with a task, silence token, and transition matrix initialization value', 'add ASG loss CLI arguments like transitions init, max replabel, and linseg updates to a parser', 'compute the ASG loss for a speech recognition sample by passing a model and sample batch', 'aggregate logging outputs from data parallel ASG loss training across multiple processes', 'review the ASGCriterion linseg_step method that controls LinSeg initialization progress during training', 'build a fairseq criterion that computes cross entropy loss with accuracy metrics for speech recognition', 'compute negative log likelihood loss from model log probabilities and target tokens with padding ignored', 'get logging output with correct predictions, total tokens, and sample size for training metrics', 'run the forward pass to compute cross entropy loss, sample size, and accuracy logging for a batch', 'aggregate logging outputs from data parallel training to compute average loss and accuracy across GPUs']
```

Usage

```
{'build_cross_entropy_acc_criterion': 'build a fairseq criterion that computes cross entropy loss with accuracy metrics for speech recognition', 'compute_loss_nll': 'compute negative log likelihood loss from model log probabilities and target tokens with padding ignored', 'get_logging_output_accuracy': 'get logging output with correct predictions, total tokens, and sample size for training metrics', 'forward_cross_entropy_acc': 'run the forward pass to compute cross entropy loss, sample size, and accuracy logging for a batch', 'aggregate_logging_outputs_parallel': 'aggregate logging outputs from data parallel training to compute average loss and accuracy across GPUs'}
```

