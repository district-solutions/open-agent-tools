# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/megatron_gpt2/checkpoint_reshaping_and_interoperability.py

Prompts

```
['convert a Megatron-LM checkpoint to a HuggingFace Transformers GPT-2 checkpoint with sharding', 'convert a HuggingFace Transformers GPT-2 checkpoint to a Megatron-LM checkpoint with tensor and pipeline parallel splits', 'merge multiple sharded HuggingFace Transformers checkpoint files into a single state dict', 'load Megatron-LM sharded checkpoint state dicts for a given tensor and pipeline parallel rank', 'print the recursive structure and tensor shapes of a checkpoint state dict for inspection', 'convert a Megatron-LM GPT-2 checkpoint to HuggingFace transformers format', 'run the CLI to convert a Megatron-LM checkpoint from a .zip or .pt file to HuggingFace format', 'fix the query-key-value tensor ordering for Megatron-LM checkpoint version compatibility', 'summarize the convert_megatron_checkpoint function that transforms Megatron-LM state dicts to HuggingFace GPT-2 format']
```

Usage

```
{'convert_megatron_to_transformers_checkpoint': 'convert a Megatron-LM checkpoint to a HuggingFace Transformers GPT-2 checkpoint with sharding', 'convert_transformers_to_megatron_checkpoint': 'convert a HuggingFace Transformers GPT-2 checkpoint to a Megatron-LM checkpoint with tensor and pipeline parallel splits', 'merge_transformers_sharded_checkpoints': 'merge multiple sharded HuggingFace Transformers checkpoint files into a single state dict', 'get_megatron_sharded_states': 'load Megatron-LM sharded checkpoint state dicts for a given tensor and pipeline parallel rank', 'print_checkpoint_structure': 'print the recursive structure and tensor shapes of a checkpoint state dict for inspection'}
```

## File: huggingface_transformers/src/transformers/models/megatron_gpt2/convert_megatron_gpt2_checkpoint.py

Prompts

```
['convert a Megatron-LM checkpoint to a HuggingFace Transformers GPT-2 checkpoint with sharding', 'convert a HuggingFace Transformers GPT-2 checkpoint to a Megatron-LM checkpoint with tensor and pipeline parallel splits', 'merge multiple sharded HuggingFace Transformers checkpoint files into a single state dict', 'load Megatron-LM sharded checkpoint state dicts for a given tensor and pipeline parallel rank', 'print the recursive structure and tensor shapes of a checkpoint state dict for inspection', 'convert a Megatron-LM GPT-2 checkpoint to HuggingFace transformers format', 'run the CLI to convert a Megatron-LM checkpoint from a .zip or .pt file to HuggingFace format', 'fix the query-key-value tensor ordering for Megatron-LM checkpoint version compatibility', 'summarize the convert_megatron_checkpoint function that transforms Megatron-LM state dicts to HuggingFace GPT-2 format']
```

Usage

```
{'convert_megatron_checkpoint_to_huggingface': 'convert a Megatron-LM GPT-2 checkpoint to HuggingFace transformers format', 'run_megatron_checkpoint_conversion_cli': 'run the CLI to convert a Megatron-LM checkpoint from a .zip or .pt file to HuggingFace format', 'fix_query_key_value_ordering': 'fix the query-key-value tensor ordering for Megatron-LM checkpoint version compatibility', 'print_checkpoint_structure': 'print the recursive structure of a converted state dictionary with tensor shapes', 'summarize_convert_megatron_checkpoint': 'summarize the convert_megatron_checkpoint function that transforms Megatron-LM state dicts to HuggingFace GPT-2 format'}
```

