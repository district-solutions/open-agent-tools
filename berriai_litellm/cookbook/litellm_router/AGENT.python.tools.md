# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/cookbook/litellm_router/load_test_proxy.py

Prompts

```
['run a concurrent load test against the litellm proxy with 100 parallel requests', 'create a litellm router with multiple azure and openai model deployments', 'test the make_openai_completion function that sends chat requests to the local proxy', 'refactor the concurrent call count and thread pool executor for custom load testing', 'review the request and error logging that tracks response times and exceptions', 'run a load test that sends concurrent requests to a LiteLLM queuing endpoint and polls for results', 'run a single queued completion request to the LiteLLM queue endpoint and poll until finished', 'test concurrent request handling by submitting multiple random questions to the queue endpoint simultaneously', 'review the LiteLLM Router model list configuration with Azure and OpenAI deployments for gpt-3.5-turbo', 'summarize the load test results showing total requests, successful calls, and failed calls with exceptions', 'run a load test sending 150 concurrent completion requests through the litellm Router', 'review the ThreadPoolExecutor pattern for submitting concurrent completion calls with random questions', 'refactor the request and error logging to write structured JSON instead of plain text']
```

Usage

```
{'run_load_test_proxy': 'run a concurrent load test against the litellm proxy with 100 parallel requests', 'create_router_model_list': 'create a litellm router with multiple azure and openai model deployments', 'test_make_openai_completion': 'test the make_openai_completion function that sends chat requests to the local proxy', 'refactor_concurrent_calls': 'refactor the concurrent call count and thread pool executor for custom load testing', 'review_request_logging': 'review the request and error logging that tracks response times and exceptions'}
```

## File: berriai_litellm/cookbook/litellm_router/load_test_queuing.py

Prompts

```
['run a concurrent load test against the litellm proxy with 100 parallel requests', 'create a litellm router with multiple azure and openai model deployments', 'test the make_openai_completion function that sends chat requests to the local proxy', 'refactor the concurrent call count and thread pool executor for custom load testing', 'review the request and error logging that tracks response times and exceptions', 'run a load test that sends concurrent requests to a LiteLLM queuing endpoint and polls for results', 'run a single queued completion request to the LiteLLM queue endpoint and poll until finished', 'test concurrent request handling by submitting multiple random questions to the queue endpoint simultaneously', 'review the LiteLLM Router model list configuration with Azure and OpenAI deployments for gpt-3.5-turbo', 'summarize the load test results showing total requests, successful calls, and failed calls with exceptions', 'run a load test sending 150 concurrent completion requests through the litellm Router', 'review the ThreadPoolExecutor pattern for submitting concurrent completion calls with random questions', 'refactor the request and error logging to write structured JSON instead of plain text']
```

Usage

```
{'run_load_test_queuing': 'run a load test that sends concurrent requests to a LiteLLM queuing endpoint and polls for results', 'run_make_openai_completion': 'run a single queued completion request to the LiteLLM queue endpoint and poll until finished', 'test_concurrent_requests': 'test concurrent request handling by submitting multiple random questions to the queue endpoint simultaneously', 'review_router_model_list': 'review the LiteLLM Router model list configuration with Azure and OpenAI deployments for gpt-3.5-turbo', 'summarize_load_test_results': 'summarize the load test results showing total requests, successful calls, and failed calls with exceptions'}
```

## File: berriai_litellm/cookbook/litellm_router/load_test_router.py

Prompts

```
['run a concurrent load test against the litellm proxy with 100 parallel requests', 'create a litellm router with multiple azure and openai model deployments', 'test the make_openai_completion function that sends chat requests to the local proxy', 'refactor the concurrent call count and thread pool executor for custom load testing', 'review the request and error logging that tracks response times and exceptions', 'run a load test that sends concurrent requests to a LiteLLM queuing endpoint and polls for results', 'run a single queued completion request to the LiteLLM queue endpoint and poll until finished', 'test concurrent request handling by submitting multiple random questions to the queue endpoint simultaneously', 'review the LiteLLM Router model list configuration with Azure and OpenAI deployments for gpt-3.5-turbo', 'summarize the load test results showing total requests, successful calls, and failed calls with exceptions', 'run a load test sending 150 concurrent completion requests through the litellm Router', 'review the ThreadPoolExecutor pattern for submitting concurrent completion calls with random questions', 'refactor the request and error logging to write structured JSON instead of plain text']
```

Usage

```
{'run_load_test_router': 'run a load test sending 150 concurrent completion requests through the litellm Router', 'create_router_model_list': 'create a Router with multiple Azure and OpenAI model deployments under a shared alias', 'test_make_openai_completion': 'test the make_openai_completion function that calls router.completion with timing and logging', 'review_concurrent_futures_usage': 'review the ThreadPoolExecutor pattern for submitting concurrent completion calls with random questions', 'refactor_request_logging': 'refactor the request and error logging to write structured JSON instead of plain text'}
```

