# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/chat_service/services/browser_chat/client.py

Prompts

```
['run the browser chat client websocket server on a configurable port and host', 'create a BrowserHandler HTTP request handler class to serve chat pages and handle POST interactions', 'set up command-line arguments for the browser chat client including port, host, and serving port', 'handle incoming websocket messages and relay them through the message_available threading event', 'send a reset signal via POST to the /reset endpoint to clear the current chat session', 'run the browser chat server on a specified port using the BrowserManager', 'set up command line arguments for the browser chat server including port and config path', 'run the BrowserManager with given options, starting its task and ensuring shutdown', 'parse a configuration file and merge world options into the browser chat server options', 'review the browser chat runner entry point that sets up args and starts the server']
```

Usage

```
{'run_browser_chat_client': 'run the browser chat client websocket server on a configurable port and host', 'setup_browser_handler': 'create a BrowserHandler HTTP request handler class to serve chat pages and handle POST interactions', 'configure_browser_chat_args': 'set up command-line arguments for the browser chat client including port, host, and serving port', 'handle_interactive_messages': 'handle incoming websocket messages and relay them through the message_available threading event', 'reset_chat_session': 'send a reset signal via POST to the /reset endpoint to clear the current chat session'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/browser_chat/run.py

Prompts

```
['run the browser chat client websocket server on a configurable port and host', 'create a BrowserHandler HTTP request handler class to serve chat pages and handle POST interactions', 'set up command-line arguments for the browser chat client including port, host, and serving port', 'handle incoming websocket messages and relay them through the message_available threading event', 'send a reset signal via POST to the /reset endpoint to clear the current chat session', 'run the browser chat server on a specified port using the BrowserManager', 'set up command line arguments for the browser chat server including port and config path', 'run the BrowserManager with given options, starting its task and ensuring shutdown', 'parse a configuration file and merge world options into the browser chat server options', 'review the browser chat runner entry point that sets up args and starts the server']
```

Usage

```
{'run_browser_chat_server': 'run the browser chat server on a specified port using the BrowserManager', 'setup_browser_chat_args': 'set up command line arguments for the browser chat server including port and config path', 'run_browser_manager': 'run the BrowserManager with given options, starting its task and ensuring shutdown', 'parse_browser_chat_config': 'parse a configuration file and merge world options into the browser chat server options', 'review_browser_chat_entry': 'review the browser chat runner entry point that sets up args and starts the server'}
```

