# Agent Python Tools

- repo: lsdefine/GenericAgent
- repo_uri: https://github.com/lsdefine/GenericAgent

## File: lsdefine_GenericAgent/memory/skill_search/skill_search/__main__.py

Prompts

```
["run skill_search CLI to search for skills matching a query string like 'python testing'", 'run skill_search CLI with --json flag to get structured JSON output of search results', 'run skill_search CLI with --category flag to limit results to a specific skill category', 'run skill_search CLI with --env flag to detect and display the current environment info', 'run skill_search CLI with --stats flag to display index statistics and category distribution', 'search for skills using a query string with optional category filter and top_k limit', 'detect the current OS, shell, available runtimes and tools for skill matching', 'retrieve skill index statistics filtered by the current or provided environment', 'create a SkillIndex dataclass instance with metadata like name, category, tags, and quality scores', 'create a SearchResult dataclass instance wrapping a SkillIndex with relevance and quality scores']
```

Usage

```
{'run_skill_search_query': "run skill_search CLI to search for skills matching a query string like 'python testing'", 'run_skill_search_json_output': 'run skill_search CLI with --json flag to get structured JSON output of search results', 'run_skill_search_category_filter': 'run skill_search CLI with --category flag to limit results to a specific skill category', 'run_skill_search_env_detect': 'run skill_search CLI with --env flag to detect and display the current environment info', 'run_skill_search_stats': 'run skill_search CLI with --stats flag to display index statistics and category distribution'}
```

## File: lsdefine_GenericAgent/memory/skill_search/skill_search/engine.py

Prompts

```
["run skill_search CLI to search for skills matching a query string like 'python testing'", 'run skill_search CLI with --json flag to get structured JSON output of search results', 'run skill_search CLI with --category flag to limit results to a specific skill category', 'run skill_search CLI with --env flag to detect and display the current environment info', 'run skill_search CLI with --stats flag to display index statistics and category distribution', 'search for skills using a query string with optional category filter and top_k limit', 'detect the current OS, shell, available runtimes and tools for skill matching', 'retrieve skill index statistics filtered by the current or provided environment', 'create a SkillIndex dataclass instance with metadata like name, category, tags, and quality scores', 'create a SearchResult dataclass instance wrapping a SkillIndex with relevance and quality scores']
```

Usage

```
{'search_skill_search': 'search for skills using a query string with optional category filter and top_k limit', 'detect_environment': 'detect the current OS, shell, available runtimes and tools for skill matching', 'get_stats': 'retrieve skill index statistics filtered by the current or provided environment', 'create_SkillIndex': 'create a SkillIndex dataclass instance with metadata like name, category, tags, and quality scores', 'create_SearchResult': 'create a SearchResult dataclass instance wrapping a SkillIndex with relevance and quality scores'}
```

