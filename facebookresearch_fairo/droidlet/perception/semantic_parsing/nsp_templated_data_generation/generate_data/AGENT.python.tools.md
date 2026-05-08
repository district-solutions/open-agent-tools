# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_data/action_node.py

Prompts

```
['generate an ActionNode instance using the generate class method with template attributes', 'generate a natural language description from an ActionNode using generate_description', 'convert an ActionNode to a structured action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new dialogue types or filter layouts', 'generate a GetMemory action node from a template with filter arguments for semantic parsing', 'generate a PutMemory action node from a template with filter and upsert arguments for semantic parsing', 'generate a text description from a GetMemory action node using its template objects', 'generate a text description from a PutMemory action node using its template objects', 'review the GetMemory and PutMemory classes that extend ActionNode for dialogue action tree generation', 'generate a Move action node with location, stop condition, and repeat arguments from a template', 'generate a Build action node with schematic and optional location arguments from a template', 'generate a Destroy action node with a BlockObject target to destroy from a template', 'generate a Spawn action node that creates a Mob in the environment from a template', 'generate a Noop action node that returns random chat phrases for non-action messages', 'run the script to apply grammar updates to an annotated templated dataset file', 'run traverse_tree on an action dictionary to recursively update nested action sequences', 'run traverse_subtree on an action dict to extract text_span values and convert has_ keys to triples', 'run read_file to load a dataset text file and return its lines as a list', 'run write_file to write a list of dataset lines to an output file']
```

Usage

```
{'generate_action_node': 'generate an ActionNode instance using the generate class method with template attributes', 'generate_action_description': 'generate a natural language description from an ActionNode using generate_description', 'convert_action_to_dict': 'convert an ActionNode to a structured action dictionary using to_dict', 'review_action_node_class': 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor_action_node_to_dict': 'refactor the ActionNode to_dict method to handle new dialogue types or filter layouts'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_data/human_bot_dialogue.py

Prompts

```
['generate an ActionNode instance using the generate class method with template attributes', 'generate a natural language description from an ActionNode using generate_description', 'convert an ActionNode to a structured action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new dialogue types or filter layouts', 'generate a GetMemory action node from a template with filter arguments for semantic parsing', 'generate a PutMemory action node from a template with filter and upsert arguments for semantic parsing', 'generate a text description from a GetMemory action node using its template objects', 'generate a text description from a PutMemory action node using its template objects', 'review the GetMemory and PutMemory classes that extend ActionNode for dialogue action tree generation', 'generate a Move action node with location, stop condition, and repeat arguments from a template', 'generate a Build action node with schematic and optional location arguments from a template', 'generate a Destroy action node with a BlockObject target to destroy from a template', 'generate a Spawn action node that creates a Mob in the environment from a template', 'generate a Noop action node that returns random chat phrases for non-action messages', 'run the script to apply grammar updates to an annotated templated dataset file', 'run traverse_tree on an action dictionary to recursively update nested action sequences', 'run traverse_subtree on an action dict to extract text_span values and convert has_ keys to triples', 'run read_file to load a dataset text file and return its lines as a list', 'run write_file to write a list of dataset lines to an output file']
```

Usage

```
{'generate_get_memory_action': 'generate a GetMemory action node from a template with filter arguments for semantic parsing', 'generate_put_memory_action': 'generate a PutMemory action node from a template with filter and upsert arguments for semantic parsing', 'generate_description_get_memory': 'generate a text description from a GetMemory action node using its template objects', 'generate_description_put_memory': 'generate a text description from a PutMemory action node using its template objects', 'review_action_node_classes': 'review the GetMemory and PutMemory classes that extend ActionNode for dialogue action tree generation'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_data/human_human_dialogue.py

Prompts

```
['generate an ActionNode instance using the generate class method with template attributes', 'generate a natural language description from an ActionNode using generate_description', 'convert an ActionNode to a structured action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new dialogue types or filter layouts', 'generate a GetMemory action node from a template with filter arguments for semantic parsing', 'generate a PutMemory action node from a template with filter and upsert arguments for semantic parsing', 'generate a text description from a GetMemory action node using its template objects', 'generate a text description from a PutMemory action node using its template objects', 'review the GetMemory and PutMemory classes that extend ActionNode for dialogue action tree generation', 'generate a Move action node with location, stop condition, and repeat arguments from a template', 'generate a Build action node with schematic and optional location arguments from a template', 'generate a Destroy action node with a BlockObject target to destroy from a template', 'generate a Spawn action node that creates a Mob in the environment from a template', 'generate a Noop action node that returns random chat phrases for non-action messages', 'run the script to apply grammar updates to an annotated templated dataset file', 'run traverse_tree on an action dictionary to recursively update nested action sequences', 'run traverse_subtree on an action dict to extract text_span values and convert has_ keys to triples', 'run read_file to load a dataset text file and return its lines as a list', 'run write_file to write a list of dataset lines to an output file']
```

Usage

```
{'generate_Move_action': 'generate a Move action node with location, stop condition, and repeat arguments from a template', 'generate_Build_action': 'generate a Build action node with schematic and optional location arguments from a template', 'generate_Destroy_action': 'generate a Destroy action node with a BlockObject target to destroy from a template', 'generate_Spawn_action': 'generate a Spawn action node that creates a Mob in the environment from a template', 'generate_Noop_action': 'generate a Noop action node that returns random chat phrases for non-action messages'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_data/update_annotated_data.py

Prompts

```
['generate an ActionNode instance using the generate class method with template attributes', 'generate a natural language description from an ActionNode using generate_description', 'convert an ActionNode to a structured action dictionary using to_dict', 'review the ActionNode class and its ARG_TYPES and CHOICES class attributes', 'refactor the ActionNode to_dict method to handle new dialogue types or filter layouts', 'generate a GetMemory action node from a template with filter arguments for semantic parsing', 'generate a PutMemory action node from a template with filter and upsert arguments for semantic parsing', 'generate a text description from a GetMemory action node using its template objects', 'generate a text description from a PutMemory action node using its template objects', 'review the GetMemory and PutMemory classes that extend ActionNode for dialogue action tree generation', 'generate a Move action node with location, stop condition, and repeat arguments from a template', 'generate a Build action node with schematic and optional location arguments from a template', 'generate a Destroy action node with a BlockObject target to destroy from a template', 'generate a Spawn action node that creates a Mob in the environment from a template', 'generate a Noop action node that returns random chat phrases for non-action messages', 'run the script to apply grammar updates to an annotated templated dataset file', 'run traverse_tree on an action dictionary to recursively update nested action sequences', 'run traverse_subtree on an action dict to extract text_span values and convert has_ keys to triples', 'run read_file to load a dataset text file and return its lines as a list', 'run write_file to write a list of dataset lines to an output file']
```

Usage

```
{'run_update_annotated_data': 'run the script to apply grammar updates to an annotated templated dataset file', 'run_traverse_tree': 'run traverse_tree on an action dictionary to recursively update nested action sequences', 'run_traverse_subtree': 'run traverse_subtree on an action dict to extract text_span values and convert has_ keys to triples', 'run_read_file': 'run read_file to load a dataset text file and return its lines as a list', 'run_write_file': 'run write_file to write a list of dataset lines to an output file'}
```

