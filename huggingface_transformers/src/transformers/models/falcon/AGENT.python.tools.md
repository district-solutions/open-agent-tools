# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/falcon/configuration_falcon.py

Prompts

```
['create a FalconConfig instance with custom num_hidden_layers and hidden_size parameters', 'initialize a FalconModel from a FalconConfig with 2 hidden layers', 'access the model configuration from an instantiated FalconModel instance', 'get the head dimension by dividing hidden_size by num_attention_heads', 'check if rotary embeddings are enabled based on the alibi setting', 'create a FalconForCausalLM model with FalconConfig for autoregressive text generation', 'build a FalconForSequenceClassification model to classify text sequences into labels', 'build a FalconForTokenClassification model for token-level tagging tasks like NER', 'build a FalconForQuestionAnswering model to extract start and end positions from context', 'build a FalconModel transformer with causal masking and rotary position embeddings']
```

Usage

```
{'create_falcon_config': 'create a FalconConfig instance with custom num_hidden_layers and hidden_size parameters', 'initialize_falcon_model': 'initialize a FalconModel from a FalconConfig with 2 hidden layers', 'access_model_config': 'access the model configuration from an instantiated FalconModel instance', 'get_head_dim': 'get the head dimension by dividing hidden_size by num_attention_heads', 'check_rotary_mode': 'check if rotary embeddings are enabled based on the alibi setting'}
```

## File: huggingface_transformers/src/transformers/models/falcon/modeling_falcon.py

Prompts

```
['create a FalconConfig instance with custom num_hidden_layers and hidden_size parameters', 'initialize a FalconModel from a FalconConfig with 2 hidden layers', 'access the model configuration from an instantiated FalconModel instance', 'get the head dimension by dividing hidden_size by num_attention_heads', 'check if rotary embeddings are enabled based on the alibi setting', 'create a FalconForCausalLM model with FalconConfig for autoregressive text generation', 'build a FalconForSequenceClassification model to classify text sequences into labels', 'build a FalconForTokenClassification model for token-level tagging tasks like NER', 'build a FalconForQuestionAnswering model to extract start and end positions from context', 'build a FalconModel transformer with causal masking and rotary position embeddings']
```

Usage

```
{'create_falcon_causal_lm': 'create a FalconForCausalLM model with FalconConfig for autoregressive text generation', 'build_falcon_sequence_classifier': 'build a FalconForSequenceClassification model to classify text sequences into labels', 'build_falcon_token_classifier': 'build a FalconForTokenClassification model for token-level tagging tasks like NER', 'build_falcon_question_answering': 'build a FalconForQuestionAnswering model to extract start and end positions from context', 'build_falcon_decoder_model': 'build a FalconModel transformer with causal masking and rotary position embeddings'}
```

