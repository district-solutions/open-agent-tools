# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/website/test_generate_skill_docs.py

Prompts

```
['run pytest to verify plain code blocks without box-drawing characters are not wrapped in ascii-guard-ignore markers', 'run pytest to verify code blocks containing Unicode box-drawing characters get wrapped in ascii-guard-ignore comments', 'run pytest to verify only code blocks with box-drawing characters are wrapped while plain blocks stay untouched', 'run pytest to verify tilde-fenced code blocks containing box-drawing characters are also wrapped in ascii-guard-ignore markers', 'run pytest to verify that SKILL.md files already containing ascii-guard-ignore markers are handled without crashing']
```

Usage

```
{'run_test_code_block_without_box_chars': 'run pytest to verify plain code blocks without box-drawing characters are not wrapped in ascii-guard-ignore markers', 'run_test_code_block_with_box_chars_wrapped': 'run pytest to verify code blocks containing Unicode box-drawing characters get wrapped in ascii-guard-ignore comments', 'run_test_multiple_code_blocks_selective_wrap': 'run pytest to verify only code blocks with box-drawing characters are wrapped while plain blocks stay untouched', 'run_test_tilde_fenced_box_wrapped': 'run pytest to verify tilde-fenced code blocks containing box-drawing characters are also wrapped in ascii-guard-ignore markers', 'run_test_already_wrapped_double_wrap_safe': 'run pytest to verify that SKILL.md files already containing ascii-guard-ignore markers are handled without crashing'}
```

