# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/src/llama_cookbook/datasets/custom_dataset.py

Prompts

```
['load a Python module from a .py file that is not in the Python path', 'dynamically load and call a custom dataset function from a .py file using a config and tokenizer', 'dynamically load and call a custom data collator function from a .py file using a config', 'review the load_module_from_py_file function to understand how it uses importlib to load arbitrary Python files', 'refactor get_custom_dataset to support additional file formats beyond .py files', 'load the samsum dataset from Hugging Face for a given split like train or test', 'get a preprocessed and tokenized samsum dataset ready for dialogue summarization model training', 'apply a summarization prompt template to samsum dialogue samples for instruction tuning', 'tokenize samsum dialogue and summary pairs with input ids, attention masks, and labels', 'review the samsum dataset loading function that handles trust_remote_code errors from Hugging Face', 'run the toxicchat dataset loader via fire CLI to print sample training data', 'run the toxicchat dataset loader in JSONL mode to export prompt and label pairs', 'create a Llama Guard formatted dataset from the lmsys toxic-chat HuggingFace dataset', 'map toxic chat moderation categories to Llama Guard category codes using the mapping table', 'tokenize a full prompt string into input IDs, labels, and attention mask for training']
```

Usage

```
{'load_module_from_py_file': 'load a Python module from a .py file that is not in the Python path', 'get_custom_dataset': 'dynamically load and call a custom dataset function from a .py file using a config and tokenizer', 'get_data_collator': 'dynamically load and call a custom data collator function from a .py file using a config', 'review_load_module_from_py_file': 'review the load_module_from_py_file function to understand how it uses importlib to load arbitrary Python files', 'refactor_get_custom_dataset': 'refactor get_custom_dataset to support additional file formats beyond .py files'}
```

## File: facebookresearch_llama-recipes/src/llama_cookbook/datasets/samsum_dataset.py

Prompts

```
['load a Python module from a .py file that is not in the Python path', 'dynamically load and call a custom dataset function from a .py file using a config and tokenizer', 'dynamically load and call a custom data collator function from a .py file using a config', 'review the load_module_from_py_file function to understand how it uses importlib to load arbitrary Python files', 'refactor get_custom_dataset to support additional file formats beyond .py files', 'load the samsum dataset from Hugging Face for a given split like train or test', 'get a preprocessed and tokenized samsum dataset ready for dialogue summarization model training', 'apply a summarization prompt template to samsum dialogue samples for instruction tuning', 'tokenize samsum dialogue and summary pairs with input ids, attention masks, and labels', 'review the samsum dataset loading function that handles trust_remote_code errors from Hugging Face', 'run the toxicchat dataset loader via fire CLI to print sample training data', 'run the toxicchat dataset loader in JSONL mode to export prompt and label pairs', 'create a Llama Guard formatted dataset from the lmsys toxic-chat HuggingFace dataset', 'map toxic chat moderation categories to Llama Guard category codes using the mapping table', 'tokenize a full prompt string into input IDs, labels, and attention mask for training']
```

Usage

```
{'load_samsum_dataset': 'load the samsum dataset from Hugging Face for a given split like train or test', 'get_preprocessed_samsum_dataset': 'get a preprocessed and tokenized samsum dataset ready for dialogue summarization model training', 'apply_prompt_template_samsum': 'apply a summarization prompt template to samsum dialogue samples for instruction tuning', 'tokenize_samsum_samples': 'tokenize samsum dialogue and summary pairs with input ids, attention masks, and labels', 'review_samsum_dataset_loading': 'review the samsum dataset loading function that handles trust_remote_code errors from Hugging Face'}
```

## File: facebookresearch_llama-recipes/src/llama_cookbook/datasets/toxicchat_dataset.py

Prompts

```
['load a Python module from a .py file that is not in the Python path', 'dynamically load and call a custom dataset function from a .py file using a config and tokenizer', 'dynamically load and call a custom data collator function from a .py file using a config', 'review the load_module_from_py_file function to understand how it uses importlib to load arbitrary Python files', 'refactor get_custom_dataset to support additional file formats beyond .py files', 'load the samsum dataset from Hugging Face for a given split like train or test', 'get a preprocessed and tokenized samsum dataset ready for dialogue summarization model training', 'apply a summarization prompt template to samsum dialogue samples for instruction tuning', 'tokenize samsum dialogue and summary pairs with input ids, attention masks, and labels', 'review the samsum dataset loading function that handles trust_remote_code errors from Hugging Face', 'run the toxicchat dataset loader via fire CLI to print sample training data', 'run the toxicchat dataset loader in JSONL mode to export prompt and label pairs', 'create a Llama Guard formatted dataset from the lmsys toxic-chat HuggingFace dataset', 'map toxic chat moderation categories to Llama Guard category codes using the mapping table', 'tokenize a full prompt string into input IDs, labels, and attention mask for training']
```

Usage

```
{'run_toxicchat_dataset_main': 'run the toxicchat dataset loader via fire CLI to print sample training data', 'run_toxicchat_dataset_jsonl': 'run the toxicchat dataset loader in JSONL mode to export prompt and label pairs', 'create_llamaguard_toxicchat_dataset': 'create a Llama Guard formatted dataset from the lmsys toxic-chat HuggingFace dataset', 'map_tc_categories_to_lg': 'map toxic chat moderation categories to Llama Guard category codes using the mapping table', 'tokenize_prompt_and_labels': 'tokenize a full prompt string into input IDs, labels, and attention mask for training'}
```

