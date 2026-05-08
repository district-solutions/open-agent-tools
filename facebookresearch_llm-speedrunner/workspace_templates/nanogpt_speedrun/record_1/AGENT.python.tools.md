# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/workspace_templates/nanogpt_speedrun/record_1/train_gpt2.py

Prompts

```
['run the GPT model forward pass with token indices and optional targets for loss computation', 'build a GPTConfig dataclass to set block_size, vocab_size, n_layer, n_head, and n_embd hyperparameters', 'create a DistributedDataLoader to load binary token shards across multiple DDP processes for training', 'test the CausalSelfAttention module with scaled dot product attention and causal masking on input tensors', 'review the GPT configure_optimizers method to set up AdamW with weight decay and learning rate']
```

Usage

```
{'run_GPT_model': 'run the GPT model forward pass with token indices and optional targets for loss computation', 'build_GPTConfig': 'build a GPTConfig dataclass to set block_size, vocab_size, n_layer, n_head, and n_embd hyperparameters', 'create_DistributedDataLoader': 'create a DistributedDataLoader to load binary token shards across multiple DDP processes for training', 'test_CausalSelfAttention': 'test the CausalSelfAttention module with scaled dot product attention and causal masking on input tensors', 'review_GPT_configure_optimizers': 'review the GPT configure_optimizers method to set up AdamW with weight decay and learning rate'}
```

