# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/espnet/tests/test_api.py

Prompts

```
['test that the ESPnet pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the ESPnet HuggingFace inference API pipelines', 'review the PipelineTestCase class to verify ESPnet allowed tasks and unsupported task handling', 'refactor the TESTABLE_MODELS dictionary to add or update ESPnet model mappings for speech tasks', 'test the automatic speech recognition API with a FLAC audio file and verify text output', 'test the ASR API error handling by sending a malformed FLAC audio file', 'test the automatic speech recognition API with a dual channel OGG audio file', 'test the automatic speech recognition API with a WebM audio file and verify text output', 'read an audio sample file from the samples directory and return its raw bytes', 'test the TextToSpeechTestCase to verify the TTS API returns valid audio/flac output for text input', 'test the TextToSpeechTestCase to verify the TTS API returns a 400 error for malformed binary input', 'run the TextToSpeechTestCase unittest suite to validate the ESPNet text-to-speech API endpoint', 'review the TextToSpeechTestCase class and its test methods for the ESPNet TTS API', 'refactor the TextToSpeechTestCase to add additional test cases for edge cases or new TTS features', 'run the DockerBuildTestCase to verify the docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'test that a docker image can be built from the project root directory', 'review the cd context manager class that handles directory changes with automatic restoration', 'refactor the cd context manager to support additional path resolution or error handling']
```

Usage

```
{'test_pipeline_tasks_enabled': 'test that the ESPnet pipeline has at least one task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run_pipeline_unit_tests': 'run the unittest test suite for the ESPnet HuggingFace inference API pipelines', 'review_PipelineTestCase': 'review the PipelineTestCase class to verify ESPnet allowed tasks and unsupported task handling', 'refactor_TESTABLE_MODELS': 'refactor the TESTABLE_MODELS dictionary to add or update ESPnet model mappings for speech tasks'}
```

## File: huggingface_api-inference-community/docker_images/espnet/tests/test_api_automatic_speech_recognition.py

Prompts

```
['test that the ESPnet pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the ESPnet HuggingFace inference API pipelines', 'review the PipelineTestCase class to verify ESPnet allowed tasks and unsupported task handling', 'refactor the TESTABLE_MODELS dictionary to add or update ESPnet model mappings for speech tasks', 'test the automatic speech recognition API with a FLAC audio file and verify text output', 'test the ASR API error handling by sending a malformed FLAC audio file', 'test the automatic speech recognition API with a dual channel OGG audio file', 'test the automatic speech recognition API with a WebM audio file and verify text output', 'read an audio sample file from the samples directory and return its raw bytes', 'test the TextToSpeechTestCase to verify the TTS API returns valid audio/flac output for text input', 'test the TextToSpeechTestCase to verify the TTS API returns a 400 error for malformed binary input', 'run the TextToSpeechTestCase unittest suite to validate the ESPNet text-to-speech API endpoint', 'review the TextToSpeechTestCase class and its test methods for the ESPNet TTS API', 'refactor the TextToSpeechTestCase to add additional test cases for edge cases or new TTS features', 'run the DockerBuildTestCase to verify the docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'test that a docker image can be built from the project root directory', 'review the cd context manager class that handles directory changes with automatic restoration', 'refactor the cd context manager to support additional path resolution or error handling']
```

Usage

```
{'test_asr_flac_audio': 'test the automatic speech recognition API with a FLAC audio file and verify text output', 'test_asr_malformed_audio': 'test the ASR API error handling by sending a malformed FLAC audio file', 'test_asr_dual_channel_audio': 'test the automatic speech recognition API with a dual channel OGG audio file', 'test_asr_webm_audio': 'test the automatic speech recognition API with a WebM audio file and verify text output', 'read_audio_sample': 'read an audio sample file from the samples directory and return its raw bytes'}
```

## File: huggingface_api-inference-community/docker_images/espnet/tests/test_api_text_to_speech.py

Prompts

```
['test that the ESPnet pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the ESPnet HuggingFace inference API pipelines', 'review the PipelineTestCase class to verify ESPnet allowed tasks and unsupported task handling', 'refactor the TESTABLE_MODELS dictionary to add or update ESPnet model mappings for speech tasks', 'test the automatic speech recognition API with a FLAC audio file and verify text output', 'test the ASR API error handling by sending a malformed FLAC audio file', 'test the automatic speech recognition API with a dual channel OGG audio file', 'test the automatic speech recognition API with a WebM audio file and verify text output', 'read an audio sample file from the samples directory and return its raw bytes', 'test the TextToSpeechTestCase to verify the TTS API returns valid audio/flac output for text input', 'test the TextToSpeechTestCase to verify the TTS API returns a 400 error for malformed binary input', 'run the TextToSpeechTestCase unittest suite to validate the ESPNet text-to-speech API endpoint', 'review the TextToSpeechTestCase class and its test methods for the ESPNet TTS API', 'refactor the TextToSpeechTestCase to add additional test cases for edge cases or new TTS features', 'run the DockerBuildTestCase to verify the docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'test that a docker image can be built from the project root directory', 'review the cd context manager class that handles directory changes with automatic restoration', 'refactor the cd context manager to support additional path resolution or error handling']
```

Usage

```
{'test_text_to_speech_simple': 'test the TextToSpeechTestCase to verify the TTS API returns valid audio/flac output for text input', 'test_text_to_speech_malformed_input': 'test the TextToSpeechTestCase to verify the TTS API returns a 400 error for malformed binary input', 'run_text_to_speech_tests': 'run the TextToSpeechTestCase unittest suite to validate the ESPNet text-to-speech API endpoint', 'review_text_to_speech_testcase': 'review the TextToSpeechTestCase class and its test methods for the ESPNet TTS API', 'refactor_text_to_speech_testcase': 'refactor the TextToSpeechTestCase to add additional test cases for edge cases or new TTS features'}
```

## File: huggingface_api-inference-community/docker_images/espnet/tests/test_docker_build.py

Prompts

```
['test that the ESPnet pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the ESPnet HuggingFace inference API pipelines', 'review the PipelineTestCase class to verify ESPnet allowed tasks and unsupported task handling', 'refactor the TESTABLE_MODELS dictionary to add or update ESPnet model mappings for speech tasks', 'test the automatic speech recognition API with a FLAC audio file and verify text output', 'test the ASR API error handling by sending a malformed FLAC audio file', 'test the automatic speech recognition API with a dual channel OGG audio file', 'test the automatic speech recognition API with a WebM audio file and verify text output', 'read an audio sample file from the samples directory and return its raw bytes', 'test the TextToSpeechTestCase to verify the TTS API returns valid audio/flac output for text input', 'test the TextToSpeechTestCase to verify the TTS API returns a 400 error for malformed binary input', 'run the TextToSpeechTestCase unittest suite to validate the ESPNet text-to-speech API endpoint', 'review the TextToSpeechTestCase class and its test methods for the ESPNet TTS API', 'refactor the TextToSpeechTestCase to add additional test cases for edge cases or new TTS features', 'run the DockerBuildTestCase to verify the docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'test that a docker image can be built from the project root directory', 'review the cd context manager class that handles directory changes with automatic restoration', 'refactor the cd context manager to support additional path resolution or error handling']
```

Usage

```
{'run_docker_build_test': 'run the DockerBuildTestCase to verify the docker image builds successfully', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'test_docker_image_build': 'test that a docker image can be built from the project root directory', 'review_cd_class': 'review the cd context manager class that handles directory changes with automatic restoration', 'refactor_cd_class': 'refactor the cd context manager to support additional path resolution or error handling'}
```

