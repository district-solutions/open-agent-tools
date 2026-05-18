# Agent Python Tools

- repo: facebookresearch/mobilellm
- repo_uri: https://github.com/facebookresearch/mobilellm

## File: facebookresearch_mobilellm/utils/modeling_llama.py

Prompts

```
['build a LlamaForCausalLM model from config to generate text with causal language modeling', 'build a LlamaForSequenceClassification model to classify text sequences into multiple labels', 'build a LlamaForQuestionAnswering model to extract answer spans from context for QA tasks', 'build a LlamaForTokenClassification model to classify tokens for NER or similar tasks', 'build a LlamaModel decoder with layer sharing enabled to reuse decoder layers twice', 'create a cosine learning rate schedule with warmup for a PyTorch optimizer', 'build a LambdaLR scheduler using get_cosine_schedule_with_warmup with custom num_cycles', 'review the PretrainMixin class and its create_scheduler method for LR scheduling', 'test the PretrainTrainer get_train_dataloader method to verify it returns the training dataset', 'refactor the _get_cosine_schedule_with_warmup_lr_lambda function to support additional decay parameters', 'run process_args to parse HfArgumentParser CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass with local_dir, input_model_filename, output_model_filename, share_embedding, and layer_sharing fields', 'create a DataArguments dataclass with train_data_local_path and eval_data_local_path fields for dataset paths', 'create a TrainingArguments dataclass extending transformers.TrainingArguments with cache_dir, optim, output_dir, and model_max_length', 'review the process_args function that uses HfArgumentParser to parse and return model, data, and training arguments']
```

Usage

```
{'build_causal_lm': 'build a LlamaForCausalLM model from config to generate text with causal language modeling', 'build_sequence_classifier': 'build a LlamaForSequenceClassification model to classify text sequences into multiple labels', 'build_question_answering': 'build a LlamaForQuestionAnswering model to extract answer spans from context for QA tasks', 'build_token_classifier': 'build a LlamaForTokenClassification model to classify tokens for NER or similar tasks', 'build_decoder_with_layer_sharing': 'build a LlamaModel decoder with layer sharing enabled to reuse decoder layers twice'}
```

## File: facebookresearch_mobilellm/utils/pretrain_trainer.py

Prompts

```
['build a LlamaForCausalLM model from config to generate text with causal language modeling', 'build a LlamaForSequenceClassification model to classify text sequences into multiple labels', 'build a LlamaForQuestionAnswering model to extract answer spans from context for QA tasks', 'build a LlamaForTokenClassification model to classify tokens for NER or similar tasks', 'build a LlamaModel decoder with layer sharing enabled to reuse decoder layers twice', 'create a cosine learning rate schedule with warmup for a PyTorch optimizer', 'build a LambdaLR scheduler using get_cosine_schedule_with_warmup with custom num_cycles', 'review the PretrainMixin class and its create_scheduler method for LR scheduling', 'test the PretrainTrainer get_train_dataloader method to verify it returns the training dataset', 'refactor the _get_cosine_schedule_with_warmup_lr_lambda function to support additional decay parameters', 'run process_args to parse HfArgumentParser CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass with local_dir, input_model_filename, output_model_filename, share_embedding, and layer_sharing fields', 'create a DataArguments dataclass with train_data_local_path and eval_data_local_path fields for dataset paths', 'create a TrainingArguments dataclass extending transformers.TrainingArguments with cache_dir, optim, output_dir, and model_max_length', 'review the process_args function that uses HfArgumentParser to parse and return model, data, and training arguments']
```

Usage

```
{'create_cosine_lr_schedule': 'create a cosine learning rate schedule with warmup for a PyTorch optimizer', 'build_lambda_lr_scheduler': 'build a LambdaLR scheduler using get_cosine_schedule_with_warmup with custom num_cycles', 'review_PretrainMixin_create_scheduler': 'review the PretrainMixin class and its create_scheduler method for LR scheduling', 'test_PretrainTrainer_dataloader': 'test the PretrainTrainer get_train_dataloader method to verify it returns the training dataset', 'refactor_cosine_schedule_lambda': 'refactor the _get_cosine_schedule_with_warmup_lr_lambda function to support additional decay parameters'}
```

## File: facebookresearch_mobilellm/utils/process_args.py

Prompts

```
['build a LlamaForCausalLM model from config to generate text with causal language modeling', 'build a LlamaForSequenceClassification model to classify text sequences into multiple labels', 'build a LlamaForQuestionAnswering model to extract answer spans from context for QA tasks', 'build a LlamaForTokenClassification model to classify tokens for NER or similar tasks', 'build a LlamaModel decoder with layer sharing enabled to reuse decoder layers twice', 'create a cosine learning rate schedule with warmup for a PyTorch optimizer', 'build a LambdaLR scheduler using get_cosine_schedule_with_warmup with custom num_cycles', 'review the PretrainMixin class and its create_scheduler method for LR scheduling', 'test the PretrainTrainer get_train_dataloader method to verify it returns the training dataset', 'refactor the _get_cosine_schedule_with_warmup_lr_lambda function to support additional decay parameters', 'run process_args to parse HfArgumentParser CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass with local_dir, input_model_filename, output_model_filename, share_embedding, and layer_sharing fields', 'create a DataArguments dataclass with train_data_local_path and eval_data_local_path fields for dataset paths', 'create a TrainingArguments dataclass extending transformers.TrainingArguments with cache_dir, optim, output_dir, and model_max_length', 'review the process_args function that uses HfArgumentParser to parse and return model, data, and training arguments']
```

Usage

```
{'run_process_args': 'run process_args to parse HfArgumentParser CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create_model_arguments': 'create a ModelArguments dataclass with local_dir, input_model_filename, output_model_filename, share_embedding, and layer_sharing fields', 'create_data_arguments': 'create a DataArguments dataclass with train_data_local_path and eval_data_local_path fields for dataset paths', 'create_training_arguments': 'create a TrainingArguments dataclass extending transformers.TrainingArguments with cache_dir, optim, output_dir, and model_max_length', 'review_process_args': 'review the process_args function that uses HfArgumentParser to parse and return model, data, and training arguments'}
```

