# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/nvidia_nim/rerank/common_utils.py

Prompts

```
['get the appropriate NVIDIA NIM rerank config class based on the model string prefix', 'build a configuration class for NVIDIA NIM ranking models that use the /v1/ranking endpoint', 'create a function that constructs the full NVIDIA NIM ranking API URL from a base URL', 'test the method that transforms rerank requests with a clean model name for NVIDIA NIM ranking', "refactor the method that strips 'nvidia_nim/' and 'ranking/' prefixes from model names", 'review the NVIDIA NIM ranking configuration class and its API endpoint handling', 'build the Nvidia NIM rerank API URL from api_base and model name', 'map Cohere rerank params like top_n to Nvidia NIM format with top_k', 'transform rerank request to Nvidia NIM format with query object and passages array', 'transform Nvidia NIM rerank response to LiteLLM standard RerankResponse format', 'validate Nvidia NIM API key and build default authorization headers']
```

Usage

```
{'get_nvidia_nim_rerank_config': 'get the appropriate NVIDIA NIM rerank config class based on the model string prefix'}
```

## File: berriai_litellm/litellm/llms/nvidia_nim/rerank/ranking_transformation.py

Prompts

```
['get the appropriate NVIDIA NIM rerank config class based on the model string prefix', 'build a configuration class for NVIDIA NIM ranking models that use the /v1/ranking endpoint', 'create a function that constructs the full NVIDIA NIM ranking API URL from a base URL', 'test the method that transforms rerank requests with a clean model name for NVIDIA NIM ranking', "refactor the method that strips 'nvidia_nim/' and 'ranking/' prefixes from model names", 'review the NVIDIA NIM ranking configuration class and its API endpoint handling', 'build the Nvidia NIM rerank API URL from api_base and model name', 'map Cohere rerank params like top_n to Nvidia NIM format with top_k', 'transform rerank request to Nvidia NIM format with query object and passages array', 'transform Nvidia NIM rerank response to LiteLLM standard RerankResponse format', 'validate Nvidia NIM API key and build default authorization headers']
```

Usage

```
{'build_nvidia_nim_ranking_config': 'build a configuration class for NVIDIA NIM ranking models that use the /v1/ranking endpoint', 'create_get_complete_url': 'create a function that constructs the full NVIDIA NIM ranking API URL from a base URL', 'test_transform_rerank_request': 'test the method that transforms rerank requests with a clean model name for NVIDIA NIM ranking', 'refactor_get_clean_model_name': "refactor the method that strips 'nvidia_nim/' and 'ranking/' prefixes from model names", 'review_nvidia_nim_ranking_config': 'review the NVIDIA NIM ranking configuration class and its API endpoint handling'}
```

## File: berriai_litellm/litellm/llms/nvidia_nim/rerank/transformation.py

Prompts

```
['get the appropriate NVIDIA NIM rerank config class based on the model string prefix', 'build a configuration class for NVIDIA NIM ranking models that use the /v1/ranking endpoint', 'create a function that constructs the full NVIDIA NIM ranking API URL from a base URL', 'test the method that transforms rerank requests with a clean model name for NVIDIA NIM ranking', "refactor the method that strips 'nvidia_nim/' and 'ranking/' prefixes from model names", 'review the NVIDIA NIM ranking configuration class and its API endpoint handling', 'build the Nvidia NIM rerank API URL from api_base and model name', 'map Cohere rerank params like top_n to Nvidia NIM format with top_k', 'transform rerank request to Nvidia NIM format with query object and passages array', 'transform Nvidia NIM rerank response to LiteLLM standard RerankResponse format', 'validate Nvidia NIM API key and build default authorization headers']
```

Usage

```
{'build_nvidia_nim_rerank_url': 'build the Nvidia NIM rerank API URL from api_base and model name', 'map_cohere_rerank_params_to_nvidia': 'map Cohere rerank params like top_n to Nvidia NIM format with top_k', 'transform_rerank_request_to_nvidia': 'transform rerank request to Nvidia NIM format with query object and passages array', 'transform_rerank_response_to_litellm': 'transform Nvidia NIM rerank response to LiteLLM standard RerankResponse format', 'validate_nvidia_nim_api_key': 'validate Nvidia NIM API key and build default authorization headers'}
```

