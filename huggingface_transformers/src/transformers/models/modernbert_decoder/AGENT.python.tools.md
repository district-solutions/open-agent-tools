# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/modernbert_decoder/configuration_modernbert_decoder.py

Prompts

```
['create a ModernBertDecoderConfig instance with default or custom transformer hyperparameters', 'build layer_types list assigning full_attention and sliding_attention based on num_hidden_layers', 'convert rope_scaling kwargs into standardized rope_parameters dict with full and sliding attention', 'initialize default rope theta values for global and local attention from default_theta', 'access ModernBertDecoderConfig metadata including model_type, keys_to_ignore_at_inference, and vocab_size', 'create a ModernBertDecoderForCausalLM model for causal language modeling with a language modeling head', 'build a ModernBertDecoderForSequenceClassification model for sequence classification using the last token', 'test loading a pretrained ModernBertDecoderModel from a checkpoint and running inference', 'run text generation with ModernBertDecoderForCausalLM using tokenizer inputs and max length', 'review the ModernBertDecoderAttention class that supports causal multi-headed self attention with sliding window', 'create a ModernBertDecoderConfig with custom hidden size, number of layers, and attention heads', 'build a ModernBertDecoderForCausalLM model for autoregressive text generation with a language modeling head', 'run sequence classification on input text using ModernBertDecoderForSequenceClassification with a linear classifier head', 'test the ModernBertDecoderAttention module with sliding window and full attention patterns', 'review the ModernBertDecoderModel forward pass with position embeddings and causal masking']
```

Usage

```
{'create_ModernBertDecoderConfig': 'create a ModernBertDecoderConfig instance with default or custom transformer hyperparameters', 'build_layer_types_from_config': 'build layer_types list assigning full_attention and sliding_attention based on num_hidden_layers', 'convert_rope_params_to_dict': 'convert rope_scaling kwargs into standardized rope_parameters dict with full and sliding attention', 'initialize_rope_theta_values': 'initialize default rope theta values for global and local attention from default_theta', 'access_config_metadata': 'access ModernBertDecoderConfig metadata including model_type, keys_to_ignore_at_inference, and vocab_size'}
```

## File: huggingface_transformers/src/transformers/models/modernbert_decoder/modeling_modernbert_decoder.py

Prompts

```
['create a ModernBertDecoderConfig instance with default or custom transformer hyperparameters', 'build layer_types list assigning full_attention and sliding_attention based on num_hidden_layers', 'convert rope_scaling kwargs into standardized rope_parameters dict with full and sliding attention', 'initialize default rope theta values for global and local attention from default_theta', 'access ModernBertDecoderConfig metadata including model_type, keys_to_ignore_at_inference, and vocab_size', 'create a ModernBertDecoderForCausalLM model for causal language modeling with a language modeling head', 'build a ModernBertDecoderForSequenceClassification model for sequence classification using the last token', 'test loading a pretrained ModernBertDecoderModel from a checkpoint and running inference', 'run text generation with ModernBertDecoderForCausalLM using tokenizer inputs and max length', 'review the ModernBertDecoderAttention class that supports causal multi-headed self attention with sliding window', 'create a ModernBertDecoderConfig with custom hidden size, number of layers, and attention heads', 'build a ModernBertDecoderForCausalLM model for autoregressive text generation with a language modeling head', 'run sequence classification on input text using ModernBertDecoderForSequenceClassification with a linear classifier head', 'test the ModernBertDecoderAttention module with sliding window and full attention patterns', 'review the ModernBertDecoderModel forward pass with position embeddings and causal masking']
```

Usage

```
{'create_causal_lm_model': 'create a ModernBertDecoderForCausalLM model for causal language modeling with a language modeling head', 'build_sequence_classifier': 'build a ModernBertDecoderForSequenceClassification model for sequence classification using the last token', 'test_pretrained_model': 'test loading a pretrained ModernBertDecoderModel from a checkpoint and running inference', 'run_language_generation': 'run text generation with ModernBertDecoderForCausalLM using tokenizer inputs and max length', 'review_attention_mechanism': 'review the ModernBertDecoderAttention class that supports causal multi-headed self attention with sliding window'}
```

## File: huggingface_transformers/src/transformers/models/modernbert_decoder/modular_modernbert_decoder.py

Prompts

```
['create a ModernBertDecoderConfig instance with default or custom transformer hyperparameters', 'build layer_types list assigning full_attention and sliding_attention based on num_hidden_layers', 'convert rope_scaling kwargs into standardized rope_parameters dict with full and sliding attention', 'initialize default rope theta values for global and local attention from default_theta', 'access ModernBertDecoderConfig metadata including model_type, keys_to_ignore_at_inference, and vocab_size', 'create a ModernBertDecoderForCausalLM model for causal language modeling with a language modeling head', 'build a ModernBertDecoderForSequenceClassification model for sequence classification using the last token', 'test loading a pretrained ModernBertDecoderModel from a checkpoint and running inference', 'run text generation with ModernBertDecoderForCausalLM using tokenizer inputs and max length', 'review the ModernBertDecoderAttention class that supports causal multi-headed self attention with sliding window', 'create a ModernBertDecoderConfig with custom hidden size, number of layers, and attention heads', 'build a ModernBertDecoderForCausalLM model for autoregressive text generation with a language modeling head', 'run sequence classification on input text using ModernBertDecoderForSequenceClassification with a linear classifier head', 'test the ModernBertDecoderAttention module with sliding window and full attention patterns', 'review the ModernBertDecoderModel forward pass with position embeddings and causal masking']
```

Usage

```
{'create_modernbert_decoder_config': 'create a ModernBertDecoderConfig with custom hidden size, number of layers, and attention heads', 'build_causal_lm_model': 'build a ModernBertDecoderForCausalLM model for autoregressive text generation with a language modeling head', 'run_sequence_classification': 'run sequence classification on input text using ModernBertDecoderForSequenceClassification with a linear classifier head', 'test_attention_mechanism': 'test the ModernBertDecoderAttention module with sliding window and full attention patterns', 'review_decoder_forward_pass': 'review the ModernBertDecoderModel forward pass with position embeddings and causal masking'}
```

