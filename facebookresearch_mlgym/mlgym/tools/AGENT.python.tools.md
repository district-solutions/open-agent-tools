# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/mlgym/tools/parsing.py

Prompts

```
['parse a bash function file into a list of Command objects using ParseCommandBash', 'parse a script file with a YAML docstring into Command objects using ParseCommandBash', 'generate documentation strings for a list of Command objects using ParseCommandBash', 'generate detailed documentation with argument types and descriptions using ParseCommandDetailed', 'get a registered parser instance by name using ParseCommand.get', 'create a ToolsConfig dataclass to manage command files, environment variables, and blocklists for MLGym', 'parse command patterns into compiled regex for matching single-line and multi-line commands in ToolHandler', 'process multi-line command input by adding heredoc syntax to commands terminated by end markers', 'check if an action should be blocked by validating against the blocklist and standalone blocklist', 'retrieve the state command from ToolHandler to get the current working directory environment state']
```

Usage

```
{'parse_bash_command_file': 'parse a bash function file into a list of Command objects using ParseCommandBash', 'parse_script_with_yaml': 'parse a script file with a YAML docstring into Command objects using ParseCommandBash', 'generate_command_docs': 'generate documentation strings for a list of Command objects using ParseCommandBash', 'generate_detailed_command_docs': 'generate detailed documentation with argument types and descriptions using ParseCommandDetailed', 'get_parser_by_name': 'get a registered parser instance by name using ParseCommand.get'}
```

## File: facebookresearch_mlgym/mlgym/tools/tools.py

Prompts

```
['parse a bash function file into a list of Command objects using ParseCommandBash', 'parse a script file with a YAML docstring into Command objects using ParseCommandBash', 'generate documentation strings for a list of Command objects using ParseCommandBash', 'generate detailed documentation with argument types and descriptions using ParseCommandDetailed', 'get a registered parser instance by name using ParseCommand.get', 'create a ToolsConfig dataclass to manage command files, environment variables, and blocklists for MLGym', 'parse command patterns into compiled regex for matching single-line and multi-line commands in ToolHandler', 'process multi-line command input by adding heredoc syntax to commands terminated by end markers', 'check if an action should be blocked by validating against the blocklist and standalone blocklist', 'retrieve the state command from ToolHandler to get the current working directory environment state']
```

Usage

```
{'create_tools_config': 'create a ToolsConfig dataclass to manage command files, environment variables, and blocklists for MLGym', 'parse_command_patterns': 'parse command patterns into compiled regex for matching single-line and multi-line commands in ToolHandler', 'guard_multiline_input': 'process multi-line command input by adding heredoc syntax to commands terminated by end markers', 'check_blocked_action': 'check if an action should be blocked by validating against the blocklist and standalone blocklist', 'get_state_command': 'retrieve the state command from ToolHandler to get the current working directory environment state'}
```

