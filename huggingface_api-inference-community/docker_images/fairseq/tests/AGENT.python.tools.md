# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/fairseq/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the unittest TestCase class PipelineTestCase for the fairseq inference API', 'review the TESTABLE_MODELS dictionary mapping task types to Hugging Face model IDs', 'review the ALL_TASKS set containing text-to-speech and audio-to-audio task types', 'test the audio-to-audio API by sending a valid FLAC file and verifying the JSON response', 'test the audio-to-audio API by sending a malformed FLAC file and verifying a 400 error', 'review the AudioToAudioTestCase class and its setUp, tearDown, and test methods for the audio-to-audio API', 'refactor the AudioToAudioTestCase read method to support additional audio file formats beyond FLAC', 'summarize the AudioToAudioTestCase class that tests the fairseq audio-to-audio inference endpoint', 'test the TextToSpeechTestCase test_simple method to verify TTS returns audio/flac response', 'test the TextToSpeechTestCase test_malformed_input method to verify 400 status on invalid UTF-8', 'run the TextToSpeechTestCase unittest class to validate the fairseq text-to-speech API endpoint', 'review the TextToSpeechTestCase class setup, teardown, and test methods for correctness', 'refactor the TextToSpeechTestCase to parameterize test inputs and expected responses', 'run the unittest test case that builds a docker image from the fairseq directory', 'test that the docker image can be built successfully from the fairseq project root', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'summarize the DockerBuildTestCase class that verifies docker build works from the project directory']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'run_pipeline_unit_tests': 'run the unittest TestCase class PipelineTestCase for the fairseq inference API', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary mapping task types to Hugging Face model IDs', 'review_ALL_TASKS': 'review the ALL_TASKS set containing text-to-speech and audio-to-audio task types'}
```

## File: huggingface_api-inference-community/docker_images/fairseq/tests/test_api_audio_to_audio.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the unittest TestCase class PipelineTestCase for the fairseq inference API', 'review the TESTABLE_MODELS dictionary mapping task types to Hugging Face model IDs', 'review the ALL_TASKS set containing text-to-speech and audio-to-audio task types', 'test the audio-to-audio API by sending a valid FLAC file and verifying the JSON response', 'test the audio-to-audio API by sending a malformed FLAC file and verifying a 400 error', 'review the AudioToAudioTestCase class and its setUp, tearDown, and test methods for the audio-to-audio API', 'refactor the AudioToAudioTestCase read method to support additional audio file formats beyond FLAC', 'summarize the AudioToAudioTestCase class that tests the fairseq audio-to-audio inference endpoint', 'test the TextToSpeechTestCase test_simple method to verify TTS returns audio/flac response', 'test the TextToSpeechTestCase test_malformed_input method to verify 400 status on invalid UTF-8', 'run the TextToSpeechTestCase unittest class to validate the fairseq text-to-speech API endpoint', 'review the TextToSpeechTestCase class setup, teardown, and test methods for correctness', 'refactor the TextToSpeechTestCase to parameterize test inputs and expected responses', 'run the unittest test case that builds a docker image from the fairseq directory', 'test that the docker image can be built successfully from the fairseq project root', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'summarize the DockerBuildTestCase class that verifies docker build works from the project directory']
```

Usage

```
{'test_audio_to_audio_simple': 'test the audio-to-audio API by sending a valid FLAC file and verifying the JSON response', 'test_audio_to_audio_malformed': 'test the audio-to-audio API by sending a malformed FLAC file and verifying a 400 error', 'review_AudioToAudioTestCase': 'review the AudioToAudioTestCase class and its setUp, tearDown, and test methods for the audio-to-audio API', 'refactor_AudioToAudioTestCase_read': 'refactor the AudioToAudioTestCase read method to support additional audio file formats beyond FLAC', 'summarize_AudioToAudioTestCase': 'summarize the AudioToAudioTestCase class that tests the fairseq audio-to-audio inference endpoint'}
```

## File: huggingface_api-inference-community/docker_images/fairseq/tests/test_api_text_to_speech.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the unittest TestCase class PipelineTestCase for the fairseq inference API', 'review the TESTABLE_MODELS dictionary mapping task types to Hugging Face model IDs', 'review the ALL_TASKS set containing text-to-speech and audio-to-audio task types', 'test the audio-to-audio API by sending a valid FLAC file and verifying the JSON response', 'test the audio-to-audio API by sending a malformed FLAC file and verifying a 400 error', 'review the AudioToAudioTestCase class and its setUp, tearDown, and test methods for the audio-to-audio API', 'refactor the AudioToAudioTestCase read method to support additional audio file formats beyond FLAC', 'summarize the AudioToAudioTestCase class that tests the fairseq audio-to-audio inference endpoint', 'test the TextToSpeechTestCase test_simple method to verify TTS returns audio/flac response', 'test the TextToSpeechTestCase test_malformed_input method to verify 400 status on invalid UTF-8', 'run the TextToSpeechTestCase unittest class to validate the fairseq text-to-speech API endpoint', 'review the TextToSpeechTestCase class setup, teardown, and test methods for correctness', 'refactor the TextToSpeechTestCase to parameterize test inputs and expected responses', 'run the unittest test case that builds a docker image from the fairseq directory', 'test that the docker image can be built successfully from the fairseq project root', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'summarize the DockerBuildTestCase class that verifies docker build works from the project directory']
```

Usage

```
{'test_text_to_speech_simple': 'test the TextToSpeechTestCase test_simple method to verify TTS returns audio/flac response', 'test_text_to_speech_malformed_input': 'test the TextToSpeechTestCase test_malformed_input method to verify 400 status on invalid UTF-8', 'run_text_to_speech_tests': 'run the TextToSpeechTestCase unittest class to validate the fairseq text-to-speech API endpoint', 'review_text_to_speech_testcase': 'review the TextToSpeechTestCase class setup, teardown, and test methods for correctness', 'refactor_text_to_speech_tests': 'refactor the TextToSpeechTestCase to parameterize test inputs and expected responses'}
```

## File: huggingface_api-inference-community/docker_images/fairseq/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the unittest TestCase class PipelineTestCase for the fairseq inference API', 'review the TESTABLE_MODELS dictionary mapping task types to Hugging Face model IDs', 'review the ALL_TASKS set containing text-to-speech and audio-to-audio task types', 'test the audio-to-audio API by sending a valid FLAC file and verifying the JSON response', 'test the audio-to-audio API by sending a malformed FLAC file and verifying a 400 error', 'review the AudioToAudioTestCase class and its setUp, tearDown, and test methods for the audio-to-audio API', 'refactor the AudioToAudioTestCase read method to support additional audio file formats beyond FLAC', 'summarize the AudioToAudioTestCase class that tests the fairseq audio-to-audio inference endpoint', 'test the TextToSpeechTestCase test_simple method to verify TTS returns audio/flac response', 'test the TextToSpeechTestCase test_malformed_input method to verify 400 status on invalid UTF-8', 'run the TextToSpeechTestCase unittest class to validate the fairseq text-to-speech API endpoint', 'review the TextToSpeechTestCase class setup, teardown, and test methods for correctness', 'refactor the TextToSpeechTestCase to parameterize test inputs and expected responses', 'run the unittest test case that builds a docker image from the fairseq directory', 'test that the docker image can be built successfully from the fairseq project root', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'summarize the DockerBuildTestCase class that verifies docker build works from the project directory']
```

Usage

```
{'run_docker_build_test': 'run the unittest test case that builds a docker image from the fairseq directory', 'test_docker_image_build': 'test that the docker image can be built successfully from the fairseq project root', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'summarize_docker_build_testcase': 'summarize the DockerBuildTestCase class that verifies docker build works from the project directory'}
```

