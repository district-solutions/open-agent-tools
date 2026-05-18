# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/mlgym/agent/base.py

Prompts

```
['run a BaseAgent in an MLGym environment and return the agent info and trajectory', 'setup a BaseAgent for a new task by initializing system messages and demonstrations', 'process an observation and generate the next thought action and output from the model', 'save the agent trajectory including history environment state and model stats to disk', 'validate model output format and requery up to two times on format or blocklist errors', 'use HistoryProcessor.get to retrieve a registered history processor instance by its class name', 'use LastNObservations to keep the first and last N user messages and summarize older ones', 'use ClosedWindowHistoryProcessor to replace outdated code windows for the same file with line count summaries', 'use DefaultHistoryProcessor to return conversation history without any modifications', 'use last_n_history to keep the first message and last N user messages while summarizing older output', 'parse a JSON model response into thought and action using JsonParser', 'parse an XML-tagged model response into thought and action using XMLThoughtActionParser', 'parse a discussion and code block response using ThoughtActionParser', 'parse a single command model response using ActionParser', 'get a parser instance by name from the ParseFunction registry']
```

Usage

```
{'run_BaseAgent': 'run a BaseAgent in an MLGym environment and return the agent info and trajectory', 'setup_BaseAgent': 'setup a BaseAgent for a new task by initializing system messages and demonstrations', 'forward_BaseAgent': 'process an observation and generate the next thought action and output from the model', 'save_trajectory_BaseAgent': 'save the agent trajectory including history environment state and model stats to disk', 'check_format_and_requery_BaseAgent': 'validate model output format and requery up to two times on format or blocklist errors'}
```

## File: facebookresearch_mlgym/mlgym/agent/history_processors.py

Prompts

```
['run a BaseAgent in an MLGym environment and return the agent info and trajectory', 'setup a BaseAgent for a new task by initializing system messages and demonstrations', 'process an observation and generate the next thought action and output from the model', 'save the agent trajectory including history environment state and model stats to disk', 'validate model output format and requery up to two times on format or blocklist errors', 'use HistoryProcessor.get to retrieve a registered history processor instance by its class name', 'use LastNObservations to keep the first and last N user messages and summarize older ones', 'use ClosedWindowHistoryProcessor to replace outdated code windows for the same file with line count summaries', 'use DefaultHistoryProcessor to return conversation history without any modifications', 'use last_n_history to keep the first message and last N user messages while summarizing older output', 'parse a JSON model response into thought and action using JsonParser', 'parse an XML-tagged model response into thought and action using XMLThoughtActionParser', 'parse a discussion and code block response using ThoughtActionParser', 'parse a single command model response using ActionParser', 'get a parser instance by name from the ParseFunction registry']
```

Usage

```
{'get_history_processor_by_name': 'use HistoryProcessor.get to retrieve a registered history processor instance by its class name', 'truncate_history_to_last_n': 'use LastNObservations to keep the first and last N user messages and summarize older ones', 'replace_outdated_code_windows': 'use ClosedWindowHistoryProcessor to replace outdated code windows for the same file with line count summaries', 'pass_through_history_unchanged': 'use DefaultHistoryProcessor to return conversation history without any modifications', 'summarize_old_user_messages': 'use last_n_history to keep the first message and last N user messages while summarizing older output'}
```

## File: facebookresearch_mlgym/mlgym/agent/parsing.py

Prompts

```
['run a BaseAgent in an MLGym environment and return the agent info and trajectory', 'setup a BaseAgent for a new task by initializing system messages and demonstrations', 'process an observation and generate the next thought action and output from the model', 'save the agent trajectory including history environment state and model stats to disk', 'validate model output format and requery up to two times on format or blocklist errors', 'use HistoryProcessor.get to retrieve a registered history processor instance by its class name', 'use LastNObservations to keep the first and last N user messages and summarize older ones', 'use ClosedWindowHistoryProcessor to replace outdated code windows for the same file with line count summaries', 'use DefaultHistoryProcessor to return conversation history without any modifications', 'use last_n_history to keep the first message and last N user messages while summarizing older output', 'parse a JSON model response into thought and action using JsonParser', 'parse an XML-tagged model response into thought and action using XMLThoughtActionParser', 'parse a discussion and code block response using ThoughtActionParser', 'parse a single command model response using ActionParser', 'get a parser instance by name from the ParseFunction registry']
```

Usage

```
{'parse_json_model_response': 'parse a JSON model response into thought and action using JsonParser', 'parse_xml_command_response': 'parse an XML-tagged model response into thought and action using XMLThoughtActionParser', 'parse_thought_action_response': 'parse a discussion and code block response using ThoughtActionParser', 'parse_single_command_response': 'parse a single command model response using ActionParser', 'lookup_parser_by_name': 'get a parser instance by name from the ParseFunction registry'}
```

