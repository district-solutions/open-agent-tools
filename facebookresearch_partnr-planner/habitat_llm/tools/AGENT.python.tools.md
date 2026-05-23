# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/prompts.py

Prompts

```
['get a Prompt instance by type string such as FRT_CG or FindRoomPrompt using get_prompt', 'create a FindRoomPrompt that matches a natural language query to rooms from a given room list', 'build a zero-shot receptacle finding prompt that matches a target receptacle query against a house receptacle list', 'create a few-shot furniture retrieval prompt that matches furniture queries against a list of receptacles with room context', 'build a few-shot object finding prompt that matches object queries against a list of objects with location and distance info', 'create a subclass of Tool that implements description, process_high_level_action, and argument_types', 'create a subclass of PerceptionTool that implements description and process_high_level_action for environment perception', 'define the grammar string for a Tool using its name and argument_types list', 'compare two Tool instances for equality using their name and agent_uid attributes', "get a state description string from a PerceptionTool showing the agent's current room"]
```

Usage

```
{'get_prompt_factory': 'get a Prompt instance by type string such as FRT_CG or FindRoomPrompt using get_prompt', 'find_room_prompt': 'create a FindRoomPrompt that matches a natural language query to rooms from a given room list', 'FRT_CG_Prompt': 'build a zero-shot receptacle finding prompt that matches a target receptacle query against a house receptacle list', 'FRT_FEW_SHOT_Prompt': 'create a few-shot furniture retrieval prompt that matches furniture queries against a list of receptacles with room context', 'FOT_FEW_SHOT_Prompt': 'build a few-shot object finding prompt that matches object queries against a list of objects with location and distance info'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/tool.py

Prompts

```
['get a Prompt instance by type string such as FRT_CG or FindRoomPrompt using get_prompt', 'create a FindRoomPrompt that matches a natural language query to rooms from a given room list', 'build a zero-shot receptacle finding prompt that matches a target receptacle query against a house receptacle list', 'create a few-shot furniture retrieval prompt that matches furniture queries against a list of receptacles with room context', 'build a few-shot object finding prompt that matches object queries against a list of objects with location and distance info', 'create a subclass of Tool that implements description, process_high_level_action, and argument_types', 'create a subclass of PerceptionTool that implements description and process_high_level_action for environment perception', 'define the grammar string for a Tool using its name and argument_types list', 'compare two Tool instances for equality using their name and agent_uid attributes', "get a state description string from a PerceptionTool showing the agent's current room"]
```

Usage

```
{'create_tool_subclass': 'create a subclass of Tool that implements description, process_high_level_action, and argument_types', 'create_perception_tool_subclass': 'create a subclass of PerceptionTool that implements description and process_high_level_action for environment perception', 'define_tool_grammar': 'define the grammar string for a Tool using its name and argument_types list', 'compare_tools': 'compare two Tool instances for equality using their name and agent_uid attributes', 'get_state_description': "get a state description string from a PerceptionTool showing the agent's current room"}
```

