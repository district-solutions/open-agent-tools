# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/entrypoints/openai/transcription_adapters/base.py

Prompts

```
['build a TranscriptionAdapter subclass to add support for a new ASR model', 'register a TranscriptionAdapter subclass with a model key using the decorator', 'resolve the correct TranscriptionAdapter for a model by matching its architecture names', 'build sampling_params dict from a TranscriptionRequest for GenerateReqInput', 'build a TranscriptionVerboseResponse with segments and timestamps from transcription results', 'build a Qwen3-ASR transcription adapter that registers as Qwen3ASR and supports chunked streaming', 'build sampling parameters for Qwen3-ASR transcription requests with near-greedy temperature', 'postprocess Qwen3-ASR output text by stripping the <asr_text> tag prefix', 'build a verbose transcription response with language, duration, text, and usage for Qwen3-ASR', 'test the chunked streaming configuration with 2-second unfixed chunks for Qwen3-ASR', 'build sampling params dict for Whisper transcription request with temperature, max tokens, and language', 'build a TranscriptionVerboseResponse with segments, timestamps, and usage from Whisper model output', 'parse Whisper timestamp tokens from output_ids into time-aligned transcription segments', "register the WhisperAdapter class as a transcription adapter keyed by 'Whisper'", 'resolve the correct transcription adapter by matching model architecture names against the registry']
```

Usage

```
{'build_transcription_adapter': 'build a TranscriptionAdapter subclass to add support for a new ASR model', 'register_transcription_adapter': 'register a TranscriptionAdapter subclass with a model key using the decorator', 'resolve_adapter': 'resolve the correct TranscriptionAdapter for a model by matching its architecture names', 'build_sampling_params': 'build sampling_params dict from a TranscriptionRequest for GenerateReqInput', 'build_verbose_response': 'build a TranscriptionVerboseResponse with segments and timestamps from transcription results'}
```

## File: sgl-project_sglang/python/sglang/srt/entrypoints/openai/transcription_adapters/qwen3_asr.py

Prompts

```
['build a TranscriptionAdapter subclass to add support for a new ASR model', 'register a TranscriptionAdapter subclass with a model key using the decorator', 'resolve the correct TranscriptionAdapter for a model by matching its architecture names', 'build sampling_params dict from a TranscriptionRequest for GenerateReqInput', 'build a TranscriptionVerboseResponse with segments and timestamps from transcription results', 'build a Qwen3-ASR transcription adapter that registers as Qwen3ASR and supports chunked streaming', 'build sampling parameters for Qwen3-ASR transcription requests with near-greedy temperature', 'postprocess Qwen3-ASR output text by stripping the <asr_text> tag prefix', 'build a verbose transcription response with language, duration, text, and usage for Qwen3-ASR', 'test the chunked streaming configuration with 2-second unfixed chunks for Qwen3-ASR', 'build sampling params dict for Whisper transcription request with temperature, max tokens, and language', 'build a TranscriptionVerboseResponse with segments, timestamps, and usage from Whisper model output', 'parse Whisper timestamp tokens from output_ids into time-aligned transcription segments', "register the WhisperAdapter class as a transcription adapter keyed by 'Whisper'", 'resolve the correct transcription adapter by matching model architecture names against the registry']
```

Usage

```
{'build_transcription_adapter_qwen3_asr': 'build a Qwen3-ASR transcription adapter that registers as Qwen3ASR and supports chunked streaming', 'build_sampling_params_qwen3_asr': 'build sampling parameters for Qwen3-ASR transcription requests with near-greedy temperature', 'postprocess_text_qwen3_asr': 'postprocess Qwen3-ASR output text by stripping the <asr_text> tag prefix', 'build_verbose_response_qwen3_asr': 'build a verbose transcription response with language, duration, text, and usage for Qwen3-ASR', 'test_chunked_streaming_config_qwen3_asr': 'test the chunked streaming configuration with 2-second unfixed chunks for Qwen3-ASR'}
```

## File: sgl-project_sglang/python/sglang/srt/entrypoints/openai/transcription_adapters/whisper.py

Prompts

```
['build a TranscriptionAdapter subclass to add support for a new ASR model', 'register a TranscriptionAdapter subclass with a model key using the decorator', 'resolve the correct TranscriptionAdapter for a model by matching its architecture names', 'build sampling_params dict from a TranscriptionRequest for GenerateReqInput', 'build a TranscriptionVerboseResponse with segments and timestamps from transcription results', 'build a Qwen3-ASR transcription adapter that registers as Qwen3ASR and supports chunked streaming', 'build sampling parameters for Qwen3-ASR transcription requests with near-greedy temperature', 'postprocess Qwen3-ASR output text by stripping the <asr_text> tag prefix', 'build a verbose transcription response with language, duration, text, and usage for Qwen3-ASR', 'test the chunked streaming configuration with 2-second unfixed chunks for Qwen3-ASR', 'build sampling params dict for Whisper transcription request with temperature, max tokens, and language', 'build a TranscriptionVerboseResponse with segments, timestamps, and usage from Whisper model output', 'parse Whisper timestamp tokens from output_ids into time-aligned transcription segments', "register the WhisperAdapter class as a transcription adapter keyed by 'Whisper'", 'resolve the correct transcription adapter by matching model architecture names against the registry']
```

Usage

```
{'build_sampling_params_whisper': 'build sampling params dict for Whisper transcription request with temperature, max tokens, and language', 'build_verbose_response_whisper': 'build a TranscriptionVerboseResponse with segments, timestamps, and usage from Whisper model output', 'parse_segments_whisper': 'parse Whisper timestamp tokens from output_ids into time-aligned transcription segments', 'register_transcription_adapter_whisper': "register the WhisperAdapter class as a transcription adapter keyed by 'Whisper'", 'resolve_adapter_by_architecture': 'resolve the correct transcription adapter by matching model architecture names against the registry'}
```

