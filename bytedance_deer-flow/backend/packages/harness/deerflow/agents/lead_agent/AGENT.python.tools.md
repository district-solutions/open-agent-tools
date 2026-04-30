# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/lead_agent/agent.py

Prompts

```
['build a lead agent with configurable model, thinking mode, plan mode, and subagent settings', 'build a middleware chain with summarization, todo list, memory, loop detection, and clarification middlewares', 'create a summarization middleware that triggers on token count or message count with configurable model', 'create a todo list middleware for tracking complex multi-step tasks in plan mode', 'resolve a chat model name from request, agent config, or global default with fallback validation', 'build the lead agent system prompt with subagent capabilities, skills, memory context, and agent soul injected', 'get the skills prompt section listing available skills with their descriptions and locations for the system prompt', 'get the agent soul configuration string loaded from SOUL.md for a given agent name', 'get the deferred tools prompt section listing available deferred tool names from the tool_search registry', 'get the memory context string formatted for injection into the lead agent system prompt', 'prime the enabled skills cache by starting a background thread to load skills', 'warm the enabled skills cache and wait up to the specified timeout for it to be ready', 'clear the skills system prompt cache and trigger an asynchronous reload']
```

Usage

```
{'build_lead_agent': 'build a lead agent with configurable model, thinking mode, plan mode, and subagent settings', 'build_middleware_chain': 'build a middleware chain with summarization, todo list, memory, loop detection, and clarification middlewares', 'create_summarization_middleware': 'create a summarization middleware that triggers on token count or message count with configurable model', 'create_todo_list_middleware': 'create a todo list middleware for tracking complex multi-step tasks in plan mode', 'resolve_model_name': 'resolve a chat model name from request, agent config, or global default with fallback validation'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/lead_agent/prompt.py

Prompts

```
['build a lead agent with configurable model, thinking mode, plan mode, and subagent settings', 'build a middleware chain with summarization, todo list, memory, loop detection, and clarification middlewares', 'create a summarization middleware that triggers on token count or message count with configurable model', 'create a todo list middleware for tracking complex multi-step tasks in plan mode', 'resolve a chat model name from request, agent config, or global default with fallback validation', 'build the lead agent system prompt with subagent capabilities, skills, memory context, and agent soul injected', 'get the skills prompt section listing available skills with their descriptions and locations for the system prompt', 'get the agent soul configuration string loaded from SOUL.md for a given agent name', 'get the deferred tools prompt section listing available deferred tool names from the tool_search registry', 'get the memory context string formatted for injection into the lead agent system prompt', 'prime the enabled skills cache by starting a background thread to load skills', 'warm the enabled skills cache and wait up to the specified timeout for it to be ready', 'clear the skills system prompt cache and trigger an asynchronous reload']
```

Usage

```
{'build_lead_agent_system_prompt': 'build the lead agent system prompt with subagent capabilities, skills, memory context, and agent soul injected', 'get_skills_prompt_section': 'get the skills prompt section listing available skills with their descriptions and locations for the system prompt', 'get_agent_soul': 'get the agent soul configuration string loaded from SOUL.md for a given agent name', 'get_deferred_tools_prompt_section': 'get the deferred tools prompt section listing available deferred tool names from the tool_search registry', 'get_memory_context': 'get the memory context string formatted for injection into the lead agent system prompt', 'prime_enabled_skills_cache': 'prime the enabled skills cache by starting a background thread to load skills', 'warm_enabled_skills_cache': 'warm the enabled skills cache and wait up to the specified timeout for it to be ready', 'clear_skills_system_prompt_cache': 'clear the skills system prompt cache and trigger an asynchronous reload'}
```

