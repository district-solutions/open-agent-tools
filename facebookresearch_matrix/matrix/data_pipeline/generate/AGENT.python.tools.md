# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/data_pipeline/generate/vllm_generate.py

Prompts

```
['run vLLM LLM inference on a JSONL input file using Ray Data and write responses to an output directory', 'create a VllmInference callable class that processes batches of prompts through a vLLM model and returns generated responses', 'run a Ray remote function that maps VllmInference over input JSONL batches with configurable concurrency and GPU allocation', 'review the VllmInference __call__ method that extracts prompts, applies templates, and generates LLM outputs for each batch', 'refactor the main entry point to pass custom vLLM model arguments and sampling parameters for distributed LLM generation']
```

Usage

```
{'run_vllm_inference_on_jsonl': 'run vLLM LLM inference on a JSONL input file using Ray Data and write responses to an output directory', 'create_vllminference_batch_processor': 'create a VllmInference callable class that processes batches of prompts through a vLLM model and returns generated responses', 'run_remotely_ray_map_batches': 'run a Ray remote function that maps VllmInference over input JSONL batches with configurable concurrency and GPU allocation', 'review_vllminference_call_method': 'review the VllmInference __call__ method that extracts prompts, applies templates, and generates LLM outputs for each batch', 'refactor_main_for_custom_model_args': 'refactor the main entry point to pass custom vLLM model arguments and sampling parameters for distributed LLM generation'}
```

