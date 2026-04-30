# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/diffusers/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping diffusers pipeline tasks to test model IDs', 'review the ALL_TASKS set containing all Hugging Face inference task names', 'run the PipelineTestCase unittest class to validate diffusers pipeline task support', 'test the image-to-image API endpoint by sending a base64 encoded JPEG image with a prompt parameter', 'test the image-to-image API endpoint by sending malformed binary data and verifying a 400 error response', 'test the image-to-image API against all parameterized models listed in TESTABLE_MODELS for the image-to-image task', 'review the ImageToImageTestCase class that sets up and tears down MODEL_ID and TASK environment variables for each test', 'test the image-to-image pipeline by clearing the get_pipeline cache before running parameterized model tests', 'run the TextToImageTestCase test suite to validate the text-to-image API endpoint', 'test the text-to-image API by sending a prompt and verifying a valid image response', 'test that the text-to-image API returns a 400 error for malformed binary input', 'review the TextToImageTestCase class to understand the parameterized test setup for diffusers models', 'summarize the text-to-image test file covering simple prompt and malformed input test cases', 'run the docker build test that builds a docker image from the diffusers directory', 'test that the docker image can be built successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary mapping diffusers pipeline tasks to test model IDs', 'review_ALL_TASKS': 'review the ALL_TASKS set containing all Hugging Face inference task names', 'run_PipelineTestCase': 'run the PipelineTestCase unittest class to validate diffusers pipeline task support'}
```

## File: huggingface_api-inference-community/docker_images/diffusers/tests/test_api_image_to_image.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping diffusers pipeline tasks to test model IDs', 'review the ALL_TASKS set containing all Hugging Face inference task names', 'run the PipelineTestCase unittest class to validate diffusers pipeline task support', 'test the image-to-image API endpoint by sending a base64 encoded JPEG image with a prompt parameter', 'test the image-to-image API endpoint by sending malformed binary data and verifying a 400 error response', 'test the image-to-image API against all parameterized models listed in TESTABLE_MODELS for the image-to-image task', 'review the ImageToImageTestCase class that sets up and tears down MODEL_ID and TASK environment variables for each test', 'test the image-to-image pipeline by clearing the get_pipeline cache before running parameterized model tests', 'run the TextToImageTestCase test suite to validate the text-to-image API endpoint', 'test the text-to-image API by sending a prompt and verifying a valid image response', 'test that the text-to-image API returns a 400 error for malformed binary input', 'review the TextToImageTestCase class to understand the parameterized test setup for diffusers models', 'summarize the text-to-image test file covering simple prompt and malformed input test cases', 'run the docker build test that builds a docker image from the diffusers directory', 'test that the docker image can be built successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'test_image_to_image_simple': 'test the image-to-image API endpoint by sending a base64 encoded JPEG image with a prompt parameter', 'test_image_to_image_malformed_input': 'test the image-to-image API endpoint by sending malformed binary data and verifying a 400 error response', 'test_image_to_image_parameterized_models': 'test the image-to-image API against all parameterized models listed in TESTABLE_MODELS for the image-to-image task', 'review_ImageToImageTestCase': 'review the ImageToImageTestCase class that sets up and tears down MODEL_ID and TASK environment variables for each test', 'test_image_to_image_pipeline_cache': 'test the image-to-image pipeline by clearing the get_pipeline cache before running parameterized model tests'}
```

## File: huggingface_api-inference-community/docker_images/diffusers/tests/test_api_text_to_image.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping diffusers pipeline tasks to test model IDs', 'review the ALL_TASKS set containing all Hugging Face inference task names', 'run the PipelineTestCase unittest class to validate diffusers pipeline task support', 'test the image-to-image API endpoint by sending a base64 encoded JPEG image with a prompt parameter', 'test the image-to-image API endpoint by sending malformed binary data and verifying a 400 error response', 'test the image-to-image API against all parameterized models listed in TESTABLE_MODELS for the image-to-image task', 'review the ImageToImageTestCase class that sets up and tears down MODEL_ID and TASK environment variables for each test', 'test the image-to-image pipeline by clearing the get_pipeline cache before running parameterized model tests', 'run the TextToImageTestCase test suite to validate the text-to-image API endpoint', 'test the text-to-image API by sending a prompt and verifying a valid image response', 'test that the text-to-image API returns a 400 error for malformed binary input', 'review the TextToImageTestCase class to understand the parameterized test setup for diffusers models', 'summarize the text-to-image test file covering simple prompt and malformed input test cases', 'run the docker build test that builds a docker image from the diffusers directory', 'test that the docker image can be built successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'run_text_to_image_tests': 'run the TextToImageTestCase test suite to validate the text-to-image API endpoint', 'test_simple_text_to_image': 'test the text-to-image API by sending a prompt and verifying a valid image response', 'test_malformed_input_handling': 'test that the text-to-image API returns a 400 error for malformed binary input', 'review_TextToImageTestCase': 'review the TextToImageTestCase class to understand the parameterized test setup for diffusers models', 'summarize_text_to_image_test': 'summarize the text-to-image test file covering simple prompt and malformed input test cases'}
```

## File: huggingface_api-inference-community/docker_images/diffusers/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping diffusers pipeline tasks to test model IDs', 'review the ALL_TASKS set containing all Hugging Face inference task names', 'run the PipelineTestCase unittest class to validate diffusers pipeline task support', 'test the image-to-image API endpoint by sending a base64 encoded JPEG image with a prompt parameter', 'test the image-to-image API endpoint by sending malformed binary data and verifying a 400 error response', 'test the image-to-image API against all parameterized models listed in TESTABLE_MODELS for the image-to-image task', 'review the ImageToImageTestCase class that sets up and tears down MODEL_ID and TASK environment variables for each test', 'test the image-to-image pipeline by clearing the get_pipeline cache before running parameterized model tests', 'run the TextToImageTestCase test suite to validate the text-to-image API endpoint', 'test the text-to-image API by sending a prompt and verifying a valid image response', 'test that the text-to-image API returns a 400 error for malformed binary input', 'review the TextToImageTestCase class to understand the parameterized test setup for diffusers models', 'summarize the text-to-image test file covering simple prompt and malformed input test cases', 'run the docker build test that builds a docker image from the diffusers directory', 'test that the docker image can be built successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images from a configurable path']
```

Usage

```
{'build_docker_image': 'run the docker build test that builds a docker image from the diffusers directory', 'test_docker_build': 'test that the docker image can be built successfully using the DockerBuildTestCase', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images from a configurable path'}
```

