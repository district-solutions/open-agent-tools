# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/tests/trainer/test_activation_checkpointing.py

Prompts

```
['add activation checkpoint configuration options to a CfgNode for memory-efficient training', 'create an ActivationCheckpointModelingHook from a config to wrap model layers with checkpointing', 'apply the ActivationCheckpointModelingHook to a PyTorch model to wrap children with CheckpointWrapper', 'test that activation checkpoint config adds expected REENTRANT and AUTO_WRAP_POLICY defaults', 'run Detectron2GoRunner training with activation checkpointing enabled via modeling hooks and resume']
```

Usage

```
{'add_activation_checkpoint_configs': 'add activation checkpoint configuration options to a CfgNode for memory-efficient training', 'create_ActivationCheckpointModelingHook': 'create an ActivationCheckpointModelingHook from a config to wrap model layers with checkpointing', 'apply_ActivationCheckpointModelingHook': 'apply the ActivationCheckpointModelingHook to a PyTorch model to wrap children with CheckpointWrapper', 'test_activation_checkpointing_config': 'test that activation checkpoint config adds expected REENTRANT and AUTO_WRAP_POLICY defaults', 'run_training_with_activation_checkpointing': 'run Detectron2GoRunner training with activation checkpointing enabled via modeling hooks and resume'}
```

