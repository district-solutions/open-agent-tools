# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/generate_data/action_node.py

Prompts

```
['generate an ActionNode instance with ARG_TYPES or CHOICES using the generate class method', 'generate the natural language description for an ActionNode using the generate_description method', 'convert an ActionNode and its children into a recursive action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new action types or dialogue types', 'generate a GetMemory action node from a template with filter arguments for dialogue generation', 'generate a PutMemory action node from a template with upsert and filter arguments for dialogue generation', 'generate text descriptions from a GetMemory action node template objects for natural language output', 'generate text descriptions from a PutMemory action node template objects for natural language output', 'review the GetMemory class to understand how filters, block objects, and location arguments are configured', 'generate a Move action object with optional location, stop condition, and repeat arguments', 'generate a Build action object with optional schematic, location, and repeat arguments', 'generate a Destroy action object with an optional BlockObject to destroy', 'generate a Spawn action object that spawns a Mob with optional repeat arguments', 'generate a Noop action object for non-action chat messages like greetings']
```

Usage

```
{'generate_action_node': 'generate an ActionNode instance with ARG_TYPES or CHOICES using the generate class method', 'generate_description_action_node': 'generate the natural language description for an ActionNode using the generate_description method', 'to_dict_action_tree': 'convert an ActionNode and its children into a recursive action dictionary using to_dict', 'review_action_node_class': 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor_action_node_to_dict': 'refactor the ActionNode to_dict method to handle new action types or dialogue types'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/generate_data/human_bot_dialogue.py

Prompts

```
['generate an ActionNode instance with ARG_TYPES or CHOICES using the generate class method', 'generate the natural language description for an ActionNode using the generate_description method', 'convert an ActionNode and its children into a recursive action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new action types or dialogue types', 'generate a GetMemory action node from a template with filter arguments for dialogue generation', 'generate a PutMemory action node from a template with upsert and filter arguments for dialogue generation', 'generate text descriptions from a GetMemory action node template objects for natural language output', 'generate text descriptions from a PutMemory action node template objects for natural language output', 'review the GetMemory class to understand how filters, block objects, and location arguments are configured', 'generate a Move action object with optional location, stop condition, and repeat arguments', 'generate a Build action object with optional schematic, location, and repeat arguments', 'generate a Destroy action object with an optional BlockObject to destroy', 'generate a Spawn action object that spawns a Mob with optional repeat arguments', 'generate a Noop action object for non-action chat messages like greetings']
```

Usage

```
{'generate_get_memory_action': 'generate a GetMemory action node from a template with filter arguments for dialogue generation', 'generate_put_memory_action': 'generate a PutMemory action node from a template with upsert and filter arguments for dialogue generation', 'get_memory_generate_description': 'generate text descriptions from a GetMemory action node template objects for natural language output', 'put_memory_generate_description': 'generate text descriptions from a PutMemory action node template objects for natural language output', 'review_get_memory_class': 'review the GetMemory class to understand how filters, block objects, and location arguments are configured'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/generate_data/human_human_dialogue.py

Prompts

```
['generate an ActionNode instance with ARG_TYPES or CHOICES using the generate class method', 'generate the natural language description for an ActionNode using the generate_description method', 'convert an ActionNode and its children into a recursive action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new action types or dialogue types', 'generate a GetMemory action node from a template with filter arguments for dialogue generation', 'generate a PutMemory action node from a template with upsert and filter arguments for dialogue generation', 'generate text descriptions from a GetMemory action node template objects for natural language output', 'generate text descriptions from a PutMemory action node template objects for natural language output', 'review the GetMemory class to understand how filters, block objects, and location arguments are configured', 'generate a Move action object with optional location, stop condition, and repeat arguments', 'generate a Build action object with optional schematic, location, and repeat arguments', 'generate a Destroy action object with an optional BlockObject to destroy', 'generate a Spawn action object that spawns a Mob with optional repeat arguments', 'generate a Noop action object for non-action chat messages like greetings']
```

Usage

```
{'generate_Move_action': 'generate a Move action object with optional location, stop condition, and repeat arguments', 'generate_Build_action': 'generate a Build action object with optional schematic, location, and repeat arguments', 'generate_Destroy_action': 'generate a Destroy action object with an optional BlockObject to destroy', 'generate_Spawn_action': 'generate a Spawn action object that spawns a Mob with optional repeat arguments', 'generate_Noop_action': 'generate a Noop action object for non-action chat messages like greetings'}
```

