# Agent Python Tools

- repo: lsdefine/GenericAgent
- repo_uri: https://github.com/lsdefine/GenericAgent

## File: lsdefine_GenericAgent/tests/test_minimax.py

Prompts

```
['test the MiniMax temperature clamping in _openai_stream to clamp zero and negative values to 0.01', 'test the _parse_mixed_response method to strip <think> tags from MiniMax M2.7 responses', 'test the compress_history_tags function to truncate <think> tags in old conversation messages', 'test the auto_make_url function to construct correct MiniMax API endpoint URLs', 'test NativeOAISession.ask and NativeToolClient.chat to extract <think> tags from MiniMax responses', 'test the MiniMax end-to-end streaming pipeline with thinking tags and content parsing', 'test the MiniMax response parsing for tool_use blocks with function name and arguments', 'build a mock SSE HTTP response from a list of text chunks with usage data', 'test live MiniMax API chat completion with real API key and streaming response']
```

Usage

```
{'test_minimax_temperature_clamping': 'test the MiniMax temperature clamping in _openai_stream to clamp zero and negative values to 0.01', 'test_think_tag_handling': 'test the _parse_mixed_response method to strip <think> tags from MiniMax M2.7 responses', 'test_history_tag_compression': 'test the compress_history_tags function to truncate <think> tags in old conversation messages', 'test_auto_make_url': 'test the auto_make_url function to construct correct MiniMax API endpoint URLs', 'test_native_session_think_tag': 'test NativeOAISession.ask and NativeToolClient.chat to extract <think> tags from MiniMax responses'}
```

## File: lsdefine_GenericAgent/tests/test_minimax_integration.py

Prompts

```
['test the MiniMax temperature clamping in _openai_stream to clamp zero and negative values to 0.01', 'test the _parse_mixed_response method to strip <think> tags from MiniMax M2.7 responses', 'test the compress_history_tags function to truncate <think> tags in old conversation messages', 'test the auto_make_url function to construct correct MiniMax API endpoint URLs', 'test NativeOAISession.ask and NativeToolClient.chat to extract <think> tags from MiniMax responses', 'test the MiniMax end-to-end streaming pipeline with thinking tags and content parsing', 'test the MiniMax response parsing for tool_use blocks with function name and arguments', 'build a mock SSE HTTP response from a list of text chunks with usage data', 'test live MiniMax API chat completion with real API key and streaming response']
```

Usage

```
{'test_minimax_streaming_pipeline': 'test the MiniMax end-to-end streaming pipeline with thinking tags and content parsing', 'test_minimax_tool_call_parsing': 'test the MiniMax response parsing for tool_use blocks with function name and arguments', 'test_minimax_temperature_clamping': 'test that MiniMax HTTP requests enforce clamped temperature values in the request body', 'build_minimax_sse_mock_response': 'build a mock SSE HTTP response from a list of text chunks with usage data', 'test_minimax_live_chat_completion': 'test live MiniMax API chat completion with real API key and streaming response'}
```

