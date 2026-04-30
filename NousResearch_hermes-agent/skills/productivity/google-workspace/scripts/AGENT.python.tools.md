# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/skills/productivity/google-workspace/scripts/_hermes_home.py

Prompts

```
['get the hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'display the hermes home directory as a user-friendly tilde-shortened path string', 'search gmail messages using an IMAP-style query and return message metadata', 'send a gmail message with a recipient, subject, and body as plain text or HTML', 'list calendar events within a date range ordered by start time', 'create a calendar event with a summary, start time, end time, and optional attendees', 'search google drive files by text query and return file metadata', 'run the gws_bridge.py CLI to execute gws commands with an auto-refreshed OAuth access token', 'get a valid Google OAuth access token, refreshing it automatically if expired', 'refresh an expired Google OAuth access token using the stored refresh token and client credentials', 'get the file path to the Google OAuth token JSON file inside the Hermes home directory', 'check if stored Google Workspace OAuth token is valid and print authentication status', 'store a Google OAuth client_secret.json file in the Hermes home directory', 'generate and print a Google OAuth authorization URL for user consent', 'exchange a Google OAuth authorization code for an access token and save it', 'revoke a stored Google OAuth token with Google and delete the local token file']
```

Usage

```
{'get_hermes_home': 'get the hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'display_hermes_home': 'display the hermes home directory as a user-friendly tilde-shortened path string'}
```

## File: NousResearch_hermes-agent/skills/productivity/google-workspace/scripts/google_api.py

Prompts

```
['get the hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'display the hermes home directory as a user-friendly tilde-shortened path string', 'search gmail messages using an IMAP-style query and return message metadata', 'send a gmail message with a recipient, subject, and body as plain text or HTML', 'list calendar events within a date range ordered by start time', 'create a calendar event with a summary, start time, end time, and optional attendees', 'search google drive files by text query and return file metadata', 'run the gws_bridge.py CLI to execute gws commands with an auto-refreshed OAuth access token', 'get a valid Google OAuth access token, refreshing it automatically if expired', 'refresh an expired Google OAuth access token using the stored refresh token and client credentials', 'get the file path to the Google OAuth token JSON file inside the Hermes home directory', 'check if stored Google Workspace OAuth token is valid and print authentication status', 'store a Google OAuth client_secret.json file in the Hermes home directory', 'generate and print a Google OAuth authorization URL for user consent', 'exchange a Google OAuth authorization code for an access token and save it', 'revoke a stored Google OAuth token with Google and delete the local token file']
```

Usage

```
{'search_gmail_messages': 'search gmail messages using an IMAP-style query and return message metadata', 'send_gmail_message': 'send a gmail message with a recipient, subject, and body as plain text or HTML', 'list_calendar_events': 'list calendar events within a date range ordered by start time', 'create_calendar_event': 'create a calendar event with a summary, start time, end time, and optional attendees', 'search_drive_files': 'search google drive files by text query and return file metadata'}
```

## File: NousResearch_hermes-agent/skills/productivity/google-workspace/scripts/gws_bridge.py

Prompts

```
['get the hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'display the hermes home directory as a user-friendly tilde-shortened path string', 'search gmail messages using an IMAP-style query and return message metadata', 'send a gmail message with a recipient, subject, and body as plain text or HTML', 'list calendar events within a date range ordered by start time', 'create a calendar event with a summary, start time, end time, and optional attendees', 'search google drive files by text query and return file metadata', 'run the gws_bridge.py CLI to execute gws commands with an auto-refreshed OAuth access token', 'get a valid Google OAuth access token, refreshing it automatically if expired', 'refresh an expired Google OAuth access token using the stored refresh token and client credentials', 'get the file path to the Google OAuth token JSON file inside the Hermes home directory', 'check if stored Google Workspace OAuth token is valid and print authentication status', 'store a Google OAuth client_secret.json file in the Hermes home directory', 'generate and print a Google OAuth authorization URL for user consent', 'exchange a Google OAuth authorization code for an access token and save it', 'revoke a stored Google OAuth token with Google and delete the local token file']
```

Usage

```
{'run_gws_bridge': 'run the gws_bridge.py CLI to execute gws commands with an auto-refreshed OAuth access token', 'get_valid_token': 'get a valid Google OAuth access token, refreshing it automatically if expired', 'refresh_token': 'refresh an expired Google OAuth access token using the stored refresh token and client credentials', 'get_hermes_home': 'get the Hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'get_token_path': 'get the file path to the Google OAuth token JSON file inside the Hermes home directory'}
```

## File: NousResearch_hermes-agent/skills/productivity/google-workspace/scripts/setup.py

Prompts

```
['get the hermes home directory path from the HERMES_HOME environment variable or default to ~/.hermes', 'display the hermes home directory as a user-friendly tilde-shortened path string', 'search gmail messages using an IMAP-style query and return message metadata', 'send a gmail message with a recipient, subject, and body as plain text or HTML', 'list calendar events within a date range ordered by start time', 'create a calendar event with a summary, start time, end time, and optional attendees', 'search google drive files by text query and return file metadata', 'run the gws_bridge.py CLI to execute gws commands with an auto-refreshed OAuth access token', 'get a valid Google OAuth access token, refreshing it automatically if expired', 'refresh an expired Google OAuth access token using the stored refresh token and client credentials', 'get the file path to the Google OAuth token JSON file inside the Hermes home directory', 'check if stored Google Workspace OAuth token is valid and print authentication status', 'store a Google OAuth client_secret.json file in the Hermes home directory', 'generate and print a Google OAuth authorization URL for user consent', 'exchange a Google OAuth authorization code for an access token and save it', 'revoke a stored Google OAuth token with Google and delete the local token file']
```

Usage

```
{'check_google_workspace_auth': 'check if stored Google Workspace OAuth token is valid and print authentication status', 'store_google_client_secret': 'store a Google OAuth client_secret.json file in the Hermes home directory', 'generate_google_auth_url': 'generate and print a Google OAuth authorization URL for user consent', 'exchange_google_auth_code': 'exchange a Google OAuth authorization code for an access token and save it', 'revoke_google_workspace_token': 'revoke a stored Google OAuth token with Google and delete the local token file'}
```

