# Agent Python Tools

- repo: facebookresearch/covidprognosis
- repo_uri: https://github.com/facebookresearch/covidprognosis

## File: facebookresearch_covidprognosis/covidprognosis/models/moco_model.py

Prompts

```
['build a MoCo model with query and key encoders, a queue, and momentum update for contrastive learning', 'run the MoCo forward pass with query and key image batches to compute logits and labels', 'test the MoCo momentum update of the key encoder using the momentum coefficient', 'review the MoCo dequeue and enqueue method that manages the negative key queue buffer', 'summarize the concat_all_gather utility that gathers tensors across all GPUs via distributed all_gather']
```

Usage

```
{'build_MoCo_model': 'build a MoCo model with query and key encoders, a queue, and momentum update for contrastive learning', 'run_MoCo_forward': 'run the MoCo forward pass with query and key image batches to compute logits and labels', 'test_momentum_update_key_encoder': 'test the MoCo momentum update of the key encoder using the momentum coefficient', 'review_dequeue_and_enqueue': 'review the MoCo dequeue and enqueue method that manages the negative key queue buffer', 'summarize_concat_all_gather': 'summarize the concat_all_gather utility that gathers tensors across all GPUs via distributed all_gather'}
```

