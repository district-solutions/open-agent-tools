# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/enterprise/litellm_enterprise/integrations/test_custom_guardrail.py

Prompts

```
['test the CustomGuardrail with Mode default as a list of event hooks like pre_call and post_call', 'test the CustomGuardrail with Mode configured without a default so guardrail only fires on tag match', 'test the CustomGuardrail with Mode tag value as a list of event hooks for matched tags', 'test the CustomGuardrail with Mode using a single tag mapping and default event hook', 'run the should_run_guardrail method on a CustomGuardrail instance to check if it should fire for a given event type', 'test the PrometheusLogger class initialization and budget metrics cron job setup with AsyncIOScheduler', 'test the prometheus_label_factory function to verify end_user label filtering for Prometheus metrics', 'test the PrometheusLogger _parse_prometheus_config method to validate metrics configuration parsing and label filtering', 'test the async_log_success_event method to verify request counters increment by 1 not token counts', 'test the increment_callback_logging_failure method to track callback failures for S3Logger and LangFuseLogger', 'test async prometheus success logging with callbacks by running a mocked litellm completion and verifying request metrics', 'test prometheus budget logging with callbacks by creating a router with provider budget config and asserting remaining budget metrics', 'test prometheus metric tracking for provider budget by mocking the PrometheusLogger and verifying track_provider_remaining_budget was called', 'test the router cooldown event callback by mocking a router deployment and asserting PrometheusLogger outage and cooldown methods were invoked', 'test the router cooldown event callback handles gracefully when no PrometheusLogger is registered in litellm callbacks']
```

Usage

```
{'test_custom_guardrail_with_mode_default_list': 'test the CustomGuardrail with Mode default as a list of event hooks like pre_call and post_call', 'test_custom_guardrail_with_mode_no_default': 'test the CustomGuardrail with Mode configured without a default so guardrail only fires on tag match', 'test_custom_guardrail_with_mode_tag_value_list': 'test the CustomGuardrail with Mode tag value as a list of event hooks for matched tags', 'test_custom_guardrail_with_mode': 'test the CustomGuardrail with Mode using a single tag mapping and default event hook', 'run_should_run_guardrail': 'run the should_run_guardrail method on a CustomGuardrail instance to check if it should fire for a given event type'}
```

## File: berriai_litellm/tests/enterprise/litellm_enterprise/integrations/test_prometheus.py

Prompts

```
['test the CustomGuardrail with Mode default as a list of event hooks like pre_call and post_call', 'test the CustomGuardrail with Mode configured without a default so guardrail only fires on tag match', 'test the CustomGuardrail with Mode tag value as a list of event hooks for matched tags', 'test the CustomGuardrail with Mode using a single tag mapping and default event hook', 'run the should_run_guardrail method on a CustomGuardrail instance to check if it should fire for a given event type', 'test the PrometheusLogger class initialization and budget metrics cron job setup with AsyncIOScheduler', 'test the prometheus_label_factory function to verify end_user label filtering for Prometheus metrics', 'test the PrometheusLogger _parse_prometheus_config method to validate metrics configuration parsing and label filtering', 'test the async_log_success_event method to verify request counters increment by 1 not token counts', 'test the increment_callback_logging_failure method to track callback failures for S3Logger and LangFuseLogger', 'test async prometheus success logging with callbacks by running a mocked litellm completion and verifying request metrics', 'test prometheus budget logging with callbacks by creating a router with provider budget config and asserting remaining budget metrics', 'test prometheus metric tracking for provider budget by mocking the PrometheusLogger and verifying track_provider_remaining_budget was called', 'test the router cooldown event callback by mocking a router deployment and asserting PrometheusLogger outage and cooldown methods were invoked', 'test the router cooldown event callback handles gracefully when no PrometheusLogger is registered in litellm callbacks']
```

Usage

```
{'test_prometheus_logger_initialization': 'test the PrometheusLogger class initialization and budget metrics cron job setup with AsyncIOScheduler', 'test_prometheus_label_filtering': 'test the prometheus_label_factory function to verify end_user label filtering for Prometheus metrics', 'test_prometheus_config_parsing': 'test the PrometheusLogger _parse_prometheus_config method to validate metrics configuration parsing and label filtering', 'test_request_counter_semantics': 'test the async_log_success_event method to verify request counters increment by 1 not token counts', 'test_callback_failure_metrics': 'test the increment_callback_logging_failure method to track callback failures for S3Logger and LangFuseLogger'}
```

## File: berriai_litellm/tests/enterprise/litellm_enterprise/integrations/test_prometheus_unit_tests.py

Prompts

```
['test the CustomGuardrail with Mode default as a list of event hooks like pre_call and post_call', 'test the CustomGuardrail with Mode configured without a default so guardrail only fires on tag match', 'test the CustomGuardrail with Mode tag value as a list of event hooks for matched tags', 'test the CustomGuardrail with Mode using a single tag mapping and default event hook', 'run the should_run_guardrail method on a CustomGuardrail instance to check if it should fire for a given event type', 'test the PrometheusLogger class initialization and budget metrics cron job setup with AsyncIOScheduler', 'test the prometheus_label_factory function to verify end_user label filtering for Prometheus metrics', 'test the PrometheusLogger _parse_prometheus_config method to validate metrics configuration parsing and label filtering', 'test the async_log_success_event method to verify request counters increment by 1 not token counts', 'test the increment_callback_logging_failure method to track callback failures for S3Logger and LangFuseLogger', 'test async prometheus success logging with callbacks by running a mocked litellm completion and verifying request metrics', 'test prometheus budget logging with callbacks by creating a router with provider budget config and asserting remaining budget metrics', 'test prometheus metric tracking for provider budget by mocking the PrometheusLogger and verifying track_provider_remaining_budget was called', 'test the router cooldown event callback by mocking a router deployment and asserting PrometheusLogger outage and cooldown methods were invoked', 'test the router cooldown event callback handles gracefully when no PrometheusLogger is registered in litellm callbacks']
```

Usage

```
{'test_prometheus_success_logging': 'test async prometheus success logging with callbacks by running a mocked litellm completion and verifying request metrics', 'test_prometheus_budget_logging': 'test prometheus budget logging with callbacks by creating a router with provider budget config and asserting remaining budget metrics', 'test_prometheus_metric_tracking': 'test prometheus metric tracking for provider budget by mocking the PrometheusLogger and verifying track_provider_remaining_budget was called', 'test_router_cooldown_callback': 'test the router cooldown event callback by mocking a router deployment and asserting PrometheusLogger outage and cooldown methods were invoked', 'test_router_cooldown_no_prometheus': 'test the router cooldown event callback handles gracefully when no PrometheusLogger is registered in litellm callbacks'}
```

