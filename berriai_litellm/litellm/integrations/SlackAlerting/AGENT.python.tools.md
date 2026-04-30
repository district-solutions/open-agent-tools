# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/SlackAlerting/batching_handler.py

Prompts

```
['squash a queue of slack alert payloads into grouped items by url and alert type with counts', 'send a single slack alert payload to a webhook url via async http post request', 'print an alerting payload to the console when log_to_console is enabled on the slack alerting instance', 'create a budget alert type instance by calling get_budget_alert_type with a string type key', 'test the abstract base class BaseBudgetAlertType and its two abstract methods get_event_message and get_id', 'review the SoftBudgetAlert class that returns a soft budget crossed message and extracts token from user info', 'summarize the ProjectBudgetAlert class that returns a project budget message and uses token as the alert ID', 'review the ProxyBudgetAlert class that returns a proxy budget message and always uses a default ID', 'build a SlackAlerting instance to send alerts to Slack webhooks on LLM proxy events', 'send budget alerts to Slack when keys, teams, or projects exceed spend thresholds', 'send a daily Slack report of top failed deployments and slowest model responses', 'send Slack alerts when models or regions experience repeated 408 or 500+ errors', 'send a weekly or monthly Slack spend report broken down by team and tags', 'process slack alerting variables by resolving os.environ references in webhook URL mappings', 'test process_slack_alerting_variables with list and string webhook URL values containing os.environ references', 'review process_slack_alerting_variables to verify it resolves environment variable webhook URLs correctly', 'refactor _add_langfuse_trace_id_to_alert to retry fetching langfuse trace id up to three times', 'summarize _add_langfuse_trace_id_to_alert which returns a langfuse trace URL from request data']
```

Usage

```
{'squash_payloads': 'squash a queue of slack alert payloads into grouped items by url and alert type with counts', 'send_to_webhook': 'send a single slack alert payload to a webhook url via async http post request', 'print_alerting_payload_warning': 'print an alerting payload to the console when log_to_console is enabled on the slack alerting instance'}
```

## File: berriai_litellm/litellm/integrations/SlackAlerting/budget_alert_types.py

Prompts

```
['squash a queue of slack alert payloads into grouped items by url and alert type with counts', 'send a single slack alert payload to a webhook url via async http post request', 'print an alerting payload to the console when log_to_console is enabled on the slack alerting instance', 'create a budget alert type instance by calling get_budget_alert_type with a string type key', 'test the abstract base class BaseBudgetAlertType and its two abstract methods get_event_message and get_id', 'review the SoftBudgetAlert class that returns a soft budget crossed message and extracts token from user info', 'summarize the ProjectBudgetAlert class that returns a project budget message and uses token as the alert ID', 'review the ProxyBudgetAlert class that returns a proxy budget message and always uses a default ID', 'build a SlackAlerting instance to send alerts to Slack webhooks on LLM proxy events', 'send budget alerts to Slack when keys, teams, or projects exceed spend thresholds', 'send a daily Slack report of top failed deployments and slowest model responses', 'send Slack alerts when models or regions experience repeated 408 or 500+ errors', 'send a weekly or monthly Slack spend report broken down by team and tags', 'process slack alerting variables by resolving os.environ references in webhook URL mappings', 'test process_slack_alerting_variables with list and string webhook URL values containing os.environ references', 'review process_slack_alerting_variables to verify it resolves environment variable webhook URLs correctly', 'refactor _add_langfuse_trace_id_to_alert to retry fetching langfuse trace id up to three times', 'summarize _add_langfuse_trace_id_to_alert which returns a langfuse trace URL from request data']
```

Usage

```
{'create_get_budget_alert_type': 'create a budget alert type instance by calling get_budget_alert_type with a string type key', 'test_BaseBudgetAlertType': 'test the abstract base class BaseBudgetAlertType and its two abstract methods get_event_message and get_id', 'review_SoftBudgetAlert': 'review the SoftBudgetAlert class that returns a soft budget crossed message and extracts token from user info', 'summarize_ProjectBudgetAlert': 'summarize the ProjectBudgetAlert class that returns a project budget message and uses token as the alert ID', 'review_ProxyBudgetAlert': 'review the ProxyBudgetAlert class that returns a proxy budget message and always uses a default ID'}
```

## File: berriai_litellm/litellm/integrations/SlackAlerting/slack_alerting.py

Prompts

```
['squash a queue of slack alert payloads into grouped items by url and alert type with counts', 'send a single slack alert payload to a webhook url via async http post request', 'print an alerting payload to the console when log_to_console is enabled on the slack alerting instance', 'create a budget alert type instance by calling get_budget_alert_type with a string type key', 'test the abstract base class BaseBudgetAlertType and its two abstract methods get_event_message and get_id', 'review the SoftBudgetAlert class that returns a soft budget crossed message and extracts token from user info', 'summarize the ProjectBudgetAlert class that returns a project budget message and uses token as the alert ID', 'review the ProxyBudgetAlert class that returns a proxy budget message and always uses a default ID', 'build a SlackAlerting instance to send alerts to Slack webhooks on LLM proxy events', 'send budget alerts to Slack when keys, teams, or projects exceed spend thresholds', 'send a daily Slack report of top failed deployments and slowest model responses', 'send Slack alerts when models or regions experience repeated 408 or 500+ errors', 'send a weekly or monthly Slack spend report broken down by team and tags', 'process slack alerting variables by resolving os.environ references in webhook URL mappings', 'test process_slack_alerting_variables with list and string webhook URL values containing os.environ references', 'review process_slack_alerting_variables to verify it resolves environment variable webhook URLs correctly', 'refactor _add_langfuse_trace_id_to_alert to retry fetching langfuse trace id up to three times', 'summarize _add_langfuse_trace_id_to_alert which returns a langfuse trace URL from request data']
```

Usage

```
{'build_slack_alerting_instance': 'build a SlackAlerting instance to send alerts to Slack webhooks on LLM proxy events', 'send_slack_budget_alerts': 'send budget alerts to Slack when keys, teams, or projects exceed spend thresholds', 'send_daily_spend_report': 'send a daily Slack report of top failed deployments and slowest model responses', 'send_outage_alerts': 'send Slack alerts when models or regions experience repeated 408 or 500+ errors', 'send_spend_report': 'send a weekly or monthly Slack spend report broken down by team and tags'}
```

## File: berriai_litellm/litellm/integrations/SlackAlerting/utils.py

Prompts

```
['squash a queue of slack alert payloads into grouped items by url and alert type with counts', 'send a single slack alert payload to a webhook url via async http post request', 'print an alerting payload to the console when log_to_console is enabled on the slack alerting instance', 'create a budget alert type instance by calling get_budget_alert_type with a string type key', 'test the abstract base class BaseBudgetAlertType and its two abstract methods get_event_message and get_id', 'review the SoftBudgetAlert class that returns a soft budget crossed message and extracts token from user info', 'summarize the ProjectBudgetAlert class that returns a project budget message and uses token as the alert ID', 'review the ProxyBudgetAlert class that returns a proxy budget message and always uses a default ID', 'build a SlackAlerting instance to send alerts to Slack webhooks on LLM proxy events', 'send budget alerts to Slack when keys, teams, or projects exceed spend thresholds', 'send a daily Slack report of top failed deployments and slowest model responses', 'send Slack alerts when models or regions experience repeated 408 or 500+ errors', 'send a weekly or monthly Slack spend report broken down by team and tags', 'process slack alerting variables by resolving os.environ references in webhook URL mappings', 'test process_slack_alerting_variables with list and string webhook URL values containing os.environ references', 'review process_slack_alerting_variables to verify it resolves environment variable webhook URLs correctly', 'refactor _add_langfuse_trace_id_to_alert to retry fetching langfuse trace id up to three times', 'summarize _add_langfuse_trace_id_to_alert which returns a langfuse trace URL from request data']
```

Usage

```
{'process_slack_alerting_variables': 'process slack alerting variables by resolving os.environ references in webhook URL mappings', 'test_process_slack_alerting_variables': 'test process_slack_alerting_variables with list and string webhook URL values containing os.environ references', 'review_process_slack_alerting_variables': 'review process_slack_alerting_variables to verify it resolves environment variable webhook URLs correctly', 'refactor__add_langfuse_trace_id_to_alert': 'refactor _add_langfuse_trace_id_to_alert to retry fetching langfuse trace id up to three times', 'summarize__add_langfuse_trace_id_to_alert': 'summarize _add_langfuse_trace_id_to_alert which returns a langfuse trace URL from request data'}
```

