# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/nn/moe/test_moe_layer.py

Prompts

```
['create a MOELayer using Top2Gate and a Linear expert module for mixture of experts', 'test the MOELayer forward pass with identity expert weights and verify output shape', 'test the MOELayer with multiple local experts using a ModuleList of Linear modules', 'test the MOELayer backward pass by computing MSELoss and verifying gradient values', 'create a RoundRobinGate class that round-robins tokens to experts for routing tests', 'test creating a Top2Gate instance with specified input and expert dimensions', 'test creating a Top2Gate instance and moving it to CUDA device', 'test the Top2Gate forward pass returning auxiliary loss, combine weights, and dispatch mask', 'test the top2gating function to verify expert capacity allocation per GShard Algorithm 1', 'test the top2gating function dispatch mask behavior when all tokens select the same expert']
```

Usage

```
{'create_MOELayer_with_Top2Gate': 'create a MOELayer using Top2Gate and a Linear expert module for mixture of experts', 'test_MOELayer_forward_pass': 'test the MOELayer forward pass with identity expert weights and verify output shape', 'test_MOELayer_multi_experts': 'test the MOELayer with multiple local experts using a ModuleList of Linear modules', 'test_MOELayer_backward_pass': 'test the MOELayer backward pass by computing MSELoss and verifying gradient values', 'create_RoundRobinGate_for_routing': 'create a RoundRobinGate class that round-robins tokens to experts for routing tests'}
```

## File: facebookresearch_fairscale/tests/nn/moe/test_top2gating.py

Prompts

```
['create a MOELayer using Top2Gate and a Linear expert module for mixture of experts', 'test the MOELayer forward pass with identity expert weights and verify output shape', 'test the MOELayer with multiple local experts using a ModuleList of Linear modules', 'test the MOELayer backward pass by computing MSELoss and verifying gradient values', 'create a RoundRobinGate class that round-robins tokens to experts for routing tests', 'test creating a Top2Gate instance with specified input and expert dimensions', 'test creating a Top2Gate instance and moving it to CUDA device', 'test the Top2Gate forward pass returning auxiliary loss, combine weights, and dispatch mask', 'test the top2gating function to verify expert capacity allocation per GShard Algorithm 1', 'test the top2gating function dispatch mask behavior when all tokens select the same expert']
```

Usage

```
{'test_Top2Gate_creation': 'test creating a Top2Gate instance with specified input and expert dimensions', 'test_Top2Gate_cuda': 'test creating a Top2Gate instance and moving it to CUDA device', 'test_Top2Gate_forward': 'test the Top2Gate forward pass returning auxiliary loss, combine weights, and dispatch mask', 'test_top2gating_overflow': 'test the top2gating function to verify expert capacity allocation per GShard Algorithm 1', 'test_top2gating_dispatch': 'test the top2gating function dispatch mask behavior when all tokens select the same expert'}
```

