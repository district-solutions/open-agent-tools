# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/sentence_transformers/tests/test_api.py

Prompts

```
['test that at least one pipeline task is enabled in the sentence transformers API', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the sentence transformers API', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to model IDs', 'refactor the test_unsupported_tasks method to add additional task validation checks', 'test the feature extraction API endpoint with a valid sentence input and verify float embeddings', 'test the feature extraction API endpoint with malformed UTF-8 bytes and verify a 400 error response', 'test the feature extraction API by sending a JSON payload with an inputs key', 'test the feature extraction API by sending raw text as the request body', 'review the FeatureExtractionTestCase class that sets up and tears down environment variables for model testing', 'test the sentence similarity API by sending a source sentence and list of sentences and verifying float scores', 'test the sentence similarity API returns 400 when the sentences input field is missing', 'test the sentence similarity API returns 400 when malformed binary data is sent as input', 'review the SentenceSimilarityTestCase class that parameterizes tests across multiple sentence similarity models', 'test the sentence similarity API accepts inputs both nested under an inputs key and as a flat JSON body', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager for changing directories safely', 'refactor the DockerBuildTestCase to support building docker images with custom arguments']
```

Usage

```
{'test_pipeline_tasks_enabled': 'test that at least one pipeline task is enabled in the sentence transformers API', 'test_unsupported_tasks_raise_error': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for the sentence transformers API', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to model IDs', 'refactor_PipelineTestCase_test_unsupported_tasks': 'refactor the test_unsupported_tasks method to add additional task validation checks'}
```

## File: huggingface_api-inference-community/docker_images/sentence_transformers/tests/test_api_feature_extraction.py

Prompts

```
['test that at least one pipeline task is enabled in the sentence transformers API', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the sentence transformers API', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to model IDs', 'refactor the test_unsupported_tasks method to add additional task validation checks', 'test the feature extraction API endpoint with a valid sentence input and verify float embeddings', 'test the feature extraction API endpoint with malformed UTF-8 bytes and verify a 400 error response', 'test the feature extraction API by sending a JSON payload with an inputs key', 'test the feature extraction API by sending raw text as the request body', 'review the FeatureExtractionTestCase class that sets up and tears down environment variables for model testing', 'test the sentence similarity API by sending a source sentence and list of sentences and verifying float scores', 'test the sentence similarity API returns 400 when the sentences input field is missing', 'test the sentence similarity API returns 400 when malformed binary data is sent as input', 'review the SentenceSimilarityTestCase class that parameterizes tests across multiple sentence similarity models', 'test the sentence similarity API accepts inputs both nested under an inputs key and as a flat JSON body', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager for changing directories safely', 'refactor the DockerBuildTestCase to support building docker images with custom arguments']
```

Usage

```
{'test_feature_extraction_simple': 'test the feature extraction API endpoint with a valid sentence input and verify float embeddings', 'test_feature_extraction_malformed': 'test the feature extraction API endpoint with malformed UTF-8 bytes and verify a 400 error response', 'test_feature_extraction_json_input': 'test the feature extraction API by sending a JSON payload with an inputs key', 'test_feature_extraction_raw_input': 'test the feature extraction API by sending raw text as the request body', 'review_feature_extraction_testcase': 'review the FeatureExtractionTestCase class that sets up and tears down environment variables for model testing'}
```

## File: huggingface_api-inference-community/docker_images/sentence_transformers/tests/test_api_sentence_similarity.py

Prompts

```
['test that at least one pipeline task is enabled in the sentence transformers API', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the sentence transformers API', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to model IDs', 'refactor the test_unsupported_tasks method to add additional task validation checks', 'test the feature extraction API endpoint with a valid sentence input and verify float embeddings', 'test the feature extraction API endpoint with malformed UTF-8 bytes and verify a 400 error response', 'test the feature extraction API by sending a JSON payload with an inputs key', 'test the feature extraction API by sending raw text as the request body', 'review the FeatureExtractionTestCase class that sets up and tears down environment variables for model testing', 'test the sentence similarity API by sending a source sentence and list of sentences and verifying float scores', 'test the sentence similarity API returns 400 when the sentences input field is missing', 'test the sentence similarity API returns 400 when malformed binary data is sent as input', 'review the SentenceSimilarityTestCase class that parameterizes tests across multiple sentence similarity models', 'test the sentence similarity API accepts inputs both nested under an inputs key and as a flat JSON body', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager for changing directories safely', 'refactor the DockerBuildTestCase to support building docker images with custom arguments']
```

Usage

```
{'test_sentence_similarity_simple': 'test the sentence similarity API by sending a source sentence and list of sentences and verifying float scores', 'test_sentence_similarity_missing_input': 'test the sentence similarity API returns 400 when the sentences input field is missing', 'test_sentence_similarity_malformed_input': 'test the sentence similarity API returns 400 when malformed binary data is sent as input', 'review_SentenceSimilarityTestCase': 'review the SentenceSimilarityTestCase class that parameterizes tests across multiple sentence similarity models', 'test_sentence_similarity_two_formats': 'test the sentence similarity API accepts inputs both nested under an inputs key and as a flat JSON body'}
```

## File: huggingface_api-inference-community/docker_images/sentence_transformers/tests/test_docker_build.py

Prompts

```
['test that at least one pipeline task is enabled in the sentence transformers API', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class and its test methods for the sentence transformers API', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to model IDs', 'refactor the test_unsupported_tasks method to add additional task validation checks', 'test the feature extraction API endpoint with a valid sentence input and verify float embeddings', 'test the feature extraction API endpoint with malformed UTF-8 bytes and verify a 400 error response', 'test the feature extraction API by sending a JSON payload with an inputs key', 'test the feature extraction API by sending raw text as the request body', 'review the FeatureExtractionTestCase class that sets up and tears down environment variables for model testing', 'test the sentence similarity API by sending a source sentence and list of sentences and verifying float scores', 'test the sentence similarity API returns 400 when the sentences input field is missing', 'test the sentence similarity API returns 400 when malformed binary data is sent as input', 'review the SentenceSimilarityTestCase class that parameterizes tests across multiple sentence similarity models', 'test the sentence similarity API accepts inputs both nested under an inputs key and as a flat JSON body', 'build a docker image by running docker build in the project directory', 'test that the docker image builds successfully using the DockerBuildTestCase', 'use the cd context manager to temporarily change the working directory', 'review the cd class context manager for changing directories safely', 'refactor the DockerBuildTestCase to support building docker images with custom arguments']
```

Usage

```
{'build_docker_image': 'build a docker image by running docker build in the project directory', 'test_docker_build': 'test that the docker image builds successfully using the DockerBuildTestCase', 'use_cd_context_manager': 'use the cd context manager to temporarily change the working directory', 'review_cd_class': 'review the cd class context manager for changing directories safely', 'refactor_docker_build_test': 'refactor the DockerBuildTestCase to support building docker images with custom arguments'}
```

