# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/workspace_templates/nanogpt_speedrun/record_6/train_gpt2.py

Prompts

```
['run the GPT-2 model training loop with DDP, Muon optimizer, and gradient accumulation on tokenized data', 'create a Muon optimizer instance with SGD-momentum and Newton-Schulz orthogonalization for 2D transformer parameters', 'build a GPT-2 model with rotary embeddings, causal self-attention, RMSNorm, and ReLU-squared MLP blocks', 'test the Newton-Schulz iteration function that orthogonalizes a 2D matrix using quintic iteration in bfloat16', 'review the DistributedDataLoader class that loads binary token shards and yields batches across distributed processes']
```

Usage

```
{'run_GPT_training': 'run the GPT-2 model training loop with DDP, Muon optimizer, and gradient accumulation on tokenized data', 'create_Muon_optimizer': 'create a Muon optimizer instance with SGD-momentum and Newton-Schulz orthogonalization for 2D transformer parameters', 'build_GPT_model': 'build a GPT-2 model with rotary embeddings, causal self-attention, RMSNorm, and ReLU-squared MLP blocks', 'test_zeropower_via_newtonschulz5': 'test the Newton-Schulz iteration function that orthogonalizes a 2D matrix using quintic iteration in bfloat16', 'review_DistributedDataLoader': 'review the DistributedDataLoader class that loads binary token shards and yields batches across distributed processes'}
```

