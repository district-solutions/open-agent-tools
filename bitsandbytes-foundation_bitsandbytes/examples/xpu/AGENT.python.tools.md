# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/examples/xpu/benchmark_paged_memory.py

Prompts

```
['run the paged optimizer memory benchmark to compare GPU memory usage across AdamW variants', 'create a LLaMA model from config with configurable hidden size, layers, and device', 'measure peak GPU memory usage during training with a specified optimizer class', 'test GPU memory savings of paged optimizers versus non-paged optimizers', 'summarize benchmark results comparing peak memory and optimizer state distribution across AdamW variants', 'run single-step training with a bitsandbytes paged optimizer on XPU device', 'compare paged_adamw against standard adamw optimizer loss curves', 'run training using HuggingFace Trainer with a bitsandbytes paged optimizer', 'create a bitsandbytes optimizer by name such as paged_adamw8bit or paged_lion32bit', 'prepare and tokenize a subset of the Alpaca dataset for causal language model training']
```

Usage

```
{'run_benchmark_paged_memory': 'run the paged optimizer memory benchmark to compare GPU memory usage across AdamW variants', 'create_model_llama': 'create a LLaMA model from config with configurable hidden size, layers, and device', 'measure_training_memory': 'measure peak GPU memory usage during training with a specified optimizer class', 'test_optimizer_memory_savings': 'test GPU memory savings of paged optimizers versus non-paged optimizers', 'summarize_benchmark_results': 'summarize benchmark results comparing peak memory and optimizer state distribution across AdamW variants'}
```

## File: bitsandbytes-foundation_bitsandbytes/examples/xpu/paged_xpu_training.py

Prompts

```
['run the paged optimizer memory benchmark to compare GPU memory usage across AdamW variants', 'create a LLaMA model from config with configurable hidden size, layers, and device', 'measure peak GPU memory usage during training with a specified optimizer class', 'test GPU memory savings of paged optimizers versus non-paged optimizers', 'summarize benchmark results comparing peak memory and optimizer state distribution across AdamW variants', 'run single-step training with a bitsandbytes paged optimizer on XPU device', 'compare paged_adamw against standard adamw optimizer loss curves', 'run training using HuggingFace Trainer with a bitsandbytes paged optimizer', 'create a bitsandbytes optimizer by name such as paged_adamw8bit or paged_lion32bit', 'prepare and tokenize a subset of the Alpaca dataset for causal language model training']
```

Usage

```
{'run_training_paged_optimizer': 'run single-step training with a bitsandbytes paged optimizer on XPU device', 'compare_paged_vs_nonpaged': 'compare paged_adamw against standard adamw optimizer loss curves', 'run_trainer_mode': 'run training using HuggingFace Trainer with a bitsandbytes paged optimizer', 'create_bnb_optimizer': 'create a bitsandbytes optimizer by name such as paged_adamw8bit or paged_lion32bit', 'prepare_alpaca_dataset': 'prepare and tokenize a subset of the Alpaca dataset for causal language model training'}
```

