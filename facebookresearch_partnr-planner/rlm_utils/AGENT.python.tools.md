# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/rlm_utils/convert_hf_checkpoint.py

Prompts

```
['convert a HuggingFace checkpoint to gpt-fast format by merging sharded weights and saving as model.pth', 'run the CLI tool to convert a HuggingFace checkpoint directory to gpt-fast model.pth format', 'permute Q and K attention weights to match gpt-fast format using head dimension reshaping', 'merge multiple sharded pytorch_model.bin files into a single consolidated state dictionary', 'map HuggingFace weight keys to custom gpt-fast naming conventions using regex-based layer number extraction', 'run an interactive FastGPT model that accepts JSON prompts via stdin and streams generated text responses', 'run the FastGPT model in REST mode to accept JSON requests on stdin with a 5-minute keepalive timeout', 'run the FastGPT model in KB mode to read prompts from input_file.txt and generate responses', 'run distributed GPT inference across multiple GPUs using torch.distributed scatter to broadcast prompts and kwargs', 'run the FastGPT model with optional grammar definitions to constrain generated text output', 'serve a FastGPTLanguageModel on a given IP and port using gpt-fast compiled checkpoint', 'serve an AutoTransformersLanguageModel on a given IP and port using HuggingFace transformers', 'launch multiple LLM server instances on a SLURM cluster using submitit executor', 'keep remote language model servers alive by polling and sending keep_alive requests', 'generate text from prompts using AutoTransformersLanguageModel with optional grammar constraints']
```

Usage

```
{'convert_hf_checkpoint_to_gpt_fast': 'convert a HuggingFace checkpoint to gpt-fast format by merging sharded weights and saving as model.pth', 'run_convert_hf_checkpoint_cli': 'run the CLI tool to convert a HuggingFace checkpoint directory to gpt-fast model.pth format', 'permute_attention_weights': 'permute Q and K attention weights to match gpt-fast format using head dimension reshaping', 'merge_sharded_pytorch_binaries': 'merge multiple sharded pytorch_model.bin files into a single consolidated state dictionary', 'map_hf_weights_to_custom_format': 'map HuggingFace weight keys to custom gpt-fast naming conventions using regex-based layer number extraction'}
```

## File: facebookresearch_partnr-planner/rlm_utils/interactive_genfast_gpt.py

Prompts

```
['convert a HuggingFace checkpoint to gpt-fast format by merging sharded weights and saving as model.pth', 'run the CLI tool to convert a HuggingFace checkpoint directory to gpt-fast model.pth format', 'permute Q and K attention weights to match gpt-fast format using head dimension reshaping', 'merge multiple sharded pytorch_model.bin files into a single consolidated state dictionary', 'map HuggingFace weight keys to custom gpt-fast naming conventions using regex-based layer number extraction', 'run an interactive FastGPT model that accepts JSON prompts via stdin and streams generated text responses', 'run the FastGPT model in REST mode to accept JSON requests on stdin with a 5-minute keepalive timeout', 'run the FastGPT model in KB mode to read prompts from input_file.txt and generate responses', 'run distributed GPT inference across multiple GPUs using torch.distributed scatter to broadcast prompts and kwargs', 'run the FastGPT model with optional grammar definitions to constrain generated text output', 'serve a FastGPTLanguageModel on a given IP and port using gpt-fast compiled checkpoint', 'serve an AutoTransformersLanguageModel on a given IP and port using HuggingFace transformers', 'launch multiple LLM server instances on a SLURM cluster using submitit executor', 'keep remote language model servers alive by polling and sending keep_alive requests', 'generate text from prompts using AutoTransformersLanguageModel with optional grammar constraints']
```

Usage

```
{'run_interactive_gpt_model': 'run an interactive FastGPT model that accepts JSON prompts via stdin and streams generated text responses', 'run_gpt_with_rest_input': 'run the FastGPT model in REST mode to accept JSON requests on stdin with a 5-minute keepalive timeout', 'run_gpt_with_file_input': 'run the FastGPT model in KB mode to read prompts from input_file.txt and generate responses', 'run_distributed_gpt_inference': 'run distributed GPT inference across multiple GPUs using torch.distributed scatter to broadcast prompts and kwargs', 'run_gpt_with_grammar_constraints': 'run the FastGPT model with optional grammar definitions to constrain generated text output'}
```

## File: facebookresearch_partnr-planner/rlm_utils/serve_model.py

Prompts

```
['convert a HuggingFace checkpoint to gpt-fast format by merging sharded weights and saving as model.pth', 'run the CLI tool to convert a HuggingFace checkpoint directory to gpt-fast model.pth format', 'permute Q and K attention weights to match gpt-fast format using head dimension reshaping', 'merge multiple sharded pytorch_model.bin files into a single consolidated state dictionary', 'map HuggingFace weight keys to custom gpt-fast naming conventions using regex-based layer number extraction', 'run an interactive FastGPT model that accepts JSON prompts via stdin and streams generated text responses', 'run the FastGPT model in REST mode to accept JSON requests on stdin with a 5-minute keepalive timeout', 'run the FastGPT model in KB mode to read prompts from input_file.txt and generate responses', 'run distributed GPT inference across multiple GPUs using torch.distributed scatter to broadcast prompts and kwargs', 'run the FastGPT model with optional grammar definitions to constrain generated text output', 'serve a FastGPTLanguageModel on a given IP and port using gpt-fast compiled checkpoint', 'serve an AutoTransformersLanguageModel on a given IP and port using HuggingFace transformers', 'launch multiple LLM server instances on a SLURM cluster using submitit executor', 'keep remote language model servers alive by polling and sending keep_alive requests', 'generate text from prompts using AutoTransformersLanguageModel with optional grammar constraints']
```

Usage

```
{'serve_fastgpt_model': 'serve a FastGPTLanguageModel on a given IP and port using gpt-fast compiled checkpoint', 'serve_autotransformers_model': 'serve an AutoTransformersLanguageModel on a given IP and port using HuggingFace transformers', 'launch_slurm_servers': 'launch multiple LLM server instances on a SLURM cluster using submitit executor', 'keep_alive_check': 'keep remote language model servers alive by polling and sending keep_alive requests', 'batch_generate_with_grammar': 'generate text from prompts using AutoTransformersLanguageModel with optional grammar constraints'}
```

