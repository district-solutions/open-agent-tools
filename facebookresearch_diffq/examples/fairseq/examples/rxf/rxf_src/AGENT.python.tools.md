# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/rxf/rxf_src/label_smoothed_cross_entropy_r3f.py

Prompts

```
['build a Fairseq criterion that combines label-smoothed cross-entropy with R3F noise perturbation using normal or uniform noise', 'create a function that computes symmetric KL divergence between noised and original model logits', 'test the label-smoothed cross-entropy loss computation with configurable smoothing and padding index', 'review the reduce_metrics method that aggregates loss, NLL loss, and symmetric KL across distributed workers', 'refactor the noise sampler to support additional noise distributions beyond normal and uniform', 'build a Fairseq criterion that combines NLL loss with symmetric KL divergence regularization for sentence prediction', 'create a normal or uniform noise sampler with configurable epsilon for robust feature regularization', 'compute the symmetric KL divergence between noised logits and original logits for regularization', 'review the forward method that computes combined NLL and symmetric KL loss for classification or regression', 'aggregate logging outputs from data parallel training to compute average loss and accuracy']
```

Usage

```
{'build_criterion_with_r3f_noise': 'build a Fairseq criterion that combines label-smoothed cross-entropy with R3F noise perturbation using normal or uniform noise', 'create_symmetric_kl_divergence': 'create a function that computes symmetric KL divergence between noised and original model logits', 'test_label_smoothed_loss': 'test the label-smoothed cross-entropy loss computation with configurable smoothing and padding index', 'review_reduce_metrics': 'review the reduce_metrics method that aggregates loss, NLL loss, and symmetric KL across distributed workers', 'refactor_noise_sampler': 'refactor the noise sampler to support additional noise distributions beyond normal and uniform'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/rxf/rxf_src/sentence_prediction_r3f.py

Prompts

```
['build a Fairseq criterion that combines label-smoothed cross-entropy with R3F noise perturbation using normal or uniform noise', 'create a function that computes symmetric KL divergence between noised and original model logits', 'test the label-smoothed cross-entropy loss computation with configurable smoothing and padding index', 'review the reduce_metrics method that aggregates loss, NLL loss, and symmetric KL across distributed workers', 'refactor the noise sampler to support additional noise distributions beyond normal and uniform', 'build a Fairseq criterion that combines NLL loss with symmetric KL divergence regularization for sentence prediction', 'create a normal or uniform noise sampler with configurable epsilon for robust feature regularization', 'compute the symmetric KL divergence between noised logits and original logits for regularization', 'review the forward method that computes combined NLL and symmetric KL loss for classification or regression', 'aggregate logging outputs from data parallel training to compute average loss and accuracy']
```

Usage

```
{'build_criterion_r3f': 'build a Fairseq criterion that combines NLL loss with symmetric KL divergence regularization for sentence prediction', 'create_noise_sampler': 'create a normal or uniform noise sampler with configurable epsilon for robust feature regularization', 'compute_symm_kl': 'compute the symmetric KL divergence between noised logits and original logits for regularization', 'review_forward_loss': 'review the forward method that computes combined NLL and symmetric KL loss for classification or regression', 'aggregate_logging_outputs': 'aggregate logging outputs from data parallel training to compute average loss and accuracy'}
```

