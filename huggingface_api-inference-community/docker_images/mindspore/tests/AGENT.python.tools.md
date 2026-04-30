# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/mindspore/tests/test_api.py

Prompts

```
['run the PipelineTestCase unittest class to verify allowed tasks and unsupported task handling', 'test that at least one task is enabled in ALLOWED_TASKS using unittest', 'test that unsupported tasks raise EnvironmentError when passed to get_pipeline', 'review the PipelineTestCase class and its test methods for HuggingFace MindSpore pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for image classification', 'test the image classification API by sending a JPEG image and verifying the response contains label and score fields', 'test the image classification API with a different resolution image to verify consistent label and score output', 'read a sample image file from the samples directory and return its binary payload for API testing', 'set up the test environment by configuring MODEL_ID and TASK environment variables for image classification', 'restore previous environment variables or delete MODEL_ID and TASK after running image classification tests', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that changes the working directory and restores it on exit', 'review the cd context manager class that handles temporary directory changes with os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'run_PipelineTestCase': 'run the PipelineTestCase unittest class to verify allowed tasks and unsupported task handling', 'test_PipelineTestCase_has_at_least_one_task_enabled': 'test that at least one task is enabled in ALLOWED_TASKS using unittest', 'test_PipelineTestCase_unsupported_tasks': 'test that unsupported tasks raise EnvironmentError when passed to get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for HuggingFace MindSpore pipeline validation', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for image classification'}
```

## File: huggingface_api-inference-community/docker_images/mindspore/tests/test_api_image_classification.py

Prompts

```
['run the PipelineTestCase unittest class to verify allowed tasks and unsupported task handling', 'test that at least one task is enabled in ALLOWED_TASKS using unittest', 'test that unsupported tasks raise EnvironmentError when passed to get_pipeline', 'review the PipelineTestCase class and its test methods for HuggingFace MindSpore pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for image classification', 'test the image classification API by sending a JPEG image and verifying the response contains label and score fields', 'test the image classification API with a different resolution image to verify consistent label and score output', 'read a sample image file from the samples directory and return its binary payload for API testing', 'set up the test environment by configuring MODEL_ID and TASK environment variables for image classification', 'restore previous environment variables or delete MODEL_ID and TASK after running image classification tests', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that changes the working directory and restores it on exit', 'review the cd context manager class that handles temporary directory changes with os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_image_classification_simple': 'test the image classification API by sending a JPEG image and verifying the response contains label and score fields', 'test_image_classification_different_resolution': 'test the image classification API with a different resolution image to verify consistent label and score output', 'read_sample_image': 'read a sample image file from the samples directory and return its binary payload for API testing', 'setup_image_classification_test': 'set up the test environment by configuring MODEL_ID and TASK environment variables for image classification', 'teardown_image_classification_test': 'restore previous environment variables or delete MODEL_ID and TASK after running image classification tests'}
```

## File: huggingface_api-inference-community/docker_images/mindspore/tests/test_docker_build.py

Prompts

```
['run the PipelineTestCase unittest class to verify allowed tasks and unsupported task handling', 'test that at least one task is enabled in ALLOWED_TASKS using unittest', 'test that unsupported tasks raise EnvironmentError when passed to get_pipeline', 'review the PipelineTestCase class and its test methods for HuggingFace MindSpore pipeline validation', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for image classification', 'test the image classification API by sending a JPEG image and verifying the response contains label and score fields', 'test the image classification API with a different resolution image to verify consistent label and score output', 'read a sample image file from the samples directory and return its binary payload for API testing', 'set up the test environment by configuring MODEL_ID and TASK environment variables for image classification', 'restore previous environment variables or delete MODEL_ID and TASK after running image classification tests', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using unittest and subprocess', 'create a context manager that changes the working directory and restores it on exit', 'review the cd context manager class that handles temporary directory changes with os.chdir', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image builds successfully using unittest and subprocess', 'create_cd_context_manager': 'create a context manager that changes the working directory and restores it on exit', 'review_cd_class': 'review the cd context manager class that handles temporary directory changes with os.chdir', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

