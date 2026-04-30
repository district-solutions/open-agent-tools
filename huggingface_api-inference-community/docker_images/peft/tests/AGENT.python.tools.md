# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/peft/tests/test_api.py

Prompts

```
['test that the PEFT pipeline has at least one allowed task implemented', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class that validates PEFT allowed tasks and unsupported task handling', 'run the unittest PipelineTestCase to verify PEFT pipeline task configuration', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to test model IDs', 'run the TextGenerationTestCase unittest to verify text generation API endpoints return correct responses', 'test the text generation API with simple input strings in both JSON dict and raw formats', 'test that the text generation API returns a 400 error for malformed UTF-8 input bytes', 'review the TextGenerationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'review the skipIf decorator that conditionally skips tests when text-generation is not in ALLOWED_TASKS']
```

Usage

```
{'test_PipelineTestCase_test_has_at_least_one_task_enabled': 'test that the PEFT pipeline has at least one allowed task implemented', 'test_PipelineTestCase_test_unsupported_tasks': 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class that validates PEFT allowed tasks and unsupported task handling', 'run_PipelineTestCase': 'run the unittest PipelineTestCase to verify PEFT pipeline task configuration', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to test model IDs'}
```

## File: huggingface_api-inference-community/docker_images/peft/tests/test_api_text_generation.py

Prompts

```
['test that the PEFT pipeline has at least one allowed task implemented', 'test that unsupported tasks raise an EnvironmentError when calling get_pipeline', 'review the PipelineTestCase class that validates PEFT allowed tasks and unsupported task handling', 'run the unittest PipelineTestCase to verify PEFT pipeline task configuration', 'summarize the TESTABLE_MODELS dictionary mapping pipeline tasks to test model IDs', 'run the TextGenerationTestCase unittest to verify text generation API endpoints return correct responses', 'test the text generation API with simple input strings in both JSON dict and raw formats', 'test that the text generation API returns a 400 error for malformed UTF-8 input bytes', 'review the TextGenerationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'review the skipIf decorator that conditionally skips tests when text-generation is not in ALLOWED_TASKS']
```

Usage

```
{'run_text_generation_tests': 'run the TextGenerationTestCase unittest to verify text generation API endpoints return correct responses', 'test_simple_text_generation': 'test the text generation API with simple input strings in both JSON dict and raw formats', 'test_malformed_input_handling': 'test that the text generation API returns a 400 error for malformed UTF-8 input bytes', 'review_text_generation_test_setup': 'review the TextGenerationTestCase setUp and tearDown methods that manage MODEL_ID and TASK environment variables', 'review_skipif_decorator': 'review the skipIf decorator that conditionally skips tests when text-generation is not in ALLOWED_TASKS'}
```

