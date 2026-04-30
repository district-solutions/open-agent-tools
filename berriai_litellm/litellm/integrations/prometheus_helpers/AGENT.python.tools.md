# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/prometheus_helpers/prometheus_api.py

Prompts

```
['query prometheus API for a specific metric name over the last 24 hours and return raw results', 'get fallback metrics from prometheus for successful and failed deployment fallbacks over the last 24 hours', 'check if prometheus is connected by verifying the PROMETHEUS_URL environment variable is set', 'get daily spend data from prometheus for the last 30 days, optionally filtered by api key', 'run a prometheus query for any metric name and retrieve the result data from the prometheus API']
```

Usage

```
{'query_prometheus_metric': 'query prometheus API for a specific metric name over the last 24 hours and return raw results', 'get_fallback_metrics': 'get fallback metrics from prometheus for successful and failed deployment fallbacks over the last 24 hours', 'check_prometheus_connection': 'check if prometheus is connected by verifying the PROMETHEUS_URL environment variable is set', 'get_daily_spend': 'get daily spend data from prometheus for the last 30 days, optionally filtered by api key', 'run_prometheus_query': 'run a prometheus query for any metric name and retrieve the result data from the prometheus API'}
```

