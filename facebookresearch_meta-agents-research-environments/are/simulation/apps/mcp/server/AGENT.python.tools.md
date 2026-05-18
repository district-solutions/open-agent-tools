# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/apps/mcp/server/are_simulation_mcp_server.py

Prompts

```
['run an MCP server that wraps multiple ARE simulation apps using stdio or sse transport', 'run an MCP server loaded from a scenario class to expose apps and their states', "load an ARE simulation app class from its fully qualified path and verify it's a subclass of App", "load a Scenario class from its fully qualified path and verify it's a subclass of Scenario", "get an ARE simulation app instance by its name from the MCP server's registered apps"]
```

Usage

```
{'run_mcp_server_with_apps': 'run an MCP server that wraps multiple ARE simulation apps using stdio or sse transport', 'run_mcp_server_with_scenario': 'run an MCP server loaded from a scenario class to expose apps and their states', 'load_app_class': "load an ARE simulation app class from its fully qualified path and verify it's a subclass of App", 'load_scenario_class': "load a Scenario class from its fully qualified path and verify it's a subclass of Scenario", 'get_app_by_name': "get an ARE simulation app instance by its name from the MCP server's registered apps"}
```

