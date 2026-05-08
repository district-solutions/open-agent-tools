# Agent Python Tools

- repo: facebookresearch/clevr-dataset-gen
- repo_uri: https://github.com/facebookresearch/clevr-dataset-gen

## File: facebookresearch_clevr-dataset-gen/question_generation/generate_questions.py

Prompts

```
['run generate_questions.py to create synthetic CLEVR questions and answers from scene JSON files', 'instantiate question templates using depth-first search to generate valid CLEVR questions with answers', 'precompute filter options mapping object attributes to indices for a CLEVR scene structure', 'find spatial relationship filter options between objects in a CLEVR scene for question generation', 'replace optional bracketed text segments in question templates with 50 percent probability of removal', 'answer a structured question by executing its function program nodes against a scene structure', 'check if a question is degenerate by testing if replacing relate nodes yields the same answer', 'replace a specified node in a question program with a scene node and trim unused nodes', 'create a filter handler function that filters scene objects by a given attribute value', 'create a query handler function that retrieves a specific attribute value from a scene object']
```

Usage

```
{'run_generate_questions': 'run generate_questions.py to create synthetic CLEVR questions and answers from scene JSON files', 'instantiate_templates_dfs': 'instantiate question templates using depth-first search to generate valid CLEVR questions with answers', 'precompute_filter_options': 'precompute filter options mapping object attributes to indices for a CLEVR scene structure', 'find_relate_filter_options': 'find spatial relationship filter options between objects in a CLEVR scene for question generation', 'replace_optionals': 'replace optional bracketed text segments in question templates with 50 percent probability of removal'}
```

## File: facebookresearch_clevr-dataset-gen/question_generation/question_engine.py

Prompts

```
['run generate_questions.py to create synthetic CLEVR questions and answers from scene JSON files', 'instantiate question templates using depth-first search to generate valid CLEVR questions with answers', 'precompute filter options mapping object attributes to indices for a CLEVR scene structure', 'find spatial relationship filter options between objects in a CLEVR scene for question generation', 'replace optional bracketed text segments in question templates with 50 percent probability of removal', 'answer a structured question by executing its function program nodes against a scene structure', 'check if a question is degenerate by testing if replacing relate nodes yields the same answer', 'replace a specified node in a question program with a scene node and trim unused nodes', 'create a filter handler function that filters scene objects by a given attribute value', 'create a query handler function that retrieves a specific attribute value from a scene object']
```

Usage

```
{'answer_question': 'answer a structured question by executing its function program nodes against a scene structure', 'is_degenerate': 'check if a question is degenerate by testing if replacing relate nodes yields the same answer', 'insert_scene_node': 'replace a specified node in a question program with a scene node and trim unused nodes', 'make_filter_handler': 'create a filter handler function that filters scene objects by a given attribute value', 'make_query_handler': 'create a query handler function that retrieves a specific attribute value from a scene object'}
```

