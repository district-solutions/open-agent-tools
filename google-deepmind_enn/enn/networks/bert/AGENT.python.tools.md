# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/networks/bert/base.py

Prompts

```
['create a BertConfig with custom vocab_size, hidden_size, and num_hidden_layers for a BERT model', 'build a small BERT configuration with 110M parameters using the bert_small factory function', 'build a large BERT configuration with 340M parameters using the bert_large factory function', 'create a BertInput NamedTuple with token_ids, segment_ids, and input_mask numpy arrays', 'review the BertConfigs enum to select BERT_SMALL or BERT_LARGE preset configurations', 'create a BERT ENN model with state using a BertConfig and training flag', 'build a BERT Haiku module with configurable vocab size, hidden size, and attention heads', 'run a forward pass of the BERT model on input token IDs to get pooled output and logits', 'review the BERT transformer layer implementation with multi-head attention, feed-forward network, and layer normalization', 'summarize the BERT embedding layer that combines word, token type, and position embeddings with layer norm', 'create an epinet ENN head for BERT classification with configurable hidden layers and prior scale', 'build an ensemble ENN head for BERT classification with multiple parallel MLP networks', 'create a dropout ENN head for BERT classification with configurable dropout rate', 'build a baseline classifier head ENN using CommonOutputLayer with PRNG-based indexing', 'create a BERT finetuning output layer with optional extra projection and dropout for classification', 'test the BERT ENN forward pass and verify output shape matches expected dimensions', 'run parameterized tests for BERT ENN across multiple output sizes and training modes', 'create a fake BERT dataset with random token IDs, segment IDs, and input masks', 'review the NetworkTest class and its parameterized test_forward_pass method for BERT ENN', 'summarize the BERT ENN test module that validates forward pass output shapes']
```

Usage

```
{'create_bert_config': 'create a BertConfig with custom vocab_size, hidden_size, and num_hidden_layers for a BERT model', 'build_bert_small': 'build a small BERT configuration with 110M parameters using the bert_small factory function', 'build_bert_large': 'build a large BERT configuration with 340M parameters using the bert_large factory function', 'create_bert_input': 'create a BertInput NamedTuple with token_ids, segment_ids, and input_mask numpy arrays', 'review_bertconfigs_enum': 'review the BertConfigs enum to select BERT_SMALL or BERT_LARGE preset configurations'}
```

## File: google-deepmind_enn/enn/networks/bert/bert.py

Prompts

```
['create a BertConfig with custom vocab_size, hidden_size, and num_hidden_layers for a BERT model', 'build a small BERT configuration with 110M parameters using the bert_small factory function', 'build a large BERT configuration with 340M parameters using the bert_large factory function', 'create a BertInput NamedTuple with token_ids, segment_ids, and input_mask numpy arrays', 'review the BertConfigs enum to select BERT_SMALL or BERT_LARGE preset configurations', 'create a BERT ENN model with state using a BertConfig and training flag', 'build a BERT Haiku module with configurable vocab size, hidden size, and attention heads', 'run a forward pass of the BERT model on input token IDs to get pooled output and logits', 'review the BERT transformer layer implementation with multi-head attention, feed-forward network, and layer normalization', 'summarize the BERT embedding layer that combines word, token type, and position embeddings with layer norm', 'create an epinet ENN head for BERT classification with configurable hidden layers and prior scale', 'build an ensemble ENN head for BERT classification with multiple parallel MLP networks', 'create a dropout ENN head for BERT classification with configurable dropout rate', 'build a baseline classifier head ENN using CommonOutputLayer with PRNG-based indexing', 'create a BERT finetuning output layer with optional extra projection and dropout for classification', 'test the BERT ENN forward pass and verify output shape matches expected dimensions', 'run parameterized tests for BERT ENN across multiple output sizes and training modes', 'create a fake BERT dataset with random token IDs, segment IDs, and input masks', 'review the NetworkTest class and its parameterized test_forward_pass method for BERT ENN', 'summarize the BERT ENN test module that validates forward pass output shapes']
```

Usage

```
{'make_bert_enn': 'create a BERT ENN model with state using a BertConfig and training flag', 'BERT_init': 'build a BERT Haiku module with configurable vocab size, hidden size, and attention heads', 'BERT_call': 'run a forward pass of the BERT model on input token IDs to get pooled output and logits', 'BERT_bert_layer': 'review the BERT transformer layer implementation with multi-head attention, feed-forward network, and layer normalization', 'BERT_embeddings': 'summarize the BERT embedding layer that combines word, token type, and position embeddings with layer norm'}
```

## File: google-deepmind_enn/enn/networks/bert/cls_heads.py

Prompts

```
['create a BertConfig with custom vocab_size, hidden_size, and num_hidden_layers for a BERT model', 'build a small BERT configuration with 110M parameters using the bert_small factory function', 'build a large BERT configuration with 340M parameters using the bert_large factory function', 'create a BertInput NamedTuple with token_ids, segment_ids, and input_mask numpy arrays', 'review the BertConfigs enum to select BERT_SMALL or BERT_LARGE preset configurations', 'create a BERT ENN model with state using a BertConfig and training flag', 'build a BERT Haiku module with configurable vocab size, hidden size, and attention heads', 'run a forward pass of the BERT model on input token IDs to get pooled output and logits', 'review the BERT transformer layer implementation with multi-head attention, feed-forward network, and layer normalization', 'summarize the BERT embedding layer that combines word, token type, and position embeddings with layer norm', 'create an epinet ENN head for BERT classification with configurable hidden layers and prior scale', 'build an ensemble ENN head for BERT classification with multiple parallel MLP networks', 'create a dropout ENN head for BERT classification with configurable dropout rate', 'build a baseline classifier head ENN using CommonOutputLayer with PRNG-based indexing', 'create a BERT finetuning output layer with optional extra projection and dropout for classification', 'test the BERT ENN forward pass and verify output shape matches expected dimensions', 'run parameterized tests for BERT ENN across multiple output sizes and training modes', 'create a fake BERT dataset with random token IDs, segment IDs, and input masks', 'review the NetworkTest class and its parameterized test_forward_pass method for BERT ENN', 'summarize the BERT ENN test module that validates forward pass output shapes']
```

Usage

```
{'make_head_enn_epinet': 'create an epinet ENN head for BERT classification with configurable hidden layers and prior scale', 'make_head_enn_ensemble': 'build an ensemble ENN head for BERT classification with multiple parallel MLP networks', 'make_head_enn_dropout': 'create a dropout ENN head for BERT classification with configurable dropout rate', 'make_baseline_head_enn': 'build a baseline classifier head ENN using CommonOutputLayer with PRNG-based indexing', 'CommonOutputLayer_call': 'create a BERT finetuning output layer with optional extra projection and dropout for classification'}
```

## File: google-deepmind_enn/enn/networks/bert/test.py

Prompts

```
['create a BertConfig with custom vocab_size, hidden_size, and num_hidden_layers for a BERT model', 'build a small BERT configuration with 110M parameters using the bert_small factory function', 'build a large BERT configuration with 340M parameters using the bert_large factory function', 'create a BertInput NamedTuple with token_ids, segment_ids, and input_mask numpy arrays', 'review the BertConfigs enum to select BERT_SMALL or BERT_LARGE preset configurations', 'create a BERT ENN model with state using a BertConfig and training flag', 'build a BERT Haiku module with configurable vocab size, hidden size, and attention heads', 'run a forward pass of the BERT model on input token IDs to get pooled output and logits', 'review the BERT transformer layer implementation with multi-head attention, feed-forward network, and layer normalization', 'summarize the BERT embedding layer that combines word, token type, and position embeddings with layer norm', 'create an epinet ENN head for BERT classification with configurable hidden layers and prior scale', 'build an ensemble ENN head for BERT classification with multiple parallel MLP networks', 'create a dropout ENN head for BERT classification with configurable dropout rate', 'build a baseline classifier head ENN using CommonOutputLayer with PRNG-based indexing', 'create a BERT finetuning output layer with optional extra projection and dropout for classification', 'test the BERT ENN forward pass and verify output shape matches expected dimensions', 'run parameterized tests for BERT ENN across multiple output sizes and training modes', 'create a fake BERT dataset with random token IDs, segment IDs, and input masks', 'review the NetworkTest class and its parameterized test_forward_pass method for BERT ENN', 'summarize the BERT ENN test module that validates forward pass output shapes']
```

Usage

```
{'test_bert_enn_forward_pass': 'test the BERT ENN forward pass and verify output shape matches expected dimensions', 'run_bert_enn_parameterized_tests': 'run parameterized tests for BERT ENN across multiple output sizes and training modes', 'create_fake_bert_dataset': 'create a fake BERT dataset with random token IDs, segment IDs, and input masks', 'review_networktest_class': 'review the NetworkTest class and its parameterized test_forward_pass method for BERT ENN', 'summarize_bert_enn_test': 'summarize the BERT ENN test module that validates forward pass output shapes'}
```

