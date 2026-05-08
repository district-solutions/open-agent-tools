# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/ifeval/utils.py

Prompts

```
['test if an LLM response strictly follows all given instructions using the ifeval instruction registry', 'test if an LLM response loosely follows instructions by checking multiple response variations', 'process LLM evaluation results by running both strict and loose instruction following checks', 'aggregate instruction level accuracy scores across multiple evaluation examples', 'create an InputExample dataclass with instruction IDs, prompt, and kwargs for ifeval evaluation']
```

Usage

```
{'test_instruction_following_strict': 'test if an LLM response strictly follows all given instructions using the ifeval instruction registry', 'test_instruction_following_loose': 'test if an LLM response loosely follows instructions by checking multiple response variations', 'process_results': 'process LLM evaluation results by running both strict and loose instruction following checks', 'agg_inst_level_acc': 'aggregate instruction level accuracy scores across multiple evaluation examples', 'create_InputExample': 'create an InputExample dataclass with instruction IDs, prompt, and kwargs for ifeval evaluation'}
```

