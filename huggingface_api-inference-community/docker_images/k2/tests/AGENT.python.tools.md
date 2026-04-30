# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/k2/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the k2 automatic speech recognition pipeline', 'review the PipelineTestCase class and its test methods for the k2 inference API', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs for speech recognition', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns a 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'read an audio sample file from the samples directory and return its bytes', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class that handles directory changes with os.getcwd and os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run_pipeline_unit_tests': 'run the unittest test suite for the k2 automatic speech recognition pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for the k2 inference API', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs for speech recognition'}
```

## File: huggingface_api-inference-community/docker_images/k2/tests/test_api_automatic_speech_recognition.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the k2 automatic speech recognition pipeline', 'review the PipelineTestCase class and its test methods for the k2 inference API', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs for speech recognition', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns a 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'read an audio sample file from the samples directory and return its bytes', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class that handles directory changes with os.getcwd and os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_simple_asr': 'test the automatic speech recognition API with a simple FLAC audio file', 'test_malformed_audio_asr': 'test the ASR API returns a 400 error for malformed audio files', 'test_dual_channel_asr': 'test the ASR API handles dual channel OGG audio files correctly', 'test_webm_asr': 'test the ASR API processes WebM audio files and returns transcribed text', 'read_audio_sample': 'read an audio sample file from the samples directory and return its bytes'}
```

## File: huggingface_api-inference-community/docker_images/k2/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for the k2 automatic speech recognition pipeline', 'review the PipelineTestCase class and its test methods for the k2 inference API', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs for speech recognition', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns a 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'read an audio sample file from the samples directory and return its bytes', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class that handles directory changes with os.getcwd and os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image builds successfully using unittest and subprocess', 'create_cd_context_manager': 'create a context manager that temporarily changes the working directory and restores it on exit', 'review_cd_class': 'review the cd context manager class that handles directory changes with os.getcwd and os.chdir', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

