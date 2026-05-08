# Agent Python Tools

- repo: facebookresearch/collaborative-reasoner
- repo_uri: https://github.com/facebookresearch/collaborative-reasoner

## File: facebookresearch_collaborative-reasoner/utils/chat_utils.py

Prompts

```
['create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply a chat template to convert message lists into system user assistant format', 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint', 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate average student and teacher completion token lengths across conversation turns', 'assess correct, incorrect, and unsure rates from a list of turn correctness scores', 'load a JSONL file and return a list of dictionaries from each line', 'load a JSON file and return a dictionary with the parsed data', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get a list of all JSONL file paths in a given directory', 'hash a UUID string using SHA-256 and return the result as an integer', 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test a code execution worker by sending a simple assertion and retrying on failure', 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp', 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build a Prompt class instance with a name, template string, description, and list of required args', 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name']
```

Usage

```
{'create_chat_role_factory': 'create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate_next_turn': 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply_chat_template': 'apply a chat template to convert message lists into system user assistant format', 'generate_completion': 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate_next_turn_candidates': 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint'}
```

## File: facebookresearch_collaborative-reasoner/utils/eval_utils.py

Prompts

```
['create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply a chat template to convert message lists into system user assistant format', 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint', 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate average student and teacher completion token lengths across conversation turns', 'assess correct, incorrect, and unsure rates from a list of turn correctness scores', 'load a JSONL file and return a list of dictionaries from each line', 'load a JSON file and return a dictionary with the parsed data', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get a list of all JSONL file paths in a given directory', 'hash a UUID string using SHA-256 and return the result as an integer', 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test a code execution worker by sending a simple assertion and retrying on failure', 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp', 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build a Prompt class instance with a name, template string, description, and list of required args', 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name']
```

Usage

```
{'evaluate_agreement_and_correctness': 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute_social_behavior_metrics': 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count_turns_to_success': 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate_average_token_lengths': 'calculate average student and teacher completion token lengths across conversation turns', 'assess_behavior_quality': 'assess correct, incorrect, and unsure rates from a list of turn correctness scores'}
```

## File: facebookresearch_collaborative-reasoner/utils/file_utils.py

Prompts

```
['create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply a chat template to convert message lists into system user assistant format', 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint', 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate average student and teacher completion token lengths across conversation turns', 'assess correct, incorrect, and unsure rates from a list of turn correctness scores', 'load a JSONL file and return a list of dictionaries from each line', 'load a JSON file and return a dictionary with the parsed data', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get a list of all JSONL file paths in a given directory', 'hash a UUID string using SHA-256 and return the result as an integer', 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test a code execution worker by sending a simple assertion and retrying on failure', 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp', 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build a Prompt class instance with a name, template string, description, and list of required args', 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name']
```

Usage

```
{'load_jsonl_file': 'load a JSONL file and return a list of dictionaries from each line', 'load_json_file': 'load a JSON file and return a dictionary with the parsed data', 'save_jsonl_file': 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get_jsonl_files_in_dir': 'get a list of all JSONL file paths in a given directory', 'hash_uuid_to_int': 'hash a UUID string using SHA-256 and return the result as an integer'}
```

## File: facebookresearch_collaborative-reasoner/utils/http_utils.py

Prompts

```
['create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply a chat template to convert message lists into system user assistant format', 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint', 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate average student and teacher completion token lengths across conversation turns', 'assess correct, incorrect, and unsure rates from a list of turn correctness scores', 'load a JSONL file and return a list of dictionaries from each line', 'load a JSON file and return a dictionary with the parsed data', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get a list of all JSONL file paths in a given directory', 'hash a UUID string using SHA-256 and return the result as an integer', 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test a code execution worker by sending a simple assertion and retrying on failure', 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp', 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build a Prompt class instance with a name, template string, description, and list of required args', 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name']
```

Usage

```
{'get_registry_url_from_file': 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get_worker_list': 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test_worker': 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test_exec_worker': 'test a code execution worker by sending a simple assertion and retrying on failure', 'http_post_with_retry': 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp'}
```

## File: facebookresearch_collaborative-reasoner/utils/prompt_utils.py

Prompts

```
['create a ChatRoleFactory to distribute chat role generation across multiple model endpoints', 'generate the next chat turn by sending messages to an LLM endpoint via aiohttp', 'apply a chat template to convert message lists into system user assistant format', 'generate text completions by appending a prompt to chat turns and sending to a completion endpoint', 'generate multiple candidate chat turns in parallel using the Matrix client or legacy HTTP endpoint', 'evaluate whether a conversation reached agreement and if the agreed answer was formally correct', 'compute assertive, persuasive, and persuasion quality scores from a conversation turn list', 'count the number of turns it takes for a rater to achieve a perfect score', 'calculate average student and teacher completion token lengths across conversation turns', 'assess correct, incorrect, and unsure rates from a list of turn correctness scores', 'load a JSONL file and return a list of dictionaries from each line', 'load a JSON file and return a dictionary with the parsed data', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'get a list of all JSONL file paths in a given directory', 'hash a UUID string using SHA-256 and return the result as an integer', 'read the registry URL from .registry_url.txt and raise the file descriptor limit to the hard limit', 'get a list of ModelEndpoint workers for a given model name from a Ray cluster URL', 'test connectivity to a model or code execution worker endpoint with exponential backoff retries', 'test a code execution worker by sending a simple assertion and retrying on failure', 'send an async HTTP POST request with automatic retries and timeout handling via aiohttp', 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build a Prompt class instance with a name, template string, description, and list of required args', 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name']
```

Usage

```
{'render_prompt_template': 'create a Prompt object with a Jinja2 template string and render it with keyword arguments', 'get_prompt_by_name': 'load a named prompt template from prompt_library.json and render it with provided keyword arguments', 'validate_required_args': 'review the Prompt class prompt_render method to validate all required args are present before rendering', 'build_prompt_class': 'build a Prompt class instance with a name, template string, description, and list of required args', 'load_prompt_library': 'summarize the get_prompt function that loads prompt templates from a JSON file and renders by name'}
```

