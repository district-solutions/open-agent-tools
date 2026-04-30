# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/ministral/modeling_ministral.py

Prompts

```
['generate text from a MinistralForCausalLM model using tokenizer inputs and max_length', 'build a MinistralModel from a MinistralConfig with embedding tokens and decoder layers', 'run a MinistralForCausalLM forward pass with input_ids, attention_mask, and optional labels for loss', 'create a MinistralForSequenceClassification model for downstream sequence classification tasks', 'create a MinistralForTokenClassification model for downstream token classification tasks', 'create a MinistralForQuestionAnswering model for extractive question answering', 'apply rotary position embeddings to query and key tensors using cos and sin components', 'compute multi-headed attention in MinistralAttention with sliding window support', 'create a MinistralConfig with sliding window attention and custom layer types', 'create a MinistralForCausalLM model for autoregressive text generation', 'test the MinistralForSequenceClassification head for sequence-level prediction', 'run the MinistralForTokenClassification head for token-level labeling']
```

Usage

```
{'generate_ministral_text': 'generate text from a MinistralForCausalLM model using tokenizer inputs and max_length', 'build_ministral_model': 'build a MinistralModel from a MinistralConfig with embedding tokens and decoder layers', 'run_ministral_causal_lm': 'run a MinistralForCausalLM forward pass with input_ids, attention_mask, and optional labels for loss', 'create_sequence_classifier': 'create a MinistralForSequenceClassification model for downstream sequence classification tasks', 'create_token_classifier': 'create a MinistralForTokenClassification model for downstream token classification tasks', 'create_question_answerer': 'create a MinistralForQuestionAnswering model for extractive question answering', 'apply_rotary_position_embedding': 'apply rotary position embeddings to query and key tensors using cos and sin components', 'compute_ministral_attention': 'compute multi-headed attention in MinistralAttention with sliding window support'}
```

## File: huggingface_transformers/src/transformers/models/ministral/modular_ministral.py

Prompts

```
['generate text from a MinistralForCausalLM model using tokenizer inputs and max_length', 'build a MinistralModel from a MinistralConfig with embedding tokens and decoder layers', 'run a MinistralForCausalLM forward pass with input_ids, attention_mask, and optional labels for loss', 'create a MinistralForSequenceClassification model for downstream sequence classification tasks', 'create a MinistralForTokenClassification model for downstream token classification tasks', 'create a MinistralForQuestionAnswering model for extractive question answering', 'apply rotary position embeddings to query and key tensors using cos and sin components', 'compute multi-headed attention in MinistralAttention with sliding window support', 'create a MinistralConfig with sliding window attention and custom layer types', 'create a MinistralForCausalLM model for autoregressive text generation', 'test the MinistralForSequenceClassification head for sequence-level prediction', 'run the MinistralForTokenClassification head for token-level labeling']
```

Usage

```
{'create_ministral_config': 'create a MinistralConfig with sliding window attention and custom layer types', 'build_ministral_model': 'build a MinistralModel with mixed full and sliding attention decoder layers', 'create_ministral_causal_lm': 'create a MinistralForCausalLM model for autoregressive text generation', 'test_ministral_classification': 'test the MinistralForSequenceClassification head for sequence-level prediction', 'run_ministral_token_classification': 'run the MinistralForTokenClassification head for token-level labeling'}
```

