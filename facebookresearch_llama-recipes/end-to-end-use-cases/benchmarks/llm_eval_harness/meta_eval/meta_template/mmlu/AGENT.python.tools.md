# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/mmlu/utils.py

Prompts

```
['process a HuggingFace dataset for MMLU pretrain evaluation by extracting problems and numeric gold answers', 'process a HuggingFace dataset for MMLU instruct evaluation by extracting problems and text gold answers', 'extract the input prompt text from a doc dict with the answer character stripped off', 'extract the full input prompt text from a doc dict including the answer portion', 'extract the gold answer value from a processed MMLU doc dict']
```

Usage

```
{'process_docs_pretrain': 'process a HuggingFace dataset for MMLU pretrain evaluation by extracting problems and numeric gold answers', 'process_docs_instruct': 'process a HuggingFace dataset for MMLU instruct evaluation by extracting problems and text gold answers', 'doc_to_text_pretrain': 'extract the input prompt text from a doc dict with the answer character stripped off', 'doc_to_text_instruct': 'extract the full input prompt text from a doc dict including the answer portion', 'doc_to_target': 'extract the gold answer value from a processed MMLU doc dict'}
```

