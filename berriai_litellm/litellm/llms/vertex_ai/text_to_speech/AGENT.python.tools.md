# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/text_to_speech/text_to_speech_handler.py

Prompts

```
['create a VertexTextToSpeechRequest with text input, voice config, and audio encoding settings', 'run synchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'run asynchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'test validate_vertex_input to ensure text or ssml is provided and SSML auto-detection works correctly', 'build a VertexTextToSpeechAPI client that authenticates with Vertex AI and synthesizes speech to binary audio', 'map OpenAI TTS parameters to Vertex AI TTS parameters including voice and audio encoding', 'dispatch a Vertex AI text-to-speech request with credentials and voice configuration', 'transform an OpenAI TTS request into Vertex AI TTS format with authentication and request body', 'transform a Vertex AI TTS JSON response into binary audio content', 'validate Vertex AI environment and set up authentication headers for TTS requests']
```

Usage

```
{'create_vertex_text_to_speech_request': 'create a VertexTextToSpeechRequest with text input, voice config, and audio encoding settings', 'run_vertex_audio_speech': 'run synchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'run_async_vertex_audio_speech': 'run asynchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'test_validate_vertex_input': 'test validate_vertex_input to ensure text or ssml is provided and SSML auto-detection works correctly', 'build_vertex_text_to_speech_api': 'build a VertexTextToSpeechAPI client that authenticates with Vertex AI and synthesizes speech to binary audio'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/text_to_speech/transformation.py

Prompts

```
['create a VertexTextToSpeechRequest with text input, voice config, and audio encoding settings', 'run synchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'run asynchronous text-to-speech synthesis via Google Cloud Vertex AI and return binary audio content', 'test validate_vertex_input to ensure text or ssml is provided and SSML auto-detection works correctly', 'build a VertexTextToSpeechAPI client that authenticates with Vertex AI and synthesizes speech to binary audio', 'map OpenAI TTS parameters to Vertex AI TTS parameters including voice and audio encoding', 'dispatch a Vertex AI text-to-speech request with credentials and voice configuration', 'transform an OpenAI TTS request into Vertex AI TTS format with authentication and request body', 'transform a Vertex AI TTS JSON response into binary audio content', 'validate Vertex AI environment and set up authentication headers for TTS requests']
```

Usage

```
{'map_openai_params': 'map OpenAI TTS parameters to Vertex AI TTS parameters including voice and audio encoding', 'dispatch_text_to_speech': 'dispatch a Vertex AI text-to-speech request with credentials and voice configuration', 'transform_text_to_speech_request': 'transform an OpenAI TTS request into Vertex AI TTS format with authentication and request body', 'transform_text_to_speech_response': 'transform a Vertex AI TTS JSON response into binary audio content', 'validate_environment': 'validate Vertex AI environment and set up authentication headers for TTS requests'}
```

