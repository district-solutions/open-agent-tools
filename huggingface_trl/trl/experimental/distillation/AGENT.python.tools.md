# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/experimental/distillation/distillation.py

Prompts

```
['run full off-policy distillation training from a teacher model to a smaller student model using command-line args', 'run mixed on/off-policy distillation training with configurable lambda and beta weights', 'run distillation training with LoRA parameter-efficient fine-tuning on the student model', 'build an argparse parser for the distillation training script with model, dataset, and training config', 'train a student model via knowledge distillation from a teacher model with optional eval and logging', 'compute the generalized Jensen-Shannon Divergence loss between student and teacher model log-probabilities', 'generate on-policy completions from the student model using vLLM or model.generate() for distillation training', 'trim padded batch tensors into per-sample sequences for teacher-server logprob requests', 'log prompt-completion samples to console, wandb, and trackio during distillation training']
```

Usage

```
{'run_distillation_training': 'run full off-policy distillation training from a teacher model to a smaller student model using command-line args', 'run_mixed_policy_distillation': 'run mixed on/off-policy distillation training with configurable lambda and beta weights', 'run_lora_distillation': 'run distillation training with LoRA parameter-efficient fine-tuning on the student model', 'build_distillation_parser': 'build an argparse parser for the distillation training script with model, dataset, and training config', 'train_distillation_model': 'train a student model via knowledge distillation from a teacher model with optional eval and logging'}
```

## File: huggingface_trl/trl/experimental/distillation/distillation_trainer.py

Prompts

```
['run full off-policy distillation training from a teacher model to a smaller student model using command-line args', 'run mixed on/off-policy distillation training with configurable lambda and beta weights', 'run distillation training with LoRA parameter-efficient fine-tuning on the student model', 'build an argparse parser for the distillation training script with model, dataset, and training config', 'train a student model via knowledge distillation from a teacher model with optional eval and logging', 'compute the generalized Jensen-Shannon Divergence loss between student and teacher model log-probabilities', 'generate on-policy completions from the student model using vLLM or model.generate() for distillation training', 'trim padded batch tensors into per-sample sequences for teacher-server logprob requests', 'log prompt-completion samples to console, wandb, and trackio during distillation training']
```

Usage

```
{'train_distillation_model': 'train a student language model via knowledge distillation from a teacher model using generalized JSD loss', 'compute_jsd_divergence_loss': 'compute the generalized Jensen-Shannon Divergence loss between student and teacher model log-probabilities', 'generate_student_completions': 'generate on-policy completions from the student model using vLLM or model.generate() for distillation training', 'build_teacher_request_inputs': 'trim padded batch tensors into per-sample sequences for teacher-server logprob requests', 'log_training_completions': 'log prompt-completion samples to console, wandb, and trackio during distillation training'}
```

