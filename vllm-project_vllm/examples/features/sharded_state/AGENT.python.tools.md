# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/features/sharded_state/load_sharded_state_offline.py

Prompts

```
['load a vLLM model saved in sharded_state format and run inference validation', 'parse CLI arguments for loading a sharded state model with tensor parallel size and sampling params', 'run text generation inference using a loaded sharded state model with configurable temperature and top-p', 'configure sampling parameters including temperature, top-p, and max tokens for sharded model inference', 'validate a sharded state model by generating text from a prompt and displaying output', 'run the script to save each worker model state dict to a sharded checkpoint for fast tensor-parallel loading', 'run the argparse parser to configure model path, output directory, file pattern, and max file size for sharded state saving', 'run the main function to create an LLM instance, save sharded state, and copy metadata files to the output directory', 'review the save_sharded_state call that dumps worker states to safetensor files with configurable max size and filename pattern', 'review the main function that validates model path, creates LLM from engine args, saves sharded state, and copies non-weight metadata files']
```

Usage

```
{'load_sharded_state_model': 'load a vLLM model saved in sharded_state format and run inference validation', 'parse_args_sharded_loading': 'parse CLI arguments for loading a sharded state model with tensor parallel size and sampling params', 'run_inference_with_sharded_model': 'run text generation inference using a loaded sharded state model with configurable temperature and top-p', 'configure_sampling_params': 'configure sampling parameters including temperature, top-p, and max tokens for sharded model inference', 'validate_sharded_model_loading': 'validate a sharded state model by generating text from a prompt and displaying output'}
```

## File: vllm-project_vllm/examples/features/sharded_state/save_sharded_state_offline.py

Prompts

```
['load a vLLM model saved in sharded_state format and run inference validation', 'parse CLI arguments for loading a sharded state model with tensor parallel size and sampling params', 'run text generation inference using a loaded sharded state model with configurable temperature and top-p', 'configure sampling parameters including temperature, top-p, and max tokens for sharded model inference', 'validate a sharded state model by generating text from a prompt and displaying output', 'run the script to save each worker model state dict to a sharded checkpoint for fast tensor-parallel loading', 'run the argparse parser to configure model path, output directory, file pattern, and max file size for sharded state saving', 'run the main function to create an LLM instance, save sharded state, and copy metadata files to the output directory', 'review the save_sharded_state call that dumps worker states to safetensor files with configurable max size and filename pattern', 'review the main function that validates model path, creates LLM from engine args, saves sharded state, and copies non-weight metadata files']
```

Usage

```
{'run_save_sharded_state': 'run the script to save each worker model state dict to a sharded checkpoint for fast tensor-parallel loading', 'run_parse_args': 'run the argparse parser to configure model path, output directory, file pattern, and max file size for sharded state saving', 'run_main': 'run the main function to create an LLM instance, save sharded state, and copy metadata files to the output directory', 'review_save_sharded_state': 'review the save_sharded_state call that dumps worker states to safetensor files with configurable max size and filename pattern', 'review_main': 'review the main function that validates model path, creates LLM from engine args, saves sharded state, and copies non-weight metadata files'}
```

