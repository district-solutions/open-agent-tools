# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/main/eval.py

Prompts

```
['run lm-eval harness evaluation on a consolidated LLM checkpoint with specified tasks', 'run validation evaluation on JSONL data sources and compute NLL metrics per source', 'run the eval CLI with a config file and optional dot-list overrides for EvalArgs', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval compatibility', 'consolidate distributed checkpoints and load the model and tokenizer for evaluation', 'run the generate script with a checkpoint path to generate text from user prompts interactively', 'load a consolidated model and tokenizer from a checkpoint directory using load_consolidated_model_and_tokenizer', 'sample tokens from model logits using temperature, top_p, or top_k sampling strategies', 'create a KVCache module with key-value cache buffers and optional Canon layer state for autoregressive generation', 'use PackedCausalTransformerGenerator to generate text with configurable max length, temperature, and top_p sampling', 'run the LLM training loop via train.py with a YAML config file and optional CLI overrides', 'build a TrainArgs dataclass to configure model, optimizer, data, distributed, checkpoint, and logging settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize an LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a language model transformer with configurable vocab size, attention implementation, and z-loss support', 'create a causal attention mask for fmha, sdpa, or flex_attention with optional sliding window', 'compute the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings, transformer layers, and output modules', 'parallelize a transformer model across tensor parallel workers for attention and feedforward layers']
```

Usage

```
{'run_lm_harness_eval': 'run lm-eval harness evaluation on a consolidated LLM checkpoint with specified tasks', 'run_validation_eval': 'run validation evaluation on JSONL data sources and compute NLL metrics per source', 'run_eval_cli': 'run the eval CLI with a config file and optional dot-list overrides for EvalArgs', 'create_eval_harness_lm': 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval compatibility', 'consolidate_and_load_checkpoint': 'consolidate distributed checkpoints and load the model and tokenizer for evaluation'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/main/generate.py

Prompts

```
['run lm-eval harness evaluation on a consolidated LLM checkpoint with specified tasks', 'run validation evaluation on JSONL data sources and compute NLL metrics per source', 'run the eval CLI with a config file and optional dot-list overrides for EvalArgs', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval compatibility', 'consolidate distributed checkpoints and load the model and tokenizer for evaluation', 'run the generate script with a checkpoint path to generate text from user prompts interactively', 'load a consolidated model and tokenizer from a checkpoint directory using load_consolidated_model_and_tokenizer', 'sample tokens from model logits using temperature, top_p, or top_k sampling strategies', 'create a KVCache module with key-value cache buffers and optional Canon layer state for autoregressive generation', 'use PackedCausalTransformerGenerator to generate text with configurable max length, temperature, and top_p sampling', 'run the LLM training loop via train.py with a YAML config file and optional CLI overrides', 'build a TrainArgs dataclass to configure model, optimizer, data, distributed, checkpoint, and logging settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize an LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a language model transformer with configurable vocab size, attention implementation, and z-loss support', 'create a causal attention mask for fmha, sdpa, or flex_attention with optional sliding window', 'compute the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings, transformer layers, and output modules', 'parallelize a transformer model across tensor parallel workers for attention and feedforward layers']
```

Usage

```
{'run_text_generation': 'run the generate script with a checkpoint path to generate text from user prompts interactively', 'load_consolidated_model': 'load a consolidated model and tokenizer from a checkpoint directory using load_consolidated_model_and_tokenizer', 'sample_tokens_with_temperature': 'sample tokens from model logits using temperature, top_p, or top_k sampling strategies', 'create_kv_cache': 'create a KVCache module with key-value cache buffers and optional Canon layer state for autoregressive generation', 'generate_with_packed_transformer': 'use PackedCausalTransformerGenerator to generate text with configurable max length, temperature, and top_p sampling'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/main/train.py

Prompts

```
['run lm-eval harness evaluation on a consolidated LLM checkpoint with specified tasks', 'run validation evaluation on JSONL data sources and compute NLL metrics per source', 'run the eval CLI with a config file and optional dot-list overrides for EvalArgs', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval compatibility', 'consolidate distributed checkpoints and load the model and tokenizer for evaluation', 'run the generate script with a checkpoint path to generate text from user prompts interactively', 'load a consolidated model and tokenizer from a checkpoint directory using load_consolidated_model_and_tokenizer', 'sample tokens from model logits using temperature, top_p, or top_k sampling strategies', 'create a KVCache module with key-value cache buffers and optional Canon layer state for autoregressive generation', 'use PackedCausalTransformerGenerator to generate text with configurable max length, temperature, and top_p sampling', 'run the LLM training loop via train.py with a YAML config file and optional CLI overrides', 'build a TrainArgs dataclass to configure model, optimizer, data, distributed, checkpoint, and logging settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize an LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a language model transformer with configurable vocab size, attention implementation, and z-loss support', 'create a causal attention mask for fmha, sdpa, or flex_attention with optional sliding window', 'compute the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings, transformer layers, and output modules', 'parallelize a transformer model across tensor parallel workers for attention and feedforward layers']
```

Usage

```
{'run_train_lm': 'run the LLM training loop via train.py with a YAML config file and optional CLI overrides', 'build_train_args': 'build a TrainArgs dataclass to configure model, optimizer, data, distributed, checkpoint, and logging settings', 'create_train_state': 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate_train_args': 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize_model': 'parallelize an LMTransformer model using FSDP and tensor parallelism across a device mesh'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/main/transformer.py

Prompts

```
['run lm-eval harness evaluation on a consolidated LLM checkpoint with specified tasks', 'run validation evaluation on JSONL data sources and compute NLL metrics per source', 'run the eval CLI with a config file and optional dot-list overrides for EvalArgs', 'create an EvalHarnessLM wrapper around a PackedCausalTransformerGenerator for lm-eval compatibility', 'consolidate distributed checkpoints and load the model and tokenizer for evaluation', 'run the generate script with a checkpoint path to generate text from user prompts interactively', 'load a consolidated model and tokenizer from a checkpoint directory using load_consolidated_model_and_tokenizer', 'sample tokens from model logits using temperature, top_p, or top_k sampling strategies', 'create a KVCache module with key-value cache buffers and optional Canon layer state for autoregressive generation', 'use PackedCausalTransformerGenerator to generate text with configurable max length, temperature, and top_p sampling', 'run the LLM training loop via train.py with a YAML config file and optional CLI overrides', 'build a TrainArgs dataclass to configure model, optimizer, data, distributed, checkpoint, and logging settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize an LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a language model transformer with configurable vocab size, attention implementation, and z-loss support', 'create a causal attention mask for fmha, sdpa, or flex_attention with optional sliding window', 'compute the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings, transformer layers, and output modules', 'parallelize a transformer model across tensor parallel workers for attention and feedforward layers']
```

Usage

```
{'create_LMTransformer': 'create a language model transformer with configurable vocab size, attention implementation, and z-loss support', 'create_causal_mask': 'create a causal attention mask for fmha, sdpa, or flex_attention with optional sliding window', 'get_num_flop_per_token': 'compute the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build_fsdp_grouping_plan': 'build an FSDP grouping plan for token embeddings, transformer layers, and output modules', 'tp_parallelize': 'parallelize a transformer model across tensor parallel workers for attention and feedforward layers'}
```

