# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/flair/tests/test_api.py

Prompts

```
['test that at least one pipeline task is enabled in the Flair inference docker image', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline in the Flair module', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the Flair inference API', 'review the TESTABLE_MODELS dictionary mapping token-classification tasks to Flair model IDs for testing', 'review the ALL_TASKS set listing all HuggingFace inference tasks used to identify unsupported ones', 'test the token classification API with a simple sentence input and verify entity group output', 'test the token classification API with malformed UTF-8 bytes and verify a 400 error response', 'run the parameterized token classification test suite against all testable Flair models', 'review the TokenClassificationTestCase class that tests entity extraction with entity_group, word, start, end, and score fields', 'refactor the TokenClassificationTestCase to add new test cases for edge cases in token classification', 'test that the flair docker image builds successfully using docker build', 'test the cd context manager for changing the current working directory', 'run the DockerBuildTestCase to verify the docker image can be built', 'review the cd context manager class that changes and restores the working directory', 'refactor the DockerBuildTestCase to support building with custom docker build arguments']
```

Usage

```
{'test_pipeline_tasks_enabled': 'test that at least one pipeline task is enabled in the Flair inference docker image', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline in the Flair module', 'run_PipelineTestCase': 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the Flair inference API', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary mapping token-classification tasks to Flair model IDs for testing', 'review_ALL_TASKS': 'review the ALL_TASKS set listing all HuggingFace inference tasks used to identify unsupported ones'}
```

## File: huggingface_api-inference-community/docker_images/flair/tests/test_api_token_classification.py

Prompts

```
['test that at least one pipeline task is enabled in the Flair inference docker image', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline in the Flair module', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the Flair inference API', 'review the TESTABLE_MODELS dictionary mapping token-classification tasks to Flair model IDs for testing', 'review the ALL_TASKS set listing all HuggingFace inference tasks used to identify unsupported ones', 'test the token classification API with a simple sentence input and verify entity group output', 'test the token classification API with malformed UTF-8 bytes and verify a 400 error response', 'run the parameterized token classification test suite against all testable Flair models', 'review the TokenClassificationTestCase class that tests entity extraction with entity_group, word, start, end, and score fields', 'refactor the TokenClassificationTestCase to add new test cases for edge cases in token classification', 'test that the flair docker image builds successfully using docker build', 'test the cd context manager for changing the current working directory', 'run the DockerBuildTestCase to verify the docker image can be built', 'review the cd context manager class that changes and restores the working directory', 'refactor the DockerBuildTestCase to support building with custom docker build arguments']
```

Usage

```
{'test_token_classification_simple': 'test the token classification API with a simple sentence input and verify entity group output', 'test_token_classification_malformed_input': 'test the token classification API with malformed UTF-8 bytes and verify a 400 error response', 'run_token_classification_tests': 'run the parameterized token classification test suite against all testable Flair models', 'review_token_classification_testcase': 'review the TokenClassificationTestCase class that tests entity extraction with entity_group, word, start, end, and score fields', 'refactor_token_classification_testcase': 'refactor the TokenClassificationTestCase to add new test cases for edge cases in token classification'}
```

## File: huggingface_api-inference-community/docker_images/flair/tests/test_docker_build.py

Prompts

```
['test that at least one pipeline task is enabled in the Flair inference docker image', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline in the Flair module', 'run the PipelineTestCase unittest class to validate allowed and unsupported tasks for the Flair inference API', 'review the TESTABLE_MODELS dictionary mapping token-classification tasks to Flair model IDs for testing', 'review the ALL_TASKS set listing all HuggingFace inference tasks used to identify unsupported ones', 'test the token classification API with a simple sentence input and verify entity group output', 'test the token classification API with malformed UTF-8 bytes and verify a 400 error response', 'run the parameterized token classification test suite against all testable Flair models', 'review the TokenClassificationTestCase class that tests entity extraction with entity_group, word, start, end, and score fields', 'refactor the TokenClassificationTestCase to add new test cases for edge cases in token classification', 'test that the flair docker image builds successfully using docker build', 'test the cd context manager for changing the current working directory', 'run the DockerBuildTestCase to verify the docker image can be built', 'review the cd context manager class that changes and restores the working directory', 'refactor the DockerBuildTestCase to support building with custom docker build arguments']
```

Usage

```
{'test_docker_build': 'test that the flair docker image builds successfully using docker build', 'test_cd_context_manager': 'test the cd context manager for changing the current working directory', 'run_docker_build_test': 'run the DockerBuildTestCase to verify the docker image can be built', 'review_cd_class': 'review the cd context manager class that changes and restores the working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building with custom docker build arguments'}
```

