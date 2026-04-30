# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/e2e/conftest.py

Prompts

```
['test the gateway e2e message flow by sending events through adapter.handle_message and capturing send() calls', 'create mock telegram modules so TelegramAdapter can be imported without the real library installed', 'create mock discord modules so DiscordAdapter can be imported without the real library installed', 'create mock slack modules so SlackAdapter can be imported without the real library installed', 'build a GatewayRunner with mocked internals for e2e testing, skipping __init__ to avoid filesystem and network side effects']
```

Usage

```
{'test_gateway_e2e_flow': 'test the gateway e2e message flow by sending events through adapter.handle_message and capturing send() calls', 'create_mock_telegram_modules': 'create mock telegram modules so TelegramAdapter can be imported without the real library installed', 'create_mock_discord_modules': 'create mock discord modules so DiscordAdapter can be imported without the real library installed', 'create_mock_slack_modules': 'create mock slack modules so SlackAdapter can be imported without the real library installed', 'build_gateway_runner': 'build a GatewayRunner with mocked internals for e2e testing, skipping __init__ to avoid filesystem and network side effects'}
```

