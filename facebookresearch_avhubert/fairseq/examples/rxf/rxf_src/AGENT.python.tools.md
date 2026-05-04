# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/rxf/rxf_src/label_smoothed_cross_entropy_r3f.py

Prompts

```
['build a fairseq criterion that combines label smoothed cross entropy with R3F noisy KL divergence loss', 'create a function that computes symmetric KL divergence between noised and original model logits', 'review the forward method that adds noise to token embeddings and computes R3F loss during training', 'test the compute_loss method that calculates label smoothed NLL loss from model normalized probabilities', 'refactor the reduce_metrics static method to aggregate logging outputs from data parallel training workers', 'build a Fairseq sentence prediction criterion with R3F noisy KL regularization for robust representations', 'create a normal or uniform noise sampler with configurable epsilon for embedding perturbation', 'compute the symmetric KL divergence between noised logits and original input logits', 'run the forward pass to compute combined NLL loss and noisy KL regularization loss', 'aggregate logging outputs from data parallel training to compute average loss and accuracy']
```

Usage

```
{'build_criterion_with_label_smoothing': 'build a fairseq criterion that combines label smoothed cross entropy with R3F noisy KL divergence loss', 'create_symm_kl_computation': 'create a function that computes symmetric KL divergence between noised and original model logits', 'review_forward_training_loop': 'review the forward method that adds noise to token embeddings and computes R3F loss during training', 'test_compute_loss_method': 'test the compute_loss method that calculates label smoothed NLL loss from model normalized probabilities', 'refactor_reduce_metrics_aggregation': 'refactor the reduce_metrics static method to aggregate logging outputs from data parallel training workers'}
```

## File: facebookresearch_avhubert/fairseq/examples/rxf/rxf_src/sentence_prediction_r3f.py

Prompts

```
['build a fairseq criterion that combines label smoothed cross entropy with R3F noisy KL divergence loss', 'create a function that computes symmetric KL divergence between noised and original model logits', 'review the forward method that adds noise to token embeddings and computes R3F loss during training', 'test the compute_loss method that calculates label smoothed NLL loss from model normalized probabilities', 'refactor the reduce_metrics static method to aggregate logging outputs from data parallel training workers', 'build a Fairseq sentence prediction criterion with R3F noisy KL regularization for robust representations', 'create a normal or uniform noise sampler with configurable epsilon for embedding perturbation', 'compute the symmetric KL divergence between noised logits and original input logits', 'run the forward pass to compute combined NLL loss and noisy KL regularization loss', 'aggregate logging outputs from data parallel training to compute average loss and accuracy']
```

Usage

```
{'build_criterion_r3f': 'build a Fairseq sentence prediction criterion with R3F noisy KL regularization for robust representations', 'create_noise_sampler': 'create a normal or uniform noise sampler with configurable epsilon for embedding perturbation', 'compute_symm_kl': 'compute the symmetric KL divergence between noised logits and original input logits', 'run_forward_loss': 'run the forward pass to compute combined NLL loss and noisy KL regularization loss', 'aggregate_logging_outputs': 'aggregate logging outputs from data parallel training to compute average loss and accuracy'}
```

