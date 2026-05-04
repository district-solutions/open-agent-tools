# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/roberta/wsc/wsc_criterion.py

Prompts

```
['build a WSCCriterion to compute margin or cross-entropy loss for Winograd Schema Challenge tasks', 'build a WinograndeCriterion subclass to compute batched loss for Winogrande dataset evaluation', 'run get_lprobs to compute log-probability scores from masked model logits for tokens', 'run get_loss to compute margin-based or cross-entropy loss between query and candidate log-probs', 'review aggregate_logging_outputs to aggregate loss and accuracy metrics across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using JSONL data', 'load a WSC dataset split from a JSONL file with query and candidate token masks', 'disambiguate a pronoun in a sentence using a RoBERTa model and WSC task', 'binarize text with a mask for masked language modeling on noun phrase candidates', 'setup a WinograndeTask for WinoGrande dataset with two-candidate Winograd schema evaluation', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence by combining standard noun chunks with consecutive noun tokens', 'find a text span within a spaCy sentence by matching the search text across token boundaries', 'iterate over a JSONL Winograd Schema Challenge file yielding spaCy sentences with pronoun spans and query text', 'filter a list of spaCy noun chunks by excluding pronouns or chunks matching a given query string']
```

Usage

```
{'build_wsc_criterion': 'build a WSCCriterion to compute margin or cross-entropy loss for Winograd Schema Challenge tasks', 'build_winogrande_criterion': 'build a WinograndeCriterion subclass to compute batched loss for Winogrande dataset evaluation', 'run_get_lprobs': 'run get_lprobs to compute log-probability scores from masked model logits for tokens', 'run_get_loss': 'run get_loss to compute margin-based or cross-entropy loss between query and candidate log-probs', 'review_aggregate_logging_outputs': 'review aggregate_logging_outputs to aggregate loss and accuracy metrics across data parallel training'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/roberta/wsc/wsc_task.py

Prompts

```
['build a WSCCriterion to compute margin or cross-entropy loss for Winograd Schema Challenge tasks', 'build a WinograndeCriterion subclass to compute batched loss for Winogrande dataset evaluation', 'run get_lprobs to compute log-probability scores from masked model logits for tokens', 'run get_loss to compute margin-based or cross-entropy loss between query and candidate log-probs', 'review aggregate_logging_outputs to aggregate loss and accuracy metrics across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using JSONL data', 'load a WSC dataset split from a JSONL file with query and candidate token masks', 'disambiguate a pronoun in a sentence using a RoBERTa model and WSC task', 'binarize text with a mask for masked language modeling on noun phrase candidates', 'setup a WinograndeTask for WinoGrande dataset with two-candidate Winograd schema evaluation', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence by combining standard noun chunks with consecutive noun tokens', 'find a text span within a spaCy sentence by matching the search text across token boundaries', 'iterate over a JSONL Winograd Schema Challenge file yielding spaCy sentences with pronoun spans and query text', 'filter a list of spaCy noun chunks by excluding pronouns or chunks matching a given query string']
```

Usage

```
{'build_WSCTask_for_winograd': 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using JSONL data', 'load_dataset_WSC_split': 'load a WSC dataset split from a JSONL file with query and candidate token masks', 'disambiguate_pronoun_WSC': 'disambiguate a pronoun in a sentence using a RoBERTa model and WSC task', 'binarize_with_mask_WSC': 'binarize text with a mask for masked language modeling on noun phrase candidates', 'setup_WinograndeTask': 'setup a WinograndeTask for WinoGrande dataset with two-candidate Winograd schema evaluation'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/roberta/wsc/wsc_utils.py

Prompts

```
['build a WSCCriterion to compute margin or cross-entropy loss for Winograd Schema Challenge tasks', 'build a WinograndeCriterion subclass to compute batched loss for Winogrande dataset evaluation', 'run get_lprobs to compute log-probability scores from masked model logits for tokens', 'run get_loss to compute margin-based or cross-entropy loss between query and candidate log-probs', 'review aggregate_logging_outputs to aggregate loss and accuracy metrics across data parallel training', 'build a WSCTask to finetune RoBERTa for Winograd Schema Challenge using JSONL data', 'load a WSC dataset split from a JSONL file with query and candidate token masks', 'disambiguate a pronoun in a sentence using a RoBERTa model and WSC task', 'binarize text with a mask for masked language modeling on noun phrase candidates', 'setup a WinograndeTask for WinoGrande dataset with two-candidate Winograd schema evaluation', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence by combining standard noun chunks with consecutive noun tokens', 'find a text span within a spaCy sentence by matching the search text across token boundaries', 'iterate over a JSONL Winograd Schema Challenge file yielding spaCy sentences with pronoun spans and query text', 'filter a list of spaCy noun chunks by excluding pronouns or chunks matching a given query string']
```

Usage

```
{'convert_sentence_to_json': 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extended_noun_chunks': 'extract extended noun chunks from a spaCy sentence by combining standard noun chunks with consecutive noun tokens', 'find_span': 'find a text span within a spaCy sentence by matching the search text across token boundaries', 'jsonl_iterator': 'iterate over a JSONL Winograd Schema Challenge file yielding spaCy sentences with pronoun spans and query text', 'filter_noun_chunks': 'filter a list of spaCy noun chunks by excluding pronouns or chunks matching a given query string'}
```

