# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/distilbert/test_modeling_distilbert.py

Prompts

```
['test the DistilBertModel class and verify output shape matches expected batch, sequence, and hidden dimensions', 'test the DistilBertForMaskedLM class and verify logits shape matches batch, sequence length, and vocab size', 'test the DistilBertForSequenceClassification class and verify logits shape matches batch size and number of labels', 'test the DistilBertForQuestionAnswering class and verify start and end logits shapes match batch and sequence length', 'test the DistilBertForTokenClassification class and verify logits shape matches batch, sequence length, and label count', 'test the DistilBertForMultipleChoice class and verify logits shape matches batch size and number of choices', 'test DistilBertModel with sinusoidal positional embeddings and verify they match manually computed sinusoidal encodings', 'test FlashAttention-2 inference equivalence by comparing model outputs with and without flash attention implementation', 'test the DistilBertConfig class and verify common configuration attributes are correctly initialized']
```

Usage

```
{'test_distilbert_model': 'test the DistilBertModel class and verify output shape matches expected batch, sequence, and hidden dimensions', 'test_distilbert_for_masked_lm': 'test the DistilBertForMaskedLM class and verify logits shape matches batch, sequence length, and vocab size', 'test_distilbert_for_sequence_classification': 'test the DistilBertForSequenceClassification class and verify logits shape matches batch size and number of labels', 'test_distilbert_for_question_answering': 'test the DistilBertForQuestionAnswering class and verify start and end logits shapes match batch and sequence length', 'test_distilbert_for_token_classification': 'test the DistilBertForTokenClassification class and verify logits shape matches batch, sequence length, and label count', 'test_distilbert_for_multiple_choice': 'test the DistilBertForMultipleChoice class and verify logits shape matches batch size and number of choices', 'test_distilbert_model_with_sinusoidal_encodings': 'test DistilBertModel with sinusoidal positional embeddings and verify they match manually computed sinusoidal encodings', 'test_flash_attn_2_inference_equivalence': 'test FlashAttention-2 inference equivalence by comparing model outputs with and without flash attention implementation', 'test_config': 'test the DistilBertConfig class and verify common configuration attributes are correctly initialized'}
```

