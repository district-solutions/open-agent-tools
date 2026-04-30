# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/containers/endpoint_factory.py

Prompts

```
['create a sync SDK function from an endpoint configuration dict using the generic container handler', 'create an async SDK function that wraps a sync endpoint function with context variable propagation', 'generate all container endpoint functions from the endpoints.json configuration file', 'list files in a container by calling the sync list_container_files endpoint with a container_id', 'upload a file to a container by calling the sync upload_container_file endpoint with a container_id and file data', 'create a managed container using the OpenAI Container API with a specified name and optional expiration settings', 'list all managed containers with optional pagination parameters for after cursor, limit, and sort order', 'retrieve a specific container by its ID and return the container object with its current state', 'delete a managed container by its ID and return a result confirming the deletion', 'decode a LiteLLM-managed container ID to extract original ID, resolved provider, and updated params', 'build container creation optional params by filtering valid parameters like expires_after and file_ids from passed params', 'build container list optional params by filtering valid parameters like after, limit, and order from passed params', 'encode container ID in response object with provider and model metadata for routing follow-up calls', 'filter container creation optional params through provider config to map and validate supported OpenAI parameters']
```

Usage

```
{'create_sync_endpoint': 'create a sync SDK function from an endpoint configuration dict using the generic container handler', 'create_async_endpoint': 'create an async SDK function that wraps a sync endpoint function with context variable propagation', 'generate_container_endpoints': 'generate all container endpoint functions from the endpoints.json configuration file', 'list_container_files': 'list files in a container by calling the sync list_container_files endpoint with a container_id', 'upload_container_file': 'upload a file to a container by calling the sync upload_container_file endpoint with a container_id and file data'}
```

## File: berriai_litellm/litellm/containers/main.py

Prompts

```
['create a sync SDK function from an endpoint configuration dict using the generic container handler', 'create an async SDK function that wraps a sync endpoint function with context variable propagation', 'generate all container endpoint functions from the endpoints.json configuration file', 'list files in a container by calling the sync list_container_files endpoint with a container_id', 'upload a file to a container by calling the sync upload_container_file endpoint with a container_id and file data', 'create a managed container using the OpenAI Container API with a specified name and optional expiration settings', 'list all managed containers with optional pagination parameters for after cursor, limit, and sort order', 'retrieve a specific container by its ID and return the container object with its current state', 'delete a managed container by its ID and return a result confirming the deletion', 'decode a LiteLLM-managed container ID to extract original ID, resolved provider, and updated params', 'build container creation optional params by filtering valid parameters like expires_after and file_ids from passed params', 'build container list optional params by filtering valid parameters like after, limit, and order from passed params', 'encode container ID in response object with provider and model metadata for routing follow-up calls', 'filter container creation optional params through provider config to map and validate supported OpenAI parameters']
```

Usage

```
{'create_container': 'create a managed container using the OpenAI Container API with a specified name and optional expiration settings', 'list_containers': 'list all managed containers with optional pagination parameters for after cursor, limit, and sort order', 'retrieve_container': 'retrieve a specific container by its ID and return the container object with its current state', 'delete_container': 'delete a managed container by its ID and return a result confirming the deletion', 'upload_container_file': 'upload a file such as CSV, Excel, or Python script to a managed container session'}
```

## File: berriai_litellm/litellm/containers/utils.py

Prompts

```
['create a sync SDK function from an endpoint configuration dict using the generic container handler', 'create an async SDK function that wraps a sync endpoint function with context variable propagation', 'generate all container endpoint functions from the endpoints.json configuration file', 'list files in a container by calling the sync list_container_files endpoint with a container_id', 'upload a file to a container by calling the sync upload_container_file endpoint with a container_id and file data', 'create a managed container using the OpenAI Container API with a specified name and optional expiration settings', 'list all managed containers with optional pagination parameters for after cursor, limit, and sort order', 'retrieve a specific container by its ID and return the container object with its current state', 'delete a managed container by its ID and return a result confirming the deletion', 'decode a LiteLLM-managed container ID to extract original ID, resolved provider, and updated params', 'build container creation optional params by filtering valid parameters like expires_after and file_ids from passed params', 'build container list optional params by filtering valid parameters like after, limit, and order from passed params', 'encode container ID in response object with provider and model metadata for routing follow-up calls', 'filter container creation optional params through provider config to map and validate supported OpenAI parameters']
```

Usage

```
{'decode_managed_container_id_for_request': 'decode a LiteLLM-managed container ID to extract original ID, resolved provider, and updated params', 'build_container_create_params': 'build container creation optional params by filtering valid parameters like expires_after and file_ids from passed params', 'build_container_list_params': 'build container list optional params by filtering valid parameters like after, limit, and order from passed params', 'encode_container_id_in_response': 'encode container ID in response object with provider and model metadata for routing follow-up calls', 'filter_container_create_optional_params': 'filter container creation optional params through provider config to map and validate supported OpenAI parameters'}
```

