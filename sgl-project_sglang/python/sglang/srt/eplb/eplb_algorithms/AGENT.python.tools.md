# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/eplb/eplb_algorithms/deepseek.py

Prompts

```
['build a balanced packing of weighted items into equal-sized packs with minimized weight imbalance', 'create expert replication that distributes logical experts across physical replicas to minimize maximum load', 'test hierarchical expert rebalancing across nodes and GPUs with NVLink-aware packing', 'refactor the expert rebalance entry point to support both hierarchical and global load-balance policies', 'summarize the DeepSeek EPLB module for expert-parallelism load balancing in MoE models', 'build a function that packs groups of tokens across distributed nodes for load balancing', 'create a function that maps redundant experts chunkwise for MoE layer load balancing', 'run expert rebalancing for the prefill phase across multiple nodes and groups', 'run expert rebalancing for the decode phase with physical-to-logical expert mapping', 'test the unified expert rebalancing dispatcher supporting hierarchical and decode modes', 'run the rebalance_experts function to balance expert load across GPUs for expert-parallelism', 'run rebalance_experts with active_ranks below num_gpus to trigger global load-balance fallback', 'run rebalance_experts with enable_hierarchical to use hierarchical load-balance policy across groups and nodes', 'run rebalance_experts with enable_hierarchical disabled to use global load-balance policy across all GPUs']
```

Usage

```
{'build_balanced_packing': 'build a balanced packing of weighted items into equal-sized packs with minimized weight imbalance', 'create_replicate_experts': 'create expert replication that distributes logical experts across physical replicas to minimize maximum load', 'test_rebalance_experts_hierarchical': 'test hierarchical expert rebalancing across nodes and GPUs with NVLink-aware packing', 'refactor_rebalance_experts': 'refactor the expert rebalance entry point to support both hierarchical and global load-balance policies', 'summarize_deepseek_eplb': 'summarize the DeepSeek EPLB module for expert-parallelism load balancing in MoE models'}
```

## File: sgl-project_sglang/python/sglang/srt/eplb/eplb_algorithms/deepseek_vec.py

Prompts

```
['build a balanced packing of weighted items into equal-sized packs with minimized weight imbalance', 'create expert replication that distributes logical experts across physical replicas to minimize maximum load', 'test hierarchical expert rebalancing across nodes and GPUs with NVLink-aware packing', 'refactor the expert rebalance entry point to support both hierarchical and global load-balance policies', 'summarize the DeepSeek EPLB module for expert-parallelism load balancing in MoE models', 'build a function that packs groups of tokens across distributed nodes for load balancing', 'create a function that maps redundant experts chunkwise for MoE layer load balancing', 'run expert rebalancing for the prefill phase across multiple nodes and groups', 'run expert rebalancing for the decode phase with physical-to-logical expert mapping', 'test the unified expert rebalancing dispatcher supporting hierarchical and decode modes', 'run the rebalance_experts function to balance expert load across GPUs for expert-parallelism', 'run rebalance_experts with active_ranks below num_gpus to trigger global load-balance fallback', 'run rebalance_experts with enable_hierarchical to use hierarchical load-balance policy across groups and nodes', 'run rebalance_experts with enable_hierarchical disabled to use global load-balance policy across all GPUs']
```

Usage

```
{'build_pack_groups': 'build a function that packs groups of tokens across distributed nodes for load balancing', 'create_make_redundant_experts': 'create a function that maps redundant experts chunkwise for MoE layer load balancing', 'run_prefill_rebalance_experts': 'run expert rebalancing for the prefill phase across multiple nodes and groups', 'run_decode_rebalance_experts': 'run expert rebalancing for the decode phase with physical-to-logical expert mapping', 'test_rebalance_experts': 'test the unified expert rebalancing dispatcher supporting hierarchical and decode modes'}
```

## File: sgl-project_sglang/python/sglang/srt/eplb/eplb_algorithms/elasticity_aware.py

Prompts

```
['build a balanced packing of weighted items into equal-sized packs with minimized weight imbalance', 'create expert replication that distributes logical experts across physical replicas to minimize maximum load', 'test hierarchical expert rebalancing across nodes and GPUs with NVLink-aware packing', 'refactor the expert rebalance entry point to support both hierarchical and global load-balance policies', 'summarize the DeepSeek EPLB module for expert-parallelism load balancing in MoE models', 'build a function that packs groups of tokens across distributed nodes for load balancing', 'create a function that maps redundant experts chunkwise for MoE layer load balancing', 'run expert rebalancing for the prefill phase across multiple nodes and groups', 'run expert rebalancing for the decode phase with physical-to-logical expert mapping', 'test the unified expert rebalancing dispatcher supporting hierarchical and decode modes', 'run the rebalance_experts function to balance expert load across GPUs for expert-parallelism', 'run rebalance_experts with active_ranks below num_gpus to trigger global load-balance fallback', 'run rebalance_experts with enable_hierarchical to use hierarchical load-balance policy across groups and nodes', 'run rebalance_experts with enable_hierarchical disabled to use global load-balance policy across all GPUs']
```

Usage

```
{'run_rebalance_experts': 'run the rebalance_experts function to balance expert load across GPUs for expert-parallelism', 'test_rebalance_experts_hierarchical': 'test the rebalance_experts_hierarchical function for hierarchical expert load balancing', 'run_rebalance_experts_fallback': 'run rebalance_experts with active_ranks below num_gpus to trigger global load-balance fallback', 'run_rebalance_experts_hierarchical_mode': 'run rebalance_experts with enable_hierarchical to use hierarchical load-balance policy across groups and nodes', 'run_rebalance_experts_global_mode': 'run rebalance_experts with enable_hierarchical disabled to use global load-balance policy across all GPUs'}
```

