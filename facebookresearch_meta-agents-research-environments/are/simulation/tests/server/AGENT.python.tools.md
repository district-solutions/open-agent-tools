# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/server/are_simulation_mcp_server_test.py

Prompts

```
['test that apps are initialized and their tools are exposed on the MCP server', 'test that a scenario can be loaded and data matches the expected scenario data', 'test that state updates and tool calls work correctly for calendar app events', 'create a MockScenario subclass that initializes CalendarApp and ContactsApp with sample data', 'create an ARESimulationMCPServer instance with apps or a scenario to expose tools and resources', 'run the pytest test to verify no GUI imports exist outside the gui directory', 'create an AST visitor that collects all import statements from a Python file', 'extract all import statements from a Python file using AST parsing', 'list all Python files in a directory tree excluding gui and tests subdirectories', 'refactor the ImportVisitor class to also track relative imports or import aliases', 'test the SessionManager class initialization with inactivity limit and cleanup interval parameters', 'test adding and retrieving ARESimulationGui instances by session ID in the SessionManager', 'test checking whether a session exists in the SessionManager before and after adding it', 'test the SessionManager cleanup method that removes inactive sessions exceeding the inactivity limit', 'test stopping the SessionManager which halts all active ARESimulationGui instances and cleanup timers', 'test the update_graphql_cache function with string, list, and object inputs for a session', 'test the get_world_logs_for_graphql function to convert agent logs to GraphQL format', 'test processing of various agent log types like StepLog, SystemPromptLog, and TaskLog', 'test that SubagentLog processes child logs recursively with is_subagent flag', 'test that update_graphql_cache skips updates when the cached value has not changed']
```

Usage

```
{'test_app_initialization_and_tools_exposure': 'test that apps are initialized and their tools are exposed on the MCP server', 'test_scenario_loading': 'test that a scenario can be loaded and data matches the expected scenario data', 'test_state_update_and_tool_call': 'test that state updates and tool calls work correctly for calendar app events', 'create_MockScenario': 'create a MockScenario subclass that initializes CalendarApp and ContactsApp with sample data', 'create_ARESimulationMCPServer': 'create an ARESimulationMCPServer instance with apps or a scenario to expose tools and resources'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/server/gui_import_isolation_test.py

Prompts

```
['test that apps are initialized and their tools are exposed on the MCP server', 'test that a scenario can be loaded and data matches the expected scenario data', 'test that state updates and tool calls work correctly for calendar app events', 'create a MockScenario subclass that initializes CalendarApp and ContactsApp with sample data', 'create an ARESimulationMCPServer instance with apps or a scenario to expose tools and resources', 'run the pytest test to verify no GUI imports exist outside the gui directory', 'create an AST visitor that collects all import statements from a Python file', 'extract all import statements from a Python file using AST parsing', 'list all Python files in a directory tree excluding gui and tests subdirectories', 'refactor the ImportVisitor class to also track relative imports or import aliases', 'test the SessionManager class initialization with inactivity limit and cleanup interval parameters', 'test adding and retrieving ARESimulationGui instances by session ID in the SessionManager', 'test checking whether a session exists in the SessionManager before and after adding it', 'test the SessionManager cleanup method that removes inactive sessions exceeding the inactivity limit', 'test stopping the SessionManager which halts all active ARESimulationGui instances and cleanup timers', 'test the update_graphql_cache function with string, list, and object inputs for a session', 'test the get_world_logs_for_graphql function to convert agent logs to GraphQL format', 'test processing of various agent log types like StepLog, SystemPromptLog, and TaskLog', 'test that SubagentLog processes child logs recursively with is_subagent flag', 'test that update_graphql_cache skips updates when the cached value has not changed']
```

Usage

```
{'run_import_isolation_test': 'run the pytest test to verify no GUI imports exist outside the gui directory', 'create_import_visitor': 'create an AST visitor that collects all import statements from a Python file', 'extract_imports_from_file': 'extract all import statements from a Python file using AST parsing', 'list_python_files_excluding_gui': 'list all Python files in a directory tree excluding gui and tests subdirectories', 'refactor_import_visitor': 'refactor the ImportVisitor class to also track relative imports or import aliases'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/server/session_manager_test.py

Prompts

```
['test that apps are initialized and their tools are exposed on the MCP server', 'test that a scenario can be loaded and data matches the expected scenario data', 'test that state updates and tool calls work correctly for calendar app events', 'create a MockScenario subclass that initializes CalendarApp and ContactsApp with sample data', 'create an ARESimulationMCPServer instance with apps or a scenario to expose tools and resources', 'run the pytest test to verify no GUI imports exist outside the gui directory', 'create an AST visitor that collects all import statements from a Python file', 'extract all import statements from a Python file using AST parsing', 'list all Python files in a directory tree excluding gui and tests subdirectories', 'refactor the ImportVisitor class to also track relative imports or import aliases', 'test the SessionManager class initialization with inactivity limit and cleanup interval parameters', 'test adding and retrieving ARESimulationGui instances by session ID in the SessionManager', 'test checking whether a session exists in the SessionManager before and after adding it', 'test the SessionManager cleanup method that removes inactive sessions exceeding the inactivity limit', 'test stopping the SessionManager which halts all active ARESimulationGui instances and cleanup timers', 'test the update_graphql_cache function with string, list, and object inputs for a session', 'test the get_world_logs_for_graphql function to convert agent logs to GraphQL format', 'test processing of various agent log types like StepLog, SystemPromptLog, and TaskLog', 'test that SubagentLog processes child logs recursively with is_subagent flag', 'test that update_graphql_cache skips updates when the cached value has not changed']
```

Usage

```
{'test_session_manager_initialization': 'test the SessionManager class initialization with inactivity limit and cleanup interval parameters', 'test_add_and_get_are_simulation_instance': 'test adding and retrieving ARESimulationGui instances by session ID in the SessionManager', 'test_session_exists': 'test checking whether a session exists in the SessionManager before and after adding it', 'test_cleanup_inactive_are_simulation': 'test the SessionManager cleanup method that removes inactive sessions exceeding the inactivity limit', 'test_stop_session_manager': 'test stopping the SessionManager which halts all active ARESimulationGui instances and cleanup timers'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/server/subscription_test.py

Prompts

```
['test that apps are initialized and their tools are exposed on the MCP server', 'test that a scenario can be loaded and data matches the expected scenario data', 'test that state updates and tool calls work correctly for calendar app events', 'create a MockScenario subclass that initializes CalendarApp and ContactsApp with sample data', 'create an ARESimulationMCPServer instance with apps or a scenario to expose tools and resources', 'run the pytest test to verify no GUI imports exist outside the gui directory', 'create an AST visitor that collects all import statements from a Python file', 'extract all import statements from a Python file using AST parsing', 'list all Python files in a directory tree excluding gui and tests subdirectories', 'refactor the ImportVisitor class to also track relative imports or import aliases', 'test the SessionManager class initialization with inactivity limit and cleanup interval parameters', 'test adding and retrieving ARESimulationGui instances by session ID in the SessionManager', 'test checking whether a session exists in the SessionManager before and after adding it', 'test the SessionManager cleanup method that removes inactive sessions exceeding the inactivity limit', 'test stopping the SessionManager which halts all active ARESimulationGui instances and cleanup timers', 'test the update_graphql_cache function with string, list, and object inputs for a session', 'test the get_world_logs_for_graphql function to convert agent logs to GraphQL format', 'test processing of various agent log types like StepLog, SystemPromptLog, and TaskLog', 'test that SubagentLog processes child logs recursively with is_subagent flag', 'test that update_graphql_cache skips updates when the cached value has not changed']
```

Usage

```
{'test_update_graphql_cache': 'test the update_graphql_cache function with string, list, and object inputs for a session', 'test_get_world_logs_for_graphql': 'test the get_world_logs_for_graphql function to convert agent logs to GraphQL format', 'test_agent_log_types': 'test processing of various agent log types like StepLog, SystemPromptLog, and TaskLog', 'test_subagent_log_recursive': 'test that SubagentLog processes child logs recursively with is_subagent flag', 'test_graphql_cache_no_change': 'test that update_graphql_cache skips updates when the cached value has not changed'}
```

