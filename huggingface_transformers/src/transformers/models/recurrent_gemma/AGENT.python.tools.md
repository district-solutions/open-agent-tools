# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/recurrent_gemma/configuration_recurrent_gemma.py

Prompts

```
['create a RecurrentGemmaConfig instance with default recurrentgemma-2b style configuration', 'create a RecurrentGemmaConfig with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a RecurrentGemmaModel from a RecurrentGemmaConfig instance', 'get the layers_block_type property that repeats block_types to cover num_hidden_layers', 'validate the RecurrentGemmaConfig architecture to ensure num_key_value_heads is smaller than num_attention_heads', 'convert a RecurrentGemma checkpoint file to HuggingFace Transformers format using write_model', 'convert a Gemma tokenizer model file to HuggingFace format using write_tokenizer', 'run the CLI script to convert RecurrentGemma weights and tokenizer to HuggingFace format', 'select a RecurrentGemmaConfig from CONFIG_MAPPING by model size key 2B or 7B', 'map checkpoint layer names to HuggingFace RecurrentGemma layer names using LAYER_NAME_MAPPING', 'create a RecurrentGemmaModel with a RecurrentGemmaConfig for causal language modeling', 'build a RecurrentGemmaForCausalLM and generate text with max_length using tokenizer inputs', 'test the RecurrentGemmaModel forward pass with input_ids, position_ids, and attention_mask', 'review the RecurrentGemmaRglru class and its _rnn_scan method for linear RNN recurrence', 'summarize the RecurrentGemmaDecoderLayer temporal block and MLP residual block architecture']
```

Usage

```
{'create_config_default': 'create a RecurrentGemmaConfig instance with default recurrentgemma-2b style configuration', 'create_config_custom': 'create a RecurrentGemmaConfig with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build_model_from_config': 'build a RecurrentGemmaModel from a RecurrentGemmaConfig instance', 'get_layers_block_type': 'get the layers_block_type property that repeats block_types to cover num_hidden_layers', 'validate_architecture': 'validate the RecurrentGemmaConfig architecture to ensure num_key_value_heads is smaller than num_attention_heads'}
```

## File: huggingface_transformers/src/transformers/models/recurrent_gemma/convert_recurrent_gemma_to_hf.py

Prompts

```
['create a RecurrentGemmaConfig instance with default recurrentgemma-2b style configuration', 'create a RecurrentGemmaConfig with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a RecurrentGemmaModel from a RecurrentGemmaConfig instance', 'get the layers_block_type property that repeats block_types to cover num_hidden_layers', 'validate the RecurrentGemmaConfig architecture to ensure num_key_value_heads is smaller than num_attention_heads', 'convert a RecurrentGemma checkpoint file to HuggingFace Transformers format using write_model', 'convert a Gemma tokenizer model file to HuggingFace format using write_tokenizer', 'run the CLI script to convert RecurrentGemma weights and tokenizer to HuggingFace format', 'select a RecurrentGemmaConfig from CONFIG_MAPPING by model size key 2B or 7B', 'map checkpoint layer names to HuggingFace RecurrentGemma layer names using LAYER_NAME_MAPPING', 'create a RecurrentGemmaModel with a RecurrentGemmaConfig for causal language modeling', 'build a RecurrentGemmaForCausalLM and generate text with max_length using tokenizer inputs', 'test the RecurrentGemmaModel forward pass with input_ids, position_ids, and attention_mask', 'review the RecurrentGemmaRglru class and its _rnn_scan method for linear RNN recurrence', 'summarize the RecurrentGemmaDecoderLayer temporal block and MLP residual block architecture']
```

Usage

```
{'convert_recurrent_gemma_checkpoint': 'convert a RecurrentGemma checkpoint file to HuggingFace Transformers format using write_model', 'convert_gemma_tokenizer': 'convert a Gemma tokenizer model file to HuggingFace format using write_tokenizer', 'run_cli_conversion': 'run the CLI script to convert RecurrentGemma weights and tokenizer to HuggingFace format', 'select_model_config': 'select a RecurrentGemmaConfig from CONFIG_MAPPING by model size key 2B or 7B', 'map_layer_names': 'map checkpoint layer names to HuggingFace RecurrentGemma layer names using LAYER_NAME_MAPPING'}
```

## File: huggingface_transformers/src/transformers/models/recurrent_gemma/modeling_recurrent_gemma.py

Prompts

```
['create a RecurrentGemmaConfig instance with default recurrentgemma-2b style configuration', 'create a RecurrentGemmaConfig with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a RecurrentGemmaModel from a RecurrentGemmaConfig instance', 'get the layers_block_type property that repeats block_types to cover num_hidden_layers', 'validate the RecurrentGemmaConfig architecture to ensure num_key_value_heads is smaller than num_attention_heads', 'convert a RecurrentGemma checkpoint file to HuggingFace Transformers format using write_model', 'convert a Gemma tokenizer model file to HuggingFace format using write_tokenizer', 'run the CLI script to convert RecurrentGemma weights and tokenizer to HuggingFace format', 'select a RecurrentGemmaConfig from CONFIG_MAPPING by model size key 2B or 7B', 'map checkpoint layer names to HuggingFace RecurrentGemma layer names using LAYER_NAME_MAPPING', 'create a RecurrentGemmaModel with a RecurrentGemmaConfig for causal language modeling', 'build a RecurrentGemmaForCausalLM and generate text with max_length using tokenizer inputs', 'test the RecurrentGemmaModel forward pass with input_ids, position_ids, and attention_mask', 'review the RecurrentGemmaRglru class and its _rnn_scan method for linear RNN recurrence', 'summarize the RecurrentGemmaDecoderLayer temporal block and MLP residual block architecture']
```

Usage

```
{'create_recurrent_gemma_model': 'create a RecurrentGemmaModel with a RecurrentGemmaConfig for causal language modeling', 'build_causal_lm_generate': 'build a RecurrentGemmaForCausalLM and generate text with max_length using tokenizer inputs', 'test_recurrent_gemma_forward': 'test the RecurrentGemmaModel forward pass with input_ids, position_ids, and attention_mask', 'review_recurrent_gemma_rglru': 'review the RecurrentGemmaRglru class and its _rnn_scan method for linear RNN recurrence', 'summarize_recurrent_gemma_decoder_layer': 'summarize the RecurrentGemmaDecoderLayer temporal block and MLP residual block architecture'}
```

