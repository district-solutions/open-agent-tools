# Agent Python Tools

- repo: matatonic/openedai-speech
- repo_uri: https://github.com/matatonic/openedai-speech

## File: matatonic_openedai-speech/audio_reader.py

Prompts

```
['run the audio_reader.py CLI module to convert stdin text to speech and play it aloud', 'create an OpenAI_tts instance with a model, voice, speed, and base directory for text-to-speech generation', 'test the OpenAI_tts.speech_to_file method by passing text and returning an audio file path', 'build a SimpleAudioPlayer that queues and plays audio files from a background thread', 'review the tempdir context manager that creates and cleans up a temporary directory', 'create a FastAPI-based OpenAI-compatible stub server with CORS middleware and model registration endpoints', 'register a model with the OpenAIStub server using its register_model method by name', 'deregister a previously registered model from the OpenAIStub server by name', 'get a list of all registered models from the OpenAIStub server via the /v1/models endpoint', 'get metadata for a specific model from the OpenAIStub server via the /v1/models/{model} endpoint', 'run say.py to convert text to speech using OpenAI TTS-1 with alloy voice', 'run say.py to convert text from a file to speech and save as mp3 output', 'run say.py to generate speech with a custom voice and playback speed setting', 'run say.py to stream text-to-speech audio output to a specified filename', 'test the parse_args function with custom model, voice, format, and speed arguments', 'run the OpenedAI Speech API server on a specified host and port with optional XTTS device and unload timer', 'generate streaming speech audio from text using the /v1/audio/speech endpoint with model, voice, format, and speed parameters', 'build ffmpeg command-line arguments to convert raw PCM audio to mp3, opus, aac, flac, wav, or pcm format', 'preprocess raw text input by applying regex substitutions from config/pre_process_map.yaml and stripping whitespace', 'map a voice name to speaker configuration from config/voice_to_speaker.yaml for a given model']
```

Usage

```
{'run_audio_reader_cli': 'run the audio_reader.py CLI module to convert stdin text to speech and play it aloud', 'create_openai_tts': 'create an OpenAI_tts instance with a model, voice, speed, and base directory for text-to-speech generation', 'test_speech_to_file': 'test the OpenAI_tts.speech_to_file method by passing text and returning an audio file path', 'build_simple_audio_player': 'build a SimpleAudioPlayer that queues and plays audio files from a background thread', 'review_tempdir_context_manager': 'review the tempdir context manager that creates and cleans up a temporary directory'}
```

## File: matatonic_openedai-speech/openedai.py

Prompts

```
['run the audio_reader.py CLI module to convert stdin text to speech and play it aloud', 'create an OpenAI_tts instance with a model, voice, speed, and base directory for text-to-speech generation', 'test the OpenAI_tts.speech_to_file method by passing text and returning an audio file path', 'build a SimpleAudioPlayer that queues and plays audio files from a background thread', 'review the tempdir context manager that creates and cleans up a temporary directory', 'create a FastAPI-based OpenAI-compatible stub server with CORS middleware and model registration endpoints', 'register a model with the OpenAIStub server using its register_model method by name', 'deregister a previously registered model from the OpenAIStub server by name', 'get a list of all registered models from the OpenAIStub server via the /v1/models endpoint', 'get metadata for a specific model from the OpenAIStub server via the /v1/models/{model} endpoint', 'run say.py to convert text to speech using OpenAI TTS-1 with alloy voice', 'run say.py to convert text from a file to speech and save as mp3 output', 'run say.py to generate speech with a custom voice and playback speed setting', 'run say.py to stream text-to-speech audio output to a specified filename', 'test the parse_args function with custom model, voice, format, and speed arguments', 'run the OpenedAI Speech API server on a specified host and port with optional XTTS device and unload timer', 'generate streaming speech audio from text using the /v1/audio/speech endpoint with model, voice, format, and speed parameters', 'build ffmpeg command-line arguments to convert raw PCM audio to mp3, opus, aac, flac, wav, or pcm format', 'preprocess raw text input by applying regex substitutions from config/pre_process_map.yaml and stripping whitespace', 'map a voice name to speaker configuration from config/voice_to_speaker.yaml for a given model']
```

Usage

```
{'create_openai_stub_server': 'create a FastAPI-based OpenAI-compatible stub server with CORS middleware and model registration endpoints', 'register_model_openai_stub': 'register a model with the OpenAIStub server using its register_model method by name', 'deregister_model_openai_stub': 'deregister a previously registered model from the OpenAIStub server by name', 'get_model_list_openai_stub': 'get a list of all registered models from the OpenAIStub server via the /v1/models endpoint', 'get_model_info_openai_stub': 'get metadata for a specific model from the OpenAIStub server via the /v1/models/{model} endpoint'}
```

## File: matatonic_openedai-speech/say.py

Prompts

```
['run the audio_reader.py CLI module to convert stdin text to speech and play it aloud', 'create an OpenAI_tts instance with a model, voice, speed, and base directory for text-to-speech generation', 'test the OpenAI_tts.speech_to_file method by passing text and returning an audio file path', 'build a SimpleAudioPlayer that queues and plays audio files from a background thread', 'review the tempdir context manager that creates and cleans up a temporary directory', 'create a FastAPI-based OpenAI-compatible stub server with CORS middleware and model registration endpoints', 'register a model with the OpenAIStub server using its register_model method by name', 'deregister a previously registered model from the OpenAIStub server by name', 'get a list of all registered models from the OpenAIStub server via the /v1/models endpoint', 'get metadata for a specific model from the OpenAIStub server via the /v1/models/{model} endpoint', 'run say.py to convert text to speech using OpenAI TTS-1 with alloy voice', 'run say.py to convert text from a file to speech and save as mp3 output', 'run say.py to generate speech with a custom voice and playback speed setting', 'run say.py to stream text-to-speech audio output to a specified filename', 'test the parse_args function with custom model, voice, format, and speed arguments', 'run the OpenedAI Speech API server on a specified host and port with optional XTTS device and unload timer', 'generate streaming speech audio from text using the /v1/audio/speech endpoint with model, voice, format, and speed parameters', 'build ffmpeg command-line arguments to convert raw PCM audio to mp3, opus, aac, flac, wav, or pcm format', 'preprocess raw text input by applying regex substitutions from config/pre_process_map.yaml and stripping whitespace', 'map a voice name to speaker configuration from config/voice_to_speaker.yaml for a given model']
```

Usage

```
{'run_say_tts': 'run say.py to convert text to speech using OpenAI TTS-1 with alloy voice', 'run_say_from_file': 'run say.py to convert text from a file to speech and save as mp3 output', 'run_say_with_voice': 'run say.py to generate speech with a custom voice and playback speed setting', 'run_say_streaming': 'run say.py to stream text-to-speech audio output to a specified filename', 'test_parse_args': 'test the parse_args function with custom model, voice, format, and speed arguments'}
```

## File: matatonic_openedai-speech/speech.py

Prompts

```
['run the audio_reader.py CLI module to convert stdin text to speech and play it aloud', 'create an OpenAI_tts instance with a model, voice, speed, and base directory for text-to-speech generation', 'test the OpenAI_tts.speech_to_file method by passing text and returning an audio file path', 'build a SimpleAudioPlayer that queues and plays audio files from a background thread', 'review the tempdir context manager that creates and cleans up a temporary directory', 'create a FastAPI-based OpenAI-compatible stub server with CORS middleware and model registration endpoints', 'register a model with the OpenAIStub server using its register_model method by name', 'deregister a previously registered model from the OpenAIStub server by name', 'get a list of all registered models from the OpenAIStub server via the /v1/models endpoint', 'get metadata for a specific model from the OpenAIStub server via the /v1/models/{model} endpoint', 'run say.py to convert text to speech using OpenAI TTS-1 with alloy voice', 'run say.py to convert text from a file to speech and save as mp3 output', 'run say.py to generate speech with a custom voice and playback speed setting', 'run say.py to stream text-to-speech audio output to a specified filename', 'test the parse_args function with custom model, voice, format, and speed arguments', 'run the OpenedAI Speech API server on a specified host and port with optional XTTS device and unload timer', 'generate streaming speech audio from text using the /v1/audio/speech endpoint with model, voice, format, and speed parameters', 'build ffmpeg command-line arguments to convert raw PCM audio to mp3, opus, aac, flac, wav, or pcm format', 'preprocess raw text input by applying regex substitutions from config/pre_process_map.yaml and stripping whitespace', 'map a voice name to speaker configuration from config/voice_to_speaker.yaml for a given model']
```

Usage

```
{'run_openedai_tts_server': 'run the OpenedAI Speech API server on a specified host and port with optional XTTS device and unload timer', 'generate_speech_streaming': 'generate streaming speech audio from text using the /v1/audio/speech endpoint with model, voice, format, and speed parameters', 'build_ffmpeg_args': 'build ffmpeg command-line arguments to convert raw PCM audio to mp3, opus, aac, flac, wav, or pcm format', 'preprocess_text_input': 'preprocess raw text input by applying regex substitutions from config/pre_process_map.yaml and stripping whitespace', 'map_voice_to_speaker': 'map a voice name to speaker configuration from config/voice_to_speaker.yaml for a given model'}
```

