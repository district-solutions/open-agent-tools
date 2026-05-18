# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/agents/default_agent/tools/action_executor.py

Prompts

```
['extract an AgentAction from LLM output by splitting on a designated token', 'parse an AgentAction into a ParsedAction with tool name and arguments', 'execute a ParsedAction and log the result using append_agent_log and make_timestamp', 'append a FinalAnswerLog entry with observation content and attachments to the agent log', 'create an AgentAction dataclass instance with a rationale string and optional action', 'parse a JSON blob string into a dictionary by extracting content between the first and last braces', 'parse a JSON blob string to extract the action name and action_input arguments for tool execution', 'create an ObservationLog object with timestamp, content, agent_id, and optional attachments for agent logging', 'execute an AgentAction by parsing it, running the tool call, and logging rationale, tool call, and observation', 'update the tools dictionary on a JsonActionExecutor instance to swap available tools at runtime']
```

Usage

```
{'extract_action_from_llm_output': 'extract an AgentAction from LLM output by splitting on a designated token', 'parse_action_into_parsed_action': 'parse an AgentAction into a ParsedAction with tool name and arguments', 'execute_parsed_action_with_logging': 'execute a ParsedAction and log the result using append_agent_log and make_timestamp', 'append_final_answer_to_log': 'append a FinalAnswerLog entry with observation content and attachments to the agent log', 'create_agent_action_dataclass': 'create an AgentAction dataclass instance with a rationale string and optional action'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/agents/default_agent/tools/json_action_executor.py

Prompts

```
['extract an AgentAction from LLM output by splitting on a designated token', 'parse an AgentAction into a ParsedAction with tool name and arguments', 'execute a ParsedAction and log the result using append_agent_log and make_timestamp', 'append a FinalAnswerLog entry with observation content and attachments to the agent log', 'create an AgentAction dataclass instance with a rationale string and optional action', 'parse a JSON blob string into a dictionary by extracting content between the first and last braces', 'parse a JSON blob string to extract the action name and action_input arguments for tool execution', 'create an ObservationLog object with timestamp, content, agent_id, and optional attachments for agent logging', 'execute an AgentAction by parsing it, running the tool call, and logging rationale, tool call, and observation', 'update the tools dictionary on a JsonActionExecutor instance to swap available tools at runtime']
```

Usage

```
{'parse_json_blob': 'parse a JSON blob string into a dictionary by extracting content between the first and last braces', 'parse_json_tool_call': 'parse a JSON blob string to extract the action name and action_input arguments for tool execution', 'get_observation_log': 'create an ObservationLog object with timestamp, content, agent_id, and optional attachments for agent logging', 'JsonActionExecutor_execute_action': 'execute an AgentAction by parsing it, running the tool call, and logging rationale, tool call, and observation', 'JsonActionExecutor_update_tools': 'update the tools dictionary on a JsonActionExecutor instance to swap available tools at runtime'}
```

