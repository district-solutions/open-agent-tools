# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/perception/find_agent_action_tool.py

Prompts

```
['initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', "process a high-level action to get summarized history of the other agent's actions", 'retrieve the state history string of the other agent from the environment interface', 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'return the list of argument types required by the FindObjectTool for tool-based LLM planning', 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'get a formatted list of all receptacles grouped by type from the environment world graph', 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process a natural language room query and return the matching room node name', 'get the tool description string from the FindRoomTool skill configuration', 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter']
```

Usage

```
{'init_FindAgentActionTool': 'initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set_environment_FindAgentActionTool': 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set_llm_FindAgentActionTool': 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', 'process_high_level_action_FindAgentActionTool': "process a high-level action to get summarized history of the other agent's actions", 'get_state_history_FindAgentActionTool': 'retrieve the state history string of the other agent from the environment interface'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/perception/find_object_tool.py

Prompts

```
['initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', "process a high-level action to get summarized history of the other agent's actions", 'retrieve the state history string of the other agent from the environment interface', 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'return the list of argument types required by the FindObjectTool for tool-based LLM planning', 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'get a formatted list of all receptacles grouped by type from the environment world graph', 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process a natural language room query and return the matching room node name', 'get the tool description string from the FindRoomTool skill configuration', 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter']
```

Usage

```
{'process_high_level_action': 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get_object_list': 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set_environment': 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set_llm': 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'argument_types': 'return the list of argument types required by the FindObjectTool for tool-based LLM planning'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/perception/find_receptacle_tool.py

Prompts

```
['initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', "process a high-level action to get summarized history of the other agent's actions", 'retrieve the state history string of the other agent from the environment interface', 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'return the list of argument types required by the FindObjectTool for tool-based LLM planning', 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'get a formatted list of all receptacles grouped by type from the environment world graph', 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process a natural language room query and return the matching room node name', 'get the tool description string from the FindRoomTool skill configuration', 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter']
```

Usage

```
{'create_FindReceptacleTool': 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'set_environment': 'set the EnvironmentInterface on a FindReceptacleTool to access the world graph for receptacle lookup', 'set_llm': 'set the BaseLLM on a FindReceptacleTool to enable prompt generation and LLM-based receptacle matching', 'process_high_level_action': 'process a natural language furniture query through the LLM to find the exact Furniture node name', 'get_receptacles_list': 'get a formatted list of all receptacles grouped by type from the environment world graph'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/perception/find_room_tool.py

Prompts

```
['initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', "process a high-level action to get summarized history of the other agent's actions", 'retrieve the state history string of the other agent from the environment interface', 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'return the list of argument types required by the FindObjectTool for tool-based LLM planning', 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'get a formatted list of all receptacles grouped by type from the environment world graph', 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process a natural language room query and return the matching room node name', 'get the tool description string from the FindRoomTool skill configuration', 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter']
```

Usage

```
{'init_FindRoomTool': 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set_environment_FindRoomTool': 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set_llm_FindRoomTool': 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process_high_level_action_FindRoomTool': 'process a natural language room query and return the matching room node name', 'get_description_FindRoomTool': 'get the tool description string from the FindRoomTool skill configuration'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/perception/query_map_tool.py

Prompts

```
['initialize a FindAgentActionTool instance with a skill_config object for multi-agent planning', 'set the EnvironmentInterface on a FindAgentActionTool so it can access agent state history', 'set the BaseLLM on a FindAgentActionTool to enable LLM-based action summarization', "process a high-level action to get summarized history of the other agent's actions", 'retrieve the state history string of the other agent from the environment interface', 'process a natural language query to find the exact object identifier in the world-graph using the LLM', 'get a list of all objects in the world-graph with their distance from the agent and room location', 'set the environment interface on the FindObjectTool instance to access the simulation world-graph', 'set the LLM interface on the FindObjectTool to enable natural language object lookup and prompt generation', 'return the list of argument types required by the FindObjectTool for tool-based LLM planning', 'create a FindReceptacleTool instance with a skill config to find furniture by natural language description', 'get a formatted list of all receptacles grouped by type from the environment world graph', 'initialize a FindRoomTool instance with a skill_config object for room finding', 'set the EnvironmentInterface on FindRoomTool to enable world graph room lookups', 'set the BaseLLM on FindRoomTool to enable natural language room query processing', 'process a natural language room query and return the matching room node name', 'get the tool description string from the FindRoomTool skill configuration', 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter']
```

Usage

```
{'instantiate_QueryMapTool': 'instantiate a QueryMapTool with llm_config and skill_config to initialize the LLM and store the skill configuration', 'set_environment_QueryMapTool': 'call set_environment on a QueryMapTool instance to attach the Habitat environment before querying the map', 'get_description_QueryMapTool': 'access the description property of QueryMapTool to retrieve the skill configuration description string', 'process_high_level_action_QueryMapTool': 'call process_high_level_action on QueryMapTool with a query and observations to query the environment map', 'review_QueryMapTool_bug': 'review the QueryMapTool process_high_level_action method which references undefined variable input instead of query parameter'}
```

