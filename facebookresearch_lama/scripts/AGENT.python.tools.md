# Agent Python Tools

- repo: facebookresearch/lama
- repo_uri: https://github.com/facebookresearch/lama

## File: facebookresearch_lama/scripts/batch_eval_KB_completion.py

Prompts

```
['run batch evaluation of a language model on KB completion dataset with MRR and Precision metrics', 'filter KB completion samples by vocabulary subset, max sentence length, and object label validity', 'batchify KB completion samples into batches sorted by sentence length for efficient model inference', 'lowercase all KB completion samples while preserving MASK tokens for case-insensitive evaluation', 'initialize logging with file and console handlers for LAMA evaluation experiments', 'run the script to create LAMA-UHN by filtering easy-to-guess questions from a LAMA dataset directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to filter queries where the object is a top-k guess for the subject name', 'review the LAMAUHNFilter base class and its filter method that removes matching queries from a list', 'refactor the PersonNameFilter get_top_k_for_name method to use a different BERT model or template', 'run knowledge base completion experiments across relations using a specified language model and dataset', 'run KB completion experiments across all pre-configured language models for a given dataset', 'get T-REx dataset relations and file path parameters for KB completion experiments', 'get Google RE dataset relations with templates for KB completion experiments', 'get ConceptNet dataset parameters for running KB completion experiments']
```

Usage

```
{'run_batch_eval_KB_completion': 'run batch evaluation of a language model on KB completion dataset with MRR and Precision metrics', 'run_filter_samples': 'filter KB completion samples by vocabulary subset, max sentence length, and object label validity', 'run_batchify': 'batchify KB completion samples into batches sorted by sentence length for efficient model inference', 'run_lowercase_samples': 'lowercase all KB completion samples while preserving MASK tokens for case-insensitive evaluation', 'run_init_logging': 'initialize logging with file and console handlers for LAMA evaluation experiments'}
```

## File: facebookresearch_lama/scripts/create_lama_uhn.py

Prompts

```
['run batch evaluation of a language model on KB completion dataset with MRR and Precision metrics', 'filter KB completion samples by vocabulary subset, max sentence length, and object label validity', 'batchify KB completion samples into batches sorted by sentence length for efficient model inference', 'lowercase all KB completion samples while preserving MASK tokens for case-insensitive evaluation', 'initialize logging with file and console handlers for LAMA evaluation experiments', 'run the script to create LAMA-UHN by filtering easy-to-guess questions from a LAMA dataset directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to filter queries where the object is a top-k guess for the subject name', 'review the LAMAUHNFilter base class and its filter method that removes matching queries from a list', 'refactor the PersonNameFilter get_top_k_for_name method to use a different BERT model or template', 'run knowledge base completion experiments across relations using a specified language model and dataset', 'run KB completion experiments across all pre-configured language models for a given dataset', 'get T-REx dataset relations and file path parameters for KB completion experiments', 'get Google RE dataset relations with templates for KB completion experiments', 'get ConceptNet dataset parameters for running KB completion experiments']
```

Usage

```
{'create_lama_uhn_dataset': 'run the script to create LAMA-UHN by filtering easy-to-guess questions from a LAMA dataset directory', 'run_string_match_filter': 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run_person_name_filter': 'run the PersonNameFilter using BERT masked language modeling to filter queries where the object is a top-k guess for the subject name', 'review_LAMAUHNFilter_class': 'review the LAMAUHNFilter base class and its filter method that removes matching queries from a list', 'refactor_PersonNameFilter_get_top_k': 'refactor the PersonNameFilter get_top_k_for_name method to use a different BERT model or template'}
```

## File: facebookresearch_lama/scripts/run_experiments.py

Prompts

```
['run batch evaluation of a language model on KB completion dataset with MRR and Precision metrics', 'filter KB completion samples by vocabulary subset, max sentence length, and object label validity', 'batchify KB completion samples into batches sorted by sentence length for efficient model inference', 'lowercase all KB completion samples while preserving MASK tokens for case-insensitive evaluation', 'initialize logging with file and console handlers for LAMA evaluation experiments', 'run the script to create LAMA-UHN by filtering easy-to-guess questions from a LAMA dataset directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to filter queries where the object is a top-k guess for the subject name', 'review the LAMAUHNFilter base class and its filter method that removes matching queries from a list', 'refactor the PersonNameFilter get_top_k_for_name method to use a different BERT model or template', 'run knowledge base completion experiments across relations using a specified language model and dataset', 'run KB completion experiments across all pre-configured language models for a given dataset', 'get T-REx dataset relations and file path parameters for KB completion experiments', 'get Google RE dataset relations with templates for KB completion experiments', 'get ConceptNet dataset parameters for running KB completion experiments']
```

Usage

```
{'run_experiments_KB_completion': 'run knowledge base completion experiments across relations using a specified language model and dataset', 'run_all_LMs_evaluation': 'run KB completion experiments across all pre-configured language models for a given dataset', 'get_TREx_parameters': 'get T-REx dataset relations and file path parameters for KB completion experiments', 'get_GoogleRE_parameters': 'get Google RE dataset relations with templates for KB completion experiments', 'get_ConceptNet_parameters': 'get ConceptNet dataset parameters for running KB completion experiments'}
```

