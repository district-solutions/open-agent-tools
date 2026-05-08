# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_recognition/criterions/ASG_loss.py

Prompts

```
['build an ASGCriterion instance from args and task for speech recognition training', 'add ASG loss CLI arguments like transitions init and max replabel to a parser', 'compute the ASG loss for a model output and target sample during training', 'aggregate logging outputs from data parallel ASG loss training across processes', 'review the LinSeg initialization step logic for ASG transition matrix warmup', 'create a CrossEntropyWithAccCriterion instance with a task and sentence_avg setting for fairseq training', 'compute the negative log-likelihood loss and log-probs from model output and target tokens', 'get logging output with accuracy metrics including correct predictions and total tokens for a sample', 'run the forward pass to compute cross entropy loss with accuracy metrics for a speech recognition sample', 'aggregate logging outputs from data parallel training to compute average loss and token accuracy']
```

Usage

```
{'build_asg_criterion': 'build an ASGCriterion instance from args and task for speech recognition training', 'add_asg_loss_args': 'add ASG loss CLI arguments like transitions init and max replabel to a parser', 'compute_asg_loss_forward': 'compute the ASG loss for a model output and target sample during training', 'aggregate_asg_logging_outputs': 'aggregate logging outputs from data parallel ASG loss training across processes', 'review_asg_linseg_step': 'review the LinSeg initialization step logic for ASG transition matrix warmup'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/criterions/cross_entropy_acc.py

Prompts

```
['build an ASGCriterion instance from args and task for speech recognition training', 'add ASG loss CLI arguments like transitions init and max replabel to a parser', 'compute the ASG loss for a model output and target sample during training', 'aggregate logging outputs from data parallel ASG loss training across processes', 'review the LinSeg initialization step logic for ASG transition matrix warmup', 'create a CrossEntropyWithAccCriterion instance with a task and sentence_avg setting for fairseq training', 'compute the negative log-likelihood loss and log-probs from model output and target tokens', 'get logging output with accuracy metrics including correct predictions and total tokens for a sample', 'run the forward pass to compute cross entropy loss with accuracy metrics for a speech recognition sample', 'aggregate logging outputs from data parallel training to compute average loss and token accuracy']
```

Usage

```
{'create_cross_entropy_acc_criterion': 'create a CrossEntropyWithAccCriterion instance with a task and sentence_avg setting for fairseq training', 'compute_loss_nll': 'compute the negative log-likelihood loss and log-probs from model output and target tokens', 'get_logging_output_accuracy': 'get logging output with accuracy metrics including correct predictions and total tokens for a sample', 'forward_cross_entropy_acc': 'run the forward pass to compute cross entropy loss with accuracy metrics for a speech recognition sample', 'aggregate_logging_outputs': 'aggregate logging outputs from data parallel training to compute average loss and token accuracy'}
```

