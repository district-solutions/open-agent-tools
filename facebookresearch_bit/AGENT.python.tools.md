# Agent Python Tools

- repo: facebookresearch/bit
- repo_uri: https://github.com/facebookresearch/bit

## File: facebookresearch_bit/helper.py

Prompts

```
['generate a random 5-character alphanumeric job ID string', 'initialize logging to a file and console with a given log path', 'print all argument key-value pairs to the logger as info messages', 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'log and visualize learnable clipping values from a dictionary of PyTorch tensors', 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save the student model state dict and config to the output directory during training', 'check and log the gradient scale ratio across weight, bias, and layer norm parameters', 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'train the KDLearner student model using knowledge distillation from the teacher model', 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate a pair of token sequences in place to fit within a maximum combined length', 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute the exact match score between a gold answer and a predicted answer string', 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores']
```

Usage

```
{'generate_job_id': 'generate a random 5-character alphanumeric job ID string', 'init_logging': 'initialize logging to a file and console with a given log path', 'print_args': 'print all argument key-value pairs to the logger as info messages', 'soft_cross_entropy': 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'visualize_clip': 'log and visualize learnable clipping values from a dictionary of PyTorch tensors'}
```

## File: facebookresearch_bit/kd_learner_glue.py

Prompts

```
['generate a random 5-character alphanumeric job ID string', 'initialize logging to a file and console with a given log path', 'print all argument key-value pairs to the logger as info messages', 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'log and visualize learnable clipping values from a dictionary of PyTorch tensors', 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save the student model state dict and config to the output directory during training', 'check and log the gradient scale ratio across weight, bias, and layer norm parameters', 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'train the KDLearner student model using knowledge distillation from the teacher model', 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate a pair of token sequences in place to fit within a maximum combined length', 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute the exact match score between a gold answer and a predicted answer string', 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores']
```

Usage

```
{'build_KDLearner_optimizer': 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train_KDLearner_with_KD': 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate_KDLearner_model': 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save_KDLearner_checkpoint': 'save the student model state dict and config to the output directory during training', 'check_grad_scale_KDLearner': 'check and log the gradient scale ratio across weight, bias, and layer norm parameters'}
```

## File: facebookresearch_bit/kd_learner_squad.py

Prompts

```
['generate a random 5-character alphanumeric job ID string', 'initialize logging to a file and console with a given log path', 'print all argument key-value pairs to the logger as info messages', 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'log and visualize learnable clipping values from a dictionary of PyTorch tensors', 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save the student model state dict and config to the output directory during training', 'check and log the gradient scale ratio across weight, bias, and layer norm parameters', 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'train the KDLearner student model using knowledge distillation from the teacher model', 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate a pair of token sequences in place to fit within a maximum combined length', 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute the exact match score between a gold answer and a predicted answer string', 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores']
```

Usage

```
{'build_KDLearner': 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'build_KDLearner_optimizer': 'build the KDLearner optimizer with BertAdam and warmup linear schedule for training', 'train_KDLearner': 'train the KDLearner student model using knowledge distillation from the teacher model', 'eval_KDLearner': 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'check_grad_scale_KDLearner': 'check the gradient scale ratio of student model parameters during training'}
```

## File: facebookresearch_bit/utils_glue.py

Prompts

```
['generate a random 5-character alphanumeric job ID string', 'initialize logging to a file and console with a given log path', 'print all argument key-value pairs to the logger as info messages', 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'log and visualize learnable clipping values from a dictionary of PyTorch tensors', 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save the student model state dict and config to the output directory during training', 'check and log the gradient scale ratio across weight, bias, and layer norm parameters', 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'train the KDLearner student model using knowledge distillation from the teacher model', 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate a pair of token sequences in place to fit within a maximum combined length', 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute the exact match score between a gold answer and a predicted answer string', 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores']
```

Usage

```
{'convert_examples_to_features': 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute_metrics': 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'get_tensor_data': 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'use_data_processor': 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate_seq_pair': 'truncate a pair of token sequences in place to fit within a maximum combined length'}
```

## File: facebookresearch_bit/utils_squad.py

Prompts

```
['generate a random 5-character alphanumeric job ID string', 'initialize logging to a file and console with a given log path', 'print all argument key-value pairs to the logger as info messages', 'compute soft cross entropy loss between predicted logits and target logits using PyTorch', 'log and visualize learnable clipping values from a dictionary of PyTorch tensors', 'build a KDLearner optimizer with grouped parameters and BertAdam schedule for knowledge distillation training', 'train a student model using knowledge distillation with logit, representation, and attention distillation from a teacher model', 'evaluate a student model on GLUE tasks with classification or regression output modes and compute metrics', 'save the student model state dict and config to the output directory during training', 'check and log the gradient scale ratio across weight, bias, and layer norm parameters', 'build a KDLearner instance with student and teacher models for knowledge distillation on SQuAD', 'train the KDLearner student model using knowledge distillation from the teacher model', 'evaluate a model on the SQuAD dataset and return F1 and exact match scores', 'convert GLUE task InputExample objects into tokenized InputFeatures with padding and truncation for BERT models', 'compute task-specific evaluation metrics like accuracy, F1, MCC, or correlation for GLUE benchmark tasks', 'create a PyTorch TensorDataset from a list of InputFeatures for classification or regression output modes', 'load and parse GLUE dataset TSV files into InputExample objects using task-specific DataProcessor subclasses', 'truncate a pair of token sequences in place to fit within a maximum combined length', 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute the exact match score between a gold answer and a predicted answer string', 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores']
```

Usage

```
{'normalize_answer': 'normalize a SQuAD answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute_exact': 'compute the exact match score between a gold answer and a predicted answer string', 'compute_f1': 'compute the F1 score between a gold answer and a predicted answer using token-level overlap', 'evaluate_squad': 'evaluate SQuAD 1.1 predictions against a dataset and return exact match and F1 scores', 'evaluate_squad_v2': 'evaluate SQuAD 2.0 predictions with unanswerable question support and return exact match and F1 scores'}
```

