# Agent Python Tools

- repo: facebookresearch/madgrad
- repo_uri: https://github.com/facebookresearch/madgrad

## File: facebookresearch_madgrad/tests/test_madgrad.py

Prompts

```
['test that MADGRAD raises ValueError when momentum is set to 1.0', 'test that MADGRAD raises ValueError when learning rate is zero or negative', 'test that MADGRAD raises ValueError when weight_decay is negative', 'test MADGRAD optimizer step reduces loss on full precision CUDA tensors', 'test MADGRAD produces identical results for dense and sparse gradient tensors', 'test that MirrorMADGRAD raises ValueError when momentum is set to 1.0', 'test that MirrorMADGRAD raises ValueError when learning rate is zero or negative', 'test that MirrorMADGRAD raises ValueError when weight_decay is negative', 'test that MirrorMADGRAD raises ValueError when eps is negative', 'test MirrorMADGRAD optimizer step reduces loss over 5 iterations with full precision params']
```

Usage

```
{'test_MADGRAD_invalid_momentum': 'test that MADGRAD raises ValueError when momentum is set to 1.0', 'test_MADGRAD_invalid_lr': 'test that MADGRAD raises ValueError when learning rate is zero or negative', 'test_MADGRAD_invalid_weight_decay': 'test that MADGRAD raises ValueError when weight_decay is negative', 'test_MADGRAD_step_full_precision': 'test MADGRAD optimizer step reduces loss on full precision CUDA tensors', 'test_MADGRAD_sparse_grads': 'test MADGRAD produces identical results for dense and sparse gradient tensors'}
```

## File: facebookresearch_madgrad/tests/test_mirrormadgrad.py

Prompts

```
['test that MADGRAD raises ValueError when momentum is set to 1.0', 'test that MADGRAD raises ValueError when learning rate is zero or negative', 'test that MADGRAD raises ValueError when weight_decay is negative', 'test MADGRAD optimizer step reduces loss on full precision CUDA tensors', 'test MADGRAD produces identical results for dense and sparse gradient tensors', 'test that MirrorMADGRAD raises ValueError when momentum is set to 1.0', 'test that MirrorMADGRAD raises ValueError when learning rate is zero or negative', 'test that MirrorMADGRAD raises ValueError when weight_decay is negative', 'test that MirrorMADGRAD raises ValueError when eps is negative', 'test MirrorMADGRAD optimizer step reduces loss over 5 iterations with full precision params']
```

Usage

```
{'test_MirrorMADGRAD_invalid_momentum': 'test that MirrorMADGRAD raises ValueError when momentum is set to 1.0', 'test_MirrorMADGRAD_invalid_lr': 'test that MirrorMADGRAD raises ValueError when learning rate is zero or negative', 'test_MirrorMADGRAD_invalid_weight_decay': 'test that MirrorMADGRAD raises ValueError when weight_decay is negative', 'test_MirrorMADGRAD_invalid_eps': 'test that MirrorMADGRAD raises ValueError when eps is negative', 'test_MirrorMADGRAD_step_full_precision': 'test MirrorMADGRAD optimizer step reduces loss over 5 iterations with full precision params'}
```

