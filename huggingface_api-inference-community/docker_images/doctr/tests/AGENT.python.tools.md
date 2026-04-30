# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/doctr/tests/test_api.py

Prompts

```
['run the PipelineTestCase unittest class to validate allowed tasks and unsupported task handling', 'test that at least one pipeline task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for correctness and coverage', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for testing', 'test the object detection API by sending an image and verifying the response contains labels, scores, and bounding boxes', 'run the ObjectDetectionTestCase to validate the object detection endpoint returns correct JSON response format', 'review the ObjectDetectionTestCase class that tests object detection with parameterized model IDs and sample images', 'create a test that reads an image file and posts it to the object detection API endpoint', 'refactor the ObjectDetectionTestCase to add new test cases for different image formats or edge cases', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully from the project directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution features', 'review the DockerBuildTestCase class and its test_can_build_docker_image method for correctness']
```

Usage

```
{'run_PipelineTestCase': 'run the PipelineTestCase unittest class to validate allowed tasks and unsupported task handling', 'test_test_has_at_least_one_task_enabled': 'test that at least one pipeline task is enabled in ALLOWED_TASKS', 'test_test_unsupported_tasks': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for correctness and coverage', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for testing'}
```

## File: huggingface_api-inference-community/docker_images/doctr/tests/test_api_object_detection.py

Prompts

```
['run the PipelineTestCase unittest class to validate allowed tasks and unsupported task handling', 'test that at least one pipeline task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for correctness and coverage', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for testing', 'test the object detection API by sending an image and verifying the response contains labels, scores, and bounding boxes', 'run the ObjectDetectionTestCase to validate the object detection endpoint returns correct JSON response format', 'review the ObjectDetectionTestCase class that tests object detection with parameterized model IDs and sample images', 'create a test that reads an image file and posts it to the object detection API endpoint', 'refactor the ObjectDetectionTestCase to add new test cases for different image formats or edge cases', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully from the project directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution features', 'review the DockerBuildTestCase class and its test_can_build_docker_image method for correctness']
```

Usage

```
{'test_object_detection_api': 'test the object detection API by sending an image and verifying the response contains labels, scores, and bounding boxes', 'run_object_detection_test': 'run the ObjectDetectionTestCase to validate the object detection endpoint returns correct JSON response format', 'review_object_detection_testcase': 'review the ObjectDetectionTestCase class that tests object detection with parameterized model IDs and sample images', 'create_object_detection_test': 'create a test that reads an image file and posts it to the object detection API endpoint', 'refactor_object_detection_testcase': 'refactor the ObjectDetectionTestCase to add new test cases for different image formats or edge cases'}
```

## File: huggingface_api-inference-community/docker_images/doctr/tests/test_docker_build.py

Prompts

```
['run the PipelineTestCase unittest class to validate allowed tasks and unsupported task handling', 'test that at least one pipeline task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for correctness and coverage', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for testing', 'test the object detection API by sending an image and verifying the response contains labels, scores, and bounding boxes', 'run the ObjectDetectionTestCase to validate the object detection endpoint returns correct JSON response format', 'review the ObjectDetectionTestCase class that tests object detection with parameterized model IDs and sample images', 'create a test that reads an image file and posts it to the object detection API endpoint', 'refactor the ObjectDetectionTestCase to add new test cases for different image formats or edge cases', 'build a docker image by running docker build in the project root directory', 'test that the docker image can be built successfully from the project directory', 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor the cd context manager class to support additional path resolution features', 'review the DockerBuildTestCase class and its test_can_build_docker_image method for correctness']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image can be built successfully from the project directory', 'create_cd_context_manager': 'create a context manager that temporarily changes the working directory and restores it on exit', 'refactor_cd_class': 'refactor the cd context manager class to support additional path resolution features', 'review_docker_build_test': 'review the DockerBuildTestCase class and its test_can_build_docker_image method for correctness'}
```

