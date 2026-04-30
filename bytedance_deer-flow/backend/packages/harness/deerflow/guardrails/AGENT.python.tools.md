# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/guardrails/builtin.py

Prompts

```
['create an AllowlistProvider with a list of allowed tools for guardrail evaluation', 'test the AllowlistProvider evaluate method with a GuardrailRequest for tool access control', 'review the AllowlistProvider class and its allowlist/denylist tool filtering logic', 'refactor the AllowlistProvider aevaluate method to support async tool name validation', 'summarize the AllowlistProvider evaluate method and its GuardrailDecision return behavior', 'create a GuardrailMiddleware instance with a GuardrailProvider to evaluate tool calls before execution', 'build a GuardrailRequest from a ToolCallRequest containing tool name, input args, agent id, and timestamp', 'test the sync wrap_tool_call method to evaluate and block denied tool calls with error ToolMessages', 'review the async awrap_tool_call method that evaluates tool calls and preserves LangGraph control-flow signals', 'summarize the GuardrailMiddleware class that intercepts tool calls via fail_closed policy to enforce guardrail decisions', 'create a GuardrailRequest dataclass with tool name, input dict, agent id, and thread id for authorization context', 'create a GuardrailDecision dataclass with allow boolean, reasons list, and optional policy id for provider verdicts', 'create a GuardrailReason dataclass with a code string and optional message for structured allow/deny reasons', 'build a pluggable GuardrailProvider protocol implementing evaluate and aevaluate methods for tool-call authorization', 'test the GuardrailProvider protocol and its dataclasses for pre-tool-call authorization decisions']
```

Usage

```
{'create_allowlist_provider': 'create an AllowlistProvider with a list of allowed tools for guardrail evaluation', 'test_allowlist_provider': 'test the AllowlistProvider evaluate method with a GuardrailRequest for tool access control', 'review_allowlist_provider': 'review the AllowlistProvider class and its allowlist/denylist tool filtering logic', 'refactor_aevaluate': 'refactor the AllowlistProvider aevaluate method to support async tool name validation', 'summarize_guardrail_evaluation': 'summarize the AllowlistProvider evaluate method and its GuardrailDecision return behavior'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/guardrails/middleware.py

Prompts

```
['create an AllowlistProvider with a list of allowed tools for guardrail evaluation', 'test the AllowlistProvider evaluate method with a GuardrailRequest for tool access control', 'review the AllowlistProvider class and its allowlist/denylist tool filtering logic', 'refactor the AllowlistProvider aevaluate method to support async tool name validation', 'summarize the AllowlistProvider evaluate method and its GuardrailDecision return behavior', 'create a GuardrailMiddleware instance with a GuardrailProvider to evaluate tool calls before execution', 'build a GuardrailRequest from a ToolCallRequest containing tool name, input args, agent id, and timestamp', 'test the sync wrap_tool_call method to evaluate and block denied tool calls with error ToolMessages', 'review the async awrap_tool_call method that evaluates tool calls and preserves LangGraph control-flow signals', 'summarize the GuardrailMiddleware class that intercepts tool calls via fail_closed policy to enforce guardrail decisions', 'create a GuardrailRequest dataclass with tool name, input dict, agent id, and thread id for authorization context', 'create a GuardrailDecision dataclass with allow boolean, reasons list, and optional policy id for provider verdicts', 'create a GuardrailReason dataclass with a code string and optional message for structured allow/deny reasons', 'build a pluggable GuardrailProvider protocol implementing evaluate and aevaluate methods for tool-call authorization', 'test the GuardrailProvider protocol and its dataclasses for pre-tool-call authorization decisions']
```

Usage

```
{'create_GuardrailMiddleware': 'create a GuardrailMiddleware instance with a GuardrailProvider to evaluate tool calls before execution', 'build_GuardrailRequest': 'build a GuardrailRequest from a ToolCallRequest containing tool name, input args, agent id, and timestamp', 'test_wrap_tool_call': 'test the sync wrap_tool_call method to evaluate and block denied tool calls with error ToolMessages', 'review_awrap_tool_call': 'review the async awrap_tool_call method that evaluates tool calls and preserves LangGraph control-flow signals', 'summarize_GuardrailMiddleware': 'summarize the GuardrailMiddleware class that intercepts tool calls via fail_closed policy to enforce guardrail decisions'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/guardrails/provider.py

Prompts

```
['create an AllowlistProvider with a list of allowed tools for guardrail evaluation', 'test the AllowlistProvider evaluate method with a GuardrailRequest for tool access control', 'review the AllowlistProvider class and its allowlist/denylist tool filtering logic', 'refactor the AllowlistProvider aevaluate method to support async tool name validation', 'summarize the AllowlistProvider evaluate method and its GuardrailDecision return behavior', 'create a GuardrailMiddleware instance with a GuardrailProvider to evaluate tool calls before execution', 'build a GuardrailRequest from a ToolCallRequest containing tool name, input args, agent id, and timestamp', 'test the sync wrap_tool_call method to evaluate and block denied tool calls with error ToolMessages', 'review the async awrap_tool_call method that evaluates tool calls and preserves LangGraph control-flow signals', 'summarize the GuardrailMiddleware class that intercepts tool calls via fail_closed policy to enforce guardrail decisions', 'create a GuardrailRequest dataclass with tool name, input dict, agent id, and thread id for authorization context', 'create a GuardrailDecision dataclass with allow boolean, reasons list, and optional policy id for provider verdicts', 'create a GuardrailReason dataclass with a code string and optional message for structured allow/deny reasons', 'build a pluggable GuardrailProvider protocol implementing evaluate and aevaluate methods for tool-call authorization', 'test the GuardrailProvider protocol and its dataclasses for pre-tool-call authorization decisions']
```

Usage

```
{'create_GuardrailRequest': 'create a GuardrailRequest dataclass with tool name, input dict, agent id, and thread id for authorization context', 'create_GuardrailDecision': 'create a GuardrailDecision dataclass with allow boolean, reasons list, and optional policy id for provider verdicts', 'create_GuardrailReason': 'create a GuardrailReason dataclass with a code string and optional message for structured allow/deny reasons', 'build_GuardrailProvider': 'build a pluggable GuardrailProvider protocol implementing evaluate and aevaluate methods for tool-call authorization', 'test_GuardrailProvider': 'test the GuardrailProvider protocol and its dataclasses for pre-tool-call authorization decisions'}
```

