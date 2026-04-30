# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/interceptors/advisor.py

Prompts

```
['orchestrate the advisor tool loop for non-native LLM providers that do not support advisor_20260301 natively', 'build a synthetic advisor tool definition that a non-native provider can understand', 'find the first tool_use block named advisor in an executor response', 'inject an advisor result as a tool_result turn into the conversation history', 'build the message list for an advisor sub-call with conversation and question context', 'build a concrete MessagesInterceptor subclass that short-circuits Anthropic /messages API calls', 'test the MessagesInterceptor.can_handle method to verify it returns True for matching tool and provider patterns', 'test the MessagesInterceptor.handle async method to verify it returns an AnthropicMessagesResponse or AsyncIterator', 'refactor the MessagesInterceptor base class to support additional short-circuit interception patterns', 'review the MessagesInterceptor class and its abstract methods can_handle and handle for correctness']
```

Usage

```
{'orchestrate_advisor_tool_loop': 'orchestrate the advisor tool loop for non-native LLM providers that do not support advisor_20260301 natively', 'build_synthetic_advisor_tool': 'build a synthetic advisor tool definition that a non-native provider can understand', 'find_advisor_tool_use': 'find the first tool_use block named advisor in an executor response', 'inject_advisor_turn': 'inject an advisor result as a tool_result turn into the conversation history', 'build_advisor_context': 'build the message list for an advisor sub-call with conversation and question context'}
```

## File: berriai_litellm/litellm/llms/anthropic/experimental_pass_through/messages/interceptors/base.py

Prompts

```
['orchestrate the advisor tool loop for non-native LLM providers that do not support advisor_20260301 natively', 'build a synthetic advisor tool definition that a non-native provider can understand', 'find the first tool_use block named advisor in an executor response', 'inject an advisor result as a tool_result turn into the conversation history', 'build the message list for an advisor sub-call with conversation and question context', 'build a concrete MessagesInterceptor subclass that short-circuits Anthropic /messages API calls', 'test the MessagesInterceptor.can_handle method to verify it returns True for matching tool and provider patterns', 'test the MessagesInterceptor.handle async method to verify it returns an AnthropicMessagesResponse or AsyncIterator', 'refactor the MessagesInterceptor base class to support additional short-circuit interception patterns', 'review the MessagesInterceptor class and its abstract methods can_handle and handle for correctness']
```

Usage

```
{'build_MessagesInterceptor': 'build a concrete MessagesInterceptor subclass that short-circuits Anthropic /messages API calls', 'test_can_handle': 'test the MessagesInterceptor.can_handle method to verify it returns True for matching tool and provider patterns', 'test_handle': 'test the MessagesInterceptor.handle async method to verify it returns an AnthropicMessagesResponse or AsyncIterator', 'refactor_MessagesInterceptor': 'refactor the MessagesInterceptor base class to support additional short-circuit interception patterns', 'review_MessagesInterceptor': 'review the MessagesInterceptor class and its abstract methods can_handle and handle for correctness'}
```

