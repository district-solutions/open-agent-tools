# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/guardrails/guardrail_hooks/lasso/lasso.py

Prompts

```
['create a LassoGuardrail instance with API key and optional masking to enforce content policies on LLM calls', 'run the Lasso guardrail on prompt or completion messages to classify violations via the Lasso Security API', 'apply masked content to a litellm ModelResponse after Lasso detects violations in the response', 'check Lasso API response findings for violations with BLOCK action to determine if request should be rejected', 'get the LassoGuardrailConfigModel class for configuring the Lasso guardrail in the LiteLLM proxy']
```

Usage

```
{'create_lasso_guardrail': 'create a LassoGuardrail instance with API key and optional masking to enforce content policies on LLM calls', 'run_lasso_guardrail': 'run the Lasso guardrail on prompt or completion messages to classify violations via the Lasso Security API', 'apply_masking_to_model_response': 'apply masked content to a litellm ModelResponse after Lasso detects violations in the response', 'check_for_blocking_actions': 'check Lasso API response findings for violations with BLOCK action to determine if request should be rejected', 'get_config_model': 'get the LassoGuardrailConfigModel class for configuring the Lasso guardrail in the LiteLLM proxy'}
```

