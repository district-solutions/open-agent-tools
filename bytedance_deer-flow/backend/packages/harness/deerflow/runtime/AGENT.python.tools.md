# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/converters.py

Prompts

```
['convert a LangChain BaseMessage object to an OpenAI chat completion message dict', 'convert a list of LangChain messages to OpenAI chat completion message dicts', 'convert a LangChain AIMessage to a full OpenAI completion response dict with usage metadata', 'infer the OpenAI finish_reason from a LangChain AIMessage based on tool calls or response metadata', 'review the converters module functions that translate LangChain messages to OpenAI wire format', 'create a RunJournal callback handler to capture LangChain run events and token usage', 'record a middleware state change event with tag, hook, action, and changes', 'flush all buffered events to the RunEventStore asynchronously', 'get accumulated token usage and message count data for run completion', 'review the RunJournal class event capture design and callback lifecycle methods', 'build a function that recursively serializes LangChain objects to JSON-serialisable Python structures', 'create a function that serializes LangGraph channel values and strips internal __pregel_* keys', 'test the function that serializes messages-mode tuples containing message chunks and metadata', 'summarize the main serialize function that dispatches to mode-specific serialization for messages or values', 'refactor the serialize_lc_object function to support additional Pydantic v3 model_dump_exclusion patterns', 'set the current authenticated user in the async task context for repository isolation', 'reset the current user context to its previous state using the stored token', 'get the current authenticated user from the context or return None if unset', 'require the current authenticated user from context or raise a RuntimeError if unset', 'get the current user id string or return the default user id for filesystem paths']
```

Usage

```
{'convert_langchain_to_openai_message': 'convert a LangChain BaseMessage object to an OpenAI chat completion message dict', 'convert_langchain_messages_to_openai': 'convert a list of LangChain messages to OpenAI chat completion message dicts', 'convert_langchain_to_openai_completion': 'convert a LangChain AIMessage to a full OpenAI completion response dict with usage metadata', 'infer_finish_reason': 'infer the OpenAI finish_reason from a LangChain AIMessage based on tool calls or response metadata', 'review_converters_module': 'review the converters module functions that translate LangChain messages to OpenAI wire format'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/journal.py

Prompts

```
['convert a LangChain BaseMessage object to an OpenAI chat completion message dict', 'convert a list of LangChain messages to OpenAI chat completion message dicts', 'convert a LangChain AIMessage to a full OpenAI completion response dict with usage metadata', 'infer the OpenAI finish_reason from a LangChain AIMessage based on tool calls or response metadata', 'review the converters module functions that translate LangChain messages to OpenAI wire format', 'create a RunJournal callback handler to capture LangChain run events and token usage', 'record a middleware state change event with tag, hook, action, and changes', 'flush all buffered events to the RunEventStore asynchronously', 'get accumulated token usage and message count data for run completion', 'review the RunJournal class event capture design and callback lifecycle methods', 'build a function that recursively serializes LangChain objects to JSON-serialisable Python structures', 'create a function that serializes LangGraph channel values and strips internal __pregel_* keys', 'test the function that serializes messages-mode tuples containing message chunks and metadata', 'summarize the main serialize function that dispatches to mode-specific serialization for messages or values', 'refactor the serialize_lc_object function to support additional Pydantic v3 model_dump_exclusion patterns', 'set the current authenticated user in the async task context for repository isolation', 'reset the current user context to its previous state using the stored token', 'get the current authenticated user from the context or return None if unset', 'require the current authenticated user from context or raise a RuntimeError if unset', 'get the current user id string or return the default user id for filesystem paths']
```

Usage

```
{'create_runjournal_callback_handler': 'create a RunJournal callback handler to capture LangChain run events and token usage', 'record_middleware_state_change': 'record a middleware state change event with tag, hook, action, and changes', 'flush_buffered_events': 'flush all buffered events to the RunEventStore asynchronously', 'get_completion_data': 'get accumulated token usage and message count data for run completion', 'review_runjournal_event_capture': 'review the RunJournal class event capture design and callback lifecycle methods'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/serialization.py

Prompts

```
['convert a LangChain BaseMessage object to an OpenAI chat completion message dict', 'convert a list of LangChain messages to OpenAI chat completion message dicts', 'convert a LangChain AIMessage to a full OpenAI completion response dict with usage metadata', 'infer the OpenAI finish_reason from a LangChain AIMessage based on tool calls or response metadata', 'review the converters module functions that translate LangChain messages to OpenAI wire format', 'create a RunJournal callback handler to capture LangChain run events and token usage', 'record a middleware state change event with tag, hook, action, and changes', 'flush all buffered events to the RunEventStore asynchronously', 'get accumulated token usage and message count data for run completion', 'review the RunJournal class event capture design and callback lifecycle methods', 'build a function that recursively serializes LangChain objects to JSON-serialisable Python structures', 'create a function that serializes LangGraph channel values and strips internal __pregel_* keys', 'test the function that serializes messages-mode tuples containing message chunks and metadata', 'summarize the main serialize function that dispatches to mode-specific serialization for messages or values', 'refactor the serialize_lc_object function to support additional Pydantic v3 model_dump_exclusion patterns', 'set the current authenticated user in the async task context for repository isolation', 'reset the current user context to its previous state using the stored token', 'get the current authenticated user from the context or return None if unset', 'require the current authenticated user from context or raise a RuntimeError if unset', 'get the current user id string or return the default user id for filesystem paths']
```

Usage

```
{'build_serialize_lc_object': 'build a function that recursively serializes LangChain objects to JSON-serialisable Python structures', 'create_serialize_channel_values': 'create a function that serializes LangGraph channel values and strips internal __pregel_* keys', 'test_serialize_messages_tuple': 'test the function that serializes messages-mode tuples containing message chunks and metadata', 'summarize_serialize': 'summarize the main serialize function that dispatches to mode-specific serialization for messages or values', 'refactor_serialize_lc_object': 'refactor the serialize_lc_object function to support additional Pydantic v3 model_dump_exclusion patterns'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/user_context.py

Prompts

```
['convert a LangChain BaseMessage object to an OpenAI chat completion message dict', 'convert a list of LangChain messages to OpenAI chat completion message dicts', 'convert a LangChain AIMessage to a full OpenAI completion response dict with usage metadata', 'infer the OpenAI finish_reason from a LangChain AIMessage based on tool calls or response metadata', 'review the converters module functions that translate LangChain messages to OpenAI wire format', 'create a RunJournal callback handler to capture LangChain run events and token usage', 'record a middleware state change event with tag, hook, action, and changes', 'flush all buffered events to the RunEventStore asynchronously', 'get accumulated token usage and message count data for run completion', 'review the RunJournal class event capture design and callback lifecycle methods', 'build a function that recursively serializes LangChain objects to JSON-serialisable Python structures', 'create a function that serializes LangGraph channel values and strips internal __pregel_* keys', 'test the function that serializes messages-mode tuples containing message chunks and metadata', 'summarize the main serialize function that dispatches to mode-specific serialization for messages or values', 'refactor the serialize_lc_object function to support additional Pydantic v3 model_dump_exclusion patterns', 'set the current authenticated user in the async task context for repository isolation', 'reset the current user context to its previous state using the stored token', 'get the current authenticated user from the context or return None if unset', 'require the current authenticated user from context or raise a RuntimeError if unset', 'get the current user id string or return the default user id for filesystem paths']
```

Usage

```
{'set_current_user': 'set the current authenticated user in the async task context for repository isolation', 'reset_current_user': 'reset the current user context to its previous state using the stored token', 'get_current_user': 'get the current authenticated user from the context or return None if unset', 'require_current_user': 'require the current authenticated user from context or raise a RuntimeError if unset', 'get_effective_user_id': 'get the current user id string or return the default user id for filesystem paths'}
```

