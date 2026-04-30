# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/arcee/configuration_arcee.py

Prompts

```
['create an ArceeConfig instance with default model architecture parameters for the Arcee AFM-4.5B model', 'build an ArceeConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'test the ArceeConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review the ArceeConfig __post_init__ method that computes head_dim and num_key_value_heads defaults', 'summarize the ArceeConfig configuration parameters including vocab_size, hidden_size, and attention settings', 'create an ArceeForCausalLM model for autoregressive text generation with RoPE embeddings', 'build an ArceeModel transformer with decoder layers, attention, and RMSNorm', 'test ArceeForSequenceClassification for mapping input sequences to class labels', 'review ArceeAttention multi-headed attention with GQA and rotary position embeddings', 'summarize ArceeDecoderLayer with self-attention, MLP, and residual connections']
```

Usage

```
{'create_arcee_config': 'create an ArceeConfig instance with default model architecture parameters for the Arcee AFM-4.5B model', 'build_arcee_config_custom': 'build an ArceeConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'test_arcee_validate_architecture': 'test the ArceeConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review_arcee_config_init': 'review the ArceeConfig __post_init__ method that computes head_dim and num_key_value_heads defaults', 'summarize_arcee_config_params': 'summarize the ArceeConfig configuration parameters including vocab_size, hidden_size, and attention settings'}
```

## File: huggingface_transformers/src/transformers/models/arcee/modeling_arcee.py

Prompts

```
['create an ArceeConfig instance with default model architecture parameters for the Arcee AFM-4.5B model', 'build an ArceeConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'test the ArceeConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review the ArceeConfig __post_init__ method that computes head_dim and num_key_value_heads defaults', 'summarize the ArceeConfig configuration parameters including vocab_size, hidden_size, and attention settings', 'create an ArceeForCausalLM model for autoregressive text generation with RoPE embeddings', 'build an ArceeModel transformer with decoder layers, attention, and RMSNorm', 'test ArceeForSequenceClassification for mapping input sequences to class labels', 'review ArceeAttention multi-headed attention with GQA and rotary position embeddings', 'summarize ArceeDecoderLayer with self-attention, MLP, and residual connections']
```

Usage

```
{'create_arcee_causal_lm': 'create an ArceeForCausalLM model for autoregressive text generation with RoPE embeddings', 'build_arcee_model': 'build an ArceeModel transformer with decoder layers, attention, and RMSNorm', 'test_arcee_sequence_classification': 'test ArceeForSequenceClassification for mapping input sequences to class labels', 'review_arcee_attention': 'review ArceeAttention multi-headed attention with GQA and rotary position embeddings', 'summarize_arcee_decoder_layer': 'summarize ArceeDecoderLayer with self-attention, MLP, and residual connections'}
```

