# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/math_hard/utils.py

Prompts

```
['normalize a math final answer string by removing units, LaTeX wrappers, and shorthand TeX', 'check if two normalized LaTeX math strings are symbolically equivalent using sympy', 'extract the last boxed or fboxed LaTeX expression from a model response string', "evaluate a model's math answer against a ground truth and return an exact match score", 'process a HuggingFace dataset by extracting problems, normalizing answers, and mapping document fields']
```

Usage

```
{'normalize_final_answer': 'normalize a math final answer string by removing units, LaTeX wrappers, and shorthand TeX', 'is_equiv': 'check if two normalized LaTeX math strings are symbolically equivalent using sympy', 'last_boxed_only_string': 'extract the last boxed or fboxed LaTeX expression from a model response string', 'process_results': "evaluate a model's math answer against a ground truth and return an exact match score", 'process_docs': 'process a HuggingFace dataset by extracting problems, normalizing answers, and mapping document fields'}
```

