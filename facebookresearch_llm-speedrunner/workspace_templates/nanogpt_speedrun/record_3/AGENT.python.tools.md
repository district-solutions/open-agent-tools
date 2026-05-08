# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/workspace_templates/nanogpt_speedrun/record_3/train_gpt2.py

Prompts

```
['run the GPT-2 model training loop with DDP across multiple GPUs using torchrun', 'create an OrthogonalNesterov optimizer that uses Newton-Schulz iteration for zeroth power gradient updates', 'build a CombinedOptimizer that wraps multiple optimizers and supports unified step, zero_grad, and scale_lrs', 'create a GPT-2 model with Rotary embeddings, causal self-attention, and weight-tying between embeddings and lm_head', 'create a DistributedDataLoader that shards binary token files across DDP processes for distributed training']
```

Usage

```
{'run_gpt2_training': 'run the GPT-2 model training loop with DDP across multiple GPUs using torchrun', 'create_orthogonal_nesterov_optimizer': 'create an OrthogonalNesterov optimizer that uses Newton-Schulz iteration for zeroth power gradient updates', 'build_combined_optimizer': 'build a CombinedOptimizer that wraps multiple optimizers and supports unified step, zero_grad, and scale_lrs', 'create_gpt_model': 'create a GPT-2 model with Rotary embeddings, causal self-attention, and weight-tying between embeddings and lm_head', 'create_distributed_dataloader': 'create a DistributedDataLoader that shards binary token files across DDP processes for distributed training'}
```

