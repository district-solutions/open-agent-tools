# Agent Python Tools

- repo: facebookresearch/cruxeval
- repo_uri: https://github.com/facebookresearch/cruxeval

## File: facebookresearch_cruxeval/prompts.py

Prompts

```
['generate a direct output prompt that asks an LLM to complete an assertion with the function output for a given Python code and input', 'generate a chain-of-thought output prompt that asks an LLM to trace execution step by step before completing an assertion for given Python code and input', 'generate a direct input prompt that asks an LLM to find an input that produces a given output for a Python function', 'generate a chain-of-thought input prompt that asks an LLM to reason step by step to find an input producing a given output for a Python function', 'generate a Phind-style direct output prompt that asks an LLM to complete an assert statement with the function output without extra information']
```

Usage

```
{'make_direct_output_prompt': 'generate a direct output prompt that asks an LLM to complete an assertion with the function output for a given Python code and input', 'make_cot_output_prompt': 'generate a chain-of-thought output prompt that asks an LLM to trace execution step by step before completing an assertion for given Python code and input', 'make_direct_input_prompt': 'generate a direct input prompt that asks an LLM to find an input that produces a given output for a Python function', 'make_cot_input_prompt': 'generate a chain-of-thought input prompt that asks an LLM to reason step by step to find an input producing a given output for a Python function', 'make_direct_output_prompt_phind': 'generate a Phind-style direct output prompt that asks an LLM to complete an assert statement with the function output without extra information'}
```

