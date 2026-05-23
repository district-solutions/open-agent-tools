# Agent Python Tools

- repo: facebookresearch/perfect
- repo_uri: https://github.com/facebookresearch/perfect

## File: facebookresearch_perfect/fewshot/process_datasets.py

Prompts

```
['run the script to convert Gao et al datasets to unified JSON format', 'run process_data to convert all six few-shot datasets from CSV to JSON', 'run convert_datasets to transform a single task CSV into JSON records', 'review save_dataset function that writes a DataFrame as JSON records to disk', 'review the Arguments dataclass with data_dir and out_dir configuration fields', 'run the few-shot causal language model fine-tuning script with a JSON config file', 'run prototypical evaluation on a validation dataset using the BaseTrainer and AutoTask', 'run classifier evaluation on a validation dataset using RobertaForSequenceClassification', 'run prompt tuning with soft PET and prototypical evaluation on a language model', 'run adapter-based fine-tuning with frozen model parameters and trainable layernorms']
```

Usage

```
{'run_process_datasets': 'run the script to convert Gao et al datasets to unified JSON format', 'run_process_data': 'run process_data to convert all six few-shot datasets from CSV to JSON', 'run_convert_datasets': 'run convert_datasets to transform a single task CSV into JSON records', 'review_save_dataset': 'review save_dataset function that writes a DataFrame as JSON records to disk', 'review_Arguments': 'review the Arguments dataclass with data_dir and out_dir configuration fields'}
```

## File: facebookresearch_perfect/fewshot/run_clm.py

Prompts

```
['run the script to convert Gao et al datasets to unified JSON format', 'run process_data to convert all six few-shot datasets from CSV to JSON', 'run convert_datasets to transform a single task CSV into JSON records', 'review save_dataset function that writes a DataFrame as JSON records to disk', 'review the Arguments dataclass with data_dir and out_dir configuration fields', 'run the few-shot causal language model fine-tuning script with a JSON config file', 'run prototypical evaluation on a validation dataset using the BaseTrainer and AutoTask', 'run classifier evaluation on a validation dataset using RobertaForSequenceClassification', 'run prompt tuning with soft PET and prototypical evaluation on a language model', 'run adapter-based fine-tuning with frozen model parameters and trainable layernorms']
```

Usage

```
{'run_fewshot_clm_training': 'run the few-shot causal language model fine-tuning script with a JSON config file', 'run_prototypical_evaluation': 'run prototypical evaluation on a validation dataset using the BaseTrainer and AutoTask', 'run_classifier_evaluation': 'run classifier evaluation on a validation dataset using RobertaForSequenceClassification', 'run_prompt_tuning': 'run prompt tuning with soft PET and prototypical evaluation on a language model', 'run_adapter_fine_tuning': 'run adapter-based fine-tuning with frozen model parameters and trainable layernorms'}
```

