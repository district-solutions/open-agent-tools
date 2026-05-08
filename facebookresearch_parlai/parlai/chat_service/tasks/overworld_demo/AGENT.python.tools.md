# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/chat_service/tasks/overworld_demo/worlds.py

Prompts

```
['create a MessengerEchoOnboardWorld subclass of OnboardWorld that sends an intro message then marks the episode done', 'create a MessengerEchoTaskWorld that echoes user input back until the user sends [DONE]', 'create a MessengerOnboardDataOnboardWorld that collects user name and favorite color during onboarding', 'create a MessengerOnboardDataTaskWorld that relays collected onboarding data back to the user', 'create a MessengerOverworld that routes agents to demo worlds like echo, onboard data, or chat via quick replies']
```

Usage

```
{'create_echo_onboard_world': 'create a MessengerEchoOnboardWorld subclass of OnboardWorld that sends an intro message then marks the episode done', 'create_echo_task_world': 'create a MessengerEchoTaskWorld that echoes user input back until the user sends [DONE]', 'create_onboard_data_world': 'create a MessengerOnboardDataOnboardWorld that collects user name and favorite color during onboarding', 'create_onboard_data_task_world': 'create a MessengerOnboardDataTaskWorld that relays collected onboarding data back to the user', 'create_overworld_router': 'create a MessengerOverworld that routes agents to demo worlds like echo, onboard data, or chat via quick replies'}
```

