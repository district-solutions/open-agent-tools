# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/integration-tests/fixtures/neuron/export_models.py

Prompts

```
['run the script to export all configured neuron models to the HuggingFace hub', 'export a single neuron model for a given config using maybe_export_model', 'compute a short hash from the neuron backend and Dockerfile git tree SHAs', 'generate a unique neuron model name from a config name and backend hash', 'get the text-generation-inference Docker image from the environment or local Docker host', 'launch a TGI docker container for a given model using the neuron_launcher pytest fixture', 'check the health of a TGI service by calling the LauncherHandle health method with a timeout', 'run multiple async text generation requests in parallel using the neuron_generate_load fixture', 'get the TGI docker image name from the environment or local docker images', 'create a TestClient instance wrapping AsyncInferenceClient for a given service base URL']
```

Usage

```
{'export_neuron_models': 'run the script to export all configured neuron models to the HuggingFace hub', 'export_single_neuron_model': 'export a single neuron model for a given config using maybe_export_model', 'get_neuron_backend_hash': 'compute a short hash from the neuron backend and Dockerfile git tree SHAs', 'get_neuron_model_name': 'generate a unique neuron model name from a config name and backend hash', 'get_tgi_docker_image': 'get the text-generation-inference Docker image from the environment or local Docker host'}
```

## File: huggingface_text-generation-inference/integration-tests/fixtures/neuron/service.py

Prompts

```
['run the script to export all configured neuron models to the HuggingFace hub', 'export a single neuron model for a given config using maybe_export_model', 'compute a short hash from the neuron backend and Dockerfile git tree SHAs', 'generate a unique neuron model name from a config name and backend hash', 'get the text-generation-inference Docker image from the environment or local Docker host', 'launch a TGI docker container for a given model using the neuron_launcher pytest fixture', 'check the health of a TGI service by calling the LauncherHandle health method with a timeout', 'run multiple async text generation requests in parallel using the neuron_generate_load fixture', 'get the TGI docker image name from the environment or local docker images', 'create a TestClient instance wrapping AsyncInferenceClient for a given service base URL']
```

Usage

```
{'launch_tgi_container': 'launch a TGI docker container for a given model using the neuron_launcher pytest fixture', 'check_service_health': 'check the health of a TGI service by calling the LauncherHandle health method with a timeout', 'run_parallel_generations': 'run multiple async text generation requests in parallel using the neuron_generate_load fixture', 'get_tgi_image': 'get the TGI docker image name from the environment or local docker images', 'create_test_client': 'create a TestClient instance wrapping AsyncInferenceClient for a given service base URL'}
```

