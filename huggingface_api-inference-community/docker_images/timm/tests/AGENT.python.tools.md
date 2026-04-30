# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/timm/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for Hugging Face inference pipeline validation', 'summarize the TESTABLE_MODELS dictionary containing image-classification model IDs for testing', 'refactor test_unsupported_tasks to add additional unsupported task scenarios', 'test the image classification API endpoint with a sample JPEG image and validate the response', 'test the image classification API with a different resolution image to verify robustness', 'read a sample image file from the samples directory and return its binary payload', 'set environment variables for model ID and task to configure the image classification pipeline', 'restore original environment variables after running image classification tests', 'test that the docker image builds successfully from the project root directory', 'run a block of code in a different working directory using the cd context manager', 'review the cd context manager class that temporarily changes the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for Hugging Face inference pipeline validation', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary containing image-classification model IDs for testing', 'refactor_PipelineTestCase_test_unsupported_tasks': 'refactor test_unsupported_tasks to add additional unsupported task scenarios'}
```

## File: huggingface_api-inference-community/docker_images/timm/tests/test_api_image_classification.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for Hugging Face inference pipeline validation', 'summarize the TESTABLE_MODELS dictionary containing image-classification model IDs for testing', 'refactor test_unsupported_tasks to add additional unsupported task scenarios', 'test the image classification API endpoint with a sample JPEG image and validate the response', 'test the image classification API with a different resolution image to verify robustness', 'read a sample image file from the samples directory and return its binary payload', 'set environment variables for model ID and task to configure the image classification pipeline', 'restore original environment variables after running image classification tests', 'test that the docker image builds successfully from the project root directory', 'run a block of code in a different working directory using the cd context manager', 'review the cd context manager class that temporarily changes the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_image_classification_simple': 'test the image classification API endpoint with a sample JPEG image and validate the response', 'test_image_classification_different_resolution': 'test the image classification API with a different resolution image to verify robustness', 'read_sample_image': 'read a sample image file from the samples directory and return its binary payload', 'setup_image_classification_test': 'set environment variables for model ID and task to configure the image classification pipeline', 'teardown_image_classification_test': 'restore original environment variables after running image classification tests'}
```

## File: huggingface_api-inference-community/docker_images/timm/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for Hugging Face inference pipeline validation', 'summarize the TESTABLE_MODELS dictionary containing image-classification model IDs for testing', 'refactor test_unsupported_tasks to add additional unsupported task scenarios', 'test the image classification API endpoint with a sample JPEG image and validate the response', 'test the image classification API with a different resolution image to verify robustness', 'read a sample image file from the samples directory and return its binary payload', 'set environment variables for model ID and task to configure the image classification pipeline', 'restore original environment variables after running image classification tests', 'test that the docker image builds successfully from the project root directory', 'run a block of code in a different working directory using the cd context manager', 'review the cd context manager class that temporarily changes the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_docker_image_build': 'test that the docker image builds successfully from the project root directory', 'run_cd_context_manager': 'run a block of code in a different working directory using the cd context manager', 'review_cd_class': 'review the cd context manager class that temporarily changes the current working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments', 'summarize_docker_build_testcase': 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method'}
```

