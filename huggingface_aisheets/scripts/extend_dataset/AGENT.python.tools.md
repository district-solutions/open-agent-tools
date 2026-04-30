# Agent Python Tools

- repo: huggingface/aisheets
- repo_uri: https://github.com/huggingface/aisheets

## File: huggingface_aisheets/scripts/extend_dataset/with_inference_client.py

Prompts

```
['run a pipeline to augment a HuggingFace dataset with LLM-generated columns and push to hub', 'build a dependency graph for columns that reference other columns in the generation config', 'generate a completion using HuggingFace InferenceClient with retry logic and exponential backoff', 'process a node in the parallel pipeline by resolving dependencies and generating LLM output', 'load a YAML configuration from a local file or remote URL for the pipeline', 'run the vllm dataset extension pipeline to augment a HuggingFace dataset with LLM-generated columns', 'process a dataset column by generating values using vllm LLM chat completions with a prompt template', 'load a processor configuration from a YAML file to build a dependency graph for column generation', 'build a directed dependency graph from column configurations to determine generation order', 'check if CUDA is available and print the GPU device name for vllm inference']
```

Usage

```
{'run_pipeline_augment_dataset': 'run a pipeline to augment a HuggingFace dataset with LLM-generated columns and push to hub', 'build_dependency_graph_columns': 'build a dependency graph for columns that reference other columns in the generation config', 'generate_completion_inference_client': 'generate a completion using HuggingFace InferenceClient with retry logic and exponential backoff', 'process_node_parallel_pipeline': 'process a node in the parallel pipeline by resolving dependencies and generating LLM output', 'load_config_yaml_source': 'load a YAML configuration from a local file or remote URL for the pipeline'}
```

## File: huggingface_aisheets/scripts/extend_dataset/with_vllm.py

Prompts

```
['run a pipeline to augment a HuggingFace dataset with LLM-generated columns and push to hub', 'build a dependency graph for columns that reference other columns in the generation config', 'generate a completion using HuggingFace InferenceClient with retry logic and exponential backoff', 'process a node in the parallel pipeline by resolving dependencies and generating LLM output', 'load a YAML configuration from a local file or remote URL for the pipeline', 'run the vllm dataset extension pipeline to augment a HuggingFace dataset with LLM-generated columns', 'process a dataset column by generating values using vllm LLM chat completions with a prompt template', 'load a processor configuration from a YAML file to build a dependency graph for column generation', 'build a directed dependency graph from column configurations to determine generation order', 'check if CUDA is available and print the GPU device name for vllm inference']
```

Usage

```
{'run_dataset_extension_pipeline': 'run the vllm dataset extension pipeline to augment a HuggingFace dataset with LLM-generated columns', 'process_column_with_llm': 'process a dataset column by generating values using vllm LLM chat completions with a prompt template', 'load_processor_config_from_yaml': 'load a processor configuration from a YAML file to build a dependency graph for column generation', 'build_dependency_graph_for_columns': 'build a directed dependency graph from column configurations to determine generation order', 'check_cuda_availability_for_gpu': 'check if CUDA is available and print the GPU device name for vllm inference'}
```

