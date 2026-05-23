# Agent Python Tools

- repo: facebookresearch/swe-rl
- repo_uri: https://github.com/facebookresearch/swe-rl

## File: facebookresearch_swe-rl/tests/test_reward.py

Prompts

```
['test calculate_search_replace_reward with multi-file SEARCH/REPLACE edits across a.py and b.py', 'test calculate_search_replace_reward returns zero reward when edits target non-existent files', 'test calculate_search_replace_reward handles new file creation alongside existing file edits', 'test calculate_search_replace_reward returns negative reward for malformed solution output', 'test calculate_reward_unidiff computes similarity between oracle and predicted diff patches']
```

Usage

```
{'test_multifile_edit': 'test calculate_search_replace_reward with multi-file SEARCH/REPLACE edits across a.py and b.py', 'test_zero_reward': 'test calculate_search_replace_reward returns zero reward when edits target non-existent files', 'test_new_file': 'test calculate_search_replace_reward handles new file creation alongside existing file edits', 'test_failed_parse': 'test calculate_search_replace_reward returns negative reward for malformed solution output', 'test_reward_unidiff': 'test calculate_reward_unidiff computes similarity between oracle and predicted diff patches'}
```

