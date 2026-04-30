# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/stanza/tests/test_api.py

Prompts

```
['test that the Stanza pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest to validate Stanza inference pipeline task support', 'review the TESTABLE_MODELS dictionary containing token-classification examples for English and Turkish Stanza models', 'review the ALL_TASKS set listing all supported HuggingFace inference task types', 'test the token classification API endpoint with valid text inputs and verify entity group responses', 'test the token classification API endpoint with malformed UTF-8 input and verify 400 error response', 'test the token classification API by sending JSON inputs and checking entity group word start end score keys', 'test the token classification API by sending raw text input and verifying the response structure', 'review the TokenClassificationTestCase class and its parameterized test setup for token classification models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class for safe directory change and restoration', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the Stanza pipeline has at least one task enabled via ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run_pipeline_test_case': 'run the PipelineTestCase unittest to validate Stanza inference pipeline task support', 'review_testable_models': 'review the TESTABLE_MODELS dictionary containing token-classification examples for English and Turkish Stanza models', 'review_all_tasks': 'review the ALL_TASKS set listing all supported HuggingFace inference task types'}
```

## File: huggingface_api-inference-community/docker_images/stanza/tests/test_api_token_classification.py

Prompts

```
['test that the Stanza pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest to validate Stanza inference pipeline task support', 'review the TESTABLE_MODELS dictionary containing token-classification examples for English and Turkish Stanza models', 'review the ALL_TASKS set listing all supported HuggingFace inference task types', 'test the token classification API endpoint with valid text inputs and verify entity group responses', 'test the token classification API endpoint with malformed UTF-8 input and verify 400 error response', 'test the token classification API by sending JSON inputs and checking entity group word start end score keys', 'test the token classification API by sending raw text input and verifying the response structure', 'review the TokenClassificationTestCase class and its parameterized test setup for token classification models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class for safe directory change and restoration', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'test_token_classification_simple': 'test the token classification API endpoint with valid text inputs and verify entity group responses', 'test_token_classification_malformed': 'test the token classification API endpoint with malformed UTF-8 input and verify 400 error response', 'test_token_classification_json_input': 'test the token classification API by sending JSON inputs and checking entity group word start end score keys', 'test_token_classification_direct_input': 'test the token classification API by sending raw text input and verifying the response structure', 'review_token_classification_testcase': 'review the TokenClassificationTestCase class and its parameterized test setup for token classification models'}
```

## File: huggingface_api-inference-community/docker_images/stanza/tests/test_docker_build.py

Prompts

```
['test that the Stanza pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest to validate Stanza inference pipeline task support', 'review the TESTABLE_MODELS dictionary containing token-classification examples for English and Turkish Stanza models', 'review the ALL_TASKS set listing all supported HuggingFace inference task types', 'test the token classification API endpoint with valid text inputs and verify entity group responses', 'test the token classification API endpoint with malformed UTF-8 input and verify 400 error response', 'test the token classification API by sending JSON inputs and checking entity group word start end score keys', 'test the token classification API by sending raw text input and verifying the response structure', 'review the TokenClassificationTestCase class and its parameterized test setup for token classification models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using unittest', 'create a context manager that temporarily changes the working directory and restores it on exit', 'review the cd context manager class for safe directory change and restoration', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project directory', 'test_docker_build': 'test that the docker image builds successfully using unittest', 'create_cd_context_manager': 'create a context manager that temporarily changes the working directory and restores it on exit', 'review_cd_class': 'review the cd context manager class for safe directory change and restoration', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images from a configurable path'}
```

