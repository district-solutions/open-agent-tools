# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/data-reallife-eval/Babilong/prompts.py

Prompts

```
['build a prompt input string by calling get_formatted_input with context, question, examples, instruction, and post_prompt arguments', 'use the DEFAULT_PROMPTS dictionary to get instruction, examples, and post_prompt for any qa1 through qa20 task', 'use the DEFAULT_PROMPTS_ZEYUAN dictionary to get modified prompts optimized for smaller pretrained models on qa1 through qa5 tasks', 'customize prompt formatting by passing DEFAULT_TEMPLATE_ZEYUAN as the template argument to get_formatted_input for qa1 through qa5', 'use the CUSTOM_SYSTEM_PROMPTS dictionary to retrieve the LONGLORA_LLAMA2 system prompt for safe and helpful model responses']
```

Usage

```
{'build_formatted_qa_input': 'build a prompt input string by calling get_formatted_input with context, question, examples, instruction, and post_prompt arguments', 'use_default_prompts_for_qa_tasks': 'use the DEFAULT_PROMPTS dictionary to get instruction, examples, and post_prompt for any qa1 through qa20 task', 'use_zeyuan_prompts_for_qa1_to_qa5': 'use the DEFAULT_PROMPTS_ZEYUAN dictionary to get modified prompts optimized for smaller pretrained models on qa1 through qa5 tasks', 'customize_template_with_zeyuan_variant': 'customize prompt formatting by passing DEFAULT_TEMPLATE_ZEYUAN as the template argument to get_formatted_input for qa1 through qa5', 'use_custom_system_prompt_for_longlora': 'use the CUSTOM_SYSTEM_PROMPTS dictionary to retrieve the LONGLORA_LLAMA2 system prompt for safe and helpful model responses'}
```

