# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/markuplm/test_feature_extraction_markuplm.py

Prompts

```
['test the MarkupLMFeatureExtractor call method to encode HTML strings into nodes and xpaths', 'test the MarkupLMFeatureExtractor with batched HTML string input and verify output structure', 'test the MarkupLMFeatureExtractor save and load functionality via FeatureExtractionSavingTestMixin', 'test the MarkupLMFeatureExtractionTester prepare_feat_extract_dict method', 'test the get_html_strings helper function returns two HTML string samples', 'test the MarkupLMModel forward pass with input_ids, attention_mask, and token_type_ids', 'test MarkupLMForSequenceClassification with xpath_tags_seq, xpath_subs_seq, and labels', 'test MarkupLMForTokenClassification with xpath_tags_seq, xpath_subs_seq, and token labels', 'test MarkupLMForQuestionAnswering with start_positions and end_positions', 'run MarkupLMModel integration test with microsoft/markuplm-base model and verify last_hidden_state shape', 'test the MarkupLMProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the MarkupLMProcessor save and load pretrained with additional tokenizer and feature extractor kwargs', 'test the MarkupLMProcessor for web page classification and token classification with HTML string inputs', 'test the MarkupLMProcessor with parse_html=False using nodes and xpaths inputs for token classification', 'test the MarkupLMProcessor for token classification training with node_labels and batched inputs', 'test the MarkupLMTokenizer and MarkupLMTokenizerFast classes for correct tokenization behavior', 'create a MarkupLMTokenizer with vocab, merges, and tags_dict for document layout understanding', 'encode HTML nodes with corresponding XPath sequences using MarkupLMTokenizer', 'test left and right padding with max_length and truncation strategies on MarkupLMTokenizer', 'test node_labels parameter for token classification with only_label_first_subword option']
```

Usage

```
{'test_feature_extraction_call': 'test the MarkupLMFeatureExtractor call method to encode HTML strings into nodes and xpaths', 'test_feature_extraction_batched': 'test the MarkupLMFeatureExtractor with batched HTML string input and verify output structure', 'test_feature_extraction_saving': 'test the MarkupLMFeatureExtractor save and load functionality via FeatureExtractionSavingTestMixin', 'test_markuplm_extraction_tester': 'test the MarkupLMFeatureExtractionTester prepare_feat_extract_dict method', 'test_get_html_strings': 'test the get_html_strings helper function returns two HTML string samples'}
```

## File: huggingface_transformers/tests/models/markuplm/test_modeling_markuplm.py

Prompts

```
['test the MarkupLMFeatureExtractor call method to encode HTML strings into nodes and xpaths', 'test the MarkupLMFeatureExtractor with batched HTML string input and verify output structure', 'test the MarkupLMFeatureExtractor save and load functionality via FeatureExtractionSavingTestMixin', 'test the MarkupLMFeatureExtractionTester prepare_feat_extract_dict method', 'test the get_html_strings helper function returns two HTML string samples', 'test the MarkupLMModel forward pass with input_ids, attention_mask, and token_type_ids', 'test MarkupLMForSequenceClassification with xpath_tags_seq, xpath_subs_seq, and labels', 'test MarkupLMForTokenClassification with xpath_tags_seq, xpath_subs_seq, and token labels', 'test MarkupLMForQuestionAnswering with start_positions and end_positions', 'run MarkupLMModel integration test with microsoft/markuplm-base model and verify last_hidden_state shape', 'test the MarkupLMProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the MarkupLMProcessor save and load pretrained with additional tokenizer and feature extractor kwargs', 'test the MarkupLMProcessor for web page classification and token classification with HTML string inputs', 'test the MarkupLMProcessor with parse_html=False using nodes and xpaths inputs for token classification', 'test the MarkupLMProcessor for token classification training with node_labels and batched inputs', 'test the MarkupLMTokenizer and MarkupLMTokenizerFast classes for correct tokenization behavior', 'create a MarkupLMTokenizer with vocab, merges, and tags_dict for document layout understanding', 'encode HTML nodes with corresponding XPath sequences using MarkupLMTokenizer', 'test left and right padding with max_length and truncation strategies on MarkupLMTokenizer', 'test node_labels parameter for token classification with only_label_first_subword option']
```

Usage

```
{'test_MarkupLMModel': 'test the MarkupLMModel forward pass with input_ids, attention_mask, and token_type_ids', 'test_MarkupLMForSequenceClassification': 'test MarkupLMForSequenceClassification with xpath_tags_seq, xpath_subs_seq, and labels', 'test_MarkupLMForTokenClassification': 'test MarkupLMForTokenClassification with xpath_tags_seq, xpath_subs_seq, and token labels', 'test_MarkupLMForQuestionAnswering': 'test MarkupLMForQuestionAnswering with start_positions and end_positions', 'run_MarkupLMModelIntegrationTest': 'run MarkupLMModel integration test with microsoft/markuplm-base model and verify last_hidden_state shape'}
```

## File: huggingface_transformers/tests/models/markuplm/test_processing_markuplm.py

Prompts

```
['test the MarkupLMFeatureExtractor call method to encode HTML strings into nodes and xpaths', 'test the MarkupLMFeatureExtractor with batched HTML string input and verify output structure', 'test the MarkupLMFeatureExtractor save and load functionality via FeatureExtractionSavingTestMixin', 'test the MarkupLMFeatureExtractionTester prepare_feat_extract_dict method', 'test the get_html_strings helper function returns two HTML string samples', 'test the MarkupLMModel forward pass with input_ids, attention_mask, and token_type_ids', 'test MarkupLMForSequenceClassification with xpath_tags_seq, xpath_subs_seq, and labels', 'test MarkupLMForTokenClassification with xpath_tags_seq, xpath_subs_seq, and token labels', 'test MarkupLMForQuestionAnswering with start_positions and end_positions', 'run MarkupLMModel integration test with microsoft/markuplm-base model and verify last_hidden_state shape', 'test the MarkupLMProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the MarkupLMProcessor save and load pretrained with additional tokenizer and feature extractor kwargs', 'test the MarkupLMProcessor for web page classification and token classification with HTML string inputs', 'test the MarkupLMProcessor with parse_html=False using nodes and xpaths inputs for token classification', 'test the MarkupLMProcessor for token classification training with node_labels and batched inputs', 'test the MarkupLMTokenizer and MarkupLMTokenizerFast classes for correct tokenization behavior', 'create a MarkupLMTokenizer with vocab, merges, and tags_dict for document layout understanding', 'encode HTML nodes with corresponding XPath sequences using MarkupLMTokenizer', 'test left and right padding with max_length and truncation strategies on MarkupLMTokenizer', 'test node_labels parameter for token classification with only_label_first_subword option']
```

Usage

```
{'test_save_load_pretrained_default': 'test the MarkupLMProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test_save_load_pretrained_additional_features': 'test the MarkupLMProcessor save and load pretrained with additional tokenizer and feature extractor kwargs', 'test_processor_case_1': 'test the MarkupLMProcessor for web page classification and token classification with HTML string inputs', 'test_processor_case_2': 'test the MarkupLMProcessor with parse_html=False using nodes and xpaths inputs for token classification', 'test_processor_case_3': 'test the MarkupLMProcessor for token classification training with node_labels and batched inputs'}
```

## File: huggingface_transformers/tests/models/markuplm/test_tokenization_markuplm.py

Prompts

```
['test the MarkupLMFeatureExtractor call method to encode HTML strings into nodes and xpaths', 'test the MarkupLMFeatureExtractor with batched HTML string input and verify output structure', 'test the MarkupLMFeatureExtractor save and load functionality via FeatureExtractionSavingTestMixin', 'test the MarkupLMFeatureExtractionTester prepare_feat_extract_dict method', 'test the get_html_strings helper function returns two HTML string samples', 'test the MarkupLMModel forward pass with input_ids, attention_mask, and token_type_ids', 'test MarkupLMForSequenceClassification with xpath_tags_seq, xpath_subs_seq, and labels', 'test MarkupLMForTokenClassification with xpath_tags_seq, xpath_subs_seq, and token labels', 'test MarkupLMForQuestionAnswering with start_positions and end_positions', 'run MarkupLMModel integration test with microsoft/markuplm-base model and verify last_hidden_state shape', 'test the MarkupLMProcessor save and load pretrained methods with default tokenizer and feature extractor', 'test the MarkupLMProcessor save and load pretrained with additional tokenizer and feature extractor kwargs', 'test the MarkupLMProcessor for web page classification and token classification with HTML string inputs', 'test the MarkupLMProcessor with parse_html=False using nodes and xpaths inputs for token classification', 'test the MarkupLMProcessor for token classification training with node_labels and batched inputs', 'test the MarkupLMTokenizer and MarkupLMTokenizerFast classes for correct tokenization behavior', 'create a MarkupLMTokenizer with vocab, merges, and tags_dict for document layout understanding', 'encode HTML nodes with corresponding XPath sequences using MarkupLMTokenizer', 'test left and right padding with max_length and truncation strategies on MarkupLMTokenizer', 'test node_labels parameter for token classification with only_label_first_subword option']
```

Usage

```
{'test_markuplm_tokenization': 'test the MarkupLMTokenizer and MarkupLMTokenizerFast classes for correct tokenization behavior', 'create_tokenizer_markuplm': 'create a MarkupLMTokenizer with vocab, merges, and tags_dict for document layout understanding', 'encode_nodes_xpaths': 'encode HTML nodes with corresponding XPath sequences using MarkupLMTokenizer', 'test_padding_truncation': 'test left and right padding with max_length and truncation strategies on MarkupLMTokenizer', 'test_node_labels': 'test node_labels parameter for token classification with only_label_first_subword option'}
```

