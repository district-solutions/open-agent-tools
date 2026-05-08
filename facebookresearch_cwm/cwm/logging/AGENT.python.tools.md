# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/logging/logger.py

Prompts

```
['initialize the root logger with stdout and stderr handlers using a custom LogFormatter', 'add a file handler to the root logger that appends log output to a specified file', 'set the root logger level to a string name or integer value with fallback to NOTSET', 'use the log_timing context manager to log start and completion time of a code block', 'format a log record with rank prefix, timestamp, elapsed delta, and indented multiline messages', 'create a JsonlMetricsLogger instance to log experiment metrics to a JSONL file in a given directory', 'log a dictionary of metrics with an optional global step using the JsonlMetricsLogger log_metrics method', 'log a text string under a given key to the JSONL metrics file using the log_text method', 'sanitize a metrics dictionary by converting torch.Tensor values to Python floats using the _sanitize function', 'use the MetricsLogger as a context manager to automatically open and close the logger']
```

Usage

```
{'initialize_logger': 'initialize the root logger with stdout and stderr handlers using a custom LogFormatter', 'add_logger_file_handler': 'add a file handler to the root logger that appends log output to a specified file', 'set_root_log_level': 'set the root logger level to a string name or integer value with fallback to NOTSET', 'log_timing': 'use the log_timing context manager to log start and completion time of a code block', 'LogFormatter_format': 'format a log record with rank prefix, timestamp, elapsed delta, and indented multiline messages'}
```

## File: facebookresearch_cwm/cwm/logging/metrics.py

Prompts

```
['initialize the root logger with stdout and stderr handlers using a custom LogFormatter', 'add a file handler to the root logger that appends log output to a specified file', 'set the root logger level to a string name or integer value with fallback to NOTSET', 'use the log_timing context manager to log start and completion time of a code block', 'format a log record with rank prefix, timestamp, elapsed delta, and indented multiline messages', 'create a JsonlMetricsLogger instance to log experiment metrics to a JSONL file in a given directory', 'log a dictionary of metrics with an optional global step using the JsonlMetricsLogger log_metrics method', 'log a text string under a given key to the JSONL metrics file using the log_text method', 'sanitize a metrics dictionary by converting torch.Tensor values to Python floats using the _sanitize function', 'use the MetricsLogger as a context manager to automatically open and close the logger']
```

Usage

```
{'create_jsonl_metrics_logger': 'create a JsonlMetricsLogger instance to log experiment metrics to a JSONL file in a given directory', 'log_metrics_with_step': 'log a dictionary of metrics with an optional global step using the JsonlMetricsLogger log_metrics method', 'log_text_to_jsonl': 'log a text string under a given key to the JSONL metrics file using the log_text method', 'sanitize_torch_tensors': 'sanitize a metrics dictionary by converting torch.Tensor values to Python floats using the _sanitize function', 'use_metrics_logger_context_manager': 'use the MetricsLogger as a context manager to automatically open and close the logger'}
```

