# Agent Python Tools

- repo: open-webui/pipelines
- repo_uri: https://github.com/open-webui/pipelines

## File: open-webui_pipelines/utils/pipelines/auth.py

Prompts

```
['create a JWT token from a data dict with optional expiration delta using HS256 algorithm', 'decode a JWT token string and return the payload dict or None on failure', 'verify a plain password against a bcrypt hashed password using passlib', 'generate a bcrypt hash from a plain password using passlib CryptContext', 'extract and validate the current user token from FastAPI Bearer auth header', 'build an OpenAI-style streaming chat completion chunk with model id and content delta', 'create a function that extracts the last user message text from a list of chat messages', 'build OpenAI function-calling tool specs from a Python object with callable methods and docstrings', 'add or prepend a system message to the beginning of a chat message list', 'pop the system message from a chat message list and return it separately', 'convert a GitHub blob URL to its raw.githubusercontent.com equivalent', 'test the convert_to_raw_url function with a sample GitHub URL', 'refactor convert_to_raw_url to also handle GitHub gist URLs', 'summarize the convert_to_raw_url function and its URL transformation logic', 'review the convert_to_raw_url function for edge cases and error handling']
```

Usage

```
{'create_token': 'create a JWT token from a data dict with optional expiration delta using HS256 algorithm', 'decode_token': 'decode a JWT token string and return the payload dict or None on failure', 'verify_password': 'verify a plain password against a bcrypt hashed password using passlib', 'get_password_hash': 'generate a bcrypt hash from a plain password using passlib CryptContext', 'get_current_user': 'extract and validate the current user token from FastAPI Bearer auth header'}
```

## File: open-webui_pipelines/utils/pipelines/main.py

Prompts

```
['create a JWT token from a data dict with optional expiration delta using HS256 algorithm', 'decode a JWT token string and return the payload dict or None on failure', 'verify a plain password against a bcrypt hashed password using passlib', 'generate a bcrypt hash from a plain password using passlib CryptContext', 'extract and validate the current user token from FastAPI Bearer auth header', 'build an OpenAI-style streaming chat completion chunk with model id and content delta', 'create a function that extracts the last user message text from a list of chat messages', 'build OpenAI function-calling tool specs from a Python object with callable methods and docstrings', 'add or prepend a system message to the beginning of a chat message list', 'pop the system message from a chat message list and return it separately', 'convert a GitHub blob URL to its raw.githubusercontent.com equivalent', 'test the convert_to_raw_url function with a sample GitHub URL', 'refactor convert_to_raw_url to also handle GitHub gist URLs', 'summarize the convert_to_raw_url function and its URL transformation logic', 'review the convert_to_raw_url function for edge cases and error handling']
```

Usage

```
{'build_stream_message_template': 'build an OpenAI-style streaming chat completion chunk with model id and content delta', 'create_get_last_user_message': 'create a function that extracts the last user message text from a list of chat messages', 'build_get_tools_specs': 'build OpenAI function-calling tool specs from a Python object with callable methods and docstrings', 'add_or_update_system_message': 'add or prepend a system message to the beginning of a chat message list', 'pop_system_message': 'pop the system message from a chat message list and return it separately'}
```

## File: open-webui_pipelines/utils/pipelines/misc.py

Prompts

```
['create a JWT token from a data dict with optional expiration delta using HS256 algorithm', 'decode a JWT token string and return the payload dict or None on failure', 'verify a plain password against a bcrypt hashed password using passlib', 'generate a bcrypt hash from a plain password using passlib CryptContext', 'extract and validate the current user token from FastAPI Bearer auth header', 'build an OpenAI-style streaming chat completion chunk with model id and content delta', 'create a function that extracts the last user message text from a list of chat messages', 'build OpenAI function-calling tool specs from a Python object with callable methods and docstrings', 'add or prepend a system message to the beginning of a chat message list', 'pop the system message from a chat message list and return it separately', 'convert a GitHub blob URL to its raw.githubusercontent.com equivalent', 'test the convert_to_raw_url function with a sample GitHub URL', 'refactor convert_to_raw_url to also handle GitHub gist URLs', 'summarize the convert_to_raw_url function and its URL transformation logic', 'review the convert_to_raw_url function for edge cases and error handling']
```

Usage

```
{'convert_to_raw_url_github_url': 'convert a GitHub blob URL to its raw.githubusercontent.com equivalent', 'test_convert_to_raw_url': 'test the convert_to_raw_url function with a sample GitHub URL', 'refactor_convert_to_raw_url': 'refactor convert_to_raw_url to also handle GitHub gist URLs', 'summarize_convert_to_raw_url': 'summarize the convert_to_raw_url function and its URL transformation logic', 'review_convert_to_raw_url': 'review the convert_to_raw_url function for edge cases and error handling'}
```

