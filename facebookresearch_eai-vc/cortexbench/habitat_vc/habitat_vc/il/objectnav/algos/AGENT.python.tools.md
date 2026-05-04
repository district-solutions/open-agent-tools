# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/habitat_vc/habitat_vc/il/objectnav/algos/agent.py

Prompts

```
['create an ILAgent with a model, learning rates, and mini-batch size for imitation learning', 'run the ILAgent update method to train on rollouts using cross-entropy action loss', 'customize the ILAgent before_backward and before_step hooks for gradient clipping or logging', 'initialize distributed training with DecentralizedDistributedMixin to wrap the model in DDP', 'create a DDPILAgent that combines ILAgent with distributed data parallel training support']
```

Usage

```
{'create_ILAgent': 'create an ILAgent with a model, learning rates, and mini-batch size for imitation learning', 'run_ILAgent_update': 'run the ILAgent update method to train on rollouts using cross-entropy action loss', 'customize_ILAgent_hooks': 'customize the ILAgent before_backward and before_step hooks for gradient clipping or logging', 'init_DecentralizedDistributedMixin': 'initialize distributed training with DecentralizedDistributedMixin to wrap the model in DDP', 'create_DDPILAgent': 'create a DDPILAgent that combines ILAgent with distributed data parallel training support'}
```

