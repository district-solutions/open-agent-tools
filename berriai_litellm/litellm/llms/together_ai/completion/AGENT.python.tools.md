# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/together_ai/completion/transformation.py

Prompts

```
['transform a list of OpenAI-style messages into a TogetherAI-compatible string prompt', 'transform an OpenAI text completion request into a TogetherAI completion request dict', 'validate that the prompt does not contain integer tokens unsupported by TogetherAI', 'reject prompts containing multiple items since TogetherAI supports only a single prompt', 'convert OpenAI message arrays into a single string prompt for TogetherAI']
```

Usage

```
{'transform_together_prompt': 'transform a list of OpenAI-style messages into a TogetherAI-compatible string prompt', 'transform_text_completion_request': 'transform an OpenAI text completion request into a TogetherAI completion request dict', 'validate_together_prompt_tokens': 'validate that the prompt does not contain integer tokens unsupported by TogetherAI', 'reject_multiple_prompts': 'reject prompts containing multiple items since TogetherAI supports only a single prompt', 'transform_messages_to_string': 'convert OpenAI message arrays into a single string prompt for TogetherAI'}
```

