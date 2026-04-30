# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/open_clip/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate all pipeline task tests pass', 'review the TESTABLE_MODELS dictionary containing zero-shot-image-classification model IDs for the OpenCLIP pipeline', 'review the ALL_TASKS set listing all Hugging Face pipeline task names for validation', 'test the zero-shot image classification endpoint with a plane image and candidate labels', 'test the zero-shot image classification endpoint with a different resolution plane image', 'review the ZeroShotImageClassificationTestCase class for parameterized model testing and environment setup', 'refactor the read helper method to support additional image file formats from the samples directory', 'summarize the setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase unittest', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_PipelineTestCase_has_at_least_one_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_PipelineTestCase_unsupported_tasks': 'test the PipelineTestCase to verify unsupported tasks raise EnvironmentError when calling get_pipeline', 'run_PipelineTestCase': 'run the PipelineTestCase unittest class to validate all pipeline task tests pass', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary containing zero-shot-image-classification model IDs for the OpenCLIP pipeline', 'review_ALL_TASKS': 'review the ALL_TASKS set listing all Hugging Face pipeline task names for validation'}
```

## File: huggingface_api-inference-community/docker_images/open_clip/tests/test_api_zero_shot_image_classification.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate all pipeline task tests pass', 'review the TESTABLE_MODELS dictionary containing zero-shot-image-classification model IDs for the OpenCLIP pipeline', 'review the ALL_TASKS set listing all Hugging Face pipeline task names for validation', 'test the zero-shot image classification endpoint with a plane image and candidate labels', 'test the zero-shot image classification endpoint with a different resolution plane image', 'review the ZeroShotImageClassificationTestCase class for parameterized model testing and environment setup', 'refactor the read helper method to support additional image file formats from the samples directory', 'summarize the setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase unittest', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_zero_shot_classification_simple': 'test the zero-shot image classification endpoint with a plane image and candidate labels', 'test_zero_shot_classification_different_resolution': 'test the zero-shot image classification endpoint with a different resolution plane image', 'review_ZeroShotImageClassificationTestCase': 'review the ZeroShotImageClassificationTestCase class for parameterized model testing and environment setup', 'refactor_read_helper': 'refactor the read helper method to support additional image file formats from the samples directory', 'summarize_test_lifecycle': 'summarize the setUp and tearDown methods that manage MODEL_ID and TASK environment variables'}
```

## File: huggingface_api-inference-community/docker_images/open_clip/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test the PipelineTestCase to verify unsupported tasks raise EnvironmentError when calling get_pipeline', 'run the PipelineTestCase unittest class to validate all pipeline task tests pass', 'review the TESTABLE_MODELS dictionary containing zero-shot-image-classification model IDs for the OpenCLIP pipeline', 'review the ALL_TASKS set listing all Hugging Face pipeline task names for validation', 'test the zero-shot image classification endpoint with a plane image and candidate labels', 'test the zero-shot image classification endpoint with a different resolution plane image', 'review the ZeroShotImageClassificationTestCase class for parameterized model testing and environment setup', 'refactor the read helper method to support additional image file formats from the samples directory', 'summarize the setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'build a docker image by running docker build in the project root directory', 'test that the docker image builds successfully using the DockerBuildTestCase unittest', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project root directory', 'test_docker_build': 'test that the docker image builds successfully using the DockerBuildTestCase unittest', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

