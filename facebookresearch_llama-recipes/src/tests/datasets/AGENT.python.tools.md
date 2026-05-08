# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/src/tests/datasets/test_custom_dataset.py

Prompts

```
['test the custom dataset finetuning pipeline with Llama-2 and Llama-3.1 models using padding strategy', 'test that an AttributeError is raised when an unknown dataset function is referenced in custom_dataset.file', 'test the tokenize_dialog function with multi-turn user assistant dialog for Llama-2 and Llama-3 models', 'review the check_padded_entry function that validates attention mask, labels, and token IDs in a batch', 'review the EXPECTED_RESULTS dictionary containing expected tokenized output strings for Llama-2 and Llama-3.1 models', 'test the grammar dataset finetuning pipeline for Llama models using mocked tokenizer and model dependencies', 'run the llama cookbook finetuning main function with grammar dataset and padding batching strategy', 'validate the training dataloader batch contains input_ids, labels, and attention_mask keys', 'assert that input_ids start with bos_token_id and labels end with eos_token_id', 'check that train and eval dataloader lengths match expected sample counts divided by batch size', 'test the samsum dataset finetuning pipeline with mocked tokenizer and model loading', 'run the pytest test for samsum dataset finetuning with padding batching strategy', 'review the test_samsum_dataset function to understand dataloader assertions and token validation', 'refactor the test_samsum_dataset function to support a different dataset or batch size', 'summarize the Config dataclass that stores the model_type defaulting to llama']
```

Usage

```
{'test_custom_dataset_loading': 'test the custom dataset finetuning pipeline with Llama-2 and Llama-3.1 models using padding strategy', 'test_unknown_dataset_error': 'test that an AttributeError is raised when an unknown dataset function is referenced in custom_dataset.file', 'test_tokenize_dialog': 'test the tokenize_dialog function with multi-turn user assistant dialog for Llama-2 and Llama-3 models', 'review_check_padded_entry': 'review the check_padded_entry function that validates attention mask, labels, and token IDs in a batch', 'review_EXPECTED_RESULTS': 'review the EXPECTED_RESULTS dictionary containing expected tokenized output strings for Llama-2 and Llama-3.1 models'}
```

## File: facebookresearch_llama-recipes/src/tests/datasets/test_grammar_datasets.py

Prompts

```
['test the custom dataset finetuning pipeline with Llama-2 and Llama-3.1 models using padding strategy', 'test that an AttributeError is raised when an unknown dataset function is referenced in custom_dataset.file', 'test the tokenize_dialog function with multi-turn user assistant dialog for Llama-2 and Llama-3 models', 'review the check_padded_entry function that validates attention mask, labels, and token IDs in a batch', 'review the EXPECTED_RESULTS dictionary containing expected tokenized output strings for Llama-2 and Llama-3.1 models', 'test the grammar dataset finetuning pipeline for Llama models using mocked tokenizer and model dependencies', 'run the llama cookbook finetuning main function with grammar dataset and padding batching strategy', 'validate the training dataloader batch contains input_ids, labels, and attention_mask keys', 'assert that input_ids start with bos_token_id and labels end with eos_token_id', 'check that train and eval dataloader lengths match expected sample counts divided by batch size', 'test the samsum dataset finetuning pipeline with mocked tokenizer and model loading', 'run the pytest test for samsum dataset finetuning with padding batching strategy', 'review the test_samsum_dataset function to understand dataloader assertions and token validation', 'refactor the test_samsum_dataset function to support a different dataset or batch size', 'summarize the Config dataclass that stores the model_type defaulting to llama']
```

Usage

```
{'test_grammar_dataset': 'test the grammar dataset finetuning pipeline for Llama models using mocked tokenizer and model dependencies', 'run_grammar_finetuning_main': 'run the llama cookbook finetuning main function with grammar dataset and padding batching strategy', 'validate_train_dataloader': 'validate the training dataloader batch contains input_ids, labels, and attention_mask keys', 'assert_token_ids': 'assert that input_ids start with bos_token_id and labels end with eos_token_id', 'check_dataloader_lengths': 'check that train and eval dataloader lengths match expected sample counts divided by batch size'}
```

## File: facebookresearch_llama-recipes/src/tests/datasets/test_samsum_datasets.py

Prompts

```
['test the custom dataset finetuning pipeline with Llama-2 and Llama-3.1 models using padding strategy', 'test that an AttributeError is raised when an unknown dataset function is referenced in custom_dataset.file', 'test the tokenize_dialog function with multi-turn user assistant dialog for Llama-2 and Llama-3 models', 'review the check_padded_entry function that validates attention mask, labels, and token IDs in a batch', 'review the EXPECTED_RESULTS dictionary containing expected tokenized output strings for Llama-2 and Llama-3.1 models', 'test the grammar dataset finetuning pipeline for Llama models using mocked tokenizer and model dependencies', 'run the llama cookbook finetuning main function with grammar dataset and padding batching strategy', 'validate the training dataloader batch contains input_ids, labels, and attention_mask keys', 'assert that input_ids start with bos_token_id and labels end with eos_token_id', 'check that train and eval dataloader lengths match expected sample counts divided by batch size', 'test the samsum dataset finetuning pipeline with mocked tokenizer and model loading', 'run the pytest test for samsum dataset finetuning with padding batching strategy', 'review the test_samsum_dataset function to understand dataloader assertions and token validation', 'refactor the test_samsum_dataset function to support a different dataset or batch size', 'summarize the Config dataclass that stores the model_type defaulting to llama']
```

Usage

```
{'test_samsum_dataset': 'test the samsum dataset finetuning pipeline with mocked tokenizer and model loading', 'run_samsum_finetuning_test': 'run the pytest test for samsum dataset finetuning with padding batching strategy', 'review_test_samsum_dataset': 'review the test_samsum_dataset function to understand dataloader assertions and token validation', 'refactor_test_samsum_dataset': 'refactor the test_samsum_dataset function to support a different dataset or batch size', 'summarize_Config_dataclass': 'summarize the Config dataclass that stores the model_type defaulting to llama'}
```

