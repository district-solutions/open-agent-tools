# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/daemon/channel.py

Prompts

```
['create a FileChannelAdapter instance with notifications, responses, and events JSONL file paths', 'send an agent response string that appends to agent_responses.jsonl and events.jsonl', 'read new notifications from notifications.jsonl since the last read offset', 'block and poll for new notifications with a configurable interval and timeout', 'review the FileChannelAdapter class for file-based daemon to agent communication patterns', 'execute an ENV action via CLI subprocess and return stdout or error result', 'build a CLI command list from an app name, function name, and arguments dictionary', 'run a CLI command as a subprocess with optional event ID and state directory', 'get the set of Click flag option names for a given CLI subcommand', 'refactor execute_cli_action to support custom timeout values for subprocess execution', 'run the Gaia2 event daemon to watch events.jsonl for agent actions and fire ENV reactions', 'run the Gaia2 event daemon with an LLM judge model for multi-turn scenario grading', 'run the Gaia2 event daemon in Docker mode with a notify URL for HTTP-based notifications', 'review the Gaia2EventDaemon class that polls events.jsonl, detects turn boundaries, and executes ENV actions', 'review the Click CLI entry point that configures and starts the Gaia2 event daemon with options', 'run a single Gaia2 scenario replay by calling CLI tools for each oracle turn with optional daemon support', 'run all scenario JSON files in a directory through the replay pipeline with daemon and verbose logging', 'load and parse a Gaia2 scenario JSON file to extract oracle agent events grouped by turn using topological sort', 'load a Gaia2 scenario using ScenarioLoader and EventProcessor for correct DAG-based turn assignment matching the judge', 'resolve double-brace event_id placeholders in function arguments by looking up return values from previously executed events']
```

Usage

```
{'create_filechanneladapter': 'create a FileChannelAdapter instance with notifications, responses, and events JSONL file paths', 'send_response': 'send an agent response string that appends to agent_responses.jsonl and events.jsonl', 'read_notifications': 'read new notifications from notifications.jsonl since the last read offset', 'wait_for_notification': 'block and poll for new notifications with a configurable interval and timeout', 'review_filechanneladapter': 'review the FileChannelAdapter class for file-based daemon to agent communication patterns'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/daemon/cli_executor.py

Prompts

```
['create a FileChannelAdapter instance with notifications, responses, and events JSONL file paths', 'send an agent response string that appends to agent_responses.jsonl and events.jsonl', 'read new notifications from notifications.jsonl since the last read offset', 'block and poll for new notifications with a configurable interval and timeout', 'review the FileChannelAdapter class for file-based daemon to agent communication patterns', 'execute an ENV action via CLI subprocess and return stdout or error result', 'build a CLI command list from an app name, function name, and arguments dictionary', 'run a CLI command as a subprocess with optional event ID and state directory', 'get the set of Click flag option names for a given CLI subcommand', 'refactor execute_cli_action to support custom timeout values for subprocess execution', 'run the Gaia2 event daemon to watch events.jsonl for agent actions and fire ENV reactions', 'run the Gaia2 event daemon with an LLM judge model for multi-turn scenario grading', 'run the Gaia2 event daemon in Docker mode with a notify URL for HTTP-based notifications', 'review the Gaia2EventDaemon class that polls events.jsonl, detects turn boundaries, and executes ENV actions', 'review the Click CLI entry point that configures and starts the Gaia2 event daemon with options', 'run a single Gaia2 scenario replay by calling CLI tools for each oracle turn with optional daemon support', 'run all scenario JSON files in a directory through the replay pipeline with daemon and verbose logging', 'load and parse a Gaia2 scenario JSON file to extract oracle agent events grouped by turn using topological sort', 'load a Gaia2 scenario using ScenarioLoader and EventProcessor for correct DAG-based turn assignment matching the judge', 'resolve double-brace event_id placeholders in function arguments by looking up return values from previously executed events']
```

Usage

```
{'execute_cli_action': 'execute an ENV action via CLI subprocess and return stdout or error result', 'build_cli_cmd': 'build a CLI command list from an app name, function name, and arguments dictionary', 'run_cli': 'run a CLI command as a subprocess with optional event ID and state directory', 'get_flag_params': 'get the set of Click flag option names for a given CLI subcommand', 'refactor_execute_cli_action': 'refactor execute_cli_action to support custom timeout values for subprocess execution'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/daemon/eventd.py

Prompts

```
['create a FileChannelAdapter instance with notifications, responses, and events JSONL file paths', 'send an agent response string that appends to agent_responses.jsonl and events.jsonl', 'read new notifications from notifications.jsonl since the last read offset', 'block and poll for new notifications with a configurable interval and timeout', 'review the FileChannelAdapter class for file-based daemon to agent communication patterns', 'execute an ENV action via CLI subprocess and return stdout or error result', 'build a CLI command list from an app name, function name, and arguments dictionary', 'run a CLI command as a subprocess with optional event ID and state directory', 'get the set of Click flag option names for a given CLI subcommand', 'refactor execute_cli_action to support custom timeout values for subprocess execution', 'run the Gaia2 event daemon to watch events.jsonl for agent actions and fire ENV reactions', 'run the Gaia2 event daemon with an LLM judge model for multi-turn scenario grading', 'run the Gaia2 event daemon in Docker mode with a notify URL for HTTP-based notifications', 'review the Gaia2EventDaemon class that polls events.jsonl, detects turn boundaries, and executes ENV actions', 'review the Click CLI entry point that configures and starts the Gaia2 event daemon with options', 'run a single Gaia2 scenario replay by calling CLI tools for each oracle turn with optional daemon support', 'run all scenario JSON files in a directory through the replay pipeline with daemon and verbose logging', 'load and parse a Gaia2 scenario JSON file to extract oracle agent events grouped by turn using topological sort', 'load a Gaia2 scenario using ScenarioLoader and EventProcessor for correct DAG-based turn assignment matching the judge', 'resolve double-brace event_id placeholders in function arguments by looking up return values from previously executed events']
```

Usage

```
{'run_gaia2_event_daemon': 'run the Gaia2 event daemon to watch events.jsonl for agent actions and fire ENV reactions', 'run_daemon_with_judge': 'run the Gaia2 event daemon with an LLM judge model for multi-turn scenario grading', 'run_daemon_docker_mode': 'run the Gaia2 event daemon in Docker mode with a notify URL for HTTP-based notifications', 'review_Gaia2EventDaemon_class': 'review the Gaia2EventDaemon class that polls events.jsonl, detects turn boundaries, and executes ENV actions', 'review_main_cli_entry': 'review the Click CLI entry point that configures and starts the Gaia2 event daemon with options'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/daemon/replay.py

Prompts

```
['create a FileChannelAdapter instance with notifications, responses, and events JSONL file paths', 'send an agent response string that appends to agent_responses.jsonl and events.jsonl', 'read new notifications from notifications.jsonl since the last read offset', 'block and poll for new notifications with a configurable interval and timeout', 'review the FileChannelAdapter class for file-based daemon to agent communication patterns', 'execute an ENV action via CLI subprocess and return stdout or error result', 'build a CLI command list from an app name, function name, and arguments dictionary', 'run a CLI command as a subprocess with optional event ID and state directory', 'get the set of Click flag option names for a given CLI subcommand', 'refactor execute_cli_action to support custom timeout values for subprocess execution', 'run the Gaia2 event daemon to watch events.jsonl for agent actions and fire ENV reactions', 'run the Gaia2 event daemon with an LLM judge model for multi-turn scenario grading', 'run the Gaia2 event daemon in Docker mode with a notify URL for HTTP-based notifications', 'review the Gaia2EventDaemon class that polls events.jsonl, detects turn boundaries, and executes ENV actions', 'review the Click CLI entry point that configures and starts the Gaia2 event daemon with options', 'run a single Gaia2 scenario replay by calling CLI tools for each oracle turn with optional daemon support', 'run all scenario JSON files in a directory through the replay pipeline with daemon and verbose logging', 'load and parse a Gaia2 scenario JSON file to extract oracle agent events grouped by turn using topological sort', 'load a Gaia2 scenario using ScenarioLoader and EventProcessor for correct DAG-based turn assignment matching the judge', 'resolve double-brace event_id placeholders in function arguments by looking up return values from previously executed events']
```

Usage

```
{'run_replay_scenario': 'run a single Gaia2 scenario replay by calling CLI tools for each oracle turn with optional daemon support', 'run_replay_scenario_batch': 'run all scenario JSON files in a directory through the replay pipeline with daemon and verbose logging', 'load_scenario_events': 'load and parse a Gaia2 scenario JSON file to extract oracle agent events grouped by turn using topological sort', 'load_scenario_events_via_env': 'load a Gaia2 scenario using ScenarioLoader and EventProcessor for correct DAG-based turn assignment matching the judge', 'resolve_placeholders': 'resolve double-brace event_id placeholders in function arguments by looking up return values from previously executed events'}
```

