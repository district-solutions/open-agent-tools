# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/agent_endpoints/agent_registry.py

Prompts

```
['create an agent and add it to the database with litellm params, headers, and rate limits', 'delete an agent from the database by its agent id', 'patch an agent in the database with partial updates to name, params, or permissions', 'update an agent in the database with full replacement of name, params, headers, and rate limits', 'get all agents from the database ordered by creation time descending', 'build HTTP headers for A2A agent calls by merging dynamic client request headers with static admin-configured headers', 'test the merge_agent_headers function with dynamic and static header mappings', 'refactor merge_agent_headers to support custom merge strategies and key collision handling', 'review the merge_agent_headers function for header precedence and type conversion correctness', 'summarize how merge_agent_headers combines dynamic and static HTTP headers for outbound A2A agent calls']
```

Usage

```
{'create_agent_add_to_db': 'create an agent and add it to the database with litellm params, headers, and rate limits', 'delete_agent_from_db': 'delete an agent from the database by its agent id', 'patch_agent_in_db': 'patch an agent in the database with partial updates to name, params, or permissions', 'update_agent_in_db': 'update an agent in the database with full replacement of name, params, headers, and rate limits', 'get_all_agents_from_db': 'get all agents from the database ordered by creation time descending'}
```

## File: berriai_litellm/litellm/proxy/agent_endpoints/utils.py

Prompts

```
['create an agent and add it to the database with litellm params, headers, and rate limits', 'delete an agent from the database by its agent id', 'patch an agent in the database with partial updates to name, params, or permissions', 'update an agent in the database with full replacement of name, params, headers, and rate limits', 'get all agents from the database ordered by creation time descending', 'build HTTP headers for A2A agent calls by merging dynamic client request headers with static admin-configured headers', 'test the merge_agent_headers function with dynamic and static header mappings', 'refactor merge_agent_headers to support custom merge strategies and key collision handling', 'review the merge_agent_headers function for header precedence and type conversion correctness', 'summarize how merge_agent_headers combines dynamic and static HTTP headers for outbound A2A agent calls']
```

Usage

```
{'build_merge_agent_headers': 'build HTTP headers for A2A agent calls by merging dynamic client request headers with static admin-configured headers', 'test_merge_agent_headers': 'test the merge_agent_headers function with dynamic and static header mappings', 'refactor_merge_agent_headers': 'refactor merge_agent_headers to support custom merge strategies and key collision handling', 'review_merge_agent_headers': 'review the merge_agent_headers function for header precedence and type conversion correctness', 'summarize_merge_agent_headers': 'summarize how merge_agent_headers combines dynamic and static HTTP headers for outbound A2A agent calls'}
```

