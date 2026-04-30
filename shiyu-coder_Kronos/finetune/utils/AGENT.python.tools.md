# Agent Python Tools

- repo: shiyu-coder/Kronos
- repo_uri: https://github.com/shiyu-coder/Kronos

## File: shiyu-coder_Kronos/finetune/utils/training_utils.py

Prompts

```
['run distributed data parallel setup by initializing torch.distributed process group with nccl backend', 'cleanup the distributed process group by destroying initialized torch.distributed processes', 'set random seed for reproducibility across python random, numpy, and torch libraries', 'get human-readable model parameter count string like 175.0B or 7.1M from a pytorch model', 'reduce a tensor across all distributed processes using sum or average operation']
```

Usage

```
{'setup_ddp': 'run distributed data parallel setup by initializing torch.distributed process group with nccl backend', 'cleanup_ddp': 'cleanup the distributed process group by destroying initialized torch.distributed processes', 'set_seed': 'set random seed for reproducibility across python random, numpy, and torch libraries', 'get_model_size': 'get human-readable model parameter count string like 175.0B or 7.1M from a pytorch model', 'reduce_tensor': 'reduce a tensor across all distributed processes using sum or average operation'}
```

