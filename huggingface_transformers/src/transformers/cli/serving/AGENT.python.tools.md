# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/cli/serving/model_manager.py

Prompts

```
['create a ModelManager instance to load, cache, and manage the lifecycle of HuggingFace models', 'load a model and processor from HuggingFace cache or download them with optional progress callbacks', 'load a model and stream progress updates as SSE events for multiple subscribers', 'detect whether a loaded model is an LLM, VLM, or multimodal model based on its architecture', 'list generative models (LLMs and VLMs) available in the HuggingFace cache directory', 'create a ResponseHandler that streams SSE responses for the /v1/responses endpoint', 'build a generation config by applying max_output_tokens and other Responses API params on top of the base model config', 'compute token usage statistics including input, output, and total tokens with detail fields', 'convert Responses API input (string, flat content list, or messages list) into a standardized chat messages format', 'stream generated tokens as SSE events with delta updates, tool call parsing, and completion events', 'build a FastAPI app factory that serves chat completions, responses, and audio transcription endpoints', 'create a /v1/chat/completions endpoint that handles OpenAI-compatible chat completion requests', 'create a /v1/audio/transcriptions endpoint for processing audio transcription requests', 'test the /load_model endpoint that streams model loading progress via Server-Sent Events', 'summarize the /health and /v1/models endpoints for checking server status and listing loaded models', 'parse tool calls from complete model output text using start and end delimiter tokens', 'stream tool calls incrementally from model output using the ToolCallParser feed method', 'detect the tool call token format for a pretrained model based on its architecture name', 'convert OpenAI-format chat messages to processor-compatible inputs for a given modality', 'format a string or pydantic model chunk as an SSE data line']
```

Usage

```
{'create_model_manager': 'create a ModelManager instance to load, cache, and manage the lifecycle of HuggingFace models', 'load_model_and_processor': 'load a model and processor from HuggingFace cache or download them with optional progress callbacks', 'load_model_streaming': 'load a model and stream progress updates as SSE events for multiple subscribers', 'get_model_modality': 'detect whether a loaded model is an LLM, VLM, or multimodal model based on its architecture', 'get_gen_models': 'list generative models (LLMs and VLMs) available in the HuggingFace cache directory'}
```

## File: huggingface_transformers/src/transformers/cli/serving/response.py

Prompts

```
['create a ModelManager instance to load, cache, and manage the lifecycle of HuggingFace models', 'load a model and processor from HuggingFace cache or download them with optional progress callbacks', 'load a model and stream progress updates as SSE events for multiple subscribers', 'detect whether a loaded model is an LLM, VLM, or multimodal model based on its architecture', 'list generative models (LLMs and VLMs) available in the HuggingFace cache directory', 'create a ResponseHandler that streams SSE responses for the /v1/responses endpoint', 'build a generation config by applying max_output_tokens and other Responses API params on top of the base model config', 'compute token usage statistics including input, output, and total tokens with detail fields', 'convert Responses API input (string, flat content list, or messages list) into a standardized chat messages format', 'stream generated tokens as SSE events with delta updates, tool call parsing, and completion events', 'build a FastAPI app factory that serves chat completions, responses, and audio transcription endpoints', 'create a /v1/chat/completions endpoint that handles OpenAI-compatible chat completion requests', 'create a /v1/audio/transcriptions endpoint for processing audio transcription requests', 'test the /load_model endpoint that streams model loading progress via Server-Sent Events', 'summarize the /health and /v1/models endpoints for checking server status and listing loaded models', 'parse tool calls from complete model output text using start and end delimiter tokens', 'stream tool calls incrementally from model output using the ToolCallParser feed method', 'detect the tool call token format for a pretrained model based on its architecture name', 'convert OpenAI-format chat messages to processor-compatible inputs for a given modality', 'format a string or pydantic model chunk as an SSE data line']
```

Usage

```
{'create_response_handler_streaming': 'create a ResponseHandler that streams SSE responses for the /v1/responses endpoint', 'build_generation_config': 'build a generation config by applying max_output_tokens and other Responses API params on top of the base model config', 'compute_usage': 'compute token usage statistics including input, output, and total tokens with detail fields', 'convert_input_to_messages': 'convert Responses API input (string, flat content list, or messages list) into a standardized chat messages format', 'stream_tokens_sse': 'stream generated tokens as SSE events with delta updates, tool call parsing, and completion events'}
```

## File: huggingface_transformers/src/transformers/cli/serving/server.py

Prompts

```
['create a ModelManager instance to load, cache, and manage the lifecycle of HuggingFace models', 'load a model and processor from HuggingFace cache or download them with optional progress callbacks', 'load a model and stream progress updates as SSE events for multiple subscribers', 'detect whether a loaded model is an LLM, VLM, or multimodal model based on its architecture', 'list generative models (LLMs and VLMs) available in the HuggingFace cache directory', 'create a ResponseHandler that streams SSE responses for the /v1/responses endpoint', 'build a generation config by applying max_output_tokens and other Responses API params on top of the base model config', 'compute token usage statistics including input, output, and total tokens with detail fields', 'convert Responses API input (string, flat content list, or messages list) into a standardized chat messages format', 'stream generated tokens as SSE events with delta updates, tool call parsing, and completion events', 'build a FastAPI app factory that serves chat completions, responses, and audio transcription endpoints', 'create a /v1/chat/completions endpoint that handles OpenAI-compatible chat completion requests', 'create a /v1/audio/transcriptions endpoint for processing audio transcription requests', 'test the /load_model endpoint that streams model loading progress via Server-Sent Events', 'summarize the /health and /v1/models endpoints for checking server status and listing loaded models', 'parse tool calls from complete model output text using start and end delimiter tokens', 'stream tool calls incrementally from model output using the ToolCallParser feed method', 'detect the tool call token format for a pretrained model based on its architecture name', 'convert OpenAI-format chat messages to processor-compatible inputs for a given modality', 'format a string or pydantic model chunk as an SSE data line']
```

Usage

```
{'build_server_fastapi_app': 'build a FastAPI app factory that serves chat completions, responses, and audio transcription endpoints', 'create_chat_completions_handler': 'create a /v1/chat/completions endpoint that handles OpenAI-compatible chat completion requests', 'create_audio_transcription_handler': 'create a /v1/audio/transcriptions endpoint for processing audio transcription requests', 'test_load_model_streaming': 'test the /load_model endpoint that streams model loading progress via Server-Sent Events', 'summarize_health_and_models': 'summarize the /health and /v1/models endpoints for checking server status and listing loaded models'}
```

## File: huggingface_transformers/src/transformers/cli/serving/utils.py

Prompts

```
['create a ModelManager instance to load, cache, and manage the lifecycle of HuggingFace models', 'load a model and processor from HuggingFace cache or download them with optional progress callbacks', 'load a model and stream progress updates as SSE events for multiple subscribers', 'detect whether a loaded model is an LLM, VLM, or multimodal model based on its architecture', 'list generative models (LLMs and VLMs) available in the HuggingFace cache directory', 'create a ResponseHandler that streams SSE responses for the /v1/responses endpoint', 'build a generation config by applying max_output_tokens and other Responses API params on top of the base model config', 'compute token usage statistics including input, output, and total tokens with detail fields', 'convert Responses API input (string, flat content list, or messages list) into a standardized chat messages format', 'stream generated tokens as SSE events with delta updates, tool call parsing, and completion events', 'build a FastAPI app factory that serves chat completions, responses, and audio transcription endpoints', 'create a /v1/chat/completions endpoint that handles OpenAI-compatible chat completion requests', 'create a /v1/audio/transcriptions endpoint for processing audio transcription requests', 'test the /load_model endpoint that streams model loading progress via Server-Sent Events', 'summarize the /health and /v1/models endpoints for checking server status and listing loaded models', 'parse tool calls from complete model output text using start and end delimiter tokens', 'stream tool calls incrementally from model output using the ToolCallParser feed method', 'detect the tool call token format for a pretrained model based on its architecture name', 'convert OpenAI-format chat messages to processor-compatible inputs for a given modality', 'format a string or pydantic model chunk as an SSE data line']
```

Usage

```
{'parse_tool_calls_from_model_output': 'parse tool calls from complete model output text using start and end delimiter tokens', 'stream_tool_calls_with_parser': 'stream tool calls incrementally from model output using the ToolCallParser feed method', 'detect_tool_call_format': 'detect the tool call token format for a pretrained model based on its architecture name', 'convert_messages_to_processor_inputs': 'convert OpenAI-format chat messages to processor-compatible inputs for a given modality', 'format_chunk_as_sse_event': 'format a string or pydantic model chunk as an SSE data line'}
```

