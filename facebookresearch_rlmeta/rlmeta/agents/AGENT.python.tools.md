# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/agents/agent.py

Prompts

```
['implement a subclass of Agent that overrides async_act, async_observe_init, async_observe, and async_update methods', 'call the act method on an Agent instance to get an Action from a TimeStep', 'call observe on an Agent instance with an Action and next TimeStep to record the transition', 'create an AgentFactory with an Agent class and call it with an index to produce a uniquely named Agent instance', 'call connect on an Agent instance to establish connections for all Remote objects attached to the agent']
```

Usage

```
{'implement_agent_subclass': 'implement a subclass of Agent that overrides async_act, async_observe_init, async_observe, and async_update methods', 'use_agent_act': 'call the act method on an Agent instance to get an Action from a TimeStep', 'use_agent_observe': 'call observe on an Agent instance with an Action and next TimeStep to record the transition', 'use_agent_factory': 'create an AgentFactory with an Agent class and call it with an index to produce a uniquely named Agent instance', 'use_agent_connect': 'call connect on an Agent instance to establish connections for all Remote objects attached to the agent'}
```

