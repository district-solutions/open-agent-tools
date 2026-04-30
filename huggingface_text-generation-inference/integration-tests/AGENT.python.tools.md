# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/integration-tests/conftest.py

Prompts

```
['run pytest integration tests for text-generation-inference with --release --neuron or --gaudi flags', 'use the ResponseComparator syrupy extension to compare TGI API responses against JSON snapshots with configurable logprob tolerance', 'use the docker_launcher fixture to start a text-generation-launcher container with custom model, quantization, and shard settings', 'use the local_launcher fixture to start a text-generation-launcher subprocess with custom model, quantization, and shard settings', 'use the generate_load fixture to send concurrent async generation requests to the TGI client and collect responses']
```

Usage

```
{'run_tgi_integration_tests': 'run pytest integration tests for text-generation-inference with --release --neuron or --gaudi flags', 'compare_tgi_responses_with_snapshot': 'use the ResponseComparator syrupy extension to compare TGI API responses against JSON snapshots with configurable logprob tolerance', 'launch_tgi_server_in_docker': 'use the docker_launcher fixture to start a text-generation-launcher container with custom model, quantization, and shard settings', 'launch_tgi_server_locally': 'use the local_launcher fixture to start a text-generation-launcher subprocess with custom model, quantization, and shard settings', 'generate_batch_completions_async': 'use the generate_load fixture to send concurrent async generation requests to the TGI client and collect responses'}
```

