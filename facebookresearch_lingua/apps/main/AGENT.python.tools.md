# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/main/eval.py

Prompts

```
['run the LM Harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources and compute NLL metrics per token and per character', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval harness compatibility', 'run the eval.py CLI module with a config file and dot-list overrides for EvalArgs', 'consolidate checkpoints and load a consolidated LMTransformer model with its tokenizer for evaluation', 'run the generate.py CLI to load a consolidated LLM checkpoint and generate text from user prompts', 'sample tokens from model logits using top_p nucleus sampling with configurable temperature', 'sample tokens from model logits using top_k sampling to restrict to the k most probable tokens', 'pack multiple tokenized prompts into a single concatenated tensor with per-prompt length tracking', 'load a consolidated LMTransformer model and tokenizer from a checkpoint directory with params.json config', 'run the lingua LLM training loop with a config file via train.py config=path/to/config.yaml', 'configure TrainArgs dataclass to set model, optimizer, data, and distributed training parameters', 'manage TrainState to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, and distributed parallelism settings', 'save and resume training checkpoints using CheckpointManager for model, optimizer, and train state', 'build a language model transformer using LMTransformer with LMTransformerArgs for vocab size and layers', 'create a causal attention mask for fmha, sdpa, or flex_attention implementations with optional sliding window', 'calculate the number of FLOPs per token given non-embed params, layers, dim, and sequence length', 'build an FSDP grouping plan tuple for model layers and output for fully sharded data parallel training', 'parallelize a transformer model across tensor parallel devices using ColwiseParallel and RowwiseParallel strategies']
```

Usage

```
{'run_lm_harness_evaluation': 'run the LM Harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run_validation_evaluation': 'run validation evaluation on JSONL sources and compute NLL metrics per token and per character', 'create_eval_harness_lm_wrapper': 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval harness compatibility', 'run_eval_from_cli': 'run the eval.py CLI module with a config file and dot-list overrides for EvalArgs', 'consolidate_and_load_model': 'consolidate checkpoints and load a consolidated LMTransformer model with its tokenizer for evaluation'}
```

## File: facebookresearch_lingua/apps/main/generate.py

Prompts

```
['run the LM Harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources and compute NLL metrics per token and per character', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval harness compatibility', 'run the eval.py CLI module with a config file and dot-list overrides for EvalArgs', 'consolidate checkpoints and load a consolidated LMTransformer model with its tokenizer for evaluation', 'run the generate.py CLI to load a consolidated LLM checkpoint and generate text from user prompts', 'sample tokens from model logits using top_p nucleus sampling with configurable temperature', 'sample tokens from model logits using top_k sampling to restrict to the k most probable tokens', 'pack multiple tokenized prompts into a single concatenated tensor with per-prompt length tracking', 'load a consolidated LMTransformer model and tokenizer from a checkpoint directory with params.json config', 'run the lingua LLM training loop with a config file via train.py config=path/to/config.yaml', 'configure TrainArgs dataclass to set model, optimizer, data, and distributed training parameters', 'manage TrainState to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, and distributed parallelism settings', 'save and resume training checkpoints using CheckpointManager for model, optimizer, and train state', 'build a language model transformer using LMTransformer with LMTransformerArgs for vocab size and layers', 'create a causal attention mask for fmha, sdpa, or flex_attention implementations with optional sliding window', 'calculate the number of FLOPs per token given non-embed params, layers, dim, and sequence length', 'build an FSDP grouping plan tuple for model layers and output for fully sharded data parallel training', 'parallelize a transformer model across tensor parallel devices using ColwiseParallel and RowwiseParallel strategies']
```

Usage

```
{'run_generate_text': 'run the generate.py CLI to load a consolidated LLM checkpoint and generate text from user prompts', 'sample_tokens_top_p': 'sample tokens from model logits using top_p nucleus sampling with configurable temperature', 'sample_tokens_top_k': 'sample tokens from model logits using top_k sampling to restrict to the k most probable tokens', 'pack_prompts_packed': 'pack multiple tokenized prompts into a single concatenated tensor with per-prompt length tracking', 'load_consolidated_model': 'load a consolidated LMTransformer model and tokenizer from a checkpoint directory with params.json config'}
```

## File: facebookresearch_lingua/apps/main/train.py

Prompts

```
['run the LM Harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources and compute NLL metrics per token and per character', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval harness compatibility', 'run the eval.py CLI module with a config file and dot-list overrides for EvalArgs', 'consolidate checkpoints and load a consolidated LMTransformer model with its tokenizer for evaluation', 'run the generate.py CLI to load a consolidated LLM checkpoint and generate text from user prompts', 'sample tokens from model logits using top_p nucleus sampling with configurable temperature', 'sample tokens from model logits using top_k sampling to restrict to the k most probable tokens', 'pack multiple tokenized prompts into a single concatenated tensor with per-prompt length tracking', 'load a consolidated LMTransformer model and tokenizer from a checkpoint directory with params.json config', 'run the lingua LLM training loop with a config file via train.py config=path/to/config.yaml', 'configure TrainArgs dataclass to set model, optimizer, data, and distributed training parameters', 'manage TrainState to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, and distributed parallelism settings', 'save and resume training checkpoints using CheckpointManager for model, optimizer, and train state', 'build a language model transformer using LMTransformer with LMTransformerArgs for vocab size and layers', 'create a causal attention mask for fmha, sdpa, or flex_attention implementations with optional sliding window', 'calculate the number of FLOPs per token given non-embed params, layers, dim, and sequence length', 'build an FSDP grouping plan tuple for model layers and output for fully sharded data parallel training', 'parallelize a transformer model across tensor parallel devices using ColwiseParallel and RowwiseParallel strategies']
```

Usage

```
{'run_lm_training': 'run the lingua LLM training loop with a config file via train.py config=path/to/config.yaml', 'configure_train_args': 'configure TrainArgs dataclass to set model, optimizer, data, and distributed training parameters', 'manage_train_state': 'manage TrainState to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate_train_args': 'validate TrainArgs to check vocab size, data paths, and distributed parallelism settings', 'checkpoint_and_resume': 'save and resume training checkpoints using CheckpointManager for model, optimizer, and train state'}
```

## File: facebookresearch_lingua/apps/main/transformer.py

Prompts

```
['run the LM Harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources and compute NLL metrics per token and per character', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval harness compatibility', 'run the eval.py CLI module with a config file and dot-list overrides for EvalArgs', 'consolidate checkpoints and load a consolidated LMTransformer model with its tokenizer for evaluation', 'run the generate.py CLI to load a consolidated LLM checkpoint and generate text from user prompts', 'sample tokens from model logits using top_p nucleus sampling with configurable temperature', 'sample tokens from model logits using top_k sampling to restrict to the k most probable tokens', 'pack multiple tokenized prompts into a single concatenated tensor with per-prompt length tracking', 'load a consolidated LMTransformer model and tokenizer from a checkpoint directory with params.json config', 'run the lingua LLM training loop with a config file via train.py config=path/to/config.yaml', 'configure TrainArgs dataclass to set model, optimizer, data, and distributed training parameters', 'manage TrainState to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, and distributed parallelism settings', 'save and resume training checkpoints using CheckpointManager for model, optimizer, and train state', 'build a language model transformer using LMTransformer with LMTransformerArgs for vocab size and layers', 'create a causal attention mask for fmha, sdpa, or flex_attention implementations with optional sliding window', 'calculate the number of FLOPs per token given non-embed params, layers, dim, and sequence length', 'build an FSDP grouping plan tuple for model layers and output for fully sharded data parallel training', 'parallelize a transformer model across tensor parallel devices using ColwiseParallel and RowwiseParallel strategies']
```

Usage

```
{'build_lm_transformer_model': 'build a language model transformer using LMTransformer with LMTransformerArgs for vocab size and layers', 'create_causal_mask': 'create a causal attention mask for fmha, sdpa, or flex_attention implementations with optional sliding window', 'calculate_flops_per_token': 'calculate the number of FLOPs per token given non-embed params, layers, dim, and sequence length', 'build_fsdp_grouping_plan': 'build an FSDP grouping plan tuple for model layers and output for fully sharded data parallel training', 'tp_parallelize_model': 'parallelize a transformer model across tensor parallel devices using ColwiseParallel and RowwiseParallel strategies'}
```

