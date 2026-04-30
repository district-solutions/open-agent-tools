# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/integration-tests/gaudi/capture_expected_outputs.py

Prompts

```
['run the pytest test that captures expected greedy and batch outputs for TGI models with unknown outputs', 'review the async test function that sends single and batch generation requests to TGI and saves results to JSON', 'refactor the parametrized pytest fixture that filters TEST_CONFIGS for models with unknown expected outputs', 'review the pytest fixture that launches a TGI service using the launcher context manager', 'run the Gaudi integration test suite to capture and persist expected model outputs for unknown configurations', 'run pytest integration tests for TGI text generation models on Intel Gaudi hardware', 'configure TEST_CONFIGS dict with model IDs, expected outputs, and TGI args for Gaudi testing', 'test single async text generation request against a TGI model using greedy decoding', 'test multiple concurrent async text generation requests against a TGI model using batch decoding', 'parametrize pytest tests to run across all Gaudi model configs or only default ones']
```

Usage

```
{'run_capture_expected_outputs_test': 'run the pytest test that captures expected greedy and batch outputs for TGI models with unknown outputs', 'review_test_capture_expected_outputs': 'review the async test function that sends single and batch generation requests to TGI and saves results to JSON', 'refactor_test_config_fixture': 'refactor the parametrized pytest fixture that filters TEST_CONFIGS for models with unknown expected outputs', 'review_tgi_service_fixture': 'review the pytest fixture that launches a TGI service using the launcher context manager', 'run_gaudi_integration_tests': 'run the Gaudi integration test suite to capture and persist expected model outputs for unknown configurations'}
```

## File: huggingface_text-generation-inference/integration-tests/gaudi/test_gaudi_generate.py

Prompts

```
['run the pytest test that captures expected greedy and batch outputs for TGI models with unknown outputs', 'review the async test function that sends single and batch generation requests to TGI and saves results to JSON', 'refactor the parametrized pytest fixture that filters TEST_CONFIGS for models with unknown expected outputs', 'review the pytest fixture that launches a TGI service using the launcher context manager', 'run the Gaudi integration test suite to capture and persist expected model outputs for unknown configurations', 'run pytest integration tests for TGI text generation models on Intel Gaudi hardware', 'configure TEST_CONFIGS dict with model IDs, expected outputs, and TGI args for Gaudi testing', 'test single async text generation request against a TGI model using greedy decoding', 'test multiple concurrent async text generation requests against a TGI model using batch decoding', 'parametrize pytest tests to run across all Gaudi model configs or only default ones']
```

Usage

```
{'run_gaudi_tgi_integration_tests': 'run pytest integration tests for TGI text generation models on Intel Gaudi hardware', 'configure_test_models': 'configure TEST_CONFIGS dict with model IDs, expected outputs, and TGI args for Gaudi testing', 'test_single_request_inference': 'test single async text generation request against a TGI model using greedy decoding', 'test_batch_requests_inference': 'test multiple concurrent async text generation requests against a TGI model using batch decoding', 'parametrize_gaudi_model_tests': 'parametrize pytest tests to run across all Gaudi model configs or only default ones'}
```

