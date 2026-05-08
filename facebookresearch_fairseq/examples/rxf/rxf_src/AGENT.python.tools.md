# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/rxf/rxf_src/label_smoothed_cross_entropy_r3f.py

Prompts

```
['create a Fairseq criterion that combines label smoothed cross entropy with robust representation learning via forward smoothing', 'review the LabelSmoothedCrossEntropyR3FCriterion class init to understand noise sampler setup for normal or uniform noise types', 'review the add_args static method to see criterion-specific CLI arguments for label smoothing, eps, r3f lambda, and noise type', 'refactor the _get_symm_kl method to compute symmetric KL divergence between noised and original logits for robustness regularization', 'summarize the forward method that computes loss with label smoothing and adds symmetric KL divergence during training', 'create a FairseqCriterion subclass that computes sentence prediction loss with robust representation via feature noise', 'review the SentencePredictionR3F forward method to understand how it computes NLL loss combined with symmetric KL divergence', 'build a symmetric KL divergence loss between noised and original logits for robust feature regularization', 'test the SentencePredictionR3F noise sampler to verify normal or uniform noise injection on token embeddings', 'summarize the aggregate_logging_outputs method that aggregates loss, symmetric KL, and accuracy across data parallel training']
```

Usage

```
{'create_R3F_criterion': 'create a Fairseq criterion that combines label smoothed cross entropy with robust representation learning via forward smoothing', 'review_LabelSmoothedCrossEntropyR3FCriterion_init': 'review the LabelSmoothedCrossEntropyR3FCriterion class init to understand noise sampler setup for normal or uniform noise types', 'review_add_args': 'review the add_args static method to see criterion-specific CLI arguments for label smoothing, eps, r3f lambda, and noise type', 'refactor_get_symm_kl': 'refactor the _get_symm_kl method to compute symmetric KL divergence between noised and original logits for robustness regularization', 'summarize_forward': 'summarize the forward method that computes loss with label smoothing and adds symmetric KL divergence during training'}
```

## File: facebookresearch_fairseq/examples/rxf/rxf_src/sentence_prediction_r3f.py

Prompts

```
['create a Fairseq criterion that combines label smoothed cross entropy with robust representation learning via forward smoothing', 'review the LabelSmoothedCrossEntropyR3FCriterion class init to understand noise sampler setup for normal or uniform noise types', 'review the add_args static method to see criterion-specific CLI arguments for label smoothing, eps, r3f lambda, and noise type', 'refactor the _get_symm_kl method to compute symmetric KL divergence between noised and original logits for robustness regularization', 'summarize the forward method that computes loss with label smoothing and adds symmetric KL divergence during training', 'create a FairseqCriterion subclass that computes sentence prediction loss with robust representation via feature noise', 'review the SentencePredictionR3F forward method to understand how it computes NLL loss combined with symmetric KL divergence', 'build a symmetric KL divergence loss between noised and original logits for robust feature regularization', 'test the SentencePredictionR3F noise sampler to verify normal or uniform noise injection on token embeddings', 'summarize the aggregate_logging_outputs method that aggregates loss, symmetric KL, and accuracy across data parallel training']
```

Usage

```
{'create_sentence_prediction_r3f_criterion': 'create a FairseqCriterion subclass that computes sentence prediction loss with robust representation via feature noise', 'review_SentencePredictionR3F_forward': 'review the SentencePredictionR3F forward method to understand how it computes NLL loss combined with symmetric KL divergence', 'build_symm_kl_loss': 'build a symmetric KL divergence loss between noised and original logits for robust feature regularization', 'test_SentencePredictionR3F_noise_sampler': 'test the SentencePredictionR3F noise sampler to verify normal or uniform noise injection on token embeddings', 'summarize_aggregate_logging_outputs': 'summarize the aggregate_logging_outputs method that aggregates loss, symmetric KL, and accuracy across data parallel training'}
```

