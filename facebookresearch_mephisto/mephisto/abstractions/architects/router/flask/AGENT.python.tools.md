# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/router/flask/mephisto_flask_blueprint.py

Prompts

```
['register a MephistoRouter application with global state so HTTP requests and websockets share the same router state', 'make a synchronous request to the Mephisto core server via websocket and await the response with a 30 second timeout', 'handle incoming websocket messages by routing packets like alive, heartbeat, status updates, and agent details to the correct handler', 'submit onboarding data for an agent via the POST /submit_onboarding endpoint and forward it to the Mephisto core server', 'submit task completion data and uploaded files via the POST /submit_task endpoint and forward the unit submission packet']
```

Usage

```
{'register_mephisto_router': 'register a MephistoRouter application with global state so HTTP requests and websockets share the same router state', 'make_agent_request': 'make a synchronous request to the Mephisto core server via websocket and await the response with a 30 second timeout', 'handle_websocket_message': 'handle incoming websocket messages by routing packets like alive, heartbeat, status updates, and agent details to the correct handler', 'submit_onboarding': 'submit onboarding data for an agent via the POST /submit_onboarding endpoint and forward it to the Mephisto core server', 'submit_task': 'submit task completion data and uploaded files via the POST /submit_task endpoint and forward the unit submission packet'}
```

