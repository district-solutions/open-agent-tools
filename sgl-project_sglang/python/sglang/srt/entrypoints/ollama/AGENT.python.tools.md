# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/entrypoints/ollama/serving.py

Prompts

```
['handle an Ollama-compatible chat request and return streaming or non-streaming responses', 'handle an Ollama-compatible generate request with optional system prompt and streaming support', 'get a list of available Ollama models from the SGLang tokenizer manager', 'get detailed Ollama model information including context length and architecture details', 'convert Ollama API options like temperature and top_p into SGLang sampling parameters', 'create a SmartRouter instance routing simple tasks to local Ollama and complex tasks to remote SGLang', 'run the SmartRouter chat method to route a prompt through local Ollama or remote SGLang and return the response', 'run the SmartRouter chat_stream method to route a prompt and stream response chunks from the selected model', 'test the SmartRouter should_use_remote method to determine if a prompt should route to remote SGLang', 'review the SmartRouter _classify_with_llm method that uses an LLM judge to classify prompts as SIMPLE or COMPLEX']
```

Usage

```
{'handle_chat': 'handle an Ollama-compatible chat request and return streaming or non-streaming responses', 'handle_generate': 'handle an Ollama-compatible generate request with optional system prompt and streaming support', 'get_tags': 'get a list of available Ollama models from the SGLang tokenizer manager', 'get_show': 'get detailed Ollama model information including context length and architecture details', 'convert_options_to_sampling_params': 'convert Ollama API options like temperature and top_p into SGLang sampling parameters'}
```

## File: sgl-project_sglang/python/sglang/srt/entrypoints/ollama/smart_router.py

Prompts

```
['handle an Ollama-compatible chat request and return streaming or non-streaming responses', 'handle an Ollama-compatible generate request with optional system prompt and streaming support', 'get a list of available Ollama models from the SGLang tokenizer manager', 'get detailed Ollama model information including context length and architecture details', 'convert Ollama API options like temperature and top_p into SGLang sampling parameters', 'create a SmartRouter instance routing simple tasks to local Ollama and complex tasks to remote SGLang', 'run the SmartRouter chat method to route a prompt through local Ollama or remote SGLang and return the response', 'run the SmartRouter chat_stream method to route a prompt and stream response chunks from the selected model', 'test the SmartRouter should_use_remote method to determine if a prompt should route to remote SGLang', 'review the SmartRouter _classify_with_llm method that uses an LLM judge to classify prompts as SIMPLE or COMPLEX']
```

Usage

```
{'create_smart_router': 'create a SmartRouter instance routing simple tasks to local Ollama and complex tasks to remote SGLang', 'run_smart_router_chat': 'run the SmartRouter chat method to route a prompt through local Ollama or remote SGLang and return the response', 'run_smart_router_chat_stream': 'run the SmartRouter chat_stream method to route a prompt and stream response chunks from the selected model', 'test_smart_router_should_use_remote': 'test the SmartRouter should_use_remote method to determine if a prompt should route to remote SGLang', 'review_smart_router_classify_with_llm': 'review the SmartRouter _classify_with_llm method that uses an LLM judge to classify prompts as SIMPLE or COMPLEX'}
```

