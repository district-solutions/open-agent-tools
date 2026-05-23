# Agent Python Tools

- repo: facebookresearch/swe-rl
- repo_uri: https://github.com/facebookresearch/swe-rl

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/utils/api.py

Prompts

```
['create an OpenAIClient instance with sync and async OpenAI clients for chat and completion APIs', 'dispatch a batch of chat completion requests asynchronously with optional rate limit delay', 'dispatch a batch of completion requests asynchronously with optional rate limit delay between requests', 'collect async chat completion responses with semaphore-based concurrency control and a progress bar', 'parse and extract the solution section from thinking model output using answer tags', 'use BenchArgs to load and shard a SWE-bench Verified or Lite dataset for testing', 'parse command line arguments into a BenchArgs dataclass for dataset sharding configuration', 'parse command line arguments into an InferenceArgs dataclass for model inference settings', 'create an InferenceArgs dataclass to configure model id, temperature, and max concurrent requests', 'use parse_args_into_dataclasses to parse CLI args into any HuggingFace dataclass types', 'show a pretty-printed project structure from a dict with optional randomization and indentation', 'get all file paths, classes, and functions recursively from a project structure dict', 'lint Python code using flake8 and return new errors compared to previous code', 'create a fake git repo and return a git diff string from old and new file contents', 'normalize a patch by removing edits to trailing spaces, comments, and docstrings', 'load a JSONL file from a given filepath and return a list of dictionaries', 'write a list of dictionaries to a JSONL file at the specified filepath', 'count the number of tokens in a string prompt or list of chat messages', 'load existing instance IDs from a JSONL output file into a set', 'get a pretrained HuggingFace tokenizer using the configured TOKENIZER_MODEL']
```

Usage

```
{'create_OpenAIClient': 'create an OpenAIClient instance with sync and async OpenAI clients for chat and completion APIs', 'dispatch_chat_completions': 'dispatch a batch of chat completion requests asynchronously with optional rate limit delay', 'dispatch_completions': 'dispatch a batch of completion requests asynchronously with optional rate limit delay between requests', 'collect_responses_async': 'collect async chat completion responses with semaphore-based concurrency control and a progress bar', 'parse_thinking_output': 'parse and extract the solution section from thinking model output using answer tags'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/utils/args.py

Prompts

```
['create an OpenAIClient instance with sync and async OpenAI clients for chat and completion APIs', 'dispatch a batch of chat completion requests asynchronously with optional rate limit delay', 'dispatch a batch of completion requests asynchronously with optional rate limit delay between requests', 'collect async chat completion responses with semaphore-based concurrency control and a progress bar', 'parse and extract the solution section from thinking model output using answer tags', 'use BenchArgs to load and shard a SWE-bench Verified or Lite dataset for testing', 'parse command line arguments into a BenchArgs dataclass for dataset sharding configuration', 'parse command line arguments into an InferenceArgs dataclass for model inference settings', 'create an InferenceArgs dataclass to configure model id, temperature, and max concurrent requests', 'use parse_args_into_dataclasses to parse CLI args into any HuggingFace dataclass types', 'show a pretty-printed project structure from a dict with optional randomization and indentation', 'get all file paths, classes, and functions recursively from a project structure dict', 'lint Python code using flake8 and return new errors compared to previous code', 'create a fake git repo and return a git diff string from old and new file contents', 'normalize a patch by removing edits to trailing spaces, comments, and docstrings', 'load a JSONL file from a given filepath and return a list of dictionaries', 'write a list of dictionaries to a JSONL file at the specified filepath', 'count the number of tokens in a string prompt or list of chat messages', 'load existing instance IDs from a JSONL output file into a set', 'get a pretrained HuggingFace tokenizer using the configured TOKENIZER_MODEL']
```

Usage

```
{'load_swebench_dataset': 'use BenchArgs to load and shard a SWE-bench Verified or Lite dataset for testing', 'parse_bench_args': 'parse command line arguments into a BenchArgs dataclass for dataset sharding configuration', 'parse_inference_args': 'parse command line arguments into an InferenceArgs dataclass for model inference settings', 'configure_inference_backend': 'create an InferenceArgs dataclass to configure model id, temperature, and max concurrent requests', 'parse_args_into_dataclasses': 'use parse_args_into_dataclasses to parse CLI args into any HuggingFace dataclass types'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/utils/data.py

Prompts

```
['create an OpenAIClient instance with sync and async OpenAI clients for chat and completion APIs', 'dispatch a batch of chat completion requests asynchronously with optional rate limit delay', 'dispatch a batch of completion requests asynchronously with optional rate limit delay between requests', 'collect async chat completion responses with semaphore-based concurrency control and a progress bar', 'parse and extract the solution section from thinking model output using answer tags', 'use BenchArgs to load and shard a SWE-bench Verified or Lite dataset for testing', 'parse command line arguments into a BenchArgs dataclass for dataset sharding configuration', 'parse command line arguments into an InferenceArgs dataclass for model inference settings', 'create an InferenceArgs dataclass to configure model id, temperature, and max concurrent requests', 'use parse_args_into_dataclasses to parse CLI args into any HuggingFace dataclass types', 'show a pretty-printed project structure from a dict with optional randomization and indentation', 'get all file paths, classes, and functions recursively from a project structure dict', 'lint Python code using flake8 and return new errors compared to previous code', 'create a fake git repo and return a git diff string from old and new file contents', 'normalize a patch by removing edits to trailing spaces, comments, and docstrings', 'load a JSONL file from a given filepath and return a list of dictionaries', 'write a list of dictionaries to a JSONL file at the specified filepath', 'count the number of tokens in a string prompt or list of chat messages', 'load existing instance IDs from a JSONL output file into a set', 'get a pretrained HuggingFace tokenizer using the configured TOKENIZER_MODEL']
```

Usage

```
{'show_project_structure': 'show a pretty-printed project structure from a dict with optional randomization and indentation', 'get_full_file_paths_and_classes_and_functions': 'get all file paths, classes, and functions recursively from a project structure dict', 'lint_code': 'lint Python code using flake8 and return new errors compared to previous code', 'fake_git_repo': 'create a fake git repo and return a git diff string from old and new file contents', 'normalize_patch': 'normalize a patch by removing edits to trailing spaces, comments, and docstrings'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/utils/misc.py

Prompts

```
['create an OpenAIClient instance with sync and async OpenAI clients for chat and completion APIs', 'dispatch a batch of chat completion requests asynchronously with optional rate limit delay', 'dispatch a batch of completion requests asynchronously with optional rate limit delay between requests', 'collect async chat completion responses with semaphore-based concurrency control and a progress bar', 'parse and extract the solution section from thinking model output using answer tags', 'use BenchArgs to load and shard a SWE-bench Verified or Lite dataset for testing', 'parse command line arguments into a BenchArgs dataclass for dataset sharding configuration', 'parse command line arguments into an InferenceArgs dataclass for model inference settings', 'create an InferenceArgs dataclass to configure model id, temperature, and max concurrent requests', 'use parse_args_into_dataclasses to parse CLI args into any HuggingFace dataclass types', 'show a pretty-printed project structure from a dict with optional randomization and indentation', 'get all file paths, classes, and functions recursively from a project structure dict', 'lint Python code using flake8 and return new errors compared to previous code', 'create a fake git repo and return a git diff string from old and new file contents', 'normalize a patch by removing edits to trailing spaces, comments, and docstrings', 'load a JSONL file from a given filepath and return a list of dictionaries', 'write a list of dictionaries to a JSONL file at the specified filepath', 'count the number of tokens in a string prompt or list of chat messages', 'load existing instance IDs from a JSONL output file into a set', 'get a pretrained HuggingFace tokenizer using the configured TOKENIZER_MODEL']
```

Usage

```
{'load_jsonl_file': 'load a JSONL file from a given filepath and return a list of dictionaries', 'write_jsonl_file': 'write a list of dictionaries to a JSONL file at the specified filepath', 'count_tokens_prompt': 'count the number of tokens in a string prompt or list of chat messages', 'load_existing_instance_ids': 'load existing instance IDs from a JSONL output file into a set', 'get_tokenizer': 'get a pretrained HuggingFace tokenizer using the configured TOKENIZER_MODEL'}
```

