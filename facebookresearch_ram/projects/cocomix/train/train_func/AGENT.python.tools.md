# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cocomix/train/train_func/cocomix.py

Prompts

```
['run a single training step for the language model with concept extraction and loss computation', 'review the train_step function that computes LM loss combined with concept extraction cross-entropy loss', 'refactor the train_step function to use a different gradient clipping threshold or strategy', 'test the train_step concept loss computation using top-K extracted concepts and cross-entropy', 'summarize the train_step function that performs forward pass, backward pass, and optimizer step for concept-aware LM training', 'refactor the train_step function to support a different loss computation strategy', 'test the train_step function with mock accelerator, optimizer, and batch inputs']
```

Usage

```
{'run_train_step': 'run a single training step for the language model with concept extraction and loss computation', 'review_train_step': 'review the train_step function that computes LM loss combined with concept extraction cross-entropy loss', 'refactor_train_step_gradient_clipping': 'refactor the train_step function to use a different gradient clipping threshold or strategy', 'test_train_step_concept_loss': 'test the train_step concept loss computation using top-K extracted concepts and cross-entropy', 'summarize_train_step': 'summarize the train_step function that performs forward pass, backward pass, and optimizer step for concept-aware LM training'}
```

## File: facebookresearch_ram/projects/cocomix/train/train_func/ntp.py

Prompts

```
['run a single training step for the language model with concept extraction and loss computation', 'review the train_step function that computes LM loss combined with concept extraction cross-entropy loss', 'refactor the train_step function to use a different gradient clipping threshold or strategy', 'test the train_step concept loss computation using top-K extracted concepts and cross-entropy', 'summarize the train_step function that performs forward pass, backward pass, and optimizer step for concept-aware LM training', 'refactor the train_step function to support a different loss computation strategy', 'test the train_step function with mock accelerator, optimizer, and batch inputs']
```

Usage

```
{'run_train_step': 'run a single next-token-prediction training step with gradient accumulation and logging', 'review_train_step': 'review the train_step function for gradient clipping and metric synchronization logic', 'refactor_train_step': 'refactor the train_step function to support a different loss computation strategy', 'test_train_step': 'test the train_step function with mock accelerator, optimizer, and batch inputs', 'summarize_train_step': 'summarize the train_step function which performs NTP training with HuggingFace Accelerator'}
```

