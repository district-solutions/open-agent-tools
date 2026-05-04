# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/web/app.py

Prompts

```
['create a Flask application with SocketIO for docstring generation visualization', 'test the LLM API connection with Claude or OpenAI using an API key', 'start the docstring generation process for a given repository path and config', 'stop the running docstring generation process', 'get the current completeness evaluation of docstrings in a repository', 'get the default LLM and flow control configuration from agent_config.yaml or hardcoded defaults', 'validate a configuration dictionary has required llm, flow_control, and docstring_options sections', 'save a validated configuration dictionary to a temporary YAML file for the generation process', 'review the get_default_config function to understand how it loads agent_config.yaml', 'refactor the validate_config function to support additional required configuration sections', 'create an OutputHandler thread to read subprocess stdout and emit SocketIO events for status and log updates', 'parse STATUS lines from subprocess output to extract agent name and message for visualization updates', 'filter out box drawing characters and progress indicators from subprocess log output using regex patterns', 'get the repository structure as a tree dictionary for a given repo path', 'update the active agent and status message in the visualization state singleton', 'update the docstring generation progress with total, processed, and component status counts', 'add a log message to the visualization state keeping only the latest 1000 messages']
```

Usage

```
{'create_flask_app': 'create a Flask application with SocketIO for docstring generation visualization', 'test_llm_api': 'test the LLM API connection with Claude or OpenAI using an API key', 'start_docstring_generation': 'start the docstring generation process for a given repository path and config', 'stop_docstring_generation': 'stop the running docstring generation process', 'get_completeness_data': 'get the current completeness evaluation of docstrings in a repository'}
```

## File: facebookresearch_docagent/src/web/config_handler.py

Prompts

```
['create a Flask application with SocketIO for docstring generation visualization', 'test the LLM API connection with Claude or OpenAI using an API key', 'start the docstring generation process for a given repository path and config', 'stop the running docstring generation process', 'get the current completeness evaluation of docstrings in a repository', 'get the default LLM and flow control configuration from agent_config.yaml or hardcoded defaults', 'validate a configuration dictionary has required llm, flow_control, and docstring_options sections', 'save a validated configuration dictionary to a temporary YAML file for the generation process', 'review the get_default_config function to understand how it loads agent_config.yaml', 'refactor the validate_config function to support additional required configuration sections', 'create an OutputHandler thread to read subprocess stdout and emit SocketIO events for status and log updates', 'parse STATUS lines from subprocess output to extract agent name and message for visualization updates', 'filter out box drawing characters and progress indicators from subprocess log output using regex patterns', 'get the repository structure as a tree dictionary for a given repo path', 'update the active agent and status message in the visualization state singleton', 'update the docstring generation progress with total, processed, and component status counts', 'add a log message to the visualization state keeping only the latest 1000 messages']
```

Usage

```
{'get_default_config': 'get the default LLM and flow control configuration from agent_config.yaml or hardcoded defaults', 'validate_config': 'validate a configuration dictionary has required llm, flow_control, and docstring_options sections', 'save_config': 'save a validated configuration dictionary to a temporary YAML file for the generation process', 'review_get_default_config': 'review the get_default_config function to understand how it loads agent_config.yaml', 'refactor_validate_config': 'refactor the validate_config function to support additional required configuration sections'}
```

## File: facebookresearch_docagent/src/web/process_handler.py

Prompts

```
['create a Flask application with SocketIO for docstring generation visualization', 'test the LLM API connection with Claude or OpenAI using an API key', 'start the docstring generation process for a given repository path and config', 'stop the running docstring generation process', 'get the current completeness evaluation of docstrings in a repository', 'get the default LLM and flow control configuration from agent_config.yaml or hardcoded defaults', 'validate a configuration dictionary has required llm, flow_control, and docstring_options sections', 'save a validated configuration dictionary to a temporary YAML file for the generation process', 'review the get_default_config function to understand how it loads agent_config.yaml', 'refactor the validate_config function to support additional required configuration sections', 'create an OutputHandler thread to read subprocess stdout and emit SocketIO events for status and log updates', 'parse STATUS lines from subprocess output to extract agent name and message for visualization updates', 'filter out box drawing characters and progress indicators from subprocess log output using regex patterns', 'get the repository structure as a tree dictionary for a given repo path', 'update the active agent and status message in the visualization state singleton', 'update the docstring generation progress with total, processed, and component status counts', 'add a log message to the visualization state keeping only the latest 1000 messages']
```

Usage

```
{'start_docstring_generation': 'start the docstring generation process for a repository using a config file and web integration', 'stop_docstring_generation': 'stop the running docstring generation process gracefully with a 5 second timeout before force killing', 'create_output_handler_thread': 'create an OutputHandler thread to read subprocess stdout and emit SocketIO events for status and log updates', 'parse_agent_status_output': 'parse STATUS lines from subprocess output to extract agent name and message for visualization updates', 'filter_visualization_output': 'filter out box drawing characters and progress indicators from subprocess log output using regex patterns'}
```

## File: facebookresearch_docagent/src/web/visualization_handler.py

Prompts

```
['create a Flask application with SocketIO for docstring generation visualization', 'test the LLM API connection with Claude or OpenAI using an API key', 'start the docstring generation process for a given repository path and config', 'stop the running docstring generation process', 'get the current completeness evaluation of docstrings in a repository', 'get the default LLM and flow control configuration from agent_config.yaml or hardcoded defaults', 'validate a configuration dictionary has required llm, flow_control, and docstring_options sections', 'save a validated configuration dictionary to a temporary YAML file for the generation process', 'review the get_default_config function to understand how it loads agent_config.yaml', 'refactor the validate_config function to support additional required configuration sections', 'create an OutputHandler thread to read subprocess stdout and emit SocketIO events for status and log updates', 'parse STATUS lines from subprocess output to extract agent name and message for visualization updates', 'filter out box drawing characters and progress indicators from subprocess log output using regex patterns', 'get the repository structure as a tree dictionary for a given repo path', 'update the active agent and status message in the visualization state singleton', 'update the docstring generation progress with total, processed, and component status counts', 'add a log message to the visualization state keeping only the latest 1000 messages']
```

Usage

```
{'get_repo_structure': 'get the repository structure as a tree dictionary for a given repo path', 'update_agent_status': 'update the active agent and status message in the visualization state singleton', 'update_progress': 'update the docstring generation progress with total, processed, and component status counts', 'get_completeness_data': 'get completeness evaluation data for a repository by running the eval script or using mock results', 'add_log_message': 'add a log message to the visualization state keeping only the latest 1000 messages'}
```

