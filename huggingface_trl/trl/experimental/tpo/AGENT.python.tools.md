# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/experimental/tpo/tpo.py

Prompts

```
['build a triple-preference dataset from raw UltraFeedback completions sorted by overall_score', 'wrap standard-format triple-preference data into conversational message format for chat template application', 'train a causal language model using Triple Preference Optimization with chosen, rejected, and reference completions', 'configure TPO training with beta, tpo_alpha, loss_type, and tpo_l_gamma hyperparameters', 'run TPO training via CLI with dataset, model, batch size, learning rate, and output directory arguments', 'build a TPO trainer for triple preference optimization on a causal language model with chosen, rejected, and reference completions', 'create a data collator that batches prompt, chosen, rejected, and reference token sequences with dynamic padding and completion masks', 'run triple preference optimization training with sigmoid, hinge, ipo, or tpo-l loss types on a preference dataset', 'extract the shared prompt prefix from chosen and rejected completions and strip it from the reference gold completion', 'evaluate a TPO-trained model computing token accuracy, reward margins, and log probabilities on a triple-preference dataset']
```

Usage

```
{'build_triple_preference_from_ultrafeedback': 'build a triple-preference dataset from raw UltraFeedback completions sorted by overall_score', 'to_conversational': 'wrap standard-format triple-preference data into conversational message format for chat template application', 'train_TPOTrainer': 'train a causal language model using Triple Preference Optimization with chosen, rejected, and reference completions', 'configure_TPOConfig': 'configure TPO training with beta, tpo_alpha, loss_type, and tpo_l_gamma hyperparameters', 'run_TPO_training_cli': 'run TPO training via CLI with dataset, model, batch size, learning rate, and output directory arguments'}
```

## File: huggingface_trl/trl/experimental/tpo/tpo_trainer.py

Prompts

```
['build a triple-preference dataset from raw UltraFeedback completions sorted by overall_score', 'wrap standard-format triple-preference data into conversational message format for chat template application', 'train a causal language model using Triple Preference Optimization with chosen, rejected, and reference completions', 'configure TPO training with beta, tpo_alpha, loss_type, and tpo_l_gamma hyperparameters', 'run TPO training via CLI with dataset, model, batch size, learning rate, and output directory arguments', 'build a TPO trainer for triple preference optimization on a causal language model with chosen, rejected, and reference completions', 'create a data collator that batches prompt, chosen, rejected, and reference token sequences with dynamic padding and completion masks', 'run triple preference optimization training with sigmoid, hinge, ipo, or tpo-l loss types on a preference dataset', 'extract the shared prompt prefix from chosen and rejected completions and strip it from the reference gold completion', 'evaluate a TPO-trained model computing token accuracy, reward margins, and log probabilities on a triple-preference dataset']
```

Usage

```
{'build_tpo_trainer': 'build a TPO trainer for triple preference optimization on a causal language model with chosen, rejected, and reference completions', 'create_data_collator_triple_preference': 'create a data collator that batches prompt, chosen, rejected, and reference token sequences with dynamic padding and completion masks', 'run_tpo_training': 'run triple preference optimization training with sigmoid, hinge, ipo, or tpo-l loss types on a preference dataset', 'extract_triple_prompt': 'extract the shared prompt prefix from chosen and rejected completions and strip it from the reference gold completion', 'evaluate_tpo_model': 'evaluate a TPO-trained model computing token accuracy, reward margins, and log probabilities on a triple-preference dataset'}
```

