# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/logging_service/log_analyzer/log_analyzer.py

Prompts

```
['run the log_analyzer CLI to parse execution logs and generate a JSON digest report', 'create a LogDigest instance and call analyze_logs to parse logs into a RunStudy object', 'use LogValidation to validate logs from a one_command_runner test for regression testing', 'use LogDigest._parse_line_context to extract epoch time and elapsed seconds from a log line', 'use LogDigest._add_containers_from_status_update to parse container info from status update JSON', 'validate an InstanceFlow object by checking its context, objective ID, cell ID, and stages', 'validate a FlowStage object by checking its stage ID, container count, and container details', 'validate a LogContext object by checking line number, elapsed seconds, epoch time, and UTC time', 'review the LogValidation class and its methods for validating log data in the fbpcs log analyzer']
```

Usage

```
{'run_log_analyzer_cli': 'run the log_analyzer CLI to parse execution logs and generate a JSON digest report', 'analyze_logs_with_LogDigest': 'create a LogDigest instance and call analyze_logs to parse logs into a RunStudy object', 'validate_one_runner_logs': 'use LogValidation to validate logs from a one_command_runner test for regression testing', 'parse_log_line_context': 'use LogDigest._parse_line_context to extract epoch time and elapsed seconds from a log line', 'extract_containers_from_status_update': 'use LogDigest._add_containers_from_status_update to parse container info from status update JSON'}
```

## File: facebookresearch_fbpcs/fbpcs/infra/logging_service/log_analyzer/log_validation.py

Prompts

```
['run the log_analyzer CLI to parse execution logs and generate a JSON digest report', 'create a LogDigest instance and call analyze_logs to parse logs into a RunStudy object', 'use LogValidation to validate logs from a one_command_runner test for regression testing', 'use LogDigest._parse_line_context to extract epoch time and elapsed seconds from a log line', 'use LogDigest._add_containers_from_status_update to parse container info from status update JSON', 'validate an InstanceFlow object by checking its context, objective ID, cell ID, and stages', 'validate a FlowStage object by checking its stage ID, container count, and container details', 'validate a LogContext object by checking line number, elapsed seconds, epoch time, and UTC time', 'review the LogValidation class and its methods for validating log data in the fbpcs log analyzer']
```

Usage

```
{'validate_one_runner_logs': 'validate a RunStudy object by checking log line counts, instance counts, and error lines', 'validate_log_instance': 'validate an InstanceFlow object by checking its context, objective ID, cell ID, and stages', 'validate_log_stage': 'validate a FlowStage object by checking its stage ID, container count, and container details', 'validate_log_context': 'validate a LogContext object by checking line number, elapsed seconds, epoch time, and UTC time', 'review_LogValidation_class': 'review the LogValidation class and its methods for validating log data in the fbpcs log analyzer'}
```

