# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/blenderbot/convert_blenderbot_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a ParlAI Blenderbot checkpoint to a Hugging Face PyTorch model format', 'rename state dict keys from ParlAI naming conventions to Hugging Face Transformer naming conventions', 'rename layernorm_embedding keys to layer_norm for Blenderbot-3B checkpoints with normalize_before', 'run the CLI tool to convert a Blenderbot checkpoint from source path to Hugging Face save directory', 'load a BlenderbotConfig from JSON and instantiate BlenderbotForConditionalGeneration with it', 'build a BlenderbotForConditionalGeneration model for conversational dialogue with a language modeling head', 'create a BlenderbotForCausalLM decoder-only model for autoregressive text generation', 'test the BlenderbotModel encoder-decoder forward pass with input_ids and decoder_input_ids', 'refactor the BlenderbotAttention class to support flash attention and causal masking', 'review the BlenderbotDecoderLayer cross-attention block with past_key_values caching']
```

Usage

```
{'convert_parlai_checkpoint': 'convert a ParlAI Blenderbot checkpoint to a Hugging Face PyTorch model format', 'rename_state_dict_key': 'rename state dict keys from ParlAI naming conventions to Hugging Face Transformer naming conventions', 'rename_layernorm_keys': 'rename layernorm_embedding keys to layer_norm for Blenderbot-3B checkpoints with normalize_before', 'convert_blenderbot_checkpoint_cli': 'run the CLI tool to convert a Blenderbot checkpoint from source path to Hugging Face save directory', 'load_blenderbot_config_and_model': 'load a BlenderbotConfig from JSON and instantiate BlenderbotForConditionalGeneration with it'}
```

## File: huggingface_transformers/src/transformers/models/blenderbot/modeling_blenderbot.py

Prompts

```
['convert a ParlAI Blenderbot checkpoint to a Hugging Face PyTorch model format', 'rename state dict keys from ParlAI naming conventions to Hugging Face Transformer naming conventions', 'rename layernorm_embedding keys to layer_norm for Blenderbot-3B checkpoints with normalize_before', 'run the CLI tool to convert a Blenderbot checkpoint from source path to Hugging Face save directory', 'load a BlenderbotConfig from JSON and instantiate BlenderbotForConditionalGeneration with it', 'build a BlenderbotForConditionalGeneration model for conversational dialogue with a language modeling head', 'create a BlenderbotForCausalLM decoder-only model for autoregressive text generation', 'test the BlenderbotModel encoder-decoder forward pass with input_ids and decoder_input_ids', 'refactor the BlenderbotAttention class to support flash attention and causal masking', 'review the BlenderbotDecoderLayer cross-attention block with past_key_values caching']
```

Usage

```
{'build_blenderbot_conditional_generation': 'build a BlenderbotForConditionalGeneration model for conversational dialogue with a language modeling head', 'create_blenderbot_causal_lm': 'create a BlenderbotForCausalLM decoder-only model for autoregressive text generation', 'test_blenderbot_model_forward': 'test the BlenderbotModel encoder-decoder forward pass with input_ids and decoder_input_ids', 'refactor_blenderbot_attention': 'refactor the BlenderbotAttention class to support flash attention and causal masking', 'review_blenderbot_decoder_layer': 'review the BlenderbotDecoderLayer cross-attention block with past_key_values caching'}
```

