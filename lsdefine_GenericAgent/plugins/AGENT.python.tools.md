# Agent Python Tools

- repo: lsdefine/GenericAgent
- repo_uri: https://github.com/lsdefine/GenericAgent

## File: lsdefine_GenericAgent/plugins/langfuse_tracing.py

Prompts

```
['enable Langfuse tracing for an agent by importing the module which self-activates if langfuse_config exists', 'wrap an LLM SSE parser to extract token usage from Claude or OpenAI streaming responses', 'extract token usage details from SSE response buffer including input, output, and cached tokens', 'patch tool before and after callbacks to create Langfuse tool spans with input and output tracking', 'wrap the agent runner loop to create a top-level Langfuse agent observation for the entire task']
```

Usage

```
{'enable_langfuse_tracing': 'enable Langfuse tracing for an agent by importing the module which self-activates if langfuse_config exists', 'wrap_llm_parser': 'wrap an LLM SSE parser to extract token usage from Claude or OpenAI streaming responses', 'extract_usage_from_sse': 'extract token usage details from SSE response buffer including input, output, and cached tokens', 'patch_tool_callbacks': 'patch tool before and after callbacks to create Langfuse tool spans with input and output tracking', 'wrap_agent_runner_loop': 'wrap the agent runner loop to create a top-level Langfuse agent observation for the entire task'}
```

