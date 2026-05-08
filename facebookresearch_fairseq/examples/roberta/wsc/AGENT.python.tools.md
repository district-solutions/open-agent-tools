# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/roberta/wsc/wsc_criterion.py

Prompts

```
['build a WSCCriterion class to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'create a WinograndeCriterion subclass that overrides forward to compute batched Winogrande loss and accuracy', 'test the get_lprobs method to compute log-probability scores for masked tokens through a model', 'refactor the get_loss method to switch between margin loss and cross-entropy loss formulations', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a Winograd Schema dataset by loading a JSONL split with query tokens, candidate tokens, and masks', 'build a WinoGrande dataset by loading a JSONL split with two-candidate Winograd schema samples', 'run pronoun disambiguation on a sentence using a RoBERTa model to resolve coreference', 'run binarization on text with prefix and suffix to produce token IDs and a boolean mask', 'review the WSCTask setup_task method to load a dictionary and initialize the Winograd Schema task', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence including both standard noun phrases and consecutive noun tokens', 'find a text span within a spaCy sentence by searching for matching text starting from a given token index', 'iterate over a WSC JSONL file yielding spaCy sentences with pronoun spans and query text for Winograd schema analysis', 'filter a list of spaCy noun chunks to exclude pronouns or chunks matching a specific query string']
```

Usage

```
{'build_wsc_criterion': 'build a WSCCriterion class to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'create_winogrande_criterion': 'create a WinograndeCriterion subclass that overrides forward to compute batched Winogrande loss and accuracy', 'test_get_lprobs': 'test the get_lprobs method to compute log-probability scores for masked tokens through a model', 'refactor_get_loss': 'refactor the get_loss method to switch between margin loss and cross-entropy loss formulations', 'review_aggregate_logging_outputs': 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training'}
```

## File: facebookresearch_fairseq/examples/roberta/wsc/wsc_task.py

Prompts

```
['build a WSCCriterion class to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'create a WinograndeCriterion subclass that overrides forward to compute batched Winogrande loss and accuracy', 'test the get_lprobs method to compute log-probability scores for masked tokens through a model', 'refactor the get_loss method to switch between margin loss and cross-entropy loss formulations', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a Winograd Schema dataset by loading a JSONL split with query tokens, candidate tokens, and masks', 'build a WinoGrande dataset by loading a JSONL split with two-candidate Winograd schema samples', 'run pronoun disambiguation on a sentence using a RoBERTa model to resolve coreference', 'run binarization on text with prefix and suffix to produce token IDs and a boolean mask', 'review the WSCTask setup_task method to load a dictionary and initialize the Winograd Schema task', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence including both standard noun phrases and consecutive noun tokens', 'find a text span within a spaCy sentence by searching for matching text starting from a given token index', 'iterate over a WSC JSONL file yielding spaCy sentences with pronoun spans and query text for Winograd schema analysis', 'filter a list of spaCy noun chunks to exclude pronouns or chunks matching a specific query string']
```

Usage

```
{'build_WSCTask_load_dataset': 'build a Winograd Schema dataset by loading a JSONL split with query tokens, candidate tokens, and masks', 'build_WinograndeTask_load_dataset': 'build a WinoGrande dataset by loading a JSONL split with two-candidate Winograd schema samples', 'run_WSCTask_disambiguate_pronoun': 'run pronoun disambiguation on a sentence using a RoBERTa model to resolve coreference', 'run_WSCTask_binarize_with_mask': 'run binarization on text with prefix and suffix to produce token IDs and a boolean mask', 'review_WSCTask_setup_task': 'review the WSCTask setup_task method to load a dictionary and initialize the Winograd Schema task'}
```

## File: facebookresearch_fairseq/examples/roberta/wsc/wsc_utils.py

Prompts

```
['build a WSCCriterion class to compute Winograd Schema Challenge loss with margin or cross-entropy formulation', 'create a WinograndeCriterion subclass that overrides forward to compute batched Winogrande loss and accuracy', 'test the get_lprobs method to compute log-probability scores for masked tokens through a model', 'refactor the get_loss method to switch between margin loss and cross-entropy loss formulations', 'review the aggregate_logging_outputs static method to aggregate loss and accuracy across data parallel training', 'build a Winograd Schema dataset by loading a JSONL split with query tokens, candidate tokens, and masks', 'build a WinoGrande dataset by loading a JSONL split with two-candidate Winograd schema samples', 'run pronoun disambiguation on a sentence using a RoBERTa model to resolve coreference', 'run binarization on text with prefix and suffix to produce token IDs and a boolean mask', 'review the WSCTask setup_task method to load a dictionary and initialize the Winograd Schema task', 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extract extended noun chunks from a spaCy sentence including both standard noun phrases and consecutive noun tokens', 'find a text span within a spaCy sentence by searching for matching text starting from a given token index', 'iterate over a WSC JSONL file yielding spaCy sentences with pronoun spans and query text for Winograd schema analysis', 'filter a list of spaCy noun chunks to exclude pronouns or chunks matching a specific query string']
```

Usage

```
{'convert_sentence_to_json': 'convert a WSC sentence with underscore and bracket markers into a structured JSON dictionary with span indices', 'extended_noun_chunks': 'extract extended noun chunks from a spaCy sentence including both standard noun phrases and consecutive noun tokens', 'find_span': 'find a text span within a spaCy sentence by searching for matching text starting from a given token index', 'jsonl_iterator': 'iterate over a WSC JSONL file yielding spaCy sentences with pronoun spans and query text for Winograd schema analysis', 'filter_noun_chunks': 'filter a list of spaCy noun chunks to exclude pronouns or chunks matching a specific query string'}
```

