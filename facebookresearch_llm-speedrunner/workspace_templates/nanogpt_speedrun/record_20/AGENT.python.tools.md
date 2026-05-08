# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/workspace_templates/nanogpt_speedrun/record_20/train_gpt2.py

Prompts

```
['run the distributed GPT-2 training loop with Muon optimizer and FP8 lm_head on GPU', 'review the Muon optimizer class that performs Newton-Schulz orthogonalization on weight updates', 'review the GPT model class with U-net skip connections and FlexAttention block masks', 'review the custom FP8 matmul operator for efficient lm_head forward and backward passes', 'review the distributed data generator that shards binary token files across GPU ranks']
```

Usage

```
{'run_train_gpt2': 'run the distributed GPT-2 training loop with Muon optimizer and FP8 lm_head on GPU', 'review_Muon_optimizer': 'review the Muon optimizer class that performs Newton-Schulz orthogonalization on weight updates', 'review_GPT_model': 'review the GPT model class with U-net skip connections and FlexAttention block masks', 'review_mm_op': 'review the custom FP8 matmul operator for efficient lm_head forward and backward passes', 'review_distributed_data_generator': 'review the distributed data generator that shards binary token files across GPU ranks'}
```

