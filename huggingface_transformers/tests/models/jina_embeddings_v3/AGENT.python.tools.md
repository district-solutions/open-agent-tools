# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/jina_embeddings_v3/test_modeling_jina_embeddings_v3.py

Prompts

```
['test the JinaEmbeddingsV3Model class to verify last_hidden_state and pooler_output shapes for forward passes with and without attention masks', 'test the JinaEmbeddingsV3ForMaskedLM class to verify logits shape matches (batch_size, seq_length, vocab_size) during masked language modeling', 'test the JinaEmbeddingsV3ForQuestionAnswering class to verify start_logits and end_logits shapes for question answering tasks', 'test the JinaEmbeddingsV3ForSequenceClassification class to verify logits shape matches (batch_size, num_labels) for sequence classification', 'test the JinaEmbeddingsV3ForTokenClassification class to verify logits shape matches (batch_size, seq_length, num_labels) for token classification']
```

Usage

```
{'test_model_inference': 'test the JinaEmbeddingsV3Model class to verify last_hidden_state and pooler_output shapes for forward passes with and without attention masks', 'test_masked_lm_head': 'test the JinaEmbeddingsV3ForMaskedLM class to verify logits shape matches (batch_size, seq_length, vocab_size) during masked language modeling', 'test_question_answering_head': 'test the JinaEmbeddingsV3ForQuestionAnswering class to verify start_logits and end_logits shapes for question answering tasks', 'test_sequence_classification_head': 'test the JinaEmbeddingsV3ForSequenceClassification class to verify logits shape matches (batch_size, num_labels) for sequence classification', 'test_token_classification_head': 'test the JinaEmbeddingsV3ForTokenClassification class to verify logits shape matches (batch_size, seq_length, num_labels) for token classification'}
```

