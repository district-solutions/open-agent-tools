# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/community/tavily/tools.py

Prompts

```
['search the web using the web_search_tool with a query string and return normalized JSON results', 'fetch the contents of a web page at a given URL using the web_fetch_tool and return title and raw content', 'get a configured TavilyClient instance from app config for use with web search and fetch tools', 'configure the web_search tool with a custom max_results value from app config', 'handle failed web_fetch results and return error messages or truncated content up to 4096 characters']
```

Usage

```
{'search_web': 'search the web using the web_search_tool with a query string and return normalized JSON results', 'fetch_webpage': 'fetch the contents of a web page at a given URL using the web_fetch_tool and return title and raw content', 'get_tavily_client': 'get a configured TavilyClient instance from app config for use with web search and fetch tools', 'configure_web_search': 'configure the web_search tool with a custom max_results value from app config', 'handle_fetch_errors': 'handle failed web_fetch results and return error messages or truncated content up to 4096 characters'}
```

