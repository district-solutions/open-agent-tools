# Agent Python Tools

- repo: open-webui/open-terminal
- repo_uri: https://github.com/open-webui/open-terminal

## File: open-webui_open-terminal/open_terminal/cli.py

Prompts

```
['run the open-terminal sandbox API server with custom host, port, and API key options', 'run the MCP server using stdio transport for terminal-based interaction', 'run the MCP server using streamable-http transport with custom host and port', 'run the sandbox API server loading settings from a TOML config file', 'run the sandbox API server with restricted CORS allowed origins for production', 'build a function that loads and merges system and user TOML config files with override precedence', 'create an init function that loads config files and caches them module-wide for later lookups', 'test the load_config function with an explicit TOML file path argument', 'refactor the config get function to support nested key lookups with dot notation', 'review the config module for correct precedence ordering of system, user, and explicit config files', 'execute a shell command in the background and return a command ID with output', 'send input text to a running background process stdin', 'kill a running background process by sending SIGTERM or SIGKILL', 'list all tracked background processes with their status and exit codes', 'get command status and new output since last poll for a background process', 'read a file and return its contents with optional line range', 'write text content to a file creating parent directories automatically', 'search for a text pattern across files in a directory using regex or literal matching', 'search for files and subdirectories by name within a directory using glob patterns', 'find and replace exact strings in a file with optional line range narrowing', 'upload a file to the specified path via multipart form data', 'bundle files and directories into a single ZIP archive for download', 'create a new interactive terminal session with PTY backend', 'attach to an existing terminal session via WebSocket for interactive use', 'detect TCP ports currently listening on localhost filtered by user']
```

Usage

```
{'run_sandbox_api_server': 'run the open-terminal sandbox API server with custom host, port, and API key options', 'run_mcp_server_stdio': 'run the MCP server using stdio transport for terminal-based interaction', 'run_mcp_server_streamable_http': 'run the MCP server using streamable-http transport with custom host and port', 'run_server_with_config': 'run the sandbox API server loading settings from a TOML config file', 'run_server_with_cors': 'run the sandbox API server with restricted CORS allowed origins for production'}
```

## File: open-webui_open-terminal/open_terminal/config.py

Prompts

```
['run the open-terminal sandbox API server with custom host, port, and API key options', 'run the MCP server using stdio transport for terminal-based interaction', 'run the MCP server using streamable-http transport with custom host and port', 'run the sandbox API server loading settings from a TOML config file', 'run the sandbox API server with restricted CORS allowed origins for production', 'build a function that loads and merges system and user TOML config files with override precedence', 'create an init function that loads config files and caches them module-wide for later lookups', 'test the load_config function with an explicit TOML file path argument', 'refactor the config get function to support nested key lookups with dot notation', 'review the config module for correct precedence ordering of system, user, and explicit config files', 'execute a shell command in the background and return a command ID with output', 'send input text to a running background process stdin', 'kill a running background process by sending SIGTERM or SIGKILL', 'list all tracked background processes with their status and exit codes', 'get command status and new output since last poll for a background process', 'read a file and return its contents with optional line range', 'write text content to a file creating parent directories automatically', 'search for a text pattern across files in a directory using regex or literal matching', 'search for files and subdirectories by name within a directory using glob patterns', 'find and replace exact strings in a file with optional line range narrowing', 'upload a file to the specified path via multipart form data', 'bundle files and directories into a single ZIP archive for download', 'create a new interactive terminal session with PTY backend', 'attach to an existing terminal session via WebSocket for interactive use', 'detect TCP ports currently listening on localhost filtered by user']
```

Usage

```
{'build_load_toml_config': 'build a function that loads and merges system and user TOML config files with override precedence', 'create_init_config_cache': 'create an init function that loads config files and caches them module-wide for later lookups', 'test_load_config_explicit_path': 'test the load_config function with an explicit TOML file path argument', 'refactor_config_get': 'refactor the config get function to support nested key lookups with dot notation', 'review_config_precedence': 'review the config module for correct precedence ordering of system, user, and explicit config files'}
```

## File: open-webui_open-terminal/open_terminal/main.py

Prompts

```
['run the open-terminal sandbox API server with custom host, port, and API key options', 'run the MCP server using stdio transport for terminal-based interaction', 'run the MCP server using streamable-http transport with custom host and port', 'run the sandbox API server loading settings from a TOML config file', 'run the sandbox API server with restricted CORS allowed origins for production', 'build a function that loads and merges system and user TOML config files with override precedence', 'create an init function that loads config files and caches them module-wide for later lookups', 'test the load_config function with an explicit TOML file path argument', 'refactor the config get function to support nested key lookups with dot notation', 'review the config module for correct precedence ordering of system, user, and explicit config files', 'execute a shell command in the background and return a command ID with output', 'send input text to a running background process stdin', 'kill a running background process by sending SIGTERM or SIGKILL', 'list all tracked background processes with their status and exit codes', 'get command status and new output since last poll for a background process', 'read a file and return its contents with optional line range', 'write text content to a file creating parent directories automatically', 'search for a text pattern across files in a directory using regex or literal matching', 'search for files and subdirectories by name within a directory using glob patterns', 'find and replace exact strings in a file with optional line range narrowing', 'upload a file to the specified path via multipart form data', 'bundle files and directories into a single ZIP archive for download', 'create a new interactive terminal session with PTY backend', 'attach to an existing terminal session via WebSocket for interactive use', 'detect TCP ports currently listening on localhost filtered by user']
```

Usage

```
{'execute_shell_command': 'execute a shell command in the background and return a command ID with output', 'send_input_to_process': 'send input text to a running background process stdin', 'kill_running_process': 'kill a running background process by sending SIGTERM or SIGKILL', 'list_running_processes': 'list all tracked background processes with their status and exit codes', 'get_process_status': 'get command status and new output since last poll for a background process', 'read_file_with_range': 'read a file and return its contents with optional line range', 'write_file_content': 'write text content to a file creating parent directories automatically', 'search_file_contents': 'search for a text pattern across files in a directory using regex or literal matching', 'search_files_by_name': 'search for files and subdirectories by name within a directory using glob patterns', 'replace_file_content': 'find and replace exact strings in a file with optional line range narrowing', 'upload_file_to_server': 'upload a file to the specified path via multipart form data', 'bundle_files_into_archive': 'bundle files and directories into a single ZIP archive for download', 'create_terminal_session': 'create a new interactive terminal session with PTY backend', 'attach_terminal_via_websocket': 'attach to an existing terminal session via WebSocket for interactive use', 'detect_listening_ports': 'detect TCP ports currently listening on localhost filtered by user'}
```

