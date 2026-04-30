# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/base_llm/managed_resources/base_managed_resource.py

Prompts

```
['create a resource for each model in the target model names list using the LiteLLM router', 'store a unified resource ID with model mappings in cache and database', 'retrieve a unified resource by ID from cache or database', 'delete a unified resource from cache and database by its unified resource ID', 'filter healthy deployments based on model mappings for a managed resource', 'test the python function is_base64_encoded_unified_id to check if a resource ID is a base64 encoded unified ID', 'create a unified ID string from resource type, UUID, model names, provider resource ID, and model ID', 'build a function to decode a base64 encoded unified ID string back to its original format', 'run the parse_unified_id function to extract all components from an encoded or decoded unified ID into a dictionary', 'summarize the extract functions for unified IDs: model names, resource type, UUID, model ID, and provider resource ID']
```

Usage

```
{'create_resource_for_each_model': 'create a resource for each model in the target model names list using the LiteLLM router', 'store_unified_resource_id': 'store a unified resource ID with model mappings in cache and database', 'get_unified_resource_id': 'retrieve a unified resource by ID from cache or database', 'delete_unified_resource_id': 'delete a unified resource from cache and database by its unified resource ID', 'filter_deployments': 'filter healthy deployments based on model mappings for a managed resource'}
```

## File: berriai_litellm/litellm/llms/base_llm/managed_resources/utils.py

Prompts

```
['create a resource for each model in the target model names list using the LiteLLM router', 'store a unified resource ID with model mappings in cache and database', 'retrieve a unified resource by ID from cache or database', 'delete a unified resource from cache and database by its unified resource ID', 'filter healthy deployments based on model mappings for a managed resource', 'test the python function is_base64_encoded_unified_id to check if a resource ID is a base64 encoded unified ID', 'create a unified ID string from resource type, UUID, model names, provider resource ID, and model ID', 'build a function to decode a base64 encoded unified ID string back to its original format', 'run the parse_unified_id function to extract all components from an encoded or decoded unified ID into a dictionary', 'summarize the extract functions for unified IDs: model names, resource type, UUID, model ID, and provider resource ID']
```

Usage

```
{'test_is_base64_encoded_unified_id': 'test the python function is_base64_encoded_unified_id to check if a resource ID is a base64 encoded unified ID', 'create_generate_unified_id_string': 'create a unified ID string from resource type, UUID, model names, provider resource ID, and model ID', 'build_decode_unified_id': 'build a function to decode a base64 encoded unified ID string back to its original format', 'run_parse_unified_id': 'run the parse_unified_id function to extract all components from an encoded or decoded unified ID into a dictionary', 'summarize_extract_functions': 'summarize the extract functions for unified IDs: model names, resource type, UUID, model ID, and provider resource ID'}
```

