# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/gla/eval.py

Prompts

```
['run the LM harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources to compute NLL metrics per token and per character', 'create an HFLikeModelAdapter wrapping a transformer model for HuggingFace lm_eval compatibility', 'consolidate distributed checkpoints and load the model with tokenizer for evaluation', 'run eval.py with a config file and optional CLI overrides via OmegaConf dot notation', 'run the generator to produce text from prompts using a consolidated LLM checkpoint', 'run sample_tokens to sample next tokens from logits with temperature and top_p or top_k', 'run sample_top_p to perform nucleus sampling on a probability tensor with threshold p', 'run pack_prompts to concatenate a list of tokenized prompts into a single packed tensor with lengths', 'run load_consolidated_model_and_tokenizer to load an LMTransformer model and HuggingFace tokenizer from a checkpoint directory', 'run the LM training loop with a YAML config file via python train.py config=path/to/config.yaml', 'run training with CLI overrides like python train.py config=cfg.yaml model.dim=512 steps=5000', 'run async evaluation on a Slurm cluster by setting async_eval_gpus=8 in the training config', 'review the TrainArgs dataclass to understand all configurable training hyperparameters and nested args', 'review the TrainState class to understand how training state is saved and restored via state_dict', 'build an LMTransformer model from LMTransformerArgs for GLA, GDN, or Mamba2 architectures', 'run a forward pass on the LMTransformer with token values and optional targets', 'initialize the LMTransformer weights by resetting HuggingFace module initialization flags', 'build an FSDP grouping plan tuple for GLA, GDN, Mamba2, or Llama models', 'parallelize a model across tensor parallel workers using ColwiseParallel and RowwiseParallel layouts']
```

Usage

```
{'run_lm_harness_eval': 'run the LM harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run_validation_eval': 'run validation evaluation on JSONL sources to compute NLL metrics per token and per character', 'create_hf_model_adapter': 'create an HFLikeModelAdapter wrapping a transformer model for HuggingFace lm_eval compatibility', 'consolidate_and_load_model': 'consolidate distributed checkpoints and load the model with tokenizer for evaluation', 'run_eval_from_cli': 'run eval.py with a config file and optional CLI overrides via OmegaConf dot notation'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/gla/generate.py

Prompts

```
['run the LM harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources to compute NLL metrics per token and per character', 'create an HFLikeModelAdapter wrapping a transformer model for HuggingFace lm_eval compatibility', 'consolidate distributed checkpoints and load the model with tokenizer for evaluation', 'run eval.py with a config file and optional CLI overrides via OmegaConf dot notation', 'run the generator to produce text from prompts using a consolidated LLM checkpoint', 'run sample_tokens to sample next tokens from logits with temperature and top_p or top_k', 'run sample_top_p to perform nucleus sampling on a probability tensor with threshold p', 'run pack_prompts to concatenate a list of tokenized prompts into a single packed tensor with lengths', 'run load_consolidated_model_and_tokenizer to load an LMTransformer model and HuggingFace tokenizer from a checkpoint directory', 'run the LM training loop with a YAML config file via python train.py config=path/to/config.yaml', 'run training with CLI overrides like python train.py config=cfg.yaml model.dim=512 steps=5000', 'run async evaluation on a Slurm cluster by setting async_eval_gpus=8 in the training config', 'review the TrainArgs dataclass to understand all configurable training hyperparameters and nested args', 'review the TrainState class to understand how training state is saved and restored via state_dict', 'build an LMTransformer model from LMTransformerArgs for GLA, GDN, or Mamba2 architectures', 'run a forward pass on the LMTransformer with token values and optional targets', 'initialize the LMTransformer weights by resetting HuggingFace module initialization flags', 'build an FSDP grouping plan tuple for GLA, GDN, Mamba2, or Llama models', 'parallelize a model across tensor parallel workers using ColwiseParallel and RowwiseParallel layouts']
```

Usage

```
{'run_generate_text': 'run the generator to produce text from prompts using a consolidated LLM checkpoint', 'run_sample_tokens': 'run sample_tokens to sample next tokens from logits with temperature and top_p or top_k', 'run_sample_top_p': 'run sample_top_p to perform nucleus sampling on a probability tensor with threshold p', 'run_pack_prompts': 'run pack_prompts to concatenate a list of tokenized prompts into a single packed tensor with lengths', 'run_load_consolidated_model': 'run load_consolidated_model_and_tokenizer to load an LMTransformer model and HuggingFace tokenizer from a checkpoint directory'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/gla/train.py

Prompts

```
['run the LM harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources to compute NLL metrics per token and per character', 'create an HFLikeModelAdapter wrapping a transformer model for HuggingFace lm_eval compatibility', 'consolidate distributed checkpoints and load the model with tokenizer for evaluation', 'run eval.py with a config file and optional CLI overrides via OmegaConf dot notation', 'run the generator to produce text from prompts using a consolidated LLM checkpoint', 'run sample_tokens to sample next tokens from logits with temperature and top_p or top_k', 'run sample_top_p to perform nucleus sampling on a probability tensor with threshold p', 'run pack_prompts to concatenate a list of tokenized prompts into a single packed tensor with lengths', 'run load_consolidated_model_and_tokenizer to load an LMTransformer model and HuggingFace tokenizer from a checkpoint directory', 'run the LM training loop with a YAML config file via python train.py config=path/to/config.yaml', 'run training with CLI overrides like python train.py config=cfg.yaml model.dim=512 steps=5000', 'run async evaluation on a Slurm cluster by setting async_eval_gpus=8 in the training config', 'review the TrainArgs dataclass to understand all configurable training hyperparameters and nested args', 'review the TrainState class to understand how training state is saved and restored via state_dict', 'build an LMTransformer model from LMTransformerArgs for GLA, GDN, or Mamba2 architectures', 'run a forward pass on the LMTransformer with token values and optional targets', 'initialize the LMTransformer weights by resetting HuggingFace module initialization flags', 'build an FSDP grouping plan tuple for GLA, GDN, Mamba2, or Llama models', 'parallelize a model across tensor parallel workers using ColwiseParallel and RowwiseParallel layouts']
```

Usage

```
{'run_train_lm': 'run the LM training loop with a YAML config file via python train.py config=path/to/config.yaml', 'run_train_with_cli_overrides': 'run training with CLI overrides like python train.py config=cfg.yaml model.dim=512 steps=5000', 'run_async_eval_on_slurm': 'run async evaluation on a Slurm cluster by setting async_eval_gpus=8 in the training config', 'review_TrainArgs': 'review the TrainArgs dataclass to understand all configurable training hyperparameters and nested args', 'review_TrainState': 'review the TrainState class to understand how training state is saved and restored via state_dict'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/gla/transformer.py

Prompts

```
['run the LM harness evaluation on a consolidated model checkpoint using simple_evaluate', 'run validation evaluation on JSONL sources to compute NLL metrics per token and per character', 'create an HFLikeModelAdapter wrapping a transformer model for HuggingFace lm_eval compatibility', 'consolidate distributed checkpoints and load the model with tokenizer for evaluation', 'run eval.py with a config file and optional CLI overrides via OmegaConf dot notation', 'run the generator to produce text from prompts using a consolidated LLM checkpoint', 'run sample_tokens to sample next tokens from logits with temperature and top_p or top_k', 'run sample_top_p to perform nucleus sampling on a probability tensor with threshold p', 'run pack_prompts to concatenate a list of tokenized prompts into a single packed tensor with lengths', 'run load_consolidated_model_and_tokenizer to load an LMTransformer model and HuggingFace tokenizer from a checkpoint directory', 'run the LM training loop with a YAML config file via python train.py config=path/to/config.yaml', 'run training with CLI overrides like python train.py config=cfg.yaml model.dim=512 steps=5000', 'run async evaluation on a Slurm cluster by setting async_eval_gpus=8 in the training config', 'review the TrainArgs dataclass to understand all configurable training hyperparameters and nested args', 'review the TrainState class to understand how training state is saved and restored via state_dict', 'build an LMTransformer model from LMTransformerArgs for GLA, GDN, or Mamba2 architectures', 'run a forward pass on the LMTransformer with token values and optional targets', 'initialize the LMTransformer weights by resetting HuggingFace module initialization flags', 'build an FSDP grouping plan tuple for GLA, GDN, Mamba2, or Llama models', 'parallelize a model across tensor parallel workers using ColwiseParallel and RowwiseParallel layouts']
```

Usage

```
{'build_LMTransformer': 'build an LMTransformer model from LMTransformerArgs for GLA, GDN, or Mamba2 architectures', 'forward_LMTransformer': 'run a forward pass on the LMTransformer with token values and optional targets', 'init_weights_LMTransformer': 'initialize the LMTransformer weights by resetting HuggingFace module initialization flags', 'build_fsdp_grouping_plan': 'build an FSDP grouping plan tuple for GLA, GDN, Mamba2, or Llama models', 'tp_parallelize': 'parallelize a model across tensor parallel workers using ColwiseParallel and RowwiseParallel layouts'}
```

