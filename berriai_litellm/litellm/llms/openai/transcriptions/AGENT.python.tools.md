# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/transcriptions/gpt_transformation.py

Prompts

```
['test the OpenAIGPTAudioTranscriptionConfig class for audio transcription support', 'create an OpenAIGPTAudioTranscriptionConfig instance for gpt-4o-transcribe models', 'build a call to get_supported_openai_params to retrieve supported params for gpt-4o-transcribe', 'test get_supported_openai_params returns language, prompt, response_format, temperature, and include', 'run transform_audio_transcription_request to build an AudioTranscriptionRequestData from model, audio file, and optional params', 'create audio transcription requests using the OpenAIAudioTranscription class with model, audio file, and optional parameters', 'run async audio transcription requests with OpenAI client, timeout, and logging support', 'make synchronous OpenAI audio transcription API calls with optional response header capture', 'make asynchronous OpenAI audio transcription API calls with raw response header extraction', 'test the OpenAIAudioTranscription class transcription handling with provider config and logging integration', 'build the complete transcription endpoint URL from an api_base for OpenAI Whisper models', 'test the list of supported OpenAI audio transcription params for Whisper models', 'map OpenAI audio transcription params to Whisper-compatible parameter values', 'transform an audio transcription request into AudioTranscriptionRequestData with verbose_json format', 'transform an HTTP response into a TranscriptionResponse object from Whisper transcription']
```

Usage

```
{'test_OpenAIGPTAudioTranscriptionConfig': 'test the OpenAIGPTAudioTranscriptionConfig class for audio transcription support', 'create_OpenAIGPTAudioTranscriptionConfig': 'create an OpenAIGPTAudioTranscriptionConfig instance for gpt-4o-transcribe models', 'build_get_supported_openai_params': 'build a call to get_supported_openai_params to retrieve supported params for gpt-4o-transcribe', 'test_get_supported_openai_params': 'test get_supported_openai_params returns language, prompt, response_format, temperature, and include', 'run_transform_audio_transcription_request': 'run transform_audio_transcription_request to build an AudioTranscriptionRequestData from model, audio file, and optional params'}
```

## File: berriai_litellm/litellm/llms/openai/transcriptions/handler.py

Prompts

```
['test the OpenAIGPTAudioTranscriptionConfig class for audio transcription support', 'create an OpenAIGPTAudioTranscriptionConfig instance for gpt-4o-transcribe models', 'build a call to get_supported_openai_params to retrieve supported params for gpt-4o-transcribe', 'test get_supported_openai_params returns language, prompt, response_format, temperature, and include', 'run transform_audio_transcription_request to build an AudioTranscriptionRequestData from model, audio file, and optional params', 'create audio transcription requests using the OpenAIAudioTranscription class with model, audio file, and optional parameters', 'run async audio transcription requests with OpenAI client, timeout, and logging support', 'make synchronous OpenAI audio transcription API calls with optional response header capture', 'make asynchronous OpenAI audio transcription API calls with raw response header extraction', 'test the OpenAIAudioTranscription class transcription handling with provider config and logging integration', 'build the complete transcription endpoint URL from an api_base for OpenAI Whisper models', 'test the list of supported OpenAI audio transcription params for Whisper models', 'map OpenAI audio transcription params to Whisper-compatible parameter values', 'transform an audio transcription request into AudioTranscriptionRequestData with verbose_json format', 'transform an HTTP response into a TranscriptionResponse object from Whisper transcription']
```

Usage

```
{'create_openai_audio_transcriptions': 'create audio transcription requests using the OpenAIAudioTranscription class with model, audio file, and optional parameters', 'run_async_audio_transcriptions': 'run async audio transcription requests with OpenAI client, timeout, and logging support', 'make_sync_openai_audio_transcriptions_request': 'make synchronous OpenAI audio transcription API calls with optional response header capture', 'make_openai_audio_transcriptions_request': 'make asynchronous OpenAI audio transcription API calls with raw response header extraction', 'test_openai_audio_transcription': 'test the OpenAIAudioTranscription class transcription handling with provider config and logging integration'}
```

## File: berriai_litellm/litellm/llms/openai/transcriptions/whisper_transformation.py

Prompts

```
['test the OpenAIGPTAudioTranscriptionConfig class for audio transcription support', 'create an OpenAIGPTAudioTranscriptionConfig instance for gpt-4o-transcribe models', 'build a call to get_supported_openai_params to retrieve supported params for gpt-4o-transcribe', 'test get_supported_openai_params returns language, prompt, response_format, temperature, and include', 'run transform_audio_transcription_request to build an AudioTranscriptionRequestData from model, audio file, and optional params', 'create audio transcription requests using the OpenAIAudioTranscription class with model, audio file, and optional parameters', 'run async audio transcription requests with OpenAI client, timeout, and logging support', 'make synchronous OpenAI audio transcription API calls with optional response header capture', 'make asynchronous OpenAI audio transcription API calls with raw response header extraction', 'test the OpenAIAudioTranscription class transcription handling with provider config and logging integration', 'build the complete transcription endpoint URL from an api_base for OpenAI Whisper models', 'test the list of supported OpenAI audio transcription params for Whisper models', 'map OpenAI audio transcription params to Whisper-compatible parameter values', 'transform an audio transcription request into AudioTranscriptionRequestData with verbose_json format', 'transform an HTTP response into a TranscriptionResponse object from Whisper transcription']
```

Usage

```
{'build_whisper_transcription_url': 'build the complete transcription endpoint URL from an api_base for OpenAI Whisper models', 'test_supported_openai_params': 'test the list of supported OpenAI audio transcription params for Whisper models', 'map_openai_params_to_whisper': 'map OpenAI audio transcription params to Whisper-compatible parameter values', 'transform_audio_transcription_request': 'transform an audio transcription request into AudioTranscriptionRequestData with verbose_json format', 'transform_audio_transcription_response': 'transform an HTTP response into a TranscriptionResponse object from Whisper transcription'}
```

