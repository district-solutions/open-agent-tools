# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/recipe/recipe.py

Prompts

```
['create a Recipe instance from a YAML or JSON recipe file path', 'create a Recipe instance from a YAML or JSON recipe string with a target stage', 'create a Recipe instance from a list of Modifier objects with a group name', 'create a Recipe instance from a dictionary containing stage and modifier definitions', 'generate a YAML string representation of a Recipe, optionally merging with an existing recipe file', 'parse a markdown recipe card and extract YAML front matter from a file', 'convert a list of llmcompressor modifiers into a YAML-serializable dictionary grouped by stage', 'filter a recipe dictionary to only include keys matching a target stage name', 'merge two recipe dictionaries by renaming conflicting stage keys with numeric suffixes', 'parse a JSON or YAML string into a dictionary for llmcompressor recipe content']
```

Usage

```
{'create_recipe_from_file': 'create a Recipe instance from a YAML or JSON recipe file path', 'create_recipe_from_string': 'create a Recipe instance from a YAML or JSON recipe string with a target stage', 'create_recipe_from_modifiers': 'create a Recipe instance from a list of Modifier objects with a group name', 'create_recipe_from_dict': 'create a Recipe instance from a dictionary containing stage and modifier definitions', 'generate_recipe_yaml': 'generate a YAML string representation of a Recipe, optionally merging with an existing recipe file'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/recipe/utils.py

Prompts

```
['create a Recipe instance from a YAML or JSON recipe file path', 'create a Recipe instance from a YAML or JSON recipe string with a target stage', 'create a Recipe instance from a list of Modifier objects with a group name', 'create a Recipe instance from a dictionary containing stage and modifier definitions', 'generate a YAML string representation of a Recipe, optionally merging with an existing recipe file', 'parse a markdown recipe card and extract YAML front matter from a file', 'convert a list of llmcompressor modifiers into a YAML-serializable dictionary grouped by stage', 'filter a recipe dictionary to only include keys matching a target stage name', 'merge two recipe dictionaries by renaming conflicting stage keys with numeric suffixes', 'parse a JSON or YAML string into a dictionary for llmcompressor recipe content']
```

Usage

```
{'parse_recipe_from_md': 'parse a markdown recipe card and extract YAML front matter from a file', 'get_yaml_serializable_dict': 'convert a list of llmcompressor modifiers into a YAML-serializable dictionary grouped by stage', 'filter_dict': 'filter a recipe dictionary to only include keys matching a target stage name', 'append_recipe_dict': 'merge two recipe dictionaries by renaming conflicting stage keys with numeric suffixes', 'load_json_or_yaml_string': 'parse a JSON or YAML string into a dictionary for llmcompressor recipe content'}
```

