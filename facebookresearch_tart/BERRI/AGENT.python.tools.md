# Agent Python Tools

- repo: facebookresearch/tart
- repo_uri: https://github.com/facebookresearch/tart

## File: facebookresearch_tart/BERRI/create_tart_dual_train_data.py

Prompts

```
['run the script to create TART dual encoder training data from JSONL input files', 'create train and dev JSONL splits from dual encoder retrieval training data', 'process instruction unfollowing samples by mapping questions to randomly sampled contexts', 'load a JSONL file and return a list of parsed JSON objects', 'extract prompt columns from a DataFrame row to build a list of instruction prompts', 'run the script to create TART full train and dev JSON datasets from input JSONL files', 'process input data to create positive and negative labeled query document pairs with prompts', 'load JSON line-delimited data files and return a list of parsed JSON objects', 'extract prompt columns from a data row and return a list of prompt strings', 'run the denoising script to classify retrieved passages as positive or hard negative contexts', 'run the data training arguments parser to configure dataset paths, sequence length, and top-k passages', 'run the model arguments parser to configure pretrained model path, tokenizer, and early stopping patience', 'run the process_prompts function to load task-specific instruction prompts from an instruction file', 'run the preprocess_function to tokenize sentence pairs with padding and truncation for the EncT5 model']
```

Usage

```
{'run_create_tart_dual_train_data': 'run the script to create TART dual encoder training data from JSONL input files', 'create_train_dev_split': 'create train and dev JSONL splits from dual encoder retrieval training data', 'process_instruction_unfollowing_sample': 'process instruction unfollowing samples by mapping questions to randomly sampled contexts', 'load_jsonlines': 'load a JSONL file and return a list of parsed JSON objects', 'process_prompts': 'extract prompt columns from a DataFrame row to build a list of instruction prompts'}
```

## File: facebookresearch_tart/BERRI/create_tart_full_train_data.py

Prompts

```
['run the script to create TART dual encoder training data from JSONL input files', 'create train and dev JSONL splits from dual encoder retrieval training data', 'process instruction unfollowing samples by mapping questions to randomly sampled contexts', 'load a JSONL file and return a list of parsed JSON objects', 'extract prompt columns from a DataFrame row to build a list of instruction prompts', 'run the script to create TART full train and dev JSON datasets from input JSONL files', 'process input data to create positive and negative labeled query document pairs with prompts', 'load JSON line-delimited data files and return a list of parsed JSON objects', 'extract prompt columns from a data row and return a list of prompt strings', 'run the denoising script to classify retrieved passages as positive or hard negative contexts', 'run the data training arguments parser to configure dataset paths, sequence length, and top-k passages', 'run the model arguments parser to configure pretrained model path, tokenizer, and early stopping patience', 'run the process_prompts function to load task-specific instruction prompts from an instruction file', 'run the preprocess_function to tokenize sentence pairs with padding and truncation for the EncT5 model']
```

Usage

```
{'run_create_tart_train_data': 'run the script to create TART full train and dev JSON datasets from input JSONL files', 'process_data_positive_negative': 'process input data to create positive and negative labeled query document pairs with prompts', 'process_instruction_unfollowing_sample': 'process instruction unfollowing samples by sampling contexts and creating negative labeled training data', 'load_data_json_lines': 'load JSON line-delimited data files and return a list of parsed JSON objects', 'process_prompts_from_row': 'extract prompt columns from a data row and return a list of prompt strings'}
```

## File: facebookresearch_tart/BERRI/denoising.py

Prompts

```
['run the script to create TART dual encoder training data from JSONL input files', 'create train and dev JSONL splits from dual encoder retrieval training data', 'process instruction unfollowing samples by mapping questions to randomly sampled contexts', 'load a JSONL file and return a list of parsed JSON objects', 'extract prompt columns from a DataFrame row to build a list of instruction prompts', 'run the script to create TART full train and dev JSON datasets from input JSONL files', 'process input data to create positive and negative labeled query document pairs with prompts', 'load JSON line-delimited data files and return a list of parsed JSON objects', 'extract prompt columns from a data row and return a list of prompt strings', 'run the denoising script to classify retrieved passages as positive or hard negative contexts', 'run the data training arguments parser to configure dataset paths, sequence length, and top-k passages', 'run the model arguments parser to configure pretrained model path, tokenizer, and early stopping patience', 'run the process_prompts function to load task-specific instruction prompts from an instruction file', 'run the preprocess_function to tokenize sentence pairs with padding and truncation for the EncT5 model']
```

Usage

```
{'run_denoising_main': 'run the denoising script to classify retrieved passages as positive or hard negative contexts', 'run_DataTrainingArguments': 'run the data training arguments parser to configure dataset paths, sequence length, and top-k passages', 'run_ModelArguments': 'run the model arguments parser to configure pretrained model path, tokenizer, and early stopping patience', 'run_process_prompts': 'run the process_prompts function to load task-specific instruction prompts from an instruction file', 'run_preprocess_function': 'run the preprocess_function to tokenize sentence pairs with padding and truncation for the EncT5 model'}
```

