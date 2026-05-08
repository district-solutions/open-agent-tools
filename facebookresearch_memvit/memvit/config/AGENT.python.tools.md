# Agent Python Tools

- repo: facebookresearch/memvit
- repo_uri: https://github.com/facebookresearch/memvit

## File: facebookresearch_memvit/memvit/config/defaults.py

Prompts

```
['get a copy of the default MeMViT config CfgNode for training or testing', 'get a cloned config and modify TRAIN.BATCH_SIZE or SOLVER.BASE_LR before training', 'validate and infer config settings including LR scaling by NUM_SHARDS before training', 'assert checkpoint type is pytorch or caffe2 and batch size divides evenly across GPUs', 'review the MeMViT specific config options like MEMVIT.ENABLE, MEMVIT.ATTN_MAX_LEN, and MEMVIT.SAMPLER']
```

Usage

```
{'get_cfg_default': 'get a copy of the default MeMViT config CfgNode for training or testing', 'get_cfg_clone_modify': 'get a cloned config and modify TRAIN.BATCH_SIZE or SOLVER.BASE_LR before training', 'assert_and_infer_cfg_validate': 'validate and infer config settings including LR scaling by NUM_SHARDS before training', 'assert_and_infer_cfg_checkpoints': 'assert checkpoint type is pytorch or caffe2 and batch size divides evenly across GPUs', 'review_cfg_memvit_options': 'review the MeMViT specific config options like MEMVIT.ENABLE, MEMVIT.ATTN_MAX_LEN, and MEMVIT.SAMPLER'}
```

