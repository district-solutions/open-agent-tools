# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/span_marker/tests/test_api.py

Prompts

```
['test that the span marker pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the span marker model', 'review the TESTABLE_MODELS dictionary mapping token classification to the span marker bert tiny model', 'refactor the ALL_TASKS set to add or remove supported HuggingFace inference tasks', 'test the token classification API endpoint with a simple text input string', 'test the token classification API endpoint with malformed UTF-8 binary data', 'test the token classification API by sending JSON input with an inputs key', 'test the token classification API by sending raw string input directly', 'test that the token classification response contains entity_group, word, start, end, and score keys', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the cd context manager to support additional path expansion or error handling']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the span marker pipeline has at least one task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run_pipeline_test_case': 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the span marker model', 'review_testable_models_dict': 'review the TESTABLE_MODELS dictionary mapping token classification to the span marker bert tiny model', 'refactor_all_tasks_set': 'refactor the ALL_TASKS set to add or remove supported HuggingFace inference tasks'}
```

## File: huggingface_api-inference-community/docker_images/span_marker/tests/test_api_token_classification.py

Prompts

```
['test that the span marker pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the span marker model', 'review the TESTABLE_MODELS dictionary mapping token classification to the span marker bert tiny model', 'refactor the ALL_TASKS set to add or remove supported HuggingFace inference tasks', 'test the token classification API endpoint with a simple text input string', 'test the token classification API endpoint with malformed UTF-8 binary data', 'test the token classification API by sending JSON input with an inputs key', 'test the token classification API by sending raw string input directly', 'test that the token classification response contains entity_group, word, start, end, and score keys', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the cd context manager to support additional path expansion or error handling']
```

Usage

```
{'test_token_classification_simple': 'test the token classification API endpoint with a simple text input string', 'test_token_classification_malformed': 'test the token classification API endpoint with malformed UTF-8 binary data', 'test_token_classification_json_input': 'test the token classification API by sending JSON input with an inputs key', 'test_token_classification_raw_input': 'test the token classification API by sending raw string input directly', 'test_token_classification_response_schema': 'test that the token classification response contains entity_group, word, start, end, and score keys'}
```

## File: huggingface_api-inference-community/docker_images/span_marker/tests/test_docker_build.py

Prompts

```
['test that the span marker pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the span marker model', 'review the TESTABLE_MODELS dictionary mapping token classification to the span marker bert tiny model', 'refactor the ALL_TASKS set to add or remove supported HuggingFace inference tasks', 'test the token classification API endpoint with a simple text input string', 'test the token classification API endpoint with malformed UTF-8 binary data', 'test the token classification API by sending JSON input with an inputs key', 'test the token classification API by sending raw string input directly', 'test that the token classification response contains entity_group, word, start, end, and score keys', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the cd context manager to support additional path expansion or error handling']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'refactor_cd_class': 'refactor the cd context manager to support additional path expansion or error handling'}
```

