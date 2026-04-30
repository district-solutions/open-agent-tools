# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/nemo/tests/test_api.py

Prompts

```
['test that the pipeline has at least one allowed task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for Hugging Face inference pipeline validation', 'review the PipelineTestCase class and its test methods for pipeline validation logic', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'review the AutomaticSpeecRecognitionTestCase class and its test methods for ASR API coverage', 'build a docker image by running docker build in the project directory', 'test that the docker image can be built successfully from the project root', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager that changes and restores the working directory', 'run the DockerBuildTestCase to verify the docker image builds without errors']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the pipeline has at least one allowed task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run_pipeline_test_suite': 'run the unittest test suite for Hugging Face inference pipeline validation', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for pipeline validation logic', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs'}
```

## File: huggingface_api-inference-community/docker_images/nemo/tests/test_api_automatic_speech_recognition.py

Prompts

```
['test that the pipeline has at least one allowed task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for Hugging Face inference pipeline validation', 'review the PipelineTestCase class and its test methods for pipeline validation logic', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'review the AutomaticSpeecRecognitionTestCase class and its test methods for ASR API coverage', 'build a docker image by running docker build in the project directory', 'test that the docker image can be built successfully from the project root', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager that changes and restores the working directory', 'run the DockerBuildTestCase to verify the docker image builds without errors']
```

Usage

```
{'test_simple_asr': 'test the automatic speech recognition API with a simple FLAC audio file', 'test_malformed_audio_asr': 'test the ASR API returns 400 error for malformed audio files', 'test_dual_channel_asr': 'test the ASR API handles dual channel OGG audio files correctly', 'test_webm_asr': 'test the ASR API processes WebM audio files and returns transcribed text', 'review_asr_test_class': 'review the AutomaticSpeecRecognitionTestCase class and its test methods for ASR API coverage'}
```

## File: huggingface_api-inference-community/docker_images/nemo/tests/test_docker_build.py

Prompts

```
['test that the pipeline has at least one allowed task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the unittest test suite for Hugging Face inference pipeline validation', 'review the PipelineTestCase class and its test methods for pipeline validation logic', 'summarize the TESTABLE_MODELS dictionary mapping tasks to model IDs', 'test the automatic speech recognition API with a simple FLAC audio file', 'test the ASR API returns 400 error for malformed audio files', 'test the ASR API handles dual channel OGG audio files correctly', 'test the ASR API processes WebM audio files and returns transcribed text', 'review the AutomaticSpeecRecognitionTestCase class and its test methods for ASR API coverage', 'build a docker image by running docker build in the project directory', 'test that the docker image can be built successfully from the project root', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager that changes and restores the working directory', 'run the DockerBuildTestCase to verify the docker image builds without errors']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project directory', 'test_docker_build': 'test that the docker image can be built successfully from the project root', 'cd_context_manager': 'use the cd context manager to temporarily change the working directory', 'review_cd_class': 'review the cd class context manager that changes and restores the working directory', 'run_docker_build_test': 'run the DockerBuildTestCase to verify the docker image builds without errors'}
```

