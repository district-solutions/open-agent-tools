# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/templates/templates.py

Prompts

```
['pick a random natural language template for a given action type like Move or Build', 'get a template filtered by dialogue length or no inbuilt composites constraints', 'get a template instantiated with a parse tree node and template attributes', 'review the template_map dictionary that maps action types to their template lists', 'summarize how get_template selects and instantiates templates from the template_map']
```

Usage

```
{'get_template_for_action': 'pick a random natural language template for a given action type like Move or Build', 'get_template_with_constraints': 'get a template filtered by dialogue length or no inbuilt composites constraints', 'get_template_with_node': 'get a template instantiated with a parse tree node and template attributes', 'review_template_map': 'review the template_map dictionary that maps action types to their template lists', 'summarize_template_selection': 'summarize how get_template selects and instantiates templates from the template_map'}
```

