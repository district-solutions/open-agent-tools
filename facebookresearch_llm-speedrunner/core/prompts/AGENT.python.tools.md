# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/core/prompts/coder_prompts.py

Prompts

```
['generate a code improvement prompt using basic_code_prompt with task description, file names, and ideas', 'generate a zero knowledge code prompt using basic_code_prompt with no ideas or knowledge provided', 'customize a code prompt with available packages using the PACKAGE_INFO_COMPONENT template', 'customize a code prompt with bug history using the CHILD_BUG_INFO_COMPONENT template', 'customize a code prompt with domain knowledge using the KNOWLEDGE_INFO_COMPONENT template', 'generate an ideation prompt for improving code with a task description and summary', 'generate a debug ideation prompt to hypothesize fixes for buggy code', 'generate an ideation prompt that includes previous change history and outcomes', 'generate an ideation prompt that incorporates relevant domain knowledge', 'generate an ideation prompt that excludes previously proposed ideas']
```

Usage

```
{'generate_basic_code_prompt': 'generate a code improvement prompt using basic_code_prompt with task description, file names, and ideas', 'generate_zero_knowledge_prompt': 'generate a zero knowledge code prompt using basic_code_prompt with no ideas or knowledge provided', 'customize_prompt_with_packages': 'customize a code prompt with available packages using the PACKAGE_INFO_COMPONENT template', 'customize_prompt_with_bug_history': 'customize a code prompt with bug history using the CHILD_BUG_INFO_COMPONENT template', 'customize_prompt_with_knowledge': 'customize a code prompt with domain knowledge using the KNOWLEDGE_INFO_COMPONENT template'}
```

## File: facebookresearch_llm-speedrunner/core/prompts/ideator_prompts.py

Prompts

```
['generate a code improvement prompt using basic_code_prompt with task description, file names, and ideas', 'generate a zero knowledge code prompt using basic_code_prompt with no ideas or knowledge provided', 'customize a code prompt with available packages using the PACKAGE_INFO_COMPONENT template', 'customize a code prompt with bug history using the CHILD_BUG_INFO_COMPONENT template', 'customize a code prompt with domain knowledge using the KNOWLEDGE_INFO_COMPONENT template', 'generate an ideation prompt for improving code with a task description and summary', 'generate a debug ideation prompt to hypothesize fixes for buggy code', 'generate an ideation prompt that includes previous change history and outcomes', 'generate an ideation prompt that incorporates relevant domain knowledge', 'generate an ideation prompt that excludes previously proposed ideas']
```

Usage

```
{'generate_ideation_prompt': 'generate an ideation prompt for improving code with a task description and summary', 'generate_debug_ideation_prompt': 'generate a debug ideation prompt to hypothesize fixes for buggy code', 'generate_ideation_prompt_with_history': 'generate an ideation prompt that includes previous change history and outcomes', 'generate_ideation_prompt_with_knowledge': 'generate an ideation prompt that incorporates relevant domain knowledge', 'generate_ideation_prompt_ignoring_ideas': 'generate an ideation prompt that excludes previously proposed ideas'}
```

