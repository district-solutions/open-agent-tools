# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/prompts/init_prompts.py

Prompts

```
['initialize prompts from a list of prompt dictionaries into the in-memory prompt registry', 'create a new versioned prompt in the LiteLLM proxy with dotprompt content and LLM parameters', 'list all available prompts in the LiteLLM proxy filtered by environment and user permissions', 'get all versions of a specific prompt by base prompt ID from the database', 'test a dotprompt template by rendering variables and executing an LLM call with streaming', 'convert a .prompt file upload to JSON format with content and metadata fields', 'discover prompt initializers from litellm integrations and return a mapping of integration names to initializer functions', 'initialize a prompt spec with a prompt integration and register it in the in-memory prompt registry', 'get a prompt spec from the in-memory prompt registry by its prompt id', 'get the custom prompt management callback from the in-memory prompt registry by its prompt id', 'delete all prompts matching a given base prompt id from the in-memory prompt registry']
```

Usage

```
{'init_prompts': 'initialize prompts from a list of prompt dictionaries into the in-memory prompt registry'}
```

## File: berriai_litellm/litellm/proxy/prompts/prompt_endpoints.py

Prompts

```
['initialize prompts from a list of prompt dictionaries into the in-memory prompt registry', 'create a new versioned prompt in the LiteLLM proxy with dotprompt content and LLM parameters', 'list all available prompts in the LiteLLM proxy filtered by environment and user permissions', 'get all versions of a specific prompt by base prompt ID from the database', 'test a dotprompt template by rendering variables and executing an LLM call with streaming', 'convert a .prompt file upload to JSON format with content and metadata fields', 'discover prompt initializers from litellm integrations and return a mapping of integration names to initializer functions', 'initialize a prompt spec with a prompt integration and register it in the in-memory prompt registry', 'get a prompt spec from the in-memory prompt registry by its prompt id', 'get the custom prompt management callback from the in-memory prompt registry by its prompt id', 'delete all prompts matching a given base prompt id from the in-memory prompt registry']
```

Usage

```
{'create_prompt': 'create a new versioned prompt in the LiteLLM proxy with dotprompt content and LLM parameters', 'list_prompts': 'list all available prompts in the LiteLLM proxy filtered by environment and user permissions', 'get_prompt_versions': 'get all versions of a specific prompt by base prompt ID from the database', 'test_prompt': 'test a dotprompt template by rendering variables and executing an LLM call with streaming', 'convert_prompt_file_to_json': 'convert a .prompt file upload to JSON format with content and metadata fields'}
```

## File: berriai_litellm/litellm/proxy/prompts/prompt_registry.py

Prompts

```
['initialize prompts from a list of prompt dictionaries into the in-memory prompt registry', 'create a new versioned prompt in the LiteLLM proxy with dotprompt content and LLM parameters', 'list all available prompts in the LiteLLM proxy filtered by environment and user permissions', 'get all versions of a specific prompt by base prompt ID from the database', 'test a dotprompt template by rendering variables and executing an LLM call with streaming', 'convert a .prompt file upload to JSON format with content and metadata fields', 'discover prompt initializers from litellm integrations and return a mapping of integration names to initializer functions', 'initialize a prompt spec with a prompt integration and register it in the in-memory prompt registry', 'get a prompt spec from the in-memory prompt registry by its prompt id', 'get the custom prompt management callback from the in-memory prompt registry by its prompt id', 'delete all prompts matching a given base prompt id from the in-memory prompt registry']
```

Usage

```
{'discover_prompt_initializers': 'discover prompt initializers from litellm integrations and return a mapping of integration names to initializer functions', 'initialize_prompt': 'initialize a prompt spec with a prompt integration and register it in the in-memory prompt registry', 'get_prompt_by_id': 'get a prompt spec from the in-memory prompt registry by its prompt id', 'get_prompt_callback_by_id': 'get the custom prompt management callback from the in-memory prompt registry by its prompt id', 'delete_prompts_by_base_id': 'delete all prompts matching a given base prompt id from the in-memory prompt registry'}
```

