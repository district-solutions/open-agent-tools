# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/community/infoquest/infoquest_client.py

Prompts

```
['create an InfoQuestClient instance with custom fetch and search timeout parameters', 'run a web search query using InfoQuestClient and return cleaned JSON results', 'run an image search query using InfoQuestClient and return cleaned image results with URLs', 'fetch and extract readable content from a URL using InfoQuest fetch API', 'review the clean_results method that deduplicates and formats web search results into pages and news items', 'search the web using the web_search_tool with a query string and return results', 'fetch the contents of a web page at a given URL and extract article as markdown', 'search for images online using the image_search_tool with a visual query', 'build an InfoQuestClient with configurable search, fetch, and image search parameters', 'test the web_search_tool by passing a query and verifying string results']
```

Usage

```
{'create_infoquest_client': 'create an InfoQuestClient instance with custom fetch and search timeout parameters', 'run_web_search': 'run a web search query using InfoQuestClient and return cleaned JSON results', 'run_image_search': 'run an image search query using InfoQuestClient and return cleaned image results with URLs', 'fetch_webpage_content': 'fetch and extract readable content from a URL using InfoQuest fetch API', 'review_clean_results': 'review the clean_results method that deduplicates and formats web search results into pages and news items'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/community/infoquest/tools.py

Prompts

```
['create an InfoQuestClient instance with custom fetch and search timeout parameters', 'run a web search query using InfoQuestClient and return cleaned JSON results', 'run an image search query using InfoQuestClient and return cleaned image results with URLs', 'fetch and extract readable content from a URL using InfoQuest fetch API', 'review the clean_results method that deduplicates and formats web search results into pages and news items', 'search the web using the web_search_tool with a query string and return results', 'fetch the contents of a web page at a given URL and extract article as markdown', 'search for images online using the image_search_tool with a visual query', 'build an InfoQuestClient with configurable search, fetch, and image search parameters', 'test the web_search_tool by passing a query and verifying string results']
```

Usage

```
{'search_web_query': 'search the web using the web_search_tool with a query string and return results', 'fetch_webpage_url': 'fetch the contents of a web page at a given URL and extract article as markdown', 'search_images_query': 'search for images online using the image_search_tool with a visual query', 'build_infoquest_client': 'build an InfoQuestClient with configurable search, fetch, and image search parameters', 'test_web_search_tool': 'test the web_search_tool by passing a query and verifying string results'}
```

