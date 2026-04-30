# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/bertopic/tests/test_api.py

Prompts

```
['test that the BERTopic pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the BERTopic inference API', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to BERTopic model IDs', 'summarize the ALL_TASKS set containing all Hugging Face pipeline task types', 'test the text classification API endpoint with a simple input sentence and verify label score output', 'test the text classification API endpoint with malformed binary data and verify a 400 error response', 'test the text classification API against multiple parameterized model IDs using parameterized_class decorator', 'test the text classification API with both JSON dict and raw string input formats', 'test the text classification API with proper MODEL_ID and TASK environment variable setup and teardown', 'build a docker image by running docker build in the project root directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'test that the docker image can be built successfully from the project directory', 'review the cd context manager class that handles temporary directory changes with path expansion', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the BERTopic pipeline has at least one task enabled via ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for the BERTopic inference API', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping text-classification to BERTopic model IDs', 'summarize_ALL_TASKS': 'summarize the ALL_TASKS set containing all Hugging Face pipeline task types'}
```

## File: huggingface_api-inference-community/docker_images/bertopic/tests/test_api_text_classification.py

Prompts

```
['test that the BERTopic pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the BERTopic inference API', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to BERTopic model IDs', 'summarize the ALL_TASKS set containing all Hugging Face pipeline task types', 'test the text classification API endpoint with a simple input sentence and verify label score output', 'test the text classification API endpoint with malformed binary data and verify a 400 error response', 'test the text classification API against multiple parameterized model IDs using parameterized_class decorator', 'test the text classification API with both JSON dict and raw string input formats', 'test the text classification API with proper MODEL_ID and TASK environment variable setup and teardown', 'build a docker image by running docker build in the project root directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'test that the docker image can be built successfully from the project directory', 'review the cd context manager class that handles temporary directory changes with path expansion', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_text_classification_simple': 'test the text classification API endpoint with a simple input sentence and verify label score output', 'test_text_classification_malformed_input': 'test the text classification API endpoint with malformed binary data and verify a 400 error response', 'test_text_classification_parameterized_models': 'test the text classification API against multiple parameterized model IDs using parameterized_class decorator', 'test_text_classification_json_and_raw_input': 'test the text classification API with both JSON dict and raw string input formats', 'test_text_classification_env_setup_teardown': 'test the text classification API with proper MODEL_ID and TASK environment variable setup and teardown'}
```

## File: huggingface_api-inference-community/docker_images/bertopic/tests/test_docker_build.py

Prompts

```
['test that the BERTopic pipeline has at least one task enabled via ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the BERTopic inference API', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to BERTopic model IDs', 'summarize the ALL_TASKS set containing all Hugging Face pipeline task types', 'test the text classification API endpoint with a simple input sentence and verify label score output', 'test the text classification API endpoint with malformed binary data and verify a 400 error response', 'test the text classification API against multiple parameterized model IDs using parameterized_class decorator', 'test the text classification API with both JSON dict and raw string input formats', 'test the text classification API with proper MODEL_ID and TASK environment variable setup and teardown', 'build a docker image by running docker build in the project root directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'test that the docker image can be built successfully from the project directory', 'review the cd context manager class that handles temporary directory changes with path expansion', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'create_cd_context_manager': 'create a context manager that temporarily changes the working directory and restores it on exit', 'test_docker_build': 'test that the docker image can be built successfully from the project directory', 'review_cd_class': 'review the cd context manager class that handles temporary directory changes with path expansion', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

