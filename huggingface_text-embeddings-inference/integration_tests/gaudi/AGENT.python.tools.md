# Agent Python Tools

- repo: huggingface/text-embeddings-inference
- repo_uri: https://github.com/huggingface/text-embeddings-inference

## File: huggingface_text-embeddings-inference/integration_tests/gaudi/conftest.py

Prompts

```
['stream docker container logs to stderr in a separate background thread', 'send a POST request to the /embed endpoint and return the JSON response', 'run a health check loop that retries the generate endpoint until the server is ready', 'check if a docker container is running or created and return its status', 'launch a docker container running the TEI HPU image for integration testing with automatic cleanup', 'run the async pytest test that sends a single embedding request to the TEI Gaudi service and validates output', 'test the text-embeddings-inference service on Gaudi hardware using the BAAI bge-large-en-v1.5 model', 'create a pytest fixture that provides parameterized model configurations from TEST_CONFIGS for embedding model tests', 'create a pytest fixture that launches and manages the TEI service using the gaudi_launcher context manager', 'create an async pytest fixture that waits for the TEI service health check before returning the client']
```

Usage

```
{'stream_container_logs': 'stream docker container logs to stderr in a separate background thread', 'generate_embeddings': 'send a POST request to the /embed endpoint and return the JSON response', 'health_check_launcher': 'run a health check loop that retries the generate endpoint until the server is ready', 'container_launcher_health': 'check if a docker container is running or created and return its status', 'gaudi_launcher_fixture': 'launch a docker container running the TEI HPU image for integration testing with automatic cleanup'}
```

## File: huggingface_text-embeddings-inference/integration_tests/gaudi/test_embed.py

Prompts

```
['stream docker container logs to stderr in a separate background thread', 'send a POST request to the /embed endpoint and return the JSON response', 'run a health check loop that retries the generate endpoint until the server is ready', 'check if a docker container is running or created and return its status', 'launch a docker container running the TEI HPU image for integration testing with automatic cleanup', 'run the async pytest test that sends a single embedding request to the TEI Gaudi service and validates output', 'test the text-embeddings-inference service on Gaudi hardware using the BAAI bge-large-en-v1.5 model', 'create a pytest fixture that provides parameterized model configurations from TEST_CONFIGS for embedding model tests', 'create a pytest fixture that launches and manages the TEI service using the gaudi_launcher context manager', 'create an async pytest fixture that waits for the TEI service health check before returning the client']
```

Usage

```
{'run_test_model_single_request': 'run the async pytest test that sends a single embedding request to the TEI Gaudi service and validates output', 'test_embedding_inference_gaudi': 'test the text-embeddings-inference service on Gaudi hardware using the BAAI bge-large-en-v1.5 model', 'create_test_config_fixture': 'create a pytest fixture that provides parameterized model configurations from TEST_CONFIGS for embedding model tests', 'create_tei_service_fixture': 'create a pytest fixture that launches and manages the TEI service using the gaudi_launcher context manager', 'create_tei_client_fixture': 'create an async pytest fixture that waits for the TEI service health check before returning the client'}
```

