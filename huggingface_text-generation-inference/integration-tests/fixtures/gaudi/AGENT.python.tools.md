# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/integration-tests/fixtures/gaudi/service.py

Prompts

```
['run the gaudi_launcher pytest fixture to start a TGI container for a model', 'test the ContainerLauncherHandle health check method to verify a Docker container is running', 'create a TestClient instance extending AsyncInferenceClient with a service name and base URL', 'stream Docker container logs to stderr in a background thread during integration tests', 'generate concurrent text generation load using asyncio gather with the gaudi_generate_load fixture']
```

Usage

```
{'run_gaudi_launcher_fixture': 'run the gaudi_launcher pytest fixture to start a TGI container for a model', 'test_container_health_check': 'test the ContainerLauncherHandle health check method to verify a Docker container is running', 'create_test_client': 'create a TestClient instance extending AsyncInferenceClient with a service name and base URL', 'stream_container_logs': 'stream Docker container logs to stderr in a background thread during integration tests', 'generate_concurrent_load': 'generate concurrent text generation load using asyncio gather with the gaudi_generate_load fixture'}
```

