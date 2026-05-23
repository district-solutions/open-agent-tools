# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/logging/history_buffer.py

Prompts

```
['create a HistoryBuffer instance to record log history with a configurable max length', 'update a HistoryBuffer with new log values and their accumulation counts', 'compute the mean of the latest window_size values in a HistoryBuffer', 'get the minimum or maximum value within a window of a HistoryBuffer', 'register a custom statistics method on HistoryBuffer for use via the statistics method', 'create an MMLogger instance with a custom name and optional log file path', 'use MMFormatter to format log messages with colorful prefixes for different log levels', 'use FilterDuplicateWarning to suppress repeated warning messages in the logging output', 'call print_log to log a message using an existing MMLogger instance or the current logger', 'get the current MMLogger instance using the get_current_instance class method', 'create a MessageHub instance to record log scalars and runtime information during training', 'update a scalar log value like loss or learning rate in the MessageHub', 'batch update multiple scalar log values from a dictionary into the MessageHub', 'retrieve a HistoryBuffer instance by key from the MessageHub log scalars', 'serialize the MessageHub log scalars, runtime info, and resumed keys to a state dictionary']
```

Usage

```
{'create_HistoryBuffer': 'create a HistoryBuffer instance to record log history with a configurable max length', 'update_HistoryBuffer': 'update a HistoryBuffer with new log values and their accumulation counts', 'statistics_HistoryBuffer_mean': 'compute the mean of the latest window_size values in a HistoryBuffer', 'statistics_HistoryBuffer_min_max': 'get the minimum or maximum value within a window of a HistoryBuffer', 'register_HistoryBuffer_statistics': 'register a custom statistics method on HistoryBuffer for use via the statistics method'}
```

## File: facebookresearch_sapiens/engine/mmengine/logging/logger.py

Prompts

```
['create a HistoryBuffer instance to record log history with a configurable max length', 'update a HistoryBuffer with new log values and their accumulation counts', 'compute the mean of the latest window_size values in a HistoryBuffer', 'get the minimum or maximum value within a window of a HistoryBuffer', 'register a custom statistics method on HistoryBuffer for use via the statistics method', 'create an MMLogger instance with a custom name and optional log file path', 'use MMFormatter to format log messages with colorful prefixes for different log levels', 'use FilterDuplicateWarning to suppress repeated warning messages in the logging output', 'call print_log to log a message using an existing MMLogger instance or the current logger', 'get the current MMLogger instance using the get_current_instance class method', 'create a MessageHub instance to record log scalars and runtime information during training', 'update a scalar log value like loss or learning rate in the MessageHub', 'batch update multiple scalar log values from a dictionary into the MessageHub', 'retrieve a HistoryBuffer instance by key from the MessageHub log scalars', 'serialize the MessageHub log scalars, runtime info, and resumed keys to a state dictionary']
```

Usage

```
{'create_MMLogger_instance': 'create an MMLogger instance with a custom name and optional log file path', 'use_MMFormatter_colorful_logs': 'use MMFormatter to format log messages with colorful prefixes for different log levels', 'filter_duplicate_warnings': 'use FilterDuplicateWarning to suppress repeated warning messages in the logging output', 'print_log_message': 'call print_log to log a message using an existing MMLogger instance or the current logger', 'get_current_MMLogger': 'get the current MMLogger instance using the get_current_instance class method'}
```

## File: facebookresearch_sapiens/engine/mmengine/logging/message_hub.py

Prompts

```
['create a HistoryBuffer instance to record log history with a configurable max length', 'update a HistoryBuffer with new log values and their accumulation counts', 'compute the mean of the latest window_size values in a HistoryBuffer', 'get the minimum or maximum value within a window of a HistoryBuffer', 'register a custom statistics method on HistoryBuffer for use via the statistics method', 'create an MMLogger instance with a custom name and optional log file path', 'use MMFormatter to format log messages with colorful prefixes for different log levels', 'use FilterDuplicateWarning to suppress repeated warning messages in the logging output', 'call print_log to log a message using an existing MMLogger instance or the current logger', 'get the current MMLogger instance using the get_current_instance class method', 'create a MessageHub instance to record log scalars and runtime information during training', 'update a scalar log value like loss or learning rate in the MessageHub', 'batch update multiple scalar log values from a dictionary into the MessageHub', 'retrieve a HistoryBuffer instance by key from the MessageHub log scalars', 'serialize the MessageHub log scalars, runtime info, and resumed keys to a state dictionary']
```

Usage

```
{'create_MessageHub_instance': 'create a MessageHub instance to record log scalars and runtime information during training', 'update_scalar_MessageHub': 'update a scalar log value like loss or learning rate in the MessageHub', 'update_scalars_MessageHub': 'batch update multiple scalar log values from a dictionary into the MessageHub', 'get_scalar_MessageHub': 'retrieve a HistoryBuffer instance by key from the MessageHub log scalars', 'state_dict_MessageHub': 'serialize the MessageHub log scalars, runtime info, and resumed keys to a state dictionary'}
```

