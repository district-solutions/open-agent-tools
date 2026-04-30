# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gpt_neox/configuration_gpt_neox.py

Prompts

```
['create a GPTNeoXConfig instance with default gpt-neox-20b style configuration parameters', 'validate the GPTNeoXConfig architecture ensures hidden size is divisible by attention heads', 'configure rotary position embedding parameters for GPTNeoXConfig from kwargs', 'initialize a GPTNeoXModel with a GPTNeoXConfig for random weight model creation', 'customize GPTNeoXConfig parameters like hidden_size, num_hidden_layers, and attention_heads', 'create a GPTNeoXForCausalLM model with config and generate text autoregressively', 'build a GPTNeoXForSequenceClassification model for text classification with custom label count', 'run a GPTNeoXForTokenClassification model for token-level NER or POS tagging tasks', 'test a GPTNeoXForQuestionAnswering model to extract start and end positions from context', 'review the GPTNeoXRotaryEmbedding class and apply_rotary_pos_emb function for positional encoding', 'build a GPTNeoX language model with causal LM head for next-token prediction and text generation', 'create a GPTNeoX transformer base model with embedding, attention layers, and rotary positional embeddings', 'test GPTNeoX sequence classification with pooled last-token logits and configurable label count', 'refactor GPTNeoX attention to support query-key-value projection, rotary embeddings, and cached KV inference', 'review GPTNeoX question answering head that splits sequence output into start and end logits']
```

Usage

```
{'create_gpt_neox_config': 'create a GPTNeoXConfig instance with default gpt-neox-20b style configuration parameters', 'validate_gpt_neox_architecture': 'validate the GPTNeoXConfig architecture ensures hidden size is divisible by attention heads', 'configure_gpt_neox_rope_params': 'configure rotary position embedding parameters for GPTNeoXConfig from kwargs', 'initialize_gpt_neox_model': 'initialize a GPTNeoXModel with a GPTNeoXConfig for random weight model creation', 'customize_gpt_neox_config': 'customize GPTNeoXConfig parameters like hidden_size, num_hidden_layers, and attention_heads'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neox/modeling_gpt_neox.py

Prompts

```
['create a GPTNeoXConfig instance with default gpt-neox-20b style configuration parameters', 'validate the GPTNeoXConfig architecture ensures hidden size is divisible by attention heads', 'configure rotary position embedding parameters for GPTNeoXConfig from kwargs', 'initialize a GPTNeoXModel with a GPTNeoXConfig for random weight model creation', 'customize GPTNeoXConfig parameters like hidden_size, num_hidden_layers, and attention_heads', 'create a GPTNeoXForCausalLM model with config and generate text autoregressively', 'build a GPTNeoXForSequenceClassification model for text classification with custom label count', 'run a GPTNeoXForTokenClassification model for token-level NER or POS tagging tasks', 'test a GPTNeoXForQuestionAnswering model to extract start and end positions from context', 'review the GPTNeoXRotaryEmbedding class and apply_rotary_pos_emb function for positional encoding', 'build a GPTNeoX language model with causal LM head for next-token prediction and text generation', 'create a GPTNeoX transformer base model with embedding, attention layers, and rotary positional embeddings', 'test GPTNeoX sequence classification with pooled last-token logits and configurable label count', 'refactor GPTNeoX attention to support query-key-value projection, rotary embeddings, and cached KV inference', 'review GPTNeoX question answering head that splits sequence output into start and end logits']
```

Usage

```
{'create_gpt_neox_causal_lm': 'create a GPTNeoXForCausalLM model with config and generate text autoregressively', 'build_gpt_neox_sequence_classifier': 'build a GPTNeoXForSequenceClassification model for text classification with custom label count', 'run_gpt_neox_token_classifier': 'run a GPTNeoXForTokenClassification model for token-level NER or POS tagging tasks', 'test_gpt_neox_question_answering': 'test a GPTNeoXForQuestionAnswering model to extract start and end positions from context', 'review_gpt_neox_rotary_embedding': 'review the GPTNeoXRotaryEmbedding class and apply_rotary_pos_emb function for positional encoding'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neox/modular_gpt_neox.py

Prompts

```
['create a GPTNeoXConfig instance with default gpt-neox-20b style configuration parameters', 'validate the GPTNeoXConfig architecture ensures hidden size is divisible by attention heads', 'configure rotary position embedding parameters for GPTNeoXConfig from kwargs', 'initialize a GPTNeoXModel with a GPTNeoXConfig for random weight model creation', 'customize GPTNeoXConfig parameters like hidden_size, num_hidden_layers, and attention_heads', 'create a GPTNeoXForCausalLM model with config and generate text autoregressively', 'build a GPTNeoXForSequenceClassification model for text classification with custom label count', 'run a GPTNeoXForTokenClassification model for token-level NER or POS tagging tasks', 'test a GPTNeoXForQuestionAnswering model to extract start and end positions from context', 'review the GPTNeoXRotaryEmbedding class and apply_rotary_pos_emb function for positional encoding', 'build a GPTNeoX language model with causal LM head for next-token prediction and text generation', 'create a GPTNeoX transformer base model with embedding, attention layers, and rotary positional embeddings', 'test GPTNeoX sequence classification with pooled last-token logits and configurable label count', 'refactor GPTNeoX attention to support query-key-value projection, rotary embeddings, and cached KV inference', 'review GPTNeoX question answering head that splits sequence output into start and end logits']
```

Usage

```
{'build_gpt_neox_causal_lm': 'build a GPTNeoX language model with causal LM head for next-token prediction and text generation', 'create_gpt_neox_model': 'create a GPTNeoX transformer base model with embedding, attention layers, and rotary positional embeddings', 'test_gpt_neox_sequence_classification': 'test GPTNeoX sequence classification with pooled last-token logits and configurable label count', 'refactor_gpt_neox_attention': 'refactor GPTNeoX attention to support query-key-value projection, rotary embeddings, and cached KV inference', 'review_gpt_neox_question_answering': 'review GPTNeoX question answering head that splits sequence output into start and end logits'}
```

