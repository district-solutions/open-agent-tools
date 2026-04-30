# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/parser/abstract_parser.py

Prompts

```
['create a Parser instance with a tokenizer to unify reasoning and tool call extraction from model outputs', 'build a DelegatingParser that delegates reasoning and tool call parsing to separate parser instances', 'test parse_delta to extract reasoning and tool calls from streaming model output deltas', 'extract response outputs as ResponseOutputItem objects from a complete model-generated string', 'wrap ReasoningParser and ToolParser classes into a _WrappedParser via class attributes', 'register a Parser subclass with the ParserManager registry using eager or decorator mode', 'register a lazily loaded Parser class by module path and class name', 'get a unified Parser that handles both reasoning extraction and tool call parsing', 'get a ToolParser class by name with optional auto-tool-choice and model name support', 'list all registered parser names from both eager and lazy registries']
```

Usage

```
{'create_parser': 'create a Parser instance with a tokenizer to unify reasoning and tool call extraction from model outputs', 'build_delegating_parser': 'build a DelegatingParser that delegates reasoning and tool call parsing to separate parser instances', 'test_parse_delta': 'test parse_delta to extract reasoning and tool calls from streaming model output deltas', 'extract_response_outputs': 'extract response outputs as ResponseOutputItem objects from a complete model-generated string', 'wrap_parser_classes': 'wrap ReasoningParser and ToolParser classes into a _WrappedParser via class attributes'}
```

## File: vllm-project_vllm/vllm/parser/parser_manager.py

Prompts

```
['create a Parser instance with a tokenizer to unify reasoning and tool call extraction from model outputs', 'build a DelegatingParser that delegates reasoning and tool call parsing to separate parser instances', 'test parse_delta to extract reasoning and tool calls from streaming model output deltas', 'extract response outputs as ResponseOutputItem objects from a complete model-generated string', 'wrap ReasoningParser and ToolParser classes into a _WrappedParser via class attributes', 'register a Parser subclass with the ParserManager registry using eager or decorator mode', 'register a lazily loaded Parser class by module path and class name', 'get a unified Parser that handles both reasoning extraction and tool call parsing', 'get a ToolParser class by name with optional auto-tool-choice and model name support', 'list all registered parser names from both eager and lazy registries']
```

Usage

```
{'register_parser_module': 'register a Parser subclass with the ParserManager registry using eager or decorator mode', 'register_lazy_parser_module': 'register a lazily loaded Parser class by module path and class name', 'get_unified_parser': 'get a unified Parser that handles both reasoning extraction and tool call parsing', 'get_tool_parser': 'get a ToolParser class by name with optional auto-tool-choice and model name support', 'list_registered_parsers': 'list all registered parser names from both eager and lazy registries'}
```

