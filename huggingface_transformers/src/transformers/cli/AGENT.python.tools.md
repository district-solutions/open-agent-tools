# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/cli/add_new_model_like.py

Prompts

```
['create a new HuggingFace Transformers model module by duplicating an existing model type', 'add a new model to all auto mapping registrations in the Transformers auto module', 'create a modular model file that subclasses all classes from an existing model module', 'create test files for a new model by copying and adapting existing model tests', 'create a documentation markdown file for a new model with class autodoc references', 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream model chat completion tokens to the console with rich markdown rendering and speed stats', 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download a model and tokenizer to a custom cache directory', 'download a model and tokenizer even if already cached locally', 'download a custom model with trust_remote_code enabled for hub-defined modeling files', 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration', 'run the transformers env command to print environment and version information', 'run the transformers env command with an accelerate config file argument', 'run the transformers version command to print the transformers CLI version', 'review the env function that prints environment and version information', 'review the version function that prints the transformers CLI version']
```

Usage

```
{'create_model_like': 'create a new HuggingFace Transformers model module by duplicating an existing model type', 'add_model_auto_mappings': 'add a new model to all auto mapping registrations in the Transformers auto module', 'create_modular_file': 'create a modular model file that subclasses all classes from an existing model module', 'create_test_files': 'create test files for a new model by copying and adapting existing model tests', 'create_doc_file': 'create a documentation markdown file for a new model with class autodoc references'}
```

## File: huggingface_transformers/src/transformers/cli/chat.py

Prompts

```
['create a new HuggingFace Transformers model module by duplicating an existing model type', 'add a new model to all auto mapping registrations in the Transformers auto module', 'create a modular model file that subclasses all classes from an existing model module', 'create test files for a new model by copying and adapting existing model tests', 'create a documentation markdown file for a new model with class autodoc references', 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream model chat completion tokens to the console with rich markdown rendering and speed stats', 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download a model and tokenizer to a custom cache directory', 'download a model and tokenizer even if already cached locally', 'download a custom model with trust_remote_code enabled for hub-defined modeling files', 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration', 'run the transformers env command to print environment and version information', 'run the transformers env command with an accelerate config file argument', 'run the transformers version command to print the transformers CLI version', 'review the env function that prints environment and version information', 'review the version function that prints the transformers CLI version']
```

Usage

```
{'run_chat_cli': 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create_chat_session': 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save_chat_history': 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse_generate_flags': 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream_model_output': 'stream model chat completion tokens to the console with rich markdown rendering and speed stats'}
```

## File: huggingface_transformers/src/transformers/cli/download.py

Prompts

```
['create a new HuggingFace Transformers model module by duplicating an existing model type', 'add a new model to all auto mapping registrations in the Transformers auto module', 'create a modular model file that subclasses all classes from an existing model module', 'create test files for a new model by copying and adapting existing model tests', 'create a documentation markdown file for a new model with class autodoc references', 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream model chat completion tokens to the console with rich markdown rendering and speed stats', 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download a model and tokenizer to a custom cache directory', 'download a model and tokenizer even if already cached locally', 'download a custom model with trust_remote_code enabled for hub-defined modeling files', 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration', 'run the transformers env command to print environment and version information', 'run the transformers env command with an accelerate config file argument', 'run the transformers version command to print the transformers CLI version', 'review the env function that prints environment and version information', 'review the version function that prints the transformers CLI version']
```

Usage

```
{'download_model': 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download_model_cache_dir': 'download a model and tokenizer to a custom cache directory', 'download_model_force': 'download a model and tokenizer even if already cached locally', 'download_model_trust_remote': 'download a custom model with trust_remote_code enabled for hub-defined modeling files'}
```

## File: huggingface_transformers/src/transformers/cli/serve.py

Prompts

```
['create a new HuggingFace Transformers model module by duplicating an existing model type', 'add a new model to all auto mapping registrations in the Transformers auto module', 'create a modular model file that subclasses all classes from an existing model module', 'create test files for a new model by copying and adapting existing model tests', 'create a documentation markdown file for a new model with class autodoc references', 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream model chat completion tokens to the console with rich markdown rendering and speed stats', 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download a model and tokenizer to a custom cache directory', 'download a model and tokenizer even if already cached locally', 'download a custom model with trust_remote_code enabled for hub-defined modeling files', 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration', 'run the transformers env command to print environment and version information', 'run the transformers env command with an accelerate config file argument', 'run the transformers version command to print the transformers CLI version', 'review the env function that prints environment and version information', 'review the version function that prints the transformers CLI version']
```

Usage

```
{'run_serve_fastapi_server': 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build_serve_model_manager': 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create_chat_completion_handler': 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test_health_endpoint': 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize_serve_cli_options': 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration'}
```

## File: huggingface_transformers/src/transformers/cli/system.py

Prompts

```
['create a new HuggingFace Transformers model module by duplicating an existing model type', 'add a new model to all auto mapping registrations in the Transformers auto module', 'create a modular model file that subclasses all classes from an existing model module', 'create test files for a new model by copying and adapting existing model tests', 'create a documentation markdown file for a new model with class autodoc references', 'run the transformers chat CLI to interact with a language model via typer command-line interface', 'create a chat session with a model using the Chat class and AsyncInferenceClient streaming', 'save a chat conversation history and settings to a JSON file with timestamped filenames', 'parse generate flags from CLI arguments into a dictionary of generation config kwargs', 'stream model chat completion tokens to the console with rich markdown rendering and speed stats', 'download a model and its tokenizer from the Hugging Face Hub given a model ID', 'download a model and tokenizer to a custom cache directory', 'download a model and tokenizer even if already cached locally', 'download a custom model with trust_remote_code enabled for hub-defined modeling files', 'run a FastAPI server to serve HuggingFace models with an OpenAI-compatible API on a specified host and port', 'build a model manager that loads and unloads transformer models automatically based on usage and timeout', 'create a chat completion handler that supports streaming and non-streaming OpenAI-compatible chat completions', 'test the /health endpoint and /v1/models endpoint for server health and model listing', 'summarize the CLI options for continuous batching, quantization, torch.compile, and CUDA graph configuration', 'run the transformers env command to print environment and version information', 'run the transformers env command with an accelerate config file argument', 'run the transformers version command to print the transformers CLI version', 'review the env function that prints environment and version information', 'review the version function that prints the transformers CLI version']
```

Usage

```
{'run_env_info': 'run the transformers env command to print environment and version information', 'run_env_with_accelerate_config': 'run the transformers env command with an accelerate config file argument', 'run_version_info': 'run the transformers version command to print the transformers CLI version', 'review_env_function': 'review the env function that prints environment and version information', 'review_version_function': 'review the version function that prints the transformers CLI version'}
```

