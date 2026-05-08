# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/3p-integrations/modal/many-llamas-human-eval/download.py

Prompts

```
['run the modal app to download a HuggingFace model into a cloud volume', 'force re-download a specific HuggingFace model using the modal download function', 'download a HuggingFace model with only safetensors format files using snapshot_download', 'create a modal Volume named llamas to store downloaded model files', 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads', 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files', 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create an OpenAI client configured with a custom base URL and API key', 'get a chat completion response from the vLLM server via the OpenAI API', 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops', 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate pass@k for each problem given number of samples and correct answers', 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files']
```

Usage

```
{'run_download_model': 'run the modal app to download a HuggingFace model into a cloud volume', 'download_model_force': 'force re-download a specific HuggingFace model using the modal download function', 'download_model_safetensors': 'download a HuggingFace model with only safetensors format files using snapshot_download', 'configure_modal_volume': 'create a modal Volume named llamas to store downloaded model files', 'configure_modal_image': 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads'}
```

## File: facebookresearch_llama-recipes/3p-integrations/modal/many-llamas-human-eval/eval.py

Prompts

```
['run the modal app to download a HuggingFace model into a cloud volume', 'force re-download a specific HuggingFace model using the modal download function', 'download a HuggingFace model with only safetensors format files using snapshot_download', 'create a modal Volume named llamas to store downloaded model files', 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads', 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files', 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create an OpenAI client configured with a custom base URL and API key', 'get a chat completion response from the vLLM server via the OpenAI API', 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops', 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate pass@k for each problem given number of samples and correct answers', 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files']
```

Usage

```
{'run_eval_all_tasks': 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run_eval_single_task': 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run_modal_entrypoint': 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review_eval_single_task': 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review_eval_all_tasks': 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files'}
```

## File: facebookresearch_llama-recipes/3p-integrations/modal/many-llamas-human-eval/generate.py

Prompts

```
['run the modal app to download a HuggingFace model into a cloud volume', 'force re-download a specific HuggingFace model using the modal download function', 'download a HuggingFace model with only safetensors format files using snapshot_download', 'create a modal Volume named llamas to store downloaded model files', 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads', 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files', 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create an OpenAI client configured with a custom base URL and API key', 'get a chat completion response from the vLLM server via the OpenAI API', 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops', 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate pass@k for each problem given number of samples and correct answers', 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files']
```

Usage

```
{'run_humaneval_generation': 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn_parallel_clients': 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'save_humaneval_dataset': 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create_openai_client': 'create an OpenAI client configured with a custom base URL and API key', 'get_chat_completion': 'get a chat completion response from the vLLM server via the OpenAI API'}
```

## File: facebookresearch_llama-recipes/3p-integrations/modal/many-llamas-human-eval/inference.py

Prompts

```
['run the modal app to download a HuggingFace model into a cloud volume', 'force re-download a specific HuggingFace model using the modal download function', 'download a HuggingFace model with only safetensors format files using snapshot_download', 'create a modal Volume named llamas to store downloaded model files', 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads', 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files', 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create an OpenAI client configured with a custom base URL and API key', 'get a chat completion response from the vLLM server via the OpenAI API', 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops', 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate pass@k for each problem given number of samples and correct answers', 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files']
```

Usage

```
{'deploy_vllm_server': 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run_serve_function': 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure_bearer_auth': 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create_async_engine': 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get_model_config': 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops'}
```

## File: facebookresearch_llama-recipes/3p-integrations/modal/many-llamas-human-eval/plot.py

Prompts

```
['run the modal app to download a HuggingFace model into a cloud volume', 'force re-download a specific HuggingFace model using the modal download function', 'download a HuggingFace model with only safetensors format files using snapshot_download', 'create a modal Volume named llamas to store downloaded model files', 'build a modal Image with huggingface_hub and hf-transfer for fast model downloads', 'run modal app to evaluate all HumanEval tasks in the humaneval volume', 'run modal sandbox to evaluate a single HumanEval sample file against problems', 'run the modal local entrypoint that triggers evaluation of all pending tasks', 'review the eval_single_task function that spawns a Modal sandbox to evaluate functional correctness', 'review the eval_all_tasks function that discovers and spawns evaluations for all pending JSONL files', 'run the modal app to generate HumanEval completions using a vLLM server in parallel', 'spawn parallel Modal clients to generate completions for each HumanEval eval task', 'download and save the HumanEval dataset to a Modal cloud volume as JSONL', 'create an OpenAI client configured with a custom base URL and API key', 'get a chat completion response from the vLLM server via the OpenAI API', 'deploy a Modal app that serves Llama 3.2 3B Instruct via vLLM on an A100 GPU', 'run the serve function to start an OpenAI-compatible vLLM inference server with FastAPI', 'configure HTTP Bearer token authentication on the vLLM API routes using FastAPI dependencies', 'create an AsyncLLMEngine from AsyncEngineArgs with GPU memory utilization and max model length settings', 'get the model config from a vLLM engine, handling both running and non-running asyncio event loops', 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate pass@k for each problem given number of samples and correct answers', 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files']
```

Usage

```
{'run_modal_plot_humaneval': 'run the modal app to generate pass@k and fail@k plots from HumanEval results', 'render_plots_function': 'render pass@k and fail@k line plots from HumanEval JSONL result files', 'estimate_pass_at_k': 'estimate pass@k for each problem given number of samples and correct answers', 'estimate_pass_at_k_estimator': 'calculate the combinatorial estimator 1 minus comb(n-c,k) over comb(n,k)', 'main_entrypoint': 'execute the local entrypoint that saves pass@k and fail@k plots as JPEG files'}
```

