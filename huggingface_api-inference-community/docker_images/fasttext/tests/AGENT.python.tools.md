# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/fasttext/tests/test_api.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping task types to fasttext model IDs for testing', 'review the ALL_TASKS set containing all HuggingFace pipeline task types', 'test the PipelineTestCase class to validate fasttext inference pipeline task support', 'test the feature extraction API with a valid sentence input and verify it returns a list of floats', 'test the feature extraction API with malformed UTF-8 bytes and verify it returns a 400 error', 'run the FeatureExtractionTestCase unit tests to validate the fasttext feature-extraction endpoint behavior', 'review the FeatureExtractionTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'test the feature extraction endpoint with both JSON dict and raw string input formats', 'test the TextClassificationTestCase to verify single word text classification returns label and score', 'test the TextClassificationTestCase to verify malformed UTF-8 input returns a 400 error', 'test the TextClassificationTestCase to verify multi-word input handling for language identification models', 'review the TextClassificationTestCase setUp and tearDown methods for environment variable management', 'refactor the TextClassificationTestCase parameterized class decorator to support additional testable models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_PipelineTestCase_has_at_least_one_task_enabled': 'test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test_PipelineTestCase_unsupported_tasks': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary mapping task types to fasttext model IDs for testing', 'review_ALL_TASKS': 'review the ALL_TASKS set containing all HuggingFace pipeline task types', 'test_PipelineTestCase': 'test the PipelineTestCase class to validate fasttext inference pipeline task support'}
```

## File: huggingface_api-inference-community/docker_images/fasttext/tests/test_api_feature_extraction.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping task types to fasttext model IDs for testing', 'review the ALL_TASKS set containing all HuggingFace pipeline task types', 'test the PipelineTestCase class to validate fasttext inference pipeline task support', 'test the feature extraction API with a valid sentence input and verify it returns a list of floats', 'test the feature extraction API with malformed UTF-8 bytes and verify it returns a 400 error', 'run the FeatureExtractionTestCase unit tests to validate the fasttext feature-extraction endpoint behavior', 'review the FeatureExtractionTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'test the feature extraction endpoint with both JSON dict and raw string input formats', 'test the TextClassificationTestCase to verify single word text classification returns label and score', 'test the TextClassificationTestCase to verify malformed UTF-8 input returns a 400 error', 'test the TextClassificationTestCase to verify multi-word input handling for language identification models', 'review the TextClassificationTestCase setUp and tearDown methods for environment variable management', 'refactor the TextClassificationTestCase parameterized class decorator to support additional testable models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_feature_extraction_simple': 'test the feature extraction API with a valid sentence input and verify it returns a list of floats', 'test_feature_extraction_malformed': 'test the feature extraction API with malformed UTF-8 bytes and verify it returns a 400 error', 'run_feature_extraction_tests': 'run the FeatureExtractionTestCase unit tests to validate the fasttext feature-extraction endpoint behavior', 'review_feature_extraction_test_setup': 'review the FeatureExtractionTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'test_feature_extraction_json_and_raw': 'test the feature extraction endpoint with both JSON dict and raw string input formats'}
```

## File: huggingface_api-inference-community/docker_images/fasttext/tests/test_api_text_classification.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping task types to fasttext model IDs for testing', 'review the ALL_TASKS set containing all HuggingFace pipeline task types', 'test the PipelineTestCase class to validate fasttext inference pipeline task support', 'test the feature extraction API with a valid sentence input and verify it returns a list of floats', 'test the feature extraction API with malformed UTF-8 bytes and verify it returns a 400 error', 'run the FeatureExtractionTestCase unit tests to validate the fasttext feature-extraction endpoint behavior', 'review the FeatureExtractionTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'test the feature extraction endpoint with both JSON dict and raw string input formats', 'test the TextClassificationTestCase to verify single word text classification returns label and score', 'test the TextClassificationTestCase to verify malformed UTF-8 input returns a 400 error', 'test the TextClassificationTestCase to verify multi-word input handling for language identification models', 'review the TextClassificationTestCase setUp and tearDown methods for environment variable management', 'refactor the TextClassificationTestCase parameterized class decorator to support additional testable models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_text_classification_simple': 'test the TextClassificationTestCase to verify single word text classification returns label and score', 'test_text_classification_malformed': 'test the TextClassificationTestCase to verify malformed UTF-8 input returns a 400 error', 'test_text_classification_multiple_words': 'test the TextClassificationTestCase to verify multi-word input handling for language identification models', 'review_text_classification_test_setup': 'review the TextClassificationTestCase setUp and tearDown methods for environment variable management', 'refactor_text_classification_parameterized': 'refactor the TextClassificationTestCase parameterized class decorator to support additional testable models'}
```

## File: huggingface_api-inference-community/docker_images/fasttext/tests/test_docker_build.py

Prompts

```
['test the PipelineTestCase to verify at least one task is enabled in ALLOWED_TASKS', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline', 'review the TESTABLE_MODELS dictionary mapping task types to fasttext model IDs for testing', 'review the ALL_TASKS set containing all HuggingFace pipeline task types', 'test the PipelineTestCase class to validate fasttext inference pipeline task support', 'test the feature extraction API with a valid sentence input and verify it returns a list of floats', 'test the feature extraction API with malformed UTF-8 bytes and verify it returns a 400 error', 'run the FeatureExtractionTestCase unit tests to validate the fasttext feature-extraction endpoint behavior', 'review the FeatureExtractionTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'test the feature extraction endpoint with both JSON dict and raw string input formats', 'test the TextClassificationTestCase to verify single word text classification returns label and score', 'test the TextClassificationTestCase to verify malformed UTF-8 input returns a 400 error', 'test the TextClassificationTestCase to verify multi-word input handling for language identification models', 'review the TextClassificationTestCase setUp and tearDown methods for environment variable management', 'refactor the TextClassificationTestCase parameterized class decorator to support additional testable models', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use the cd context manager to temporarily change the working directory', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project directory', 'test_docker_build': 'test that the docker image builds successfully using the DockerBuildTestCase class', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

