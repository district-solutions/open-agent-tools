# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/examples/pytorch/multiple-choice/run_swag.py

Prompts

```
['run fine-tuning of a pretrained model for the SWAG multiple-choice dataset', 'test evaluation of a fine-tuned model on the SWAG validation dataset', 'create ModelArguments dataclass for model, config, and tokenizer CLI parameters', 'build DataTrainingArguments dataclass for train and eval file CLI parameters', 'refactor the preprocess_function to tokenize multiple-choice examples with 4 endings per context', 'fine tune a transformers model on a multiple choice task using accelerate without the Trainer API', 'parse command line arguments for dataset name, model path, batch size, learning rate and training epochs', 'load a dataset from the hub or local files and preprocess it for multiple choice tokenization with accelerate', 'create train and evaluation data loaders with dynamic padding collator for multiple choice examples', 'train a multiple choice model using accelerate with gradient accumulation, mixed precision and checkpointing']
```

Usage

```
{'run_swag_finetune': 'run fine-tuning of a pretrained model for the SWAG multiple-choice dataset', 'test_run_swag_eval': 'test evaluation of a fine-tuned model on the SWAG validation dataset', 'create_model_arguments': 'create ModelArguments dataclass for model, config, and tokenizer CLI parameters', 'build_data_training_args': 'build DataTrainingArguments dataclass for train and eval file CLI parameters', 'refactor_preprocess_function': 'refactor the preprocess_function to tokenize multiple-choice examples with 4 endings per context'}
```

## File: huggingface_transformers/examples/pytorch/multiple-choice/run_swag_no_trainer.py

Prompts

```
['run fine-tuning of a pretrained model for the SWAG multiple-choice dataset', 'test evaluation of a fine-tuned model on the SWAG validation dataset', 'create ModelArguments dataclass for model, config, and tokenizer CLI parameters', 'build DataTrainingArguments dataclass for train and eval file CLI parameters', 'refactor the preprocess_function to tokenize multiple-choice examples with 4 endings per context', 'fine tune a transformers model on a multiple choice task using accelerate without the Trainer API', 'parse command line arguments for dataset name, model path, batch size, learning rate and training epochs', 'load a dataset from the hub or local files and preprocess it for multiple choice tokenization with accelerate', 'create train and evaluation data loaders with dynamic padding collator for multiple choice examples', 'train a multiple choice model using accelerate with gradient accumulation, mixed precision and checkpointing']
```

Usage

```
{'fine tune model multiple choice': 'fine tune a transformers model on a multiple choice task using accelerate without the Trainer API', 'parse command line arguments': 'parse command line arguments for dataset name, model path, batch size, learning rate and training epochs', 'load and preprocess dataset': 'load a dataset from the hub or local files and preprocess it for multiple choice tokenization with accelerate', 'create data loaders': 'create train and evaluation data loaders with dynamic padding collator for multiple choice examples', 'train model with accelerator': 'train a multiple choice model using accelerate with gradient accumulation, mixed precision and checkpointing'}
```

