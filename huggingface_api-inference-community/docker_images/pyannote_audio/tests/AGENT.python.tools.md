# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/pyannote_audio/tests/test_api.py

Prompts

```
['test that the pyannote audio pipeline has at least one task enabled in ALLOWED_TASKS', 'test that calling get_pipeline with an unsupported task raises an EnvironmentError', 'review the PipelineTestCase class that validates allowed and unsupported Hugging Face tasks', 'summarize the TESTABLE_MODELS dictionary mapping task names to pyannote model IDs', 'summarize the ALL_TASKS set containing all Hugging Face inference task types', 'test the automatic speech recognition API by sending a FLAC audio file and verifying the text response', 'test that the ASR API returns a 400 error with a malformed soundfile message for bad audio', 'test the ASR API by sending a dual-channel OGG audio file and verifying the text response', 'test the ASR API by sending a WebM audio file and verifying the text response', 'read an audio sample file from the samples directory and return its raw bytes payload']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the pyannote audio pipeline has at least one task enabled in ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that calling get_pipeline with an unsupported task raises an EnvironmentError', 'review_PipelineTestCase': 'review the PipelineTestCase class that validates allowed and unsupported Hugging Face tasks', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping task names to pyannote model IDs', 'summarize_ALL_TASKS': 'summarize the ALL_TASKS set containing all Hugging Face inference task types'}
```

## File: huggingface_api-inference-community/docker_images/pyannote_audio/tests/test_api_automatic_speech_recognition.py

Prompts

```
['test that the pyannote audio pipeline has at least one task enabled in ALLOWED_TASKS', 'test that calling get_pipeline with an unsupported task raises an EnvironmentError', 'review the PipelineTestCase class that validates allowed and unsupported Hugging Face tasks', 'summarize the TESTABLE_MODELS dictionary mapping task names to pyannote model IDs', 'summarize the ALL_TASKS set containing all Hugging Face inference task types', 'test the automatic speech recognition API by sending a FLAC audio file and verifying the text response', 'test that the ASR API returns a 400 error with a malformed soundfile message for bad audio', 'test the ASR API by sending a dual-channel OGG audio file and verifying the text response', 'test the ASR API by sending a WebM audio file and verifying the text response', 'read an audio sample file from the samples directory and return its raw bytes payload']
```

Usage

```
{'test_simple_asr_flac': 'test the automatic speech recognition API by sending a FLAC audio file and verifying the text response', 'test_malformed_audio_handling': 'test that the ASR API returns a 400 error with a malformed soundfile message for bad audio', 'test_dual_channel_ogg_asr': 'test the ASR API by sending a dual-channel OGG audio file and verifying the text response', 'test_webm_audio_asr': 'test the ASR API by sending a WebM audio file and verifying the text response', 'read_audio_sample': 'read an audio sample file from the samples directory and return its raw bytes payload'}
```

