# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/watsonx/audio_transcription/transformation.py

Prompts

```
['transform an audio transcription request into WatsonX multipart/form-data format with model, project_id, and optional params', 'transform a WatsonX HTTP response into a TranscriptionResponse object extracting text and usage fields', 'build the complete WatsonX audio transcription URL with the /ml/v1/audio/transcriptions endpoint and version query parameter', 'validate the environment for WatsonX audio transcription by checking credentials and removing Content-Type headers', 'get the list of supported OpenAI audio transcription parameters for WatsonX including language, prompt, response_format, temperature, and timestamp_granularities']
```

Usage

```
{'transform_audio_transcription_request': 'transform an audio transcription request into WatsonX multipart/form-data format with model, project_id, and optional params', 'transform_audio_transcription_response': 'transform a WatsonX HTTP response into a TranscriptionResponse object extracting text and usage fields', 'get_complete_url': 'build the complete WatsonX audio transcription URL with the /ml/v1/audio/transcriptions endpoint and version query parameter', 'validate_environment': 'validate the environment for WatsonX audio transcription by checking credentials and removing Content-Type headers', 'get_supported_openai_params': 'get the list of supported OpenAI audio transcription parameters for WatsonX including language, prompt, response_format, temperature, and timestamp_granularities'}
```

