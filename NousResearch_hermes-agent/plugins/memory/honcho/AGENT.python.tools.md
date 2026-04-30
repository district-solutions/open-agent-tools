# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/plugins/memory/honcho/cli.py

Prompts

```
['run the interactive Honcho setup wizard to configure API key, deployment mode, and peer identities', 'run the honcho status command to show current config, connection status, and peer data', 'run the honcho sync command to clone Honcho config to all existing Hermes profiles', 'run the honcho identity command to seed AI peer identity from a SOUL.md file or show current representation', 'run the honcho migrate command to step through migrating OpenClaw native memory files to Honcho', 'create a HonchoClientConfig from environment variables with a custom workspace ID and host', 'build a HonchoClientConfig from a JSON config file with host-specific overrides', 'test the HonchoClientConfig resolution by loading from config path and environment fallback', 'get or create a singleton Honcho client instance from a config object', 'resolve a Honcho session name from working directory, session title, and session strategy', 'create a HonchoSessionManager and get_or_create a conversation session by key for user modeling', 'save messages to Honcho with async, turn, session, or N-turn write frequency modes', "query Honcho's dialectic endpoint about a peer with configurable reasoning level", 'migrate local session history to Honcho as an XML transcript file for cross-session context', 'perform semantic search over Honcho session context and return relevant excerpts']
```

Usage

```
{'run_honcho_setup': 'run the interactive Honcho setup wizard to configure API key, deployment mode, and peer identities', 'run_honcho_status': 'run the honcho status command to show current config, connection status, and peer data', 'run_honcho_sync': 'run the honcho sync command to clone Honcho config to all existing Hermes profiles', 'run_honcho_identity': 'run the honcho identity command to seed AI peer identity from a SOUL.md file or show current representation', 'run_honcho_migrate': 'run the honcho migrate command to step through migrating OpenClaw native memory files to Honcho'}
```

## File: NousResearch_hermes-agent/plugins/memory/honcho/client.py

Prompts

```
['run the interactive Honcho setup wizard to configure API key, deployment mode, and peer identities', 'run the honcho status command to show current config, connection status, and peer data', 'run the honcho sync command to clone Honcho config to all existing Hermes profiles', 'run the honcho identity command to seed AI peer identity from a SOUL.md file or show current representation', 'run the honcho migrate command to step through migrating OpenClaw native memory files to Honcho', 'create a HonchoClientConfig from environment variables with a custom workspace ID and host', 'build a HonchoClientConfig from a JSON config file with host-specific overrides', 'test the HonchoClientConfig resolution by loading from config path and environment fallback', 'get or create a singleton Honcho client instance from a config object', 'resolve a Honcho session name from working directory, session title, and session strategy', 'create a HonchoSessionManager and get_or_create a conversation session by key for user modeling', 'save messages to Honcho with async, turn, session, or N-turn write frequency modes', "query Honcho's dialectic endpoint about a peer with configurable reasoning level", 'migrate local session history to Honcho as an XML transcript file for cross-session context', 'perform semantic search over Honcho session context and return relevant excerpts']
```

Usage

```
{'create_honcho_client_config': 'create a HonchoClientConfig from environment variables with a custom workspace ID and host', 'build_honcho_client_from_config': 'build a HonchoClientConfig from a JSON config file with host-specific overrides', 'test_honcho_client_config': 'test the HonchoClientConfig resolution by loading from config path and environment fallback', 'get_honcho_client_instance': 'get or create a singleton Honcho client instance from a config object', 'resolve_honcho_session_name': 'resolve a Honcho session name from working directory, session title, and session strategy'}
```

## File: NousResearch_hermes-agent/plugins/memory/honcho/session.py

Prompts

```
['run the interactive Honcho setup wizard to configure API key, deployment mode, and peer identities', 'run the honcho status command to show current config, connection status, and peer data', 'run the honcho sync command to clone Honcho config to all existing Hermes profiles', 'run the honcho identity command to seed AI peer identity from a SOUL.md file or show current representation', 'run the honcho migrate command to step through migrating OpenClaw native memory files to Honcho', 'create a HonchoClientConfig from environment variables with a custom workspace ID and host', 'build a HonchoClientConfig from a JSON config file with host-specific overrides', 'test the HonchoClientConfig resolution by loading from config path and environment fallback', 'get or create a singleton Honcho client instance from a config object', 'resolve a Honcho session name from working directory, session title, and session strategy', 'create a HonchoSessionManager and get_or_create a conversation session by key for user modeling', 'save messages to Honcho with async, turn, session, or N-turn write frequency modes', "query Honcho's dialectic endpoint about a peer with configurable reasoning level", 'migrate local session history to Honcho as an XML transcript file for cross-session context', 'perform semantic search over Honcho session context and return relevant excerpts']
```

Usage

```
{'create_honcho_session': 'create a HonchoSessionManager and get_or_create a conversation session by key for user modeling', 'save_honcho_session': 'save messages to Honcho with async, turn, session, or N-turn write frequency modes', 'query_dialectic': "query Honcho's dialectic endpoint about a peer with configurable reasoning level", 'migrate_local_history': 'migrate local session history to Honcho as an XML transcript file for cross-session context', 'search_context': 'perform semantic search over Honcho session context and return relevant excerpts'}
```

