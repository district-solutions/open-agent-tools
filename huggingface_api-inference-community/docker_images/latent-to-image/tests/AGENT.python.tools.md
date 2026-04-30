# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/latent-to-image/tests/test_api.py

Prompts

```
['test that the latent-to-image pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with invalid TASK env var', 'review the PipelineTestCase class that validates allowed tasks and unsupported task handling for latent-to-image', 'summarize the TESTABLE_MODELS dictionary mapping latent-to-image task to stable-diffusion-v1-5 model', 'refactor test_unsupported_tasks to add additional task validation or custom error assertions', 'test the latent-to-image API by sending a base64-encoded PyTorch tensor and verifying the image response', 'test the latent-to-image API error handling by sending malformed base64 input and verifying a 400 response', 'test the TextToImageTestCase setUp method that configures MODEL_ID and TASK environment variables for the app', 'test the TextToImageTestCase setUpClass method that clears the get_pipeline cache before running tests', 'test the TextToImageTestCase tearDown method that restores original environment variables after each test', 'create a function that uses the cd context manager to temporarily change the working directory', 'run the DockerBuildTestCase to verify that the docker image can be built', 'test that running docker build in the project directory succeeds without errors', 'review the cd context manager class that changes and restores the working directory', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the latent-to-image pipeline has at least one task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with invalid TASK env var', 'review_PipelineTestCase': 'review the PipelineTestCase class that validates allowed tasks and unsupported task handling for latent-to-image', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping latent-to-image task to stable-diffusion-v1-5 model', 'refactor_PipelineTestCase_test_unsupported_tasks': 'refactor test_unsupported_tasks to add additional task validation or custom error assertions'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/tests/test_api_latent_to_image.py

Prompts

```
['test that the latent-to-image pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with invalid TASK env var', 'review the PipelineTestCase class that validates allowed tasks and unsupported task handling for latent-to-image', 'summarize the TESTABLE_MODELS dictionary mapping latent-to-image task to stable-diffusion-v1-5 model', 'refactor test_unsupported_tasks to add additional task validation or custom error assertions', 'test the latent-to-image API by sending a base64-encoded PyTorch tensor and verifying the image response', 'test the latent-to-image API error handling by sending malformed base64 input and verifying a 400 response', 'test the TextToImageTestCase setUp method that configures MODEL_ID and TASK environment variables for the app', 'test the TextToImageTestCase setUpClass method that clears the get_pipeline cache before running tests', 'test the TextToImageTestCase tearDown method that restores original environment variables after each test', 'create a function that uses the cd context manager to temporarily change the working directory', 'run the DockerBuildTestCase to verify that the docker image can be built', 'test that running docker build in the project directory succeeds without errors', 'review the cd context manager class that changes and restores the working directory', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'test_latent_to_image_simple': 'test the latent-to-image API by sending a base64-encoded PyTorch tensor and verifying the image response', 'test_latent_to_image_malformed_input': 'test the latent-to-image API error handling by sending malformed base64 input and verifying a 400 response', 'test_TextToImageTestCase_setUp': 'test the TextToImageTestCase setUp method that configures MODEL_ID and TASK environment variables for the app', 'test_TextToImageTestCase_setUpClass': 'test the TextToImageTestCase setUpClass method that clears the get_pipeline cache before running tests', 'test_TextToImageTestCase_tearDown': 'test the TextToImageTestCase tearDown method that restores original environment variables after each test'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/tests/test_docker_build.py

Prompts

```
['test that the latent-to-image pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with invalid TASK env var', 'review the PipelineTestCase class that validates allowed tasks and unsupported task handling for latent-to-image', 'summarize the TESTABLE_MODELS dictionary mapping latent-to-image task to stable-diffusion-v1-5 model', 'refactor test_unsupported_tasks to add additional task validation or custom error assertions', 'test the latent-to-image API by sending a base64-encoded PyTorch tensor and verifying the image response', 'test the latent-to-image API error handling by sending malformed base64 input and verifying a 400 response', 'test the TextToImageTestCase setUp method that configures MODEL_ID and TASK environment variables for the app', 'test the TextToImageTestCase setUpClass method that clears the get_pipeline cache before running tests', 'test the TextToImageTestCase tearDown method that restores original environment variables after each test', 'create a function that uses the cd context manager to temporarily change the working directory', 'run the DockerBuildTestCase to verify that the docker image can be built', 'test that running docker build in the project directory succeeds without errors', 'review the cd context manager class that changes and restores the working directory', 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method']
```

Usage

```
{'use_cd_context_manager': 'create a function that uses the cd context manager to temporarily change the working directory', 'run_docker_build_test': 'run the DockerBuildTestCase to verify that the docker image can be built', 'test_docker_image_build': 'test that running docker build in the project directory succeeds without errors', 'review_cd_class': 'review the cd context manager class that changes and restores the working directory', 'summarize_docker_build_test': 'summarize the DockerBuildTestCase class and its test_can_build_docker_image method'}
```

