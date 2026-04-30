# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/base_llm/evals/transformation.py

Prompts

```
['create eval request by transforming CreateEvalRequest to provider-specific format with headers and litellm params', 'list evals by transforming ListEvalsParams into URL and query parameters for the Evals API', 'get eval by transforming eval ID and api base into a complete request URL and headers', 'create run request by transforming CreateRunRequest for a specific eval ID into provider-specific format', 'delete eval by transforming eval ID and api base into a DELETE request URL and headers']
```

Usage

```
{'create_eval_request': 'create eval request by transforming CreateEvalRequest to provider-specific format with headers and litellm params', 'list_evals_request': 'list evals by transforming ListEvalsParams into URL and query parameters for the Evals API', 'get_eval_request': 'get eval by transforming eval ID and api base into a complete request URL and headers', 'create_run_request': 'create run request by transforming CreateRunRequest for a specific eval ID into provider-specific format', 'delete_eval_request': 'delete eval by transforming eval ID and api base into a DELETE request URL and headers'}
```

