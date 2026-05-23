# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/agent/agent.py

Prompts

```
['create an Agent instance with a uid, config, and optional environment interface', 'reset the Agent state variables and skill hidden states for a new episode', 'process a high level action like Pick or Place to generate low level control commands', "get a Tool instance by name from the Agent's registered tools dictionary", 'pass a shared LLM instance to all Agent tools that require one']
```

Usage

```
{'create_agent_instance': 'create an Agent instance with a uid, config, and optional environment interface', 'reset_agent_state': 'reset the Agent state variables and skill hidden states for a new episode', 'process_high_level_action': 'process a high level action like Pick or Place to generate low level control commands', 'get_tool_from_name': "get a Tool instance by name from the Agent's registered tools dictionary", 'pass_llm_to_tools': 'pass a shared LLM instance to all Agent tools that require one'}
```

