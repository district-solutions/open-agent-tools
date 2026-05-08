# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/criterions/multi_modality_compound.py

Prompts

```
['build a FairseqCriterion that combines CTC and cross-entropy loss for speech-text joint pretraining', 'create a SpeechTextPreTrainCompoundCriterionConfig dataclass with zero_infinity and post_process fields', 'run the forward method to compute CTC or cross-entropy loss based on sample mode', 'review the reduce_metrics method that aggregates CTC loss, UER, WER, and raw WER across workers', 'test the mode2value and value2mode static methods that encode training mode as prime numbers', 'review the SpeechTextPreTrainCrossEntCriterion class and its multi-modality cross entropy loss computation', 'review the compute_loss method that handles both dict and tensor targets with masking', 'review the forward method that computes loss and returns logging output for training', 'review the get_lprobs_and_target method that extracts log probabilities and targets from model output', 'refactor the compute_loss method to support additional target types beyond dict and tensor', 'create a fairseq criterion that combines guided knowledge distillation loss with cross entropy for speech-text joint models', 'review the guide_loss_and_acc method to understand how teacher log probs guide student speech encoder training', 'refactor the compute_loss_and_acc method to support custom label smoothing or padding index configuration', 'test the aggregate_logging_outputs static method to verify correct aggregation of loss and accuracy metrics across data parallel GPUs', 'summarize the forward method logic for dual speech-text input handling with attention cost regularization']
```

Usage

```
{'build_compound_criterion': 'build a FairseqCriterion that combines CTC and cross-entropy loss for speech-text joint pretraining', 'create_compound_criterion_config': 'create a SpeechTextPreTrainCompoundCriterionConfig dataclass with zero_infinity and post_process fields', 'run_forward_compound': 'run the forward method to compute CTC or cross-entropy loss based on sample mode', 'review_reduce_metrics': 'review the reduce_metrics method that aggregates CTC loss, UER, WER, and raw WER across workers', 'test_mode2value': 'test the mode2value and value2mode static methods that encode training mode as prime numbers'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/criterions/multi_modality_cross_entropy.py

Prompts

```
['build a FairseqCriterion that combines CTC and cross-entropy loss for speech-text joint pretraining', 'create a SpeechTextPreTrainCompoundCriterionConfig dataclass with zero_infinity and post_process fields', 'run the forward method to compute CTC or cross-entropy loss based on sample mode', 'review the reduce_metrics method that aggregates CTC loss, UER, WER, and raw WER across workers', 'test the mode2value and value2mode static methods that encode training mode as prime numbers', 'review the SpeechTextPreTrainCrossEntCriterion class and its multi-modality cross entropy loss computation', 'review the compute_loss method that handles both dict and tensor targets with masking', 'review the forward method that computes loss and returns logging output for training', 'review the get_lprobs_and_target method that extracts log probabilities and targets from model output', 'refactor the compute_loss method to support additional target types beyond dict and tensor', 'create a fairseq criterion that combines guided knowledge distillation loss with cross entropy for speech-text joint models', 'review the guide_loss_and_acc method to understand how teacher log probs guide student speech encoder training', 'refactor the compute_loss_and_acc method to support custom label smoothing or padding index configuration', 'test the aggregate_logging_outputs static method to verify correct aggregation of loss and accuracy metrics across data parallel GPUs', 'summarize the forward method logic for dual speech-text input handling with attention cost regularization']
```

Usage

```
{'review_SpeechTextPreTrainCrossEntCriterion': 'review the SpeechTextPreTrainCrossEntCriterion class and its multi-modality cross entropy loss computation', 'review_compute_loss': 'review the compute_loss method that handles both dict and tensor targets with masking', 'review_forward': 'review the forward method that computes loss and returns logging output for training', 'review_get_lprobs_and_target': 'review the get_lprobs_and_target method that extracts log probabilities and targets from model output', 'refactor_compute_loss': 'refactor the compute_loss method to support additional target types beyond dict and tensor'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/criterions/text_guide_cross_entropy_acc.py

Prompts

```
['build a FairseqCriterion that combines CTC and cross-entropy loss for speech-text joint pretraining', 'create a SpeechTextPreTrainCompoundCriterionConfig dataclass with zero_infinity and post_process fields', 'run the forward method to compute CTC or cross-entropy loss based on sample mode', 'review the reduce_metrics method that aggregates CTC loss, UER, WER, and raw WER across workers', 'test the mode2value and value2mode static methods that encode training mode as prime numbers', 'review the SpeechTextPreTrainCrossEntCriterion class and its multi-modality cross entropy loss computation', 'review the compute_loss method that handles both dict and tensor targets with masking', 'review the forward method that computes loss and returns logging output for training', 'review the get_lprobs_and_target method that extracts log probabilities and targets from model output', 'refactor the compute_loss method to support additional target types beyond dict and tensor', 'create a fairseq criterion that combines guided knowledge distillation loss with cross entropy for speech-text joint models', 'review the guide_loss_and_acc method to understand how teacher log probs guide student speech encoder training', 'refactor the compute_loss_and_acc method to support custom label smoothing or padding index configuration', 'test the aggregate_logging_outputs static method to verify correct aggregation of loss and accuracy metrics across data parallel GPUs', 'summarize the forward method logic for dual speech-text input handling with attention cost regularization']
```

Usage

```
{'create_guided_criterion': 'create a fairseq criterion that combines guided knowledge distillation loss with cross entropy for speech-text joint models', 'review_guide_loss_and_acc': 'review the guide_loss_and_acc method to understand how teacher log probs guide student speech encoder training', 'refactor_compute_loss_and_acc': 'refactor the compute_loss_and_acc method to support custom label smoothing or padding index configuration', 'test_aggregate_logging_outputs': 'test the aggregate_logging_outputs static method to verify correct aggregation of loss and accuracy metrics across data parallel GPUs', 'summarize_forward_dual_input': 'summarize the forward method logic for dual speech-text input handling with attention cost regularization'}
```

