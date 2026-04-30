# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/modernbert/configuration_modernbert.py

Prompts

```
['create a ModernBertConfig with custom hidden_size, num_hidden_layers, vocab_size, and attention settings', 'build a ModernBertConfig and convert rope_scaling parameters to standardized rope_parameters dict', 'create a ModernBertConfig that auto-generates layer_types alternating sliding_attention and full_attention', 'test the ModernBertConfig to_dict method for serializing configuration to a dictionary', 'review the ModernBertConfig sliding_window property that derives window size from local_attention', 'create a ModernBertForMaskedLM model for masked language modeling with configurable vocab size', 'build a ModernBertForSequenceClassification model with cls or mean pooling for text classification', 'create a ModernBertForTokenClassification model for named entity recognition tasks', 'build a ModernBertForQuestionAnswering model that outputs start and end logits for span extraction', 'create a ModernBertForMultipleChoice model for multiple choice question answering tasks', 'build a ModernBertModel from a ModernBertConfig for base sequence encoding with embeddings and encoder layers']
```

Usage

```
{'create_modernbert_config': 'create a ModernBertConfig with custom hidden_size, num_hidden_layers, vocab_size, and attention settings', 'build_modernbert_config_with_rope': 'build a ModernBertConfig and convert rope_scaling parameters to standardized rope_parameters dict', 'create_modernbert_config_with_layer_types': 'create a ModernBertConfig that auto-generates layer_types alternating sliding_attention and full_attention', 'test_modernbert_config_to_dict': 'test the ModernBertConfig to_dict method for serializing configuration to a dictionary', 'review_modernbert_sliding_window': 'review the ModernBertConfig sliding_window property that derives window size from local_attention'}
```

## File: huggingface_transformers/src/transformers/models/modernbert/modeling_modernbert.py

Prompts

```
['create a ModernBertConfig with custom hidden_size, num_hidden_layers, vocab_size, and attention settings', 'build a ModernBertConfig and convert rope_scaling parameters to standardized rope_parameters dict', 'create a ModernBertConfig that auto-generates layer_types alternating sliding_attention and full_attention', 'test the ModernBertConfig to_dict method for serializing configuration to a dictionary', 'review the ModernBertConfig sliding_window property that derives window size from local_attention', 'create a ModernBertForMaskedLM model for masked language modeling with configurable vocab size', 'build a ModernBertForSequenceClassification model with cls or mean pooling for text classification', 'create a ModernBertForTokenClassification model for named entity recognition tasks', 'build a ModernBertForQuestionAnswering model that outputs start and end logits for span extraction', 'create a ModernBertForMultipleChoice model for multiple choice question answering tasks', 'build a ModernBertModel from a ModernBertConfig for base sequence encoding with embeddings and encoder layers']
```

Usage

```
{'create_masked_lm': 'create a ModernBertForMaskedLM model for masked language modeling with configurable vocab size', 'build_sequence_classifier': 'build a ModernBertForSequenceClassification model with cls or mean pooling for text classification', 'create_token_classifier': 'create a ModernBertForTokenClassification model for named entity recognition tasks', 'build_question_answerer': 'build a ModernBertForQuestionAnswering model that outputs start and end logits for span extraction', 'create_multiple_choice_model': 'create a ModernBertForMultipleChoice model for multiple choice question answering tasks'}
```

## File: huggingface_transformers/src/transformers/models/modernbert/modular_modernbert.py

Prompts

```
['create a ModernBertConfig with custom hidden_size, num_hidden_layers, vocab_size, and attention settings', 'build a ModernBertConfig and convert rope_scaling parameters to standardized rope_parameters dict', 'create a ModernBertConfig that auto-generates layer_types alternating sliding_attention and full_attention', 'test the ModernBertConfig to_dict method for serializing configuration to a dictionary', 'review the ModernBertConfig sliding_window property that derives window size from local_attention', 'create a ModernBertForMaskedLM model for masked language modeling with configurable vocab size', 'build a ModernBertForSequenceClassification model with cls or mean pooling for text classification', 'create a ModernBertForTokenClassification model for named entity recognition tasks', 'build a ModernBertForQuestionAnswering model that outputs start and end logits for span extraction', 'create a ModernBertForMultipleChoice model for multiple choice question answering tasks', 'build a ModernBertModel from a ModernBertConfig for base sequence encoding with embeddings and encoder layers']
```

Usage

```
{'create_modernbert_config': 'create a ModernBertConfig with custom hidden_size, num_hidden_layers, and local_attention settings', 'build_modernbert_model': 'build a ModernBertModel from a ModernBertConfig for base sequence encoding with embeddings and encoder layers', 'create_masked_lm': 'create a ModernBertForMaskedLM model for masked language modeling with sparse prediction support', 'build_sequence_classifier': 'build a ModernBertForSequenceClassification model with cls or mean pooling for text classification', 'create_token_classifier': 'create a ModernBertForTokenClassification model for named entity recognition with token-level predictions'}
```

