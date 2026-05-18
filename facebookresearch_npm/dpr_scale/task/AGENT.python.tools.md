# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/dpr_scale/task/all_gather.py

Prompts

```
['use AllGatherGrad to gather tensors across GPUs with automatic gradient back-propagation support', 'use AllGatherGrad2 to gather tensors into a list with async reduce for gradient back-propagation', 'call my_all_gather to gather tensors from all processes and stack them along dimension 0', 'call my_all_gather2 to gather tensors from all processes into a tuple with per-rank gradient reduction', 'review the AllGatherGrad class forward and backward methods for distributed tensor gathering with gradients', 'build a PyTorch Lightning module for masked language modeling with softmax or contrastive task types', 'run the contrastive training step that computes similarity scores and contrastive loss across distributed GPUs', 'run the softmax training step that computes cross-entropy loss for masked token prediction', 'review the _compute_simscores method that calculates inner product or L2 similarity between hidden state vectors', 'build an encoding task subclass that extracts and saves token embeddings to a memory-mapped numpy file']
```

Usage

```
{'use_all_gather_with_grad': 'use AllGatherGrad to gather tensors across GPUs with automatic gradient back-propagation support', 'use_all_gather_grad2': 'use AllGatherGrad2 to gather tensors into a list with async reduce for gradient back-propagation', 'call_my_all_gather': 'call my_all_gather to gather tensors from all processes and stack them along dimension 0', 'call_my_all_gather2': 'call my_all_gather2 to gather tensors from all processes into a tuple with per-rank gradient reduction', 'review_all_gather_grad_class': 'review the AllGatherGrad class forward and backward methods for distributed tensor gathering with gradients'}
```

## File: facebookresearch_npm/dpr_scale/task/mlm_task.py

Prompts

```
['use AllGatherGrad to gather tensors across GPUs with automatic gradient back-propagation support', 'use AllGatherGrad2 to gather tensors into a list with async reduce for gradient back-propagation', 'call my_all_gather to gather tensors from all processes and stack them along dimension 0', 'call my_all_gather2 to gather tensors from all processes into a tuple with per-rank gradient reduction', 'review the AllGatherGrad class forward and backward methods for distributed tensor gathering with gradients', 'build a PyTorch Lightning module for masked language modeling with softmax or contrastive task types', 'run the contrastive training step that computes similarity scores and contrastive loss across distributed GPUs', 'run the softmax training step that computes cross-entropy loss for masked token prediction', 'review the _compute_simscores method that calculates inner product or L2 similarity between hidden state vectors', 'build an encoding task subclass that extracts and saves token embeddings to a memory-mapped numpy file']
```

Usage

```
{'build_MaskedLanguageModelingTask': 'build a PyTorch Lightning module for masked language modeling with softmax or contrastive task types', 'run_contrastive_training_step': 'run the contrastive training step that computes similarity scores and contrastive loss across distributed GPUs', 'run_softmax_training_step': 'run the softmax training step that computes cross-entropy loss for masked token prediction', 'review_compute_simscores': 'review the _compute_simscores method that calculates inner product or L2 similarity between hidden state vectors', 'build_MaskedLanguageModelingEncodingTask': 'build an encoding task subclass that extracts and saves token embeddings to a memory-mapped numpy file'}
```

