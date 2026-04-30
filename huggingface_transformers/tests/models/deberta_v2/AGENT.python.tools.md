# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/deberta_v2/test_modeling_deberta_v2.py

Prompts

```
['test the DebertaV2Model forward pass with input_ids, attention_mask, and token_type_ids', 'test DebertaV2ForMaskedLM returns correct logits shape for masked language modeling', 'test DebertaV2ForSequenceClassification with labels and verify loss output', 'test DebertaV2ForTokenClassification returns correct logits shape per token', 'test DebertaV2ForQuestionAnswering returns start and end logits for span extraction', 'test DebertaV2Tokenizer with do_lower_case=True to verify lowercase tokenization of mixed-case input sequences', 'test DebertaV2Tokenizer with split_by_punct=True to verify punctuation is split into separate tokens', 'test DebertaV2Tokenizer with both do_lower_case=True and split_by_punct=True to verify combined preprocessing behavior', 'test DebertaV2Tokenizer post processor to verify [CLS] and [SEP] special tokens are added to single and pair inputs', 'test DebertaV2Tokenizer integration by encoding a multilingual sequence and verifying expected token IDs match reference values']
```

Usage

```
{'test_deberta_v2_model': 'test the DebertaV2Model forward pass with input_ids, attention_mask, and token_type_ids', 'test_deberta_v2_masked_lm': 'test DebertaV2ForMaskedLM returns correct logits shape for masked language modeling', 'test_deberta_v2_sequence_classification': 'test DebertaV2ForSequenceClassification with labels and verify loss output', 'test_deberta_v2_token_classification': 'test DebertaV2ForTokenClassification returns correct logits shape per token', 'test_deberta_v2_question_answering': 'test DebertaV2ForQuestionAnswering returns start and end logits for span extraction'}
```

## File: huggingface_transformers/tests/models/deberta_v2/test_tokenization_deberta_v2.py

Prompts

```
['test the DebertaV2Model forward pass with input_ids, attention_mask, and token_type_ids', 'test DebertaV2ForMaskedLM returns correct logits shape for masked language modeling', 'test DebertaV2ForSequenceClassification with labels and verify loss output', 'test DebertaV2ForTokenClassification returns correct logits shape per token', 'test DebertaV2ForQuestionAnswering returns start and end logits for span extraction', 'test DebertaV2Tokenizer with do_lower_case=True to verify lowercase tokenization of mixed-case input sequences', 'test DebertaV2Tokenizer with split_by_punct=True to verify punctuation is split into separate tokens', 'test DebertaV2Tokenizer with both do_lower_case=True and split_by_punct=True to verify combined preprocessing behavior', 'test DebertaV2Tokenizer post processor to verify [CLS] and [SEP] special tokens are added to single and pair inputs', 'test DebertaV2Tokenizer integration by encoding a multilingual sequence and verifying expected token IDs match reference values']
```

Usage

```
{'test_tokenization_deberta_v2_do_lower_case': 'test DebertaV2Tokenizer with do_lower_case=True to verify lowercase tokenization of mixed-case input sequences', 'test_tokenization_deberta_v2_split_by_punct': 'test DebertaV2Tokenizer with split_by_punct=True to verify punctuation is split into separate tokens', 'test_tokenization_deberta_v2_do_lower_case_split_by_punct': 'test DebertaV2Tokenizer with both do_lower_case=True and split_by_punct=True to verify combined preprocessing behavior', 'test_tokenization_deberta_v2_post_processor': 'test DebertaV2Tokenizer post processor to verify [CLS] and [SEP] special tokens are added to single and pair inputs', 'test_tokenization_deberta_v2_integration': 'test DebertaV2Tokenizer integration by encoding a multilingual sequence and verifying expected token IDs match reference values'}
```

