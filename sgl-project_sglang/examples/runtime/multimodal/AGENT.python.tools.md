# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/examples/runtime/multimodal/llama3_llava_server.py

Prompts

```
['send an async POST request to a URL with JSON data and optional delay', 'test concurrent requests to the multimodal server for image caption generation', 'test streaming responses from the multimodal server for image caption generation', 'normalize a host and port into a base URL string', 'build a conversation template for LLaVA-NeXT with Llama-3 chat format', 'download a video from a URL and save it to a local cache directory', 'create an OpenAI API client connected to a local SGLang server at the given base URL', 'test streaming image-based chat completions against an SGLang multimodal server', 'test streaming video-based chat completions by sampling frames and sending them to an SGLang server', 'prepare a list of video frames as base64-encoded image messages with a text prompt for an SGLang API call', 'test the async send_request function to POST generate requests to a Pixtral server endpoint', 'test the test_concurrent function to send single or multiple image generation requests to a Pixtral server', 'test the test_streaming function to receive streaming text responses from a Pixtral multimodal server', 'run the pixtral_server.py CLI module to test a Pixtral model with single or multiple images via argparse', 'build a test script that sends image generation requests to a running SGLang Pixtral server with configurable host and port', 'build a conversation template for Qwen with LLaVA-NeXT chat format']
```

Usage

```
{'send_request': 'send an async POST request to a URL with JSON data and optional delay', 'test_concurrent': 'test concurrent requests to the multimodal server for image caption generation', 'test_streaming': 'test streaming responses from the multimodal server for image caption generation', 'normalize_base_url': 'normalize a host and port into a base URL string', 'conv_llava_llama_3': 'build a conversation template for LLaVA-NeXT with Llama-3 chat format'}
```

## File: sgl-project_sglang/examples/runtime/multimodal/llava_onevision_server.py

Prompts

```
['send an async POST request to a URL with JSON data and optional delay', 'test concurrent requests to the multimodal server for image caption generation', 'test streaming responses from the multimodal server for image caption generation', 'normalize a host and port into a base URL string', 'build a conversation template for LLaVA-NeXT with Llama-3 chat format', 'download a video from a URL and save it to a local cache directory', 'create an OpenAI API client connected to a local SGLang server at the given base URL', 'test streaming image-based chat completions against an SGLang multimodal server', 'test streaming video-based chat completions by sampling frames and sending them to an SGLang server', 'prepare a list of video frames as base64-encoded image messages with a text prompt for an SGLang API call', 'test the async send_request function to POST generate requests to a Pixtral server endpoint', 'test the test_concurrent function to send single or multiple image generation requests to a Pixtral server', 'test the test_streaming function to receive streaming text responses from a Pixtral multimodal server', 'run the pixtral_server.py CLI module to test a Pixtral model with single or multiple images via argparse', 'build a test script that sends image generation requests to a running SGLang Pixtral server with configurable host and port', 'build a conversation template for Qwen with LLaVA-NeXT chat format']
```

Usage

```
{'download_video_url_cache_dir': 'download a video from a URL and save it to a local cache directory', 'create_openai_client_base_url': 'create an OpenAI API client connected to a local SGLang server at the given base URL', 'test_image_stream_request': 'test streaming image-based chat completions against an SGLang multimodal server', 'test_video_stream_request': 'test streaming video-based chat completions by sampling frames and sending them to an SGLang server', 'prepare_video_messages_video_path': 'prepare a list of video frames as base64-encoded image messages with a text prompt for an SGLang API call'}
```

## File: sgl-project_sglang/examples/runtime/multimodal/pixtral_server.py

Prompts

```
['send an async POST request to a URL with JSON data and optional delay', 'test concurrent requests to the multimodal server for image caption generation', 'test streaming responses from the multimodal server for image caption generation', 'normalize a host and port into a base URL string', 'build a conversation template for LLaVA-NeXT with Llama-3 chat format', 'download a video from a URL and save it to a local cache directory', 'create an OpenAI API client connected to a local SGLang server at the given base URL', 'test streaming image-based chat completions against an SGLang multimodal server', 'test streaming video-based chat completions by sampling frames and sending them to an SGLang server', 'prepare a list of video frames as base64-encoded image messages with a text prompt for an SGLang API call', 'test the async send_request function to POST generate requests to a Pixtral server endpoint', 'test the test_concurrent function to send single or multiple image generation requests to a Pixtral server', 'test the test_streaming function to receive streaming text responses from a Pixtral multimodal server', 'run the pixtral_server.py CLI module to test a Pixtral model with single or multiple images via argparse', 'build a test script that sends image generation requests to a running SGLang Pixtral server with configurable host and port', 'build a conversation template for Qwen with LLaVA-NeXT chat format']
```

Usage

```
{'test_send_request': 'test the async send_request function to POST generate requests to a Pixtral server endpoint', 'test_test_concurrent': 'test the test_concurrent function to send single or multiple image generation requests to a Pixtral server', 'test_test_streaming': 'test the test_streaming function to receive streaming text responses from a Pixtral multimodal server', 'run_pixtral_server_test': 'run the pixtral_server.py CLI module to test a Pixtral model with single or multiple images via argparse', 'build_pixtral_image_test': 'build a test script that sends image generation requests to a running SGLang Pixtral server with configurable host and port'}
```

## File: sgl-project_sglang/examples/runtime/multimodal/qwen_llava_server.py

Prompts

```
['send an async POST request to a URL with JSON data and optional delay', 'test concurrent requests to the multimodal server for image caption generation', 'test streaming responses from the multimodal server for image caption generation', 'normalize a host and port into a base URL string', 'build a conversation template for LLaVA-NeXT with Llama-3 chat format', 'download a video from a URL and save it to a local cache directory', 'create an OpenAI API client connected to a local SGLang server at the given base URL', 'test streaming image-based chat completions against an SGLang multimodal server', 'test streaming video-based chat completions by sampling frames and sending them to an SGLang server', 'prepare a list of video frames as base64-encoded image messages with a text prompt for an SGLang API call', 'test the async send_request function to POST generate requests to a Pixtral server endpoint', 'test the test_concurrent function to send single or multiple image generation requests to a Pixtral server', 'test the test_streaming function to receive streaming text responses from a Pixtral multimodal server', 'run the pixtral_server.py CLI module to test a Pixtral model with single or multiple images via argparse', 'build a test script that sends image generation requests to a running SGLang Pixtral server with configurable host and port', 'build a conversation template for Qwen with LLaVA-NeXT chat format']
```

Usage

```
{'send_request': 'send an async POST request to a URL with JSON data and optional delay', 'test_concurrent': 'test concurrent requests to the multimodal server for image caption generation', 'test_streaming': 'test streaming responses from the multimodal server for image caption generation', 'normalize_base_url': 'normalize a host and port into a base URL string', 'conv_qwen': 'build a conversation template for Qwen with LLaVA-NeXT chat format'}
```

