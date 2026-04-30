# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/block_code_execution/block_code_execution.py

Prompts

```
['create a BlockCodeExecutionGuardrail instance with blocked languages, action mode, and confidence threshold', 'detect fenced code blocks in markdown text and return their positions, languages, and confidence scores', 'block LLM requests that contain execution intent phrases like run, execute, or read file commands', 'mask executable code blocks in LLM responses when confidence exceeds the configured threshold', "check if user text contains phrases indicating they do not want code executed, such as explain or don't run"]
```

Usage

```
{'create_guardrail_block_code_execution': 'create a BlockCodeExecutionGuardrail instance with blocked languages, action mode, and confidence threshold', 'detect_code_blocks_in_text': 'detect fenced code blocks in markdown text and return their positions, languages, and confidence scores', 'block_execution_requests': 'block LLM requests that contain execution intent phrases like run, execute, or read file commands', 'mask_code_blocks_in_response': 'mask executable code blocks in LLM responses when confidence exceeds the configured threshold', 'check_no_execution_intent': "check if user text contains phrases indicating they do not want code executed, such as explain or don't run"}
```

