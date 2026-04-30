# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/codestral/completion/handler.py

Prompts

```
['build a codestral text completion call using the CodestralTextCompletion class with messages, model, and api_key parameters', 'test the async_completion method of CodestralTextCompletion to send a non-streaming request to the codestral api', 'review the async_streaming method of CodestralTextCompletion that returns a CustomStreamWrapper for streaming responses', 'refactor the output_parser method of CodestralTextCompletion to strip chatml template tokens from generated text', 'summarize the make_call async function that posts to the codestral api and returns a completion stream', 'create a CodestralTextCompletionConfig instance with suffix, temperature, and max_tokens parameters', 'map OpenAI completion parameters to Codestral-specific params like suffix, seed, and min_tokens', 'get the list of supported OpenAI params for a Codestral completion model', 'parse a Codestral SSE streaming chunk into a GenericStreamingChunk with text and finish_reason', 'get the base OpenAI text completion config from CodestralTextCompletionConfig']
```

Usage

```
{'build_codestral_completion': 'build a codestral text completion call using the CodestralTextCompletion class with messages, model, and api_key parameters', 'test_async_completion': 'test the async_completion method of CodestralTextCompletion to send a non-streaming request to the codestral api', 'review_async_streaming': 'review the async_streaming method of CodestralTextCompletion that returns a CustomStreamWrapper for streaming responses', 'refactor_output_parser': 'refactor the output_parser method of CodestralTextCompletion to strip chatml template tokens from generated text', 'summarize_make_call': 'summarize the make_call async function that posts to the codestral api and returns a completion stream'}
```

## File: berriai_litellm/litellm/llms/codestral/completion/transformation.py

Prompts

```
['build a codestral text completion call using the CodestralTextCompletion class with messages, model, and api_key parameters', 'test the async_completion method of CodestralTextCompletion to send a non-streaming request to the codestral api', 'review the async_streaming method of CodestralTextCompletion that returns a CustomStreamWrapper for streaming responses', 'refactor the output_parser method of CodestralTextCompletion to strip chatml template tokens from generated text', 'summarize the make_call async function that posts to the codestral api and returns a completion stream', 'create a CodestralTextCompletionConfig instance with suffix, temperature, and max_tokens parameters', 'map OpenAI completion parameters to Codestral-specific params like suffix, seed, and min_tokens', 'get the list of supported OpenAI params for a Codestral completion model', 'parse a Codestral SSE streaming chunk into a GenericStreamingChunk with text and finish_reason', 'get the base OpenAI text completion config from CodestralTextCompletionConfig']
```

Usage

```
{'create_CodestralTextCompletionConfig': 'create a CodestralTextCompletionConfig instance with suffix, temperature, and max_tokens parameters', 'map_openai_params_codestral': 'map OpenAI completion parameters to Codestral-specific params like suffix, seed, and min_tokens', 'get_supported_openai_params_codestral': 'get the list of supported OpenAI params for a Codestral completion model', 'parse_codestral_streaming_chunk': 'parse a Codestral SSE streaming chunk into a GenericStreamingChunk with text and finish_reason', 'get_config_codestral': 'get the base OpenAI text completion config from CodestralTextCompletionConfig'}
```

