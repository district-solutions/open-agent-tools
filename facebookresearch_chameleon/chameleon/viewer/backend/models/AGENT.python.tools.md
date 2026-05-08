# Agent Python Tools

- repo: facebookresearch/chameleon
- repo_uri: https://github.com/facebookresearch/chameleon

## File: facebookresearch_chameleon/chameleon/viewer/backend/models/abstract_model.py

Prompts

```
['implement a subclass of AbstractMultimodalGenerator that provides concrete text, image, and multimodal streaming generation methods', 'call generate_text_streaming on a multimodal generator to stream text completions from a list of mixed token prompts', 'call generate_image_streaming on a multimodal generator to stream PIL images from a mixed token prompt with configurable CFG weights', 'call generate_multimodal_streaming on a multimodal generator to stream mixed text and image tokens with repetition penalty and suffix tokens', 'create a StreamingImage dataclass instance with a PIL image and a final boolean flag for streaming image output', 'build a ChameleonDistributedGenerator to spawn multi-GPU worker processes for distributed model inference', 'generate streaming text output from a prompt using the ChameleonDistributedGenerator across distributed workers', 'generate streaming image output from a text prompt using the ChameleonDistributedGenerator with VQGAN decoding', 'generate streaming multimodal text and image output from a prompt using the ChameleonDistributedGenerator', 'create a RedisQueue or AsyncRedisQueue for thread-safe request and response passing between distributed workers', 'generate batched text completions from multiple prompts using the ChameleonLocalGenerator model with temperature and top_p sampling', 'convert a mixed sequence of text strings and PIL images into token IDs using the Chameleon tokenizer and image tokenizer', 'serve a Chameleon multimodal model via uvicorn on a specified host and port with optional Redis locking', 'create a FastAPI web app with WebSocket endpoints for streaming text and image generation from a multimodal generator', 'run nvidia-smi and return the GPU status output as a string for health checks', 'acquire a Redis distributed lock with periodic queue status updates sent over a WebSocket connection', 'await and parse incoming WebSocket JSON messages into validated WSMultimodalMessage objects']
```

Usage

```
{'implement_AbstractMultimodalGenerator': 'implement a subclass of AbstractMultimodalGenerator that provides concrete text, image, and multimodal streaming generation methods', 'use_generate_text_streaming': 'call generate_text_streaming on a multimodal generator to stream text completions from a list of mixed token prompts', 'use_generate_image_streaming': 'call generate_image_streaming on a multimodal generator to stream PIL images from a mixed token prompt with configurable CFG weights', 'use_generate_multimodal_streaming': 'call generate_multimodal_streaming on a multimodal generator to stream mixed text and image tokens with repetition penalty and suffix tokens', 'create_StreamingImage_dataclass': 'create a StreamingImage dataclass instance with a PIL image and a final boolean flag for streaming image output'}
```

## File: facebookresearch_chameleon/chameleon/viewer/backend/models/chameleon_distributed.py

Prompts

```
['implement a subclass of AbstractMultimodalGenerator that provides concrete text, image, and multimodal streaming generation methods', 'call generate_text_streaming on a multimodal generator to stream text completions from a list of mixed token prompts', 'call generate_image_streaming on a multimodal generator to stream PIL images from a mixed token prompt with configurable CFG weights', 'call generate_multimodal_streaming on a multimodal generator to stream mixed text and image tokens with repetition penalty and suffix tokens', 'create a StreamingImage dataclass instance with a PIL image and a final boolean flag for streaming image output', 'build a ChameleonDistributedGenerator to spawn multi-GPU worker processes for distributed model inference', 'generate streaming text output from a prompt using the ChameleonDistributedGenerator across distributed workers', 'generate streaming image output from a text prompt using the ChameleonDistributedGenerator with VQGAN decoding', 'generate streaming multimodal text and image output from a prompt using the ChameleonDistributedGenerator', 'create a RedisQueue or AsyncRedisQueue for thread-safe request and response passing between distributed workers', 'generate batched text completions from multiple prompts using the ChameleonLocalGenerator model with temperature and top_p sampling', 'convert a mixed sequence of text strings and PIL images into token IDs using the Chameleon tokenizer and image tokenizer', 'serve a Chameleon multimodal model via uvicorn on a specified host and port with optional Redis locking', 'create a FastAPI web app with WebSocket endpoints for streaming text and image generation from a multimodal generator', 'run nvidia-smi and return the GPU status output as a string for health checks', 'acquire a Redis distributed lock with periodic queue status updates sent over a WebSocket connection', 'await and parse incoming WebSocket JSON messages into validated WSMultimodalMessage objects']
```

Usage

```
{'build_distributed_generator': 'build a ChameleonDistributedGenerator to spawn multi-GPU worker processes for distributed model inference', 'generate_text_streaming': 'generate streaming text output from a prompt using the ChameleonDistributedGenerator across distributed workers', 'generate_image_streaming': 'generate streaming image output from a text prompt using the ChameleonDistributedGenerator with VQGAN decoding', 'generate_multimodal_streaming': 'generate streaming multimodal text and image output from a prompt using the ChameleonDistributedGenerator', 'create_redis_queue': 'create a RedisQueue or AsyncRedisQueue for thread-safe request and response passing between distributed workers'}
```

## File: facebookresearch_chameleon/chameleon/viewer/backend/models/chameleon_local.py

Prompts

```
['implement a subclass of AbstractMultimodalGenerator that provides concrete text, image, and multimodal streaming generation methods', 'call generate_text_streaming on a multimodal generator to stream text completions from a list of mixed token prompts', 'call generate_image_streaming on a multimodal generator to stream PIL images from a mixed token prompt with configurable CFG weights', 'call generate_multimodal_streaming on a multimodal generator to stream mixed text and image tokens with repetition penalty and suffix tokens', 'create a StreamingImage dataclass instance with a PIL image and a final boolean flag for streaming image output', 'build a ChameleonDistributedGenerator to spawn multi-GPU worker processes for distributed model inference', 'generate streaming text output from a prompt using the ChameleonDistributedGenerator across distributed workers', 'generate streaming image output from a text prompt using the ChameleonDistributedGenerator with VQGAN decoding', 'generate streaming multimodal text and image output from a prompt using the ChameleonDistributedGenerator', 'create a RedisQueue or AsyncRedisQueue for thread-safe request and response passing between distributed workers', 'generate batched text completions from multiple prompts using the ChameleonLocalGenerator model with temperature and top_p sampling', 'convert a mixed sequence of text strings and PIL images into token IDs using the Chameleon tokenizer and image tokenizer', 'serve a Chameleon multimodal model via uvicorn on a specified host and port with optional Redis locking', 'create a FastAPI web app with WebSocket endpoints for streaming text and image generation from a multimodal generator', 'run nvidia-smi and return the GPU status output as a string for health checks', 'acquire a Redis distributed lock with periodic queue status updates sent over a WebSocket connection', 'await and parse incoming WebSocket JSON messages into validated WSMultimodalMessage objects']
```

Usage

```
{'generate_text_streaming': 'generate streaming text output from a text or multimodal prompt using the ChameleonLocalGenerator model', 'generate_image_streaming': 'generate streaming image output from a text prompt using the ChameleonLocalGenerator model with CFG weights', 'generate_multimodal_streaming': 'generate streaming multimodal output with interleaved text and images from a prompt using ChameleonLocalGenerator', 'generate_batched_text': 'generate batched text completions from multiple prompts using the ChameleonLocalGenerator model with temperature and top_p sampling', 'tokens_from_inputs': 'convert a mixed sequence of text strings and PIL images into token IDs using the Chameleon tokenizer and image tokenizer'}
```

## File: facebookresearch_chameleon/chameleon/viewer/backend/models/service.py

Prompts

```
['implement a subclass of AbstractMultimodalGenerator that provides concrete text, image, and multimodal streaming generation methods', 'call generate_text_streaming on a multimodal generator to stream text completions from a list of mixed token prompts', 'call generate_image_streaming on a multimodal generator to stream PIL images from a mixed token prompt with configurable CFG weights', 'call generate_multimodal_streaming on a multimodal generator to stream mixed text and image tokens with repetition penalty and suffix tokens', 'create a StreamingImage dataclass instance with a PIL image and a final boolean flag for streaming image output', 'build a ChameleonDistributedGenerator to spawn multi-GPU worker processes for distributed model inference', 'generate streaming text output from a prompt using the ChameleonDistributedGenerator across distributed workers', 'generate streaming image output from a text prompt using the ChameleonDistributedGenerator with VQGAN decoding', 'generate streaming multimodal text and image output from a prompt using the ChameleonDistributedGenerator', 'create a RedisQueue or AsyncRedisQueue for thread-safe request and response passing between distributed workers', 'generate batched text completions from multiple prompts using the ChameleonLocalGenerator model with temperature and top_p sampling', 'convert a mixed sequence of text strings and PIL images into token IDs using the Chameleon tokenizer and image tokenizer', 'serve a Chameleon multimodal model via uvicorn on a specified host and port with optional Redis locking', 'create a FastAPI web app with WebSocket endpoints for streaming text and image generation from a multimodal generator', 'run nvidia-smi and return the GPU status output as a string for health checks', 'acquire a Redis distributed lock with periodic queue status updates sent over a WebSocket connection', 'await and parse incoming WebSocket JSON messages into validated WSMultimodalMessage objects']
```

Usage

```
{'serve_chameleon_model': 'serve a Chameleon multimodal model via uvicorn on a specified host and port with optional Redis locking', 'create_web_app': 'create a FastAPI web app with WebSocket endpoints for streaming text and image generation from a multimodal generator', 'run_nvidia_smi': 'run nvidia-smi and return the GPU status output as a string for health checks', 'acquire_redis_lock': 'acquire a Redis distributed lock with periodic queue status updates sent over a WebSocket connection', 'await_websocket_message': 'await and parse incoming WebSocket JSON messages into validated WSMultimodalMessage objects'}
```

