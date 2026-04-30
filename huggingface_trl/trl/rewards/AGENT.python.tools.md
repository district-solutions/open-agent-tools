# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/rewards/accuracy_rewards.py

Prompts

```
['create a reward function that checks if model completions match ground truth solutions using math verification', 'test the accuracy_reward function with latex boxed answers and fractional solutions', 'run reasoning_accuracy_reward to extract final answers after reasoning delimiters like <think> and verify against solutions', 'build a reward evaluation pipeline using accuracy_reward and reasoning_accuracy_reward for math problem grading', 'review the accuracy_rewards module for math verification with latex parsing and timeout handling in worker threads', 'test the think_format_reward function that evaluates if reasoning text is enclosed within <think> and </think> tags', 'summarize the think_format_reward function that checks completion format and returns 1.0 or 0.0 rewards', 'review the think_format_reward function that validates <think>...</think> tag enclosure in model completions', 'refactor the think_format_reward function to support configurable opening and closing tag delimiters', 'create a reward function that validates reasoning text is properly enclosed within <think> and </think> tags for RLHF training', 'create a reward function that penalizes overlong completions using the DAPO paper formula']
```

Usage

```
{'create_accuracy_reward': 'create a reward function that checks if model completions match ground truth solutions using math verification', 'test_accuracy_reward': 'test the accuracy_reward function with latex boxed answers and fractional solutions', 'run_reasoning_accuracy_reward': 'run reasoning_accuracy_reward to extract final answers after reasoning delimiters like <think> and verify against solutions', 'build_reward_evaluator': 'build a reward evaluation pipeline using accuracy_reward and reasoning_accuracy_reward for math problem grading', 'review_accuracy_rewards': 'review the accuracy_rewards module for math verification with latex parsing and timeout handling in worker threads'}
```

## File: huggingface_trl/trl/rewards/format_rewards.py

Prompts

```
['create a reward function that checks if model completions match ground truth solutions using math verification', 'test the accuracy_reward function with latex boxed answers and fractional solutions', 'run reasoning_accuracy_reward to extract final answers after reasoning delimiters like <think> and verify against solutions', 'build a reward evaluation pipeline using accuracy_reward and reasoning_accuracy_reward for math problem grading', 'review the accuracy_rewards module for math verification with latex parsing and timeout handling in worker threads', 'test the think_format_reward function that evaluates if reasoning text is enclosed within <think> and </think> tags', 'summarize the think_format_reward function that checks completion format and returns 1.0 or 0.0 rewards', 'review the think_format_reward function that validates <think>...</think> tag enclosure in model completions', 'refactor the think_format_reward function to support configurable opening and closing tag delimiters', 'create a reward function that validates reasoning text is properly enclosed within <think> and </think> tags for RLHF training', 'create a reward function that penalizes overlong completions using the DAPO paper formula']
```

Usage

```
{'test_think_format_reward': 'test the think_format_reward function that evaluates if reasoning text is enclosed within <think> and </think> tags', 'summarize_think_format_reward': 'summarize the think_format_reward function that checks completion format and returns 1.0 or 0.0 rewards', 'review_think_format_reward': 'review the think_format_reward function that validates <think>...</think> tag enclosure in model completions', 'refactor_think_format_reward': 'refactor the think_format_reward function to support configurable opening and closing tag delimiters', 'create_think_format_reward': 'create a reward function that validates reasoning text is properly enclosed within <think> and </think> tags for RLHF training'}
```

## File: huggingface_trl/trl/rewards/other_rewards.py

Prompts

```
['create a reward function that checks if model completions match ground truth solutions using math verification', 'test the accuracy_reward function with latex boxed answers and fractional solutions', 'run reasoning_accuracy_reward to extract final answers after reasoning delimiters like <think> and verify against solutions', 'build a reward evaluation pipeline using accuracy_reward and reasoning_accuracy_reward for math problem grading', 'review the accuracy_rewards module for math verification with latex parsing and timeout handling in worker threads', 'test the think_format_reward function that evaluates if reasoning text is enclosed within <think> and </think> tags', 'summarize the think_format_reward function that checks completion format and returns 1.0 or 0.0 rewards', 'review the think_format_reward function that validates <think>...</think> tag enclosure in model completions', 'refactor the think_format_reward function to support configurable opening and closing tag delimiters', 'create a reward function that validates reasoning text is properly enclosed within <think> and </think> tags for RLHF training', 'create a reward function that penalizes overlong completions using the DAPO paper formula']
```

Usage

```
{'create_get_soft_overlong_punishment': 'create a reward function that penalizes overlong completions using the DAPO paper formula'}
```

