# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/sklearn/tests/test_api.py

Prompts

```
['test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation', 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test the tabular classification API returns 400 error when model cannot be loaded', 'test the tabular classification API warns about unexpected or missing input columns', 'test the tabular classification API returns 400 error for malformed non-JSON input data', 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests', 'run docker build command to build the sklearn docker image from the project directory', 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_pipeline_has_task_enabled': 'test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review_TESTABLE_MODELS': 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review_TEST_CASES': 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize_ALL_TASKS': 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation'}
```

## File: huggingface_api-inference-community/docker_images/sklearn/tests/test_api_tabular_classification.py

Prompts

```
['test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation', 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test the tabular classification API returns 400 error when model cannot be loaded', 'test the tabular classification API warns about unexpected or missing input columns', 'test the tabular classification API returns 400 error for malformed non-JSON input data', 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests', 'run docker build command to build the sklearn docker image from the project directory', 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_tabular_classification_success': 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test_wrong_sklearn_version_warning': 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test_cannot_load_model': 'test the tabular classification API returns 400 error when model cannot be loaded', 'test_extra_columns_warning': 'test the tabular classification API warns about unexpected or missing input columns', 'test_malformed_input': 'test the tabular classification API returns 400 error for malformed non-JSON input data'}
```

## File: huggingface_api-inference-community/docker_images/sklearn/tests/test_api_tabular_regression.py

Prompts

```
['test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation', 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test the tabular classification API returns 400 error when model cannot be loaded', 'test the tabular classification API warns about unexpected or missing input columns', 'test the tabular classification API returns 400 error for malformed non-JSON input data', 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests', 'run docker build command to build the sklearn docker image from the project directory', 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_tabular_regression_success': 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test_wrong_sklearn_version_warning': 'test the TabularRegressionTestCase to verify warnings are raised when using an old sklearn version', 'test_cannot_load_model': 'test the TabularRegressionTestCase to verify error handling when a model cannot be loaded on the current sklearn version', 'test_extra_columns_warning': 'test the TabularRegressionTestCase to verify warnings are raised for extra or missing columns in input data', 'test_malformed_input': 'test the TabularRegressionTestCase to verify proper 400 error response when malformed input is sent to the API'}
```

## File: huggingface_api-inference-community/docker_images/sklearn/tests/test_api_text_classification.py

Prompts

```
['test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation', 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test the tabular classification API returns 400 error when model cannot be loaded', 'test the tabular classification API warns about unexpected or missing input columns', 'test the tabular classification API returns 400 error for malformed non-JSON input data', 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests', 'run docker build command to build the sklearn docker image from the project directory', 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'test_text_classification_success': 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'test_wrong_sklearn_version_warning': 'test the TextClassificationTestCase to verify a 400 response with unpickle estimator warnings for old sklearn models', 'test_cannot_load_model': 'test the TextClassificationTestCase to verify a 400 error when a model cannot be loaded on the current sklearn version', 'test_malformed_input': 'test the TextClassificationTestCase to verify a 400 response when sending malformed binary data to the inference API', 'review_text_classification_test_setup': 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests'}
```

## File: huggingface_api-inference-community/docker_images/sklearn/tests/test_docker_build.py

Prompts

```
['test that the sklearn pipeline has at least one task enabled using PipelineTestCase', 'test that unsupported tasks raise EnvironmentError when calling get_pipeline with an invalid task', 'review the TESTABLE_MODELS dictionary containing sklearn model IDs for tabular classification, regression, and text classification', 'review the TEST_CASES dictionary mapping model IDs to their input output and configuration metadata', 'summarize the ALL_TASKS set listing all Hugging Face task types including tabular classification and text generation', 'test the tabular classification API endpoint returns 200 status code with correct predictions', 'test the tabular classification API raises unpickle estimator warnings for old sklearn models', 'test the tabular classification API returns 400 error when model cannot be loaded', 'test the tabular classification API warns about unexpected or missing input columns', 'test the tabular classification API returns 400 error for malformed non-JSON input data', 'test the TabularRegressionTestCase to verify successful 200 response code for tabular regression predictions', 'test the TextClassificationTestCase to verify a 200 response with label and score keys for text classification', 'review the TextClassificationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables for parameterized tests', 'run docker build command to build the sklearn docker image from the project directory', 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use the cd context manager to temporarily change the working directory in a with block', 'review the cd context manager class that saves and restores the current working directory', 'refactor the DockerBuildTestCase to support building docker images with custom build arguments']
```

Usage

```
{'build_docker_image_sklearn': 'run docker build command to build the sklearn docker image from the project directory', 'test_docker_build': 'run the unittest test case that verifies the sklearn docker image builds successfully', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory in a with block', 'review_cd_class': 'review the cd context manager class that saves and restores the current working directory', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom build arguments'}
```

