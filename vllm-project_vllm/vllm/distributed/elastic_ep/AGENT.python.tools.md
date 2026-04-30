# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/elastic_ep/elastic_execute.py

Prompts

```
['transfer model weights between distributed workers during elastic EP scaling', 'broadcast expert mapping metadata across data parallel group ranks', 'create standby distributed groups for elastic EP reconfiguration', 'switch to new distributed groups and reconfigure MoE modules after scaling', 'perform expert placement load balancing expert resharding after scaling', 'create an ElasticEPScalingState instance to manage elastic expert parallelism scaling with worker type and scale type', 'run the ElasticEPScalingState progress method to advance through scale up or scale down state transitions', 'test the staged TCP store barrier synchronization across DP group engines with timeout handling', 'refactor the handle_notification method to process EEP notification types during scaling operations', 'summarize the ElasticEPScalingState methods for weight transfer, KV cache sync, and EPLB reshuffle', 'get the standby data parallel group coordinator for distributed inference', 'get the standby expert parallel group coordinator for mixture-of-experts routing', 'get the standby expert parallel load balancing group coordinator', 'pop and clear all standby groups returning world, dp, ep, eplb coordinators and node count']
```

Usage

```
{'transfer_weights': 'transfer model weights between distributed workers during elastic EP scaling', 'broadcast_expert_mapping': 'broadcast expert mapping metadata across data parallel group ranks', 'create_standby_groups': 'create standby distributed groups for elastic EP reconfiguration', 'switch_and_prepare': 'switch to new distributed groups and reconfigure MoE modules after scaling', 'perform_eplb_reshuffle': 'perform expert placement load balancing expert resharding after scaling'}
```

## File: vllm-project_vllm/vllm/distributed/elastic_ep/elastic_state.py

Prompts

```
['transfer model weights between distributed workers during elastic EP scaling', 'broadcast expert mapping metadata across data parallel group ranks', 'create standby distributed groups for elastic EP reconfiguration', 'switch to new distributed groups and reconfigure MoE modules after scaling', 'perform expert placement load balancing expert resharding after scaling', 'create an ElasticEPScalingState instance to manage elastic expert parallelism scaling with worker type and scale type', 'run the ElasticEPScalingState progress method to advance through scale up or scale down state transitions', 'test the staged TCP store barrier synchronization across DP group engines with timeout handling', 'refactor the handle_notification method to process EEP notification types during scaling operations', 'summarize the ElasticEPScalingState methods for weight transfer, KV cache sync, and EPLB reshuffle', 'get the standby data parallel group coordinator for distributed inference', 'get the standby expert parallel group coordinator for mixture-of-experts routing', 'get the standby expert parallel load balancing group coordinator', 'pop and clear all standby groups returning world, dp, ep, eplb coordinators and node count']
```

Usage

```
{'create_ElasticEPScalingState': 'create an ElasticEPScalingState instance to manage elastic expert parallelism scaling with worker type and scale type', 'run_ElasticEPScalingState_progress': 'run the ElasticEPScalingState progress method to advance through scale up or scale down state transitions', 'test_ElasticEPScalingState_staged_barrier': 'test the staged TCP store barrier synchronization across DP group engines with timeout handling', 'refactor_ElasticEPScalingState_handle_notification': 'refactor the handle_notification method to process EEP notification types during scaling operations', 'summarize_ElasticEPScalingState_methods': 'summarize the ElasticEPScalingState methods for weight transfer, KV cache sync, and EPLB reshuffle'}
```

## File: vllm-project_vllm/vllm/distributed/elastic_ep/standby_state.py

Prompts

```
['transfer model weights between distributed workers during elastic EP scaling', 'broadcast expert mapping metadata across data parallel group ranks', 'create standby distributed groups for elastic EP reconfiguration', 'switch to new distributed groups and reconfigure MoE modules after scaling', 'perform expert placement load balancing expert resharding after scaling', 'create an ElasticEPScalingState instance to manage elastic expert parallelism scaling with worker type and scale type', 'run the ElasticEPScalingState progress method to advance through scale up or scale down state transitions', 'test the staged TCP store barrier synchronization across DP group engines with timeout handling', 'refactor the handle_notification method to process EEP notification types during scaling operations', 'summarize the ElasticEPScalingState methods for weight transfer, KV cache sync, and EPLB reshuffle', 'get the standby data parallel group coordinator for distributed inference', 'get the standby expert parallel group coordinator for mixture-of-experts routing', 'get the standby expert parallel load balancing group coordinator', 'pop and clear all standby groups returning world, dp, ep, eplb coordinators and node count']
```

Usage

```
{'create_standby_groups': 'create standby distributed groups for world, dp, ep, and eplb with configurable tensor parallel size', 'get_standby_dp_group': 'get the standby data parallel group coordinator for distributed inference', 'get_standby_ep_group': 'get the standby expert parallel group coordinator for mixture-of-experts routing', 'get_standby_eplb_group': 'get the standby expert parallel load balancing group coordinator', 'pop_standby_groups': 'pop and clear all standby groups returning world, dp, ep, eplb coordinators and node count'}
```

