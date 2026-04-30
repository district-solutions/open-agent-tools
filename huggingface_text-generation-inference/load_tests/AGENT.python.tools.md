# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/load_tests/benchmarks.py

Prompts

```
['run the TGI benchmark suite for a model using the CLI with --sha and --results-file', 'start a TGI Docker container with TGIDockerRunner for a given model and GPU count', 'run a text-generation-inference-benchmark Docker container with BenchmarkRunner using custom parameters', 'build a pandas DataFrame from benchmark JSON result files using build_df', 'run a Docker container with GPU support, volume mounts, and log sentinel monitoring via run_docker']
```

Usage

```
{'run_tgi_benchmark': 'run the TGI benchmark suite for a model using the CLI with --sha and --results-file', 'start_tgi_container': 'start a TGI Docker container with TGIDockerRunner for a given model and GPU count', 'run_benchmark_container': 'run a text-generation-inference-benchmark Docker container with BenchmarkRunner using custom parameters', 'build_results_dataframe': 'build a pandas DataFrame from benchmark JSON result files using build_df', 'run_docker_container': 'run a Docker container with GPU support, volume mounts, and log sentinel monitoring via run_docker'}
```

