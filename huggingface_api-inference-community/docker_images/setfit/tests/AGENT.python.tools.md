# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/setfit/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one ML task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class that validates allowed and unsupported ML pipeline tasks', 'run the PipelineTestCase unittest suite to validate the setfit inference API pipeline configuration', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to a setfit MiniLM model ID', 'test the text classification API endpoint with a simple input sentence', 'test the text classification API endpoint with malformed UTF-8 input bytes', 'test the TextClassificationTestCase class to verify text classification API responses', 'review the TextClassificationTestCase class and its test methods for text classification', 'refactor the TextClassificationTestCase class to add additional test cases for edge cases', 'build a docker image by running docker build from the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd class that implements __enter__ and __exit__ for directory switching', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_PipelineTestCase_has_at_least_one_task_enabled': 'test the PipelineTestCase to verify at least one ML task is enabled in ALLOWED_TASKS', 'test_PipelineTestCase_unsupported_tasks': 'test the PipelineTestCase to verify unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class that validates allowed and unsupported ML pipeline tasks', 'run_PipelineTestCase_tests': 'run the PipelineTestCase unittest suite to validate the setfit inference API pipeline configuration', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping text-classification to a setfit MiniLM model ID'}
```

## File: huggingface_api-inference-community/docker_images/setfit/tests/test_api_text_classification.py

Prompts

```
['test the PipelineTestCase to verify at least one ML task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class that validates allowed and unsupported ML pipeline tasks', 'run the PipelineTestCase unittest suite to validate the setfit inference API pipeline configuration', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to a setfit MiniLM model ID', 'test the text classification API endpoint with a simple input sentence', 'test the text classification API endpoint with malformed UTF-8 input bytes', 'test the TextClassificationTestCase class to verify text classification API responses', 'review the TextClassificationTestCase class and its test methods for text classification', 'refactor the TextClassificationTestCase class to add additional test cases for edge cases', 'build a docker image by running docker build from the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd class that implements __enter__ and __exit__ for directory switching', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_text_classification_simple': 'test the text classification API endpoint with a simple input sentence', 'test_text_classification_malformed': 'test the text classification API endpoint with malformed UTF-8 input bytes', 'test_TextClassificationTestCase': 'test the TextClassificationTestCase class to verify text classification API responses', 'review_TextClassificationTestCase': 'review the TextClassificationTestCase class and its test methods for text classification', 'refactor_TextClassificationTestCase': 'refactor the TextClassificationTestCase class to add additional test cases for edge cases'}
```

## File: huggingface_api-inference-community/docker_images/setfit/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one ML task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class that validates allowed and unsupported ML pipeline tasks', 'run the PipelineTestCase unittest suite to validate the setfit inference API pipeline configuration', 'summarize the TESTABLE_MODELS dictionary mapping text-classification to a setfit MiniLM model ID', 'test the text classification API endpoint with a simple input sentence', 'test the text classification API endpoint with malformed UTF-8 input bytes', 'test the TextClassificationTestCase class to verify text classification API responses', 'review the TextClassificationTestCase class and its test methods for text classification', 'refactor the TextClassificationTestCase class to add additional test cases for edge cases', 'build a docker image by running docker build from the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd class that implements __enter__ and __exit__ for directory switching', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build from the project root directory', 'test_docker_build': 'test that the docker image builds successfully using unittest and subprocess', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd class that implements __enter__ and __exit__ for directory switching', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

