# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/loggers/logger.py

Prompts

```
['create a LoggerConfig with custom output_directory, buffer_size, and flush_period for labgraph logging', 'implement the abstract Logger write method to persist messages_by_logging_id to disk', 'run the Logger background loop that periodically flushes buffered messages based on buffer_size or flush_period', 'buffer messages by logging_id then flush the buffer to get a dict of messages grouped by logging_id', 'setup a Logger to subscribe to Cthulhu streams and create Consumer callbacks for each logging_id']
```

Usage

```
{'create_logger_config': 'create a LoggerConfig with custom output_directory, buffer_size, and flush_period for labgraph logging', 'implement_logger_write': 'implement the abstract Logger write method to persist messages_by_logging_id to disk', 'run_logger_background_loop': 'run the Logger background loop that periodically flushes buffered messages based on buffer_size or flush_period', 'buffer_and_flush_messages': 'buffer messages by logging_id then flush the buffer to get a dict of messages grouped by logging_id', 'setup_logger_consumers': 'setup a Logger to subscribe to Cthulhu streams and create Consumer callbacks for each logging_id'}
```

