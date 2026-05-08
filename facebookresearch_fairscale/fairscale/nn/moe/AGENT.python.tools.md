# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/moe/moe_layer.py

Prompts

```
['create a MOELayer with a Top2Gate and expert network for mixture of experts', 'run the MOELayer forward pass with a 3D input tensor to get expert-weighted output', 'review the MOELayer constructor to understand gate, experts, and process group arguments', 'test the _AllToAll custom autograd function for distributed all-to-all communication', 'summarize the MOELayer forward method implementing GShard Algorithm 2 with dispatch and combine', 'create a Top2Gate module with a given model dimension and number of experts', 'run top2gating on logits tensor to get auxiliary loss, combine weights, and dispatch mask', 'generate Gumbel-distributed random samples for a given shape and device using gumbel_rsample', 'create a one-hot encoded tensor from index values and number of classes', 'review the top2gating function implementing Top2Gating from the GShard paper with Gumbel-max trick']
```

Usage

```
{'create_moe_layer': 'create a MOELayer with a Top2Gate and expert network for mixture of experts', 'run_moe_forward': 'run the MOELayer forward pass with a 3D input tensor to get expert-weighted output', 'review_moe_layer_init': 'review the MOELayer constructor to understand gate, experts, and process group arguments', 'test_alltoall_autograd': 'test the _AllToAll custom autograd function for distributed all-to-all communication', 'summarize_moe_layer_forward': 'summarize the MOELayer forward method implementing GShard Algorithm 2 with dispatch and combine'}
```

## File: facebookresearch_fairscale/fairscale/nn/moe/top2gate.py

Prompts

```
['create a MOELayer with a Top2Gate and expert network for mixture of experts', 'run the MOELayer forward pass with a 3D input tensor to get expert-weighted output', 'review the MOELayer constructor to understand gate, experts, and process group arguments', 'test the _AllToAll custom autograd function for distributed all-to-all communication', 'summarize the MOELayer forward method implementing GShard Algorithm 2 with dispatch and combine', 'create a Top2Gate module with a given model dimension and number of experts', 'run top2gating on logits tensor to get auxiliary loss, combine weights, and dispatch mask', 'generate Gumbel-distributed random samples for a given shape and device using gumbel_rsample', 'create a one-hot encoded tensor from index values and number of classes', 'review the top2gating function implementing Top2Gating from the GShard paper with Gumbel-max trick']
```

Usage

```
{'create_Top2Gate_module': 'create a Top2Gate module with a given model dimension and number of experts', 'run_top2gating_on_logits': 'run top2gating on logits tensor to get auxiliary loss, combine weights, and dispatch mask', 'generate_gumbel_rsample': 'generate Gumbel-distributed random samples for a given shape and device using gumbel_rsample', 'create_one_hot_encoding': 'create a one-hot encoded tensor from index values and number of classes', 'review_top2gating_implementation': 'review the top2gating function implementing Top2Gating from the GShard paper with Gumbel-max trick'}
```

