# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/parser/harmony_utils.py

Prompts

```
['create a Harmony system message with model identity, reasoning effort, and tool descriptions', 'parse Chat Completion API messages into Harmony Message objects for the GPT-OSS model', 'parse Harmony model output token IDs into reasoning and final content strings', 'render a list of Harmony messages into token IDs for model completion', 'create a ToolDescription from a ChatCompletionToolsParam or OpenAI Tool object', 'create a ResponsesParser instance with tokenizer, reasoning parser, response messages, request, and optional tool parser', 'run the ResponsesParser process method to extract reasoning, tool calls, and text content from completion output', 'build ResponseOutputItem list from parsed context by converting function calls and tool outputs into proper response items', 'create a ResponsesParser via the get_responses_parser_for_simple_context factory function with optional reasoning and tool parsers', 'test the ResponsesParser extracts reasoning summaries, function tool calls, and assistant text from completion output']
```

Usage

```
{'create_harmony_system_message': 'create a Harmony system message with model identity, reasoning effort, and tool descriptions', 'parse_chat_inputs_to_harmony_messages': 'parse Chat Completion API messages into Harmony Message objects for the GPT-OSS model', 'parse_chat_output': 'parse Harmony model output token IDs into reasoning and final content strings', 'render_for_completion': 'render a list of Harmony messages into token IDs for model completion', 'create_tool_definition': 'create a ToolDescription from a ChatCompletionToolsParam or OpenAI Tool object'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/parser/responses_parser.py

Prompts

```
['create a Harmony system message with model identity, reasoning effort, and tool descriptions', 'parse Chat Completion API messages into Harmony Message objects for the GPT-OSS model', 'parse Harmony model output token IDs into reasoning and final content strings', 'render a list of Harmony messages into token IDs for model completion', 'create a ToolDescription from a ChatCompletionToolsParam or OpenAI Tool object', 'create a ResponsesParser instance with tokenizer, reasoning parser, response messages, request, and optional tool parser', 'run the ResponsesParser process method to extract reasoning, tool calls, and text content from completion output', 'build ResponseOutputItem list from parsed context by converting function calls and tool outputs into proper response items', 'create a ResponsesParser via the get_responses_parser_for_simple_context factory function with optional reasoning and tool parsers', 'test the ResponsesParser extracts reasoning summaries, function tool calls, and assistant text from completion output']
```

Usage

```
{'create_ResponsesParser': 'create a ResponsesParser instance with tokenizer, reasoning parser, response messages, request, and optional tool parser', 'run_ResponsesParser_process': 'run the ResponsesParser process method to extract reasoning, tool calls, and text content from completion output', 'build_responses_output_items': 'build ResponseOutputItem list from parsed context by converting function calls and tool outputs into proper response items', 'create_get_responses_parser_factory': 'create a ResponsesParser via the get_responses_parser_for_simple_context factory function with optional reasoning and tool parsers', 'test_ResponsesParser_reasoning_tool_extraction': 'test the ResponsesParser extracts reasoning summaries, function tool calls, and assistant text from completion output'}
```

