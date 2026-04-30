# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/experimental/grpo_with_replay_buffer/grpo_with_replay_buffer_trainer.py

Prompts

```
['create a ReplayBuffer with a max_size to store and sample previously seen rollouts by score', 'sample groups from the replay buffer weighted by normalized scores with replacement support', 'update the replay buffer with groups that have reward variance (std > 0) for later reuse', 'update current batch data with samples from replay buffer replacing groups with zero variance', 'generate completions from prompts, compute per-token log probabilities, rewards, and advantages for GRPO training']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with a max_size to store and sample previously seen rollouts by score', 'sample_from_replay_buffer': 'sample groups from the replay buffer weighted by normalized scores with replacement support', 'update_replay_buffer': 'update the replay buffer with groups that have reward variance (std > 0) for later reuse', 'update_with_replay_buffer': 'update current batch data with samples from replay buffer replacing groups with zero variance', 'generate_and_score_completions': 'generate completions from prompts, compute per-token log probabilities, rewards, and advantages for GRPO training'}
```

