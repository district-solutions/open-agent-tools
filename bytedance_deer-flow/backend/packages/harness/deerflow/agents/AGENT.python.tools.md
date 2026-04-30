# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/factory.py

Prompts

```
['create a DeerFlow agent from plain Python arguments with model, tools, and middleware configuration', 'create a DeerFlow agent using declarative RuntimeFeatures flags for sandbox, vision, memory, and subagent capabilities', 'create a DeerFlow agent in plan mode with TodoMiddleware for structured multi-step task tracking', 'create a DeerFlow agent with extra middlewares inserted via @Next/@Prev anchor positioning', 'build an ordered middleware chain and extra tools from a RuntimeFeatures configuration object', 'create a RuntimeFeatures instance with sandbox enabled and memory disabled for a deerflow agent', 'build a RuntimeFeatures dataclass with custom AgentMiddleware instances for sandbox and vision features', 'create a middleware class decorated with @Next to place it after a specified AgentMiddleware anchor in the chain', 'create a middleware class decorated with @Prev to place it before a specified AgentMiddleware anchor in the chain', 'review the RuntimeFeatures dataclass and its feature flags for sandbox, memory, summarization, subagent, vision, auto_title, and guardrail', 'build a LangGraph agent state class that extends AgentState with sandbox, thread data, artifacts, and viewed images fields', 'create a TypedDict for sandbox state containing an optional sandbox_id string field', 'create a TypedDict for thread data state with optional workspace_path, uploads_path, and outputs_path fields', 'create a TypedDict for viewed image data containing base64 encoded image string and mime_type', 'merge and deduplicate two artifact lists while preserving insertion order using dict.fromkeys']
```

Usage

```
{'create_deerflow_agent': 'create a DeerFlow agent from plain Python arguments with model, tools, and middleware configuration', 'create_deerflow_agent_features': 'create a DeerFlow agent using declarative RuntimeFeatures flags for sandbox, vision, memory, and subagent capabilities', 'create_deerflow_agent_plan_mode': 'create a DeerFlow agent in plan mode with TodoMiddleware for structured multi-step task tracking', 'create_deerflow_agent_extra_middleware': 'create a DeerFlow agent with extra middlewares inserted via @Next/@Prev anchor positioning', 'assemble_from_features': 'build an ordered middleware chain and extra tools from a RuntimeFeatures configuration object'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/features.py

Prompts

```
['create a DeerFlow agent from plain Python arguments with model, tools, and middleware configuration', 'create a DeerFlow agent using declarative RuntimeFeatures flags for sandbox, vision, memory, and subagent capabilities', 'create a DeerFlow agent in plan mode with TodoMiddleware for structured multi-step task tracking', 'create a DeerFlow agent with extra middlewares inserted via @Next/@Prev anchor positioning', 'build an ordered middleware chain and extra tools from a RuntimeFeatures configuration object', 'create a RuntimeFeatures instance with sandbox enabled and memory disabled for a deerflow agent', 'build a RuntimeFeatures dataclass with custom AgentMiddleware instances for sandbox and vision features', 'create a middleware class decorated with @Next to place it after a specified AgentMiddleware anchor in the chain', 'create a middleware class decorated with @Prev to place it before a specified AgentMiddleware anchor in the chain', 'review the RuntimeFeatures dataclass and its feature flags for sandbox, memory, summarization, subagent, vision, auto_title, and guardrail', 'build a LangGraph agent state class that extends AgentState with sandbox, thread data, artifacts, and viewed images fields', 'create a TypedDict for sandbox state containing an optional sandbox_id string field', 'create a TypedDict for thread data state with optional workspace_path, uploads_path, and outputs_path fields', 'create a TypedDict for viewed image data containing base64 encoded image string and mime_type', 'merge and deduplicate two artifact lists while preserving insertion order using dict.fromkeys']
```

Usage

```
{'create_RuntimeFeatures': 'create a RuntimeFeatures instance with sandbox enabled and memory disabled for a deerflow agent', 'build_RuntimeFeatures_custom': 'build a RuntimeFeatures dataclass with custom AgentMiddleware instances for sandbox and vision features', 'create_Next_decorator': 'create a middleware class decorated with @Next to place it after a specified AgentMiddleware anchor in the chain', 'create_Prev_decorator': 'create a middleware class decorated with @Prev to place it before a specified AgentMiddleware anchor in the chain', 'review_RuntimeFeatures': 'review the RuntimeFeatures dataclass and its feature flags for sandbox, memory, summarization, subagent, vision, auto_title, and guardrail'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/thread_state.py

Prompts

```
['create a DeerFlow agent from plain Python arguments with model, tools, and middleware configuration', 'create a DeerFlow agent using declarative RuntimeFeatures flags for sandbox, vision, memory, and subagent capabilities', 'create a DeerFlow agent in plan mode with TodoMiddleware for structured multi-step task tracking', 'create a DeerFlow agent with extra middlewares inserted via @Next/@Prev anchor positioning', 'build an ordered middleware chain and extra tools from a RuntimeFeatures configuration object', 'create a RuntimeFeatures instance with sandbox enabled and memory disabled for a deerflow agent', 'build a RuntimeFeatures dataclass with custom AgentMiddleware instances for sandbox and vision features', 'create a middleware class decorated with @Next to place it after a specified AgentMiddleware anchor in the chain', 'create a middleware class decorated with @Prev to place it before a specified AgentMiddleware anchor in the chain', 'review the RuntimeFeatures dataclass and its feature flags for sandbox, memory, summarization, subagent, vision, auto_title, and guardrail', 'build a LangGraph agent state class that extends AgentState with sandbox, thread data, artifacts, and viewed images fields', 'create a TypedDict for sandbox state containing an optional sandbox_id string field', 'create a TypedDict for thread data state with optional workspace_path, uploads_path, and outputs_path fields', 'create a TypedDict for viewed image data containing base64 encoded image string and mime_type', 'merge and deduplicate two artifact lists while preserving insertion order using dict.fromkeys']
```

Usage

```
{'build_thread_state': 'build a LangGraph agent state class that extends AgentState with sandbox, thread data, artifacts, and viewed images fields', 'create_sandbox_state': 'create a TypedDict for sandbox state containing an optional sandbox_id string field', 'create_thread_data_state': 'create a TypedDict for thread data state with optional workspace_path, uploads_path, and outputs_path fields', 'create_viewed_image_data': 'create a TypedDict for viewed image data containing base64 encoded image string and mime_type', 'merge_artifacts_list': 'merge and deduplicate two artifact lists while preserving insertion order using dict.fromkeys'}
```

