# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/speech_to_text/api_router.py

Prompts

```
['create a FastAPI endpoint that accepts audio files and returns transcription results via streaming or JSON', 'create a FastAPI endpoint that accepts audio files and returns translated text via streaming or JSON', 'attach the speech-to-text API router to a FastAPI application instance', 'initialize OpenAI serving transcription and translation handlers with engine client and configuration args', 'review the create_transcriptions endpoint that handles audio upload, reads file data, and streams transcription results', 'build a pydantic model for OpenAI-compatible speech-to-text transcription requests with audio file, language, prompt, and sampling parameters', 'build a pydantic model for OpenAI-compatible audio translation requests with audio file, source language, target language, and sampling parameters', 'convert a TranscriptionRequest or TranslationRequest into vLLM SamplingParams or BeamSearchParams for model inference', 'validate that stream options like stream_include_usage are only set when stream is true in transcription or translation requests', 'build OpenAI-compatible transcription response models including plain text, verbose with segments and word timestamps, and streaming chunk responses', 'create an OpenAISpeechToText instance for transcription or translation with engine client and model config', 'run speech-to-text transcription or translation on audio data with streaming or non-streaming response', 'test auto-detection of spoken language from an audio chunk using model inference', 'summarize speech-to-text tokens into verbose segments with timestamps and log probabilities', 'review the asr_inter_chunk_separator function that selects language-appropriate chunk separators']
```

Usage

```
{'create_transcriptions': 'create a FastAPI endpoint that accepts audio files and returns transcription results via streaming or JSON', 'create_translations': 'create a FastAPI endpoint that accepts audio files and returns translated text via streaming or JSON', 'attach_router': 'attach the speech-to-text API router to a FastAPI application instance', 'init_transcription_state': 'initialize OpenAI serving transcription and translation handlers with engine client and configuration args', 'review_create_transcriptions': 'review the create_transcriptions endpoint that handles audio upload, reads file data, and streams transcription results'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/speech_to_text/protocol.py

Prompts

```
['create a FastAPI endpoint that accepts audio files and returns transcription results via streaming or JSON', 'create a FastAPI endpoint that accepts audio files and returns translated text via streaming or JSON', 'attach the speech-to-text API router to a FastAPI application instance', 'initialize OpenAI serving transcription and translation handlers with engine client and configuration args', 'review the create_transcriptions endpoint that handles audio upload, reads file data, and streams transcription results', 'build a pydantic model for OpenAI-compatible speech-to-text transcription requests with audio file, language, prompt, and sampling parameters', 'build a pydantic model for OpenAI-compatible audio translation requests with audio file, source language, target language, and sampling parameters', 'convert a TranscriptionRequest or TranslationRequest into vLLM SamplingParams or BeamSearchParams for model inference', 'validate that stream options like stream_include_usage are only set when stream is true in transcription or translation requests', 'build OpenAI-compatible transcription response models including plain text, verbose with segments and word timestamps, and streaming chunk responses', 'create an OpenAISpeechToText instance for transcription or translation with engine client and model config', 'run speech-to-text transcription or translation on audio data with streaming or non-streaming response', 'test auto-detection of spoken language from an audio chunk using model inference', 'summarize speech-to-text tokens into verbose segments with timestamps and log probabilities', 'review the asr_inter_chunk_separator function that selects language-appropriate chunk separators']
```

Usage

```
{'build_transcription_request': 'build a pydantic model for OpenAI-compatible speech-to-text transcription requests with audio file, language, prompt, and sampling parameters', 'build_translation_request': 'build a pydantic model for OpenAI-compatible audio translation requests with audio file, source language, target language, and sampling parameters', 'convert_to_sampling_params': 'convert a TranscriptionRequest or TranslationRequest into vLLM SamplingParams or BeamSearchParams for model inference', 'validate_stream_options': 'validate that stream options like stream_include_usage are only set when stream is true in transcription or translation requests', 'build_transcription_response': 'build OpenAI-compatible transcription response models including plain text, verbose with segments and word timestamps, and streaming chunk responses'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/speech_to_text/speech_to_text.py

Prompts

```
['create a FastAPI endpoint that accepts audio files and returns transcription results via streaming or JSON', 'create a FastAPI endpoint that accepts audio files and returns translated text via streaming or JSON', 'attach the speech-to-text API router to a FastAPI application instance', 'initialize OpenAI serving transcription and translation handlers with engine client and configuration args', 'review the create_transcriptions endpoint that handles audio upload, reads file data, and streams transcription results', 'build a pydantic model for OpenAI-compatible speech-to-text transcription requests with audio file, language, prompt, and sampling parameters', 'build a pydantic model for OpenAI-compatible audio translation requests with audio file, source language, target language, and sampling parameters', 'convert a TranscriptionRequest or TranslationRequest into vLLM SamplingParams or BeamSearchParams for model inference', 'validate that stream options like stream_include_usage are only set when stream is true in transcription or translation requests', 'build OpenAI-compatible transcription response models including plain text, verbose with segments and word timestamps, and streaming chunk responses', 'create an OpenAISpeechToText instance for transcription or translation with engine client and model config', 'run speech-to-text transcription or translation on audio data with streaming or non-streaming response', 'test auto-detection of spoken language from an audio chunk using model inference', 'summarize speech-to-text tokens into verbose segments with timestamps and log probabilities', 'review the asr_inter_chunk_separator function that selects language-appropriate chunk separators']
```

Usage

```
{'create_openai_speech_to_text': 'create an OpenAISpeechToText instance for transcription or translation with engine client and model config', 'run_speech_to_text': 'run speech-to-text transcription or translation on audio data with streaming or non-streaming response', 'test_language_detection': 'test auto-detection of spoken language from an audio chunk using model inference', 'summarize_verbose_segments': 'summarize speech-to-text tokens into verbose segments with timestamps and log probabilities', 'review_asr_inter_chunk_separator': 'review the asr_inter_chunk_separator function that selects language-appropriate chunk separators'}
```

