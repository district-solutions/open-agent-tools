# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/yoso/test_modeling_yoso.py

Prompts

```
['test the YosoModel class with input_ids, token_type_ids, and attention_mask to verify hidden state output shape', 'test the YosoForMaskedLM class with labels to verify logits output shape matches vocab size', 'test the YosoForQuestionAnswering class with start_positions and end_positions to verify start and end logits shapes', 'test the YosoForSequenceClassification class with labels to verify logits output shape matches num_labels', 'test the YosoForTokenClassification class with token_labels to verify logits output shape matches sequence length and num_labels', 'test the YosoForMultipleChoice class with expanded inputs and choice_labels to verify logits output shape matches num_choices', 'test YosoModel and YosoForMaskedLM inference with pretrained uw-madison/yoso-4096 model and verify output shapes and values']
```

Usage

```
{'test_YosoModel': 'test the YosoModel class with input_ids, token_type_ids, and attention_mask to verify hidden state output shape', 'test_YosoForMaskedLM': 'test the YosoForMaskedLM class with labels to verify logits output shape matches vocab size', 'test_YosoForQuestionAnswering': 'test the YosoForQuestionAnswering class with start_positions and end_positions to verify start and end logits shapes', 'test_YosoForSequenceClassification': 'test the YosoForSequenceClassification class with labels to verify logits output shape matches num_labels', 'test_YosoForTokenClassification': 'test the YosoForTokenClassification class with token_labels to verify logits output shape matches sequence length and num_labels', 'test_YosoForMultipleChoice': 'test the YosoForMultipleChoice class with expanded inputs and choice_labels to verify logits output shape matches num_choices', 'test_YosoModelIntegrationTest': 'test YosoModel and YosoForMaskedLM inference with pretrained uw-madison/yoso-4096 model and verify output shapes and values'}
```

