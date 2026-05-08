# Agent Python Tools

- repo: facebookresearch/coconut
- repo_uri: https://github.com/facebookresearch/coconut

## File: facebookresearch_coconut/coconut.py

Prompts

```
['initialize a Coconut model wrapping a GPT2 or Llama3 causal language model with latent token IDs', 'run a multi-pass forward pass through Coconut that replaces latent tokens with preceding hidden states', 'generate text autoregressively using Coconut with latent token feedback and FSDP sync support', 'set the Coconut model and its wrapped base causal language model to training mode', 'set the Coconut model and its wrapped base causal language model to evaluation mode', 'load a JSON dataset and tokenize question, steps, and answer fields using a HuggingFace tokenizer', 'create a data collator that pads batches to align latent tokens for KV cache reuse', 'build a dataset of question-only samples with configurable latent token sequences for reasoning stages', 'create a chain-of-thought dataset with latent tokens and skip steps for scheduled stage training', 'tokenize a single sample into question, steps, and answer token lists with special tokens', 'create a Config object from a dictionary to access keys with dot notation', 'run set_seed to set random seeds for Python, NumPy, and PyTorch reproducibility', 'review the Config class that wraps a dictionary for dot-notation attribute access', 'test the set_seed function to verify deterministic behavior across random, numpy, and torch', 'summarize the Config class usage for converting dictionary access to object attribute access']
```

Usage

```
{'init_coconut_model': 'initialize a Coconut model wrapping a GPT2 or Llama3 causal language model with latent token IDs', 'forward_coconut': 'run a multi-pass forward pass through Coconut that replaces latent tokens with preceding hidden states', 'generate_coconut': 'generate text autoregressively using Coconut with latent token feedback and FSDP sync support', 'train_coconut': 'set the Coconut model and its wrapped base causal language model to training mode', 'eval_coconut': 'set the Coconut model and its wrapped base causal language model to evaluation mode'}
```

## File: facebookresearch_coconut/dataset.py

Prompts

```
['initialize a Coconut model wrapping a GPT2 or Llama3 causal language model with latent token IDs', 'run a multi-pass forward pass through Coconut that replaces latent tokens with preceding hidden states', 'generate text autoregressively using Coconut with latent token feedback and FSDP sync support', 'set the Coconut model and its wrapped base causal language model to training mode', 'set the Coconut model and its wrapped base causal language model to evaluation mode', 'load a JSON dataset and tokenize question, steps, and answer fields using a HuggingFace tokenizer', 'create a data collator that pads batches to align latent tokens for KV cache reuse', 'build a dataset of question-only samples with configurable latent token sequences for reasoning stages', 'create a chain-of-thought dataset with latent tokens and skip steps for scheduled stage training', 'tokenize a single sample into question, steps, and answer token lists with special tokens', 'create a Config object from a dictionary to access keys with dot notation', 'run set_seed to set random seeds for Python, NumPy, and PyTorch reproducibility', 'review the Config class that wraps a dictionary for dot-notation attribute access', 'test the set_seed function to verify deterministic behavior across random, numpy, and torch', 'summarize the Config class usage for converting dictionary access to object attribute access']
```

Usage

```
{'get_dataset': 'load a JSON dataset and tokenize question, steps, and answer fields using a HuggingFace tokenizer', 'MyCollator': 'create a data collator that pads batches to align latent tokens for KV cache reuse', 'get_question_latent_dataset': 'build a dataset of question-only samples with configurable latent token sequences for reasoning stages', 'get_cot_latent_dataset': 'create a chain-of-thought dataset with latent tokens and skip steps for scheduled stage training', 'tokenize_sample': 'tokenize a single sample into question, steps, and answer token lists with special tokens'}
```

## File: facebookresearch_coconut/utils.py

Prompts

```
['initialize a Coconut model wrapping a GPT2 or Llama3 causal language model with latent token IDs', 'run a multi-pass forward pass through Coconut that replaces latent tokens with preceding hidden states', 'generate text autoregressively using Coconut with latent token feedback and FSDP sync support', 'set the Coconut model and its wrapped base causal language model to training mode', 'set the Coconut model and its wrapped base causal language model to evaluation mode', 'load a JSON dataset and tokenize question, steps, and answer fields using a HuggingFace tokenizer', 'create a data collator that pads batches to align latent tokens for KV cache reuse', 'build a dataset of question-only samples with configurable latent token sequences for reasoning stages', 'create a chain-of-thought dataset with latent tokens and skip steps for scheduled stage training', 'tokenize a single sample into question, steps, and answer token lists with special tokens', 'create a Config object from a dictionary to access keys with dot notation', 'run set_seed to set random seeds for Python, NumPy, and PyTorch reproducibility', 'review the Config class that wraps a dictionary for dot-notation attribute access', 'test the set_seed function to verify deterministic behavior across random, numpy, and torch', 'summarize the Config class usage for converting dictionary access to object attribute access']
```

Usage

```
{'create_Config_wrapper': 'create a Config object from a dictionary to access keys with dot notation', 'run_set_seed': 'run set_seed to set random seeds for Python, NumPy, and PyTorch reproducibility', 'review_Config_class': 'review the Config class that wraps a dictionary for dot-notation attribute access', 'test_set_seed_function': 'test the set_seed function to verify deterministic behavior across random, numpy, and torch', 'summarize_Config_usage': 'summarize the Config class usage for converting dictionary access to object attribute access'}
```

