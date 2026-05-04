# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/roberta/wsc/wsc_criterion.py

Prompts

```
['build a WSCCriterion to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'build a WinograndeCriterion subclass to compute Winogrande dataset loss using batched forward pass', 'test the get_lprobs method to compute log-probability scores from masked model logits', 'test the get_loss method to compute margin-based or cross-entropy loss between query and candidate scores', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using a JSONL data directory', 'load a WSC dataset split from a JSONL file with query tokens, candidate tokens, and masks', 'disambiguate a pronoun in a sentence by comparing masked language model log-probabilities of candidates', 'binarize text with a mask tensor marking the span of a target noun phrase for masked prediction', 'setup a WinograndeTask for two-candidate Winograd schema tasks with padded query and candidate token datasets', 'convert a sentence with underscore and bracket markers into a structured JSON object with span indices and text', 'iterate over a JSONL file of Winograd Schema Corpus samples yielding spaCy sentences with pronoun spans and queries', 'iterate over a Winogrande JSONL file yielding sentences with pronoun spans and candidate options', 'filter a list of spaCy noun chunks to exclude pronouns or a specific query text', 'find a text span within a spaCy sentence object starting from a given token index']
```

Usage

```
{'build_wsc_criterion': 'build a WSCCriterion to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'build_winogrande_criterion': 'build a WinograndeCriterion subclass to compute Winogrande dataset loss using batched forward pass', 'test_get_lprobs': 'test the get_lprobs method to compute log-probability scores from masked model logits', 'test_get_loss': 'test the get_loss method to compute margin-based or cross-entropy loss between query and candidate scores', 'review_aggregate_logging_outputs': 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training'}
```

## File: facebookresearch_avhubert/fairseq/examples/roberta/wsc/wsc_task.py

Prompts

```
['build a WSCCriterion to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'build a WinograndeCriterion subclass to compute Winogrande dataset loss using batched forward pass', 'test the get_lprobs method to compute log-probability scores from masked model logits', 'test the get_loss method to compute margin-based or cross-entropy loss between query and candidate scores', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using a JSONL data directory', 'load a WSC dataset split from a JSONL file with query tokens, candidate tokens, and masks', 'disambiguate a pronoun in a sentence by comparing masked language model log-probabilities of candidates', 'binarize text with a mask tensor marking the span of a target noun phrase for masked prediction', 'setup a WinograndeTask for two-candidate Winograd schema tasks with padded query and candidate token datasets', 'convert a sentence with underscore and bracket markers into a structured JSON object with span indices and text', 'iterate over a JSONL file of Winograd Schema Corpus samples yielding spaCy sentences with pronoun spans and queries', 'iterate over a Winogrande JSONL file yielding sentences with pronoun spans and candidate options', 'filter a list of spaCy noun chunks to exclude pronouns or a specific query text', 'find a text span within a spaCy sentence object starting from a given token index']
```

Usage

```
{'build_WSCTask_for_winograd': 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using a JSONL data directory', 'load_dataset_WSC_split': 'load a WSC dataset split from a JSONL file with query tokens, candidate tokens, and masks', 'disambiguate_pronoun_WSCTask': 'disambiguate a pronoun in a sentence by comparing masked language model log-probabilities of candidates', 'binarize_with_mask_WSCTask': 'binarize text with a mask tensor marking the span of a target noun phrase for masked prediction', 'setup_WinograndeTask': 'setup a WinograndeTask for two-candidate Winograd schema tasks with padded query and candidate token datasets'}
```

## File: facebookresearch_avhubert/fairseq/examples/roberta/wsc/wsc_utils.py

Prompts

```
['build a WSCCriterion to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'build a WinograndeCriterion subclass to compute Winogrande dataset loss using batched forward pass', 'test the get_lprobs method to compute log-probability scores from masked model logits', 'test the get_loss method to compute margin-based or cross-entropy loss between query and candidate scores', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using a JSONL data directory', 'load a WSC dataset split from a JSONL file with query tokens, candidate tokens, and masks', 'disambiguate a pronoun in a sentence by comparing masked language model log-probabilities of candidates', 'binarize text with a mask tensor marking the span of a target noun phrase for masked prediction', 'setup a WinograndeTask for two-candidate Winograd schema tasks with padded query and candidate token datasets', 'convert a sentence with underscore and bracket markers into a structured JSON object with span indices and text', 'iterate over a JSONL file of Winograd Schema Corpus samples yielding spaCy sentences with pronoun spans and queries', 'iterate over a Winogrande JSONL file yielding sentences with pronoun spans and candidate options', 'filter a list of spaCy noun chunks to exclude pronouns or a specific query text', 'find a text span within a spaCy sentence object starting from a given token index']
```

Usage

```
{'convert_sentence_to_json': 'convert a sentence with underscore and bracket markers into a structured JSON object with span indices and text', 'iterate_jsonl_wsc': 'iterate over a JSONL file of Winograd Schema Corpus samples yielding spaCy sentences with pronoun spans and queries', 'iterate_jsonl_winogrande': 'iterate over a Winogrande JSONL file yielding sentences with pronoun spans and candidate options', 'filter_noun_chunks': 'filter a list of spaCy noun chunks to exclude pronouns or a specific query text', 'find_span_in_sentence': 'find a text span within a spaCy sentence object starting from a given token index'}
```

