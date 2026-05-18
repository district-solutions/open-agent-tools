# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/judge/engine.py

Prompts

```
['create an LLM engine using litellm with a specified model, provider, base URL, and optional API key', 'create a validated LLM engine that probes the model with a test message before returning', 'handle RateLimitError exceptions raised when the LLM API returns 429 after exhausting retries', 'call the LLM engine with a list of message dicts and receive content and metadata back', 'detect if an exception indicates rate limiting by checking for 429, ratelimit, or throttle keywords']
```

Usage

```
{'create_litellm_engine': 'create an LLM engine using litellm with a specified model, provider, base URL, and optional API key', 'create_engine_with_validation': 'create a validated LLM engine that probes the model with a test message before returning', 'handle_rate_limit_error': 'handle RateLimitError exceptions raised when the LLM API returns 429 after exhausting retries', 'call_llm_engine': 'call the LLM engine with a list of message dicts and receive content and metadata back', 'detect_rate_limit_error': 'detect if an exception indicates rate limiting by checking for 429, ratelimit, or throttle keywords'}
```

