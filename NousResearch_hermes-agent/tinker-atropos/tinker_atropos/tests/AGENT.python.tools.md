# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tinker-atropos/tinker_atropos/tests/test_logprob_alignment.py

Prompts

```
['test the trainer.pad_data_to_good_offset method to align logprobs with token offsets and compute advantages', 'test that advantage values are zeroed for prompt tokens and computed for generated tokens in pad_data_to_good_offset', 'test that logprob and advantage statistics (mean, std, min, p50, sum) are populated after calling pad_data_to_good_offset', 'test that setting set_advantage_to_zero in overrides forces all advantage values to zero in pad_data_to_good_offset', 'test that groups with all zero advantages are skipped and produce empty datums and group_rewards lists', 'test the health endpoint returns ok status and trainer initialized flag', 'test the completions endpoint handles single and batch prompt requests', 'test the chat completions endpoint handles message-based conversations with stop sequences', 'test the generate endpoint handles token-based generation with logprobs', 'test error handling returns 503 when trainer is not initialized']
```

Usage

```
{'test_pad_data_to_good_offset': 'test the trainer.pad_data_to_good_offset method to align logprobs with token offsets and compute advantages', 'test_advantage_masking_prompt_tokens': 'test that advantage values are zeroed for prompt tokens and computed for generated tokens in pad_data_to_good_offset', 'test_logprob_statistics': 'test that logprob and advantage statistics (mean, std, min, p50, sum) are populated after calling pad_data_to_good_offset', 'test_zero_advantage_override': 'test that setting set_advantage_to_zero in overrides forces all advantage values to zero in pad_data_to_good_offset', 'test_skip_groups_all_zero_advantages': 'test that groups with all zero advantages are skipped and produce empty datums and group_rewards lists'}
```

## File: NousResearch_hermes-agent/tinker-atropos/tinker_atropos/tests/test_managed_server.py

Prompts

```
['test the trainer.pad_data_to_good_offset method to align logprobs with token offsets and compute advantages', 'test that advantage values are zeroed for prompt tokens and computed for generated tokens in pad_data_to_good_offset', 'test that logprob and advantage statistics (mean, std, min, p50, sum) are populated after calling pad_data_to_good_offset', 'test that setting set_advantage_to_zero in overrides forces all advantage values to zero in pad_data_to_good_offset', 'test that groups with all zero advantages are skipped and produce empty datums and group_rewards lists', 'test the health endpoint returns ok status and trainer initialized flag', 'test the completions endpoint handles single and batch prompt requests', 'test the chat completions endpoint handles message-based conversations with stop sequences', 'test the generate endpoint handles token-based generation with logprobs', 'test error handling returns 503 when trainer is not initialized']
```

Usage

```
{'test_health_endpoint': 'test the health endpoint returns ok status and trainer initialized flag', 'test_completions_endpoint': 'test the completions endpoint handles single and batch prompt requests', 'test_chat_completions_endpoint': 'test the chat completions endpoint handles message-based conversations with stop sequences', 'test_generate_endpoint': 'test the generate endpoint handles token-based generation with logprobs', 'test_error_handling': 'test error handling returns 503 when trainer is not initialized'}
```

