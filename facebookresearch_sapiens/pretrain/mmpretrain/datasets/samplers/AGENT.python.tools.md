# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/datasets/samplers/repeat_aug.py

Prompts

```
['create a RepeatAugSampler instance with a dataset, shuffle enabled, and 3 repeats per sample', 'iterate over the RepeatAugSampler to get repeated dataset indices for distributed training', 'set the epoch on the RepeatAugSampler to ensure different shuffle ordering each epoch', 'get the number of selected samples in the current rank using len() on the sampler', 'register the RepeatAugSampler class in the mmpretrain DATA_SAMPLERS registry for config-based instantiation']
```

Usage

```
{'create_repeat_aug_sampler': 'create a RepeatAugSampler instance with a dataset, shuffle enabled, and 3 repeats per sample', 'iterate_sampler_indices': 'iterate over the RepeatAugSampler to get repeated dataset indices for distributed training', 'set_sampler_epoch': 'set the epoch on the RepeatAugSampler to ensure different shuffle ordering each epoch', 'get_sampler_length': 'get the number of selected samples in the current rank using len() on the sampler', 'register_repeat_aug_sampler': 'register the RepeatAugSampler class in the mmpretrain DATA_SAMPLERS registry for config-based instantiation'}
```

