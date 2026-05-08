# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/text/datatypes.py

Prompts

```
['create a CWMChatMessage system message with a given body string using the system class method', 'create a CWMChatMessage user message with a given body string using the user class method', 'create a CWMChatMessage assistant message with an optional body string using the assistant class method', 'create a CWMChatMessage tool result with a body and tool name using the tool_result class method', 'create a CWMChatMessage from a dictionary representation using the from_dict class method', 'build a TikTokenTokenizer or CWMInstructTokenizer from a model path using build_tokenizer', 'encode a string into token ids with optional bos and eos tokens using Tokenizer.encode', 'decode a list of token ids back to text using Tokenizer.decode with stop token cutting', 'encode a list of chat messages into tokens using CWMInstructTokenizer.encode_prompt_dialog', 'encode a single chat message with header and end token using CWMInstructTokenizer.encode_message']
```

Usage

```
{'create_system_message': 'create a CWMChatMessage system message with a given body string using the system class method', 'create_user_message': 'create a CWMChatMessage user message with a given body string using the user class method', 'create_assistant_message': 'create a CWMChatMessage assistant message with an optional body string using the assistant class method', 'create_tool_result_message': 'create a CWMChatMessage tool result with a body and tool name using the tool_result class method', 'deserialize_message_from_dict': 'create a CWMChatMessage from a dictionary representation using the from_dict class method'}
```

## File: facebookresearch_cwm/cwm/text/tokenizers.py

Prompts

```
['create a CWMChatMessage system message with a given body string using the system class method', 'create a CWMChatMessage user message with a given body string using the user class method', 'create a CWMChatMessage assistant message with an optional body string using the assistant class method', 'create a CWMChatMessage tool result with a body and tool name using the tool_result class method', 'create a CWMChatMessage from a dictionary representation using the from_dict class method', 'build a TikTokenTokenizer or CWMInstructTokenizer from a model path using build_tokenizer', 'encode a string into token ids with optional bos and eos tokens using Tokenizer.encode', 'decode a list of token ids back to text using Tokenizer.decode with stop token cutting', 'encode a list of chat messages into tokens using CWMInstructTokenizer.encode_prompt_dialog', 'encode a single chat message with header and end token using CWMInstructTokenizer.encode_message']
```

Usage

```
{'build_tokenizer_from_path': 'build a TikTokenTokenizer or CWMInstructTokenizer from a model path using build_tokenizer', 'encode_text_to_tokens': 'encode a string into token ids with optional bos and eos tokens using Tokenizer.encode', 'decode_tokens_to_text': 'decode a list of token ids back to text using Tokenizer.decode with stop token cutting', 'encode_chat_dialog': 'encode a list of chat messages into tokens using CWMInstructTokenizer.encode_prompt_dialog', 'encode_single_message': 'encode a single chat message with header and end token using CWMInstructTokenizer.encode_message'}
```

