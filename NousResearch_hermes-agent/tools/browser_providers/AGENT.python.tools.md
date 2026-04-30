# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tools/browser_providers/base.py

Prompts

```
['create a cloud browser session with task_id and return session metadata including CDP URL', 'close a cloud browser session by its provider session ID and return success status', 'check if the cloud browser provider is configured with all required credentials', 'get the human-readable name of the cloud browser provider implementation', 'perform emergency cleanup of a cloud browser session during process exit', 'create a Browser Use cloud browser session for a given task id with CDP endpoint URL', 'close a Browser Use cloud browser session by sending a stop action to the session', 'check if the Browser Use provider is configured with a valid API key or managed gateway', 'get the provider name string for the Browser Use cloud browser backend', 'emergency cleanup a Browser Use session by force-stopping it when normal close fails', 'create a Browserbase cloud browser session with task_id, proxies, stealth, and keep_alive features', 'close a Browserbase cloud browser session by session_id using REQUEST_RELEASE status', 'emergency cleanup a Browserbase session by session_id when normal closure fails', 'test whether the BrowserbaseProvider is configured with required API key and project ID environment variables', 'review the BrowserbaseProvider class and its session lifecycle methods for cloud browser management', 'create a Firecrawl browser session with a task id and return session name, session id, and cdp url', 'close a Firecrawl browser session by session id and return success status', 'emergency cleanup a Firecrawl browser session by session id without returning a result', 'check if Firecrawl provider is configured by verifying the FIRECRAWL_API_KEY environment variable', 'get the Firecrawl provider name string from the provider_name method']
```

Usage

```
{'create_browser_session': 'create a cloud browser session with task_id and return session metadata including CDP URL', 'close_browser_session': 'close a cloud browser session by its provider session ID and return success status', 'check_browser_configured': 'check if the cloud browser provider is configured with all required credentials', 'get_provider_name': 'get the human-readable name of the cloud browser provider implementation', 'emergency_cleanup_browser': 'perform emergency cleanup of a cloud browser session during process exit'}
```

## File: NousResearch_hermes-agent/tools/browser_providers/browser_use.py

Prompts

```
['create a cloud browser session with task_id and return session metadata including CDP URL', 'close a cloud browser session by its provider session ID and return success status', 'check if the cloud browser provider is configured with all required credentials', 'get the human-readable name of the cloud browser provider implementation', 'perform emergency cleanup of a cloud browser session during process exit', 'create a Browser Use cloud browser session for a given task id with CDP endpoint URL', 'close a Browser Use cloud browser session by sending a stop action to the session', 'check if the Browser Use provider is configured with a valid API key or managed gateway', 'get the provider name string for the Browser Use cloud browser backend', 'emergency cleanup a Browser Use session by force-stopping it when normal close fails', 'create a Browserbase cloud browser session with task_id, proxies, stealth, and keep_alive features', 'close a Browserbase cloud browser session by session_id using REQUEST_RELEASE status', 'emergency cleanup a Browserbase session by session_id when normal closure fails', 'test whether the BrowserbaseProvider is configured with required API key and project ID environment variables', 'review the BrowserbaseProvider class and its session lifecycle methods for cloud browser management', 'create a Firecrawl browser session with a task id and return session name, session id, and cdp url', 'close a Firecrawl browser session by session id and return success status', 'emergency cleanup a Firecrawl browser session by session id without returning a result', 'check if Firecrawl provider is configured by verifying the FIRECRAWL_API_KEY environment variable', 'get the Firecrawl provider name string from the provider_name method']
```

Usage

```
{'create_browser_use_session': 'create a Browser Use cloud browser session for a given task id with CDP endpoint URL', 'close_browser_use_session': 'close a Browser Use cloud browser session by sending a stop action to the session', 'check_browser_use_configured': 'check if the Browser Use provider is configured with a valid API key or managed gateway', 'get_browser_use_provider_name': 'get the provider name string for the Browser Use cloud browser backend', 'emergency_cleanup_browser_use_session': 'emergency cleanup a Browser Use session by force-stopping it when normal close fails'}
```

## File: NousResearch_hermes-agent/tools/browser_providers/browserbase.py

Prompts

```
['create a cloud browser session with task_id and return session metadata including CDP URL', 'close a cloud browser session by its provider session ID and return success status', 'check if the cloud browser provider is configured with all required credentials', 'get the human-readable name of the cloud browser provider implementation', 'perform emergency cleanup of a cloud browser session during process exit', 'create a Browser Use cloud browser session for a given task id with CDP endpoint URL', 'close a Browser Use cloud browser session by sending a stop action to the session', 'check if the Browser Use provider is configured with a valid API key or managed gateway', 'get the provider name string for the Browser Use cloud browser backend', 'emergency cleanup a Browser Use session by force-stopping it when normal close fails', 'create a Browserbase cloud browser session with task_id, proxies, stealth, and keep_alive features', 'close a Browserbase cloud browser session by session_id using REQUEST_RELEASE status', 'emergency cleanup a Browserbase session by session_id when normal closure fails', 'test whether the BrowserbaseProvider is configured with required API key and project ID environment variables', 'review the BrowserbaseProvider class and its session lifecycle methods for cloud browser management', 'create a Firecrawl browser session with a task id and return session name, session id, and cdp url', 'close a Firecrawl browser session by session id and return success status', 'emergency cleanup a Firecrawl browser session by session id without returning a result', 'check if Firecrawl provider is configured by verifying the FIRECRAWL_API_KEY environment variable', 'get the Firecrawl provider name string from the provider_name method']
```

Usage

```
{'create_session_browserbase': 'create a Browserbase cloud browser session with task_id, proxies, stealth, and keep_alive features', 'close_session_browserbase': 'close a Browserbase cloud browser session by session_id using REQUEST_RELEASE status', 'emergency_cleanup_browserbase': 'emergency cleanup a Browserbase session by session_id when normal closure fails', 'test_is_configured_browserbase': 'test whether the BrowserbaseProvider is configured with required API key and project ID environment variables', 'review_browserbase_provider': 'review the BrowserbaseProvider class and its session lifecycle methods for cloud browser management'}
```

## File: NousResearch_hermes-agent/tools/browser_providers/firecrawl.py

Prompts

```
['create a cloud browser session with task_id and return session metadata including CDP URL', 'close a cloud browser session by its provider session ID and return success status', 'check if the cloud browser provider is configured with all required credentials', 'get the human-readable name of the cloud browser provider implementation', 'perform emergency cleanup of a cloud browser session during process exit', 'create a Browser Use cloud browser session for a given task id with CDP endpoint URL', 'close a Browser Use cloud browser session by sending a stop action to the session', 'check if the Browser Use provider is configured with a valid API key or managed gateway', 'get the provider name string for the Browser Use cloud browser backend', 'emergency cleanup a Browser Use session by force-stopping it when normal close fails', 'create a Browserbase cloud browser session with task_id, proxies, stealth, and keep_alive features', 'close a Browserbase cloud browser session by session_id using REQUEST_RELEASE status', 'emergency cleanup a Browserbase session by session_id when normal closure fails', 'test whether the BrowserbaseProvider is configured with required API key and project ID environment variables', 'review the BrowserbaseProvider class and its session lifecycle methods for cloud browser management', 'create a Firecrawl browser session with a task id and return session name, session id, and cdp url', 'close a Firecrawl browser session by session id and return success status', 'emergency cleanup a Firecrawl browser session by session id without returning a result', 'check if Firecrawl provider is configured by verifying the FIRECRAWL_API_KEY environment variable', 'get the Firecrawl provider name string from the provider_name method']
```

Usage

```
{'create_FirecrawlProvider_session': 'create a Firecrawl browser session with a task id and return session name, session id, and cdp url', 'close_FirecrawlProvider_session': 'close a Firecrawl browser session by session id and return success status', 'emergency_cleanup_FirecrawlProvider_session': 'emergency cleanup a Firecrawl browser session by session id without returning a result', 'check_FirecrawlProvider_is_configured': 'check if Firecrawl provider is configured by verifying the FIRECRAWL_API_KEY environment variable', 'get_FirecrawlProvider_name': 'get the Firecrawl provider name string from the provider_name method'}
```

