# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/optional-skills/mcp/fastmcp/templates/api_wrapper.py

Prompts

```
['build a FastMCP server that wraps an upstream REST API with configurable base URL, token, and timeout', 'test the upstream API health endpoint by calling the health_check tool and verifying the response', 'create a tool that fetches a single resource by ID from an upstream REST API', 'create a tool that searches upstream resources by query string with a configurable limit', 'run the FastMCP api_wrapper server as a CLI tool with API_BASE_URL and API_TOKEN environment variables', 'run a FastMCP server that exposes read-only SQLite database tools via MCP protocol', 'list all user-defined SQLite tables in the database excluding internal sqlite_ tables', 'describe columns for a SQLite table including name, type, nullability, default value, and primary key', 'run a read-only SELECT query on a SQLite database and return rows as dictionaries with column names', 'test the database server by listing tables, describing a table schema, and running a SELECT query', 'summarize a UTF-8 text file and return its character count, line count, and a preview of its content', 'search a UTF-8 text file for case-insensitive matches and return matching line numbers and text', 'read a UTF-8 text file and expose it as an MCP resource accessible by file path', 'build a FastMCP server with tools for summarizing and searching text files, runnable as a CLI module', 'test the file processor module by calling summarize_text_file and search_text_file on a sample text file']
```

Usage

```
{'build_api_wrapper_mcp_server': 'build a FastMCP server that wraps an upstream REST API with configurable base URL, token, and timeout', 'test_health_check': 'test the upstream API health endpoint by calling the health_check tool and verifying the response', 'create_get_resource_tool': 'create a tool that fetches a single resource by ID from an upstream REST API', 'create_search_resources_tool': 'create a tool that searches upstream resources by query string with a configurable limit', 'run_api_wrapper_server': 'run the FastMCP api_wrapper server as a CLI tool with API_BASE_URL and API_TOKEN environment variables'}
```

## File: NousResearch_hermes-agent/optional-skills/mcp/fastmcp/templates/database_server.py

Prompts

```
['build a FastMCP server that wraps an upstream REST API with configurable base URL, token, and timeout', 'test the upstream API health endpoint by calling the health_check tool and verifying the response', 'create a tool that fetches a single resource by ID from an upstream REST API', 'create a tool that searches upstream resources by query string with a configurable limit', 'run the FastMCP api_wrapper server as a CLI tool with API_BASE_URL and API_TOKEN environment variables', 'run a FastMCP server that exposes read-only SQLite database tools via MCP protocol', 'list all user-defined SQLite tables in the database excluding internal sqlite_ tables', 'describe columns for a SQLite table including name, type, nullability, default value, and primary key', 'run a read-only SELECT query on a SQLite database and return rows as dictionaries with column names', 'test the database server by listing tables, describing a table schema, and running a SELECT query', 'summarize a UTF-8 text file and return its character count, line count, and a preview of its content', 'search a UTF-8 text file for case-insensitive matches and return matching line numbers and text', 'read a UTF-8 text file and expose it as an MCP resource accessible by file path', 'build a FastMCP server with tools for summarizing and searching text files, runnable as a CLI module', 'test the file processor module by calling summarize_text_file and search_text_file on a sample text file']
```

Usage

```
{'run_database_server': 'run a FastMCP server that exposes read-only SQLite database tools via MCP protocol', 'list_tables_database': 'list all user-defined SQLite tables in the database excluding internal sqlite_ tables', 'describe_table_database': 'describe columns for a SQLite table including name, type, nullability, default value, and primary key', 'query_database': 'run a read-only SELECT query on a SQLite database and return rows as dictionaries with column names', 'test_database_server': 'test the database server by listing tables, describing a table schema, and running a SELECT query'}
```

## File: NousResearch_hermes-agent/optional-skills/mcp/fastmcp/templates/file_processor.py

Prompts

```
['build a FastMCP server that wraps an upstream REST API with configurable base URL, token, and timeout', 'test the upstream API health endpoint by calling the health_check tool and verifying the response', 'create a tool that fetches a single resource by ID from an upstream REST API', 'create a tool that searches upstream resources by query string with a configurable limit', 'run the FastMCP api_wrapper server as a CLI tool with API_BASE_URL and API_TOKEN environment variables', 'run a FastMCP server that exposes read-only SQLite database tools via MCP protocol', 'list all user-defined SQLite tables in the database excluding internal sqlite_ tables', 'describe columns for a SQLite table including name, type, nullability, default value, and primary key', 'run a read-only SELECT query on a SQLite database and return rows as dictionaries with column names', 'test the database server by listing tables, describing a table schema, and running a SELECT query', 'summarize a UTF-8 text file and return its character count, line count, and a preview of its content', 'search a UTF-8 text file for case-insensitive matches and return matching line numbers and text', 'read a UTF-8 text file and expose it as an MCP resource accessible by file path', 'build a FastMCP server with tools for summarizing and searching text files, runnable as a CLI module', 'test the file processor module by calling summarize_text_file and search_text_file on a sample text file']
```

Usage

```
{'summarize_text_file': 'summarize a UTF-8 text file and return its character count, line count, and a preview of its content', 'search_text_file': 'search a UTF-8 text file for case-insensitive matches and return matching line numbers and text', 'read_file_resource': 'read a UTF-8 text file and expose it as an MCP resource accessible by file path', 'build_mcp_server': 'build a FastMCP server with tools for summarizing and searching text files, runnable as a CLI module', 'test_file_processor': 'test the file processor module by calling summarize_text_file and search_text_file on a sample text file'}
```

