# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/serve/fgserve.py

Prompts

```
['run the FGServe Flask server for chat completions via CLI with argparse and config file', 'start the FGServe generation loop with ImpGen and performance logging on a given port', 'start a Flask server that handles OpenAI-compatible chat completion requests with tool support', 'start a Flask server that handles text completion requests with tokenized or raw prompt input', 'convert a ChatMessage with tool calls into a CWMChatMessage for model prompt encoding', 'create a ChatCompletionRequest with messages, tools, temperature, and max_tokens for an OpenAI-compatible API call', 'build a ChatCompletionResponse with choices, usage stats, and model info for returning OpenAI-compatible results', 'convert a ChatCompletionResponse into a ChatCompletionStreamResponse using the from_chat static method', 'define a ToolInfo with a FunctionDefinition including name, description, and JSON parameters for function calling', 'parse a ChatMessage with role, content, reasoning_content, and tool_calls including the content_str property', 'parse a model response string to extract tool call blocks and return structured ToolCall objects', 'format a list of ToolCall objects into the XML-like tool block string the model understands', 'prepare a system prompt message describing available tools and return the corresponding Tool objects list', 'parse a bash command from a tool block string into a ToolCall and format it back to XML', 'parse a SEARCH/REPLACE edit block into a ToolCall with path, old string, and new string parameters']
```

Usage

```
{'run_fgserve_cli': 'run the FGServe Flask server for chat completions via CLI with argparse and config file', 'serve_FGServeArgs': 'start the FGServe generation loop with ImpGen and performance logging on a given port', 'start_flask_server_chat_completions': 'start a Flask server that handles OpenAI-compatible chat completion requests with tool support', 'start_flask_server_text_completions': 'start a Flask server that handles text completion requests with tokenized or raw prompt input', 'convert_to_cwm_message': 'convert a ChatMessage with tool calls into a CWMChatMessage for model prompt encoding'}
```

## File: facebookresearch_cwm/serve/openai_api.py

Prompts

```
['run the FGServe Flask server for chat completions via CLI with argparse and config file', 'start the FGServe generation loop with ImpGen and performance logging on a given port', 'start a Flask server that handles OpenAI-compatible chat completion requests with tool support', 'start a Flask server that handles text completion requests with tokenized or raw prompt input', 'convert a ChatMessage with tool calls into a CWMChatMessage for model prompt encoding', 'create a ChatCompletionRequest with messages, tools, temperature, and max_tokens for an OpenAI-compatible API call', 'build a ChatCompletionResponse with choices, usage stats, and model info for returning OpenAI-compatible results', 'convert a ChatCompletionResponse into a ChatCompletionStreamResponse using the from_chat static method', 'define a ToolInfo with a FunctionDefinition including name, description, and JSON parameters for function calling', 'parse a ChatMessage with role, content, reasoning_content, and tool_calls including the content_str property', 'parse a model response string to extract tool call blocks and return structured ToolCall objects', 'format a list of ToolCall objects into the XML-like tool block string the model understands', 'prepare a system prompt message describing available tools and return the corresponding Tool objects list', 'parse a bash command from a tool block string into a ToolCall and format it back to XML', 'parse a SEARCH/REPLACE edit block into a ToolCall with path, old string, and new string parameters']
```

Usage

```
{'create_chat_completion_request': 'create a ChatCompletionRequest with messages, tools, temperature, and max_tokens for an OpenAI-compatible API call', 'build_chat_completion_response': 'build a ChatCompletionResponse with choices, usage stats, and model info for returning OpenAI-compatible results', 'convert_response_to_stream': 'convert a ChatCompletionResponse into a ChatCompletionStreamResponse using the from_chat static method', 'define_tool_info_schema': 'define a ToolInfo with a FunctionDefinition including name, description, and JSON parameters for function calling', 'parse_chat_message': 'parse a ChatMessage with role, content, reasoning_content, and tool_calls including the content_str property'}
```

## File: facebookresearch_cwm/serve/tools.py

Prompts

```
['run the FGServe Flask server for chat completions via CLI with argparse and config file', 'start the FGServe generation loop with ImpGen and performance logging on a given port', 'start a Flask server that handles OpenAI-compatible chat completion requests with tool support', 'start a Flask server that handles text completion requests with tokenized or raw prompt input', 'convert a ChatMessage with tool calls into a CWMChatMessage for model prompt encoding', 'create a ChatCompletionRequest with messages, tools, temperature, and max_tokens for an OpenAI-compatible API call', 'build a ChatCompletionResponse with choices, usage stats, and model info for returning OpenAI-compatible results', 'convert a ChatCompletionResponse into a ChatCompletionStreamResponse using the from_chat static method', 'define a ToolInfo with a FunctionDefinition including name, description, and JSON parameters for function calling', 'parse a ChatMessage with role, content, reasoning_content, and tool_calls including the content_str property', 'parse a model response string to extract tool call blocks and return structured ToolCall objects', 'format a list of ToolCall objects into the XML-like tool block string the model understands', 'prepare a system prompt message describing available tools and return the corresponding Tool objects list', 'parse a bash command from a tool block string into a ToolCall and format it back to XML', 'parse a SEARCH/REPLACE edit block into a ToolCall with path, old string, and new string parameters']
```

Usage

```
{'parse_tool_calls_from_model_response': 'parse a model response string to extract tool call blocks and return structured ToolCall objects', 'format_tool_calls_for_model': 'format a list of ToolCall objects into the XML-like tool block string the model understands', 'prepare_tools_system_prompt': 'prepare a system prompt message describing available tools and return the corresponding Tool objects list', 'run_bashtool_parse_and_format': 'parse a bash command from a tool block string into a ToolCall and format it back to XML', 'run_edittool_search_replace': 'parse a SEARCH/REPLACE edit block into a ToolCall with path, old string, and new string parameters'}
```

