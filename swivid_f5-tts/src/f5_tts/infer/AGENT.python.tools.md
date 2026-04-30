# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/infer/infer_gradio.py

Prompts

```
['run the F5-TTS Gradio demo app with CLI options for port, host, and share flag', 'synthesize speech audio from reference audio and text using the F5-TTS model with configurable seed and speed', 'generate multi-style speech with multiple voice types and emotion labels in a single generation', 'build an interactive voice chat interface that records audio, generates AI text responses, and synthesizes TTS audio', 'parse text with embedded speech type tags like {Regular} or {"name": str, "seed": int} into structured segments', 'load a vocoder model (vocos or bigvgan) from huggingface or local path for audio generation', 'load a CFM TTS model checkpoint with tokenizer and configuration for inference', 'generate speech audio from reference audio and target text using the loaded TTS model', 'transcribe reference audio to text using whisper-large-v3-turbo automatic speech recognition', 'split long text into smaller sentence-based chunks for batched TTS inference']
```

Usage

```
{'run_gradio_tts_demo': 'run the F5-TTS Gradio demo app with CLI options for port, host, and share flag', 'synthesize_speech_audio': 'synthesize speech audio from reference audio and text using the F5-TTS model with configurable seed and speed', 'generate_multistyle_speech': 'generate multi-style speech with multiple voice types and emotion labels in a single generation', 'build_voice_chat_interface': 'build an interactive voice chat interface that records audio, generates AI text responses, and synthesizes TTS audio', 'parse_speechtype_segments': 'parse text with embedded speech type tags like {Regular} or {"name": str, "seed": int} into structured segments'}
```

## File: swivid_f5-tts/src/f5_tts/infer/utils_infer.py

Prompts

```
['run the F5-TTS Gradio demo app with CLI options for port, host, and share flag', 'synthesize speech audio from reference audio and text using the F5-TTS model with configurable seed and speed', 'generate multi-style speech with multiple voice types and emotion labels in a single generation', 'build an interactive voice chat interface that records audio, generates AI text responses, and synthesizes TTS audio', 'parse text with embedded speech type tags like {Regular} or {"name": str, "seed": int} into structured segments', 'load a vocoder model (vocos or bigvgan) from huggingface or local path for audio generation', 'load a CFM TTS model checkpoint with tokenizer and configuration for inference', 'generate speech audio from reference audio and target text using the loaded TTS model', 'transcribe reference audio to text using whisper-large-v3-turbo automatic speech recognition', 'split long text into smaller sentence-based chunks for batched TTS inference']
```

Usage

```
{'create_function_load_vocoder': 'load a vocoder model (vocos or bigvgan) from huggingface or local path for audio generation', 'create_function_load_model': 'load a CFM TTS model checkpoint with tokenizer and configuration for inference', 'create_function_infer_process': 'generate speech audio from reference audio and target text using the loaded TTS model', 'create_function_transcribe': 'transcribe reference audio to text using whisper-large-v3-turbo automatic speech recognition', 'create_function_chunk_text': 'split long text into smaller sentence-based chunks for batched TTS inference'}
```

