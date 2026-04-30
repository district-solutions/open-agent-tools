# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/experimental/async_grpo/async_grpo_trainer.py

Prompts

```
['train a language model using asynchronous group relative policy optimization with vLLM rollout worker', 'create an AsyncGRPOTrainer instance with model, reward functions, and training dataset for RLHF fine-tuning', 'build a RolloutQueueDataset that pulls rollout samples from a queue with staleness checking', 'compute the GRPO loss with clipped ratios, advantages, and completion masks for policy optimization', 'sync model weights from the training process to the vLLM rollout worker with pause-resume lifecycle', 'test the AsyncGRPOTrainer with injected rollout worker stub and mock datasets', 'review the AsyncGRPOTrainer class and its asynchronous training loop with vLLM integration', "summarize the AsyncGRPOTrainer's capabilities for asynchronous group relative policy optimization", 'create an AsyncRolloutWorker instance with a model name, dataset, reward functions, and vLLM server URL for async GRPO rollout', 'start the AsyncRolloutWorker in a daemon thread to begin generating and scoring rollout groups asynchronously', 'stop the AsyncRolloutWorker by signaling the async event loop to shut down its generate and score loops', 'send updated model weights to the vLLM inference server via NCCL weight transfer and HTTP update endpoint', 'score a rollout group by computing rewards from multiple reward functions and producing RolloutSample objects with advantages']
```

Usage

```
{'train_async_grpo_model': 'train a language model using asynchronous group relative policy optimization with vLLM rollout worker', 'create_async_grpo_trainer': 'create an AsyncGRPOTrainer instance with model, reward functions, and training dataset for RLHF fine-tuning', 'build_rollout_queue_dataset': 'build a RolloutQueueDataset that pulls rollout samples from a queue with staleness checking', 'compute_grpo_loss': 'compute the GRPO loss with clipped ratios, advantages, and completion masks for policy optimization', 'sync_model_weights': 'sync model weights from the training process to the vLLM rollout worker with pause-resume lifecycle', 'test_async_grpo_trainer': 'test the AsyncGRPOTrainer with injected rollout worker stub and mock datasets', 'review_async_grpo_trainer': 'review the AsyncGRPOTrainer class and its asynchronous training loop with vLLM integration', 'summarize_grpo_trainer': "summarize the AsyncGRPOTrainer's capabilities for asynchronous group relative policy optimization"}
```

## File: huggingface_trl/trl/experimental/async_grpo/async_rollout_worker.py

Prompts

```
['train a language model using asynchronous group relative policy optimization with vLLM rollout worker', 'create an AsyncGRPOTrainer instance with model, reward functions, and training dataset for RLHF fine-tuning', 'build a RolloutQueueDataset that pulls rollout samples from a queue with staleness checking', 'compute the GRPO loss with clipped ratios, advantages, and completion masks for policy optimization', 'sync model weights from the training process to the vLLM rollout worker with pause-resume lifecycle', 'test the AsyncGRPOTrainer with injected rollout worker stub and mock datasets', 'review the AsyncGRPOTrainer class and its asynchronous training loop with vLLM integration', "summarize the AsyncGRPOTrainer's capabilities for asynchronous group relative policy optimization", 'create an AsyncRolloutWorker instance with a model name, dataset, reward functions, and vLLM server URL for async GRPO rollout', 'start the AsyncRolloutWorker in a daemon thread to begin generating and scoring rollout groups asynchronously', 'stop the AsyncRolloutWorker by signaling the async event loop to shut down its generate and score loops', 'send updated model weights to the vLLM inference server via NCCL weight transfer and HTTP update endpoint', 'score a rollout group by computing rewards from multiple reward functions and producing RolloutSample objects with advantages']
```

Usage

```
{'create_async_rollout_worker': 'create an AsyncRolloutWorker instance with a model name, dataset, reward functions, and vLLM server URL for async GRPO rollout', 'start_async_worker': 'start the AsyncRolloutWorker in a daemon thread to begin generating and scoring rollout groups asynchronously', 'stop_async_worker': 'stop the AsyncRolloutWorker by signaling the async event loop to shut down its generate and score loops', 'send_model_weights': 'send updated model weights to the vLLM inference server via NCCL weight transfer and HTTP update endpoint', 'score_rollout_group': 'score a rollout group by computing rewards from multiple reward functions and producing RolloutSample objects with advantages'}
```

