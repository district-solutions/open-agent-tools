# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/asteroid/tests/test_api.py

Prompts

```
['test that the pipeline has at least one task enabled using PipelineTestCase', 'test that get_pipeline raises EnvironmentError for unsupported tasks', 'review the PipelineTestCase class and its test methods for HuggingFace pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping audio tasks to HuggingFace model IDs', 'refactor the get_pipeline call to support additional task types from ALL_TASKS', 'test the audio source separation API with a FLAC audio file and verify the response', 'test the audio source separation API with a malformed audio file and verify error handling', 'test the audio source separation API with a dual channel OGG audio file', 'test the audio source separation API with a WebM audio file and verify the response', 'read an audio sample file from the samples directory and return its binary payload', 'test the audio-to-audio API endpoint by sending a FLAC audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a malformed FLAC file and verifying the 400 error response', 'test the audio-to-audio API endpoint by sending a dual-channel OGG audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a WebM audio file and verifying the JSON response', 'review the AudioToAudioTestCase class and its setUp and tearDown methods for environment variable management', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution options', 'review the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the pipeline has at least one task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that get_pipeline raises EnvironmentError for unsupported tasks', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for HuggingFace pipeline validation', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping audio tasks to HuggingFace model IDs', 'refactor_get_pipeline_call': 'refactor the get_pipeline call to support additional task types from ALL_TASKS'}
```

## File: huggingface_api-inference-community/docker_images/asteroid/tests/test_api_audio_source_separation.py

Prompts

```
['test that the pipeline has at least one task enabled using PipelineTestCase', 'test that get_pipeline raises EnvironmentError for unsupported tasks', 'review the PipelineTestCase class and its test methods for HuggingFace pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping audio tasks to HuggingFace model IDs', 'refactor the get_pipeline call to support additional task types from ALL_TASKS', 'test the audio source separation API with a FLAC audio file and verify the response', 'test the audio source separation API with a malformed audio file and verify error handling', 'test the audio source separation API with a dual channel OGG audio file', 'test the audio source separation API with a WebM audio file and verify the response', 'read an audio sample file from the samples directory and return its binary payload', 'test the audio-to-audio API endpoint by sending a FLAC audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a malformed FLAC file and verifying the 400 error response', 'test the audio-to-audio API endpoint by sending a dual-channel OGG audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a WebM audio file and verifying the JSON response', 'review the AudioToAudioTestCase class and its setUp and tearDown methods for environment variable management', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution options', 'review the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_audio_source_separation_simple': 'test the audio source separation API with a FLAC audio file and verify the response', 'test_audio_source_separation_malformed': 'test the audio source separation API with a malformed audio file and verify error handling', 'test_audio_source_separation_dual_channel': 'test the audio source separation API with a dual channel OGG audio file', 'test_audio_source_separation_webm': 'test the audio source separation API with a WebM audio file and verify the response', 'read_audio_sample': 'read an audio sample file from the samples directory and return its binary payload'}
```

## File: huggingface_api-inference-community/docker_images/asteroid/tests/test_api_audio_to_audio.py

Prompts

```
['test that the pipeline has at least one task enabled using PipelineTestCase', 'test that get_pipeline raises EnvironmentError for unsupported tasks', 'review the PipelineTestCase class and its test methods for HuggingFace pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping audio tasks to HuggingFace model IDs', 'refactor the get_pipeline call to support additional task types from ALL_TASKS', 'test the audio source separation API with a FLAC audio file and verify the response', 'test the audio source separation API with a malformed audio file and verify error handling', 'test the audio source separation API with a dual channel OGG audio file', 'test the audio source separation API with a WebM audio file and verify the response', 'read an audio sample file from the samples directory and return its binary payload', 'test the audio-to-audio API endpoint by sending a FLAC audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a malformed FLAC file and verifying the 400 error response', 'test the audio-to-audio API endpoint by sending a dual-channel OGG audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a WebM audio file and verifying the JSON response', 'review the AudioToAudioTestCase class and its setUp and tearDown methods for environment variable management', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution options', 'review the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_audio_to_audio_simple': 'test the audio-to-audio API endpoint by sending a FLAC audio file and verifying the JSON response', 'test_audio_to_audio_malformed': 'test the audio-to-audio API endpoint by sending a malformed FLAC file and verifying the 400 error response', 'test_audio_to_audio_dual_channel': 'test the audio-to-audio API endpoint by sending a dual-channel OGG audio file and verifying the JSON response', 'test_audio_to_audio_webm': 'test the audio-to-audio API endpoint by sending a WebM audio file and verifying the JSON response', 'review_AudioToAudioTestCase': 'review the AudioToAudioTestCase class and its setUp and tearDown methods for environment variable management'}
```

## File: huggingface_api-inference-community/docker_images/asteroid/tests/test_docker_build.py

Prompts

```
['test that the pipeline has at least one task enabled using PipelineTestCase', 'test that get_pipeline raises EnvironmentError for unsupported tasks', 'review the PipelineTestCase class and its test methods for HuggingFace pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping audio tasks to HuggingFace model IDs', 'refactor the get_pipeline call to support additional task types from ALL_TASKS', 'test the audio source separation API with a FLAC audio file and verify the response', 'test the audio source separation API with a malformed audio file and verify error handling', 'test the audio source separation API with a dual channel OGG audio file', 'test the audio source separation API with a WebM audio file and verify the response', 'read an audio sample file from the samples directory and return its binary payload', 'test the audio-to-audio API endpoint by sending a FLAC audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a malformed FLAC file and verifying the 400 error response', 'test the audio-to-audio API endpoint by sending a dual-channel OGG audio file and verifying the JSON response', 'test the audio-to-audio API endpoint by sending a WebM audio file and verifying the JSON response', 'review the AudioToAudioTestCase class and its setUp and tearDown methods for environment variable management', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution options', 'review the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image can be built successfully using unittest', 'create_cd_context_manager': 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor_cd_class': 'refactor the cd context manager class to support additional path resolution options', 'review_docker_build_test': 'review the DockerBuildTestCase class and its test_can_build_docker_image method'}
```

