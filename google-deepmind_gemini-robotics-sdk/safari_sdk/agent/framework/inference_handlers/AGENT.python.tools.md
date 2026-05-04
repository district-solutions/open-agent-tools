# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/inference_handlers/live_handler.py

Prompts

```
['create a GeminiLiveAPIHandler instance with an event bus, framework config, live config, and camera names', 'connect the GeminiLiveAPIHandler to establish a Gemini Live API session in a background task', 'disconnect the GeminiLiveAPIHandler to cleanly shut down the Live API session and cancel all tasks', 'prepare a list of image Part objects from camera blobs with optional stitching and labels', 'handle a GO_AWAY server event by counting down then reconnecting with session resumption if available', 'implement a subclass of NonStreamingHandler to handle turn-based inference with retry logic and image buffering', 'use is_retriable_exception to check if a gRPC or API exception should trigger a retry', 'use client_init_with_retries to wrap a synchronous client creation function with exponential backoff', 'use the _retry_wrapper method to wrap an async generate function with exponential backoff retry logic', 'use _collect_images_for_fr to gather camera images captured between a function call and its response', 'build a UnaryGenAIHandler instance with an event bus, config, system instructions, and tool definitions', 'connect the UnaryGenAIHandler to activate it, run bootup test, and publish session metadata', 'generate a model response from user text with buffered images and tool call handling', 'handle Gemini function calls by publishing events, waiting for results, and updating conversation history', 'clear the conversation history and reset the UnaryGenAIHandler state']
```

Usage

```
{'create_gemini_live_api_handler': 'create a GeminiLiveAPIHandler instance with an event bus, framework config, live config, and camera names', 'connect_gemini_live_session': 'connect the GeminiLiveAPIHandler to establish a Gemini Live API session in a background task', 'disconnect_gemini_live_session': 'disconnect the GeminiLiveAPIHandler to cleanly shut down the Live API session and cancel all tasks', 'prepare_image_parts_for_agent': 'prepare a list of image Part objects from camera blobs with optional stitching and labels', 'handle_go_away_and_reconnect': 'handle a GO_AWAY server event by counting down then reconnecting with session resumption if available'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/inference_handlers/nonstreaming_handler.py

Prompts

```
['create a GeminiLiveAPIHandler instance with an event bus, framework config, live config, and camera names', 'connect the GeminiLiveAPIHandler to establish a Gemini Live API session in a background task', 'disconnect the GeminiLiveAPIHandler to cleanly shut down the Live API session and cancel all tasks', 'prepare a list of image Part objects from camera blobs with optional stitching and labels', 'handle a GO_AWAY server event by counting down then reconnecting with session resumption if available', 'implement a subclass of NonStreamingHandler to handle turn-based inference with retry logic and image buffering', 'use is_retriable_exception to check if a gRPC or API exception should trigger a retry', 'use client_init_with_retries to wrap a synchronous client creation function with exponential backoff', 'use the _retry_wrapper method to wrap an async generate function with exponential backoff retry logic', 'use _collect_images_for_fr to gather camera images captured between a function call and its response', 'build a UnaryGenAIHandler instance with an event bus, config, system instructions, and tool definitions', 'connect the UnaryGenAIHandler to activate it, run bootup test, and publish session metadata', 'generate a model response from user text with buffered images and tool call handling', 'handle Gemini function calls by publishing events, waiting for results, and updating conversation history', 'clear the conversation history and reset the UnaryGenAIHandler state']
```

Usage

```
{'implement_nonstreaming_handler_subclass': 'implement a subclass of NonStreamingHandler to handle turn-based inference with retry logic and image buffering', 'use_is_retriable_exception': 'use is_retriable_exception to check if a gRPC or API exception should trigger a retry', 'use_client_init_with_retries': 'use client_init_with_retries to wrap a synchronous client creation function with exponential backoff', 'use_retry_wrapper': 'use the _retry_wrapper method to wrap an async generate function with exponential backoff retry logic', 'use_collect_images_for_fr': 'use _collect_images_for_fr to gather camera images captured between a function call and its response'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/inference_handlers/unary_genai_handler.py

Prompts

```
['create a GeminiLiveAPIHandler instance with an event bus, framework config, live config, and camera names', 'connect the GeminiLiveAPIHandler to establish a Gemini Live API session in a background task', 'disconnect the GeminiLiveAPIHandler to cleanly shut down the Live API session and cancel all tasks', 'prepare a list of image Part objects from camera blobs with optional stitching and labels', 'handle a GO_AWAY server event by counting down then reconnecting with session resumption if available', 'implement a subclass of NonStreamingHandler to handle turn-based inference with retry logic and image buffering', 'use is_retriable_exception to check if a gRPC or API exception should trigger a retry', 'use client_init_with_retries to wrap a synchronous client creation function with exponential backoff', 'use the _retry_wrapper method to wrap an async generate function with exponential backoff retry logic', 'use _collect_images_for_fr to gather camera images captured between a function call and its response', 'build a UnaryGenAIHandler instance with an event bus, config, system instructions, and tool definitions', 'connect the UnaryGenAIHandler to activate it, run bootup test, and publish session metadata', 'generate a model response from user text with buffered images and tool call handling', 'handle Gemini function calls by publishing events, waiting for results, and updating conversation history', 'clear the conversation history and reset the UnaryGenAIHandler state']
```

Usage

```
{'build_unary_genai_handler': 'build a UnaryGenAIHandler instance with an event bus, config, system instructions, and tool definitions', 'connect_handler': 'connect the UnaryGenAIHandler to activate it, run bootup test, and publish session metadata', 'generate_response': 'generate a model response from user text with buffered images and tool call handling', 'handle_tool_calls': 'handle Gemini function calls by publishing events, waiting for results, and updating conversation history', 'clear_conversation_history': 'clear the conversation history and reset the UnaryGenAIHandler state'}
```

