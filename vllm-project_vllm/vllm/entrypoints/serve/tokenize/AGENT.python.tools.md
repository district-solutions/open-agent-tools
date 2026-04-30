# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/tokenize/api_router.py

Prompts

```
['build a python module to run a fastapi server with /tokenize and /detokenize endpoints for tokenizing and detokenizing text', 'create a POST endpoint that tokenizes input text and returns token IDs using the vLLM tokenizer', 'create a POST endpoint that detokenizes token IDs back into text using the vLLM tokenizer', 'create a GET endpoint that returns comprehensive tokenizer information from the vLLM model', 'run attach_router to conditionally register the tokenizer info endpoint and attach the router to a FastAPI app', 'create a TokenizeCompletionRequest with a prompt string and optional special tokens flag', 'create a TokenizeChatRequest with chat messages and optional generation prompt settings', 'build TokenizeParams from a TokenizeCompletionRequest given a ModelConfig', 'build ChatParams from a TokenizeChatRequest with a default template and content format', 'build TokenizeParams from a TokenizeChatRequest given a ModelConfig', 'build TokenizeParams from a DetokenizeRequest with detokenization enabled', 'validate that TokenizeChatRequest does not set both continue_final_message and add_generation_prompt to true', 'create tokenize API that converts text prompts or chat messages into token IDs for vLLM models', 'create detokenize API that converts token IDs back into human-readable text prompts', 'create get tokenizer info API that returns tokenizer configuration and chat template settings', 'build TokenizerInfo dataclass that extracts and serializes tokenizer configuration to JSON', 'review OpenAIServingTokenization class that extends OpenAIServing with tokenize and detokenize endpoints']
```

Usage

```
{'build_restapi_tokenize': 'build a python module to run a fastapi server with /tokenize and /detokenize endpoints for tokenizing and detokenizing text', 'create_endpoint_tokenize': 'create a POST endpoint that tokenizes input text and returns token IDs using the vLLM tokenizer', 'create_endpoint_detokenize': 'create a POST endpoint that detokenizes token IDs back into text using the vLLM tokenizer', 'create_endpoint_tokenizer_info': 'create a GET endpoint that returns comprehensive tokenizer information from the vLLM model', 'run_attach_router': 'run attach_router to conditionally register the tokenizer info endpoint and attach the router to a FastAPI app'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/tokenize/protocol.py

Prompts

```
['build a python module to run a fastapi server with /tokenize and /detokenize endpoints for tokenizing and detokenizing text', 'create a POST endpoint that tokenizes input text and returns token IDs using the vLLM tokenizer', 'create a POST endpoint that detokenizes token IDs back into text using the vLLM tokenizer', 'create a GET endpoint that returns comprehensive tokenizer information from the vLLM model', 'run attach_router to conditionally register the tokenizer info endpoint and attach the router to a FastAPI app', 'create a TokenizeCompletionRequest with a prompt string and optional special tokens flag', 'create a TokenizeChatRequest with chat messages and optional generation prompt settings', 'build TokenizeParams from a TokenizeCompletionRequest given a ModelConfig', 'build ChatParams from a TokenizeChatRequest with a default template and content format', 'build TokenizeParams from a TokenizeChatRequest given a ModelConfig', 'build TokenizeParams from a DetokenizeRequest with detokenization enabled', 'validate that TokenizeChatRequest does not set both continue_final_message and add_generation_prompt to true', 'create tokenize API that converts text prompts or chat messages into token IDs for vLLM models', 'create detokenize API that converts token IDs back into human-readable text prompts', 'create get tokenizer info API that returns tokenizer configuration and chat template settings', 'build TokenizerInfo dataclass that extracts and serializes tokenizer configuration to JSON', 'review OpenAIServingTokenization class that extends OpenAIServing with tokenize and detokenize endpoints']
```

Usage

```
{'create_TokenizeCompletionRequest': 'create a TokenizeCompletionRequest with a prompt string and optional special tokens flag', 'create_TokenizeChatRequest': 'create a TokenizeChatRequest with chat messages and optional generation prompt settings', 'build_TokenizeCompletionRequest_build_tok_params': 'build TokenizeParams from a TokenizeCompletionRequest given a ModelConfig', 'build_TokenizeChatRequest_build_chat_params': 'build ChatParams from a TokenizeChatRequest with a default template and content format', 'build_TokenizeChatRequest_build_tok_params': 'build TokenizeParams from a TokenizeChatRequest given a ModelConfig', 'build_DetokenizeRequest_build_tok_params': 'build TokenizeParams from a DetokenizeRequest with detokenization enabled', 'validate_TokenizeChatRequest_continue_final_message': 'validate that TokenizeChatRequest does not set both continue_final_message and add_generation_prompt to true'}
```

## File: vllm-project_vllm/vllm/entrypoints/serve/tokenize/serving.py

Prompts

```
['build a python module to run a fastapi server with /tokenize and /detokenize endpoints for tokenizing and detokenizing text', 'create a POST endpoint that tokenizes input text and returns token IDs using the vLLM tokenizer', 'create a POST endpoint that detokenizes token IDs back into text using the vLLM tokenizer', 'create a GET endpoint that returns comprehensive tokenizer information from the vLLM model', 'run attach_router to conditionally register the tokenizer info endpoint and attach the router to a FastAPI app', 'create a TokenizeCompletionRequest with a prompt string and optional special tokens flag', 'create a TokenizeChatRequest with chat messages and optional generation prompt settings', 'build TokenizeParams from a TokenizeCompletionRequest given a ModelConfig', 'build ChatParams from a TokenizeChatRequest with a default template and content format', 'build TokenizeParams from a TokenizeChatRequest given a ModelConfig', 'build TokenizeParams from a DetokenizeRequest with detokenization enabled', 'validate that TokenizeChatRequest does not set both continue_final_message and add_generation_prompt to true', 'create tokenize API that converts text prompts or chat messages into token IDs for vLLM models', 'create detokenize API that converts token IDs back into human-readable text prompts', 'create get tokenizer info API that returns tokenizer configuration and chat template settings', 'build TokenizerInfo dataclass that extracts and serializes tokenizer configuration to JSON', 'review OpenAIServingTokenization class that extends OpenAIServing with tokenize and detokenize endpoints']
```

Usage

```
{'create_tokenize': 'create tokenize API that converts text prompts or chat messages into token IDs for vLLM models', 'create_detokenize': 'create detokenize API that converts token IDs back into human-readable text prompts', 'create_get_tokenizer_info': 'create get tokenizer info API that returns tokenizer configuration and chat template settings', 'build_tokenizer_info': 'build TokenizerInfo dataclass that extracts and serializes tokenizer configuration to JSON', 'review_openaiservingtokenization': 'review OpenAIServingTokenization class that extends OpenAIServing with tokenize and detokenize endpoints'}
```

