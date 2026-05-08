# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/optimizer/tests/fp16optimizer_test.py

Prompts

```
['run the unittest test suite for fp16 optimizer master maintain and memory efficient modes', 'test that fp16 optimizer master params are float32 and model params are float16 after init', 'test that zero_grad correctly resets fp16 model gradients to zero while preserving data types', 'test syncing fp16 model gradients to fp32 master params with loss scaler applied', 'test memory efficient fp16 optimizer training loop produces same results as baseline optimizer', 'test StochasticWeightAveraging optimizer in auto mode with swa_start and swa_freq parameters', 'test StochasticWeightAveraging optimizer in manual mode calling update_swa after each step', 'test that SWA changes learning rate to swa_lr after swa_start steps in auto mode', 'test bn_update method to update BatchNorm running statistics on a DataLoader', 'test StochasticWeightAveraging wrapping the Lamb optimizer on the Rosenbrock function']
```

Usage

```
{'run_fp16_optimizer_tests': 'run the unittest test suite for fp16 optimizer master maintain and memory efficient modes', 'test_master_maintain_init': 'test that fp16 optimizer master params are float32 and model params are float16 after init', 'test_master_maintain_zero_grad': 'test that zero_grad correctly resets fp16 model gradients to zero while preserving data types', 'test_master_maintain_grads_sync': 'test syncing fp16 model gradients to fp32 master params with loss scaler applied', 'test_memory_efficient_logic': 'test memory efficient fp16 optimizer training loop produces same results as baseline optimizer'}
```

## File: facebookresearch_pytext/pytext/optimizer/tests/test_swa.py

Prompts

```
['run the unittest test suite for fp16 optimizer master maintain and memory efficient modes', 'test that fp16 optimizer master params are float32 and model params are float16 after init', 'test that zero_grad correctly resets fp16 model gradients to zero while preserving data types', 'test syncing fp16 model gradients to fp32 master params with loss scaler applied', 'test memory efficient fp16 optimizer training loop produces same results as baseline optimizer', 'test StochasticWeightAveraging optimizer in auto mode with swa_start and swa_freq parameters', 'test StochasticWeightAveraging optimizer in manual mode calling update_swa after each step', 'test that SWA changes learning rate to swa_lr after swa_start steps in auto mode', 'test bn_update method to update BatchNorm running statistics on a DataLoader', 'test StochasticWeightAveraging wrapping the Lamb optimizer on the Rosenbrock function']
```

Usage

```
{'test_swa_auto_mode': 'test StochasticWeightAveraging optimizer in auto mode with swa_start and swa_freq parameters', 'test_swa_manual_mode': 'test StochasticWeightAveraging optimizer in manual mode calling update_swa after each step', 'test_swa_lr': 'test that SWA changes learning rate to swa_lr after swa_start steps in auto mode', 'test_swa_bn_update': 'test bn_update method to update BatchNorm running statistics on a DataLoader', 'test_swa_lamb_optimizer': 'test StochasticWeightAveraging wrapping the Lamb optimizer on the Rosenbrock function'}
```

