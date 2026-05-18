# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/models/inference/pipeline.py

Prompts

```
['build an ASRInferencePipeline from a model card to transcribe audio files into text', 'run the transcribe method on a list of audio file paths with optional language codes', 'run transcribe_with_context on audio inputs using ContextExample pairs for zero-shot language adaptation', 'create a ContextExample dataclass with audio input and corresponding text transcription for context conditioning', 'resample an audio waveform dictionary to 16kHz sample rate using torchaudio functional resample']
```

Usage

```
{'build_asr_inference_pipeline': 'build an ASRInferencePipeline from a model card to transcribe audio files into text', 'run_transcribe_audio': 'run the transcribe method on a list of audio file paths with optional language codes', 'run_transcribe_with_context': 'run transcribe_with_context on audio inputs using ContextExample pairs for zero-shot language adaptation', 'create_context_example': 'create a ContextExample dataclass with audio input and corresponding text transcription for context conditioning', 'resample_audio_to_16khz': 'resample an audio waveform dictionary to 16kHz sample rate using torchaudio functional resample'}
```

