# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/vllm_ext/tests/conftest.py

Prompts

```
['run vllm_runner to generate text from prompts using greedy decoding with max tokens', 'run hf_runner to generate text from prompts using transformers model with greedy decoding', 'run vllm_runner to perform beam search generation with specified beam width and max tokens', 'run hf_runner to classify text prompts using a sentence transformer or cross encoder model', 'run local_asset_server to start a threaded HTTP server that serves test image assets', 'test the FP8 KV cache generation with vLLM runner on a CUDA model with compute capability at least 10.0', 'create a function that checks if the GPU device capability meets a minimum major and minor version', 'review the pytest fixture that sets VLLM environment variables for MXFP4 and FP8 quantization testing', 'run the pytest test suite for FP8 KV cache validation on a Qwen2.5 model with vLLM', 'refactor the cuda_capability_at_least function to support additional GPU vendor platforms beyond CUDA']
```

Usage

```
{'run_vllm_runner_generate': 'run vllm_runner to generate text from prompts using greedy decoding with max tokens', 'run_hf_runner_generate': 'run hf_runner to generate text from prompts using transformers model with greedy decoding', 'run_vllm_runner_beam_search': 'run vllm_runner to perform beam search generation with specified beam width and max tokens', 'run_hf_runner_classify': 'run hf_runner to classify text prompts using a sentence transformer or cross encoder model', 'run_local_asset_server': 'run local_asset_server to start a threaded HTTP server that serves test image assets'}
```

## File: intel_auto-round/auto_round_extension/vllm_ext/tests/test_fp8kv.py

Prompts

```
['run vllm_runner to generate text from prompts using greedy decoding with max tokens', 'run hf_runner to generate text from prompts using transformers model with greedy decoding', 'run vllm_runner to perform beam search generation with specified beam width and max tokens', 'run hf_runner to classify text prompts using a sentence transformer or cross encoder model', 'run local_asset_server to start a threaded HTTP server that serves test image assets', 'test the FP8 KV cache generation with vLLM runner on a CUDA model with compute capability at least 10.0', 'create a function that checks if the GPU device capability meets a minimum major and minor version', 'review the pytest fixture that sets VLLM environment variables for MXFP4 and FP8 quantization testing', 'run the pytest test suite for FP8 KV cache validation on a Qwen2.5 model with vLLM', 'refactor the cuda_capability_at_least function to support additional GPU vendor platforms beyond CUDA']
```

Usage

```
{'test_auto_fp8_kv': 'test the FP8 KV cache generation with vLLM runner on a CUDA model with compute capability at least 10.0', 'cuda_capability_at_least': 'create a function that checks if the GPU device capability meets a minimum major and minor version', 'set_vllm_ar_env': 'review the pytest fixture that sets VLLM environment variables for MXFP4 and FP8 quantization testing', 'run_test_fp8kv': 'run the pytest test suite for FP8 KV cache validation on a Qwen2.5 model with vLLM', 'refactor_cuda_capability_at_least': 'refactor the cuda_capability_at_least function to support additional GPU vendor platforms beyond CUDA'}
```

